# Hotel_Performance_Analysis
End-to-End Hotel Performance Analytics: Relational schema design and 10 analytical queries in MySQL Workbench connected to an interactive Power BI Executive Dashboard. 

The project starts with database design and normalization in MySQL Workbench, extracts key business metrics using 10 analytical SQL queries, and visualizes the results through an interactive executive dashboard in Power BI.

---

## Database Architecture
The database is structured into five core tables with defined primary and foreign key relationships:
- **Guests:** Stores guest profile details and contact information.
- **Rooms:** Contains room inventory, room types, floor numbers (Floors 1 to 4), and live availability status.
- **Bookings:** Tracks reservation details, check-in and check-out dates, total billing amounts, and booking statuses.
- **Payments:** Records transaction amounts, payment dates, settlement status, and payment methods.
- **Services:** Details add-on hotel services requested by guests during their stay.

---

## 10 Business Questions Answered
The project answers 10 key operational questions:
1. What is the total gross revenue, amount collected, and outstanding dues?
2. How many total bookings and guests were handled, and what is the average booking value?
3. Which room types generate the highest revenue share?
4. What are the monthly revenue trends and seasonal peaks?
5. Which physical floors generate the most and least revenue?
6. What is the breakdown of collections across different payment methods?
7. What are the most frequently requested add-on services?
8. What is the current ratio of occupied rooms versus available inventory?
9. How many bookings were cancelled, and what was the revenue loss?
10. Who are the highest-spending guests for VIP loyalty outreach?

---

## Key Dashboard Metrics
Based on the Power BI dashboard:
- **Total Revenue:** $191.80K across 14 bookings.
- **Average Booking Value:** $13.70K per reservation.
- **Collections vs. Dues:** $135.40K collected (70.6%) with $56.40K in outstanding dues (29.4%).
- **Top Room Category:** Presidential Suite generated the highest revenue ($45K, accounting for 23.5% of total revenue).
- **Peak Performance Floor:** Floor 3 led performance with $91K in revenue, followed by Floor 2 ($68K).
- **Payment Method Preferences:** Digital payments dominate collections, led by Card (52.7%) and UPI (22.9%), with Cash accounting for 13.7%.
- **Top Ancillary Services:** Airport Drop (6 requests) and Extra Bed (3 requests) were the most popular add-ons.
- **Inventory Status:** 14 rooms available and 6 rooms occupied.

---

## Business Insights & Takeaways
- **Promote Luxury Tiers:** High-end rooms like the Presidential Suite drive a disproportionate share of total revenue, showing strong demand for luxury inventory.
- **Address Floor Performance Gaps:** Floor 4 generated only $10K compared to Floor 3 ($91K). Investigating room pricing or running promotions for Floor 4 rooms can balance occupancy.
- **Automate Payment Follow-ups:** Over $56K remains in outstanding balances, highlighting an opportunity to introduce pre-checkout digital payment reminders.
- **Bundle Transit Services:** With Airport Transfers in high demand, offering bundled packages during room reservation can increase average booking values.

---

## Tools & Technologies
- **MySQL & MySQL Workbench:** Database schema design, table normalization, and analytical SQL querying.
- **Power BI Desktop:** Data modeling, star schema relationships, and interactive report design.
- **DAX:** Custom measures for KPI cards, occupancy tracking, and collection calculations.
