# 📊 Market Return Dashboard — FY 2025–26
**ABC Corporation Ltd. | Damage Settlement Analysis**

A fully interactive, single-file executive dashboard built with
pure HTML, CSS and JavaScript. No backend. No subscriptions.
Just open in a browser.

![Dashboard Preview](screenshot.png)

---

## ✨ Features

- **Auto-update on upload** — drop your Excel file, dashboard
  renders in 10 seconds
- **10-second animated loader** — inline progress animation
  inside the drop zone
- **6 live KPIs** — Indent, Audited, Settlement, Gap, Rate
- **5 interactive charts** — Region bar, Area scorecards,
  DB Type, BD Status, Audit Variance
- **4 auto-generated insights** — written from live data
- **4 cascading slicers** — Region → Area → DB Type → BD Status
- **⬇ Excel export** — downloads filtered data instantly
- **📷 Screenshot button** — saves 2× retina PNG, share anywhere
- **Ash color palette** — corporate-grade design
- **Pixel-perfect layout** — locked to 1122 × 794 px (A4 landscape)

---

## 📁 File Structure
market-return-dashboard/
│
├── abc_market_return_1122x794.html   ← main dashboard file
├── screenshot.png                    ← preview image
└── README.md                         ← this file
---

## 🚀 How to Use

1. Download `abc_market_return_1122x794.html`
2. Open it in any modern browser (Chrome, Edge, Firefox)
3. Upload your `Market_Retun_File-_FY_25-26.xlsx`
4. Dashboard updates automatically

**Required Excel columns:**
| Column | Description |
|---|---|
| Region | Geographic region |
| Area | Sub-region area |
| TT | Territory |
| DB Type | Combined / Line-1 / Line-2 / SD |
| BD Status | True / False |
| Total Indent Value | Claimed damage value |
| Audited Value | Post-audit value |
| Total DPRate | Settlement / DP rate paid |

---

## 🛠 Built With

- **HTML5 / CSS3 / Vanilla JavaScript**
- **Chart.js 4.4.1** — charts and visualizations
- **SheetJS (xlsx)** — Excel file parsing
- **html2canvas** — screenshot capture
- **Google Fonts** — Inter + IBM Plex Mono
- **Claude AI** — design, logic, and build assistance

---

## 📸 Preview

> Upload your file → 10 second animated load →
> full dashboard renders live

---

## 📄 License

MIT License — free to use, modify and share.

---

## 🙋 Author

**SHAGAR GOSHAMI**
[LinkedIn](www.linkedin.com/in/shagar-goshami)
