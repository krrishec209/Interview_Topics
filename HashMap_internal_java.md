𝗧𝗿𝗶𝗰𝗸𝘆 𝗜𝗻𝘁𝗲𝗿𝘃𝗶𝗲𝘄 𝗤𝘂𝗲𝘀𝘁𝗶𝗼𝗻 - 𝗛𝗼𝘄 𝗱𝗼𝗲𝘀 𝗛𝗮𝘀𝗵𝗠𝗮𝗽 𝘄𝗼𝗿𝗸 𝗶𝗻𝘁𝗲𝗿𝗻𝗮𝗹𝗹𝘆 𝗶𝗻 𝗝𝗮𝘃𝗮?

What happens? When do you put a key-value pair in a HashMap? 

- Computes the hash of the key using hashCode().
- Maps it to an index in an array of buckets.
- Stores the entry - if a collision occurs, it uses a linked list (or tree in case of high collisions).
- Retrieves values in O(1) average time, but O(n) worst-case if many collisions occur.

𝗞𝗲𝘆 𝗼𝗽𝘁𝗶𝗺𝗶𝘇𝗮𝘁𝗶𝗼𝗻𝘀?
- Treeify: Converts linked lists to Red-Black Trees for better performance.
- Rehashing: Expands capacity when load factor (default 0.75) is exceeded.

- PDF book view on linked in post

Follow Suresh Bishnoi for more such insight.

https://www.linkedin.com/posts/bishnoisuresh_core-java-hashmap-activity-7295778685129789441-UNTT?utm_source=share&utm_medium=member_desktop&rcm=ACoAAARSzbgBGEbWHnTkxyPnkFaeZcnK-pW0lqg
