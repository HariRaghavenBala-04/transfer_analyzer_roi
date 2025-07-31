# ⚽ Transfer ROI Analyzer

![Repo size](https://img.shields.io/github/repo-size/HariRaghavenBala-04/transfer_analyzer_roi)
![Last commit](https://img.shields.io/github/last-commit/HariRaghavenBala-04/transfer_analyzer_roi)

---

## 📌 Project Overview

A data-driven tool designed to help football clubs evaluate whether a player transfer was "worth it" based on performance, cost, and resale value.

---

## 🎯 Why This Project?

I'm passionate about football strategy and data science. This project bridges both by modeling what makes a player signing valuable — from the perspective of a technical director.

---

## 👥 Who Is This For?

- Club recruitment teams  
- Analysts working in scouting or transfer strategy  
- Data scientists interested in sports economics

---

## 🧠 What I Hope to Learn

- Data merging and cleaning (across sources like FBref, Transfermarkt)
- Feature engineering (creating "value" metrics from raw stats)
- Building insights from a technical director's point of view
- Visual storytelling with Matplotlib/Seaborn/Plotly for decision-makers

---

## 📐 Initial ROI Formula

```text
ROI = (Performance Score + Resale Value if sold) / Transfer Fee

Performance Score = Goals + (0.5 × Assists) + (0.1 × Starts)
