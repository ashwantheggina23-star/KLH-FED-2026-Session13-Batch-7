# logisim-adder-circuits

# 1-Bit Half Adder & Full Adder Circuits in Logisim

This repository contains the design, logic equations, truth tables, and simulation files for 1-bit **Half Adder** and **Full Adder** circuits developed using **Logisim**.

---

## 📌 Circuit Overview & Boolean Equations

### 1. Half Adder
A Half Adder adds two single binary bits ($A$ and $B$) to produce a $Sum$ and a $Carry$ bit.

* **Sum Equation:** $Sum = A \oplus B$
* **Carry Equation:** $Carry = A \cdot B$

### 2. Full Adder
A Full Adder adds three single binary bits ($A$, $B$, and $C_{in}$) to produce a $Sum$ and a $C_{out}$ (Carry Out) bit. It is constructed using two Half Adders and an OR gate.

* **Sum Equation:** $Sum = A \oplus B \oplus C_{in}$
* **Carry-Out Equation:** $C_{out} = (A \cdot B) + (C_{in} \cdot (A \oplus B))$

---

## 📊 Truth Tables

### Half Adder Truth Table
| Input A | Input B | Sum | Carry |
|:-------:|:-------:|:---:|:-----:|
|    0    |    0    |  0  |   0   |
|    0    |    1    |  1  |   0   |
|    1    |    0    |  1  |   0   |
|    1    |    1    |  0  |   1   |

### Full Adder Truth Table
| Input A | Input B | Input C_in | Sum | C_out |
|:-------:|:-------:|:----------:|:---:|:-----:|
|    0    |    0    |     0      |  0  |   0   |
|    0    |    0    |     1      |  1  |   0   |
|    0    |    1    |     0      |  1  |   0   |
|    0    |    1    |     1      |  0  |   1   |
|    1    |    0    |     0      |  1  |   0   |
|    1    |    0    |     1      |  0  |   1   |
|    1    |    1    |     0      |  0  |   1   |
|    1    |    1    |     1      |  1  |   1   |

---

## 🖼️ Circuit Schematics

### Full Adder Schematic
![Full Adder Circuit](full_adder.png)

---

## 🚀 How to Run the Simulation

1. **Install Logisim:** Download [Logisim](http://www.cburch.com/logisim/) or Logisim-Evolution.
2. **Clone the Repository:**
   ```bash
   git clone [https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git](https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git)
