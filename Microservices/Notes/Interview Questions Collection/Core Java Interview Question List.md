
Priority guide
P1
Must prepare first
Collections, Java 8 Streams, Multithreading, JVM, Strings, equals/hashCode, Exception Handling.

P2
Senior-level depth
Concurrency utilities, Garbage Collection, ClassLoaders, Generics, Design Principles, Performance.

 P3 
Additional preparation
Advanced language features, tricky output questions, coding problems, Java 17/21+ features.

1. OOP Concepts and Java Fundamentals
1. What are the four pillars of Object-Oriented Programming?
2. What is the difference between abstraction and encapsulation?
3. What is the difference between an abstract class and an interface?
4. What is the difference between method overloading and method overriding?
5. Does Java support multiple inheritance?
6. Why does Java not support multiple inheritance through classes?
7. What is the difference between compile-time and runtime polymorphism?
8. What is the difference between this and super?
9. What is the difference between final, finally, and finalize()?
10. Can a constructor be private?
11. Can a constructor be overridden or inherited?
12. What happens if a constructor throws an exception?
13. What is the difference between static and instance members?
14. Can a static method be overridden?
15. What is method hiding in Java?
16. What is the difference between composition and inheritance?
17. What is the difference between association, aggregation, and composition?
18. What is an immutable class, and how do you create one?
19. How would you design a thread-safe immutable class?
20. What is the difference between a shallow copy and a deep copy?
2. String, StringBuilder and StringBuffer
21. Why is String immutable in Java?
22. What is the String Constant Pool?
23. What is the difference between == and equals() for Strings?
24. What is the difference between String, StringBuilder, and StringBuffer?
25. What does the intern() method do?
26. What is the output of String s = new String("Java")? How many objects may be created?
27. What happens when you concatenate Strings using the + operator?
28. How does String concatenation inside a loop affect performance?
29. Can you create your own immutable class containing a mutable object?
30. Why is String commonly used for keys in a HashMap?
31. How do you reverse a String without using built-in reverse methods?
32. How do you check whether a String is a palindrome?
33. How do you find duplicate characters in a String?
34. How do you find the first non-repeated character?
35. How do you check whether two Strings are anagrams?

3. Collections Framework — Very Important
36. Explain the Java Collections Framework hierarchy.
37. What is the difference between Collection and Collections?
38. What is the difference between List, Set, and Map?
39. What is the difference between ArrayList and LinkedList?
40. How does ArrayList grow internally?
41. How does HashMap work internally in Java 8 and later?
42. How does HashSet work internally?
43. What happens when two keys have the same hash code?
44. What happens if two unequal keys have the same hash code?
45. Why should equals() and hashCode() be overridden together?
46. What happens if a mutable object is used as a HashMap key?
47. What is the difference between HashMap, Hashtable, and ConcurrentHashMap?
48. How does ConcurrentHashMap achieve thread safety?
49. What is the difference between HashMap and LinkedHashMap?
50. What is the difference between HashMap and TreeMap?
51. How does TreeMap maintain sorted order?
52. What is the difference between HashSet, LinkedHashSet, and TreeSet?
53. What is the difference between Comparable and Comparator?
54. What are fail-fast and fail-safe iterators?
55. What is the difference between Iterator and ListIterator?
56. What is ConcurrentModificationException, and how can it occur?
57. What is the difference between ArrayList and CopyOnWriteArrayList?
58. What is the difference between PriorityQueue and TreeSet?
59. What is the time complexity of common HashMap operations?
60. How would you choose a collection for a high-performance application?

4. Java 8 Features and Streams API
61. What are the major features introduced in Java 8?
62. What is a functional interface?
63. What is the purpose of the @FunctionalInterface annotation?
64. What is a lambda expression?
65. What is the difference between a lambda expression and an anonymous inner class?
66. What are method references?
67. What is the Stream API?
68. What is the difference between a Collection and a Stream?
69. What is the difference between intermediate and terminal operations?
70. What is the difference between map() and flatMap()?
71. What is the difference between filter() and map()?
72. What is the difference between findFirst() and findAny()?
73. What is the difference between orElse() and orElseGet() in Optional?
74. How do you handle null values using Optional?
75. What is the difference between reduce() and collect()?
76. What is the difference between groupingBy() and partitioningBy()?
77. How do you find duplicate elements in a list using Streams?
78. How do you find the second-highest salary using Streams?
79. How do you group employees by department?
80. How do you convert a list into a Map using Streams?
81. How do you handle duplicate keys in Collectors.toMap()?
82. What is a parallel stream?
83. When should you avoid parallel streams?
84. Why should you avoid modifying shared mutable state inside a stream?
85. How do you optimize a complex Stream pipeline?

