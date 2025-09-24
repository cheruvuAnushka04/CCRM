# CCRM
Campus Course Records Manager (CCRM) Project Overview Campus Course Records Manager (CCRM) is a console-based Java application that manages student records, courses, enrollments, grading, transcript generation, and file operations like import/export and backup. It demonstrates core Java SE features including OOP principles, file handling with NIO.2, Java Streams, DateTime API, custom exceptions, and design patterns.

How to Run JDK Version: Java 11 or higher recommended

Compile:

text javac -d bin $(find src -name "*.java") Run:

text java -cp bin edu.ccrm.Main Use the console menu to navigate through options.

Evolution of Java (Short Bullets) 1995: Java 1.0 launched - “Write once, run anywhere” philosophy

1998: Java 2 introduced Swing UI, Collections Framework

2004: Java 5 released with generics, annotations, enhanced for-loop

2014: Java 8 with Lambda expressions, Stream API, DateTime API

2017: Java 9 with modules system (JPMS)

2021: Java 17 LTS with improved pattern matching, sealed classes

Java ME vs SE vs EE Java ME (Micro Edition) is a specialized edition of Java designed for mobile devices and embedded systems with limited resources. It provides a lightweight runtime environment and a subset of Java APIs tailored for constrained devices like feature phones, IoT gadgets, and small embedded devices. Java ME applications are typically small and optimized for low memory and processing power.

Java SE (Standard Edition) is the core Java platform used for creating general-purpose, desktop, and server applications. It includes a comprehensive set of libraries and APIs for programming user interfaces, networking, file I/O, concurrency, and more. Java SE forms the foundation for other editions and provides the Java Virtual Machine (JVM) to ensure platform independence.

Java EE (Enterprise Edition) builds on top of Java SE and offers a robust set of APIs and services for developing large-scale, multi-tiered, scalable, and secure enterprise applications. It includes components for web services, servlets, Enterprise JavaBeans (EJBs), messaging, and persistence, and typically runs in an application server environment suitable for complex business applications.

Windows Installation & Eclipse Setup Windows JDK Installation Download JDK installer from Oracle or OpenJDK.

Run installer and follow prompts.

Set JAVA_HOME environment variable:

Open Environment Variables → New system variable JAVA_HOME set to JDK path

Edit Path variable, add %JAVA_HOME%\bin

Verify install by cmd:

java -version
javac -version Eclipse Setup Download Eclipse IDE for Java Developers.

Open Eclipse and create a new Java Project.

Add your source code folder (src) to the project.

Ensure JDK is configured as the runtime in Eclipse preferences.

To run, right-click Main.java → Run As → Java Application.

To enable assertions when running:

text java -ea -cp bin edu.ccrm.Main To enable for all classes including libraries:

text java -ea:edu.ccrm... -cp bin edu.ccrm.Main To disable assertions:

text java -da -cp bin edu.ccrm.Main

The Screenshot Shows the working of the project


<img width="1724" height="530" alt="image" src="https://github.com/user-attachments/assets/9a3fe076-1718-4efb-9d09-b9f1ce04e008" />
<img width="1734" height="1450" alt="image" src="https://github.com/user-attachments/assets/7841ae20-d2df-4c61-8415-72a42b701cd6" />
<img width="1716" height="1256" alt="image" src="https://github.com/user-attachments/assets/c796f315-65c7-451a-a686-b8db4ceb4c82" />
<img width="1594" height="600" alt="image" src="https://github.com/user-attachments/assets/26edc0ae-0c8c-4e9c-879e-6b1eeb60b1b0" />


