# ![Viosimos Logo](viosimos.png) 
# Viosimos - Βιώσιμος (Sustainable)

**Viosimos** (Βιώσιμος in Greek, meaning *Sustainable*) is a simple, client-side web application designed to help users track their energy (electricity) and gas consumption. It provides an intuitive interface to input meter readings, calculate usage and costs over time, visualize trends with charts, and manage data through local browser storage and file export/import.

The goal of Viosimos is to empower individuals to better understand their consumption patterns, identify areas for savings, and contribute to a more sustainable lifestyle by being mindful of their energy and gas usage.

---

## ✨ Features

- **Energy Consumption Tracking:** Record electricity meter readings, tariffs, and dates.
- **Gas Consumption Tracking:** Record gas meter readings, tariffs, and dates.
- **Automated Calculations:** Automatically calculates usage (kWh/m³) and cost (€) between consecutive entries.
- **Data Visualization:** Interactive line charts powered by [Chart.js](https://www.chartjs.org/) to display usage and cost trends over time.
- **Summary Statistics:** Displays total days tracked and total accumulated cost.
- **Data Persistence:** Stores your entries securely in your browser's local storage using [LocalForage](https://localforage.github.io/localForage/) for asynchronous and robust data management.
- **CSV Export:** Export your energy or gas data to CSV for spreadsheet analysis.
- **JSON Export/Import:** Backup your data to JSON or restore it from a previous export, allowing easy data transfer or recovery.
- **Responsive Design:** Optimized for desktop, tablet, and mobile devices.
- **Simple & Intuitive UI:** Clean and easy-to-use interface for quick data entry and review.

---

## 🚀 Getting Started

To run **Viosimos** locally, simply clone this repository and open the `index.html` file in your preferred web browser.

### Steps:

```bash
git clone https://github.com/theo79/viosimos.git
cd viosimos

