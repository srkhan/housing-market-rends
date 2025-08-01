# housing-market-rends
a starter project on U.S. Housing Trends to help learn technologies like d3.js, react, tailwind and hosting technologies

## Project Roadmap

### **1. Set Up the Project**

* Create a new React project with Vite.
* Install dependencies: `d3`, `axios`, and optionally `tailwindcss` for styling.

### **2. Get Housing Data**

* Sign up for a free **FRED API key**.
* Use the **Case-Shiller U.S. Home Price Index** (`CSUSHPINSA`) as your first dataset.
* Later, add **state-level data** from FHFA or Zillow for more detail.

### **3. Build Core Components**

* **MetricCards** → Show latest price index + YoY change.
* **LineChart (D3)** → Plot housing prices over time.
* **Table of housing data**
* Add `useEffect` in React to fetch and format the API data.

### **4. Add Interactivity**

* Filters:

  * Date range (e.g. 2000–2025).
  * Metric (e.g. index, % change).
  * Region (when you add state data).

### **5. Style the Dashboard**

* Use TailwindCSS (or Chakra UI) for responsive layout and styling. ( want to use TailwindCSS)
* Create a clean grid layout with cards and charts. (going to create a task for a wireframe/mockup as I want to make this a multi page dashboard)

### **6. Deploy**

* Push your code to GitHub.
* Deploy to **Vercel** or **Netlify**.
* Store your **FRED API key** in environment variables.

### **7. Optional Enhancements**

* Add a **D3 choropleth U.S. map** for state comparisons. (really want to create this)
* Pull in **mortgage rate data** from FRED to show affordability context. (this might be a future enhancement)
* Add **React Query** for caching API results. (good learning opporuntity for a common practice)
* Add **dark mode** and hover tooltips. (classic UI feature to implement)

