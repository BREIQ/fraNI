# 🎨 fraNI 2.0 - Sistema de Celdas CSS Minimalista

![Language](https://img.shields.io/badge/Lenguaje-CSS3-blue?style=for-the-badge)
![Innovation](https://img.shields.io/badge/Lógica-Clases--Híbridas-brightgreen?style=for-the-badge)

**fraNI 2.0** es un framework CSS ultraligero que presenta un sistema de celdas de alta eficiencia. Su innovación principal es la lógica de **Clase Híbrida**, que combina el ancho de celda y el desplazamiento (offset) en una sola cadena lógica.

---

## 🚀 La Lógica Híbrida: `[N][Tamaño]-[S]`

A diferencia de otros frameworks que requieren múltiples clases para un solo elemento, fraNI integra todo en una cadena intuitiva:

**`[Número de Celdas] [Tamaño de Pantalla] - [Espacio/Offset]`**

### 🛠️ Cómo funciona:
Si quieres que un elemento ocupe **4 celdas** en **pantallas Grandes (Large)** con **2 celdas de desplazamiento**, simplemente usas:
### **`4lg-2`**

| Componente | Significado | Resultado Técnico |
| :--- | :--- | :--- |
| **`4`** | Ancho de Celda | `width: 33.33%` |
| **`lg`** | Tamaño de Pantalla | Objetivo `min-width: 1200px` |
| **`-2`** | Desplazamiento Izq. | `margin-left: 16.66%` |

---

## 📂 Arquitecturas de Celdas

fraNI te da la flexibilidad de elegir tu base matemática dependiendo de las necesidades del diseño:

1. **Celdas Estándar (`.line`)**: Basada en un sistema de **12 celdas** (incrementos de 8.33%).
2. **Celdas Decimales (`.line-10`)**: Basada en un sistema de **10 celdas** (incrementos de 10%) para una alineación decimal perfecta.

### Tabla de Breakpoints:
* **`lg`** (Grande): > 1200px
* **`md`** (Medio): 768px - 1199px
* **`sm`** (Pequeño): < 767px

---

### 🏗️ Niveles de Contenedor
fraNI proporciona contenedores flexibles para controlar el ancho máximo de tu diseño. Usa la clase que mejor se adapte a tu proyecto:

| Clase | Ancho Máximo | Ideal para... |
| :--- | :--- | :--- |
| `[class*="frani"]` | 1800px | Diseños cinemáticos ultra-anchos. |
| `.frani-1500` | 1500px | Pantallas modernas de alta resolución. |
| `.frani-1200` | 1200px | Diseños de escritorio estándar. |
| `.frani-900` | 900px | Contenido enfocado y estrecho (como blogs). |

> **Nota:** Todos los contenedores se centran automáticamente usando `margin: auto` e incluyen un fix de `clear:both` mediante las clases `.line` y `.line10` para prevenir colapsos en el diseño.

---

## ☕ Soporta a Breiq

Si encuentras esta lógica de celdas innovadora o útil para tus proyectos, ¡considera apoyar mi trabajo! Cada contribución me ayuda a seguir desarrollando herramientas y scripts.

### Donar vía PayPal:
[![Donate via PayPal](https://img.shields.io/badge/Donar-PayPal-003087?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/paypalme/breiq)

---
**Minimalismo en código. Eficiencia en diseño. Creado por Breiq.**