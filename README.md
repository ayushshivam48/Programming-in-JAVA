# Programming in Java

## Introduction to Java

### 🌟 What is Java?
Java is a high-level, object-oriented, platform-independent programming language developed by James Gosling at Sun Microsystems (now owned by Oracle) and released in 1995.

The philosophy behind Java:
"Write Once, Run Anywhere" (WORA) – meaning you can write Java code once and run it on any platform that supports Java without needing to recompile.

---

### 🔧 Key Features of Java

| Feature               | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| ✅ Simple            | Easy to learn, especially for those with C/C++ background                   |
| 🔒 Secure           | Provides strong memory management and avoids pointer-related issues         |
| 🔄 Object-Oriented  | Based on OOP concepts like inheritance, encapsulation, polymorphism         |
| 🌐 Platform Independent | Compiles into bytecode that runs on the Java Virtual Machine (JVM)         |
| 🚀 Robust           | Strong exception handling and type checking                                 |
| 💡 Multithreaded    | Supports multithreaded programming (handling multiple tasks at once)        |
| ⚙️ High Performance | Just-In-Time (JIT) compiler improves performance                            |
| 🌍 Distributed      | Useful for distributed computing (e.g., RMI, EJB)                           |

---

### ⚙️ How Java Works
1. Source Code (.java) → Written by the programmer
2. Compiled into Bytecode (.class) using the Java Compiler (javac)
3. Bytecode is run on the JVM (java ClassName), making it platform-independent

Java Code → Compiled → Bytecode → JVM → Output

---

### 🧱 Basic Java Program Example

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```
Explanation:
•	public class HelloWorld → Class declaration
•	public static void main → Entry point of the program
•	System.out.println() → Prints output to console

---

🧠 Java Editions
1.	Java SE (Standard Edition) – for core functionality (apps, desktop)
2.	Java EE (Enterprise Edition) – for web and enterprise apps (now Jakarta EE)
3.	Java ME (Micro Edition) – for embedded and mobile devices

________________________________________
________________________________________

## Java Programming Steps
### 🔟 10 Essential Steps in Java Programming
---
### 1. Install Java Development Kit (JDK)
Download and install the JDK. It includes:  
•	Java Compiler (javac)  
•	Java Runtime Environment (JRE)  
•	Java Virtual Machine (JVM)  

---

### 2. Set Up Environment Variables (Optional but useful)
Add the `bin` folder of your JDK to the system PATH so you can use `javac` and `java` from any terminal/command prompt.  

---

### 3. Write the Java Code
Use any text editor (Notepad, VS Code, IntelliJ IDEA, etc.)  

**Example (HelloWorld.java):**
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, Java!");
    }
}
```

---

### 4. Save the File
• Save with `.java` extension  
• Filename must match the public class name (e.g., `HelloWorld.java`)  

---

### 5. Open Command Prompt / Terminal
Navigate to the folder where your `.java` file is saved.  

---

### 6. Compile the Code
Use:  
```java
javac HelloWorld.java
```
✅ If successful, this creates a `HelloWorld.class` bytecode file.

---

### 7. Run the Program
**Use:**
```java
java HelloWorld
```
⏩ This runs the `.class` file using the Java Virtual Machine (JVM).

🖨️ **Output:**
```
Hello, Java!
```

---

### 8. Debug if Needed
If you encounter errors:
1. **Read** the error message carefully
2. **Correct** your code
3. **Recompile** and **rerun** (repeat steps 6-7)

Common error types:
- Syntax errors (missing semicolons, brackets)
- Runtime errors (NullPointerException)
- Logical errors (incorrect program logic)

---

### 9. Repeat & Practice
Essential Java concepts to practice:
- **Variables** (int, String, boolean)
- **Loops** (for, while, do-while)
- **Arrays** (declaration, initialization)
- **Classes** (OOP fundamentals)
- **Functions** (methods with parameters/return values)

Practice project ideas:
- Calculator app
- Todo list manager
- Simple banking system

---

### 10. (Optional) Use an IDE
**Popular Java IDEs:**
- ☕ Eclipse (free, open-source)
- 🧠 IntelliJ IDEA (community/full versions)
- 🕸️ NetBeans (good for beginners)

**Key IDE Features:**
- ✨ Auto-complete (code suggestions)
- 🌈 Syntax highlighting (color-coded code)
- 🔍 Built-in compiler & debugger
- 🧩 Code templates (quick snippets)
- 🔗 Version control integration

**Installation Tip:** For beginners, start with IntelliJ IDEA Community Edition

________________________________________
________________________________________

## Java Tools and Resources

Java programming involves various tools that support the full development lifecycle — from writing and compiling code to testing, debugging, and deploying applications. These tools boost productivity, manage complexity, and help ensure reliability.

---

### 🔧 1. Core Development Tools (Included in JDK)
These are essential tools provided with the Java Development Kit (JDK):

| Tool      | Purpose                     | How It Works                          |
|-----------|-----------------------------|---------------------------------------|
| javac     | Java Compiler               | Converts .java files into .class bytecode |
| java      | Java Launcher               | Runs .class files on the JVM          |
| jar       | Archive Tool                | Packages .class files and resources into a .jar file |
| javadoc   | Documentation Generator     | Produces HTML docs from code comments |
| jdb       | Java Debugger               | Helps in step-by-step code debugging in terminal |

🟢 **Importance**: These tools form the foundation of Java program development, from writing code to distributing it.

---

### 💻 2. IDEs (Integrated Development Environments)
Modern IDEs make Java programming more efficient and user-friendly.

| IDE             | Features                              | Best For                          |
|-----------------|---------------------------------------|-----------------------------------|
| IntelliJ IDEA   | Smart code completion, Spring support | Web & enterprise development      |
| Eclipse         | Plugin-based, large community         | Large enterprise applications      |
| NetBeans        | Simple UI, built-in GUI designer      | Beginners and desktop apps        |
| VS Code         | Lightweight, Java extensions          | Simple to mid-level projects      |

🟢 **Importance**: IDEs help you write, debug, and run Java programs with features like autocomplete, error hints, and integrated terminals.

---

### ⚙️ 3. Build Tools
Build tools automate tasks like compiling code, managing libraries, and packaging applications.

| Tool    | Features                     | Example Use               |
|---------|------------------------------|---------------------------|
| Maven   | XML config (pom.xml)         | Web apps, Spring Boot     |
| Gradle  | Groovy/Kotlin DSL            | Android and microservices |
| Ant     | XML config, flexible scripting | Legacy projects         |

🟢 **Importance**: These tools make project builds repeatable and easy, especially when many libraries and files are involved.

---

### 🧪 4. Testing Tools
Testing is vital to ensure your application behaves correctly.

| Tool     | Use Case            | Description                          |
|----------|---------------------|--------------------------------------|
| JUnit    | Unit Testing        | Verifies methods and logic           |
| TestNG   | Advanced Testing    | Allows grouping and parallel testing |
| Mockito  | Mocking             | Simulates objects for testing        |

🟢 **Importance**: Helps catch bugs early and maintain code quality.

---

### 🖥️ 5. GUI Development Tools
Used to create desktop-based graphical user interfaces (GUIs).

| Tool     | Description                          | Use                          |
|----------|--------------------------------------|------------------------------|
| JavaFX   | Modern UI with CSS-like styling      | Rich desktop applications    |
| Swing    | Older, simple UI toolkit             | Legacy or academic projects  |

🟢 **Importance**: Enables you to build interactive, user-friendly applications.

---

### 🌐 6. Web & Enterprise Tools
Used for creating scalable web apps and enterprise software.

| Tool            | Description                          | Use                          |
|-----------------|--------------------------------------|------------------------------|
| Spring Boot     | Simplifies backend/web app creation  | REST APIs, microservices     |
| Apache Tomcat   | Java servlet container               | Runs Java-based web apps     |
| Hibernate       | ORM tool for database connectivity   | Data persistence without SQL |

🟢 **Importance**: These tools power modern web applications and enterprise-grade systems.

---

### 🧠 How These Tools Work in a Java Project (Step-by-Step)
1. **Write Code** – In an IDE like IntelliJ or Eclipse  
2. **Compile Code** – Using javac or the IDE's internal compiler  
3. **Run Program** – Via java command or IDE Run button  
4. **Test Code** – With JUnit or TestNG to verify functionality  
5. **Debug Issues** – Using jdb or graphical debugger in IDE  
6. **Add Libraries** – Using Maven or Gradle to manage dependencies  
7. **Package App** – With jar or Maven to distribute  
8. **Deploy/Run App** – On servers like Apache Tomcat or in a JAR file  

---

### 🧩 Summary Table

| Category       | Tools/Resources                     | Role                                |
|----------------|-------------------------------------|-------------------------------------|
| Development    | javac, java, javadoc, jar           | Compile, run, document              |
| IDEs           | IntelliJ, Eclipse, NetBeans, VS Code| Write & debug efficiently           |
| Build          | Maven, Gradle, Ant                  | Automate builds & dependencies      |
| Testing        | JUnit, TestNG, Mockito              | Ensure correctness                  |
| GUI            | JavaFX, Swing                       | Build interfaces                    |
| Web            | Spring Boot, Hibernate, Tomcat      | Web & database integration          |

________________________________________
________________________________________

## Java Applet Programming

### 🧭 What is a Java Applet?
A Java Applet is a small Java program that is embedded in a web page and runs inside a web browser using the Java plugin.

