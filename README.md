# JNE Operational Efficiency 🚚📊

Operational efficiency analysis of shipping data (e.g., JNE) using Python and Pandas.
This project aims to measure **On-Time Delivery (OTD)**, service efficiency, and create operational visualizations.
---

## 📂 Project Structure
- `shipments.csv` → shipping dataset
- `jne_operational_efficiency.py` → primary Python code
- `README.md` → project documentation

---

## ⚙️ Technology Used
- Python 3.13.5
- Pandas
- Numpy
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 📊 Analyse
1. Parse date data (booking, pickup, delivery).
2. Create derived columns (month, day, SLA, etc.).
3. Measure On-Time Delivery (OTD).
4. Analyze efficiency based on:
  - Service type
  - Month
  - Distance & shipment weight
5. Visualize On-Time Delivery (OTD) and shipment volume.

---

## 🧑🏻‍💻 Summarize and Solutions
1. Which service has the lowest OTD,Why? 
    ✅ (distance, dwell time volume load)
    ✅ Evaluate service SLAs, set capacity, adjust delivery  commitments.
2. Which hub has high dwell time and low OTD 
    ✅ Candidate process fixes (shift, cut-off, linehaul)
3. 10 worst routes
    ✅ Create specific actions (reschedule linehaul, reroute via alternative hub).
    ✅ Create route-level dashboards for performance monitoring
4. Months with spikes in demand 
    ✅ Prepare capacity planning (manpower,linehaul,3rd party support)
    ✅ Action: Forecast monthly demand → allocate resources early
5. Economic impact
    ✅ Calculate estimates → refunds, complaints, contribution margin.
    ✅ Create a business case → show that increased OTD = cost savings & increased customer satisfaction

---

## Next Steps for Continuous Improvement
- 📊 Build KPI dashboard (hub, service, route, SLA)
- 🤖 Explore predictive analytics → predict OTD risk before shipment departs
- 🔄 Implement closed-loop feedback → every problem (hub/route) has corrective action

---

## ▶️ How to Execute
Clone repo here:
```bash
git clone https://github.com/justnnik/jne-operational-efficiency.git
cd jne-operational-efficiency
