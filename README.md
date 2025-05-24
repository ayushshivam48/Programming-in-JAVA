# Programming in Java

## Introduction to Java

### 🌟 What is Java?
Java is a high-level, object-oriented, platform-independent programming language developed by James Gosling at Sun Microsystems (now owned by Oracle) and released in 1995.

The philosophy behind Java:
"Write Once, Run Anywhere" (WORA) – meaning you can write Java code once and run it on any platform that supports Java without needing to recompile.

________________________________________

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

________________________________________

### ⚙️ How Java Works
1. Source Code (.java) → Written by the programmer
2. Compiled into Bytecode (.class) using the Java Compiler (javac)
3. Bytecode is run on the JVM (java ClassName), making it platform-independent

Java Code → Compiled → Bytecode → JVM → Output

________________________________________

### 🧱 Basic Java Program Example


public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}

Explanation:
•	public class HelloWorld → Class declaration
•	public static void main → Entry point of the program
•	System.out.println() → Prints output to console

________________________________________

🧠 Java Editions
1.	Java SE (Standard Edition) – for core functionality (apps, desktop)
2.	Java EE (Enterprise Edition) – for web and enterprise apps (now Jakarta EE)
3.	Java ME (Micro Edition) – for embedded and mobile devices

---

## Java Programming Steps
### 🔟 10 Essential Steps in Java Programming
________________________________________
### 1. Install Java Development Kit (JDK)
Download and install the JDK. It includes:  
•	Java Compiler (javac)  
•	Java Runtime Environment (JRE)  
•	Java Virtual Machine (JVM)  
________________________________________
### 2. Set Up Environment Variables (Optional but useful)
Add the `bin` folder of your JDK to the system PATH so you can use `javac` and `java` from any terminal/command prompt.  
________________________________________
### 3. Write the Java Code
Use any text editor (Notepad, VS Code, IntelliJ IDEA, etc.)  

**Example (HelloWorld.java):**

public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, Java!");
    }
}

________________________________________

### 4. Save the File
• Save with `.java` extension  
• Filename must match the public class name (e.g., `HelloWorld.java`)  

________________________________________

### 5. Open Command Prompt / Terminal
Navigate to the folder where your `.java` file is saved.  

________________________________________

### 6. Compile the Code
Use:  

javac HelloWorld.java

✅ If successful, this creates a `HelloWorld.class` bytecode file.

________________________________________

### 7. Run the Program
**Use:**

java HelloWorld

⏩ This runs the `.class` file using the Java Virtual Machine (JVM).

🖨️ **Output:**

Hello, Java!


________________________________________

### 8. Debug if Needed
If you encounter errors:
1. **Read** the error message carefully
2. **Correct** your code
3. **Recompile** and **rerun** (repeat steps 6-7)

Common error types:
- Syntax errors (missing semicolons, brackets)
- Runtime errors (NullPointerException)
- Logical errors (incorrect program logic)

________________________________________

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

________________________________________

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


## Java Tools and Resources

Java programming involves various tools that support the full development lifecycle — from writing and compiling code to testing, debugging, and deploying applications. These tools boost productivity, manage complexity, and help ensure reliability.

________________________________________

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

________________________________________

### 💻 2. IDEs (Integrated Development Environments)
Modern IDEs make Java programming more efficient and user-friendly.

| IDE             | Features                              | Best For                          |
|-----------------|---------------------------------------|-----------------------------------|
| IntelliJ IDEA   | Smart code completion, Spring support | Web & enterprise development      |
| Eclipse         | Plugin-based, large community         | Large enterprise applications      |
| NetBeans        | Simple UI, built-in GUI designer      | Beginners and desktop apps        |
| VS Code         | Lightweight, Java extensions          | Simple to mid-level projects      |

🟢 **Importance**: IDEs help you write, debug, and run Java programs with features like autocomplete, error hints, and integrated terminals.

________________________________________

### ⚙️ 3. Build Tools
Build tools automate tasks like compiling code, managing libraries, and packaging applications.