⚠️ **Note**: Applets were widely used in the past for web-based interactive programs (like animations or calculators), but they are now obsolete due to modern web technologies and browser security restrictions.

---

### 🧱 Key Features of Java Applets
- GUI-based Java programs that run inside browsers
- Inherit from `java.applet.Applet` class (or `javax.swing.JApplet` for Swing-based)
- Can display graphics, handle events, and interact with the user
- No `main()` method — they use lifecycle methods

---

### 🔄 Applet Lifecycle Methods
Java applets have predefined lifecycle methods:

| Method            | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `init()`          | Called once when the applet starts — initialize resources                   |
| `start()`         | Called each time the applet becomes visible or gains focus                  |
| `stop()`          | Called when the applet is no longer visible                                |
| `destroy()`       | Called when the applet is removed from memory                              |
| `paint(Graphics g)` | Called to draw content (text, shapes, etc.) on the screen                 |

---

### 🧑‍💻 Example: A Simple Java Applet
```java
import java.applet.Applet;
import java.awt.Graphics;

/* <applet code="HelloApplet.class" width="300" height="100"></applet> */

public class HelloApplet extends Applet {
    public void paint(Graphics g) {
        g.drawString("Hello from Java Applet!", 50, 50);
    }
}
```

---

### ✅ Steps to Run a Java Applet

1. **Save** as `HelloApplet.java`
2. **Compile**:
```java
   javac HelloApplet.java
```

3.	Create an HTML file (HelloApplet.html):
```html
<html>
<body>
    <applet code="HelloApplet.class" width="300" height="100"></applet>
</body>
</html>
```

4.	Run in Applet Viewer:
```java
appletviewer HelloApplet.html
```

🛑 Modern browsers no longer support applets. Use `appletviewer` from the JDK for testing:

```java
appletviewer YourApplet.html
```
---

### 📋 Historical Use Cases of Java Applets

- **Educational Tools**  
  Math and physics simulations, interactive learning modules
- **Web Utilities**  
  Small games, calculators, and other interactive tools
- **Visualizations**  
  Interactive diagrams, charts, and data visualizations

---

### ❌ Reasons for Applet Deprecation

| Issue | Impact | Modern Solution |
|-------|--------|-----------------|
| Java Plugin Requirement | No longer supported by browsers | Native browser technologies |
| Security Vulnerabilities | Sandboxing limitations | Modern security frameworks |
| Technology Obsolescence | Replaced by better alternatives | HTML5, JavaScript, WebAssembly |

---

### ✅ Modern Replacement Technologies

| Category | Technology Stack | Key Benefits |
|----------|------------------|--------------|
| Desktop Applications | JavaFX, Swing | Rich GUI capabilities |
| Web Applications | HTML5 + React/Vue | Cross-platform compatibility |
| Backend Services | Spring Boot | Microservices architecture |
| Animations/Graphics | Canvas/WebGL | Hardware-accelerated rendering |

---

### 📌 Java Applet Technical Summary

| Aspect | Details | Current Status |
|--------|---------|----------------|
| Base Class | `java.applet.Applet`<br>`javax.swing.JApplet` | Removed in Java 17 |
| Lifecycle Methods | `init()`, `start()`, `stop()`,<br>`destroy()`, `paint()` | Legacy only |
| Execution Model | Browser plugin | Discontinued |
| Modern Path | Java Web Start (also deprecated) | Self-contained apps |

> **Important Note**: All applet-related APIs were removed in Java SE 17 (JEP 398). For historical reference only.

________________________________________
________________________________________

## Encapsulation in Java

### 🔐 What is Encapsulation?
Encapsulation is the concept of wrapping data (variables) and code (methods) together as a single unit — like a capsule. It restricts direct access to some of the object's components, which is useful for protecting data from unwanted changes.

✅ **Analogy**: Think of it like a capsule of medicine — everything is sealed inside and accessed in a controlled way.

---
### 🧠 Key Concepts of Encapsulation in Java:
1. **Private Variables**: The class variables are declared as private
2. **Public Getter and Setter Methods**: These methods are used to read and update private variables

---

### 🧑‍💻 Java Example: Encapsulation

```java
public class Student {
   
    // Private data members
    private String name;
    private int age;

    // Public getter for name
    public String getName() {
        return name;
    }

    // Public setter for name
    public void setName(String newName) {
        name = newName;
    }

    // Getter for age
    public int getAge() {
        return age;
    }

    // Setter for age with validation
    public void setAge(int newAge) {
        if(newAge > 0) {
            age = newAge;
        } else {
            System.out.println("Invalid age.");
        }
    }
}
```
---

### Usage Example:

```java
public class Main {
    
    public static void main(String[] args) {
        Student s = new Student();
        s.setName("Anjali");
        s.setAge(20);

        System.out.println("Name: " + s.getName());
        System.out.println("Age: " + s.getAge());
    }
}
```
---

### 🎯 Why is Encapsulation Important?

| Benefit           | Explanation                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| ✅ Data Hiding    | Prevents unauthorized access and modification of data                        |
| ✅ Security       | Sensitive information is protected inside the class                         |
| ✅ Code Flexibility | You can change code internally without affecting external code              |
| ✅ Control        | You can add validation logic in setter methods                              |
| ✅ Reusability    | Easily maintain and reuse encapsulated classes in other programs            |

---

### 🏁 Real-Life Example
**ATM Machine Analogy**:
- Your account balance is private (hidden data)
- You enter your PIN to access it (public method)
- The system validates before granting access (controlled access)

*This demonstrates encapsulation in real-world systems!*

---

### 🔁 Summary of Key Terms

| Term             | Definition                                                                 |
|------------------|---------------------------------------------------------------------------|
| Encapsulation    | Bundling data and methods that operate on that data within a single unit   |
| Data Hiding      | Restricting direct access to an object's internal representation          |
| Private          | Access modifier that restricts visibility to the containing class only    |
| Getter/Setter    | Public methods that provide controlled access to private fields           |

> **Note**: Encapsulation is one of the four fundamental OOP concepts, along with inheritance, polymorphism, and abstraction.

________________________________________
________________________________________

## Java Programming Insights

### 🔹 1. Platform Independence
- **Write Once, Run Anywhere** (WORA) philosophy
- Java code compiles to bytecode running on JVM
- Cross-platform compatibility (Windows, macOS, Linux)

### 🔹 2. Object-Oriented Programming (OOP)
Java implements four core OOP principles:

| Principle       | Implementation in Java                     |
|-----------------|--------------------------------------------|
| Encapsulation   | Private fields with public getters/setters |
| Inheritance     | `extends` keyword for class hierarchy      |
| Polymorphism    | Method overloading and overriding          |
| Abstraction     | Abstract classes and interfaces            |

### 🔹 3. Robust and Secure
- **Automatic Memory Management** via Garbage Collection
- No pointer arithmetic (unlike C/C++)
- Built-in security manager for safe execution
- Exception handling framework

### 🔹 4. Rich API & Libraries
Java's comprehensive standard library includes:

// Collections
List<String> names = new ArrayList<>(); 

// File I/O
Files.readAllLines(Paths.get("file.txt"));

// Networking
URL url = new URL("https://api.example.com");

### 🔹 5. Multithreading Support

#### Core Features:
- Built-in `Thread` class and `Runnable` interface
- `synchronized` keyword for thread safety
- `java.util.concurrent` package with advanced utilities:
  - `ExecutorService` for thread pools
  - `ConcurrentHashMap` for thread-safe collections
  - `CountDownLatch` for synchronization

#### Benefits:
- Improved application performance
- Better resource utilization
- Enhanced responsiveness in GUI applications

// Example: Creating threads
```java
Thread thread = new Thread(() -> {
    System.out.println("Running in separate thread");
});
thread.start();
```

### 🔹 6. Essential Java Tools & IDEs

#### Core Development Tools:
| Tool | Purpose | Command to Verify |
|------|---------|-------------------|
| **JDK** | Java Development Kit (Compiler + Tools) | `javac -version` |
| **JRE** | Java Runtime Environment | `java -version` |
| **JVM** | Executes bytecode | Bundled with JRE |
| **javac** | Java Compiler | `javac -version` |

#### Top Java IDEs:
1. **IntelliJ IDEA** (Recommended)
   - Features: Smart completion, built-in tools
   - Best for: Professional development
   - Version: Community (Free) & Ultimate (Paid)

2. **Eclipse** 
   - Features: Extensive plugin ecosystem
   - Best for: Enterprise applications
   - Popular for: Spring framework development

3. **VS Code** (Growing Popularity)
   - Features: Lightweight with extensions
   - Setup: Requires Java Extension Pack


#### Example: Compiling and running Java
```java
javac Main.java
java Main
```

### 🔹 8. Thriving Java Community & Industry Adoption

#### Global Java Ecosystem
- 🌍 **10M+ developers** worldwide (2024 estimates)
- 🏆 **#2** most popular language (Stack Overflow Survey 2023)
- 📈 **25%** of all enterprise applications use Java

#### Industry Leaders Using Java
| Industry | Major Companies | Key Java Applications |
|----------|-----------------|-----------------------|
| **Tech** | Google, Netflix | Cloud services, recommendation engines |
| **Finance** | JPMorgan, Goldman Sachs | Trading systems, risk analysis |
| **E-commerce** | Amazon, Alibaba | Marketplace backends, payment systems |
| **Telecom** | Verizon, AT&T | Billing systems, network management |

