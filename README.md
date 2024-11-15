# Java Interview Questions
Welcome to the Java Interview Questions Repository! This repository is a curated collection of Java questions categorized by difficulty: Easy, Medium, and Hard. Whether you are a beginner aiming to grasp the basics or an expert wanting to challenge yourself, this repository will help you improve your Java skills.

## Introduction

Java is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible. It is a versatile language used for building a range of applications from web to mobile to enterprise applications. This repository is designed to help you practice and master Java by solving a variety of questions ranging from easy to hard.

## Why Java?

- **Platform-Independent**: Java's "write once, run anywhere" capability makes it a widely-used language for cross-platform applications.
- **Robust and Secure**: Java provides strong memory management and built-in security features.
- **Object-Oriented**: Java's object-oriented nature makes it easy to manage and modify code.
- **Extensive Libraries**: Java has a rich set of APIs and libraries that simplify development.

## Question Categories

### Easy

These questions cover basic Java concepts, syntax, and simple programming tasks. Ideal for beginners.

### Medium

These questions delve into more complex topics such as data structures, algorithms, and object-oriented programming principles.

### Hard

These questions are designed for advanced users and cover topics like multithreading, concurrency, advanced data structures, and performance optimization.

## Contributing

We welcome contributions from the community! If you have a question or improvement that you think should be included, please follow these steps:

1. Fork the repository.
2. Create a new branch for your contribution.
3. Add your question or improvement in the appropriate category folder (`easy`, `medium`, `hard`).
4. Submit a pull request with a detailed description of your changes.

---

Happy coding! If you find this repository helpful, please give it a star ⭐ and share it with others.

---

