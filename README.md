
# 🧠 Task-1: ALU Design

This project implements a basic Arithmetic Logic Unit (ALU) using Verilog. It supports operations such as addition, subtraction, AND, OR, and NOT. The ALU is tested using a SystemVerilog testbench.

## 📁 Files Included

- `design.sv` – Main Verilog ALU module  
- `testbench.sv` – Testbench to simulate the ALU  
- `README.md` – This documentation file

## ⚙️ How to Run

1. Open [EDA Playground](https://edaplayground.com/x/LURJ).
2. The code is already available in the shared link.
3. Click **Run** to simulate and view the waveforms.

## 🧪 Supported Operations

| Select Line (sel) | Operation | Description           |
|-------------------|-----------|-----------------------|
| 00                | ADD       | A + B                 |
| 01                | SUB       | A - B                 |
| 10                | AND       | A & B                 |
| 11                | OR        | A | B                 |
| 100               | NOT       | ~A (NOT A)            |

> 🔹 Note: `NOT` is a unary operation; only input A is used.

## 👩‍💻 Author

**Vineela Moturi**  
Completed 2nd Year B.Tech ECE, Vignan's IIT Duvvada  
[EDA Simulation](https://edaplayground.com/x/LURJ)