5. Exception Handling
86. What is the difference between checked and unchecked exceptions?
87. What is the difference between Exception and Error?
88. What is the difference between throw and throws?
89. Can a try block exist without a catch block?
90. Can multiple catch blocks be used?
91. What happens if both try and finally contain a return statement?
92. What is try-with-resources?
93. What is the AutoCloseable interface?
94. How do you create a custom checked exception?
95. How do you create a custom unchecked exception?
96. What is exception propagation?
97. What is the difference between final, finally, and finalize() in exception-related discussions?
98. What are suppressed exceptions?
99. What are best practices for exception handling in enterprise applications?
100. Why should exceptions not be swallowed or used for normal control flow?

6. Multithreading and Concurrency — Critical for Senior Roles
101. What is the difference between a process and a thread?
102. What are the different states in a Java thread lifecycle?
103. What is the difference between start() and run()?
104. What is the difference between sleep() and wait()?
105. What is the difference between wait(), notify(), and notifyAll()?
106. What is synchronization in Java?
107. What is the difference between a synchronized method and a synchronized block?
108. What is an intrinsic lock or monitor?
109. What is the volatile keyword?
110. What is the difference between volatile and synchronized?
111. What is a race condition?
112. What is a deadlock, and how can you prevent it?
113. What are livelock and starvation?
114. What is the difference between Runnable and Callable?
115. What is the ExecutorService framework?
116. What is the difference between execute() and submit()?
117. What is a thread pool, and why is it used?
118. How do you choose an appropriate thread pool size?
119. What is the difference between Future and CompletableFuture?
120. What is CountDownLatch?
121. What is CyclicBarrier?
122. What is Semaphore?
123. What is ReentrantLock, and how does it differ from synchronized?
124. What are atomic classes such as AtomicInteger?
125. What is the Java Memory Model?
126. What is the happens-before relationship?
127. What is a concurrent collection?
128. How do you make a shared counter thread-safe?
129. How do you implement producer-consumer using BlockingQueue?
130. How would you investigate a production thread dump showing many blocked threads?

7. JVM Internals and Memory Management
131. Explain the major components of JVM architecture.
132. What is the difference between JDK, JRE, and JVM?
133. Explain heap memory and stack memory.
134. What is Metaspace?
135. What is the difference between a memory leak and an OutOfMemoryError?
136. How does Garbage Collection work in Java?
137. What are minor, major, and full GC events?
138. What is the difference between G1 GC and other collectors such as ZGC?
139. What are strong, soft, weak, and phantom references?
140. What makes an object eligible for garbage collection?
141. Can you force Garbage Collection?
142. What is a classloader?
143. Explain parent delegation in class loading.
144. What is the difference between ClassNotFoundException and NoClassDefFoundError?
145. What is a memory dump, and how do you analyze it?
146. What is a thread dump, and when would you capture one?
147. What is JIT compilation?
148. What is escape analysis?
149. How do you investigate frequent GC pauses?
150. How would you troubleshoot OutOfMemoryError: Java heap space in production?

8. Generics, Reflection, Annotations and Serialization
151. What are Generics in Java?
152. What are bounded type parameters?
153. Explain ? extends T and ? super T.
154. What is type erasure?
155. Why can't you directly create a generic array such as new T[]?
156. What is reflection in Java?
157. What are the disadvantages of reflection?
158. What are annotations, and how do you create a custom annotation?
159. What is the difference between runtime and compile-time annotations?
160. What is serialization?
161. What is the purpose of serialVersionUID?
162. What is the transient keyword?
163. Why is native Java serialization often avoided in modern service APIs?
164. What is the difference between JSON serialization and Java object serialization?
165. How do you handle serialization compatibility between application versions?

9. Java 11, 17, 21 and Modern Java Features
166. What are the important features introduced in Java 11?
167. What are the important features introduced in Java 17?
168. What are records, and when would you use them?
169. What are sealed classes?
170. What are text blocks?
171. What is pattern matching for instanceof?
172. What are switch expressions?
173. What is pattern matching for switch in modern Java?
174. What are virtual threads introduced in Java 21?
175. How do virtual threads differ from platform threads?
176. When should you use virtual threads in a Spring Boot application?
177. What is structured concurrency, and how does its status depend on the Java version?
178. What is the Foreign Function and Memory API?
179. What is the difference between a record and a traditional POJO?
180. How would you plan a Java 8 to Java 21 migration?


