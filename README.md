# 🌍📊 World Population Data Scraping & Visualization

## 📌 Project Overview
This project is a data analytics case study focused on **automated web scraping** to collect world population data from **Wikipedia**, followed by data processing and visualization.

The main objective is to understand **global population distribution** and highlight **population inequality between countries** using a data-driven approach.

---

## 🚀 Key Features

### 🔎 Automated Web Scraping
Retrieves country population data in real-time from Wikipedia tables.

### 🧹 Data Cleaning
Raw data is processed using **Pandas** to:
- Clean numeric formats  
- Convert percentage values  
- Handle missing values  
- Prepare structured data for visualization  

### 📊 Data Visualization
Multiple visual representations are created to make insights easier to understand:

| Visualization | Purpose |
|--------------|---------|
| 📈 Horizontal Bar Chart | Shows **Top 10 & Bottom 10** countries by population |
| 🍩 Donut Chart | Displays each country's contribution to world population |
| 🍭 Lollipop Chart | Aesthetic comparison of population ranking |

---

## 🖼️ Visualization Results

### 🌍 Top Populated Countries
![Top Countries](https://github.com/Agush01-ui/ProjectDataScraping/blob/main/NegaraTerbanyak.png?raw=true)

### 🌎 Countries with the Smallest Population Share
![Smallest Countries](https://github.com/Agush01-ui/ProjectDataScraping/blob/main/NegaraPersentaseTerkecil.png?raw=true)

### 🍭 Population Ranking — Lollipop Chart
![Lollipop Chart](https://github.com/Agush01-ui/ProjectDataScraping/blob/main/LollipopChart.png?raw=true)

### 🍩 Population Contribution — Donut Chart
![Donut Chart](https://github.com/Agush01-ui/ProjectDataScraping/blob/main/DonutChart.png?raw=true)

### 📊 Barplot Visualization
![Barplot](https://github.com/Agush01-ui/ProjectDataScraping/blob/main/Barplot.png?raw=true)

---

## 📈 Visualization Insights

### 🌏 1. Global Population Dominance
India and China each contribute more than **18% of the world population**.  
Combined, the **top 10 most populated countries** account for **more than half of the global population**.

### ⚖️ 2. Extreme Inequality
There is a massive gap between the highest and lowest ranked countries.  
Indonesia ranks 4th (~3.5%), while countries like **Vatican City** and **Pitcairn Islands** contribute almost **0.0000%** globally.

### 📉 3. Ranking Gap
The Lollipop Chart clearly shows the significant difference between the **“Big Two” (India & China)** and the rest of the countries.

---

## 🛠️ Tools & Libraries
- 🐍 Python  
- 🧮 Pandas  
- 📊 Matplotlib  
- 🎨 Seaborn  
- 🌐 BeautifulSoup (Web Scraping)  
- 🔗 Requests  

---

## ▶️ How to Run This Project

```bash
# Clone repository
git clone https://github.com/Agush01-ui/ProjectDataScraping.git

# Enter project directory
cd ProjectDataScraping

# Install dependencies
pip install pandas matplotlib seaborn beautifulsoup4 requests

# Run the script
python main.py
