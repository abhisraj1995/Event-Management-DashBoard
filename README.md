# 🎯 KSR Event Management Analytics Dashboard  
**KSR DATAVIZON - Key to Sustainable Results**  
**Period Covered:** 2018 – 2024  

---

## 🧭 Overview  
The **KSR Event Management Analytics Dashboard** is a comprehensive Power BI solution designed to track and analyze event performance across multiple dimensions including **Financial Performance, Event Metrics, Attendance Rates, Geographic Distribution, and Organizer Performance**.  

This interactive dashboard provides event managers and stakeholders with actionable insights into **Revenue, Profit, ROI, Attendance Patterns, Event Ratings, and Regional Performance** — enabling data-driven decision-making for optimal event planning and execution.  

---

## 🎯 Purpose  
To deliver a **unified analytical platform** that empowers event management teams to:  
- Monitor financial health and profitability of events  
- Track attendance rates and engagement trends  
- Evaluate event quality through ratings and feedback  
- Analyze geographic and category-wise performance  
- Optimize resource allocation and maximize ROI  

---

## ⚙️ Tech Stack  
| Tool | Purpose |
|------|----------|
| 🧠 **Power BI Desktop** | Primary data visualization and dashboard development |
| 🧹 **Power Query** | Data transformation, cleaning, and ETL processes |
| 🧮 **DAX (Data Analysis Expressions)** | Advanced calculations for KPIs, ROI, Profit Margins, and YOY metrics |
| 🗃️ **Data Modeling (Star Schema)** | Structured relationships between fact and dimension tables |
| 🎨 **Custom Visuals** | Gauge charts, donut charts, heatmaps, and geographical maps |
| 💾 **File Formats** | `.pbix` (Power BI project file), `.png` (dashboard screenshots) |

---

## 🗂️ Data Model & Source  
**Source:** Simulated event management dataset created for comprehensive analytics demonstration.  

### 📋 Tables Overview  

#### 🎫 FACT_Events_Data  
Core transactional table containing:  
`Event_ID`, `Event_Name`, `Event_Type`, `Event_Format`, `Event_Date`, `Duration`, `Category_Key`, `City_Key`, `Venue_Key`, `Organizer_Key`, `State_Key`, `Attended_People`, `Attendees_Rate`, `Total_Revenue`, `Total_Investment`, `Total_Profit`, `ROI %`, `Avg_Rating`, `Ticket_Selling_Price`, `Lunch/Snacks_Provided`, `Seating_Capacity`, `No_of_Registrations`  

Used for all KPI calculations and performance analysis.

#### 📂 DIM_Category  
Contains event categories:  
`Category_Key`, `Category` (Arts, Business, Entertainment, Fashion, Film, Food, Literature, Sports, Technology, Wellness)  

#### 🏙️ DIM_City  
City-level information:  
`City_Key`, `City` (Hyderabad, Chennai, Ahmedabad, Bengaluru, Mumbai, Visakhapatnam, Pune, Kochi, Coimbatore, Indore, etc.)  

#### 🏢 DIM_Organizer  
Organizer details:  
`Organizer_Key`, `Organizer` (TechSkills, AppDevGuild, ProjectFlow, SoundCanvas, DigiMarkPro, etc.)  

#### 🗺️ DIM_State  
State-level geographic data:  
`State_Key`, `State` (Andhra Pradesh, Assam, Chhattisgarh, Delhi, Goa, Gujarat, Haryana, Himachal Pradesh, Karnataka, Kerala, Maharashtra, Odisha, Puducherry, Punjab, Rajasthan, Tamil Nadu, Telangana, Uttar Pradesh)  

#### 📍 DIM_Venue  
Venue information:  
`Venue_Key`, `Venue` (Various event venues across cities)  

---

## 🧩 Business Problem  
Event management teams struggled with:  
- **Fragmented data** across multiple event categories and locations  
- **Limited visibility** into financial performance and ROI  
- **Difficulty tracking** attendance patterns and engagement trends  
- **Inefficient resource allocation** without data-driven insights  
- **Lack of geographic analysis** for strategic event planning  

**Solution:** A centralized, interactive dashboard providing 360° visibility into event operations and performance.

---

