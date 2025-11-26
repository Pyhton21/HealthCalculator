# 🧮 Health Calculator (BMI + Ideal Weight)

A simple and interactive **Java console application** that calculates your **BMI**, determines your **BMI category**, and computes your **ideal body weight** using both the **Devine** and **Robinson** formulas.  
The program supports **metric and imperial** units and includes a **password login system** for basic access control.

---

## ⭐ Features

- 🔐 **Password-protected access**
- ⚖️ **BMI calculation**
- 📊 **BMI category detection** (Underweight, Normal, Overweight, Obese)
- 📏 Works with both **Metric (kg/m)** and **Imperial (lbs/inches)** units
- 🔁 Automatically converts imperial input to metric
- 👤 Calculates **Ideal Body Weight** using:
  - Devine Formula  
  - Robinson Formula  
- 🧮 Clear step-by-step console user interface

---

## 📂 Project Structure
HealthCalculator/
├── HealthCalculator.java


---

## 🚀 How It Works

1. User enters a **password** to access the calculator.  
2. User provides:
   - Name  
   - Unit system (metric or imperial)  
   - Height  
   - Weight  
3. Program calculates:
   - **BMI (Body Mass Index)**
   - **BMI category**
4. User enters height (in cm) and gender for **ideal weight formulas**.
5. Program outputs:
   - Ideal Weight (Devine Formula)
   - Ideal Weight (Robinson Formula)

---

## 🛠️ Technologies Used

- **Java** (JDK 8 or later)
- **Scanner** for input handling
- Mathematical formulas for BMI and IBW

---

## ▶️ Running the Program

Compile the Java file:

```bash
javac HealthCalculator.java


