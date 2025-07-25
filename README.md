# IC Tester Hardware (Manual Testing)

This is a simple manual **IC tester circuit** used to test **logic gates ICs**. The tester checks if the output of an IC gate (like AND, OR, NAND, XNOR, NOT) matches the expected truth table. It's perfect for beginners looking to test common logic gates without needing a microcontroller.

## 🛠 Features
- **Manual Testing** of common ICs like 7400, 7404, 7402, etc.
- **Green LEDs** show the output of gates.
- **Red LEDs** indicate input states (HIGH or LOW).
- **Simple Push Button Inputs** for testing gate logic.

## ⚡ Working Principle
- The **left socket** is used to test standard gates (AND, OR, NAND, XNOR) with 2 input pins.
- The **right socket** is used to test **NOT gates**, which have 6 individual gates for testing.
- **Red LEDs** show if the inputs are HIGH (1) or LOW (0).
- **Green LEDs** indicate the outputs of the gates.
- If the output doesn't match the expected logic from the truth table, the IC is defective.

## 🎛 Components Used:
- 2 × **IC Sockets** (14-pin)
  
- ![Image](https://github.com/user-attachments/assets/bc11fa84-c170-4de6-8c76-5b8fe882422b)
  
- 2 × **Micro Push Buttons** for logic inputs
  
-![Image](https://github.com/user-attachments/assets/eb0090bf-5895-49fc-afba-016d8780cab0)

- 1 × **Toggle switch** for power supply
  
- ![Image](https://github.com/user-attachments/assets/bbe749cb-0f60-4475-b7a8-3a8cb4359b2c)
 
- 2 × **Red LEDs** for input indicators
- 10 × **Green LEDs** for output indication (4 in left socket and 6 in right socket)

- ![Image](https://github.com/user-attachments/assets/a06df766-b71c-410c-9716-d055851a9034)
  
- Resistors (330Ω for LEDs)
  
-![Image](https://github.com/user-attachments/assets/558934fa-298e-463a-94a5-2dd399120bd3)

- **Zero PCB**
  
- ![Image](https://github.com/user-attachments/assets/17568367-f2e7-4c10-a573-5b8e011c2f39)
  
- **B type pin** for power supply
  
- ![Image](https://github.com/user-attachments/assets/5ebd170e-81ea-4469-8e08-c91b2d7e8789)

## 🔌 Power Supply:
- The circuit is powered using a **USB Type B** port that provides 5V to the IC under test.
- A toggle switch is used to turn power ON/OFF.

## 📷 Images
**Circuit Diagram**
![Image](https://github.com/user-attachments/assets/f43aa86d-d323-434d-b536-8391fa28a7e4)

**Hardware implementation**
![Image](https://github.com/user-attachments/assets/a724c702-bf93-465e-a195-52a642446509)


## 📃 Truth Tables

### AND Gate:
| A | B | Y = A AND B |
|---|---|-------------|
| 0 | 0 |      0      |
| 0 | 1 |      0      |
| 1 | 0 |      0      |
| 1 | 1 |      1      |

### OR Gate:
| A | B | Y = A OR B |
|---|---|------------|
| 0 | 0 |      0     |
| 0 | 1 |      1     |
| 1 | 0 |      1     |
| 1 | 1 |      1     |

### NAND Gate:
| A | B | Y = A NAND B |
|---|---|--------------|
| 0 | 0 |      1       |
| 0 | 1 |      1       |
| 1 | 0 |      1       |
| 1 | 1 |      0       |

### XNOR Gate:
| A | B | Y = A XNOR B |
|---|---|--------------|
| 0 | 0 |      1       |
| 0 | 1 |      0       |
| 1 | 0 |      0       |
| 1 | 1 |      1       |

### NOT Gate:
| A | Y = NOT A |
|---|-----------|
| 0 |     1     |
| 1 |     0     |

## Tinker cad simulation
https://www.tinkercad.com/things/aOohTY0IoSs-ic-tester

## 📝 Instructions:
1. Insert the IC into the correct socket:
   - **Left socket**: AND, OR, NAND, XNOR
   - **Right socket**: NOT gate (7404)
2. Turn ON the circuit using the toggle switch.
3. Press the buttons to give input combinations.
4. Observe red LEDs for input state and green LEDs for output.
5. Compare with the printed truth tables.
6. If the output doesn’t match expected logic, the IC may be faulty.

## 📜 License
MIT License – Feel free to fork, modify, and improve this project.