### Table of Contents
### Level : Easy
| No. | Questions |
| --- | --------- |
| 1   | [What is Java?](#1-what-is-java) |
| 2   | [Explain JVM, JRE, and JDK.](#2-explain-jvm-jre-and-jdk) |
| 3   | [What are the main features of Java?](#3-what-are-the-main-features-of-java) |
| 4   | [What is the difference between JDK and JRE?](#4-what-is-the-difference-between-jdk-and-jre) |
| 5   | [Explain public static void main(String args[]).](#5-explain-public-static-void-mainstring-args) |
| 6   | [What is a constructor in Java?](#6-what-is-a-constructor-in-java) |
| 7   | [What are the types of constructors in Java?](#7-what-are-the-types-of-constructors-in-java) |
| 8   | [What is a default constructor?](#8-what-is-a-default-constructor) |
| 9   | [Explain method overloading.](#9-explain-method-overloading) |
| 10  | [What is method overriding?](#10-what-is-method-overriding) |
| 11  | [What is inheritance?](#11-what-is-inheritance) |
| 12  | [Explain polymorphism.](#12-explain-polymorphism) |
| 13  | [What is encapsulation?](#13-what-is-encapsulation) |
| 14  | [What is abstraction?](#14-what-is-abstraction) |
| 15  | [What are the access modifiers in Java?](#15-what-are-the-access-modifiers-in-java) |
| 16  | [Explain the use of 'this' keyword.](#16-explain-the-use-of-this-keyword) |
| 17  | [What is a static method?](#17-what-is-a-static-method) |
| 18  | [What is the difference between static and non-static methods?](#18-what-is-the-difference-between-static-and-non-static-methods) |
| 19  | [What is the final keyword in Java?](#19-what-is-the-final-keyword-in-java) |
| 20  | [What are the data types in Java?](#20-what-are-the-data-types-in-java) |
| 21  | [What is the difference between int and Integer?](#21-what-is-the-difference-between-int-and-integer) |
| 22  | [What are the control statements in Java?](#22-what-are-the-control-statements-in-java) |
| 23  | [Explain the use of break and continue.](#23-explain-the-use-of-break-and-continue) |
| 24  | [What is a loop in Java?](#24-what-is-a-loop-in-java) |
| 25  | [What are the types of loops in Java?](#25-what-are-the-types-of-loops-in-java) |
| 26  | [What is an array in Java?](#26-what-is-an-array-in-java) |
| 27  | [How do you declare an array in Java?](#27-how-do-you-declare-an-array-in-java) |
| 28  | [What is the default value of an array?](#28-what-is-the-default-value-of-an-array) |
| 29  | [Explain the concept of an array of objects.](#29-explain-the-concept-of-an-array-of-objects) |
| 30  | [What is a string in Java?](#30-what-is-a-string-in-java) |
| 31  | [How do you declare a string in Java?](#31-how-do-you-declare-a-string-in-java) |
| 32  | [What is the difference between String and StringBuffer?](#32-what-is-the-difference-between-string-and-stringbuffer) |
| 33  | [What is the difference between StringBuilder and StringBuffer?](#33-what-is-the-difference-between-stringbuilder-and-stringbuffer) |
| 34  | [What are the commonly used methods of String class?](#34-what-are-the-commonly-used-methods-of-string-class) |
| 35  | [How do you compare strings in Java?](#35-how-do-you-compare-strings-in-java) |
| 36  | [What is an exception in Java?](#36-what-is-an-exception-in-java) |
| 37  | [Explain the try-catch block.](#37-explain-the-try-catch-block) |
| 38  | [What is the difference between checked and unchecked exceptions?](#38-what-is-the-difference-between-checked-and-unchecked-exceptions) |
| 39  | [What is the use of the finally block?](#39-what-is-the-use-of-the-finally-block) |
| 40  | [What is the throw keyword?](#40-what-is-the-throw-keyword) |
| 41  | [What is the throws keyword?](#41-what-is-the-throws-keyword) |
| 42  | [Explain the concept of exception propagation.](#42-explain-the-concept-of-exception-propagation) |
| 43  | [What are the types of exceptions in Java?](#43-what-are-the-types-of-exceptions-in-java) |
| 44  | [What is a custom exception?](#44-what-is-a-custom-exception) |
| 45  | [What is the use of the synchronized keyword?](#45-what-is-the-use-of-the-synchronized-keyword) |
| 46  | [What is multithreading?](#46-what-is-multithreading) |
| 47  | [What is the difference between a thread and a process?](#47-what-is-the-difference-between-a-thread-and-a-process) |
| 48  | [How do you create a thread in Java?](#48-how-do-you-create-a-thread-in-java) |
| 49  | [What is the Runnable interface?](#49-what-is-the-runnable-interface) |
| 50  | [What is the Thread class?](#50-what-is-the-thread-class) |
| 51  | [What are the states of a thread in Java?](#51-what-are-the-states-of-a-thread-in-java) |
| 52  | [What is thread priority?](#52-what-is-thread-priority) |
| 53  | [What is the difference between wait() and sleep()?](#53-what-is-the-difference-between-wait-and-sleep) |
| 54  | [What is the use of the join() method?](#54-what-is-the-use-of-the-join-method) |
| 55  | [What is the difference between notify() and notifyAll()?](#55-what-is-the-difference-between-notify-and-notifyall) |
| 56  | [What is the difference between a class and an object?](#56-what-is-the-difference-between-a-class-and-an-object) |
| 57  | [What is the use of the new keyword?](#57-what-is-the-use-of-the-new-keyword) |
| 58  | [What is the difference between an abstract class and an interface?](#58-what-is-the-difference-between-an-abstract-class-and-an-interface) |
| 59  | [What is a package in Java?](#59-what-is-a-package-in-java) |
| 60  | [What is the use of the import statement?](#60-what-is-the-use-of-the-import-statement) |
| 61  | [What is the difference between import and static import?](#61-what-is-the-difference-between-import-and-static-import) |
| 62  | [What is the use of the super keyword?](#62-what-is-the-use-of-the-super-keyword) |
| 63  | [What is the difference between an interface and a class?](#63-what-is-the-difference-between-an-interface-and-a-class) |
| 64  | [What is the use of the instanceof keyword?](#64-what-is-the-use-of-the-instanceof-keyword) |
| 65  | [What is a nested class?](#65-what-is-a-nested-class) |
| 66  | [What is an inner class?](#66-what-is-an-inner-class) |
| 67  | [What is a local inner class?](#67-what-is-a-local-inner-class) |
| 68  | [What is an anonymous inner class?](#68-what-is-an-anonymous-inner-class) |
| 69  | [What is a static nested class?](#69-what-is-a-static-nested-class) |
| 70  | [What is the use of the transient keyword?](#70-what-is-the-use-of-the-transient-keyword) |
| 71  | [What is the use of the volatile keyword?](#71-what-is-the-use-of-the-volatile-keyword) |
| 72  | [What is serialization?](#72-what-is-serialization) |
| 73  | [What is deserialization?](#73-what-is-deserialization) |
| 74  | [What is the use of the Serializable interface?](#74-what-is-the-use-of-the-serializable-interface) |
| 75  | [What is the difference between serialization and deserialization?](#75-what-is-the-difference-between-serialization-and-deserialization) |
| 76  | [What is the use of the Externalizable interface?](#76-what-is-the-use-of-the-externalizable-interface) |
| 77  | [What is the use of the readObject() method?](#77-what-is-the-use-of-the-readobject-method) |
| 78  | [What is the use of the writeObject() method?](#78-what-is-the-use-of-the-writeobject-method) |
| 79  | [What is the use of the ClassNotFoundException?](#79-what-is-the-use-of-the-classnotfoundexception) |
| 80  | [What is the use of the IOException?](#80-what-is-the-use-of-the-ioexception) |
| 81  | [What is the use of the FileNotFoundException?](#81-what-is-the-use-of-the-filenotfoundexception) |
| 82  | [What is the use of the EOFException?](#82-what-is-the-use-of-the-eofexception) |
| 83  | [What is the use of the ObjectInputStream class?](#83-what-is-the-use-of-the-objectinputstream-class) |
| 84  | [What is the use of the ObjectOutputStream class?](#84-what-is-the-use-of-the-objectoutputstream-class) |
| 85  | [What is the use of the FileInputStream class?](#85-what-is-the-use-of-the-fileinputstream-class) |
| 86  | [What is the use of the FileOutputStream class?](#86-what-is-the-use-of-the-fileoutputstream-class) |
| 87  | [What is the use of the BufferedReader class?](#87-what-is-the-use-of-the-bufferedreader-class) |
| 88  | [What is the use of the BufferedWriter class?](#88-what-is-the-use-of-the-bufferedwriter-class) |
| 89  | [What is the use of the PrintWriter class?](#89-what-is-the-use-of-the-printwriter-class) |
| 90  | [What is the use of the Scanner class?](#90-what-is-the-use-of-the-scanner-class) |
| 91  | [What is the use of the System.in?](#91-what-is-the-use-of-the-systemin) |
| 92  | [What is the use of the System.out?](#92-what-is-the-use-of-the-systemout) |
| 93  | [What is the use of the System.err?](#93-what-is-the-use-of-the-systemerr) |
| 94  | [What is the use of the printf() method?](#94-what-is-the-use-of-the-printf-method) |
| 95  | [What is the use of the format() method?](#95-what-is-the-use-of-the-format-method) |
| 96  | [What is the use of the println() method?](#96-what-is-the-use-of-the-println-method) |
| 97  | [What is the use of the print() method?](#97-what-is-the-use-of-the-print-method) |
| 98  | [What is the use of the read() method?](#98-what-is-the-use-of-the-read-method) |
| 99  | [What is the use of the write() method?](#99-what-is-the-use-of-the-write-method) |
| 100 | [What is the use of the flush() method?](#100-what-is-the-use-of-the-flush-method) |

### Table of Contents
### Level : Medium
| No. | Questions |
| --- | --------- |
| 1   | [Explain the concept of garbage collection in Java.](#1-explain-the-concept-of-garbage-collection-in-java) |
| 2   | [What is the difference between heap and stack memory in Java?](#2-what-is-the-difference-between-heap-and-stack-memory-in-java) |
| 3   | [What is the purpose of the finalize() method?](#3-what-is-the-purpose-of-the-finalize-method) |
| 4   | [What is the use of the System.gc() method?](#4-what-is-the-use-of-the-systemgc-method) |
| 5   | [What is the difference between an abstract class and a concrete class?](#5-what-is-the-difference-between-an-abstract-class-and-a-concrete-class) |
| 6   | [What is the difference between an interface and an abstract class?](#6-what-is-the-difference-between-an-interface-and-an-abstract-class) |
| 7   | [What is the use of the extends keyword?](#7-what-is-the-use-of-the-extends-keyword) |
| 8   | [What is the use of the implements keyword?](#8-what-is-the-use-of-the-implements-keyword) |
| 9   | [What is the use of the @Override annotation?](#9-what-is-the-use-of-the-override-annotation) |
| 10  | [What is the difference between a shallow copy and a deep copy?](#10-what-is-the-difference-between-a-shallow-copy-and-a-deep-copy) |
| 11  | [What is the use of the clone() method?](#11-what-is-the-use-of-the-clone-method) |
| 12  | [What is the difference between the equals() method and the == operator?](#12-what-is-the-difference-between-the-equals-method-and-the--operator) |
| 13  | [What is the use of the hashCode() method?](#13-what-is-the-use-of-the-hashcode-method) |
| 14  | [What is the difference between a HashMap and a TreeMap?](#14-what-is-the-difference-between-a-hashmap-and-a-treemap) |
| 15  | [What is the difference between a HashSet and a TreeSet?](#15-what-is-the-difference-between-a-hashset-and-a-treeset) |
| 16  | [What is the difference between a List and a Set?](#16-what-is-the-difference-between-a-list-and-a-set) |
| 17  | [What is the difference between an ArrayList and a LinkedList?](#17-what-is-the-difference-between-an-arraylist-and-a-linkedlist) |
| 18  | [What is the difference between a Vector and an ArrayList?](#18-what-is-the-difference-between-a-vector-and-an-arraylist) |
| 19  | [What is the difference between a Stack and a Queue?](#19-what-is-the-difference-between-a-stack-and-a-queue) |
| 20  | [What is the difference between a PriorityQueue and a LinkedList?](#20-what-is-the-difference-between-a-priorityqueue-and-a-linkedlist) |
| 21  | [What is the use of the Collections class?](#21-what-is-the-use-of-the-collections-class) |
| 22  | [What is the use of the Arrays class?](#22-what-is-the-use-of-the-arrays-class) |
| 23  | [What is the use of the Comparator interface?](#23-what-is-the-use-of-the-comparator-interface) |
| 24  | [What is the use of the Comparable interface?](#24-what-is-the-use-of-the-comparable-interface) |
| 25  | [What is the difference between the Iterator and the ListIterator?](#25-what-is-the-difference-between-the-iterator-and-the-listiterator) |
| 26  | [What is the use of the forEach() method?](#26-what-is-the-use-of-the-foreach-method) |
| 27  | [What is the use of the stream() method?](#27-what-is-the-use-of-the-stream-method) |
| 28  | [What is the use of the filter() method?](#28-what-is-the-use-of-the-filter-method) |
| 29  | [What is the use of the map() method?](#29-what-is-the-use-of-the-map-method) |
| 30  | [What is the use of the reduce() method?](#30-what-is-the-use-of-the-reduce-method) |
| 31  | [What is the use of the collect() method?](#31-what-is-the-use-of-the-collect-method) |
| 32  | [What is the use of the Optional class?](#32-what-is-the-use-of-the-optional-class) |
| 33  | [What is the use of the lambda expression?](#33-what-is-the-use-of-the-lambda-expression) |
| 34  | [What is the use of the method reference?](#34-what-is-the-use-of-the-method-reference) |
| 35  | [What is the use of the functional interface?](#35-what-is-the-use-of-the-functional-interface) |
| 36  | [What is the use of the default method in an interface?](#36-what-is-the-use-of-the-default-method-in-an-interface) |
| 37  | [What is the use of the static method in an interface?](#37-what-is-the-use-of-the-static-method-in-an-interface) |
| 38  | [What is the use of the Stream API?](#38-what-is-the-use-of-the-stream-api) |
| 39  | [What is the use of the Date and Time API?](#39-what-is-the-use-of-the-date-and-time-api) |
| 40  | [What is the use of the LocalDate class?](#40-what-is-the-use-of-the-localdate-class) |
| 41  | [What is the use of the LocalTime class?](#41-what-is-the-use-of-the-localtime-class) |
| 42  | [What is the use of the LocalDateTime class?](#42-what-is-the-use-of-the-localdatetime-class) |
| 43  | [What is the use of the ZonedDateTime class?](#43-what-is-the-use-of-the-zoneddatetime-class) |
| 44  | [What is the use of the Instant class?](#44-what-is-the-use-of-the-instant-class) |
| 45  | [What is the use of the Duration class?](#45-what-is-the-use-of-the-duration-class) |
| 46  | [What is the use of the Period class?](#46-what-is-the-use-of-the-period-class) |
| 47  | [What is the use of the DateTimeFormatter class?](#47-what-is-the-use-of-the-datetimeformatter-class) |
| 48  | [What is the use of the DateTimeParseException?](#48-what-is-the-use-of-the-datetimeparseexception) |
| 49  | [What is the use of the ChronoUnit class?](#49-what-is-the-use-of-the-chronounit-class) |
| 50  | [What is the use of the ChronoField class?](#50-what-is-the-use-of-the-chronofield-class) |
| 51  | [What is the use of the TemporalAdjusters class?](#51-what-is-the-use-of-the-temporaladjusters-class) |
| 52  | [What is the use of the TemporalQueries class?](#52-what-is-the-use-of-the-temporalqueries-class) |
| 53  | [What is the use of the TemporalAmount interface?](#53-what-is-the-use-of-the-temporalamount-interface) |
| 54  | [What is the use of the TemporalUnit interface?](#54-what-is-the-use-of-the-temporalunit-interface) |
| 55  | [What is the use of the TemporalField interface?](#55-what-is-the-use-of-the-temporalfield-interface) |
| 56  | [What is the use of the TemporalAccessor interface?](#56-what-is-the-use-of-the-temporalaccessor-interface) |
| 57  | [What is the use of the TemporalAdjuster interface?](#57-what-is-the-use-of-the-temporaladjuster-interface) |
| 58  | [What is the use of the TemporalQuery interface?](#58-what-is-the-use-of-the-temporalquery-interface) |
| 59  | [What is the use of the Temporal interface?](#59-what-is-the-use-of-the-temporal-interface) |
| 60  | [What is the use of the TemporalAmount implementation?](#60-what-is-the-use-of-the-temporalamount-implementation) |
| 61  | [What is the use of the TemporalUnit implementation?](#61-what-is-the-use-of-the-temporalunit-implementation) |
| 62  | [What is the use of the TemporalField implementation?](#62-what-is-the-use-of-the-temporalfield-implementation) |
| 63  | [What is the use of the TemporalAccessor implementation?](#63-what-is-the-use-of-the-temporalaccessor-implementation) |
| 64  | [What is the use of the TemporalAdjuster implementation?](#64-what-is-the-use-of-the-temporaladjuster-implementation) |
| 65  | [What is the use of the TemporalQuery implementation?](#65-what-is-the-use-of-the-temporalquery-implementation) |
| 66  | [What is the use of the Temporal implementation?](#66-what-is-the-use-of-the-temporal-implementation) |
| 67  | [What is the use of the Stream API for parallel processing?](#67-what-is-the-use-of-the-stream-api-for-parallel-processing) |
| 68  | [What is the use of the CompletableFuture class?](#68-what-is-the-use-of-the-completablefuture-class) |
| 69  | [What is the use of the ExecutorService interface?](#69-what-is-the-use-of-the-executorservice-interface) |
| 70  | [What is the use of the Executors class?](#70-what-is-the-use-of-the-executors-class) |
| 71  | [What is the use of the ScheduledExecutorService interface?](#71-what-is-the-use-of-the-scheduledexecutorservice-interface) |
| 72  | [What is the use of the Callable interface?](#72-what-is-the-use-of-the-callable-interface) |
| 73  | [What is the use of the Future interface?](#73-what-is-the-use-of-the-future-interface) |
| 74  | [What is the use of the FutureTask class?](#74-what-is-the-use-of-the-futuretask-class) |
| 75  | [What is the use of the CountDownLatch class?](#75-what-is-the-use-of-the-countdownlatch-class) |
| 76  | [What is the use of the CyclicBarrier class?](#76-what-is-the-use-of-the-cyclicbarrier-class) |
| 77  | [What is the use of the Semaphore class?](#77-what-is-the-use-of-the-semaphore-class) |
| 78  | [What is the use of the ReentrantLock class?](#78-what-is-the-use-of-the-reentrantlock-class) |
| 79  | [What is the use of the ReadWriteLock interface?](#79-what-is-the-use-of-the-readwritelock-interface) |
| 80  | [What is the use of the StampedLock class?](#80-what-is-the-use-of-the-stampedlock-class) |
| 81  | [What is the use of the Condition interface?](#81-what-is-the-use-of-the-condition-interface) |
| 82  | [What is the use of the BlockingQueue interface?](#82-what-is-the-use-of-the-blockingqueue-interface) |
| 83  | [What is the use of the LinkedBlockingQueue class?](#83-what-is-the-use-of-the-linkedblockingqueue-class) |
| 84  | [What is the use of the PriorityBlockingQueue class?](#84-what-is-the-use-of-the-priorityblockingqueue-class) |
| 85  | [What is the use of the DelayQueue class?](#85-what-is-the-use-of-the-delayqueue-class) |
| 86  | [What is the use of the SynchronousQueue class?](#86-what-is-the-use-of-the-synchronousqueue-class) |
| 87  | [What is the use of the TransferQueue interface?](#87-what-is-the-use-of-the-transferqueue-interface) |
| 88  | [What is the use of the LinkedTransferQueue class?](#88-what-is-the-use-of-the-linkedtransferqueue-class) |
| 89  | [What is the use of the ConcurrentMap interface?](#89-what-is-the-use-of-the-concurrentmap-interface) |
| 90  | [What is the use of the ConcurrentHashMap class?](#90-what-is-the-use-of-the-concurrenthashmap-class) |
| 91  | [What is the use of the CopyOnWriteArrayList class?](#91-what-is-the-use-of-the-copyonwritearraylist-class) |
| 92  | [What is the use of the CopyOnWriteArraySet class?](#92-what-is-the-use-of-the-copyonwritearrayset-class) |
| 93  | [What is the use of the ConcurrentSkipListMap class?](#93-what-is-the-use-of-the-concurrentskiplistmap-class) |
| 94  | [What is the use of the ConcurrentSkipListSet class?](#94-what-is-the-use-of-the-concurrentskiplistset-class) |
| 95  | [What is the use of the AtomicInteger class?](#95-what-is-the-use-of-the-atomicinteger-class) |
| 96  | [What is the use of the AtomicLong class?](#96-what-is-the-use-of-the-atomiclong-class) |
| 97  | [What is the use of the AtomicReference class?](#97-what-is-the-use-of-the-atomicreference-class) |
| 98  | [What is the use of the AtomicBoolean class?](#98-what-is-the-use-of-the-atomicboolean-class) |
| 99  | [What is the use of the AtomicIntegerArray class?](#99-what-is-the-use-of-the-atomicintegerarray-class) |
| 100 | [What is the use of the AtomicLongArray class?](#100-what-is-the-use-of-the-atomiclongarray-class) |

### Table of Contents
### Level : Hard
| No. | Questions |
| --- | --------- |
| 1   | [Explain the concept of memory leaks in Java.](#1-explain-the-concept-of-memory-leaks-in-java) |
| 2   | [How do you troubleshoot memory leaks in Java?](#2-how-do-you-troubleshoot-memory-leaks-in-java) |
| 3   | [What are the different types of class loaders in Java?](#3-what-are-the-different-types-of-class-loaders-in-java) |
| 4   | [How does the class loading mechanism work in Java?](#4-how-does-the-class-loading-mechanism-work-in-java) |
| 5   | [What is the use of the Reflection API in Java?](#5-what-is-the-use-of-the-reflection-api-in-java) |
| 6   | [How do you create thread-safe code in Java?](#6-how-do-you-create-thread-safe-code-in-java) |
| 7   | [What is the difference between synchronized and volatile keywords?](#7-what-is-the-difference-between-synchronized-and-volatile-keywords) |
| 8   | [What are the best practices for exception handling in Java?](#8-what-are-the-best-practices-for-exception-handling-in-java) |
| 9   | [What is the use of the java.lang.instrument package?](#9-what-is-the-use-of-the-javalanginstrument-package) |
| 10  | [How do you use the Instrumentation API in Java?](#10-how-do-you-use-the-instrumentation-api-in-java) |
| 11  | [Explain the concept of Java Memory Model (JMM).](#11-explain-the-concept-of-java-memory-model-jmm) |
| 12  | [What is the use of the Unsafe class in Java?](#12-what-is-the-use-of-the-unsafe-class-in-java) |
| 13  | [How do you perform dynamic class loading in Java?](#13-how-do-you-perform-dynamic-class-loading-in-java) |
| 14  | [What is the use of the Proxy class in Java?](#14-what-is-the-use-of-the-proxy-class-in-java) |
| 15  | [What is the difference between dynamic proxy and static proxy?](#15-what-is-the-difference-between-dynamic-proxy-and-static-proxy) |
| 16  | [How do you implement dynamic proxies in Java?](#16-how-do-you-implement-dynamic-proxies-in-java) |
| 17  | [What is the use of the java.lang.invoke package?](#17-what-is-the-use-of-the-javalanginvoke-package) |
| 18  | [What is the use of the MethodHandles class?](#18-what-is-the-use-of-the-methodhandles-class) |
| 19  | [How do you perform bytecode manipulation in Java?](#19-how-do-you-perform-bytecode-manipulation-in-java) |
| 20  | [What is the use of the ASM library in Java?](#20-what-is-the-use-of-the-asm-library-in-java) |
| 21  | [How do you perform code generation in Java?](#21-how-do-you-perform-code-generation-in-java) |
| 22  | [What is the use of the Javassist library in Java?](#22-what-is-the-use-of-the-javassist-library-in-java) |
| 23  | [How do you use the Java Compiler API?](#23-how-do-you-use-the-java-compiler-api) |
| 24  | [What is the use of the javax.tools package?](#24-what-is-the-use-of-the-javaxtools-package) |
| 25  | [How do you perform annotation processing in Java?](#25-how-do-you-perform-annotation-processing-in-java) |
| 26  | [What is the use of the javax.annotation.processing package?](#26-what-is-the-use-of-the-javaxannotationprocessing-package) |
| 27  | [How do you create custom annotations in Java?](#27-how-do-you-create-custom-annotations-in-java) |
| 28  | [What is the use of the javax.inject package?](#28-what-is-the-use-of-the-javaxinject-package) |
| 29  | [How do you perform dependency injection in Java?](#29-how-do-you-perform-dependency-injection-in-java) |
| 30  | [What is the difference between constructor injection and setter injection?](#30-what-is-the-difference-between-constructor-injection-and-setter-injection) |
| 31  | [What is the use of the javax.enterprise.context package?](#31-what-is-the-use-of-the-javaxenterprisecontext-package) |
| 32  | [What is the use of the javax.enterprise.inject package?](#32-what-is-the-use-of-the-javaxenterpriseinject-package) |
| 33  | [What is the use of the javax.enterprise.event package?](#33-what-is-the-use-of-the-javaxenterpriseevent-package) |
| 34  | [How do you use the CDI (Contexts and Dependency Injection) in Java?](#34-how-do-you-use-the-cdi-contexts-and-dependency-injection-in-java) |
| 35  | [What is the use of the javax.enterprise.inject.spi package?](#35-what-is-the-use-of-the-javaxenterpriseinjectspi-package) |
| 36  | [How do you use the Bean Validation API in Java?](#36-how-do-you-use-the-bean-validation-api-in-java) |
| 37  | [What is the use of the javax.validation package?](#37-what-is-the-use-of-the-javaxvalidation-package) |
| 38  | [How do you create custom validators in Java?](#38-how-do-you-create-custom-validators-in-java) |
| 39  | [How do you use the JPA (Java Persistence API) in Java?](#39-how-do-you-use-the-jpa-java-persistence-api-in-java) |
| 40  | [What is the use of the javax.persistence package?](#40-what-is-the-use-of-the-javaxpersistence-package) |
| 41  | [How do you perform object-relational mapping in Java?](#41-how-do-you-perform-object-relational-mapping-in-java) |
| 42  | [What is the use of the Hibernate framework in Java?](#42-what-is-the-use-of-the-hibernate-framework-in-java) |
| 43  | [How do you use the JTA (Java Transaction API) in Java?](#43-how-do-you-use-the-jta-java-transaction-api-in-java) |
| 44  | [What is the use of the javax.transaction package?](#44-what-is-the-use-of-the-javaxtransaction-package) |
| 45  | [How do you perform distributed transactions in Java?](#45-how-do-you-perform-distributed-transactions-in-java) |
| 46  | [What is the use of the XADataSource interface?](#46-what-is-the-use-of-the-xadatasource-interface) |
| 47  | [How do you use the JDBC (Java Database Connectivity) API in Java?](#47-how-do-you-use-the-jdbc-java-database-connectivity-api-in-java) |
| 48  | [What is the use of the java.sql package?](#48-what-is-the-use-of-the-javasql-package) |
| 49  | [How do you perform connection pooling in Java?](#49-how-do-you-perform-connection-pooling-in-java) |
| 50  | [What is the use of the javax.sql package?](#50-what-is-the-use-of-the-javaxsql-package) |
| 51  | [How do you use the Java EE (Enterprise Edition) platform in Java?](#51-how-do-you-use-the-java-ee-enterprise-edition-platform-in-java) |
| 52  | [What is the use of the javax.ejb package?](#52-what-is-the-use-of-the-javaxejb-package) |
| 53  | [How do you create enterprise beans in Java?](#53-how-do-you-create-enterprise-beans-in-java) |
| 54  | [What is the use of the javax.jms package?](#54-what-is-the-use-of-the-javaxjms-package) |
| 55  | [How do you use the Java Message Service (JMS) in Java?](#55-how-do-you-use-the-java-message-service-jms-in-java) |
| 56  | [What is the use of the javax.mail package?](#56-what-is-the-use-of-the-javaxmail-package) |
| 57  | [How do you send email using the JavaMail API?](#57-how-do-you-send-email-using-the-javamail-api) |
| 58  | [What is the use of the javax.ws.rs package?](#58-what-is-the-use-of-the-javaxwsrs-package) |
| 59  | [How do you create RESTful web services in Java?](#59-how-do-you-create-restful-web-services-in-java) |
| 60  | [What is the use of the JAX-RS (Java API for RESTful Web Services) in Java?](#60-what-is-the-use-of-the-jax-rs-java-api-for-restful-web-services-in-java) |
| 61  | [How do you use the JAX-WS (Java API for XML Web Services) in Java?](#61-how-do-you-use-the-jax-ws-java-api-for-xml-web-services-in-java) |
| 62  | [What is the use of the javax.xml.ws package?](#62-what-is-the-use-of-the-javaxxmlws-package) |
| 63  | [How do you create SOAP web services in Java?](#63-how-do-you-create-soap-web-services-in-java) |
| 64  | [What is the use of the JAXB (Java Architecture for XML Binding) in Java?](#64-what-is-the-use-of-the-jaxb-java-architecture-for-xml-binding-in-java) |
| 65  | [How do you perform XML binding in Java?](#65-how-do-you-perform-xml-binding-in-java) |
| 66  | [What is the use of the javax.xml.bind package?](#66-what-is-the-use-of-the-javaxxmlbind-package) |
| 67  | [How do you use the JavaFX platform in Java?](#67-how-do-you-use-the-javafx-platform-in-java) |
| 68  | [What is the use of the javafx.application package?](#68-what-is-the-use-of-the-javafxapplication-package) |
| 69  | [How do you create JavaFX applications in Java?](#69-how-do-you-create-javafx-applications-in-java) |
| 70  | [What is the use of the javafx.scene package?](#70-what-is-the-use-of-the-javafxscene-package) |
| 71  | [How do you create graphical user interfaces using JavaFX?](#71-how-do-you-create-graphical-user-interfaces-using-javafx) |
| 72  | [What is the use of the javafx.stage package?](#72-what-is-the-use-of-the-javafxstage-package) |
| 73  | [How do you use the Java 2D API in Java?](#73-how-do-you-use-the-java-2d-api-in-java) |
| 74  | [What is the use of the java.awt package?](#74-what-is-the-use-of-the-javaawt-package) |
| 75  | [How do you perform custom painting in Java?](#75-how-do-you-perform-custom-painting-in-java) |
| 76  | [What is the use of the javax.swing package?](#76-what-is-the-use-of-the-javaxswing-package) |
| 77  | [How do you create Swing applications in Java?](#77-how-do-you-create-swing-applications-in-java) |
| 78  | [What is the use of the javax.swing.event package?](#78-what-is-the-use-of-the-javaxswingevent-package) |
| 79  | [How do you handle events in Swing applications?](#79-how-do-you-handle-events-in-swing-applications) |
| 80  | [What is the use of the javax.swing.plaf package?](#80-what-is-the-use-of-the-javaxswingplaf-package) |
| 81  | [How do you customize the look and feel of Swing applications?](#81-how-do-you-customize-the-look-and-feel-of-swing-applications) |
| 82  | [What is the use of the javax.swing.table package?](#82-what-is-the-use-of-the-javaxswingtable-package) |
| 83  | [How do you create and manipulate tables in Swing applications?](#83-how-do-you-create-and-manipulate-tables-in-swing-applications) |
| 84  | [What is the use of the javax.swing.tree package?](#84-what-is-the-use-of-the-javaxswingtree-package) |
| 85  | [How do you create and manipulate trees in Swing applications?](#85-how-do-you-create-and-manipulate-trees-in-swing-applications) |
| 86  | [What is the use of the javax.swing.text package?](#86-what-is-the-use-of-the-javaxswingtext-package) |
| 87  | [How do you create and manipulate text components in Swing applications?](#87-how-do-you-create-and-manipulate-text-components-in-swing-applications) |
| 88  | [What is the use of the javax.swing.undo package?](#88-what-is-the-use-of-the-javaxswingundo-package) |
| 89  | [How do you implement undo and redo functionality in Swing applications?](#89-how-do-you-implement-undo-and-redo-functionality-in-swing-applications) |
| 90  | [What is the use of the javax.swing.filechooser package?](#90-what-is-the-use-of-the-javaxswingfilechooser-package) |
| 91  | [How do you use the JFileChooser component in Swing applications?](#91-how-do-you-use-the-jfilechooser-component-in-swing-applications) |
| 92  | [What is the use of the javax.swing.border package?](#92-what-is-the-use-of-the-javaxswingborder-package) |
| 93  | [How do you create and manipulate borders in Swing applications?](#93-how-do-you-create-and-manipulate-borders-in-swing-applications) |
| 94  | [What is the use of the javax.swing.colorchooser package?](#94-what-is-the-use-of-the-javaxswingcolorchooser-package) |
| 95  | [How do you use the JColorChooser component in Swing applications?](#95-how-do-you-use-the-jcolorchooser-component-in-swing-applications) |
| 96  | [What is the use of the javax.swing.text.html package?](#96-what-is-the-use-of-the-javaxswingtexthtml-package) |
| 97  | [How do you create and manipulate HTML text components in Swing applications?](#97-how-do-you-create-and-manipulate-html-text-components-in-swing-applications) |
| 98  | [What is the use of the javax.swing.text.html.parser package?](#98-what-is-the-use-of-the-javaxswingtexthtmlparser-package) |
| 99  | [How do you parse HTML documents in Swing applications?](#99-how-do-you-parse-html-documents-in-swing-applications) |
| 100 | [What is the use of the javax.swing.text.rtf package?](#100-what-is-the-use-of-the-javaxswingtextrtf-package) |


# Easy Java Interview Questions and Answers
## 1. What is Java?
Java is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible. It is a general-purpose programming language intended to let application developers write once, run anywhere (WORA), meaning that compiled Java code can run on all platforms that support Java without the need for recompilation.

#### **[⬆ Back to Top](#level--easy)**
---

## 2. Explain JVM, JRE, and JDK.
- **JVM (Java Virtual Machine):** An abstract machine that enables your computer to run a Java program. It provides a runtime environment in which Java bytecode can be executed.
- **JRE (Java Runtime Environment):** A package that provides the libraries, Java Virtual Machine, and other components to run applications written in Java. It does not contain tools for Java development like compilers or debuggers.
- **JDK (Java Development Kit):** A full-featured software development kit for Java. It includes JRE as well as development tools like compilers and debuggers.

#### **[⬆ Back to Top](#level--easy)**
---

## 3. What are the main features of Java?
- **Object-Oriented:** Everything in Java is an object.
- **Platform-Independent:** Java code can run on any platform that supports Java.
- **Simple:** Easy to learn and use.
- **Secure:** Java provides a secure environment for developing applications.
- **Architecture-Neutral:** Java programs are architecture-neutral.
- **Portable:** Java programs can be carried out on any platform without any implementation.
- **Robust:** Java is strong and has strong memory management.
- **Multithreaded:** Java supports multithreading.
- **Interpreted:** Java bytecode is translated on the fly to native machine instructions.
- **High-Performance:** Java is faster than traditional interpreted programming languages.
- **Distributed:** Java is designed for the distributed environment of the internet.

#### **[⬆ Back to Top](#level--easy)**
---

## 4. What is the difference between JDK and JRE?
- **JDK:** Includes tools for developing, debugging, and monitoring Java applications.
- **JRE:** Provides the libraries and JVM necessary to run Java applications.

#### **[⬆ Back to Top](#level--easy)**
---

## 5. Explain `public static void main(String args[])`.
- **public:** Accessible from anywhere.
- **static:** Can be called without creating an instance of the class.
- **void:** Does not return any value.
- **main:** The main method is the entry point of the application.
- **String args[]:** An array of strings that stores arguments passed by the command line.

#### **[⬆ Back to Top](#level--easy)**
---

## 6. What is a constructor in Java?
A constructor in Java is a special method that is used to initialize objects. The constructor is called when an object of a class is created. It can be used to set initial values for object attributes.

```java
public class MyClass {
    int x;  // Create a class attribute

    // Create a class constructor for the MyClass class
    public MyClass() {
        x = 5;  // Set the initial value for the class attribute x
    }

    public static void main(String[] args) {
        MyClass myObj = new MyClass(); // Create an object of class MyClass
        System.out.println(myObj.x); // Print the value of x
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 7. What are the types of constructors in Java?
- **Default Constructor:** A constructor that does not accept any parameters.
- **Parameterized Constructor:** A constructor that accepts one or more parameters.

#### **[⬆ Back to Top](#level--easy)**
---

## 8. What is a default constructor?
A default constructor is a constructor that does not take any arguments. If no constructor is defined in a class, the Java compiler creates a default constructor for the class.

```java
public class MyClass {
    int x;

    public MyClass() {
        // Default constructor
        x = 0;
    }

    public static void main(String[] args) {
        MyClass obj = new MyClass();
        System.out.println(obj.x); // Output will be 0
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 9. Explain method overloading.
Method overloading allows a class to have more than one method with the same name, provided their parameter lists are different. It is a way to achieve polymorphism in Java.

```java
public class MyClass {
    static int add(int a, int b) {
        return a + b;
    }

    static double add(double a, double b) {
        return a + b;
    }

    public static void main(String[] args) {
        System.out.println(add(10, 20)); // Calls int version
        System.out.println(add(10.5, 20.5)); // Calls double version
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 10. What is method overriding?
Method overriding occurs when a subclass provides a specific implementation for a method that is already defined in its superclass. The method in the subclass must have the same name, return type, and parameters as the method in the superclass.

```java
class Animal {
    void sound() {
        System.out.println("Animal makes a sound");
    }
}

class Dog extends Animal {
    void sound() {
        System.out.println("Dog barks");
    }

    public static void main(String[] args) {
        Animal obj = new Dog();
        obj.sound(); // Calls the overridden method in Dog class
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 11. What is inheritance?
Inheritance is a mechanism in Java by which one class is allowed to inherit the features (fields and methods) of another class. It promotes code reusability and establishes a relationship between classes.

```java
class Animal {
    void eat() {
        System.out.println("This animal eats food");
    }
}

class Dog extends Animal {
    void bark() {
        System.out.println("This dog barks");
    }

    public static void main(String[] args) {
        Dog dog = new Dog();
        dog.eat(); // Calls the inherited method from Animal class
        dog.bark(); // Calls the method in Dog class
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 12. Explain polymorphism.
Polymorphism in Java allows one interface to be used for a general class of actions. The specific action is determined by the exact nature of the situation.

- **Compile-time polymorphism:** Achieved by method overloading.
- **Runtime polymorphism:** Achieved by method overriding.

```java
class Animal {
    void sound() {
        System.out.println("Animal makes a sound");
    }
}

class Dog extends Animal {
    void sound() {
        System.out.println("Dog barks");
    }

    public static void main(String[] args) {
        Animal obj = new Dog();
        obj.sound(); // Calls the overridden method in Dog class
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 13. What is encapsulation?
Encapsulation is the wrapping up of data under a single unit. It is the mechanism that binds together code and the data it manipulates and keeps both safe from outside interference and misuse.

```java
public class EncapsulationExample {
    private String name;

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 14. What is abstraction?
Abstraction is the process of hiding the implementation details and showing only functionality to the user. It helps to reduce complexity and allows the programmer to focus on interactions.

```java
abstract class Animal {
    abstract void sound();
}

class Dog extends Animal {
    void sound() {
        System.out.println("Dog barks");
    }

    public static void main(String[] args) {
        Animal obj = new Dog();
        obj.sound();
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 15. What are the access modifiers in Java?
- **public:** Accessible from everywhere.
- **private:** Accessible only within the declared class.
- **protected:** Accessible within the same package and subclasses.
- **default (no modifier):** Accessible only within the same package.

#### **[⬆ Back to Top](#level--easy)**
---

## 16. Explain the use of 'this' keyword.
The `this` keyword refers to the current object in a method or constructor. It can be used to refer to the current class instance variable, invoke the current class method, or return the current class instance from a method.

```java
public class ThisExample {
    int x;

    ThisExample(int x) {
        this.x = x;
    }

    void display() {
        System.out.println("Value of x is: " + this.x);
    }

    public static void main(String[] args) {
        ThisExample obj = new ThisExample(10);
        obj.display();
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 17. What is a static method?
A static method belongs to the class rather than instances of the class. It can be invoked without creating an instance of the class.

```java
public class StaticMethodExample {
    static void display() {
        System.out.println("This is a static method.");
    }

    public static void main(String[] args) {
        StaticMethodExample.display();
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 18. What is the difference between static and non-static methods?
- **Static methods:** Belong to the class, can be called without creating an object, cannot access instance variables and instance methods directly.
- **Non-static methods:** Belong to an instance of the class, can access instance variables and methods.

#### **[⬆ Back to Top](#level--easy)**
---

## 19. What is the final keyword in Java?
- **final variable:** Cannot be changed once initialized.
- **final method:** Cannot be overridden by subclasses.
- **final class:** Cannot be subclassed.

```java
public class FinalExample {
    final int MAX_VALUE = 100;

    final void display() {
        System.out.println("This is a final method.");
    }

    public static void main(String[] args) {
        FinalExample obj = new FinalExample();
        System.out.println("MAX_VALUE: " + obj.MAX_VALUE);
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 20. What are the data types in Java?
- **Primitive data types:** byte, short, int, long, float, double, char, boolean.
- **Non-primitive data types:** String, Arrays, Classes, Interfaces.

#### **[⬆ Back to Top](#level--easy)**
---

## 21. What is the difference between int and Integer?
- **int:** A primitive data type.
- **Integer:** A wrapper class for the primitive data type `int`.

```java
int a = 10;
Integer b = 10;
```

#### **[⬆ Back to Top](#level--easy)**
---

## 22. What are the control statements in Java?
- **Decision-making statements:** if, if-else, switch.
- **Loop statements:** for, while, do-while.
- **Branching statements:** break, continue, return.

#### **[⬆ Back to Top](#level--easy)**
---

## 23. Explain the use of break and continue.
- **break:** Terminates the loop or switch statement.
- **continue:** Skips the current iteration of a loop and proceeds to the next iteration.

```java
public class BreakContinueExample {
    public static void main(String[] args) {
        for (int i = 0; i < 10; i++) {
            if (i == 5) {
                break; // Stops the loop when i is 5
            }
            System.out.println(i);
        }

        for (int i = 0; i < 10; i++) {
            if (i == 5) {
                continue; // Skips the iteration when i is 5
            }
            System.out.println(i);
        }
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 24. What is a loop in Java?
A loop is a programming construct that repeats a block of code as long as a specified condition is true.

#### **[⬆ Back to Top](#level--easy)**
---

## 25. What are the types of loops in Java?
- **for loop**
- **while loop**
- **do-while loop**

```java
public class LoopExample {
    public static void main(String[] args) {
        // for loop
        for (int i = 0; i < 5; i++) {
            System.out.println("For loop: " + i);
        }

        // while loop
        int j = 0;
        while (j < 5) {
            System.out.println("While loop: " + j);
            j++;
        }

        // do-while loop
        int k = 0;
        do {
            System.out.println("Do-while loop: " + k);
            k++;
        } while (k < 5);
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 26. What is an array in Java?
An array is a collection of similar types of elements stored in contiguous memory locations.

#### **[⬆ Back to Top](#level--easy)**
---

## 27. How do you declare an array in Java?
```java
int[] arr = new int[5];
```

#### **[⬆ Back to Top](#level--easy)**
---

## 28. What is the default value of an array?
- **int, short, byte, long:** 0
- **float, double:** 0.0
- **char:** '\u0000'
- **boolean:** false
- **Object:** null

#### **[⬆ Back to Top](#level--easy)**
---

## 29. Explain the concept of an array of objects.
An array of objects is an array that holds references to objects of a class.

```java
class Student {
    String name;

    Student(String name) {
        this.name = name;
    }
}

public class ArrayOfObjectsExample {
    public static void main(String[] args) {
        Student[] students = new Student[3];
        students[0] = new Student("John");
        students[1] = new Student("Jane");
        students[2] = new Student("Jake");

        for (Student student : students) {
            System.out.println(student.name);
        }
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 30. What is a string in Java?
A string is a sequence of characters. In Java, strings are objects of the `String` class.

#### **[⬆ Back to Top](#level--easy)**
---

## 31. How do you declare a string in Java?
```java
String str = "Hello, World!";
```

#### **[⬆ Back to Top](#level--easy)**
---

## 32. What is the difference between String and StringBuffer?
- **String:** Immutable (cannot be changed once created).
- **StringBuffer:** Mutable (can be changed after creation), synchronized.

#### **[⬆ Back to Top](#level--easy)**
---

## 33. What is the difference between StringBuilder and StringBuffer?
- **StringBuilder:** Mutable and not synchronized (faster).
- **StringBuffer:** Mutable and synchronized (thread-safe).

#### **[⬆ Back to Top](#level--easy)**
---

## 34. What are the commonly used methods of String class?
- `length()`
- `charAt(int index)`
- `substring(int beginIndex, int endIndex)`
- `equals(Object obj)`
- `compareTo(String anotherString)`
- `toLowerCase()`
- `toUpperCase()`
- `trim()`
- `replace(char oldChar, char newChar)`

#### **[⬆ Back to Top](#level--easy)**
---

## 35. How do you compare strings in Java?
- **Using `equals()` method:** Compares the content of strings.
- **Using `==` operator:** Compares the reference of strings.

```java
String str1 = "Hello";
String str2 = "Hello";
String str3 = new String("Hello");

System.out.println(str1.equals(str2)); // true
System.out.println(str1 == str2); // true
System.out.println(str1 == str3); // false
```

#### **[⬆ Back to Top](#level--easy)**
---

## 36. What is an exception in Java?
An exception is an event that occurs during the execution of a program and disrupts its normal flow. It is an object that wraps an error event that can occur within a method and is passed to the runtime system.

#### **[⬆ Back to Top](#level--easy)**
---

## 37. Explain the try-catch block.
A `try-catch` block is used to handle exceptions. The code that might throw an exception is placed inside the `try` block, and the code to handle the exception is placed inside the `catch` block.

```java
try {
    int data = 50 / 0; // This will throw an exception
} catch (ArithmeticException e) {
    System.out.println("Cannot divide by zero");
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 38. What is the difference between checked and unchecked exceptions?
- **Checked exceptions:** Checked at compile-time (e.g., IOException).
- **Unchecked exceptions:** Checked at runtime (e.g., ArithmeticException, NullPointerException).

#### **[⬆ Back to Top](#level--easy)**
---

## 39. What is the use of the finally block?
The `finally` block is used to execute important code such as closing resources. It is always executed whether an exception is handled or not.

```java
try {
    int data = 50 / 0;
} catch (ArithmeticException e) {
    System.out.println("Cannot divide by zero");
} finally {
    System.out.println("Finally block executed");
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 40. What is the throw keyword?
The `throw` keyword is used to explicitly throw an exception.

```java
public class ThrowExample {
    static void validate(int age) {
        if (age < 18)
            throw new ArithmeticException("Not valid age");
        else
            System.out.println("Welcome to vote");
    }

    public static void main(String[] args) {
        validate(13);
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 41. What is the throws keyword?
The `throws` keyword is used to declare an exception. It specifies that a method can throw a particular type of exception.

```java
import java.io.*;

public class ThrowsExample {
    void method() throws IOException {
        throw new IOException("Device error");
    }

    public static void main(String[] args) {
        try {
            new ThrowsExample().method();
        } catch (Exception e) {
            System.out.println(e);
        }
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 42. Explain the concept of exception propagation.
Exception propagation refers to the process by which an exception is passed from the point it occurred to a method that can handle it. If an exception is not caught in the current method, it is propagated to the caller method, and so on.

#### **[⬆ Back to Top](#level--easy)**
---

## 43. What are the types of exceptions in Java?
- **Checked exceptions:** Exceptions that are checked at compile-time.
- **Unchecked exceptions:** Exceptions that are checked at runtime.

#### **[⬆ Back to Top](#level--easy)**
---

## 44. What is a custom exception?
A custom exception is a user-defined exception class that extends `Exception` or `RuntimeException`.

```java
class MyException extends Exception {
    public MyException(String s) {
        super(s);
    }
}

public class CustomExceptionExample {
    public static void main(String[] args) {
        try {
            throw new MyException("Custom Exception");
        } catch (MyException e) {
            System.out.println(e.getMessage());
        }
    }
}
```

#### **[⬆ Back to Top](#level--easy)**
---

## 45. What is the use of the synchronized keyword?
The `synchronized` keyword is used to control the access of multiple threads to a shared resource. It ensures that only one thread can access the synchronized method or block at a time.

#### **[⬆ Back to Top](#level--easy)**
---

## 46. What is multithreading?
Multithreading is a feature of Java that allows concurrent execution of two or more parts of a program to maximize the utilization of CPU.

#### **[⬆ Back to Top](#level--easy)**
---

## 47. What is the difference between a thread and a process?
- **Thread:** A lightweight subprocess, a smallest unit of processing.
- **Process:** A heavyweight process, an independent unit of execution.

#### **[⬆ Back to Top](#level--easy)**
---

## 48. How do you create a thread in Java?
- **By extending `Thread` class**
- **By implementing `Runnable` interface**

#### **[⬆ Back to Top](#level--easy)**
---

## 49. What is the Runnable interface?

The `Runnable` interface should be implemented by any class whose instances are intended to be executed by a thread. The class must define a method of no arguments called `run`.

```java
public interface Runnable {
    void run();
}
```
#### **[⬆ Back to Top](#level--easy)**
---

## 50. What is the Thread class?

The `Thread` class represents a thread of execution in a program. It provides constructors and methods for creating and operating on threads.

```java
public class MyThread extends Thread {
    public void run() {
        System.out.println("Thread is running.");
    }

    public static void main(String[] args) {
        MyThread t1 = new MyThread();
        t1.start();
    }
}
```
#### **[⬆ Back to Top](#level--easy)**
---

## 51. What are the states of a thread in Java?

A thread can be in one of the following states:

- **New**: A thread that has not yet started.
- **Runnable**: A thread executing in the Java virtual machine.
- **Blocked**: A thread that is blocked waiting for a monitor lock.
- **Waiting**: A thread that is waiting indefinitely for another thread to perform a particular action.
- **Timed Waiting**: A thread that is waiting for another thread to perform an action for up to a specified waiting time.
- **Terminated**: A thread that has exited.

#### **[⬆ Back to Top](#level--easy)**
---

## 52. What is thread priority?

Thread priority is an integer value that determines the relative priority of one thread compared to another. Java threads have a priority in the range between `MIN_PRIORITY` (1) and `MAX_PRIORITY` (10).

```java
Thread t1 = new Thread();
t1.setPriority(Thread.MAX_PRIORITY);
```
#### **[⬆ Back to Top](#level--easy)**
---

## 53. What is the difference between wait() and sleep()?

- **`wait()`**: Causes the current thread to wait until another thread invokes the `notify()` or `notifyAll()` methods. It must be called within a synchronized context.
- **`sleep()`**: Causes the current thread to sleep for the specified number of milliseconds. It can be called from any context.

#### **[⬆ Back to Top](#level--easy)**
---

## 54. What is the use of the join() method?

The `join()` method allows one thread to wait until another thread completes its execution.

```java
Thread t1 = new Thread(() -> {
    System.out.println("Thread 1 is running.");
});
t1.start();
t1.join();
System.out.println("Thread 1 has finished.");
```
#### **[⬆ Back to Top](#level--easy)**
---

## 55. What is the difference between notify() and notifyAll()?

- **`notify()`**: Wakes up a single thread that is waiting on the object's monitor.
- **`notifyAll()`**: Wakes up all threads that are waiting on the object's monitor.

#### **[⬆ Back to Top](#level--easy)**
---

## 56. What is the difference between a class and an object?

- **Class**: A blueprint from which individual objects are created.
- **Object**: An instance of a class.

#### **[⬆ Back to Top](#level--easy)**
---

## 57. What is the use of the new keyword?

The `new` keyword is used to create new objects.

```java
MyClass obj = new MyClass();
```
#### **[⬆ Back to Top](#level--easy)**
---

## 58. What is the difference between an abstract class and an interface?

- **Abstract Class**: Can have both abstract and concrete methods, and can have member variables.
- **Interface**: Can only have abstract methods (until Java 8, where default and static methods were allowed), and cannot have instance variables.

#### **[⬆ Back to Top](#level--easy)**
---

## 59. What is a package in Java?

A package is a namespace that organizes a set of related classes and interfaces. For example, `java.util` contains utility classes like `ArrayList`, `HashMap`, etc.

#### **[⬆ Back to Top](#level--easy)**
---

## 60. What is the use of the import statement?

The `import` statement allows the use of classes and interfaces from other packages.

```java
import java.util.ArrayList;
```
#### **[⬆ Back to Top](#level--easy)**
---

## 61. What is the difference between import and static import?

- **import**: Imports classes and interfaces.
- **static import**: Imports static members from classes and interfaces.

```java
import static java.lang.Math.PI;
```
#### **[⬆ Back to Top](#level--easy)**
---

## 62. What is the use of the super keyword?

The `super` keyword refers to the superclass (parent class) of the object. It is used to call superclass methods, and to access the superclass constructor.

```java
class Parent {
    void display() {
        System.out.println("Parent class method.");
    }
}

class Child extends Parent {
    void display() {
        super.display();
        System.out.println("Child class method.");
    }
}
```
#### **[⬆ Back to Top](#level--easy)**
---

## 63. What is the difference between an interface and a class?

- **Class**: Can contain both concrete and abstract methods, and can have constructors.
- **Interface**: Cannot have constructors and (before Java 8) could only contain abstract methods. From Java 8 onwards, it can contain default and static methods.

#### **[⬆ Back to Top](#level--easy)**
---

## 64. What is the use of the instanceof keyword?

The `instanceof` keyword is used to test whether an object is an instance of a specific class or an interface.

```java
if (obj instanceof MyClass) {
    // Do something
}
```
#### **[⬆ Back to Top](#level--easy)**
---

## 65. What is a nested class?

A nested class is a class defined within another class.

#### **[⬆ Back to Top](#level--easy)**
---

## 66. What is an inner class?

An inner class is a non-static nested class that has access to the members of its enclosing class.

#### **[⬆ Back to Top](#level--easy)**
---

## 67. What is a local inner class?

A local inner class is a class defined within a method or a block of code.

#### **[⬆ Back to Top](#level--easy)**
---

## 68. What is an anonymous inner class?

An anonymous inner class is a local inner class without a name. It is used to instantiate objects with certain "extras," such as method overrides, without having to actually subclass a class.

```java
Runnable r = new Runnable() {
    public void run() {
        System.out.println("Anonymous inner class.");
    }
};
```
#### **[⬆ Back to Top](#level--easy)**
---

## 69. What is a static nested class?

A static nested class is a nested class that is declared static. It does not have access to the instance variables of the outer class.

#### **[⬆ Back to Top](#level--easy)**
---

## 70. What is the use of the transient keyword?

The `transient` keyword in Java is used to indicate that a field should not be serialized.

```java
class MyClass implements Serializable {
    transient int transientField;
}
```
#### **[⬆ Back to Top](#level--easy)**
---

## 71. What is the use of the volatile keyword?

The `volatile` keyword is used to indicate that a variable's value will be modified by different threads.

```java
private volatile boolean flag = true;
```
#### **[⬆ Back to Top](#level--easy)**
---

## 72. What is serialization?

Serialization is the process of converting an object's state to a byte stream.

#### **[⬆ Back to Top](#level--easy)**
---

## 73. What is deserialization?

Deserialization is the process of converting a byte stream back into an object's state.

#### **[⬆ Back to Top](#level--easy)**
---

## 74. What is the use of the Serializable interface?

The `Serializable` interface is a marker interface that enables the serialization of an object.

#### **[⬆ Back to Top](#level--easy)**
---

## 75. What is the difference between serialization and deserialization?

- **Serialization**: Converting an object into a byte stream.
- **Deserialization**: Converting a byte stream back into an object.


#### **[⬆ Back to Top](#level--easy)**
---

## 76. What is the use of the Externalizable interface?

The `Externalizable` interface allows a class to define its own custom serialization and deserialization methods.

#### **[⬆ Back to Top](#level--easy)**
---

## 77. What is the use of the readObject() method?

The `readObject()` method is used for reading an object from an ObjectInputStream.

#### **[⬆ Back to Top](#level--easy)**
---

## 78. What is the use of the writeObject() method?

The `writeObject()` method is used for writing an object to an ObjectOutputStream.

#### **[⬆ Back to Top](#level--easy)**
---

## 79. What is the use of the ClassNotFoundException?

The `ClassNotFoundException` is thrown when an application tries to load a class through its string name but no definition for the class with the specified name could be found.

#### **[⬆ Back to Top](#level--easy)**
---

## 80. What is the use of the IOException?

The `IOException` is thrown when an I/O operation fails or is interrupted.

#### **[⬆ Back to Top](#level--easy)**
---

## 81. What is the use of the FileNotFoundException?

The `FileNotFoundException` is thrown when an attempt to open the file denoted by a specified pathname has failed.

#### **[⬆ Back to Top](#level--easy)**
---

## 82. What is the use of the EOFException?

The `EOFException` is thrown when the end of a file or stream is reached unexpectedly during input.

#### **[⬆ Back to Top](#level--easy)**
---

## 83. What is the use of the ObjectInputStream class?

The `ObjectInputStream` class is used to deserialize primitive data and objects previously written using an ObjectOutputStream.

#### **[⬆ Back to Top](#level--easy)**
---

## 84. What is the use of the ObjectOutputStream class?

The `ObjectOutputStream` class is used to serialize primitive data and objects to an OutputStream.

#### **[⬆ Back to Top](#level--easy)**
---

## 85. What is the use of the FileInputStream class?

The `FileInputStream` class is used to obtain input bytes from a file in a file system.

#### **[⬆ Back to Top](#level--easy)**
---

## 86. What is the use of the FileOutputStream class?

The `FileOutputStream` class is used to write output bytes to a file.

#### **[⬆ Back to Top](#level--easy)**
---

## 87. What is the use of the BufferedReader class?

The `BufferedReader` class is used to read text from an input stream efficiently.

#### **[⬆ Back to Top](#level--easy)**
---

## 88. What is the use of the BufferedWriter class?

The `BufferedWriter` class is used to write text to an output stream efficiently.

#### **[⬆ Back to Top](#level--easy)**
---

## 89. What is the use of the PrintWriter class?

The `PrintWriter` class is used to print formatted representations of objects to a text-output stream.

#### **[⬆ Back to Top](#level--easy)**
---

## 90. What is the use of the Scanner class?

The `Scanner` class is used to parse primitive types and strings using regular expressions.

```java
Scanner sc = new Scanner(System.in);
int i = sc.nextInt();
```
#### **[⬆ Back to Top](#level--easy)**
---

## 91. What is the use of the System.in?

`System.in` is an InputStream that is typically connected to the keyboard input of the console.

#### **[⬆ Back to Top](#level--easy)**
---

## 92. What is the use of the System.out?

`System.out` is a PrintStream that is typically connected to the console output.

#### **[⬆ Back to Top](#level--easy)**
---

## 93. What is the use of the System.err?

`System.err` is a PrintStream that is typically connected to the console error output.

#### **[⬆ Back to Top](#level--easy)**
---

## 94. What is the use of the printf() method?

The `printf()` method is used to print a formatted string to the console.

```java
System.out.printf("Name: %s Age: %d", "John", 25);
```

#### **[⬆ Back to Top](#level--easy)**
---

## 95. What is the use of the format() method?

The `format()` method is similar to `printf()` and is used to create a formatted string.

```java
String formattedString = String.format("Name: %s Age: %d", "John", 25);
```
#### **[⬆ Back to Top](#level--easy)**
---

## 96. What is the use of the println() method?

The `println()` method is used to print a string to the console with a newline at the end.

```java
System.out.println("Hello, World!");
```
#### **[⬆ Back to Top](#level--easy)**
---

## 97. What is the use of the print() method?

The `print()` method is used to print a string to the console without a newline.

```java
System.out.print("Hello, ");
System.out.print("World!");
```
#### **[⬆ Back to Top](#level--easy)**
---

## 98. What is the use of the read() method?

The `read()` method is used to read a byte of data from an InputStream.

```java
int data = System.in.read();
```
#### **[⬆ Back to Top](#level--easy)**
---

## 99. What is the use of the write() method?

The `write()` method is used to write a byte of data to an OutputStream.

```java
System.out.write(65); // Writes the character 'A'
```
#### **[⬆ Back to Top](#level--easy)**
---

## 100. What is the use of the flush() method?

The `flush()` method is used to flush the OutputStream, forcing any buffered output bytes to be written out.

```java
OutputStream out = new FileOutputStream("output.txt");
out.write("Hello, World!".getBytes());
out.flush();
```
#### **[⬆ Back to Top](#level--easy)**
---

# Medium Java Interview Questions and Answers

## 1. Explain the concept of garbage collection in Java.
Garbage collection in Java is the process of automatically reclaiming memory by identifying and disposing of objects that are no longer in use. The Java Virtual Machine (JVM) manages this, which helps in preventing memory leaks. It utilizes algorithms like mark-and-sweep, generational, and reference counting to identify unreachable objects and reclaim their memory.

#### **[⬆ Back to Top](#level--medium)**
---

## 2. What is the difference between heap and stack memory in Java?
- **Heap Memory**: Used for dynamic memory allocation where objects and class instances are stored. It is managed by the garbage collector.
- **Stack Memory**: Used for static memory allocation where method calls and local variables are stored. It follows a Last-In-First-Out (LIFO) order.

#### **[⬆ Back to Top](#level--medium)**
---

## 3. What is the purpose of the `finalize()` method?
The `finalize()` method is called by the garbage collector on an object when garbage collection determines that there are no more references to the object. It is used to perform cleanup operations before the object is reclaimed.

#### **[⬆ Back to Top](#level--medium)**
---

## 4. What is the use of the `System.gc()` method?
The `System.gc()` method is a request to the JVM to perform garbage collection. However, it is not guaranteed that the JVM will execute the garbage collection immediately.

#### **[⬆ Back to Top](#level--medium)**
---

## 5. What is the difference between an abstract class and a concrete class?
- **Abstract Class**: Cannot be instantiated and may contain abstract methods (methods without a body). It is used to represent an abstract concept.
- **Concrete Class**: Can be instantiated and must provide implementations for all inherited abstract methods.

#### **[⬆ Back to Top](#level--medium)**
---

## 6. What is the difference between an interface and an abstract class?
- **Interface**: Can contain abstract methods and default methods. A class can implement multiple interfaces.
- **Abstract Class**: Can contain both abstract methods and concrete methods. A class can extend only one abstract class.

#### **[⬆ Back to Top](#level--medium)**
---

## 7. What is the use of the `extends` keyword?
The `extends` keyword is used to indicate that a class is inheriting properties and methods from a superclass.

#### **[⬆ Back to Top](#level--medium)**
---

## 8. What is the use of the `implements` keyword?
The `implements` keyword is used to indicate that a class is implementing the methods defined in an interface.

#### **[⬆ Back to Top](#level--medium)**
---

## 9. What is the use of the `@Override` annotation?
The `@Override` annotation indicates that a method is overriding a method from a superclass. It helps in compile-time checking and readability.

#### **[⬆ Back to Top](#level--medium)**
---

## 10. What is the difference between a shallow copy and a deep copy?
- **Shallow Copy**: Copies the object's reference, not the object itself. Changes to the copied object reflect in the original object.
- **Deep Copy**: Copies the object and the objects it references. Changes to the copied object do not affect the original object.

#### **[⬆ Back to Top](#level--medium)**
---

## 11. What is the use of the `clone()` method?
The `clone()` method creates a shallow copy of the object. It must be overridden and implemented to support deep copying.

#### **[⬆ Back to Top](#level--medium)**
---

## 12. What is the difference between the `equals()` method and the `==` operator?
- **equals() Method**: Compares the value/content of two objects.
- **== Operator**: Compares the reference/address of two objects.

#### **[⬆ Back to Top](#level--medium)**
---

## 13. What is the use of the `hashCode()` method?
The `hashCode()` method returns an integer hash code value for the object, used in hashing-based collections like `HashMap`, `HashSet`, etc.

#### **[⬆ Back to Top](#level--medium)**
---

## 14. What is the difference between a `HashMap` and a `TreeMap`?
- **HashMap**: Unordered collection based on hash codes.
- **TreeMap**: Ordered collection based on natural ordering or a custom comparator.

#### **[⬆ Back to Top](#level--medium)**
---

## 15. What is the difference between a `HashSet` and a `TreeSet`?
- **HashSet**: Unordered collection of unique elements.
- **TreeSet**: Ordered collection of unique elements based on natural ordering or a custom comparator.

#### **[⬆ Back to Top](#level--medium)**
---

## 16. What is the difference between a `List` and a `Set`?
- **List**: Ordered collection that allows duplicates.
- **Set**: Unordered collection that does not allow duplicates.

#### **[⬆ Back to Top](#level--medium)**
---

## 17. What is the difference between an `ArrayList` and a `LinkedList`?
- **ArrayList**: Backed by a dynamic array, provides fast random access.
- **LinkedList**: Backed by a doubly-linked list, provides fast insertions and deletions.

#### **[⬆ Back to Top](#level--medium)**
---

## 18. What is the difference between a `Vector` and an `ArrayList`?
- **Vector**: Synchronized, thread-safe, and slow.
- **ArrayList**: Non-synchronized, not thread-safe, and fast.

#### **[⬆ Back to Top](#level--medium)**
---

## 19. What is the difference between a `Stack` and a `Queue`?
- **Stack**: LIFO (Last-In-First-Out) structure.
- **Queue**: FIFO (First-In-First-Out) structure.

#### **[⬆ Back to Top](#level--medium)**
---

## 20. What is the difference between a `PriorityQueue` and a `LinkedList`?
- **PriorityQueue**: Orders elements based on their natural ordering or a custom comparator.
- **LinkedList**: Orders elements in insertion order.

#### **[⬆ Back to Top](#level--medium)**
---

## 21. What is the use of the `Collections` class?
The `Collections` class provides utility methods for collections, such as sorting, searching, and synchronization.

#### **[⬆ Back to Top](#level--medium)**
---

## 22. What is the use of the `Arrays` class?
The `Arrays` class provides utility methods for arrays, such as sorting, searching, and converting arrays to lists.

#### **[⬆ Back to Top](#level--medium)**
---

## 23. What is the use of the `Comparator` interface?
The `Comparator` interface defines a custom order for objects. It can be used to sort collections based on multiple criteria.

#### **[⬆ Back to Top](#level--medium)**
---

## 24. What is the use of the `Comparable` interface?
The `Comparable` interface defines the natural order for objects. It provides a `compareTo` method to compare objects.

#### **[⬆ Back to Top](#level--medium)**
---

## 25. What is the difference between the `Iterator` and the `ListIterator`?
- **Iterator**: Can traverse elements in one direction.
- **ListIterator**: Can traverse elements in both directions and modify the list during iteration.

#### **[⬆ Back to Top](#level--medium)**
---

## 26. What is the use of the `forEach()` method?
The `forEach()` method performs an action for each element of the collection. It is a convenient way to iterate over collections.

#### **[⬆ Back to Top](#level--medium)**
---

## 27. What is the use of the `stream()` method?
The `stream()` method converts a collection into a Stream for functional-style operations, such as filtering, mapping, and reducing.

#### **[⬆ Back to Top](#level--medium)**
---

## 28. What is the use of the `filter()` method?
The `filter()` method is used to select elements from a Stream based on a given predicate.

#### **[⬆ Back to Top](#level--medium)**
---

## 29. What is the use of the `map()` method?
The `map()` method transforms elements in a Stream by applying a given function to each element.

#### **[⬆ Back to Top](#level--medium)**
---

## 30. What is the use of the `reduce()` method?
The `reduce()` method combines elements of a Stream into a single result using a given binary operator.

#### **[⬆ Back to Top](#level--medium)**
---

## 31. What is the use of the `collect()` method?
The `collect()` method accumulates elements of a Stream into a collection or other result type.

#### **[⬆ Back to Top](#level--medium)**
---

## 32. What is the use of the `Optional` class?
The `Optional` class is a container object which may or may not contain a non-null value. It helps in avoiding null checks and NullPointerException.

#### **[⬆ Back to Top](#level--medium)**
---

## 33. What is the use of the lambda expression?
Lambda expressions provide a concise way to implement functional interfaces using an expression or block of code.

#### **[⬆ Back to Top](#level--medium)**
---

## 34. What is the use of the method reference?
Method references provide a way to refer to methods or constructors without invoking them. They are compact and readable.

#### **[⬆ Back to Top](#level--medium)**
---

## 35. What is the use of the functional interface?
A functional interface is an interface with a single abstract method. It can be used as the assignment target for lambda expressions or method references.

#### **[⬆ Back to Top](#level--medium)**
---

## 36. What is the use of the default method in an interface?
Default methods allow interfaces to have methods with default implementations. They enable interfaces to evolve without breaking existing implementations.

#### **[⬆ Back to Top](#level--medium)**
---

## 37. What is the use of the static method in an interface?
Static methods in interfaces provide utility or helper methods that are relevant to the interface but do not require an instance.

#### **[⬆ Back to Top](#level--medium)**
---

## 38. What is the use of the Stream API?
The Stream API provides a functional approach to processing collections of objects. It supports operations like filtering, mapping, and reducing.

#### **[⬆ Back to Top](#level--medium)**
---

## 39. What is the use of the Date and Time API?
The Date and Time API provides a comprehensive and flexible way to handle date and time. It includes classes like `LocalDate`, `LocalTime`, and `ZonedDateTime`.

#### **[⬆ Back to Top](#level--medium)**
---

## 40. What is the use of the `LocalDate` class?
The `LocalDate` class represents a date without time, such as 2023-10-31. It provides methods to manipulate dates and perform date arithmetic.

#### **[⬆ Back to Top](#level--medium)**
---

## 41. What is the use of the `LocalTime` class?
The `LocalTime` class represents a time without date, such as 10:15:30. It provides methods to manipulate times and perform time arithmetic.

#### **[⬆ Back to Top](#level--medium)**
---

## 42. What is the use of the `LocalDateTime` class?
The `LocalDateTime` class represents a date and time without time zone, such as 2023-10-31T10:15:30. It provides methods to manipulate date-time and perform date-time arithmetic.

#### **[⬆ Back to Top](#level--medium)**
---

## 43. What is the use of the `ZonedDateTime` class?
The `ZonedDateTime` class represents a date and time with a time zone, such as 2023-10-31T10:15:30+01:00[Europe/Paris]. It provides methods to handle time zones and perform date-time arithmetic.

#### **[⬆ Back to Top](#level--medium)**
---

## 44. What is the use of the `Instant` class?
The `Instant` class represents a point in time in UTC, such as 2023-10-31T10:15:30Z. It is useful for timestamping events and measuring time intervals.

#### **[⬆ Back to Top](#level--medium)**
---

## 45. What is the use of the `Duration` class?
The `Duration` class represents a time-based amount of time, such as "34.5 seconds". It is useful for measuring time intervals and performing date-time arithmetic.

#### **[⬆ Back to Top](#level--medium)**
---

## 46. What is the use of the `Period` class?
The `Period` class represents a date-based amount of time, such as "2 years, 3 months, and 4 days". It is useful for manipulating dates and performing date arithmetic.

#### **[⬆ Back to Top](#level--medium)**
---

## 47. What is the use of the `DateTimeFormatter` class?
The `DateTimeFormatter` class provides a way to format and parse date-time objects. It supports various date-time patterns and locales.

#### **[⬆ Back to Top](#level--medium)**
---

## 48. What is the use of the `DateTimeParseException`?
The `DateTimeParseException` is an exception thrown when a date-time string cannot be parsed according to the specified format.

#### **[⬆ Back to Top](#level--medium)**
---

## 49. What is the use of the `ChronoUnit` class?
The `ChronoUnit` class provides units of time, such as DAYS, HOURS, and MINUTES. It is used to perform date-time arithmetic and measure time intervals.

#### **[⬆ Back to Top](#level--medium)**
---

## 50. What is the use of the `ChronoField` class?
The `ChronoField` class provides fields of date-time, such as YEAR, MONTH_OF_YEAR, and DAY_OF_MONTH. It is used to manipulate date-time objects.

#### **[⬆ Back to Top](#level--medium)**
---

## 51. What is the use of the `TemporalAdjusters` class?
The `TemporalAdjusters` class provides common date-time adjusters, such as "first day of month" and "last day of year". It is used to manipulate date-time objects.

#### **[⬆ Back to Top](#level--medium)**
---

## 52. What is the use of the `TemporalQueries` class?
The `TemporalQueries` class provides common queries for date-time objects, such as "zone" and "precision". It is used to extract information from date-time objects.

#### **[⬆ Back to Top](#level--medium)**
---

## 53. What is the use of the `TemporalAmount` interface?
The `TemporalAmount` interface represents an amount of time, such as a `Duration` or `Period`. It is used to perform date-time arithmetic.

#### **[⬆ Back to Top](#level--medium)**
---

## 54. What is the use of the `TemporalUnit` interface?
The `TemporalUnit` interface represents a unit of time, such as DAYS, HOURS, and MINUTES. It is used to perform date-time arithmetic.

#### **[⬆ Back to Top](#level--medium)**
---

## 55. What is the use of the `TemporalField` interface?
The `TemporalField` interface represents a field of date-time, such as YEAR, MONTH_OF_YEAR, and DAY_OF_MONTH. It is used to manipulate date-time objects.

#### **[⬆ Back to Top](#level--medium)**
---

## 56. What is the use of the `TemporalAccessor` interface?
The `TemporalAccessor` interface provides read-only access to date-time objects. It is used to extract information from date-time objects.

#### **[⬆ Back to Top](#level--medium)**
---

## 57. What is the use of the `TemporalAdjuster` interface?
The `TemporalAdjuster` interface provides a way to manipulate date-time objects. It is used to adjust date-time objects according to specific rules.

#### **[⬆ Back to Top](#level--medium)**
---

## 58. What is the use of the `TemporalQuery` interface?
The `TemporalQuery` interface provides a way to query information from date-time objects. It is used to extract specific information from date-time objects.

#### **[⬆ Back to Top](#level--medium)**
---

## 59. What is the use of the `Temporal` interface?
The `Temporal` interface represents a date-time object with fields and units. It provides methods to manipulate and query date-time objects.

#### **[⬆ Back to Top](#level--medium)**
---

## 60. What is the use of the `TemporalAmount` implementation?
The `TemporalAmount` implementation, such as `Duration` and `Period`, represents an amount of time. It is used to perform date-time arithmetic.

#### **[⬆ Back to Top](#level--medium)**
---

## 61. What is the use of the `TemporalUnit` implementation?
The `TemporalUnit` implementation, such as `ChronoUnit`, represents a unit of time. It is used to perform date-time arithmetic.

#### **[⬆ Back to Top](#level--medium)**
---

## 62. What is the use of the `TemporalField` implementation?
The `TemporalField` implementation, such as `ChronoField`, represents a field of date-time. It is used to manipulate date-time objects.

#### **[⬆ Back to Top](#level--medium)**
---

## 63. What is the use of the `TemporalAccessor` implementation?
The `TemporalAccessor` implementation provides read-only access to date-time objects. It is used to extract information from date-time objects.

#### **[⬆ Back to Top](#level--medium)**
---

## 64. What is the use of the `TemporalAdjuster` implementation?
The `TemporalAdjuster` implementation, such as `TemporalAdjusters`, provides a way to manipulate date-time objects. It is used to adjust date-time objects according to specific rules.

#### **[⬆ Back to Top](#level--medium)**
---

## 65. What is the use of the `TemporalQuery` implementation?
The `TemporalQuery` implementation, such as `TemporalQueries`, provides a way to query information from date-time objects. It is used to extract specific information from date-time objects.

#### **[⬆ Back to Top](#level--medium)**
---

## 66. What is the use of the `Temporal` implementation?
The `Temporal` implementation represents a date-time object with fields and units. It provides methods to manipulate and query date-time objects.

#### **[⬆ Back to Top](#level--medium)**
---

## 67. What is the use of the Stream API for parallel processing?
The Stream API for parallel processing allows processing elements concurrently, leveraging multi-core processors to improve performance.

#### **[⬆ Back to Top](#level--medium)**
---

## 68. What is the use of the `CompletableFuture` class?
The `CompletableFuture` class is used to write asynchronous, non-blocking code. It provides methods to compose and combine multiple asynchronous tasks.

#### **[⬆ Back to Top](#level--medium)**
---

## 69. What is the use of the `ExecutorService` interface?
The `ExecutorService` interface provides methods to manage and control thread execution. It supports tasks submission, shutdown, and lifecycle management.

#### **[⬆ Back to Top](#level--medium)**
---

## 70. What is the use of the `Executors` class?
The `Executors` class provides factory methods for creating thread pools and other executor services.

#### **[⬆ Back to Top](#level--medium)**
---

## 71. What is the use of the `ScheduledExecutorService` interface?
The `ScheduledExecutorService` interface extends `ExecutorService` and provides methods to schedule tasks to run after a delay or periodically.

#### **[⬆ Back to Top](#level--medium)**
---

## 72. What is the use of the `Callable` interface?
The `Callable` interface represents a task that returns a result and may throw an exception. It is used with `ExecutorService` for concurrent execution.

#### **[⬆ Back to Top](#level--medium)**
---

## 73. What is the use of the `Future` interface?
The `Future` interface represents the result of an asynchronous computation. It provides methods to check if the computation is complete and retrieve the result.

#### **[⬆ Back to Top](#level--medium)**
---

## 74. What is the use of the `FutureTask` class?
The `FutureTask` class is a concrete implementation of `Future` and `Runnable`. It can be used to wrap a `Callable` or `Runnable` and execute it asynchronously.

#### **[⬆ Back to Top](#level--medium)**
---

## 75. What is the use of the `CountDownLatch` class?
The `CountDownLatch` class is used to synchronize one or more threads by allowing them to wait until a set of operations being performed by other threads completes.

#### **[⬆ Back to Top](#level--medium)**
---

## 76. What is the use of the `CyclicBarrier` class?
The `CyclicBarrier` class is used to synchronize a fixed number of threads by allowing them to wait until all threads reach a common barrier point.

#### **[⬆ Back to Top](#level--medium)**
---

## 77. What is the use of the `Semaphore` class?
The `Semaphore` class is used to control access to a shared resource by allowing a limited number of threads to acquire a permit and access the resource.

#### **[⬆ Back to Top](#level--medium)**
---

## 78. What is the use of the `ReentrantLock` class?
The `ReentrantLock` class is a reentrant mutual exclusion lock with the same basic behavior as the implicit monitor lock. It provides more flexibility and features.

#### **[⬆ Back to Top](#level--medium)**
---

## 79. What is the use of the `ReadWriteLock` interface?
The `ReadWriteLock` interface maintains a pair of associated locks, one for read-only operations and one for write operations. It improves performance by allowing multiple readers but only one writer.

#### **[⬆ Back to Top](#level--medium)**
---

## 80. What is the use of the `StampedLock` class?
The `StampedLock` class is a lock with three modes for controlling read/write access: Writing, Reading, and Optimistic Reading. It provides better performance for high-concurrency scenarios.

#### **[⬆ Back to Top](#level--medium)**
---

## 81. What is the use of the `Condition` interface?
The `Condition` interface provides a means for threads to wait until a specific condition is met. It is used in combination with `Lock` implementations.

#### **[⬆ Back to Top](#level--medium)**
---

## 82. What is the use of the `BlockingQueue` interface?
The `BlockingQueue` interface represents a thread-safe queue that supports operations that wait for the queue to become non-empty or non-full.

#### **[⬆ Back to Top](#level--medium)**
---

## 83. What is the use of the `LinkedBlockingQueue` class?
The `LinkedBlockingQueue` class is a bounded blocking queue backed by linked nodes. It supports an optional capacity bound and provides thread-safe operations.

#### **[⬆ Back to Top](#level--medium)**
---

## 84. What is the use of the `PriorityBlockingQueue` class?
The `PriorityBlockingQueue` class is an unbounded blocking queue that uses the same ordering rules as `PriorityQueue` and provides thread-safe operations.

#### **[⬆ Back to Top](#level--medium)**
---

## 85. What is the use of the `DelayQueue` class?
The `DelayQueue` class is a blocking queue in which elements can only be taken when their delay has expired. It is used for scheduling tasks.

#### **[⬆ Back to Top](#level--medium)**
---

## 86. What is the use of the `SynchronousQueue` class?
The `SynchronousQueue` class is a blocking queue in which each insert operation must wait for a corresponding remove operation by another thread. It is used for handoff designs.

#### **[⬆ Back to Top](#level--medium)**
---

## 87. What is the use of the `TransferQueue` interface?

The `TransferQueue` interface is a specialized type of `BlockingQueue` that supports an additional method called `transfer`. This method allows for handoff of elements from producers to consumers directly, blocking until the element is consumed. It is particularly useful in scenarios where the producer wants to ensure that the consumer has received the message before moving on.

#### **[⬆ Back to Top](#level--medium)**
---

## 88. What is the use of the `LinkedTransferQueue` class?

The `LinkedTransferQueue` class is an implementation of the `TransferQueue` interface. It provides an unbounded, thread-safe, and highly performant queue with the ability to transfer elements directly from producers to consumers. It supports both waiting and non-waiting operations, making it versatile for many concurrent programming scenarios.

#### **[⬆ Back to Top](#level--medium)**
---

## 89. What is the use of the `ConcurrentMap` interface?

The `ConcurrentMap` interface represents a thread-safe version of the `Map` interface. It provides atomic operations like `putIfAbsent`, `remove`, and `replace`, which are essential for safe concurrent access and modifications to the map. This helps in avoiding race conditions without needing explicit synchronization.

#### **[⬆ Back to Top](#level--medium)**
---

## 90. What is the use of the `ConcurrentHashMap` class?

The `ConcurrentHashMap` class is an implementation of the `ConcurrentMap` interface. It provides a thread-safe, high-performance map that allows concurrent read and write operations. Internally, it uses a finer-grained locking mechanism (segment locks) to improve performance compared to a synchronized `HashMap`.

#### **[⬆ Back to Top](#level--medium)**
---

## 91. What is the use of the `CopyOnWriteArrayList` class?

The `CopyOnWriteArrayList` class is a thread-safe variant of `ArrayList` where all mutative operations (like `add`, `set`, `remove`) are implemented by creating a new copy of the underlying array. This makes it suitable for scenarios where read operations vastly outnumber write operations, as reads do not block and are very fast.

#### **[⬆ Back to Top](#level--medium)**
---

## 92. What is the use of the `CopyOnWriteArraySet` class?

The `CopyOnWriteArraySet` class is a thread-safe variant of `Set` backed by a `CopyOnWriteArrayList`. It provides similar benefits, making it ideal for use cases with many read operations and few writes. This ensures that iteration and read operations are fast and do not encounter concurrency issues.

#### **[⬆ Back to Top](#level--medium)**
---

## 93. What is the use of the `ConcurrentSkipListMap` class?

The `ConcurrentSkipListMap` class is a thread-safe implementation of a `NavigableMap` based on a skip list. It maintains elements in a sorted order and allows concurrent access and updates. This makes it suitable for applications requiring a sorted map with high concurrency performance.

#### **[⬆ Back to Top](#level--medium)**
---

## 94. What is the use of the `ConcurrentSkipListSet` class?

The `ConcurrentSkipListSet` class is a thread-safe implementation of a `NavigableSet` based on a skip list. Like `ConcurrentSkipListMap`, it maintains elements in a sorted order and allows concurrent access and modifications. It is ideal for use cases needing a sorted set with high concurrency.

#### **[⬆ Back to Top](#level--medium)**
---

## 95. What is the use of the `AtomicInteger` class?

The `AtomicInteger` class provides an integer value that can be updated atomically. It supports atomic operations like `incrementAndGet`, `decrementAndGet`, `addAndGet`, and `compareAndSet`, making it useful for counters and other numeric operations where thread safety is required.

```java
import java.util.concurrent.atomic.AtomicInteger;

public class AtomicIntegerExample {
    private AtomicInteger counter = new AtomicInteger(0);

    public void increment() {
        counter.incrementAndGet();
    }

    public int get() {
        return counter.get();
    }
}
```
#### **[⬆ Back to Top](#level--medium)**
---

## 96. What is the use of the `AtomicLong` class?

The `AtomicLong` class provides a long value that can be updated atomically. It offers similar atomic operations as `AtomicInteger`, making it useful for large numeric values requiring thread-safe updates.

```java
import java.util.concurrent.atomic.AtomicLong;

public class AtomicLongExample {
    private AtomicLong counter = new AtomicLong(0);

    public void increment() {
        counter.incrementAndGet();
    }

    public long get() {
        return counter.get();
    }
}
```
#### **[⬆ Back to Top](#level--medium)**
---

## 97. What is the use of the `AtomicReference` class?

The `AtomicReference` class offers a way to atomically update reference variables. It provides atomic operations like `compareAndSet`, `getAndSet`, and `weakCompareAndSet`, making it useful for implementing lock-free data structures or managing volatile references safely.

```java
import java.util.concurrent.atomic.AtomicReference;

public class AtomicReferenceExample {
    private AtomicReference<String> reference = new AtomicReference<>("initial");

    public void setReference(String newValue) {
        reference.set(newValue);
    }

    public String getReference() {
        return reference.get();
    }
}
```
#### **[⬆ Back to Top](#level--medium)**
---

## 98. What is the use of the `AtomicBoolean` class?

The `AtomicBoolean` class provides an atomic boolean value. It supports atomic operations like `compareAndSet`, `getAndSet`, and `get`, making it useful for flags and state management in a thread-safe way.

```java
import java.util.concurrent.atomic.AtomicBoolean;

public class AtomicBooleanExample {
    private AtomicBoolean flag = new AtomicBoolean(false);

    public void setFlag(boolean newValue) {
        flag.set(newValue);
    }

    public boolean getFlag() {
        return flag.get();
    }
}
```
#### **[⬆ Back to Top](#level--medium)**
---

## 99. What is the use of the `AtomicIntegerArray` class?

The `AtomicIntegerArray` class provides an array of integers where each element can be updated atomically. It supports atomic operations on array elements like `getAndIncrement`, `compareAndSet`, and `get`, making it useful for applications requiring thread-safe access to an array of integers.

```java
import java.util.concurrent.atomic.AtomicIntegerArray;

public class AtomicIntegerArrayExample {
    private AtomicIntegerArray array = new AtomicIntegerArray(10);

    public void incrementElement(int index) {
        array.incrementAndGet(index);
    }

    public int getElement(int index) {
        return array.get(index);
    }
}
```
#### **[⬆ Back to Top](#level--medium)**
---

## 100. What is the use of the `AtomicLongArray` class?

The `AtomicLongArray` class provides an array of long values where each element can be updated atomically. It supports atomic operations on array elements similar to `AtomicIntegerArray`, making it useful for applications requiring thread-safe access to an array of long values.

```java
import java.util.concurrent.atomic.AtomicLongArray;

public class AtomicLongArrayExample {
    private AtomicLongArray array = new AtomicLongArray(10);

    public void incrementElement(int index) {
        array.incrementAndGet(index);
    }

    public long getElement(int index) {
        return array.get(index);
    }
}
```

These classes and interfaces are essential tools for developing concurrent applications in Java, providing thread-safe data structures and atomic operations to avoid race conditions and ensure data integrity.

#### **[⬆ Back to Top](#level--medium)**
---

# Medium Java Interview Questions and Answers

## 1. Explain the concept of memory leaks in Java.

Memory leaks in Java occur when objects that are no longer needed are still referenced, preventing the garbage collector from reclaiming their memory. This can lead to increased memory usage, reduced performance, and eventually, `OutOfMemoryError`.

#### **[⬆ Back to Top](#level--hard)**
---

## 2. How do you troubleshoot memory leaks in Java?

To troubleshoot memory leaks in Java:
1. **Use Profilers**: Tools like VisualVM, JProfiler, or YourKit can help identify memory leaks.
2. **Heap Dumps**: Analyze heap dumps using tools like Eclipse MAT.
3. **Logging**: Implement logging to track object creation and destruction.
4. **Code Review**: Ensure proper release of resources.

#### **[⬆ Back to Top](#level--hard)**
---

## 3. What are the different types of class loaders in Java?

Java has several types of class loaders:

| Class Loader        | Description                                                            |
|---------------------|------------------------------------------------------------------------|
| **Bootstrap Class Loader** | Loads core Java classes (rt.jar).                                |
| **Extension Class Loader** | Loads classes from the `ext` directory.                          |
| **System/Application Class Loader** | Loads classes from the application's classpath.         |
| **Custom Class Loaders** | User-defined class loaders for specific needs.                     |

#### **[⬆ Back to Top](#level--hard)**
---

## 4. How does the class loading mechanism work in Java?

The class loading mechanism in Java follows the delegation model:
1. **Bootstrap Class Loader**: Loads core classes.
2. **Extension Class Loader**: Loads classes from the Java extension directory.
3. **System/Application Class Loader**: Loads classes from the classpath.
4. **Custom Class Loaders**: Can be used to load classes from specific locations or formats.

#### **[⬆ Back to Top](#level--hard)**
---

## 5. What is the use of the Reflection API in Java?

The Reflection API in Java allows inspection and manipulation of classes, methods, and fields at runtime. It is used for:
- **Dynamic Class Loading**: Loading classes at runtime.
- **Method Invocation**: Invoking methods dynamically.
- **Field Manipulation**: Accessing and modifying fields dynamically.

#### **[⬆ Back to Top](#level--hard)**
---

## 6. How do you create thread-safe code in Java?

To create thread-safe code in Java:
- **Synchronized Blocks/Methods**: Use `synchronized` keyword.
- **Locks**: Use `java.util.concurrent.locks` package.
- **Atomic Variables**: Use `java.util.concurrent.atomic` package.
- **Concurrent Collections**: Use classes from `java.util.concurrent` package.

#### **[⬆ Back to Top](#level--hard)**
---

## 7. What is the difference between synchronized and volatile keywords?

| **Synchronized** | **Volatile** |
|------------------|--------------|
| Ensures mutual exclusion. | Ensures visibility of changes. |
| Used to lock methods/blocks. | Used with variables. |
| More overhead due to locking. | Less overhead. |
| Prevents thread interference. | Does not prevent thread interference. |

#### **[⬆ Back to Top](#level--hard)**
---

## 8. What are the best practices for exception handling in Java?

Best practices for exception handling in Java:
- **Catch Specific Exceptions**: Avoid catching generic exceptions.
- **Use Finally Blocks**: Ensure resources are released.
- **Avoid Swallowing Exceptions**: Always handle exceptions appropriately.
- **Provide Meaningful Messages**: Include informative messages in exceptions.
- **Custom Exceptions**: Use custom exceptions for specific error scenarios.

#### **[⬆ Back to Top](#level--hard)**
---

## 9. What is the use of the java.lang.instrument package?

The `java.lang.instrument` package provides services that allow an agent to instrument programs running on the JVM. It is used for:
- **Profiling**: Monitoring application performance.
- **Bytecode Manipulation**: Modifying bytecode at runtime.
- **Instrumentation**: Adding custom behavior to classes.

#### **[⬆ Back to Top](#level--hard)**
---

## 10. How do you use the Instrumentation API in Java?

To use the Instrumentation API:
1. **Create an Agent**: Implement a class with a `premain` method.
2. **Manifest File**: Specify the agent class in the JAR manifest.
3. **Attach Agent**: Attach the agent to the JVM using the `-javaagent` option.

#### **[⬆ Back to Top](#level--hard)**
---

Example of an agent:

```java
public class MyAgent {
    public static void premain(String agentArgs, Instrumentation inst) {
        // Instrumentation code
    }
}
```

Manifest file entry:
```
Premain-Class: MyAgent
```

#### **[⬆ Back to Top](#level--hard)**
---

## 11. Explain the concept of Java Memory Model (JMM).

The Java Memory Model (JMM) defines how threads interact through memory and what behaviors are allowed in concurrent execution. It provides:
- **Visibility Guarantees**: Ensures changes made by one thread are visible to others.
- **Ordering Guarantees**: Defines how operations are ordered, ensuring consistency.

**Example**:
```java
public class SharedObject {
    private int counter = 0;

    public synchronized void increment() {
        counter++;
    }

    public synchronized int getCounter() {
        return counter;
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---

## 12. What is the use of the Unsafe class in Java?

The `Unsafe` class provides low-level operations, such as:
- **Memory Access**: Allocate and deallocate memory.
- **Atomic Operations**: Perform atomic operations on fields.
- **Thread Control**: Park and unpark threads.

**Example**:
```java
import sun.misc.Unsafe;
import java.lang.reflect.Field;

public class UnsafeExample {
    private static final Unsafe unsafe;

    static {
        try {
            Field f = Unsafe.class.getDeclaredField("theUnsafe");
            f.setAccessible(true);
            unsafe = (Unsafe) f.get(null);
        } catch (Exception e) {
            throw new Error(e);
        }
    }

    private long value;

    public void setValue(long value) {
        unsafe.putLong(this, unsafe.objectFieldOffset(UnsafeExample.class.getDeclaredField("value")), value);
    }

    public long getValue() {
        return unsafe.getLong(this, unsafe.objectFieldOffset(UnsafeExample.class.getDeclaredField("value")));
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---

## 13. How do you perform dynamic class loading in Java?

Dynamic class loading allows loading classes at runtime using `Class.forName()` or custom class loaders.

**Example**:
```java
public class DynamicClassLoading {
    public static void main(String[] args) {
        try {
            Class<?> clazz = Class.forName("com.example.MyClass");
            Object instance = clazz.getDeclaredConstructor().newInstance();
            System.out.println("Class loaded and instance created: " + instance);
        } catch (Exception e) {
            e.printStackTrace();
        }
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---

## 14. What is the use of the Proxy class in Java?

The `Proxy` class in Java provides a way to create dynamic proxy classes and instances. It is used for:
- **Interception**: Intercept method calls on an interface.
- **Dynamic Behavior**: Add behavior to methods at runtime.

**Example**:
```java
import java.lang.reflect.InvocationHandler;
import java.lang.reflect.Method;
import java.lang.reflect.Proxy;

interface MyInterface {
    void sayHello();
}

class MyInvocationHandler implements InvocationHandler {
    private final Object target;

    MyInvocationHandler(Object target) {
        this.target = target;
    }

    @Override
    public Object invoke(Object proxy, Method method, Object[] args) throws Throwable {
        System.out.println("Before method call");
        Object result = method.invoke(target, args);
        System.out.println("After method call");
        return result;
    }
}

class MyClass implements MyInterface {
    public void sayHello() {
        System.out.println("Hello, World!");
    }
}

public class ProxyExample {
    public static void main(String[] args) {
        MyClass myClass = new MyClass();
        MyInterface proxyInstance = (MyInterface) Proxy.newProxyInstance(
                MyClass.class.getClassLoader(),
                new Class[]{MyInterface.class},
                new MyInvocationHandler(myClass)
        );
        proxyInstance.sayHello();
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---

## 15. What is the difference between dynamic proxy and static proxy?

| **Dynamic Proxy** | **Static Proxy** |
|-------------------|------------------|
| Created at runtime. | Created at compile time. |
| Uses `java.lang.reflect.Proxy`. | Uses a manually written class. |
| Flexible, can proxy any interface. | Limited to specific interfaces. |
| Less boilerplate code. | More boilerplate code. |

#### **[⬆ Back to Top](#level--hard)**
---

## 16. How do you implement dynamic proxies in Java?

Dynamic proxies are implemented using `java.lang.reflect.Proxy` and `InvocationHandler`.

**Example**:
```java
import java.lang.reflect.InvocationHandler;
import java.lang.reflect.Method;
import java.lang.reflect.Proxy;

interface Service {
    void perform();
}

class ServiceImpl implements Service {
    public void perform() {
        System.out.println("Performing service...");
    }
}

class ServiceInvocationHandler implements InvocationHandler {
    private final Object target;

    ServiceInvocationHandler(Object target) {
        this.target = target;
    }

    @Override
    public Object invoke(Object proxy, Method method, Object[] args) throws Throwable {
        System.out.println("Before method call");
        Object result = method.invoke(target, args);
        System.out.println("After method call");
        return result;
    }
}

public class DynamicProxyExample {
    public static void main(String[] args) {
        ServiceImpl service = new ServiceImpl();
        Service proxyInstance = (Service) Proxy.newProxyInstance(
                ServiceImpl.class.getClassLoader(),
                new Class[]{Service.class},
                new ServiceInvocationHandler(service)
        );
        proxyInstance.perform();
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---

## 17. What is the use of the java.lang.invoke package?

The `java.lang.invoke` package provides low-level primitives for performing dynamic operations, including:
- **Method Handles**: Dynamically invoke methods.
- **Lambda Metafactory**: Create lambda expressions dynamically.
- **Call Site**: Optimize method calls.

#### **[⬆ Back to Top](#level--hard)**
---

## 18. What is the use of the MethodHandles class?

The `MethodHandles` class provides factory methods for creating method handles, which are used to invoke methods dynamically.

**Example**:
```java
import java.lang.invoke.MethodHandle;
import java.lang.invoke.MethodHandles;
import java.lang.invoke.MethodType;

public class MethodHandlesExample {
    public static void main(String[] args) throws Throwable {
        MethodHandles.Lookup lookup = MethodHandles.lookup();
        MethodType methodType = MethodType.methodType(void.class);
        MethodHandle methodHandle = lookup.findVirtual(MethodHandlesExample.class, "sayHello", methodType);
        MethodHandlesExample example = new MethodHandlesExample();
        methodHandle.invoke(example);
    }

    public void sayHello() {
        System.out.println("Hello from MethodHandles!");
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---

## 19. How do you perform bytecode manipulation in Java?

Bytecode manipulation can be performed using libraries like ASM, Javassist, or ByteBuddy. These libraries allow modifying the bytecode of classes at runtime or compile time.

**Example with ASM**:
```java
import org.objectweb.asm.*;

public class BytecodeManipulationExample {
    public static void main(String[] args) throws Exception {
        ClassReader classReader = new ClassReader("com.example.MyClass");
        ClassWriter classWriter = new ClassWriter(ClassWriter.COMPUTE_FRAMES | ClassWriter.COMPUTE_MAXS);
        classReader.accept(new ClassVisitor(Opcodes.ASM7, classWriter) {
            @Override
            public void visitMethod(int access, String name, String descriptor, String signature, String[] exceptions) {
                if (name.equals("myMethod")) {
                    System.out.println("Modifying method: " + name);
                }
                super.visitMethod(access, name, descriptor, signature, exceptions);
            }
        }, 0);
        byte[] modifiedClass = classWriter.toByteArray();
        // Load the modified class and use it
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---

## 20. What is the use of the ASM library in Java?

The ASM library is used for:
- **Bytecode Analysis**: Reading and analyzing bytecode.
- **Bytecode Manipulation**: Modifying bytecode.
- **Dynamic Class Generation**: Creating classes at runtime.

#### **[⬆ Back to Top](#level--hard)**
---

## 21. How do you perform code generation in Java?

Code generation can be performed using libraries like Javassist, ASM, or tools like annotation processors.

**Example with Javassist**:
```java
import javassist.*;

public class CodeGenerationExample {
    public static void main(String[] args) throws Exception {
        ClassPool pool = ClassPool.getDefault();
        CtClass cc = pool.makeClass("com.example.GeneratedClass");
        CtMethod method = CtNewMethod.make("public void sayHello() { System.out.println(\"Hello from generated class!\"); }", cc);
        cc.addMethod(method);
        Class<?> generatedClass = cc.toClass();
        Object instance = generatedClass.getDeclaredConstructor().newInstance();
        generatedClass.getMethod("sayHello").invoke(instance);
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---

## 22. What is the use of the Javassist library in Java?

Javassist is used for:
- **Bytecode Manipulation**: Modifying existing classes or creating new ones.
- **Dynamic Proxy Generation**: Creating proxies for classes.
- **Code Injection**: Adding code to methods.

#### **[⬆ Back to Top](#level--hard)**
---

## 23. How do you use the Java Compiler API?

The Java Compiler API (`javax.tools`) allows programmatic compilation of Java source files.

**Example**:
```java
import javax.tools.JavaCompiler;
import javax.tools.ToolProvider;
import java.io.File;

public class CompilerAPIExample {
    public static void main(String[] args) {
        JavaCompiler compiler = ToolProvider.getSystemJavaCompiler();
        int result = compiler.run(null, null, null, "src/com/example/MyClass.java");
        System.out.println("Compilation result: " + result);
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---

## 24. What is the use of the javax.tools package?

The `javax.tools` package provides interfaces for tools like compilers and documentation generators. It is used for:
- **Compilation**: Compiling Java source files programmatically.
- **Documentation**: Generating documentation from source files.

#### **[⬆ Back to Top](#level--hard)**
---

## 25. How do you perform annotation processing in Java?

Annotation processing is performed using the `javax.annotation.processing` package. Create an annotation processor by extending `AbstractProcessor`.

**Example**:
```java
import javax.annotation.processing.*;
import javax.lang.model.SourceVersion;
import javax.lang.model.element.Element;
import javax.lang.model.element.TypeElement;
import java.util.Set;

@SupportedAnnotationTypes("com.example.MyAnnotation")
@SupportedSourceVersion(SourceVersion.RELEASE_8)
public class MyAnnotationProcessor extends AbstractProcessor {

    @Override
    public boolean process(Set<? extends TypeElement> annotations, RoundEnvironment roundEnv) {
        for (Element element : roundEnv.getElementsAnnotatedWith(MyAnnotation.class)) {
            // Processing logic
        }
        return true;
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---

## 26. What is the use of the javax.annotation.processing package?

The `javax.annotation.processing` package provides tools for processing annotations at compile time. It is used for:
- **Custom Annotation Processing**: Creating custom annotation processors.
- **Code Generation**: Generating code based on annotations.

#### **[⬆ Back to Top](#level--hard)**
---

## 27. How do you use the Java Reflection API?

The Java Reflection API allows inspecting and manipulating classes, methods, fields, and constructors at runtime.

**Example**:
```java
import java.lang.reflect.Method;

public class ReflectionExample {
    public static void main(String[] args) throws Exception {
        Class<?> clazz = Class.forName("com.example.MyClass");
        Object instance = clazz.getDeclaredConstructor().newInstance();
        Method method = clazz.getDeclaredMethod("myMethod");
        method.invoke(instance);
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---

## 28. What is the use of the java.lang.reflect package?

The `java.lang.reflect` package provides classes and interfaces for obtaining reflective information about classes and objects. This includes:
- **Class**: Represents classes and interfaces.
- **Method**: Represents methods.
- **Field**: Represents fields.
- **Constructor**: Represents constructors.

#### **[⬆ Back to Top](#level--hard)**
---

## 29. How do you perform dependency injection in Java?

Dependency Injection (DI) can be performed using frameworks like Spring or CDI, or manually using constructors or setters.

**Example with Spring**:
```java
import org.springframework.context.ApplicationContext;
import org.springframework.context.annotation.AnnotationConfigApplicationContext;
import org.springframework.stereotype.Component;

@Component
public class MyService {
    public void performService() {
        System.out.println("Service performed");
    }
}

@Component
public class MyComponent {
    private final MyService myService;

    public MyComponent(MyService myService) {
        this.myService = myService;
    }

    public void execute() {
        myService.performService();
    }
}

public class DependencyInjectionExample {
    public static void main(String[] args) {
        ApplicationContext context = new AnnotationConfigApplicationContext("com.example");
        MyComponent component = context.getBean(MyComponent.class);
        component.execute();
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---

## 30. What is the use of the Spring framework in Java?

The Spring framework is used for:
- **Dependency Injection**: Managing dependencies and lifecycle of beans.
- **Aspect-Oriented Programming (AOP)**: Adding cross-cutting concerns.
- **Data Access**: Simplifying database access.
- **Web Applications**: Building web applications with Spring MVC.

#### **[⬆ Back to Top](#level--hard)**
---

## 31. How do you perform aspect-oriented programming in Java?

Aspect-Oriented Programming (AOP) can be performed using frameworks like Spring AOP or AspectJ.

**Example with Spring AOP**:
```java
import org.aspectj.lang.annotation.Aspect;
import org.aspectj.lang.annotation.Before;
import org.springframework.context.annotation.AnnotationConfigApplicationContext;
import org.springframework.stereotype.Component;

@Aspect
@Component
public class LoggingAspect {
    @Before("execution(* com.example.MyService.performService(..))")
    public void logBefore() {
        System.out.println("Before method execution");
    }
}

@Component
public class MyService {
    public void performService() {
        System.out.println("Service performed");
    }
}

public class AOPExample {
    public static void main(String[] args) {
        AnnotationConfigApplicationContext context = new AnnotationConfigApplicationContext("com.example");
        MyService myService = context.getBean(MyService.class);
        myService.performService();
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---

## 32. What is the use of the AspectJ library in Java?

AspectJ is used for:
- **Pure AOP**: Providing a complete and powerful AOP solution.
- **Compile-Time Weaving**: Adding aspects during compilation.
- **Load-Time Weaving**: Adding aspects during class loading.

#### **[⬆ Back to Top](#level--hard)**
---

## 33. How do you use the Java Persistence API (JPA)?

JPA is used for object-relational mapping (ORM) to manage relational data in Java applications.

**Example with Hibernate**:
```java
import javax.persistence.*;

@Entity
public class MyEntity {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;
    private String name;

    // Getters and setters
}

public class JPAExample {
    public static void main(String[] args) {
        EntityManagerFactory emf = Persistence.createEntityManagerFactory("my-persistence-unit");
        EntityManager em = emf.createEntityManager();
        
        em.getTransaction().begin();
        
        MyEntity entity = new MyEntity();
        entity.setName("Test Entity");
        em.persist(entity);
        
        em.getTransaction().commit();
        
        em.close();
        emf.close();
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---

## 34. What is the use of the javax.persistence package?

The `javax.persistence` package provides classes and interfaces for the Java Persistence API (JPA). It is used for:
- **Entity Management**: Managing lifecycle of entities.
- **Querying**: Creating and executing queries.
- **Transaction Management**: Managing transactions.

#### **[⬆ Back to Top](#level--hard)**
---

## 35. How do you perform object-relational mapping in Java?

Object-relational mapping (ORM) can be performed using JPA implementations like Hibernate, EclipseLink, or OpenJPA.

**Example with Hibernate**:
```java
import javax.persistence.*;

@Entity
public class MyEntity {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;
    private String name;

    // Getters and setters
}

public class ORMExample {
    public static void main(String[] args) {
        EntityManagerFactory emf = Persistence.createEntityManagerFactory("my-persistence-unit");
        EntityManager em = emf.createEntityManager();
        
        em.getTransaction().begin();
        
        MyEntity entity = new MyEntity();
        entity.setName("Test Entity");
        em.persist(entity);
        
        em.getTransaction().commit();
        
        em.close();
        emf.close();
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---

## 36. What is the use of the Hibernate framework in Java?

Hibernate is used for:
- **ORM**: Mapping Java objects to database tables.
- **Data Access**: Simplifying database access.
- **Transaction Management**: Managing transactions.
- **Caching**: Improving performance with caching.

#### **[⬆ Back to Top](#level--hard)**
---

## 37. How do you use the Java Servlet API?

The Java Servlet API is used for developing web applications by handling HTTP requests and responses.

**Example**:
```java
import javax.servlet.*;
import javax.servlet.http.*;
import java.io.IOException;

public class MyServlet extends HttpServlet {
    @Override
    protected void doGet(HttpServletRequest request, HttpServletResponse response) throws ServletException, IOException {
        response.setContentType("text/html");
        response.getWriter().println("<h1>Hello, Servlet!</h1>");
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---

## 38. What is the use of the javax.servlet package?

The `javax.servlet` package provides classes and interfaces for:
- **Servlets**: Handling HTTP requests and responses.
- **Filters**: Intercepting requests and responses.
- **Listeners**: Monitoring events in a web application.

#### **[⬆ Back to Top](#level--hard)**
---

## 39. How do you use the JavaServer Pages (JSP) technology?

JSP technology is used for creating dynamic web content by embedding Java code in HTML pages.

**Example**:
```jsp
<%@ page contentType="text/html;charset=UTF-8" language="java" %>
<html>
<head>
    <title>Hello JSP</title>
</head>
<body>
<%
    String name = request.getParameter("name");
    if (name == null) {
        name = "World";
    }
%>
<h1>Hello, <%= name %>!</h1>
</body>
</html>
```
#### **[⬆ Back to Top](#level--hard)**
---

## 40. What is the use of the javax.servlet.jsp package?

The `javax.servlet.jsp` package provides classes and interfaces for JavaServer Pages (JSP). It is used for:
- **JSP Pages**: Creating JSP pages.
- **JSP Tags**: Defining custom tags.
- **JSP Actions**: Performing actions in JSP pages.

#### **[⬆ Back to Top](#level--hard)**
---

## 41. How do you perform unit testing in Java?

Unit testing in Java can be performed using frameworks like JUnit or TestNG.

**Example with JUnit**:
```java
import org.junit.jupiter.api.Assertions;
import org.junit.jupiter.api.Test;

public class MyServiceTest {

    @Test
    public void testPerformService() {
        MyService myService = new MyService();
        String result = myService.performService();
        Assertions.assertEquals("Service performed", result);
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---

## 42. What is the use of the JUnit framework in Java?

JUnit is used for:
- **Unit Testing**: Writing and running automated tests.
- **Assertions**: Checking expected results.
- **Test Fixtures**: Setting up and tearing down tests.
- **Test Runners**: Executing tests and generating reports.

#### **[⬆ Back to Top](#level--hard)**
---

## 43. How do you perform integration testing in Java?

Integration testing in Java can be performed using frameworks like Spring Test, Arquillian, or by writing custom integration tests.

**Example with Spring Test**:
```java
import org.junit.jupiter.api.Test;
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.boot.test.context.SpringBootTest;
import static org.assertj.core.api.Assertions.assertThat;

@SpringBootTest
public class MyServiceIntegrationTest {

    @Autowired
    private MyService myService;

    @Test
    public void testPerformService() {
        String result = myService.performService();
        assertThat(result).isEqualTo("Service performed");
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---

## 44. What is the use of the Mockito framework in Java?

Mockito is used for:
- **Mocking**: Creating mock objects.
- **Stubbing**: Defining behavior of mock objects.
- **Verification**: Checking interactions with mock objects.

#### **[⬆ Back to Top](#level--hard)**
---

## 45. How do you use the Mockito framework?

Mockito can be used to create mock objects and define their behavior for unit testing.

**Example**:
```java
import static org.mockito.Mockito.*;
import org.junit.jupiter.api.Test;

public class MyServiceTest {

    @Test
    public void testPerformService() {
        MyRepository mockRepository = mock(MyRepository.class);
        when(mockRepository.getData()).thenReturn("Mock Data");

        MyService myService = new MyService(mockRepository);
        String result = myService.performService();

        assertEquals("Service performed with Mock Data", result);
        verify(mockRepository).getData();
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---

## 46. What is the use of the TestNG framework in Java?

TestNG is used for:
- **Unit Testing**: Writing and running automated tests.
- **Integration Testing**: Performing integration tests.
- **Configuration**: Setting up and tearing down tests with annotations.
- **Parallel Testing**: Running tests in parallel.

#### **[⬆ Back to Top](#level--hard)**
---

## 47. How do you perform behavior-driven development (BDD) in Java?

BDD in Java can be performed using frameworks like Cucumber or JBehave.

**Example with Cucumber**:
1. **Feature file** (`src/test/resources/features/myFeature.feature`):
    ```gherkin
    Feature: My feature
    Scenario: Perform service
        Given the service is available
        When I perform the service
        Then I should get the response "Service performed"
    ```

2. **Step Definitions** (`src/test/java/com/example/StepDefinitions.java`):
    ```java
    import io.cucumber.java.en.Given;
    import io.cucumber.java.en.When;
    import io.cucumber.java.en.Then;
    import static org.junit.jupiter.api.Assertions.assertEquals;

    public class StepDefinitions {

        private MyService myService;
        private String response;

        @Given("the service is available")
        public void the_service_is_available() {
            myService = new MyService();
        }

        @When("I perform the service")
        public void i_perform_the_service() {
            response = myService.performService();
        }

        @Then("I should get the response {string}")
        public void i_should_get_the_response(String expectedResponse) {
            assertEquals(expectedResponse, response);
        }
    }
    ```

3. **Runner Class** (`src/test/java/com/example/CucumberTest.java`):
    ```java
    import org.junit.platform.suite.api.IncludeEngines;
    import org.junit.platform.suite.api.SelectClasspathResource;
    import org.junit.platform.suite.api.Suite;

    @Suite
    @IncludeEngines("cucumber")
    @SelectClasspathResource("features")
    public class CucumberTest {
    }
    ```
#### **[⬆ Back to Top](#level--hard)**
---

## 48. What is the use of the Cucumber framework in Java?

Cucumber is used for:
- **BDD**: Writing tests in a human-readable format using Gherkin language.
- **Automated Testing**: Automating tests based on feature files.
- **Integration**: Integrating with testing frameworks like JUnit or TestNG.

#### **[⬆ Back to Top](#level--hard)**
---

## 49. How do you perform closed-box testing in Java?

Closed-box testing can be performed by writing tests without knowing the internal structure of the code. This involves testing the functionality of the application based on requirements and specifications.

**Example**:
```java
import org.junit.jupiter.api.Test;
import static org.junit.jupiter.api.Assertions.assertEquals;

public class ClosedBoxTest {

    @Test
    public void testCalculateSum() {
        MyService myService = new MyService();
        int result = myService.calculateSum(5, 3);
        assertEquals(8, result);
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---

## 50. How do you perform open-box testing in Java?

Open-box testing involves writing tests with knowledge of the internal structure of the code. This includes testing private methods, internal states, and interactions between components.

**Example**:
```java
import org.junit.jupiter.api.Test;
import static org.junit.jupiter.api.Assertions.assertEquals;
import java.lang.reflect.Method;

public class OpenBoxTest {

    @Test
    public void testPrivateMethod() throws Exception {
        MyService myService = new MyService();
        Method method = MyService.class.getDeclaredMethod("privateMethod", int.class);
        method.setAccessible(true);
        int result = (int) method.invoke(myService, 5);
        assertEquals(25, result);
    }
}
```
#### **[⬆ Back to Top](#level--hard)**
---