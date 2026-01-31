# Food Delivery Hackathon – Data Analysis

## Project Overview
This project is part of a data analysis hackathon focused on analyzing a food delivery platform’s data.  
The objective is to combine multiple datasets from different sources and perform meaningful analysis to answer business-driven questions.

---

## Datasets Used
The project uses three different data sources:

1. **orders.csv** – Transactional order data  
2. **users.json** – User master data containing city and membership information  
3. **restaurants.sql** – Restaurant master data containing cuisine and rating details  

These datasets simulate real-world data integration scenarios.

---

## Data Integration
- All datasets were combined using **LEFT JOINs**.
- Join keys used:
  - `user_id` → to merge orders with users
  - `restaurant_id` → to merge orders with restaurants
- The final merged dataset ensures that **all orders are retained**.

---

## Analysis Performed
The following analyses were performed using the final merged dataset:
- Order trends over time and quarter-wise revenue
- User behavior analysis (Gold vs Regular members)
- City-wise and cuisine-wise revenue analysis
- Restaurant performance based on ratings
- Average order value and high-value user identification

---

## Tools & Technologies
- **Python**
- **Pandas**
- **SQLite**
- **Jupyter Notebook**

---

## Project Files
- `analysis.ipynb` – Complete analysis notebook with code and outputs
- `README.md` – Project documentation

---

## Conclusion
This project demonstrates practical data integration and analysis techniques using real-world styled datasets.  
It highlights how insights can be derived by combining structured and semi-structured data sources.

---

## Acknowledgement
This project was completed as part of a hackathon to enhance hands-on experience in data analytics and problem-solving.
