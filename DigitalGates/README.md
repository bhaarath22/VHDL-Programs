# **Logical Gates**

Logical gates are the fundamental building blocks of digital circuits. They perform logical operations on one or more binary inputs to produce a single binary output.

## **Table of Contents**
- [Introduction](#introductio)
- [Basic Logic Gates](#basic-logic-gates)
  - [AND Gate](#and-gate)
  - [OR Gate](#or-gate)
  - [NOT Gate](#not-gate)
- [Universal Gates](#universal-gates)
  - [NAND Gate](#nand-gate)
  - [NOR Gate](#nor-gate)
- [Exclusive Gates](#exclusive-gates)
  - [XOR Gate](#xor-gate)
  - [XNOR Gate](#xnor-gate)
- [Conclusion](#conclusion)

---

## **Introduction**

Logic gates are used to implement Boolean functions in digital electronics. Each gate follows a specific logic rule that defines how the output is determined based on the inputs. The basic gates include AND, OR, and NOT, while universal gates (NAND, NOR) can be used to build any logical function. Exclusive gates (XOR, XNOR) are used in specific digital logic applications.

---

## **Basic Logic Gates**

### **AND Gate**
- **Boolean Expression**: \( Y = A \cdot B \)
- **Logic Operation**: Produces HIGH (1) only if all inputs are HIGH (1).

| A | B | Y = A AND B |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

---

### **OR Gate**
- **Boolean Expression**: \( Y = A + B \)
- **Logic Operation**: Produces HIGH (1) if at least one input is HIGH (1).

| A | B | Y = A OR B |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 1 |

---

### **NOT Gate**
- **Boolean Expression**: \( Y = \overline{A} \)
- **Logic Operation**: Inverts the input value.

| A | Y = NOT A |
|---|---|
| 0 | 1 |
| 1 | 0 |

---

## **Universal Gates**

### **NAND Gate** (NOT AND)
- **Boolean Expression**: \( Y = \overline{A \cdot B} \)
- **Logic Operation**: Produces LOW (0) only when all inputs are HIGH (1).

| A | B | Y = NAND |
|---|---|---|
| 0 | 0 | 1 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

---

### **NOR Gate** (NOT OR)
- **Boolean Expression**: \( Y = \overline{A + B} \)
- **Logic Operation**: Produces HIGH (1) only when all inputs are LOW (0).

| A | B | Y = NOR |
|---|---|---|
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 0 |

---

## **Exclusive Gates**

### **XOR Gate** (Exclusive OR)
- **Boolean Expression**: \( Y = A \oplus B = \overline{A}B + A\overline{B} \)
- **Logic Operation**: Produces HIGH (1) when the inputs are different.

| A | B | Y = XOR |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

---

### **XNOR Gate** (Exclusive NOR)
- **Boolean Expression**: \( Y = \overline{A \oplus B} \)
- **Logic Operation**: Produces HIGH (1) when the inputs are the same.

| A | B | Y = XNOR |
|---|---|---|
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

---

## **Conclusion**

Logic gates are fundamental in digital electronics and computing. Understanding their behavior and Boolean expressions is essential for designing digital circuits. Universal gates like NAND and NOR can be used to construct any logic function, making them particularly valuable in digital design.

Would you like more examples or explanations? 🚀