## 🚀 Dashboard Goals  
✅ Track **overall event performance** and financial health  
✅ Analyze **ROI and profitability** by category, city, and organizer  
✅ Monitor **attendance rates** and event format distribution  
✅ Identify **top-performing events, categories, and organizers**  
✅ Enable **geographic analysis** for strategic expansion  
✅ Evaluate **engagement trends** and seasonal patterns  

---

## 📈 Dashboard Walkthrough  

### 📄 Page 1: Overview Dashboard  

#### 🔹 **Top KPIs (Cards)**  
| Metric | Value |
|--------|--------|
| 🎪 **Total Events** | 9,964 |
| 💰 **Total Revenue** | $325.3M |
| 💵 **Total Profit** | $119.4M |
| 📊 **ROI %** | 58 |
| ⭐ **Avg Rating** | 4.3 |

---

#### 📊 **Key Visuals**  

##### 📈 Revenue & Profit Trending (2018-2024)  
- **Line + Bar Combo Chart** showing Total Profit (green bars) and Total Revenue (cyan line)  
- Clear upward trend from 2018-2023 with slight decline in 2024  

##### 🎯 Attendance Rate Gauge  
- **Current Rate:** 90.35%  
- Visual gauge showing performance against 100% target  

##### 🎭 Event Format Distribution  
- **Donut Chart** breakdown:  
  - In-person: 50.46%  
  - Hybrid: 33.52%  
  - Virtual: 16.02%  

##### 🏆 Top 5 Categories by ROI  
1. Arts – 67.1%  
2. Entertainment – 64%  
3. Food – 63.9%  
4. Film – 63.8%  
5. Sports – 62.5%  

##### 📊 Total Registrations vs Attendees  
- **Registrations:** 537.42K  
- **Attendees:** 485.58K  
- **Attendance Rate:** 90.4%  

---

## 📄 Page 2: Financial Performance  

#### 🔹 **Financial KPIs**  
| Metric | Value |
|--------|--------|
| 💰 **Total Revenue** | $325.3M |
| 📈 **Total Investment** | $205.8M |
| 📊 **Profit Margin %** | 37 |
| 💡 **Investment Efficiency** | 1.6 |

---

#### 🗺️ ROI Performance Heatmap  
- Matrix view by State vs Category  
- Color-coded performance  
- Rajasthan and Gujarat show highest ROI (>85%)  

---

## 📄 Page 3: Event Performance  

#### 🏆 Top Rated Events  
- International Cooking Class (4.8⭐)  
- Baking Masterclass (4.7⭐)  
- Yoga and Sports Combo (4.6⭐)  

#### 📈 Seasonal Engagement Trend  
- **Peak Months:** March, April, August  
- **Low Months:** June, September  

---

## 📄 Page 4: Geographic & Organizer Performance  

#### 🏙️ Top Cities by Revenue  
1. Hyderabad – $35.6M  
2. Chennai – $29.6M  
3. Ahmedabad – $22.5M  
4. Bengaluru – $22.1M  
5. Mumbai – $21.0M  

#### 🏆 Top Organizers  
| Organizer | Avg Rating | Total Revenue | Profit Margin % |
|-----------|-------------|---------------|----------------|
| TechSkills | 4.47 | $18.1M | 40% |
| AppDevGuild | 4.36 | $16.1M | 39% |
| ProjectFlow | 4.50 | $22.5M | 39% |
| SoundCanvas | 4.28 | $21.0M | 37% |
| DigiMarkPro | 4.36 | $35.6M | 33% |

---

## 💡 Key Insights  
- Overall ROI: **58%**  
- Profit Margin: **37%**  
- Attendance Rate: **90.35%**  
- In-person events dominate (50%)  
- Arts category leads ROI (67%)  

---

## 🖼️ Dashboard Preview  

