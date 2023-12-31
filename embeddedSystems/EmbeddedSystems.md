# Embedded Systems

## Description

This roadmap gives a general overview of the concepts you will need to know to become an Embedded Systems Engineer. As an embedded system engineer, it is your job to design, implement, and debug the software and hardware components of an embedded system. This requires a strong understanding of electronics, programming languages and embedded system architecture. The topics have been carefully selected to reflect standard requirements of an Embedded Systems Engineer. A lot of passion and determination will be required of you to succeed in this field.

## What is an Embedded System?

An embedded system is a combination of computer hardware and software components, and perhaps additional mechanical or other parts, designed to perform a dedicated function. In some cases, embedded systems are part of a larger system or product. [Embedded Systems Glossary](https://barrgroup.com/embedded-systems/glossary-e), [DigiKey - Youtube](https://www.youtube.com/@digikey)

> **This roadmap contains paths to learning both software and hardware components for an absolute beginner. If you are already familiar with any concepts/tools, you can reinforce your knowledge quickly and move to the unfamiliar** - If you lack embedded systems knowledge, **Arduino** boards will be great choice to learn the basics quickly. But know that Arduino libraries are only developed for learning purposes and not optimized to used in the industry [Getting Started with Arduino](https://docs.arduino.cc/learn/starting-guide/getting-started-arduino)

### Essential Resources

- [Embedded Systems Playlist](https://youtu.be/3VtGCPIoBfs?list=PLC8H7gcKF_bSFZbEB678hOjOs7xj42Ezu)
- [General Programming](https://youtu.be/oW3rRfjWwUE?list=PLC8H7gcKF_bQ8DVcxBtukZSipJtRAUXtE)
- [Every Programmer Should Know](https://github.com/mr-mig/every-programmer-should-know)
- [How to Use Git and GitHub – Introduction for Beginners](https://www.freecodecamp.org/news/introduction-to-git-and-github/)
- [All About Circuits](https://www.allaboutcircuits.com/)
- [Modern Embedded Systems Programming](https://www.youtube.com/playlist?list=PLb-MsRpo_wlLW0EWRpAqnbbDsf4kxSI1x)
- [STM32 World](https://stm32world.com/)

## Recommended Roadmap for Beginners

### Foundational Hardware Basics

- **Basic Math and Calculus**
  - Ideally you should have a strong foundation in mathematics, particularly in areas such as algebra, calculus, and discrete mathematics. Knowledge of algebra is important in understanding and manipulating mathematical expressions, while calculus is essential for dealing with continuous signals and control systems. [Khan Academy](https://www.khanacademy.org/math/calculus-1)
- **Electric Circuits Fundamantals**
  - [Electronics](https://www.electronics-tutorials.ws/)
  - [Electronic Components](https://www.elprocus.com/major-electronic-components/)
- **Electronics Fundamentals**
  - Understanding of electronics is vital in embedded systems engineering for designing hardware, microcontrollers, sensors, actuators, circuits, and PCBs. You will learn about efficient power management, signal processing, and integration of analog and digital components as well as troubleshotting, safety and reliability. [All About Circuits](https://www.allaboutcircuits.com/textbook/), [Electronics Basics (Youtube)](https://youtube.com/playlist?list=PLAROrg3NQn7cyu01HpOv5BWo217XWBZu0)
- **Digital Circuits and Logic Design**
  - This involves creating and analyzing digital systems using logic gates, Boolean algebra, and sequential elements. It encompasses designing circuits, such as multiplexers, flip-flops, and memory systems, essential for building computers and embedded systems. [FPGA - NandLand](https://nandland.com/fpga-101/), [Digital Design](https://tinytapeout.com/digital_design/)
- **Computer Architecture**
  - [Embedded Systems Architecture - Tammy Noergaard](https://www.oreilly.com/library/view/embedded-systems-architecture/9780123821966/)

### Foundational Programming Knowledge

- A solid foundation in at least one of the following programming languages such as **C** or **C++** is required in this field. Languages such as **Assembly**, **Python**, **Rust** and **Java** are also popular in this field. It is recommended to go with **C** or **C++**.
- **C**
  - **C** is the foundation for many operating systems and software applications and it is well known for its performance, portability, and influence on other programming languages.
    - [W3 Schools](https://www.w3schools.com/c/index.php)
    - [C for Beginners (Youtube)](https://www.youtube.com/watch?v=ssJY5MDLjlo)
- **C++**

  - **C++** is a powerful, general-purpose programming language. It is efficient, versatile and supports both procedural and object-oriented paradigms making it popular for system software, game development and embedded systems.
    - [W3 Schools](https://www.w3schools.com/cpp/default.asp)
    - [C++ for Beginners (Youtube)](https://www.youtube.com/watch?v=vLnPwxZdW4Y)

- **Data Structures and Algorithms**
  - [Grokking Algorithms](https://www.manning.com/books/grokking-algorithms)
  - [Data Structures - Using C/C++ (Youtube)](https://www.youtube.com/watch?v=B31LgI4Y4DQ)
- **Design Patterns**
  - To ensure reuseablility and maintainability, having knowledge of proven, reliable solutions to recurring challenges will save you a alot of headaches.
    - [Design Patterns for Embedded Systems in C](https://repositorio.uci.cu/jspui/bitstream/123456789/10139/1/Design%20Patterns%20for%20Embedded%20Systems%20in%20C_%20An%20Embedded%20Software%20Engineering%20Toolkit%20%28%20PDFDrive%20%29.pdf)
- **State Machines / UML**
  - State machines are models used in embedded systems to represent the behavior of a component. UML (**_Unified Modeling Language_**) is a standardized notation used to design, visualize, and document the structure of software systems
    - [State Machines (Youtube)](https://www.youtube.com/playlist?list=PLPW8O6W-1chxym7TgIPV9k5E8YJtSBToI)
    - [Embedded System Design using UML State Machines](https://www.udemy.com/course/embedded-system-design-using-uml-state-machines/)
- **Build Tools**
  - **GCC, Make & CMake**
    - GCC (**_GNU Compiler Collection_**) is a versatile compiler system that supports programming languages like C/C++. Make is a build automation tool, it simplifies the compilation process and manage dependencies. CMake is a cross-platform build system that allows for efficient building, testing and packaging software
      - [GCC and Make with C/C++ Applications](https://www3.ntu.edu.sg/home/ehchua/programming/cpp/gcc_make.html)
      - [Building STM32 projects with cross platform tools like Make, CMake (YouTube )](https://www.youtube.com/playlist?list=PLEg2mgYz66IOcHRvvUDf9O1ZCGy58M1Bt)
      - [CMake Tutorial](https://cmake.org/cmake/help/latest/guide/tutorial/index.html)
- **Bash Scripting**
  - [Bash Scripting for Beginners](https://www.youtube.com/watch?v=tK9Oc6AEnR4)
- **Docker** allows developers package and run applications in lightweight, isolated containers
  - [Docker Documentation](https://docs.docker.com/get-started/)
  - [Introduction to Docker for the Embedded Developer](https://www.youtube.com/watch?v=Fz7ou-VBk-w)

### Microcontrollers

- **_What is a Microcontroller?_**
  - It is a compact computer on a single integrated circuit. It contains a processor, memory, I/O peripherals.
  - [What is a Microcontroller?](https://www.allaboutcircuits.com/technical-articles/what-is-a-microcontroller-introduction-component-characteristics-component/)
  - [Fundamentals of Microcontrollers - Arduino bare-metal breakdown (YouTube)](https://www.youtube.com/playlist?list=PLNyfXcjhOAwOF-7S-ZoW2wuQ6Y-4hfjMR)
  - [Microcontroller Tutorial - A Beginners Guide (Youtube)](https://www.youtube.com/playlist?list=PLE72E4CFE73BD1DE1)
  - [Awesome Embedded: A curated list of awesome embedded programming](https://github.com/nhivp/Awesome-Embedded)
  - [How to Choose the Right Microcontroller for Your Application](https://www.allaboutcircuits.com/technical-articles/how-to-choose-the-right-microcontroller-for-your-application/)
  - [Getting started with STM32: STM32 step-by-step](https://wiki.st.com/stm32mcu/wiki/Category:Getting_started_with_STM32_:_STM32_step_by_step)
- **GPIO**
  - GPIO (**_General Purpose Input/Output_**) is a feature in embedded systems that provides pins to connect external devices
  - [General purpose Input Output (GPIO) Configuration in STM32 (Youtube)](https://youtu.be/tjDhmavBGf0)
- **ADC**
  - ADC (**_Analog-to-Digital Converter_**)
    - [Analogue to Digital Converter (ADC) Basics](https://www.electronics-tutorials.ws/combination/analogue-to-digital-converter.html)
    - [How Do ADCs Work? - Youtube](https://www.youtube.com/watch?v=g4BvbAKNQ90)
- **DAC**
  - DAC (**_Digital-to-Analog Converter_**)
    - [Digital to Analog Converters](https://www.tutorialspoint.com/linear_integrated_circuits_applications/linear_integrated_circuits_applications_digital_to_analog_converters.htm)
    - [How Do DACs Work? - Youtube](https://www.youtube.com/watch?v=YAxrmoVtEtE)
- **PVM**
  - PVM (**_Parallel Virtual Machine_**) allows for the coordination of multiple processors to work together on a common task.
  - [Writing PVM Applications](https://etutorials.org/Linux+systems/cluster+computing+with+linux/Part+II+Parallel+Programming/Chapter+10+Parallel+Virtual+Machine/10.2+Writing+PVM+Applications/)
  - [PVM + Timers (Youtube)](https://www.youtube.com/watch?v=AjN58ceQaF4)
- **Interrupts**
  - Interrupts are signals that pause the normal execution of a microcontroller. They allow embedded systems to respond to external stimuli quickly such as I/O or timers.
  - [Embedded Systems - Interrupts](https://www.tutorialspoint.com/embedded_systems/es_interrupts.htm)
  - [Arduino Interrupts Tutorial](https://roboticsbackend.com/arduino-interrupts/)
- **Watchdog**
  - [Introduction to Watchdog Timers](https://www.embedded.com/introduction-to-watchdog-timers/)
  - [A Guide to Watchdog Timers for Embedded Systems](https://interrupt.memfault.com/blog/firmware-watchdog-best-practices)
  - [The Watchdog Timer on Arduino (Youtube)](https://www.youtube.com/watch?v=AzZBgH67mgE)
- **Clock Management**

  - [Clock Signal Management: Clock Resources of FPGAs](https://www.allaboutcircuits.com/technical-articles/clock-management-clock-resources-of-fpgas/)
  - [201- STM32 Clock System Mastery Bare Metal Coding (Youtube)](https://www.youtube.com/watch?v=R6xvpOpgdJ4)
  - [Intro to STM32F4 Register Based Programming || Clock Setup || LED Blinking || NO HAL (Youtube)](https://www.youtube.com/watch?v=GJ_LFAlOlSk)

- **DMA** - **_Direct Memory Access_**

  - [Introduction to Direct Memory Access (DMA)](https://www.youtube.com/watch?v=M16l_ymlfcs)
  - [STM32 DMA - Youtube](https://www.youtube.com/watch?v=yvLHtXJ_KSg)

### Protocols and Interfaces

- [Understanding Serial Protocols](https://www.youtube.com/watch?v=LEz5UCN3aHA)
  - **_I2C:_** **Inter-Integrated Circuit**
    - [I2C in a Nutshell](https://interrupt.memfault.com/blog/i2c-in-a-nutshell)
    - [Understanding I2C - Youtube](https://www.youtube.com/watch?v=CAvawEcxoPU)
  - **_UART:_** **Universal Asynchronous Reciever-Transmitter**
    - [Basics of UART Communication - Youtube](https://www.youtube.com/watch?v=JuvWbRhhpdI)
    - [Understanding UART - Youtube](https://www.youtube.com/watch?v=sTHckUyxwp8)
  - **_SPI:_** **Serial Peripheral Interface**
    - [Understanding SPI - Youtube](https://www.youtube.com/watch?v=0nVNwozXsIc)
- **Wireless Protocols**
  - **Bluetooth / BLE**
    - [Bluetooth Basics](https://learn.sparkfun.com/tutorials/bluetooth-basics/all)
    - [Bluetooth Low Energy Fundamentals](https://academy.nordicsemi.com/courses/bluetooth-low-energy-fundamentals/)
  - **Wi-Fi**
    - [How Wi-Fi Works (Youtube)](https://www.youtube.com/watch?v=vvhEnr52UOU)
- **Audio, Image and Video Protocols**
  - [Introduction to the I2S Interface](https://www.allaboutcircuits.com/technical-articles/introduction-to-the-i2s-interface/)
  - [Building a Digital Music Player with I2S?! What is I2S - Youtube](https://www.youtube.com/watch?v=qNLvoSQCx60)
  - [PCM Terminology and Concepts](https://larsimmisch.github.io/pyalsaaudio/terminology.html)
  - [MIPI CSI-2 Tutorial - Youtube](https://www.youtube.com/watch?v=8REu_h7bzHM)
  - [HDMI 2.1 & TMDS Crash Course - Youtube](https://www.youtube.com/watch?v=5acgSK0kWTE)
  - [MIPI Camera Serial Interface 2](https://www.mipi.org/specifications/csi-2)
- **High Speed Protocols**
  - **_USB_**
    - [An Introduction to Universal Serial Bus 2.0](https://www.infineon.com/dgdl/Infineon-AN57294_USB_101_An_Introduction_to_Universal_Serial_Bus_2.0-ApplicationNotes-v09_00-EN.pdf?fileId=8ac78c8c7cdc391c017d072d8e8e5256)
    - [How does USB device discovery work? - Youtube](https://www.youtube.com/watch?v=N0O5Uwc3C0o)
    - [MOOC - STM32 USB training - YouTube](https://www.youtube.com/playlist?list=PLnMKNibPkDnFFRBVD206EfnnHhQZI4Hxa)
  - **_Ethernet_**
    - [How the Ethernet Protocol Works](https://www.freecodecamp.org/news/the-complete-guide-to-the-ethernet-protocol/)
  - **_PCIe_**
    - [What is PCIe? - Youtube](https://www.youtube.com/watch?v=L9qXjmJdQXY)
    - [PCIe Protocol - Youtube](https://www.youtube.com/playlist?list=PLZe4P0P_9Cosd0i2ha_QRdWlR1iZ0yVG4)
- **Network Protocols**
  - **_TCP/IP & UDP_**
    - [TCP vs UDP - Explaining Facts and Debunking Myths](https://www.youtube.com/watch?v=jE_FcgpQ7Co)
    - [Networking Fundamentals - Practical Networking - YouTube](https://www.youtube.com/playlist?list=PLIFyRwBY_4bRLmKfP1KnZA6rZbRHtxmXi)
- **Memory Technologies**
  - **_NOR/NAND/SD Card/eMMC_**
    - [Flash Memory in Embedded Linux Systems](https://www.youtube.com/watch?v=hdwMvwJIV-Y)
    - [Interfacing with an SD Card - Youtube](https://www.youtube.com/watch?v=g40tUdjZ-Sk)
    - [What is a eMMC? Intro, Comparing to Other Storage, and Upgrading. SSD, M.2](https://www.youtube.com/watch?v=vGatKmqYxEA)
    - [Interfacing with an SD Card](https://www.youtube.com/watch?v=g40tUdjZ-Sk)
  - **_EEPREOM_**
    - [Using EEPROM with Arduino - Internal & External](https://www.youtube.com/watch?v=ShqvATqXA7g)
  - **_SRAM / DRAM_**
    - [What is SRAM? - Youtube](https://www.youtube.com/watch?v=kU2SsUUsftA)
    - [SRAM vs DRAM: Difference Between SRAM & DRAM Explained](https://www.enterprisestorageforum.com/hardware/sram-vs-dram/)
- **Sensors and Actuators**
  - [Complete Guide for Ultrasonic Sensor HC-SR04 with Arduino](https://randomnerdtutorials.com/complete-guide-for-ultrasonic-sensor-hc-sr04/)
  - [Calibrating Sensors](https://learn.adafruit.com/calibrating-sensors)
  - [Adafruit Motor Selection Guide](https://learn.adafruit.com/adafruit-motor-selection-guide)

### Operating Systems Fundamentals

- Learn the fundamentals of Operating Systems [Operating Systems from 0 to 1](https://github.com/tuhdo/os01/blob/master/Operating_Systems_From_0_to_1.pdf)
- **Embedded Linux**
  - [Introduction to Embedded Linux (YouTube)](https://youtube.com/playlist?list=PLEBQazB0HUyTpoJoZecRK6PpDG31Y7RPB)
  - [ Mastering Embedded Linux Programming - Chris Simmonds](https://www.packtpub.com/product/mastering-embedded-linux-programming-third-edition/9781789530384)
  - [How Linux Works - Brian Ward](https://nostarch.com/howlinuxworks3)
- **Real-Time OS & FreeRTOS**
  - This provides real-time response to external events, scheduling and resource allocation
  - [Bare-metal and RTOS Based Embedded Systems](https://microcontrollerslab.com/difference-bare-metal-and-rtos-based-embedded-systems/)
  - [Real-Time Systems Concepts](https://micrium.atlassian.net/wiki/spaces/osiidoc/pages/163855/Real-Time+Systems+Concepts)
  - [RTOS - Youtube](https://www.youtube.com/playlist?list=PLPW8O6W-1chyrd_Msnn4LD6LBs2slJITs)
  - [RTOS Fundamentals](https://www.freertos.org/implementation/a00002.html)
  - [FreeRTOS - Market leading RTOS](https://www.freertos.org/)

### Prototyping Skills

- **Breadboarding**
  - This is a prototyping method for testing electronic components before soldering them into a circuit board
  - [Everything You Need to Know about Breadboards (Youtube)](https://www.youtube.com/watch?v=mE33WpRWrXs)
- **Basics of Hardware Design**
  - You will likely not design electronic circuits and pcbs, but you have to understand your board and schematics to program the microcontroller.
  - [Hardware Design (Youtube)](https://www.youtube.com/playlist?list=PLXSyc11qLa1YhVCZ5xWPuPsE5MkgEy5TF)
  - [Basics of Different Electronic Circuit Design Process](https://www.elprocus.com/different-electronic-circuit-design-process/)
- **PCB Design**
  - **_Printed Circuit Board_** enables electrical connections between the microcontroller, sensors, actuators and other peripherals
  - [Create PCBs for Rapid Prototyping - (YouTube)](https://www.youtube.com/playlist?list=PLEBQazB0HUyRVK1RpHIjyjuTxn5srz6XM)
  - [Altium Academy - YouTube](https://www.youtube.com/@AltiumAcademy)
- **FPGA**
  - FGPA (**_Field Programmable Gate Array_**) is a type of hardware that can be reconfigured to perform various functions. They are used to implement custom logic and interfaces.
  - [Introduction to FPGA (YouTube)](https://youtube.com/playlist?list=PLEBQazB0HUyT1WmMONxRZn9NmQ_9CIKhb)
  - [FPGA Fundamentals - Nandland](https://nandland.com/fpga-101/)

### Digital Signal Processing

- DSP stands for Digital Signal Processing. It is a technique used in manipulating and analyzing digital signals
- [The Scientist and Engineer's Guide to Digital Signal Processing - Steven W. Smith](https://www.dspguide.com/pdfbook.htm)
- [Digital Signal Processing (DSP) From Ground Up in C](https://www.udemy.com/course/digital-signal-processing-dsp-from-ground-uptm-in-c/)
- **Discrete Fourier Transforms**
  - [Discrete Fourier Transform - Simple Step by Step - Youtube](https://www.youtube.com/watch?v=mkGsMWi_j4Q)
  - [The FFT Algorithm - Simple Step by Step - Youtube](https://www.youtube.com/watch?v=htCj9exbGo0)
- **Controls Systems / PID Control**
  - [Understanding Control Systems (YouTube)](https://youtube.com/playlist?list=PLn8PRpmsu08q8CE0pbZ-cSrMm_WYJfVGd)
  - [What is a PID Controller? - Youtube](https://www.youtube.com/watch?v=tFVAaUcOm4I)

### Integration with IoT & Cloud

- [Introduction to the Internet of Things and Embedded Systems](https://www.coursera.org/learn/iot)
- [A look at how IoT and embedded systems work together](https://www.techtarget.com/iotagenda/tip/A-look-at-how-IoT-and-embedded-systems-work-together)
- [Analyze the interaction between embedded systems and IoT](https://medium.com/@core-data/analyze-the-interaction-between-embedded-systems-and-iot-620547c0dd3d)
- [Seamless Cloud Services Integration in IoT Embedded Systems](https://www.techaheadcorp.com/blog/cloud-services-integration-iot-embedded-systems/#:~:text=IoT%20and%20cloud%20computing%20technologies,where%20it's%20processed%20and%20analyzed.)
- [Know About Internet of Things (IoT) and Embedded Systems](https://www.monarch-innovation.com/know-about-iot-and-embedded-systems)
- [Connecting IoT Devices to Cloud Services](https://embeddedcomputing.com/application/networking-5g/connecting-iot-devices-to-cloud-services)

### Testing

- [What is Embedded Testing in Software Testing?](https://www.guru99.com/embedded-software-testing.html)
- [Embedded Testing](https://artoftesting.com/embedded-testing)
- **_TDD_** (Test Driven Development)
  - [Test Driven Development for Embedded C - James Grenning](https://www.amazon.com/Driven-Development-Embedded-Pragmatic-Programmers/dp/193435662X)
  - **_Unit Test_**
    - [Embedded C/C++ Unit Testing Basics](https://interrupt.memfault.com/blog/unit-testing-basics)
    - [Unit Testing for C (especially Embedded Software)](http://www.throwtheswitch.org/unity)
    - [GoogleTest - Google Testing and Mocking Framework](https://github.com/google/googletest)
  - **_Integration Test_**
    - [Hardware Testing in Mass Production, Made Easier](https://www.bunniestudios.com/blog/?p=5450)

### Debugging

- **_JTAG / SWD_**
  - [Guide: Connecting your debugger](https://stm32-base.org/guides/connecting-your-debugger.html)
  - [STM32 + SWD + ST-Link + CubeIDE | Debugging on Custom Hardware Tutorial - Youtube](https://www.youtube.com/watch?v=qMUzLU636s8)
- **_OpenOCD & GDB_**
  - [This Is 100% How You Should Be Debugging | How to Use OpenOCD to Debug Embedded Software with GDB](https://www.youtube.com/watch?v=_1u7IOnivnM)
  - [GDB is REALLY easy! Find Bugs in Your Code with Only A Few Commands](https://www.youtube.com/watch?v=Dq8l1_-QgAc)

### Embedded Security

- [Embedded Systems Security](https://embeddedsecurity.io/)
- [Hashing, Hashing Algorithms, and Collisions - Cryptography (Youtube)](https://youtu.be/HHQ2QP_upGM)
- [STM32 security features - YouTube](https://youtube.com/playlist?list=PLnMKNibPkDnFzux3PHKUEi14ftDn9Cbm7)
- [Securing Embedded Linux Systems with TPM 2.0 - Youtube](https://www.youtube.com/watch?v=0qu9R7Tlw9o)

### Projects

It is very important to get your hands dirty in projects rather than relying on theroticals only. This will reinforce what you have learned and make you a better engineer.

- [STM32 Projects & Tutorials for Beginners and Up](https://www.hackster.io/stm32/projects)
- [Phil's Lab - Youtube](https://youtube.com/playlist?list=PLXSyc11qLa1a4Tqbz228dPZfMrs-KRpzA)

### Soft Skills

Soft skills are no less important than technical skills

- [Soft Skills For Embedded Systems Software Developers](https://www.embeddedrelated.com/showarticle/1470.php)
- [Skills Every Embedded Engineer Should Have](https://medium.com/@lanceharvieruntime/10-skills-every-embedded-engineer-should-have-dcb867095b91)


