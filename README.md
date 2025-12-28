# 🎨 fraNI 2.0 - Minimalist CSS Grid System

![Language](https://img.shields.io/badge/Language-CSS3-blue?style=for-the-badge)
![Innovation](https://img.shields.io/badge/Logic-Hybrid--Classes-brightgreen?style=for-the-badge)

**fraNI 2.0** is an ultra-lightweight CSS framework featuring a high-efficiency grid system. Its core innovation is the **Hybrid Class** logic, which combines column width and offset into a single, logical string.

---

## 🚀 The Hybrid Logic: `[N][Size]-[S]`

Unlike other frameworks that require multiple classes for a single element, fraNI integrates everything into one intuitive string:

**`[Number of Columns] [Screen Size] - [Space/Offset]`**

### 🛠️ How it works:
If you want a cell to occupy **4 columns** on **Large screens** with **2 columns of offset**, you simply use:
### **`4lg-2`**

| Component | Meaning | Technical Result |
| :--- | :--- | :--- |
| **`4`** | Column Width | `width: 33.33%` |
| **`lg`** | Screen Size | Target `min-width: 1200px` |
| **`-2`** | Left Offset | `margin-left: 16.66%` |

---

## 📂 Grid Architectures

fraNI gives you the flexibility to choose your mathematical base depending on the design needs:

1. **Standard Grid (`.line`)**: Based on a **12-column** system (8.33% increments).
2. **Decimal Grid (`.line-10`)**: Based on a **10-column** system (10% increments) for perfect decimal alignment.

### Breakpoints Table:
* **`lg`** (Large): > 1200px
* **`md`** (Medium): 768px - 1199px
* **`sm`** (Small): < 767px

---


## ☕ Support Breiq

If you find this grid logic innovative or useful for your projects, consider supporting my work! Every contribution helps me keep developing tools and scripts.

### Donate via PayPal:
https://www.paypal.com/paypalme/breiq

---
**Minimalism in code. Efficiency in design. Built by Breiq.**