| Tool    | Features                     | Example Use               |
|---------|------------------------------|---------------------------|
| Maven   | XML config (pom.xml)         | Web apps, Spring Boot     |
| Gradle  | Groovy/Kotlin DSL            | Android and microservices |
| Ant     | XML config, flexible scripting | Legacy projects         |

🟢 **Importance**: These tools make project builds repeatable and easy, especially when many libraries and files are involved.

________________________________________

### 🧪 4. Testing Tools
Testing is vital to ensure your application behaves correctly.

| Tool     | Use Case            | Description                          |
|----------|---------------------|--------------------------------------|
| JUnit    | Unit Testing        | Verifies methods and logic           |
| TestNG   | Advanced Testing    | Allows grouping and parallel testing |
| Mockito  | Mocking             | Simulates objects for testing        |

🟢 **Importance**: Helps catch bugs early and maintain code quality.

________________________________________

### 🖥️ 5. GUI Development Tools
Used to create desktop-based graphical user interfaces (GUIs).

| Tool     | Description                          | Use                          |
|----------|--------------------------------------|------------------------------|
| JavaFX   | Modern UI with CSS-like styling      | Rich desktop applications    |
| Swing    | Older, simple UI toolkit             | Legacy or academic projects  |

🟢 **Importance**: Enables you to build interactive, user-friendly applications.

________________________________________

### 🌐 6. Web & Enterprise Tools
Used for creating scalable web apps and enterprise software.

| Tool            | Description                          | Use                          |
|-----------------|--------------------------------------|------------------------------|
| Spring Boot     | Simplifies backend/web app creation  | REST APIs, microservices     |
| Apache Tomcat   | Java servlet container               | Runs Java-based web apps     |
| Hibernate       | ORM tool for database connectivity   | Data persistence without SQL |

🟢 **Importance**: These tools power modern web applications and enterprise-grade systems.

________________________________________

### 🧠 How These Tools Work in a Java Project (Step-by-Step)
1. **Write Code** – In an IDE like IntelliJ or Eclipse  
2. **Compile Code** – Using javac or the IDE's internal compiler  
3. **Run Program** – Via java command or IDE Run button  
4. **Test Code** – With JUnit or TestNG to verify functionality  
5. **Debug Issues** – Using jdb or graphical debugger in IDE  
6. **Add Libraries** – Using Maven or Gradle to manage dependencies  
7. **Package App** – With jar or Maven to distribute  
8. **Deploy/Run App** – On servers like Apache Tomcat or in a JAR file  

________________________________________

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

## Java Applet Programming

### 🧭 What is a Java Applet?
A Java Applet is a small Java program that is embedded in a web page and runs inside a web browser using the Java plugin.

⚠️ **Note**: Applets were widely used in the past for web-based interactive programs (like animations or calculators), but they are now obsolete due to modern web technologies and browser security restrictions.

________________________________________

### 🧱 Key Features of Java Applets
- GUI-based Java programs that run inside browsers
- Inherit from `java.applet.Applet` class (or `javax.swing.JApplet` for Swing-based)
- Can display graphics, handle events, and interact with the user
- No `main()` method — they use lifecycle methods

________________________________________

### 🔄 Applet Lifecycle Methods
Java applets have predefined lifecycle methods:

| Method            | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `init()`          | Called once when the applet starts — initialize resources                   |
| `start()`         | Called each time the applet becomes visible or gains focus                  |
| `stop()`          | Called when the applet is no longer visible                                |
| `destroy()`       | Called when the applet is removed from memory                              |
| `paint(Graphics g)` | Called to draw content (text, shapes, etc.) on the screen                 |

________________________________________

### 🧑‍💻 Example: A Simple Java Applet

import java.applet.Applet;
import java.awt.Graphics;

/* <applet code="HelloApplet.class" width="300" height="100"></applet> */
public class HelloApplet extends Applet {
    public void paint(Graphics g) {
        g.drawString("Hello from Java Applet!", 50, 50);
    }
}

________________________________________

### ✅ Steps to Run a Java Applet

1. **Save** as `HelloApplet.java`
2. **Compile**:

   javac HelloApplet.java

3.	Create an HTML file (HelloApplet.html):
<html>
<body>
    <applet code="HelloApplet.class" width="300" height="100"></applet>