### 📊 Overview Dashboard  
![Overview Dashboard](https://github.com/abhisraj1995/Event-Management-DashBoard/blob/main/Event%20Management%20Protfolio%20Dashboard.png)

### 💰 Financial Performance  
![Financial Performance](https://github.com/abhisraj1995/Event-Management-DashBoard/blob/main/Event%20Management%20Financial%20Performance%20Dashboard.png)

### 🎟️ Event Performance  
![Event Performance](https://github.com/abhisraj1995/Event-Management-DashBoard/blob/main/Event%20Management%20Event%20Performance%20DashBoard.png)

### 🌍 Geographic & Organizer Performance  
![Geographic & Organizer Performance](https://github.com/abhisraj1995/Event-Management-DashBoard/blob/main/Event%20Management%20Geographic%20%26%20Organizer%20DashBoard.png)

---

## 💼 Business Impact & Insights  

### 🎯 Key Findings  

#### 💰 Strong Financial Performance  
- **58% overall ROI** demonstrates healthy profitability  
- **$119.4M profit** from **$325.3M revenue** → **37% profit margin**  
- Consistent revenue growth from **2018–2023**

#### 👥 High Attendance Engagement  
- **90.35% attendance rate** → strong event appeal  
- **90.4% conversion** from registrations to actual attendance  
- Food provision significantly impacts ratings (**5.0 vs 4.0**)

#### 🏆 Category Performance  
- **Arts events** generate highest ROI (**67.1%**)  
- **Entertainment** and **Food** categories show strong profitability  
- **Technology** and **Business** events have high volume but lower margins  

#### 🌍 Geographic Insights  
- **Hyderabad** leads in revenue generation (**$35.6M**)  
- **Metro cities** (Mumbai, Bengaluru, Chennai) drive major profits  
- **North** and **West** regions show higher ROI potential  

#### 👨‍💼 Organizer Excellence  
- **DigiMarkPro** generates highest revenue (**$35.6M**)  
- **ProjectFlow** maintains highest rating (**4.50**)  
- **TechSkills** shows best profit margin (**40%**)  

#### 🧾 Event Format Preferences  
- **In-person** events dominate (**50.46%**)  
- **Hybrid** format gaining traction (**33.52%**)  
- **Virtual** events maintain steady presence (**16.02%**)  

---

## 📊 Dashboard Features  

### 🎨 Interactive Elements  
✅ **4-Page Navigation** — Overview, Financial, Event, and Geographic & Organizer Performance  
✅ **Dynamic Filters** — Filter by date, category, city, state, organizer  
✅ **Cross-Page Interactions** — Click-through analysis across all pages  
✅ **Custom Tooltips** — Detailed insights on hover  
✅ **Bookmarks** — Save and switch between customized views  
✅ **Drill-through Pages** — Deep dive into specific events or organizers  

### 🎯 Visual Highlights  
📊 Line & Bar combo charts for trend analysis  
🎯 Gauge charts for performance metrics  
🗺️ Interactive map for geographic analysis  
🔥 Heatmap for ROI and profitability  
📈 Scatter plots for engagement and rating patterns  
📋 Tables with conditional formatting for instant comparison  

---

## 🧠 Key Learnings  

✅ Designed a **multi-page dashboard** with intuitive navigation and UX  
✅ Built **complex DAX measures** (ROI, profit margins, YOY calculations)  
✅ Implemented **advanced visuals** — heatmaps, maps, scatter plots  
✅ Created **interactive filters** and **cross-page drill-throughs**  
✅ Applied **data modeling best practices** (Star Schema architecture)  
✅ Used **conditional formatting** for visual storytelling  
✅ Developed **custom color themes** aligned with brand identity  
✅ Optimized performance for a **large dataset (9,964 events)**  

---

## 🪄 Future Enhancements  

🔹 Add **predictive analytics** for attendance & revenue forecasting  
🔹 Integrate **real-time data refresh** via API connections  
🔹 Implement **what-if analysis** for scenario planning  
🔹 Create **mobile-optimized** dashboard views  
🔹 Add **email subscriptions** for automated report delivery  
🔹 Include **sentiment analysis** from event feedback  
🔹 Develop **budget vs actual** comparison visuals  
🔹 Integrate **weather data** to analyze seasonal impact  

---

## 🙏 Acknowledgments  

- Power BI Community for **visualization inspiration**  
- **KSR DATAVIZON Team** for project support  
- **Event Management Industry** for domain insights  

---

## 👨‍💻 Author  

**Abhishek Raj**  
💼 *Data Analyst | Power BI Developer | Business Intelligence Specialist* 

## 📌 Tags  
**Power BI** · **Data Analytics** · **Event Management** · **Business Intelligence** · **Dashboard** · **DAX** · **Data Visualization** · **ROI Analysis**
