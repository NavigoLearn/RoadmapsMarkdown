# Embedded Systems

## Description

This road map gives a general overview of the concepts you will need to know to become an Embedded Systems Engineer. As an embedded system engineer, it is your job to design, implement, and debug the software and hardware components of an embedded system. This requires a strong understanding of electronics, programming languages and computer architecture. The topics have been carefully selected to reflect standard requirements of an Embedded Systems Engineer. A lot of passion and determination will be required of you to succeed in this field.

## What is an Embedded System?

An embedded system is a combination of computer hardware and software components, and perhaps additional mechanical or other parts, designed to perform a dedicated function. In some cases, embedded systems are part of a larger system or product, as in the case of an antilock braking system in a car. [Embedded Systems Glossary](https://barrgroup.com/embedded-systems/glossary-e)

> **This roadmap contains paths to learning both software and hardware components for an absolute beginner. If you are already familiar with any concepts/tools, you can reinforce your knowledge quickly and move to the unfamiliar**

## Essential Hardware prerequisites

- **Basic Math and Calculus**
  - Ideally you should have a strong foundation in mathematics, particularly in areas such as algebra, calculus, and discrete mathematics. Knowledge of algebra is important in understanding and manipulating mathematical expressions, while calculus is essential for dealing with continuous signals and control systems. [Khan Academy](https://www.khanacademy.org/math/calculus-1)
- **Electric Circuits Fundamantals**
  - The knowledge of electric circuits is crucial in embedded systems engineering because it forms the foundation for designing, analyzing, and troubleshooting hardware components. [Electronics](https://www.electronics-tutorials.ws/), [Electronic Components](https://www.elprocus.com/major-electronic-components/)
- **Electronics Fundamentals**
  - Understanding of electronics is vital in embedded systems engineering for designing hardware, microcontrollers, sensors, actuators, circuits, and PCBs. You will learn about efficient power management, signal processing, and integration of analog and digital components as well as troubleshotting, safety and reliability. [All About Circuits](https://www.allaboutcircuits.com/textbook/), [Electronics Basics (Youtube)](https://youtube.com/playlist?list=PLAROrg3NQn7cyu01HpOv5BWo217XWBZu0)
- **Digital Circuits and Logic Design**
  - This involves creating and analyzing digital systems using logic gates, Boolean algebra, and sequential elements. It encompasses designing circuits, such as multiplexers, flip-flops, and memory systems, essential for building computers and embedded systems. [FPGA - NandLand](https://nandland.com/fpga-101/), [Digital Design](https://tinytapeout.com/digital_design/)

## Recommended Path

- **Programming Knowledge**
  - A solid foundation in at least one of the following programming languages such as **C** or **C++** is required in this field. Languages such as **Assembly**, **Python**, **Rust** and **Java** are also popular in this field.
  - **C**
    - **C** is a versatile and widely-used procedural programming language. It is known for its efficiency and simplicity, it allows low-level memory manipulation and high-level abstraction. It is the foundation for many operating systems and software applications and it is well known for its performance, portability, and influence on other programming languages.
      - [W3 Schools](https://www.w3schools.com/c/index.php)
      - [C for Beginners (Youtube)](https://www.youtube.com/watch?v=ssJY5MDLjlo)
  - **C++**
    - **C++** is a powerful, general-purpose programming language. It is efficient, versatile and supports both procedural and object-oriented paradigms making it popular for system software, game development and embedded systems.
      - [W3 Schools](https://www.w3schools.com/cpp/default.asp)
      - [C++ for Beginners (Youtube)](https://www.youtube.com/watch?v=vLnPwxZdW4Y)
  - **Assembly**
    - This is a low-level programming language represents machine code in a more human-readable format. It interacts with the computer's hardware and provide more precise control over processor operations and memory utilization.
      - [Assembly Language Tutorial](https://www.tutorialspoint.com/assembly_programming/index.htm)
- **Data Structures and Algorithms**
  - Data Structures are simply just a way of organizing and storing data while algorithms is the step-by-step approach of solving a problem. If you want to be able to achieve efficient software solutions, knowledge of this is a must!
    - [Grokking Algorithms](https://www.manning.com/books/grokking-algorithms)
    - [Data Structures - Using C/C++ (Youtube)](https://www.youtube.com/watch?v=B31LgI4Y4DQ)
- **Design Patterns**
  - To ensure reuseablility and maintainability, having knowledge of proven, reliable solutions to recurring challenges will save you a alot of headaches.
    - [Design Patterns for Embedded Systems in C](https://repositorio.uci.cu/jspui/bitstream/123456789/10139/1/Design%20Patterns%20for%20Embedded%20Systems%20in%20C_%20An%20Embedded%20Software%20Engineering%20Toolkit%20%28%20PDFDrive%20%29.pdf)
- **State Machines / UML**
  - State machines are models used in embedded systems to represent the behavior of a component. UML (**_Unified Modeling Language_**) is a standardized notation used to design, visualize, and document the structure of software systems
    - [State Machines (Youtube)](https://www.youtube.com/playlist?list=PLPW8O6W-1chxym7TgIPV9k5E8YJtSBToI)
    - [Embedded System Design using UML State Machines](https://www.udemy.com/course/embedded-system-design-using-uml-state-machines/)
- **Version Control**
  - **How to use Git**
    - Git is a version control system used to track changes in code repositories, you can collaborate and so much more [Git For Beginners in 1 hour](https://www.youtube.com/watch?v=8JJ101D3knE)
- **Build Tools**
  - **GCC, Make & CMake**
    - GCC (**_GNU Compiler Collection_**) is a versatile compiler system that supports programming languages like C/C++. Make is a build automation tool, it simplifies the compilation process and manage dependencies. CMake is a cross-platform build system that allows for efficient building, testing and packaging software
      - [GCC and Make with C/C++ Applications](https://www3.ntu.edu.sg/home/ehchua/programming/cpp/gcc_make.html)
      - [Building STM32 projects with cross platform tools like Make, CMake (YouTube )](https://www.youtube.com/playlist?list=PLEg2mgYz66IOcHRvvUDf9O1ZCGy58M1Bt)
      - [CMake Tutorial](https://cmake.org/cmake/help/latest/guide/tutorial/index.html)
  - **Docker**
    Docker allows developers package and run applications in lightweight, isolated containers
    - [Docker Documentation](https://docs.docker.com/get-started/)
    - [Introduction to Docker for the Embedded Developer](https://www.youtube.com/watch?v=Fz7ou-VBk-w)
- **Microcontrollers**
  - **_What is a microcontroller?_**
    - It is a compact computer on a single integrated circuit. It contains a processor, memory, I/O peripherals.
    - [What is a Microcontroller?](https://www.allaboutcircuits.com/technical-articles/what-is-a-microcontroller-introduction-component-characteristics-component/)
    - [Fundamentals of Microcontrollers - Arduino bare-metal breakdown (YouTube)](https://www.youtube.com/playlist?list=PLNyfXcjhOAwOF-7S-ZoW2wuQ6Y-4hfjMR)
    - [Microcontroller Tutorial - A Beginners Guide (Youtube)](https://www.youtube.com/playlist?list=PLE72E4CFE73BD1DE1)
  - **GPIO**
    - GPIO (**_General Purpose Input/Output_**) is a feature in embedded systems that provides pins to connect external devices
    - [General purpose Input Output (GPIO) Configuration in STM32 (Youtube)](https://youtu.be/tjDhmavBGf0)
