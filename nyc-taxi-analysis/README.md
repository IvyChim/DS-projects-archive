# 🗽 NYC Yellow Taxi Data Analysis (2016)

This project analyzes yellow taxi trip data in New York City for the year **2016**, using the [BigQuery Public Dataset](https://console.cloud.google.com/marketplace/product/bigquery-public-datasets/new_york_taxi_trips).  
The goal is to uncover patterns in ride behavior, earnings, tipping, and the effect of external factors such as **weather**.

> 🔗 **View the full interactive report**:  
> [👉 Click here to view the HTML report](https://ivychim.github.io/DS-projects-archive/nyc_taxi_analysis.html)

---

## 🔍 Questions Answered

**Q1: How does the number of taxi rides vary over time of day?**
Ride volume is lowest in the early morning hours (around 4–6 AM), then increases sharply during the morning commute (7–9 AM). Activity remains steady throughout the afternoon and peaks in the evening, with the highest number of rides occurring between 6 PM and 8 PM. After 9 PM, the number of rides gradually decreases.

This pattern suggests that demand is highest during evening hours, likely due to people commuting home, attending events, or going out for leisure. Drivers aiming to maximize their trip count should consider working during late afternoons and early evenings.

**Q2: What types of trips are common?**
The majority of trips tend to be short and medium distance, indicating most passengers take relatively brief rides.

**Q3: Are short or long trips better for drivers?**
Long trips generally bring higher total fares and tips per ride, which can increase driver earnings per trip. However, short trips may allow drivers to complete more rides in a shorter time, potentially increasing overall income through volume. The balance depends on factors like traffic, wait times, and fare structure, but typically, long trips yield higher earnings per trip while short trips might offer more frequent earning opportunities.

**Q4: Can the weather explain changes in taxi activity?**
Generally, heavier rainfall corresponds to increased taxi usage, likely because people avoid walking or using public transport in wet conditions. However, the data also shows that during extremely heavy rain, the number of taxi rides can drop significantly, possibly due to unsafe driving conditions or fewer people traveling overall. Similarly, extreme temperatures (very cold or very hot) can also influence the number of rides, showing that weather conditions do have a noticeable impact on taxi demand.

**Q5: How can drivers earn more tips?**
Focus on Longer Trips: While the first image shows a wide range of trip distances, longer trips (e.g.,60-120 minutes) in the "Tip Amount by Trip Duration" graph tend to have higher tip amounts. Drivers may earn more by accepting or prioritizing longer rides.

Work During Peak Hours: The "Tip Amount by Hour of Day" graph indicates that tips are higher during certain hours, likely corresponding to rush hours or late-night times when demand is high. Drivers can maximize earnings by working during these peak hours (e.g., early morning, midday, or evening).
---

## 📁 Project Structure
├── nyc_taxi_analysis.ipynb # Jupyter notebook with code & plots
├── nyc_taxi_analysis.html # Exported HTML report (for GitHub Pages)
├── README.md # Project overview (this file)
└── ...

## 🚀 Technologies Used

- **Python (pandas, seaborn, matplotlib, etc.)**
- **Google BigQuery** (for querying large datasets)
- **Jupyter Notebook**
- **GitHub Pages** (for publishing the report)

---

## 📫 Contact

Feel free to connect or reach out:

- GitHub: [@IvyChim](https://github.com/IvyChim)
- Email: ivy_zcf@outlook.com

---