#### Community Resources
- 🎓 **Oracle Java Certification** (OCPJP) - Industry standard credential
- 💡 **Java User Groups (JUGs)** - 500+ active chapters worldwide
- 🛠️ **OpenJDK** - Community-driven Java development

---

### 🔹 9. Java Career Pathways

#### In-Demand Roles (2024)
| Position | Average Salary (US) | Key Skills |
|----------|---------------------|------------|
| **Java Backend Developer** | $110,000 | Spring Boot, Microservices |
| **Android Engineer** | $105,000 | Kotlin/Java, Jetpack Components |
| **Full Stack Java Dev** | $115,000 | React/Angular + Java |
| **Cloud Solutions Architect** | $140,000 | AWS/GCP + Java |

#### Emerging Opportunities
- ☁️ **Cloud-Native Java** (Quarkus, Micronaut)
- 🤖 **AI/ML Integration** (DJL, Tribuo)
- 🔗 **Blockchain Development** (Web3j)

#### Certification Path
1. Oracle Certified Associate (OCA)
2. Oracle Certified Professional (OCP)
3. Spring Professional Certification
4. AWS Certified Developer (Java focus)

---

### 🚀 Java in 2024: Why It Matters

**Key Advantages:**
- 💪 **Performance**: Modern JVM optimizations rival native code
- 🔄 **Versatility**: From IoT to enterprise systems
- 🛡️ **Security**: Built-in security features for enterprise apps
- 📦 **Ecosystem**: 400,000+ libraries in Maven Central

> "Java continues to power the backbone of global enterprise systems while adapting to modern cloud-native architectures." - Senior Tech Analyst, 2024

**Future Outlook:**
- Gradual transition to Project Loom (virtual threads)
- Increased adoption in edge computing
- Strong position in quantum computing research

________________________________________
________________________________________

## Java Static Scope Rules  

### 🔷 What is "Static" in Java?  
In Java, the `static` keyword means that a member belongs to the class rather than to instances of the class. Static elements are shared across all objects of that class.  

---

### ✅ Java Static Scope Rules  

#### 1. Static Variables (Class Variables)  

```java
class Example {  
    static int count = 0;  // static variable  
    Example() {
        count++;  
    }  
}  
```

- Declared using the `static` keyword  
- Shared among all class instances  
- Initialized once at class loading  

#### 2. Static Methods  
```java
class Test { 
    static int x = 10;  
    static void show() {  
        System.out.println("x = " + x);  // Allowed  
        // System.out.println("y = " + y);  // ❌ Not allowed  
    }
    int y = 5;  
}
```

- Belong to the class, not the object  
- Can access only static data directly  
- Cannot use `this` keyword  

#### 3. Static Blocks
```java
class Hello {  
    static {  
        System.out.println("Static block executed");  
    }
    public static void main(String[] args) {  
        System.out.println("Main method executed");  
    }
}
```

- Executes when class is loaded  
- Runs before main method  

#### 4. Calling Rules  
- Call static members using class name:  
`MyClass.display();  // ✅ Preferred`  
- Can use object reference (but not recommended):  
`obj.display();      // ⚠️ Allowed`  

---

### 📌 Summary Table  

| Feature              | Static | Non-Static |  
|----------------------|--------|------------|  
| Belongs to class     | ✅     | ❌         |  
| Needs object access  | ❌     | ✅         |  
| Can use `this`       | ❌     | ✅         |  
| Access static members| ✅     | ✅         |  
| Access instance members | ❌   | ✅         |  

---

### 🧠 Real-Life Example  
```java
class Student {  
    static String college = "ABC University";  
    String name;
    Student(String name) {  
        this.name = name;  
    }
    void display() {  
        System.out.println(name + " studies at " + college);  
    }
}
```

Key Points:  
- `college` is shared by all students (static)  
- `name` is unique per student (non-static)  
- Static members save memory when shared data is needed

________________________________________
________________________________________

## Inheritance  

### 🔷 What is Inheritance?  
Inheritance is a mechanism in Java where one class (child/subclass) can inherit the properties and behaviors (fields and methods) of another class (parent/superclass).  

**Benefits:**  
- Promotes code reusability  
- Makes code easier to maintain and extend  
- Enables hierarchical classifications  

---

### 🔹 Syntax of Inheritance  
```java
class Superclass {
    // fields and methods
}
class Subclass extends Superclass {
    // additional fields and methods
}
```

---

### 🔍 Example  
```java
class Vehicle {
    void startEngine() {
        System.out.println("Engine started");
    }
}
class Car extends Vehicle {
    void drive() {
        System.out.println("Car is driving");
    }
}
public class Main {
    public static void main(String[] args) {
        Car myCar = new Car();
        myCar.startEngine();  // Inherited method
        myCar.drive();        // Child method
    }
}
```

**Output:**  
```
Engine started  
Car is driving  
```

---

### 🏷️ Types of Inheritance in Java  

#### 1. Single Inheritance  
One class inherits from one superclass.  

**Example:**  
```java
class Animal {
    void eat() {
        System.out.println("Animal eats food");
    }
}
class Dog extends Animal {
    void bark() {
        System.out.println("Dog barks");
    }
}
```

#### 2. Multilevel Inheritance  
A class is derived from a class that is also derived from another class.  

**Example:**  
```java
class Grandparent {
    void heritage() {
        System.out.println("Grandparent's heritage");
    }
}
class Parent extends Grandparent {
    void culture() {
        System.out.println("Parent's culture");
    }
}
class Child extends Parent {
    void modernStyle() {
        System.out.println("Child's modern style");
    }
}
```

#### 3. Hierarchical Inheritance  
Multiple classes inherit from the same parent class.  

**Example:**  
```java
class Animal {
    void eat() {
        System.out.println("Animal eats");
    }
}
class Dog extends Animal {
    void bark() {
        System.out.println("Dog barks");
    }
}
class Cat extends Animal {
    void meow() {
        System.out.println("Cat meows");
    }
}
```

#### 4. Multiple Inheritance (Through Interfaces Only)  
Java supports multiple inheritance using interfaces.  

**Example:**  
```java
interface Printable {
    void print();
}
interface Showable {
    void show();
}
class Document implements Printable, Showable {
    public void print() {
        System.out.println("Printing document...");
    }
    public void show() {
        System.out.println("Showing document...");
    }
}
```

#### 5. Hybrid Inheritance  
Combination of inheritance types, achieved via interfaces.  

**Example:**  
```java
interface A {
    void methodA();
}
interface B extends A {
    void methodB();
}
class C {
    void methodC() {
        System.out.println("Class C method");
    }
}
class D extends C implements B {
    public void methodA() {
        System.out.println("Method A from interface A");
    }
    public void methodB() {
        System.out.println("Method B from interface B");
    }
}
```

---

### ⚠️ Why Java Doesn't Support Multiple Inheritance with Classes  
Java avoids multiple inheritance with classes to prevent the Diamond Problem.  

**Problem Example:**  
```java
class A {
    void show() { System.out.println("A"); }
}
class B {
    void show() { System.out.println("B"); }
}
// class C extends A, B { } // Not allowed!
```

> **Solution:** Use interfaces instead!

---

### 📌 Summary Table  

| Inheritance Type | Supported in Java? | Example |
|-----------------|-------------------|---------|
| Single Inheritance | ✅ Yes | class B extends A |
| Multilevel Inheritance | ✅ Yes | C → B → A |
| Hierarchical Inheritance | ✅ Yes | B, C extends A |
| Multiple Inheritance (Classes) | ❌ No | Use Interfaces Instead |
| Hybrid Inheritance | ✅ Via Interfaces | Mix of all above |

---

### 🧠 Key Benefits of Inheritance  
- ✅ Code reuse  
- ✅ Method overriding for custom behavior  
- ✅ Supports polymorphism  
- ✅ Easier maintainability and scalability

________________________________________
________________________________________

## Information Hiding  

### 🔒 What is Information Hiding?  
Information Hiding is one of the core principles of object-oriented programming (OOP). It means restricting access to the internal details of an object and only exposing what is necessary.  

**Benefits:**  
- Protects the integrity of the data  
- Reduces system complexity  
- Improves maintainability and flexibility  

---

### 🧠 Why is it Important?  
- Prevents unauthorized access to data  
- Makes debugging and testing easier  
- Encourages modularity - each part can be understood independently  
- Reduces interdependency between components  

---

### ⚙️ How is it Achieved in Java?  
Information hiding in Java is achieved using:  
- **Access Modifiers**: `private`, `protected`, `public`, and `default`  
- **Encapsulation**: Wrapping data and methods in a single unit (class), making fields private while providing getters/setters  

---

### ✅ Example  

```java
class Employee {
    // Private data members (hidden from outside)
    private String name;
    private double salary;

    // Constructor
    public Employee(String name, double salary) {
        this.name = name;
        this.salary = salary;
    }

    // Public getter method (controlled access)
    public String getName() {
        return name;
    }

    // Public setter method (controlled modification)
    public void setName(String name) {
        this.name = name;
    }

    public double getSalary() {
        return salary;
    }

    public void setSalary(double salary) {
        if (salary > 0) {
            this.salary = salary;
        } else {
            System.out.println("Invalid salary amount!");
        }
    }
}

public class Company {
    public static void main(String[] args) {
        Employee emp = new Employee("Alice", 50000);

        // Accessing private fields using public methods
        System.out.println("Name: " + emp.getName());
        System.out.println("Salary: " + emp.getSalary());

        // Trying to update salary
        emp.setSalary(55000);
        System.out.println("Updated Salary: " + emp.getSalary());

        // Invalid update
        emp.setSalary(-1000); // Will trigger validation
    }
}
```

