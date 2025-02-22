🚀 Interview question: Mapping a Table Without a Primary Key in JPA

🔍 Question:
I have a table with the following columns: employee name, salary, and department. However, the table doesn't have any primary key or constraints. How can I map this table to a JPA Entity class and a JPA repository?


---

💡 Answer:

In JPA, every entity needs a primary key. If your table doesn't have one, here are a few approaches to resolve this issue:

1. Use a Composite Key with @IdClass

If a combination of columns can serve as a unique identifier (e.g., a combination of employee name and department), you can use a composite key with the @IdClass annotation.

Example:

import java.io.Serializable;
import javax.persistence.*;

public class EmployeeId implements Serializable {
 private String name;
 private String department;
}

@Entity
@IdClass(EmployeeId.class)
public class Employee {
 @Id
 private String name;
 @Id
 private String department;
 private double salary;
}


---

2. Use an Artificial Key with @GeneratedValue

If you can modify the schema, add an artificial primary key (e.g., an auto-increment ID or UUID) to the table and map it with @GeneratedValue.

Example:

@Entity
public class Employee {
 @Id
 @GeneratedValue(strategy = GenerationType.IDENTITY)
 private Long id; // Auto-generated primary key

 private String name;
 private double salary;
 private String department;
}


---

3. Read-Only Entity

If the table is read-only and doesn't need to be modified, you can create a read-only entity with the @Immutable annotation and map it to your JPA entity class.

Example:

@Entity
@Immutable
public class Employee {
 @Id
 private String name; // Artificial identifier

 private double salary;
 private String department;
}


---

4. JPA Repository

Once you map the table to the entity, you can use the JPA Repository for basic CRUD operations.


public interface EmployeeRepository extends JpaRepository<Employee, EmployeeId> {
 // Custom queries can go here
}


---

🎯 Conclusion:

For composite keys: Use @IdClass.

For artificial keys: Add an auto-generated field.

For read-only tables: Use @Immutable.


https://www.linkedin.com/posts/ravindra-v-s-223993228_jpa-java-springboot-activity-7297298692967972866-fcU2?utm_source=share&utm_medium=member_desktop&rcm=ACoAAARSzbgBGEbWHnTkxyPnkFaeZcnK-pW0lqg