</body>
</html>

4.	Run in Applet Viewer:
appletviewer HelloApplet.html

🛑 Modern browsers no longer support applets. Use `appletviewer` from the JDK for testing:

appletviewer YourApplet.html

________________________________________

### 📋 Historical Use Cases of Java Applets

- **Educational Tools**  
  Math and physics simulations, interactive learning modules
- **Web Utilities**  
  Small games, calculators, and other interactive tools
- **Visualizations**  
  Interactive diagrams, charts, and data visualizations

________________________________________

### ❌ Reasons for Applet Deprecation

| Issue | Impact | Modern Solution |
|-------|--------|-----------------|
| Java Plugin Requirement | No longer supported by browsers | Native browser technologies |
| Security Vulnerabilities | Sandboxing limitations | Modern security frameworks |
| Technology Obsolescence | Replaced by better alternatives | HTML5, JavaScript, WebAssembly |

________________________________________

### ✅ Modern Replacement Technologies

| Category | Technology Stack | Key Benefits |
|----------|------------------|--------------|
| Desktop Applications | JavaFX, Swing | Rich GUI capabilities |
| Web Applications | HTML5 + React/Vue | Cross-platform compatibility |
| Backend Services | Spring Boot | Microservices architecture |
| Animations/Graphics | Canvas/WebGL | Hardware-accelerated rendering |

________________________________________

### 📌 Java Applet Technical Summary

| Aspect | Details | Current Status |
|--------|---------|----------------|
| Base Class | `java.applet.Applet`<br>`javax.swing.JApplet` | Removed in Java 17 |
| Lifecycle Methods | `init()`, `start()`, `stop()`,<br>`destroy()`, `paint()` | Legacy only |
| Execution Model | Browser plugin | Discontinued |
| Modern Path | Java Web Start (also deprecated) | Self-contained apps |

> **Important Note**: All applet-related APIs were removed in Java SE 17 (JEP 398). For historical reference only.

________________________________________

## Encapsulation in Java

### 🔐 What is Encapsulation?
Encapsulation is the concept of wrapping data (variables) and code (methods) together as a single unit — like a capsule. It restricts direct access to some of the object's components, which is useful for protecting data from unwanted changes.

✅ **Analogy**: Think of it like a capsule of medicine — everything is sealed inside and accessed in a controlled way.

________________________________________

### 🧠 Key Concepts of Encapsulation in Java:
1. **Private Variables**: The class variables are declared as private
2. **Public Getter and Setter Methods**: These methods are used to read and update private variables

________________________________________

### 🧑‍💻 Java Example: Encapsulation

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

________________________________________

### Usage Example:

public class Main {
    public static void main(String[] args) {
        Student s = new Student();
        s.setName("Anjali");
        s.setAge(20);

        System.out.println("Name: " + s.getName());
        System.out.println("Age: " + s.getAge());
    }
}

________________________________________

### 🎯 Why is Encapsulation Important?

| Benefit           | Explanation                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| ✅ Data Hiding    | Prevents unauthorized access and modification of data                        |
| ✅ Security       | Sensitive information is protected inside the class                         |
| ✅ Code Flexibility | You can change code internally without affecting external code              |
| ✅ Control        | You can add validation logic in setter methods                              |
| ✅ Reusability    | Easily maintain and reuse encapsulated classes in other programs            |

________________________________________

### 🏁 Real-Life Example
**ATM Machine Analogy**:
- Your account balance is private (hidden data)
- You enter your PIN to access it (public method)
- The system validates before granting access (controlled access)

*This demonstrates encapsulation in real-world systems!*

________________________________________

### 🔁 Summary of Key Terms

| Term             | Definition                                                                 |
|------------------|---------------------------------------------------------------------------|
| Encapsulation    | Bundling data and methods that operate on that data within a single unit   |
| Data Hiding      | Restricting direct access to an object's internal representation          |
| Private          | Access modifier that restricts visibility to the containing class only    |
| Getter/Setter    | Public methods that provide controlled access to private fields           |

> **Note**: Encapsulation is one of the four fundamental OOP concepts, along with inheritance, polymorphism, and abstraction.

________________________________________