**Output:**  
```
Name: Alice  
Salary: 50000.0  
Updated Salary: 55000.0  
Invalid salary amount!
```

---

### 🔍 Summary  

| Feature | Description |  
|---------|-------------|  
| Access Modifiers | Limit visibility of fields/methods |  
| Encapsulation | Combines data + methods; hides internal details |  
| Getters/Setters | Allow controlled access to private data |  

Key takeaways:  
- Always make fields `private` by default  
- Expose only what's necessary through public methods  
- Use setters to validate data before assignment  
- Information hiding makes your code more robust and maintainable

________________________________________
________________________________________

## Packages in Java

### 🔍 What is a Package?
A package in Java is a namespace that organizes classes and interfaces in a logical manner. Think of it like folders on your computer that keep related files together.

**Key Benefits:**
- Avoids class name conflicts
- Manages access control
- Makes code maintenance easier

---

### 🧱 Types of Packages

1. **Built-in Packages**  
   Java provides many ready-to-use packages:
   - `java.util` → contains utility classes like ArrayList, HashMap
   - `java.io` → classes for input/output operations
   - `java.lang` → fundamental classes (automatically imported)

2. **User-defined Packages**  
   You can create your own packages to group related classes

---

### ✅ How to Create and Use a Package

#### Step 1: Create a Package
```java
package MyPackage;

public class Addition {
    public int add(int a, int b) {
        return a + b;
    }
}
```
(Save as `MyPackage/Addition.java`)

#### Step 2: Use the Package
```java
import MyPackage.Addition;

public class Main {
    public static void main(String[] args) {
        Addition obj = new Addition();
        int result = obj.add(5, 10);
        System.out.println("Sum: " + result);
    }
}
```
(Save as `Main.java`)

**Compilation & Execution:**
```java
javac MyPackage/Addition.java
javac Main.java
java Main
```

---

### 🛠️ Key Benefits of Using Packages

| Benefit | Description |
|---------|-------------|
| Namespace Management | Prevents class name conflicts |
| Modularity | Code is better organized and reusable |
| Access Control | Enables protected and default access |
| Easier Maintenance | Code is simpler to navigate and update |

---

### 🧠 Real-Life Example
**Banking Application Structure:**
- `bank.customers` → Customer account management
- `bank.transactions` → Deposit/withdrawal processing  
- `bank.employees` → Staff management systems  

This organization makes teamwork and maintenance more efficient!

**Key Takeaways:**
1. Always declare packages at the top of your Java files
2. Follow reverse domain naming convention (e.g., `com.company.project`)
3. Use `import` statements to access package contents
4. Keep related classes together in logical packages

________________________________________
________________________________________

## Interface in Java

### 🔍 What is an Interface?
An interface in Java is a blueprint of a class that contains abstract methods and constants. It specifies behavior that implementing classes must define.

**Key Points:**
- Contains abstract methods (no body)
- Can have constants (public, static, final)
- Cannot be instantiated directly
- Supports multiple inheritance

---

### 🚨 Why Use Interfaces?
1. **Achieve abstraction** - Hide implementation details
2. **Multiple inheritance** - Class can implement multiple interfaces
3. **Standard behavior** - Define common contracts
4. **Loose coupling** - Reduce dependencies between components

---

### ✨ Key Characteristics

| Feature | Description |
|---------|-------------|
| Abstract methods | Must be implemented by classes |
| Default methods | Can have implementation (Java 8+) |
| Static methods | Called via interface name |
| No constructors | Cannot be instantiated |
| Multiple inheritance | Class can implement multiple interfaces |

---

### 🔧 Syntax
```java
interface InterfaceName {
    // Constant
    int VALUE = 100;

    // Abstract method
    void methodName();

    // Default method
    default void show() {
        System.out.println("Default method");
    }

    // Static method
    static void display() {
        System.out.println("Static method");
    }
}
```

---

### 🧪 Code Example

#### 🔹 Vehicle Interface
```java
interface Vehicle {
    void start(); // Abstract method
    void stop();  // Abstract method

    default void fuelType() {
        System.out.println("Uses petrol");
    }

    static void companyInfo() {
        System.out.println("AutoMobiles Ltd.");
    }
}
```

#### 🔹 Car Implementation
```java
class Car implements Vehicle {
    public void start() {
        System.out.println("Car starting...");
    }

    public void stop() {
        System.out.println("Car stopping");
    }
    
    @Override
    public void fuelType() {
        System.out.println("Uses diesel");
    }
}
```

#### 🔹 Main Class
```java
public class Main {
    public static void main(String[] args) {
        Vehicle myCar = new Car();
        myCar.start();
        myCar.stop();
        myCar.fuelType();
        Vehicle.companyInfo();
    }
}
```

**Output:**
```
Car starting...
Car stopping
Uses diesel
AutoMobiles Ltd.
```

---

### 🧠 Real-life Example
```java
interface USBDevice {
    void connect();
}

class Printer implements USBDevice {
    public void connect() {
        System.out.println("Printer connected");
    }
}

class Scanner implements USBDevice {
    public void connect() {
        System.out.println("Scanner connected");
    }
}
```

---

### 🧱 Interface vs Abstract Class

| Feature | Abstract Class | Interface |
|---------|---------------|-----------|
| Inheritance | Single | Multiple |
| Methods | Can have implementation | Abstract/default/static |
| Variables | Any type | Only public static final |
| Instantiation | Not allowed | Not allowed |

**Key Takeaways:**
- Use interfaces for defining contracts
- Default methods allow backward compatibility
- Static methods provide utility functions
- Interfaces enable polymorphic behavior

________________________________________
________________________________________

## Experience Handling

Experience handling typically refers to the management of different types of exceptions or errors that can arise during the execution of a program. In Java, this is primarily done using exception handling mechanisms.

Java provides a powerful mechanism for exception handling, which allows developers to manage errors or unexpected conditions in a controlled manner, preventing the program from crashing unexpectedly.

---

### 🛠️ Key Concepts of Exception Handling

1. **Exception**: An abnormal condition that disrupts the normal flow of the program. Examples include division by zero, file not found, null pointer dereference, etc.

2. **Error**: A serious problem that a program cannot handle, often due to system-level failures (e.g., OutOfMemoryError).

**Java Exception Handling Keywords**:
- `try`: Used to enclose the code that might throw an exception.
- `catch`: Defines a block of code to handle the exception that was thrown.
- `finally`: A block that runs after the try and catch blocks, whether an exception is thrown or not. It is typically used for clean-up operations.
- `throw`: Used to explicitly throw an exception.
- `throws`: Declares exceptions that a method may throw.

---

### 📘 Types of Exceptions in Java

1. **Checked Exceptions**: Exceptions that are checked at compile-time (e.g., IOException, SQLException).
2. **Unchecked Exceptions**: Exceptions that occur at runtime and are not checked at compile time (e.g., NullPointerException, ArithmeticException).
3. **Errors**: Serious issues, such as OutOfMemoryError, that are usually beyond the program's control.

---

### 🔧 Syntax for Handling Exceptions

```java
try {
    // Code that might throw an exception
} catch (ExceptionType e) {
    // Code to handle the exception
} finally {
    // Code that will run after try and catch, regardless of an exception
}
```

---

### 🧑‍💻 Example of Exception Handling

#### 1. Simple Exception Handling (try-catch-finally)

```java
public class Example {
    public static void main(String[] args) {
        try {
            int result = 10 / 0;  // ArithmeticException
        } catch (ArithmeticException e) {
            System.out.println("Error: Cannot divide by zero.");
        } finally {
            System.out.println("This block runs no matter what.");
        }
    }
}
```

**Output**:
```
Error: Cannot divide by zero.
This block runs no matter what.
```

---

#### 🚀 Throwing and Declaring Exceptions

1. **Throwing an Exception**: If you want to manually throw an exception, you can use the `throw` keyword.

```java
public class ThrowExample {
    public static void main(String[] args) {
        try {
            throw new Exception("This is a custom exception");
        } catch (Exception e) {
            System.out.println("Caught exception: " + e.getMessage());
        }
    }
}
```

**Output**:
```
Caught exception: This is a custom exception
```

2. **Declaring Exceptions**: If a method can throw an exception, it must be declared using the `throws` keyword.

```java
class Example {
    public static void main(String[] args) throws Exception {
        // Code that might throw an exception
        throw new Exception("Exception thrown from main");
    }
}
```

---

### 🎯 Best Practices for Handling Exceptions

1. **Catch specific exceptions**: Catch the most specific exceptions first, then the more general ones.
2. **Do not use empty catch blocks**: Always log the exception or take some corrective action.
3. **Avoid using exceptions for flow control**: Exceptions should be used for exceptional situations, not for regular program flow.
4. **Always close resources**: Use `finally` to close resources like files and database connections.

---

### 🔄 Real-Life Example: File Reading with Exception Handling

```java
import java.io.*;

public class FileReaderExample {
    public static void main(String[] args) {
        try {
            FileReader file = new FileReader("non_existent_file.txt");
            BufferedReader fileInput = new BufferedReader(file);
            fileInput.readLine();
            fileInput.close();
        } catch (FileNotFoundException e) {
            System.out.println("File not found: " + e.getMessage());
        } catch (IOException e) {
            System.out.println("IOException occurred: " + e.getMessage());
        } finally {
            System.out.println("File reading operation completed.");
        }
    }
}
```

