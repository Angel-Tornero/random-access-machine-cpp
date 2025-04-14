[![LinkedIn][linkedin-shield]][linkedin-url]

# Random Access Machine Simulator - C++ (University Project)

## 📝 Description

This project implements a simulator for a **Random Access Machine (RAM)** in C++. It allows execution of programs written in a simplified RAM language, using input and output tapes stored in separate files.

The simulator supports a debug mode that provides step-by-step execution with visual feedback on registers, tapes, and program state.

---

### 🔧 How to Run

To execute the simulator, use the following format:

./ram_sim ram_program.ram input_tape.in output_tape.out debug

- ram_program.ram: file containing the RAM program.  
- input_tape.in: file containing the input tape.  
- output_tape.out: file where the output tape will be written.  
- debug: set to 1 to activate interactive debug mode, or 0 to run the full simulation non-interactively.  

When debug mode is active (debug = 1), a menu like the following will appear:

```bash
>h
r: view registers
t: trace
e: execute
s: disassemble
i: view input tape
o: view output tape
h: help
x: exit
```

If debug is set to 0, the simulation runs completely and prints only the total number of executed instructions.

---

## 🛠️ Built With

* C++

---

> **Disclaimer:** This project was developed during my university studies and reflects my knowledge at that time. The code may not follow modern best practices.

---

## 📫 Contact

Ángel Tornero Hernández 📧 angeltornerohdez@gmail.com  

Project Link: https://github.com/Angel-Tornero/random-access-machine-simulator-cpp

---

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555  
[linkedin-url]: https://www.linkedin.com/in/%C3%A1ngel-tornero-hern%C3%A1ndez-173192225/
