# Hello-World-Cpp-JNI Southern New Hampshire University Assignment
 integrates C++ with Java through the JNI

Embedding languages in other languages can allow the strengths of each language work with each other in certain projects. This school assignment allowed me to learn some of the pros and cons of utilizing C++, Java, and Python for various use cases.

When asked:
What are some advantages and disadvantages of C++, Java, and Python?
How would you make your selection? What criteria would you consider and why?
Why might you integrate different languages, such as C++ and Java, in a project?
How would your decision impact the security of a program?
I replied:
From my reading, I've found some advantages and disadvantages of C++, Java, and Python to be:

ADVANTAGES:

C++ is a very efficient language that includes a mix of paradigms including: procedural, object oriented, generic, and functional programming. It is also a language that can be implemented in many different areas such as the development of operating systems, device drivers, embedded software, high performance applications, and video games.

Java was influenced strongly by C and C++ though it aimed to simplify C++ in its implementation. Java removed pointers and also introduced Garbage Collection which aids with memory management automatically. Java is able to be run on any device with the Java Virtual Machine (JVM). Because Java shows errors during compile time, unit testing is short.

Python allows the programmer to code "simply". That is to say the aim of the language is to express an idea in code using fewer lines compared to other languages like C++ or Java. It is also easily embeddable into any application while also being useful for full-fledged applications. Python is useful for rapid development.

DISADVANTAGES: 

C++ has no garbage collector and thus it is the programmer's responsibility to manage memory responsibly. The syntax of C++ can be complex as well which can increase the difficulty of code maintenance and finding syntax errors. 

Java performance is not as efficient as other languages because it is not a natively executed language. Java also has a bigger memory footprint. It is not a suitable language for real-time systems.

Python's performance tends to suffer especially in real-time/embedded applications due to its dynamic typing and the presence of a Virtual Machine. 

When making the selection for which language to use in a project you should consider the length of the development, the scope of the application, and the use of the program. For development of windows applications or device drivers, real-time systems and embedded systems C++ is an appropriate choice. For projects that need to be on many different platforms are a good fit for Java and projects which need to be produced quickly or that should be embedded into other applications are generally fit for Python.

You might integrate different languages the issue of a language being apt for one aspect of a project but having performance issues in another aspect that could be improved by utilizing an integrated language. You may also want to reuse legacy code, directly access hardware or do other low-level activities, or utilize tools that are not available in the language your are integrating into. 

Deciding to integrate different languages can impact the security of the program- in C++ for example, pointer safety is compromised. It is important to consider your code may also lose portability.
