# 🛡️ Active Directory Risk Analyzer – SoCON2025 Edition

This project provides a research and analysis environment for **Active Directory security** using data from **SharpHound** and **BloodHound Community Edition**. It is designed to help identify over-privileged users and groups, visualize attack paths, and calculate risk scores in a structured and extensible way.

---

## 📓 Try it on Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lucky-luk3/SoCON-2025---Keep-only-those-privileges-that-speak-to-your-heart/blob/main/SoCON2025%20-%20Keep%20only%20those%20privileges%20that%20speak%20to%20your%20heart.ipynb)


---

## 📁 Project Structure

- **`SoCON2025 - Keep only those privileges that speak to your heart.ipynb`**  
  Main notebook for AD data analysis, visualization, and risk scoring.

- **`mylab.zip`**  
  Contains raw **SharpHound** data captures used for ingestion and enrichment.

- **`users.csv`**  
  Processed user dataset, enriched with control relationships and privilege metrics.

- **`groups.csv`**  
  Processed group dataset with privilege aggregation and group dynamics.

- **`rooted_utils.py`**  
  Utility functions used for multithreaded execution and performance improvements in the notebook.

---

## 🧠 Notebook Features

- BloodHound CE API integration.
- Graph-based privilege analysis and risk scoring.
- Attack path detection and escalation analysis to Domain Admins or Tier Zero objects.
- Interactive filters, custom weighting, and statistics tracking per execution.
- 3D graph visualizations based on risk, control paths, and privilege origin.

---

## 🚀 Goal

Help Blue Teams clean up Active Directory by identifying dangerous privilege configurations, overpowered groups, and stealthy escalation paths—before attackers do.

---