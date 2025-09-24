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
<img width="862" height="265" alt="Image" src="https://github.com/user-attachments/assets/ea14095b-9d06-49be-b78e-28bbe1109208" />
<img width="970" height="796" alt="Image" src="https://github.com/user-attachments/assets/46684622-e62b-47c6-a50f-cd47229fee52" />
<img width="964" height="697" alt="Image" src="https://github.com/user-attachments/assets/22e4020b-77b6-4e49-9131-a4e2a9e84280" />
<img width="885" height="326" alt="Image" src="https://github.com/user-attachments/assets/db8e7b73-a3f4-42bd-8339-36be5f106553" />