**Output**:
```
File not found: non_existent_file.txt
File reading operation completed.
```

---

### 📚 Notes Summary on Exception Handling

- Exception handling helps ensure that your program does not crash unexpectedly.
- Use `try-catch-finally` to manage exceptions gracefully.
- Use `throw` to manually throw exceptions and `throws` to declare them in methods.
- Checked exceptions require explicit handling (e.g., IOException), while unchecked exceptions don't.
- Always make sure to close resources (like files or connections) in the `finally` block to avoid resource leaks.

________________________________________
________________________________________

## Multithreading

Multithreading is a concurrent execution technique that allows the CPU to execute multiple threads (smaller units of a process) simultaneously. This helps in improving the efficiency and performance of a program, especially for tasks that can be performed concurrently.

---

### 🔍 What is a Thread?
A thread is the smallest unit of execution within a process. Every Java application has at least one thread — the main thread, but additional threads can be created to perform parallel tasks.

---

### 🚀 Why Use Multithreading?
1.	Improved Performance: By executing multiple tasks concurrently, the overall performance of the application improves, especially in a multi-core processor environment.
2.	Resource Utilization: Multithreading helps in utilizing CPU resources more effectively.
3.	Better User Experience: In GUI applications, multithreading can keep the user interface responsive by handling background tasks concurrently.
4.	Faster Execution: Tasks like file processing, image manipulation, etc., can be processed in parallel.

---

### 🧑‍💻 Java Threading Basics
•	Main Thread: Every Java application has one main thread that starts the execution of the program.
•	Thread Class: The Thread class in Java provides a way to create and manage threads.
•	Runnable Interface: Another way to create threads in Java is by implementing the Runnable interface.

---

### 🧑‍💻 Creating Threads in Java
There are two ways to create threads:
1.	By Extending the Thread class
2.	By Implementing the Runnable interface

---

#### Method 1: Extending the Thread Class
In this method, a class extends the Thread class and overrides its run() method, which contains the code that will be executed by the thread.

**Example: Extending the Thread class**

```java
class MyThread extends Thread {
    public void run() {
        System.out.println(Thread.currentThread().getId() + " is running");
    }

    public static void main(String[] args) {
        MyThread t1 = new MyThread();
        t1.start(); // Start the thread

        MyThread t2 = new MyThread();
        t2.start(); // Start the second thread
    }
}

```

**Explanation:**
•	The run() method contains the task to be executed by the thread.
•	start() creates a new thread of execution and invokes the run() method.
•	Thread.currentThread().getId() gives the ID of the current thread.

**Output:**
```
1 is running
2 is running
```

---

#### Method 2: Implementing the Runnable Interface
In this approach, a class implements the Runnable interface and provides an implementation for the run() method. Then, a Thread object is created and passed the Runnable object.

**Example: Implementing the Runnable interface**

```java
class MyRunnable implements Runnable {
    public void run() {
        System.out.println(Thread.currentThread().getId() + " is running");
    }

    public static void main(String[] args) {
        MyRunnable myRunnable = new MyRunnable();

        Thread t1 = new Thread(myRunnable);
        t1.start(); // Start the thread

        Thread t2 = new Thread(myRunnable);
        t2.start(); // Start the second thread
    }
}
```

**Explanation:**
•	The Runnable interface provides a single method, run(), which contains the code to be executed by the thread.
•	The Thread class is used to start the thread and associate the Runnable object with it.

**Output:**
```
1 is running
2 is running
```

---

### 🌟 Thread Life Cycle
A thread in Java goes through various states during its life cycle:
1.	New: A thread is in the "new" state when it is created but not yet started.
2.	Runnable: After invoking start(), the thread is moved to the runnable state. It's eligible for CPU time, but not necessarily running.
3.	Blocked: A thread enters this state when it's waiting for resources that are being used by another thread.
4.	Waiting: A thread enters this state when it's waiting for another thread to perform a particular action.
5.	Terminated: A thread enters the terminated state when it has finished its execution.

---

### 🚦 Thread Synchronization
When multiple threads access shared resources concurrently, it can lead to race conditions, where the outcome depends on the timing of the thread execution. To avoid this, synchronization is used.

**Why Use Synchronization?**
•	Synchronization ensures that only one thread can access a resource at a time, preventing data inconsistency and errors.

**Example: Synchronized Method**

```java
class Counter {
    private int count = 0;

    public synchronized void increment() {
        count++;
    }

    public synchronized int getCount() {
        return count;
    }
}

public class Main {
    public static void main(String[] args) {
        Counter counter = new Counter();

        Thread t1 = new Thread(() -> {
            for (int i = 0; i < 1000; i++) {
                counter.increment();
            }
        });

        Thread t2 = new Thread(() -> {
            for (int i = 0; i < 1000; i++) {
                counter.increment();
            }
        });

        t1.start();
        t2.start();

        try {
            t1.join(); // Wait for t1 to finish
            t2.join(); // Wait for t2 to finish
        } catch (InterruptedException e) {
            e.printStackTrace();
        }

        System.out.println("Final count: " + counter.getCount());
    }
}

```

**Explanation:**
•	synchronized ensures that the increment() method is accessed by only one thread at a time.
•	join() ensures that the main thread waits for both threads to complete before printing the final result.

**Output:**
```
Final count: 2000
```

---

