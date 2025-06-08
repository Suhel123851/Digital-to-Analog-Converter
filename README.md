# Digital-to-Analog-Converter

A simple 4-bit Digital to Analog Converter (DAC) simulation using Multisim.

---

## ⚙️ Working Principle

This DAC is based on the **weighted resistor method**, where each digital bit controls a switch connected to a resistor with a specific value. The most significant bit (MSB) gets the smallest resistance (R), and the least significant bit (LSB) gets the largest (8R), creating proportional voltage drops.

- 4-bit input: D3 (MSB), D2, D1, D0 (LSB)
- Resistor values are weighted: R, 2R, 4R, 8R
- An op-amp acts as a summing amplifier to combine voltages into a single analog output

---

## 🖼️ Circuit Diagram

![DAC Circuit](https://github.com/Suhel123851/Digital-to-Analog-Converter/blob/main/DAC_Circuit_Screenshot.png)

> *(Replace the image name in this link if needed)*

---

## 📊 Output Table (Binary Input vs Analog Output)

| Binary Input | Expected Output (V) |
|--------------|---------------------|
| 0000         | 0.00                |
| 0001         | 0.31                |
| 0010         | 0.62                |
| 0011         | 0.93                |
| 0100         | 1.24                |
| 0101         | 1.55                |
| 0110         | 1.86                |
| 0111         | 2.17                |
| 1000         | 2.48                |
| 1001         | 2.79                |
| 1010         | 3.10                |
| 1011         | 3.41                |
| 1100         | 3.72                |
| 1101         | 4.03                |
| 1110         | 4.34                |
| 1111         | 4.65                |

---

## 🛠️ Software Used

- [NI Multisim](https://www.multisim.com/)
- GitHub for version control and portfolio hosting

---

## 📂 Files Included

- `DAC_Circuit.ms14` - Multisim simulation file
- `DAC_Circuit_Screenshot.png` - Circuit diagram image
- `DAC_Report.pdf` - Detailed explanation (optional)

---

## 🙋‍♂️ Author

**Suhel**  
2nd Year Electrical Engineering Student  
Follow me on [GitHub](https://github.com/Suhel123851)

