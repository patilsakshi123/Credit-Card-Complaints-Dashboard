# Credit Card Complaints Dashboard

### 🗂️ **Problem Statement**

Credit card companies receive thousands of complaints daily — from billing issues to fraud disputes. Managing these complaints efficiently is crucial for customer trust, compliance, and operational improvement. However, without an integrated, interactive, and dynamic dashboard, tracking complaint volumes, response times, resolution rates, and issue trends is time-consuming and prone to oversight.

---

### 🎯 **Project Objective**

To design and build an **end-to-end, fully interactive Tableau dashboard** that tracks, analyzes, and visualizes credit card complaints — enabling stakeholders to monitor KPIs, analyze trends, identify bottlenecks, and export insights easily.

---

### 🔑 **Dashboard Details**

The dashboard is divided into **functional panels**, combining multiple advanced Tableau features to deliver **insights at a glance**:

---

#### ✅ **1️⃣ KPI Overview Panel**

**A. Total Complaints**

* **Total Complaints Count:** Shows the total number of complaint records.
* **Rolling 12 Months Complaints:** Displays the total complaints in the most recent 12-month window — dynamically calculated.
* **Sparkline:** An area+line chart showing monthly trends of complaint volumes.

**B. Timely Response**

* **Timely Response Count:** Number of complaints that received a timely response (`Yes`).
* **Closed %:** The percentage of total complaints closed on time.
* **Progress Bar:** A dual-axis bar chart visually comparing closed % vs. 100%.

**C. In-Progress**

* **In-Progress Complaints Count:** Complaints still marked “In Progress”.
* **In-Progress %:** Share of all complaints still open.
* **Weekly Sparkline:** Trend line showing how in-progress complaints evolve week by week.

---

#### 📈 **2️⃣ Complaint Trends Analysis**

* **Combo Line + Area Chart:** Visualizes complaint counts over time (Weekly, Monthly, Quarterly, Yearly).
* **Dynamic Reference Lines:** An average line updates with the selected timeframe.
* **User Toggle:** A parameter lets users switch the granularity dynamically.

---

#### 🗺️ **3️⃣ Geographical Analysis**

* **Density Map:** Highlights complaint hotspots with color intensity.
* **Filled Map:** Choropleth map showing complaint volumes by state.
* **Map Toggle:** Users can switch between Density and Filled map views using a parameter.

---

#### 🔎 **4️⃣ Issues Analysis**

* **Top 10 Issues Bar Chart:** Ranks the most common complaint issues by volume.

---

#### 📋 **5️⃣ Response Breakdown**

* **Company Response Table:** Matrix showing company response categories, number of complaints, and % of total complaints.

---

#### 📅 **6️⃣ Daily Complaints Calendar**

* An interactive calendar heatmap shows daily complaint counts for the selected month — darker shades = more complaints on that day.

---

#### 📊 **7️⃣ Submitted Via Table**

* Table showing which channels customers use to submit complaints, with record counts for each channel.

---

#### 🔄 **8️⃣ Interactivity & Export**

* **Dynamic Filters:** Action filters on charts, quick filters for date/issue/state/response.
* **Export Panel:** Allows users to export the dashboard as PDF, PPT, or PNG in multiple layouts.

---
#### ✨ **Dashboard Snapshots**

<img width="1178" height="662" alt="dashboard " src="https://github.com/user-attachments/assets/20e85f06-ba6c-427a-99cd-9b6f76bfcfc9" />


---
#### ✨ **Design Highlights**

* Clean, consistent color palette (dark blue, coral red, white highlights).
* KPIs grouped in floating containers with icons and clean typography.
* Sparklines and progress bars to instantly show performance direction.
* Sheet swapping, parameters, LODs, dual-axis charts — all used in real time.

---

### 🛠️ **Tools & Techniques Used**

* **Software:** Tableau Desktop Public
* **Techniques:**
  * Level of Detail (LOD) calculations
  * Dynamic rolling window logic
  * Parameters for sheet swapping & time toggling
  * Dual-axis charts (combo charts, progress bars)
  * Dynamic reference lines
  * Calendar heatmaps
  * Action filters & quick filters
  * Export options (PDF, PNG, PPT)

---

### 🌟 **Project Highlights**

* Fully dynamic, interactive, single-page dashboard.
* Combines **time trends, geographical insights, issue breakdowns, and daily heatmaps** in one cohesive view.
* Uses advanced Tableau techniques for real-time interaction and filtering.
* Professional design with clear hierarchy and easy navigation.
* Ready for real business scenarios (can plug real data in).

---

### 💡 **Skills Demonstrated**

* Business problem framing & solution design.
* Advanced Tableau Desktop skills.
* Data modeling, parameter-driven logic, and calculated fields.
* Visual storytelling and user experience design.
* Effective dashboard layout and export-ready presentation.
* Explaining design choices and documenting for stakeholders.

---

### ✅ **Final Outcome**

A fully functional **Credit Card Complaints Dashboard** that helps any credit card company track, manage, and analyze complaints efficiently — improving customer service, compliance tracking, and operational decisions.


