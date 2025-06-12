# 📚 Books Dashboard (Power BI)

This interactive dashboard was created using Power BI to analyze and visualize customer bookings for various services like Party Room, Play Area, and Classes. It enables tracking revenue, booking trends, and service performance to support data-driven business decisions.

---

## 📊 Dashboard Highlights

- 💰 **Total Revenue** and **Average Booking Price**
- 🧑‍🤝‍🧑 **Bookings per Customer**
- 📉 **Cancellation Rate** 
- 📅 **Booking Trends by Month**
- 🧾 **Booking Status Distribution** (Confirmed vs Pending)
- 📆 **Booking Date & Status Filters**
- 📈 **Revenue by Service Type**
- 📊 **Total Revenue by Year and Month**
- 📋 **Interactive Table View** of all customer bookings

---

## 🗂️ Dataset Overview

| Column Name      | Description                                 |
|------------------|---------------------------------------------|
| Booking ID       | Unique booking identifier                   |
| Customer Name    | Name of the customer                        |
| Booking Type     | Type of booking (Facility, Class, Party)    |
| Booking Date     | Date when the booking was made              |
| Status           | Whether the booking is Confirmed or Pending |
| Service Name     | Area or room booked                         |
| Duration         | Length of the service in minutes            |
| Price            | Amount paid for the booking                 |
| Theme            | Party theme (e.g., Princess, Sports)        |
| Subscription Type| Type of subscription, if any                |
| Instructor       | Instructor name (for classes)               |
| Time Slot        | Slot of booking (morning, afternoon, etc.)  |

---

## 📌 Key Insights

- Most bookings occurred in **April** and **May**.
- **Facility** and **Birthday Party** services are the highest revenue generators (~48K each).
- Statuses are almost evenly split: **Confirmed** (51%) and **Pending** (49%).
- The average booking price is **₹139.48**.

---

## ⚠️ Identified Problems & Suggestions

| Problem                                    | Suggested Solution                                         |
|-------------------------------------------|------------------------------------------------------------|
| Cancellation Rate shows blank             | Add logic to track and calculate cancelled bookings        |
| High number of pending bookings           | Set up reminder system or auto-confirmation workflows      |
| All price values are `0` in raw data      | Check data entry process or apply dynamic pricing updates  |
| Instructor and Time Slot values are dated | Review formatting or update to reflect correct date-times  |

---

## 🛠️ Tools Used

- **Power BI** for interactive visualizations and DAX measures
- **Excel** for data transformation and cleaning

---

## 👩‍💻 About Me

Hi! I'm **Surbhi Jain**, a passionate data analyst focused on building dashboards and insights that tell a story. I enjoy transforming data into meaningful decisions through Power BI, Excel, and SQL.

---

🔗 *Feel free to explore, fork the project, or connect with me for feedback or collaboration!*
