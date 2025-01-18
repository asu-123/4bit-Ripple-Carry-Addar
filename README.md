# 4bit-Ripple-Carry-Addar
A 4 bit Ripple Carry Addar Using basic Gate ICs.
# 4-Bit Ripple Carry Adder using Basic Gate ICs

This project demonstrates the design and implementation of a 4-bit ripple carry adder using basic logic gate ICs. A ripple carry adder is a fundamental digital circuit that performs binary addition of two 4-bit numbers.

---

## Features

- **4-Bit Addition**: Adds two 4-bit binary numbers.
- **Carry Propagation**: Handles carry propagation between consecutive bits.
- **Logic Gate Implementation**: Built entirely using basic gate ICs (AND, OR, XOR).

---

## Components Used

1. **IC 74HC08**: Quad 2-input AND gates
2. **IC 74HC32**: Quad 2-input OR gates
3. **IC 74HC86**: Quad 2-input XOR gates
4. **DIP Switches**: For input selection (A3, A2, A1, A0, B3, B2, B1, B0)
5. **LEDs**: To display the sum output and carry bit
6. **Resistors**: For current limiting (LEDs)
7. **Breadboard**
8. **Power Supply**: 5V DC
9. **Jumper Wires**

---

## Circuit Diagram

Refer to the image provided in the repository for the circuit connections. The diagram shows the arrangement of logic gates to compute the sum and carry for all 4 bits.

---

## How It Works

1. **Binary Inputs**:
   - Two 4-bit binary numbers (A3 A2 A1 A0 and B3 B2 B1 B0) are provided using DIP switches.
   
2. **Sum Calculation**:
   - Each bit of the sum is calculated using XOR gates.

3. **Carry Propagation**:
   - Carry bits are generated and propagated using AND and OR gates.

4. **Output Display**:
   - The sum bits (S3 S2 S1 S0) and the final carry are displayed using LEDs.

---

## Truth Table

| A3 A2 A1 A0 | B3 B2 B1 B0 | Carry In | Sum (S3 S2 S1 S0) | Carry Out |
|-------------|-------------|----------|--------------------|-----------|
| 0000        | 0000        | 0        | 0000               | 0         |
| 0001        | 0001        | 0        | 0010               | 0         |
| ...         | ...         | ...      | ...                | ...       |
| 1111        | 1111        | 0        | 1110               | 1         |

---

## Setup Instructions

1. Assemble the circuit on a breadboard as per the provided diagram.
2. Connect the DIP switches for binary inputs.
3. Connect the LEDs to display the sum and carry outputs.
4. Power the circuit with a 5V DC power supply.

---

## Applications

- Basic understanding of binary addition and carry propagation.
- Foundational digital design concept for arithmetic logic units (ALUs).
- Educational tool for learning about logic gates and digital circuits.

---

## Future Enhancements

- Expand to an 8-bit or 16-bit ripple carry adder.
- Add an option for subtraction using 2's complement logic.
- Display outputs on a 7-segment display or an LCD.

---

## License

This project is open-source and licensed under the MIT License. Feel free to use and modify the design.

---

## Contribution

Contributions and suggestions are welcome! Open an issue or submit a pull request with your ideas or improvements.

