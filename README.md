# OYO-hotel-booking-dashboard
Interactive executive dashboard for OYO Hotels — 119K booking records, 12 charts, built with Chart.js

# OYO Hotels — Executive Dashboard

An interactive single-page executive dashboard built for CEO/CFO-level analysis of OYO hotel booking data.

## 🔗 Live Demo
[View Dashboard](https://yourusername.github.io/oyo-hotel-booking-dashboard/oyo_dashboard.html)

## 📊 Overview
- **Dataset:** 119,390 booking records · 2015–2017 · 32 columns
- **Hotel types:** Resort Hotel & City Hotel

## 📈 Features
- 6 dynamic KPI cards (Revenue, Cancellation Rate, ADR, Lead Time, Repeat Rate)
- 12 interactive charts: trend lines, heatmap, box plot, donut, scatter, choropleth
- Global filters: Year, Hotel Type, Market Segment, Customer Type, Booking Status
- Auto-generated executive insights panel
- Dark mode toggle + Export to PDF

## 🛠 Tech Stack
- HTML5 · CSS3 · Vanilla JavaScript
- Chart.js 4.4 for all visualizations
- Pre-aggregated data pipeline in Python (pandas)

## 💡 Key Findings
- Overall cancellation rate: **37%** — Groups segment peaks at **61%**
- Non-refundable deposit bookings cancel at **99.4%** (administrative cancellations)
- Guests with 5+ special requests cancel at only **5%** vs **47.7%** with zero requests
- Portugal (PRT) contributes **40.7%** of all bookings with a **56.6%** cancel rate

## 📁 Files
| File | Description |
|------|-------------|
| `oyo_dashboard.html` | Main dashboard (open in any browser) |
| `hotel_bookings.csv` | Raw dataset |
