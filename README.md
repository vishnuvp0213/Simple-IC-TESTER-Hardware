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
- 6 × **Push Buttons** for logic inputs
- 2 × **Red LEDs** for input indicators
- 12 × **Green LEDs** for output indication (6 per socket)
- Resistors (330Ω for LEDs)
- Breadboard or PCB
- Power Supply (5V regulated, via USB)

## 🔌 Power Supply:
- The circuit is powered using a **USB Type B** port that provides 5V to the IC under test.
- A toggle switch is used to turn power ON/OFF.

## 📷 Images
![Image](https://github.com/user-attachments/assets/f43aa86d-d323-434d-b536-8391fa28a7e4)

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
