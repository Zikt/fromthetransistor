# From the Transistor to the Web Browser

## Introduction
This course is designed to guide learners through the modern computer stack, from the fundamental workings of transistors to the creation of a fully functional web browser. The course will take learners through various aspects of hardware and software development, including FPGAs, assembly programming, compilers, operating systems, and network protocols. 

**Estimated Time Commitment**: 12 weeks  
**Weekly Time Commitment**: ~10 hours per week

This course will be open source and community-maintained, providing opportunities for learners and contributors to suggest improvements and quiz questions, fostering collaborative learning.

## Course Outline

### **Section 1: Intro: Cheating our way past the transistor (0.5 weeks)**
1. **Overview:**
   - Learn how FPGAs are built using transistors and the importance of LUTs.
   - **Reading:**
     - "Digital Design and Computer Architecture" by David Harris and Sarah Harris
     - "The Art of Electronics" by Paul Horowitz and Winfield Hill (Transistor theory basics)
   - **Videos:**
     - [Transistor Basics](https://www.youtube.com/watch?v=sFqZnl8tzWk)
     - [How FPGAs Work](https://www.youtube.com/watch?v=5XITahTkXoY)
   - **Code Sample:** Basic Verilog project (Blinking LED using FPGA)

2. **Emulation with Verilator:**
   - **Reading:**
     - Verilator documentation and example codes
   - **Videos:**
     - [How to use Verilator](https://www.youtube.com/watch?v=e_MwgFQEUgY)
   - **Code Sample:** Installing and setting up Verilator for FPGA emulation

---

### **Section 2: Bringup: What language is hardware coded in? (0.5 weeks)**
1. **Verilog Basics:**
   - **Reading:**
     - "Verilog HDL: A Guide to Digital Design and Synthesis" by Samir Palnitkar
   - **Videos:**
     - [Intro to Verilog](https://www.youtube.com/watch?v=0jZfszBdZyg)
   - **Code Sample:** Blinking LED in Verilog

2. **Building a UART:**
   - **Reading:**
     - UART design documentation, ARM UART details
   - **Code Sample:** UART implementation in Verilog

---

### **Section 3: Processor: What is a processor anyway? (3 weeks)**
1. **Coding an Assembler (Python):**
   - **Reading:**
     - ARM architecture reference manual
   - **Videos:**
     - [Understanding ARM Assembly](https://www.youtube.com/watch?v=e-kSGNzu0hM)
   - **Code Sample:** Simple ARM assembler in Python

2. **Building an ARM7 CPU (Verilog):**
   - **Reading:**
     - "Digital Design with RTL Design, Verilog and VHDL" by Frank Vahid
   - **Videos:**
     - [Building a Simple CPU in Verilog](https://www.youtube.com/watch?v=Nnbg-Yu9tM8)
   - **Code Sample:** Simple ARM7 pipeline architecture

3. **Coding a BootROM (Assembler):**
   - **Code Sample:** BootROM code to download programs into RAM

---

### **Section 4: Compiler: A “high” level language (3 weeks)**
1. **Building a C Compiler (Haskell):**
   - **Reading:**
     - "Compilers: Principles, Techniques, and Tools" by Aho, Sethi, and Ullman
   - **Videos:**
     - [Introduction to Compilers](https://www.youtube.com/watch?v=5hlIUrd7d1Q)
   - **Code Sample:** Simple C compiler written in Haskell

2. **Building a Linker (Python):**
   - **Code Sample:** A basic linker generating ELF files

3. **libc + malloc (C):**
   - **Reading:**
     - C standard library implementation
   - **Code Sample:** Basic implementation of `malloc`, `memcpy`, `printf`

4. **Building an Ethernet Controller (Verilog):**
   - **Code Sample:** Basic MMIO design for an Ethernet PHY

---

### **Section 5: Operating System: Software we take for granted (3 weeks)**
1. **Building an MMU (Verilog):**
   - **Reading:**
     - ARM9 MMU documentation
   - **Code Sample:** MMU implementation in Verilog

2. **Building an Operating System (C):**
   - **Reading:**
     - "Operating Systems: Three Easy Pieces" by Remzi Arpaci-Dusseau and Andrea Arpaci-Dusseau
   - **Videos:**
     - [OS Development Tutorial](https://www.youtube.com/watch?v=MJclSZSp1FY)
   - **Code Sample:** Basic UNIX-like kernel with system calls (`open`, `read`, etc.)

3. **Talking to an SD Card (Verilog):**
   - **Code Sample:** Verilog driver for SD card

4. **FAT Filesystem (C):**
   - **Code Sample:** FAT filesystem implementation

---

### **Section 6: Browser: Coming online (1 week)**
1. **Building a TCP Stack (C):**
   - **Reading:**
     - "TCP/IP Illustrated" by W. Richard Stevens
   - **Code Sample:** Simple TCP/IP stack implementation

2. **Writing a Web Browser (C):**
   - **Videos:**
     - [How Web Browsers Work](https://www.youtube.com/watch?v=WjDrMKZWCt0)
   - **Code Sample:** Text-based web browser

---

### **Section 7: Physical: Running on real hardware (1 week)**
1. **Talking to an FPGA (C):**
   - **Reading:**
     - USB MCU JTAG documentation
   - **Code Sample:** C code for USB bit-banging JTAG

2. **Building an FPGA Board:**
   - **Videos:**
     - [Building an FPGA Board from Scratch](https://www.youtube.com/watch?v=ROo3BHk60Zs)

---

## Quizzes and Community Contributions
This course is designed to be **open-source** and **community-driven**, with the option for learners to contribute ideas and improvements. Quizzes for each section will be open for community suggestions, allowing contributors to create thought-provoking questions, coding challenges, and exercises. 

You can suggest quizzes, projects, or improvements by opening a discussion or pull request on the course's GitHub repository. Let's build and grow this course together!
