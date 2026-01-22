1. JVM (Java Virtual Machine)
Definition: The core engine that executes Java bytecode.
Role: It translates platform-independent bytecode into machine-specific instructions.
Key Features:
Enables WORA ("Write Once, Run Anywhere").
Handles memory management, garbage collection, and security.
Abstract machine that does not exist physically. 
2. JRE (Java Runtime Environment)
Definition: A software package providing everything needed to run Java applications.
Composition: JRE = JVM + Libraries (e.g., util, lang, math) + Supporting files.
Target User: End-users who only need to execute Java programs.
Limitation: It does not contain development tools like a compiler or debugger. 
3. JDK (Java Development Kit)
Definition: The full-featured software development kit required to develop Java applications.
Composition: JDK = JRE + Development Tools (e.g., javac, jdb, javadoc).
Target User: Software developers writing, compiling, and debugging code.
Tools: Includes the compiler (javac) to turn source code into bytecode and the launcher (java) to run it. 
Summary Comparison Table
Feature 	JVM	JRE	JDK
Purpose	To execute bytecode	To run Java programs	To develop and run Java programs
Contents	Execution Engine	JVM + Class Libraries	JRE + Compilers/Debuggers
Dependency	Core engine	Contains JVM	Contains JRE and JVM
Platform	Platform-independent bytecode	Platform-dependent installers	Platform-dependent installers
Relationship: JDK > JRE > JVM. If you install the JDK, you automatically have the JRE and JVM included. 