10. Coding Questions for 10 Years of Experience
181. Find the second-highest number in an array.
182. Find duplicate elements in a list.
183. Find the first non-repeated character in a String.
184. Reverse a String without using built-in reverse methods.
185. Check whether two Strings are anagrams.
186. Find the frequency of each character in a String.
187. Find the frequency of each element in a list.
188. Find the highest-paid employee in each department.
189. Sort employees by salary and then by name.
190. Group employees by department using Streams.
191. Find the second-highest salary using Streams.
192. Find the top three highest salaries.
193. Convert a list of employees into a Map keyed by employee ID.
194. Handle duplicate employee IDs while collecting into a Map.
195. Partition numbers into even and odd groups.
196. Flatten a list of lists using flatMap().
197. Find common elements between two lists.
198. Merge two sorted arrays.
199. Implement a thread-safe Singleton.
200. Implement an LRU cache using Java collections.

11. Tricky Output-Based Questions
201. What is the output when a static variable is modified through an object?
202. What happens when an overridden method is called from a constructor?
203. Which method is called when an overloaded method receives a null argument?
204. What happens when equals() is overridden but hashCode() is not?
205. What happens if you modify a HashMap key after inserting it?
206. What is the output of String comparisons using ==, equals(), and intern()?
207. What happens if a subclass reduces the visibility of an overridden method?
208. Can a finally block fail to execute?
209. What happens when a lambda captures a local variable?
210. What happens when two threads increment a non-volatile integer concurrently?
211. What is the output of Integer comparisons using ==?
212. What happens when a stream is operated on after a terminal operation?
213. Can a stream be reused?
214. What happens when parallelStream() modifies a shared ArrayList?
215. What happens when a CompletableFuture completes exceptionally?

12. Design Principles and Design Patterns
216. Explain the SOLID principles with Java examples.
217. What is the Single Responsibility Principle?
218. What is the Open/Closed Principle?
219. What is dependency inversion?
220. What is the difference between composition and inheritance in design?
221. What are the Factory and Abstract Factory patterns?
222. What is the Builder pattern?
223. What is the Strategy pattern?
224. What is the Observer pattern?
225. What is the Decorator pattern?
226. What is the Proxy pattern?
227. What is the Template Method pattern?
228. What is the Adapter pattern?
229. How do you implement Singleton safely in Java?
230. How do you choose an appropriate design pattern for a real requirement?

13. Production Scenarios and Performance Optimization
231. An application has high CPU usage. How do you investigate it?
232. An application experiences frequent Garbage Collection pauses. How do you diagnose the cause?
233. A HashMap is accessed concurrently by multiple threads. What problems can arise?
234. An API becomes slow under high traffic. How do you identify whether the issue is CPU, memory, database, or thread contention?
235. A thread pool queue grows continuously. What does it indicate?
236. How do you prevent thread pool exhaustion?
237. How do you avoid blocking operations inside asynchronous workflows?
238. When would you choose ConcurrentHashMap over Collections.synchronizedMap()?
239. How do you benchmark Java code reliably?
240. What are JMH and Java Flight Recorder?
241. How do you diagnose classloader leaks?
242. How do you prevent resource leaks involving files, sockets, and database connections?
243. How do you improve memory efficiency for large data processing?
244. How do you troubleshoot a deadlock in production?
245. How would you optimize a batch job processing millions of records?
14. Senior-Level Design and Leadership Questions
246. How do you review Java code written by junior developers?
247. How do you decide whether a performance optimization is worth the complexity?
248. How do you handle technical debt in a legacy Java application?
249. How would you migrate an older Java application to a supported LTS version with minimal downtime?
250. Describe a challenging production issue you resolved using your Core Java knowledge.

How you should prepare these questions
For your 10-year experience profile, I recommend this sequence:
Day	Focus area
Day 1	OOP, Strings, immutability, equals() and hashCode()
Day 2	Collections and internal implementation
Day 3	Java 8 Streams and coding problems
Day 4	Multithreading and concurrency
Day 5	JVM, memory management and Garbage Collection
Day 6	Exceptions, Generics, modern Java and design patterns
Day 7	Production scenarios and mock interview

My recommendation: Do not try to memorize all 250 questions. 
Prepare the top 50 deeply, practice coding daily, and explain your answers as if speaking to a senior interviewer.
We can also conduct a Core Java mock interview for a 10-year experienced candidate: I'll ask one question at a time, evaluate your answer, explain missing points, and move to the next question. This will help you practice both technical knowledge and interview communication.