### 💡 Advanced Concepts
1.	Thread Priority: Threads can be given different priorities using setPriority(int priority) to influence the order of thread execution (although Java's thread scheduler may override this).
2.	Thread Pool: Instead of creating threads manually, you can use a Thread Pool (via the Executor framework) to manage threads efficiently.
3.	Daemon Threads: A thread that runs in the background and does not prevent the program from exiting. Use setDaemon(true) to mark a thread as a daemon thread.
4.	Deadlock: A condition where two or more threads are blocked forever due to waiting for each other to release resources. It can be avoided by using proper synchronization and resource allocation strategies.

---

### 🌍 Real-World Applications of Multithreading
1.	Web Servers: Handling multiple user requests simultaneously.
2.	Image Processing: Performing complex calculations on different parts of an image simultaneously.
3.	Database Query Processing: Running parallel queries to enhance performance.
4.	Games and GUI Applications: Updating user interfaces while processing background tasks.

---

### 🧾 Summary of Multithreading Concepts

•	Thread: The smallest unit of execution.

•	Runnable Interface and Thread Class: Two ways to create threads.

•	Thread Lifecycle: Includes New, Runnable, Blocked, Waiting, and Terminated states.

•	Synchronization: Ensures thread safety when multiple threads access shared resources.

•	Thread Pooling and Executor Framework: Efficient management of multiple threads.

________________________________________
________________________________________

## I-O Stream

I/O Streams in Java refer to a mechanism that facilitates reading from and writing to different kinds of data sources (like files, memory, network, etc.). Java's I/O streams provide an abstraction for interacting with these resources, making it easier to perform data input/output operations.

---

### 📚 What is I/O Stream?
An I/O stream is a sequence of data. There are two types of streams in Java:

1.	Input Stream: For reading data.

2.	Output Stream: For writing data.

Streams can either be byte-oriented or character-oriented, depending on the type of data (binary or text) they handle.

---

### 🧑‍💻 Types of Streams in Java
Java provides two main categories of streams:


1.	Byte Streams:

o	Used for handling raw binary data.

o	Classes: InputStream, OutputStream, FileInputStream, FileOutputStream, etc.


2.	Character Streams:

o	Used for handling text (character-based data).

o	Classes: Reader, Writer, FileReader, FileWriter, etc.

---

### 📊 Byte Streams
Byte streams are used to read and write binary data (like image files, audio files, or any non-textual content).


•	InputStream: Used for reading bytes of data.

o	FileInputStream: Reads data from files in byte form.


•	OutputStream: Used for writing bytes of data.

o	FileOutputStream: Writes data to files in byte form.

**Example of Byte Streams (Reading and Writing a Binary File)**
```java
import java.io.FileInputStream;
import java.io.FileOutputStream;
import java.io.IOException;

public class ByteStreamExample {
    public static void main(String[] args) {
        try {
            // Writing to a file using FileOutputStream
            FileOutputStream fos = new FileOutputStream("output.dat");
            fos.write(65);  // Writes the byte representation of 'A'
            fos.close();

            // Reading from a file using FileInputStream
            FileInputStream fis = new FileInputStream("output.dat");
            int data = fis.read();
            System.out.println("Read byte: " + (char) data); // Output: A
            fis.close();
        } catch (IOException e) {
            e.printStackTrace();
        }
    }
}
```

---

### 📄 Character Streams
Character streams are specifically designed for handling text data (e.g., reading and writing text files). These streams convert the characters into bytes using a particular encoding scheme (like UTF-8 or ASCII).


•	Reader: Used for reading characters.

o	FileReader: Reads character data from a file.


•	Writer: Used for writing characters.

o	FileWriter: Writes character data to a file.

**Example of Character Streams (Reading and Writing Text Files)**
```java
import java.io.FileReader;
import java.io.FileWriter;
import java.io.IOException;

public class CharacterStreamExample {
    public static void main(String[] args) {
        try {
            // Writing to a text file using FileWriter
            FileWriter writer = new FileWriter("output.txt");
            writer.write("Hello, World!");
            writer.close();

            // Reading from a text file using FileReader
            FileReader reader = new FileReader("output.txt");
            int data = reader.read();
            while (data != -1) {
                System.out.print((char) data);  // Output: Hello, World!
                data = reader.read();
            }
            reader.close();
        } catch (IOException e) {
            e.printStackTrace();
        }
    }
}
```

---

### 🔄 I/O Stream Classes and Methods

1.	InputStream Class:

o	int read(): Reads the next byte of data.

o	int read(byte[] b): Reads up to b.length bytes of data into an array.

o	void close(): Closes the stream.


2.	OutputStream Class:

o	void write(int b): Writes the specified byte to the stream.

o	void write(byte[] b): Writes the specified byte array to the stream.

o	void close(): Closes the stream.


3.	Reader Class:

o	int read(): Reads a single character.

o	int read(char[] cbuf): Reads characters into an array.

o	void close(): Closes the reader.


4.	Writer Class:

o	void write(int c): Writes a single character.

o	void write(char[] cbuf): Writes a character array.

o	void close(): Closes the writer.

---

### 🧩 Buffered Streams (BufferedReader, BufferedWriter)
Buffered streams are used to optimize the performance of I/O operations by reducing the number of reads and writes. The buffer is a temporary storage area in memory that allows for faster I/O operations.

•	BufferedReader: Used to read text from a character-based stream.

•	BufferedWriter: Used to write text to a character-based stream.

**Example of Buffered Reader and Writer:**
```java
import java.io.BufferedReader;
import java.io.BufferedWriter;
import java.io.FileReader;
import java.io.FileWriter;
import java.io.IOException;

public class BufferedStreamExample {
    public static void main(String[] args) {
        try {
            // BufferedWriter
            BufferedWriter writer = new BufferedWriter(new FileWriter("output.txt"));
            writer.write("Hello, Buffered World!");
            writer.close();

            // BufferedReader
            BufferedReader reader = new BufferedReader(new FileReader("output.txt"));
            String line = reader.readLine();
            while (line != null) {
                System.out.println(line);  // Output: Hello, Buffered World!
                line = reader.readLine();
            }
            reader.close();
        } catch (IOException e) {
            e.printStackTrace();
        }
    }
}
```

---

### 🧑‍💻 Object Streams (Serialization and Deserialization)
Object streams allow reading and writing of Java objects (binary data). This is achieved through serialization and deserialization.

•	Serialization: The process of converting an object into a stream of bytes.

•	Deserialization: The process of converting the stream of bytes back into an object.

**Example of Serialization and Deserialization:**
```java
import java.io.*;

class Employee implements Serializable {
    int id;
    String name;

    Employee(int id, String name) {
        this.id = id;
        this.name = name;
    }
}

public class ObjectStreamExample {
    public static void main(String[] args) {
        // Serialization
        try {
            Employee emp = new Employee(1, "John Doe");
            ObjectOutputStream out = new ObjectOutputStream(new FileOutputStream("employee.dat"));
            out.writeObject(emp);
            out.close();
        } catch (IOException e) {
            e.printStackTrace();
        }

        // Deserialization
        try {
            ObjectInputStream in = new ObjectInputStream(new FileInputStream("employee.dat"));
            Employee emp = (Employee) in.readObject();
            in.close();
            System.out.println("Employee ID: " + emp.id + ", Name: " + emp.name);  // Output: Employee ID: 1, Name: John Doe
        } catch (IOException | ClassNotFoundException e) {
            e.printStackTrace();
        }
    }
}
```

---

### 💡 Additional I/O Stream Classes

•	DataInputStream and DataOutputStream: Used for reading and writing primitive data types (e.g., int, float, double, etc.).

•	PrintWriter: Used to print formatted representations of objects to a text-output stream.

•	RandomAccessFile: Allows reading from and writing to a file at a specific location (random access).

---

### 🧑‍💻 Summary

•	Byte Streams handle raw binary data, while Character Streams handle text data.

•	Buffered Streams enhance I/O performance by using a buffer.

•	Object Streams are used for serializing and deserializing Java objects.

•	Java provides a wide range of I/O classes, each designed for different types of data processing and storage operations.

________________________________________
________________________________________

## Applet Programming
Java applets are small applications that can be embedded in web pages. These programs are written in Java and are executed within a web browser or an applet viewer. While applets were once commonly used for adding interactive content to web pages, they have become obsolete with the rise of newer technologies like HTML5, JavaScript, and CSS. However, understanding applets can still be useful for legacy systems.

---

📚 **What is a Java Applet?**  
A Java applet is a special kind of Java program that is designed to be embedded within a web page. It runs in the context of a web browser and can provide dynamic, interactive content such as animations, games, and real-time data updates.  

- **Applet Life Cycle:** Applets have their own life cycle, which is managed by the browser or applet viewer. The life cycle consists of methods like `init()`, `start()`, `stop()`, and `destroy()`.  

---

🧑‍💻 **How Java Applet Works:**  
- The applet is embedded in an HTML page using the `<applet>` tag.  
- The Java Runtime Environment (JRE) is used to execute the applet.  
- The applet is initialized, started, stopped, and destroyed based on user interaction with the webpage or the browser.  

---

🔄 **Applet Life Cycle Methods**  
The life cycle of a Java applet includes several important methods. These methods are called by the browser or applet viewer when the applet is run, stopped, or removed.  

1. **init():**  
   - Called once when the applet is first loaded.  
   - Used to set up resources such as images or initial data.  

2. **start():**  
   - Called after `init()`, or whenever the applet is made visible again.  
   - Used to start animations, threads, or other activities.  

3. **stop():**  
   - Called when the applet is no longer visible or needs to be paused.  
   - Used to stop animations or threads.  

4. **destroy():**  
   - Called before the applet is destroyed or the browser is closed.  
   - Used to release resources or save data before the applet is removed.  

5. **paint(Graphics g):**  
   - Called whenever the applet needs to redraw its content.  
   - Used to display graphical content on the applet's window.  

---

🧑‍💻 **Basic Example of a Java Applet:**  
```java
import java.applet.Applet;
import java.awt.Graphics;

public class HelloWorldApplet extends Applet {
    // The init method is called once when the applet is loaded
    public void init() {
        setBackground(java.awt.Color.CYAN);  // Set background color
    }

    // The paint method is called whenever the applet needs to be redrawn
    public void paint(Graphics g) {
        g.drawString("Hello, World!", 20, 30);  // Display text on the applet window
    }
}
```

📝 **Explanation of the Example:**  
- `HelloWorldApplet` is a subclass of `Applet`.  
- `init()` is used to set the background color of the applet.  
- `paint(Graphics g)` is used to display the string `"Hello, World!"` at the specified coordinates `(20, 30)`.  

---

📊 **HTML Code to Embed the Applet:**  

```html
<!DOCTYPE html>
<html>
<head>
    <title>Java Applet Example</title>
</head>
<body>
    <h1>Java Applet Example</h1>
    <applet code="HelloWorldApplet.class" width="300" height="300">
        Your browser does not support Java Applets.
    </applet>
</body>
</html>
```

📝 **Explanation of the HTML Code:**  
- The `<applet>` tag specifies the location of the compiled Java applet file (`HelloWorldApplet.class`).  
- `width` and `height` set the size of the applet display area.  
- The text `"Your browser does not support Java Applets."` is displayed for browsers that don't support Java applets.  

---

🧑‍💻 **Java Applet with Interactivity:**  

```java
import java.applet.Applet;
import java.awt.Button;
import java.awt.event.ActionListener;
import java.awt.event.ActionEvent;

public class ButtonApplet extends Applet {
    Button btn;

    public void init() {
        btn = new Button("Click Me!");
        btn.setBounds(50, 50, 80, 30);  // Set position and size of the button
        btn.addActionListener(new ActionListener() {
            public void actionPerformed(ActionEvent e) {
                System.out.println("Button clicked!");  // Action when button is clicked
            }
        });
        add(btn);  // Add button to the applet
    }
}
```

📝 **Explanation of the Button Applet:**  
- `Button`: Creates a button with the label `"Click Me!"`.  
- `addActionListener()`: Adds an action listener to the button, which listens for the button click and performs an action (in this case, printing a message).  
- `add()`: Adds the button to the applet’s display area.  

---

🔧 **How to Run Java Applets:**  
To run a Java applet, follow these steps:  

1. **Compile the Applet:**  
   - Save your Java applet code in a file named `HelloWorldApplet.java`.  
   - Open the terminal or command prompt, navigate to the directory where the file is saved, and compile the applet using:  
     ```
     javac HelloWorldApplet.java
     ```  

2. **Run the Applet:**  
   - You can use the `appletviewer` command to run the applet without a browser.  
   - Create an HTML file as shown earlier.  
   - Use the following command to run the applet:  
     ```
     appletviewer HelloWorldApplet.html
     ```  

3. **Running in a Browser:**  
   - Older browsers had Java support, but modern browsers (like Chrome, Firefox, and Edge) no longer support Java applets due to security issues. It's recommended to use the `appletviewer` tool or migrate to modern technologies like JavaScript for web-based interactivity.  

---

⚠️ **Important Notes:**  
- **Security Concerns:** Java applets have been deprecated due to security vulnerabilities, and most modern browsers no longer support them. It is recommended to move away from using applets and consider alternatives like JavaFX or JavaScript for web-based interactions.  
- **Java Web Start:** Another technology for running Java applications on the web, which was introduced to replace applets, has also been discontinued as of JDK 9.  

---

⚡ **Conclusion:**  
- Java Applets were once a popular way to create interactive content for web pages but are now obsolete due to security concerns and lack of browser support.  
- The life cycle of applets includes initialization, starting, stopping, and destroying processes.  
- Modern web technologies like HTML5, JavaScript, and JavaFX have largely replaced applets for web-based applications.  

________________________________________
________________________________________

## AWT Programming  
The Abstract Window Toolkit (AWT) is a set of application programming interfaces (APIs) provided by Java to build graphical user interfaces (GUIs). It contains a collection of tools and libraries for creating windows, buttons, text boxes, and other interactive elements in Java applications.  

AWT was the original GUI framework for Java, though it has since been supplemented by Swing and JavaFX for more advanced graphical capabilities. Nevertheless, AWT is still widely used due to its simplicity and its ability to interact with native OS components.  

---  

📚 **Key Concepts in AWT:**  
1. **Components:**  
   - AWT provides a set of components (buttons, text fields, checkboxes, etc.) that are used to build the user interface.  
   - These components are containers that can hold other components, like panels or frames.  

2. **Container:**  
   - Containers are used to hold components. The `Frame` and `Panel` are examples of containers in AWT.  
   - They are responsible for the layout management and adding components to the GUI.  

3. **Event Handling:**  
   - AWT allows interaction between the user and the GUI via events.  
   - Events can be handled by implementing event listeners (like `ActionListener`, `MouseListener`, etc.).  

4. **Layout Managers:**  
   - AWT provides layout managers to manage the arrangement of components inside a container. Examples include `FlowLayout`, `GridLayout`, and `BorderLayout`.  

5. **Graphics Class:**  
   - AWT provides a `Graphics` class for drawing shapes, lines, and images on the GUI.  

---  

🧑‍💻 **Basic Structure of an AWT Application:**  
1. **Frame:** A top-level window with a title.  
2. **Component:** A button, text field, etc.  
3. **Event Handling:** Handling actions like button clicks.  

---  

🧑‍💻 **Example of an AWT Program:**  
```java
import java.awt.*;
import java.awt.event.*;

public class AWTExample extends Frame {
    // Constructor to set up the GUI components
    AWTExample() {
        // Setting the title of the frame
        setTitle("AWT Example");

        // Creating a button and setting its action
        Button btn = new Button("Click Me");
        btn.setBounds(50, 50, 100, 30); // Set button position and size

        // Adding the button to the frame
        add(btn);

        // Event handling for the button
        btn.addActionListener(new ActionListener() {
            public void actionPerformed(ActionEvent e) {
                System.out.println("Button Clicked!");
            }
        });

        // Setting layout to null (absolute positioning)
        setLayout(null);

        // Setting frame size
        setSize(400, 400);

        // Making the frame visible
        setVisible(true);
    }

    // Main method to run the application
    public static void main(String[] args) {
        new AWTExample(); // Creating an instance of AWTExample (frame)
    }
}
```

📝 **Explanation of the AWT Example:**  
1. **Frame Creation:**  
   - `Frame` is the top-level container (window) for the app.  
   - We create a `Button` component and add it to the frame.  

2. **Button and Event Handling:**  
   - We create a `Button` labeled `"Click Me"` and specify its position and size using `setBounds()`.  
   - An `ActionListener` is added to the button, which listens for clicks. When clicked, a message is printed to the console.  

3. **Visibility and Layout:**  
   - We set the frame's layout to `null` to control component positioning manually (absolute positioning).  
   - `setSize()` specifies the window size, and `setVisible(true)` makes the frame visible.  

---  

🧑‍💻 **AWT Layout Managers**  
AWT provides several built-in layout managers that define how components are arranged within containers. The common ones include:  

1. **FlowLayout:**  
   - Components are arranged in a left-to-right flow (like a line).  
   - Components will automatically wrap to the next line if the container’s width is exceeded.  
   ```java
   setLayout(new FlowLayout());
   ```  

2. **BorderLayout:**  
   - The container is divided into five regions: `North`, `South`, `East`, `West`, and `Center`.  
   ```java
   setLayout(new BorderLayout());
   add(btn, BorderLayout.CENTER); // Place button in the center
   ```  

3. **GridLayout:**  
   - A grid of rows and columns. Every component has the same size and is placed into the grid cells.  
   ```java
   setLayout(new GridLayout(2, 2)); // 2 rows, 2 columns
   ```  

4. **CardLayout:**  
   - Useful for creating tabbed panels or pages where only one component is visible at a time.  
   ```java
   setLayout(new CardLayout());
   ```  

---  

🧑‍💻 **AWT Event Handling Example:**  
```java
import java.awt.*;
import java.awt.event.*;

public class AWTEventHandling extends Frame {
    // Constructor for setting up GUI
    AWTEventHandling() {
        setTitle("AWT Event Handling");

        // Create components
        Button btn = new Button("Click Me");
        btn.setBounds(50, 50, 100, 30);

        // Register event listener for the button
        btn.addActionListener(new ActionListener() {
            public void actionPerformed(ActionEvent e) {
                // Action performed when the button is clicked
                System.out.println("Button Clicked!");
            }
        });

        // Add the button to the frame
        add(btn);

        setLayout(null);
        setSize(400, 400);
        setVisible(true);
    }

    // Main method to start the application
    public static void main(String[] args) {
        new AWTEventHandling(); // Create frame instance
    }
}
```

📝 **Explanation of Event Handling:**  
- **ActionListener:** This listener handles events generated by the button. When the button is clicked, the `actionPerformed()` method is triggered.  
- **Event Handling Process:**  
  - The event (button click) triggers a listener that performs an action (printing to the console).  

---  

⚡ **AWT Graphics Example:**  
AWT also allows drawing graphics on the window using the `Graphics` class. Here's an example of drawing a rectangle:  
```java
import java.awt.*;

public class AWTGraphics extends Frame {
    public void paint(Graphics g) {
        g.setColor(Color.RED); // Set drawing color
        g.fillRect(50, 50, 100, 100); // Draw a filled rectangle
    }

    public static void main(String[] args) {
        AWTGraphics app = new AWTGraphics();
        app.setSize(400, 400);
        app.setVisible(true);
    }
}
```

📝 **Explanation of Graphics:**  
- **Graphics Object:** It allows drawing shapes such as rectangles, lines, text, and images.  
- **fillRect():** This method draws a filled rectangle with specified width and height at a given `(x, y)` position.  

---  

⚠️ **Important Considerations:**  
- **Threading:** In AWT, the GUI components run on the **Event Dispatch Thread (EDT)**. All GUI updates should be performed on the EDT to avoid concurrency issues.  
- **AWT vs. Swing:** While AWT is simpler, **Swing** (built on top of AWT) provides more flexible, rich, and cross-platform GUI components. Swing is typically preferred for modern Java GUI applications.  

---  

⚡ **Conclusion:**  
AWT (Abstract Window Toolkit) provides the foundational tools for building graphical user interfaces in Java. Though it is largely replaced by Swing and JavaFX, it is still useful for understanding the core concepts of Java GUI development. AWT allows for creating windows, adding components, and handling user interactions, all of which are essential in building desktop applications in Java.    

________________________________________

## AWT Programming

The Abstract Window Toolkit (AWT) is a set of application programming interfaces (APIs) provided by Java to build graphical user interfaces (GUIs). It contains a collection of tools and libraries for creating windows, buttons, text boxes, and other interactive elements in Java applications.

AWT was the original GUI framework for Java, though it has since been supplemented by Swing and JavaFX for more advanced graphical capabilities. Nevertheless, AWT is still widely used due to its simplicity and its ability to interact with native OS components.

---

### 📚 Key Concepts in AWT:

1. **Components:**
   - AWT provides a set of components (buttons, text fields, checkboxes, etc.) that are used to build the user interface.
   - These components are containers that can hold other components, like panels or frames.

2. **Container:**
   - Containers are used to hold components. The Frame and Panel are examples of containers in AWT.
   - They are responsible for the layout management and adding components to the GUI.

3. **Event Handling:**
   - AWT allows interaction between the user and the GUI via events.
   - Events can be handled by implementing event listeners (like ActionListener, MouseListener, etc.).

4. **Layout Managers:**
   - AWT provides layout managers to manage the arrangement of components inside a container. Examples include FlowLayout, GridLayout, and BorderLayout.

5. **Graphics Class:**
   - AWT provides a Graphics class for drawing shapes, lines, and images on the GUI.

---

### 🧑‍💻 Basic Structure of an AWT Application:
1. **Frame:** A top-level window with a title.
2. **Component:** A button, text field, etc.
3. **Event Handling:** Handling actions like button clicks.

---

### 🧑‍💻 Example of an AWT Program:
```java
import java.awt.*;
import java.awt.event.*;

public class AWTExample extends Frame {
    // Constructor to set up the GUI components
    AWTExample() {
        // Setting the title of the frame
        setTitle("AWT Example");

        // Creating a button and setting its action
        Button btn = new Button("Click Me");
        btn.setBounds(50, 50, 100, 30); // Set button position and size

        // Adding the button to the frame
        add(btn);

        // Event handling for the button
        btn.addActionListener(new ActionListener() {
            public void actionPerformed(ActionEvent e) {
                System.out.println("Button Clicked!");
            }
        });

        // Setting layout to null (absolute positioning)
        setLayout(null);

        // Setting frame size
        setSize(400, 400);

        // Making the frame visible
        setVisible(true);
    }

    // Main method to run the application
    public static void main(String[] args) {
        new AWTExample(); // Creating an instance of AWTExample (frame)
    }
}
```

---

### 📝 Explanation of the AWT Example:
1. **Frame Creation:**
   - Frame is the top-level container (window) for the app.
   - We create a Button component and add it to the frame.

2. **Button and Event Handling:**
   - We create a Button labeled "Click Me" and specify its position and size using setBounds().
   - An ActionListener is added to the button, which listens for clicks. When clicked, a message is printed to the console.

3. **Visibility and Layout:**
   - We set the frame's layout to null to control component positioning manually (absolute positioning).
   - setSize() specifies the window size, and setVisible(true) makes the frame visible.

---

### 🧑‍💻 AWT Layout Managers
AWT provides several built-in layout managers that define how components are arranged within containers. The common ones include:

1. **FlowLayout:**
   - Components are arranged in a left-to-right flow (like a line).
   - Components will automatically wrap to the next line if the container's width is exceeded.
   ```java
   setLayout(new FlowLayout());
   ```

2. **BorderLayout:**
   - The container is divided into five regions: North, South, East, West, and Center.
   ```java
   setLayout(new BorderLayout());
   add(btn, BorderLayout.CENTER); // Place button in the center
   ```

3. **GridLayout:**
   - A grid of rows and columns. Every component has the same size and is placed into the grid cells.
   ```java
   setLayout(new GridLayout(2, 2)); // 2 rows, 2 columns
   ```

4. **CardLayout:**
   - Useful for creating tabbed panels or pages where only one component is visible at a time.
   ```java
   setLayout(new CardLayout());
   ```

---

### 🧑‍💻 AWT Event Handling Example:
```java
import java.awt.*;
import java.awt.event.*;

public class AWTEventHandling extends Frame {
    // Constructor for setting up GUI
    AWTEventHandling() {
        setTitle("AWT Event Handling");

        // Create components
        Button btn = new Button("Click Me");
        btn.setBounds(50, 50, 100, 30);

        // Register event listener for the button
        btn.addActionListener(new ActionListener() {
            public void actionPerformed(ActionEvent e) {
                // Action performed when the button is clicked
                System.out.println("Button Clicked!");
            }
        });

        // Add the button to the frame
        add(btn);

        setLayout(null);
        setSize(400, 400);
        setVisible(true);
    }

    // Main method to start the application
    public static void main(String[] args) {
        new AWTEventHandling(); // Create frame instance
    }
}
```

---

### 📝 Explanation of Event Handling:
- **ActionListener:** This listener handles events generated by the button. When the button is clicked, the actionPerformed() method is triggered.
- **Event Handling Process:**
  - The event (button click) triggers a listener that performs an action (printing to the console).

---

### ⚡ AWT Graphics Example:
AWT also allows drawing graphics on the window using the Graphics class. Here's an example of drawing a rectangle:
```java
import java.awt.*;

public class AWTGraphics extends Frame {
    public void paint(Graphics g) {
        g.setColor(Color.RED); // Set drawing color
        g.fillRect(50, 50, 100, 100); // Draw a filled rectangle
    }

    public static void main(String[] args) {
        AWTGraphics app = new AWTGraphics();
        app.setSize(400, 400);
        app.setVisible(true);
    }
}
```

---

### 📝 Explanation of Graphics:
- **Graphics Object:** It allows drawing shapes such as rectangles, lines, text, and images.
- **fillRect():** This method draws a filled rectangle with specified width and height at a given (x, y) position.
---
### ⚠️ Important Considerations:
- **Threading:** In AWT, the GUI components run on the Event Dispatch Thread (EDT). All GUI updates should be performed on the EDT to avoid concurrency issues.
- **AWT vs. Swing:** While AWT is simpler, Swing (built on top of AWT) provides more flexible, rich, and cross-platform GUI components. Swing is typically preferred for modern Java GUI applications.
---
### ⚡ Conclusion:
AWT (Abstract Window Toolkit) provides the foundational tools for building graphical user interfaces in Java. Though it is largely replaced by Swing and JavaFX, it is still useful for understanding the core concepts of Java GUI development. AWT allows for creating windows, adding components, and handling user interactions, all of which are essential in building desktop applications in Java.

________________________________________
________________________________________

## Swing Programming

Swing is a part of Java's Abstract Window Toolkit (AWT) and is used to create graphical user interfaces (GUIs) for Java applications. Swing is an advanced version of AWT with many more features and a richer set of components. Unlike AWT, which relies on the native OS for GUI rendering, Swing is written entirely in Java, which means it is platform-independent and provides a consistent appearance across different operating systems.

---

### Key Features of Swing:
- **Pluggable Look and Feel (PLAF):** Change the GUI appearance without modifying application logic
- **Lightweight components:** Don't rely on OS-specific resources, providing consistent cross-platform experience
- **Rich component set:** More sophisticated UI elements than AWT
- **Customizable:** Extensive control over component appearance and behavior

---

### Key Components of Swing
| Component | Description |
|-----------|-------------|
| `JFrame` | Main window container |
| `JButton` | Clickable button |
| `JLabel` | Text/image display |
| `JTextField` | Single-line text input |
| `JTextArea` | Multi-line text input |
| `JComboBox` | Drop-down selection list |
| `JPanel` | Container for grouping components |
| `JRadioButton` | Single selection option |
| `JCheckBox` | Multiple selection option |

---

### Swing vs AWT Comparison
| Feature | AWT | Swing |
|---------|-----|-------|
| Rendering | Native OS | Pure Java |
| Components | Heavyweight | Lightweight |
| Look & Feel | OS-dependent | Consistent across platforms |
| Customization | Limited | Extensive |
| Performance | Faster | Slightly slower |

---

### Basic Swing Program Example
```java
import javax.swing.*;
import java.awt.event.*;

public class SwingExample extends JFrame {
    
    SwingExample() {
        setTitle("Swing Example");
        JButton button = new JButton("Click Me");
        
        button.addActionListener(e -> 
            System.out.println("Button was clicked!"));
        
        setLayout(null);
        button.setBounds(100, 100, 150, 30);
        add(button);
        
        setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        setSize(400, 400);
        setVisible(true);
    }

    public static void main(String[] args) {
        new SwingExample();
    }
}
```
---

### Swing Layout Managers
1. **FlowLayout** (Default)
   ```java
   setLayout(new FlowLayout());
   ```
   - Left-to-right component flow
   - Wraps to next line when space runs out

2. **BorderLayout**
   ```java
   setLayout(new BorderLayout());
   add(component, BorderLayout.CENTER);
   ```
   - Five regions: NORTH, SOUTH, EAST, WEST, CENTER

3. **GridLayout**
   ```java
   setLayout(new GridLayout(2, 3)); // 2 rows, 3 columns
   ```
   - Equal-sized cells in grid pattern

4. **BoxLayout**
   ```java
   setLayout(new BoxLayout(getContentPane(), BoxLayout.Y_AXIS));
   ```
   - Vertical or horizontal component arrangement

### Event Handling in Swing
```java
JButton button = new JButton("Action");
button.addActionListener(e -> {
    // Handle button click
});

button.addMouseListener(new MouseAdapter() {
    public void mouseClicked(MouseEvent e) {
        // Handle mouse click
    }
});
```
---

### Common Swing Components
1. **JLabel**
   ```java
   JLabel label = new JLabel("Information", SwingConstants.CENTER);
   ```

2. **JTextField**
   ```java
   JTextField field = new JTextField(20); // 20 columns wide
   ```

3. **JTextArea**
   ```java
   JTextArea area = new JTextArea(5, 20); // 5 rows, 20 columns
   JScrollPane scrollPane = new JScrollPane(area);
   ```

4. **JComboBox**
   ```java
   String[] options = {"Option 1", "Option 2"};
   JComboBox<String> comboBox = new JComboBox<>(options);
   ```

5. **JCheckBox**
   ```java
   JCheckBox checkBox = new JCheckBox("I agree");
   ```

6. **JRadioButton**
   ```java
   ButtonGroup group = new ButtonGroup();
   JRadioButton rb1 = new JRadioButton("Option 1");
   JRadioButton rb2 = new JRadioButton("Option 2");
   group.add(rb1);
   group.add(rb2);
   ```
---

### Changing Look and Feel
```java
try {
    // Set Nimbus look and feel
    UIManager.setLookAndFeel("javax.swing.plaf.nimbus.NimbusLookAndFeel");
    
    // Or use system default
    // UIManager.setLookAndFeel(UIManager.getSystemLookAndFeelClassName());
    
    SwingUtilities.updateComponentTreeUI(frame); // Update existing frames
} catch (Exception e) {
    e.printStackTrace();
}
```
---

### Best Practices
1. Always execute Swing code on the Event Dispatch Thread (EDT):
   ```java
   SwingUtilities.invokeLater(() -> {
       // GUI creation code here
   });
   ```

2. Use model-view-controller (MVC) pattern for complex applications

3. Consider using JavaFX for modern applications (Swing is legacy)

---

### Conclusion
Swing provides:
- Rich set of GUI components
- Cross-platform consistency
- Flexible layout management
- Customizable appearance
- Event-driven programming model

While newer technologies like JavaFX exist, Swing remains widely used for:
- Legacy applications
- Simple desktop GUIs
- Applications requiring mature, stable GUI components

________________________________________
________________________________________
