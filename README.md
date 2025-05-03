# Rectifier  
## 📖 Introduction  

This project presents a **full-wave rectifier** with a **7805 voltage regulator**. The circuit is responsible for converting an alternating current (AC) into direct current (DC) and stabilizing it at **5V**.  

In practice, we used an **Arduino** for testing and a **multimeter** to measure the currents and voltages in the circuit.  

---

## 🎯 Objective  

- Convert AC voltage to DC using a **full-wave rectifier**  
- Filter the rectified voltage to reduce noise  
- Regulate the output to **5V DC** using the **7805**  
- Test the circuit functionality using an **Arduino and multimeter**  

---

## 📜 Schematic  

### 🔧 **Circuit and Components Used**  

Here is the schematic of the circuit, designed in Proteus:  
![image](https://github.com/user-attachments/assets/58c9c714-3179-4090-9788-f5db36153648)

### 📋 **Bill of Materials**  

| Name                  | Code        | Quantity | Function                          |
|-----------------------|-------------|----------|-----------------------------------|
| **Transformer**       | TR1         | 1        | Steps down 220V to 12V            |
| **Bridge Rectifier**  | BR1         | 1        | Rectifies AC voltage              |
| **Electrolytic Capacitor** | C1   | 1        | Filters DC ripple                 |
| **Ceramic Capacitors**| C2, C3      | 2        | Reduces regulator noise           |
| **Voltage Regulator** | 7805        | 1        | Stabilizes output at 5V           |
| **Indicator LED**     | D1          | 1        | Indicates power presence          |
| **Resistor**          | R1          | 1        | 220Ω – Protects the LED           |
| **Connector**         | CONNSIL2    | 1        | Power input                       |
| **Connector**         | SILL100-02  | 1        | Load output                       |

### ⚡ **How It Works**  

1. **The transformer (TR1)** steps down the mains voltage from **220V AC to 12V AC**.  
2. **The diode bridge (BR1)** converts AC into pulsating DC.  
3. **Capacitor C1** acts as a filter, reducing voltage ripple.  
4. **The 7805 regulator** stabilizes the output at **5V DC**.  
5. **Connectors CONNSIL2 and SILL100-02** provide easy connection for load and external power.  
6. **The LED** indicates when the circuit is powered and operating properly.  

---

## 🔬 Practical Testing  

During testing, we used:  
- **Arduino** to validate the regulated **5V output**  
- **Multimeter** to measure voltages and currents at various points in the circuit  

📷 **Photos of practical assembly:**  
![image](https://github.com/user-attachments/assets/2f000352-ee65-48fc-9144-a4afb91cdb96)  
![image](https://github.com/user-attachments/assets/d70582a4-2bde-4ae2-b1a2-4daed1114e59)  
![image](https://github.com/user-attachments/assets/e1d0558d-c711-4674-beac-ccc297e3c330)  

📈 **Results:**  
- The output was correctly regulated to **5V DC**  
- Multimeter readings confirmed the circuit’s efficiency  
- The LED lit up properly, indicating voltage presence  

---

## 🖥️ PCB Layout  

We created the PCB layout in **Proteus** to simplify circuit assembly.  

📷 **Layout image:**  
![image](https://github.com/user-attachments/assets/7d6862a7-ce27-4c02-bad7-6c7ff2cfb20a)  
The Printed Circuit Board (PCB) was designed using Proteus software to accommodate all components needed for the full-wave rectifier. The board was designed to be compact and efficient, ensuring a layout that minimizes interference and optimizes heat dissipation, especially due to the current that flows through the board during rectifier operation.  

---

## 🏗️ 3D Model  

We generated a **3D model of the PCB** to visualize the component layout.  

📷 **3D model image:**  
## **Front view**  
**3D render of an electronic circuit board with several components mounted on a green PCB.**  
**The board features:**  
- **A white rectangular component in the center (labeled U1)**  
- **Resistors (R1)**  
- **Capacitors (C1, C2, C3)**  
- **A diode (D1)**  
- **Other components like jumper pins (JP)**  
- **Measurement scale (50mm) in the lower right corner**  
- **Yellow and blue components**  
- **Perspective 3D view showing component height and position**  

![image](https://github.com/user-attachments/assets/c003e711-72c3-40d4-80da-a9c1a2358435)  

## **Back view**  
**View of the PCB layout showing:**  
- **Green base of the circuit board**  
- **Copper tracks connecting various points**  
- **Mounting holes for components**  
- **Circuit path layout**  

![image](https://github.com/user-attachments/assets/f7a6b1f5-bd5c-4b05-9c88-22b4733fee70)  

---

## 📌 Future Improvements  

✔️ Use an **LM317** for adjustable output voltage  
✔️ Add a **fuse** for overload protection  
✔️ Improve filtering with **higher-capacity capacitors**  
✔️ Add a **heatsink to the 7805** to prevent overheating  

---

## 🏆 Conclusion  

This project demonstrated how a **full-wave rectifier** can be used to power electronic circuits in a stable and efficient way. The use of an **Arduino and multimeter** helped validate the results, confirming a proper **5V DC output**.  

📌 **Author:** Thiago de Oliveira  
📅 **Date:** March 2025  

