# Greene County Housing Analytics Report

This project analyzes housing value trends in Greene County using Zillow Housing Data (ZHVI).  
Focus areas: ZIP codes **30642**, **30669**, and **30678** from **2010–2025**.

---

## 📊 Executive Summary
- **Highest Value:** ZIP `30642` — **$712,439** (July 2025), **+2.88%** annual change.  
- **Fastest Growth:** ZIP `30678` — **$555,761** (July 2025), **+3.22%** annual change.  
- **Lowest Performer:** ZIP `30669` — **$173,132** (July 2025), **−2.44%** annual change.  

### Long-Term Trends
- **2010–2019:** Flat housing values with volatile growth.  
- **2020–2022:** Sharp surge across all ZIPs (annual growth rates near 30%).  
- **2023–2025:** Growth slowed, volatility re-emerged (possible market correction).  

---

## 📈 Current Values & Growth

| ZIP Code | Current Value (Jul 2025) | Annual Growth Rate |
|---------:|-------------------------:|-------------------:|
| **30642** | $712,439 | +2.88% |
| **30678** | $555,761 | +3.22% |
| **30669** | $173,132 | −2.44% |

---

## ⚙️ Methodology

**Metrics Calculated**
```text
Annual % Change = ((Current − Previous) / Previous) × 100
3-Year / 5-Year Change = Compound Annual Growth Rate (CAGR)
Year-on-Year Growth = % change between yearly medians
