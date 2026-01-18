# Urban Water Sustainability Model

This repository contains a system dynamics model built in **Vensim** that analyzes the interaction between urban population growth, water demand, and water supply. The model evaluates the impacts of conservation policies, infrastructure factors, and economic costs due to water shortages over time.

---

## 📌 Problem Statement

Urban areas face increasing pressure on water resources due to population growth, climate variability, and limited supply. This model helps explore:
- How stored water changes over time under different scenarios
- The effect of conservation policies
- The economic impact of water shortages

---

## 🧠 Model Overview

The model is built using **system dynamics** principles in Vensim, and includes:

### **Stocks**
- **Population** – Total urban population over time
- **Water Storage** – Total water available in storage

### **Flows**
- **Population Growth** – Growth increases total population
- **Water Inflow** – Rainfall + external supply added to water storage
- **Water Consumption** – Demand by population, adjusted by conservation and leakage

### **Auxiliary Variables**
- Growth rate
- Rainfall
- External water supply
- Per capita water use
- Conservation factor
- Leakage rate
- Water deficit
- Shortage cost

---

## 📊 Graphs & Results

The following visualizations show the behavior of key model variables under different scenarios:

### 1. Population Growth

![Population Growth](results/population_growth.png)

---

### 2. Water Storage – Base Scenario

No conservation policy:

![Water Storage Base](results/water_storage_base.png)

---

### 3. Water Storage – Conservation Policy

Conservation factor set to 0.3:

![Water Storage Conservation](results/water_storage_conservation.png)

---

### 4. Water Consumption

Demand over time with conservation:

![Water Consumption](results/water_consumption.png)

---

### 5. Shortage Cost

Economic impact when demand exceeds supply:

![Shortage Cost](results/shortage_cost.png)

---

## 📈 Key Insights

- Without conservation, stored water depletes rapidly due to high demand.
- Introducing a conservation policy significantly slows the rate of depletion.
- Leakage and infrastructure limits further stress water availability.
- Economic costs rise when consumption exceeds supply.

---

## 📂 Folder Structure

├── model/ # Vensim model (.mdl)
├── results/ # Graph images
├── README.md # Project description

🛠 Tools Used

- **Vensim PLE** – System dynamics modeling
- **GitHub** – Version control and portfolio hosting
