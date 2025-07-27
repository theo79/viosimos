<p align="center">
  <img src="viosimos.png" alt="Viosimos Logo" width="150" />
</p>
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

viosimos/
├── index.html        # Main landing page with navigation
├── energy.html       # Electricity consumption tracking page
├── gas.html          # Gas consumption tracking page
├── style.css         # Global styles and responsive design
├── viosimos.png      # Application logo
├── license.txt       # License file (CC BY-NC 4.0)
└── README.md         # This file



Technologies Used

    HTML5 – Structure and content of the web pages

    CSS3 – Styling and responsive layout

    JavaScript (ES6+) – Interactive logic and data handling

    Chart.js – Interactive charting library

    LocalForage – Asynchronous client-side storage abstraction

💡 Future Improvements

    User Authentication and cloud data storage for multi-device sync and backup

    Monthly and annual consumption and cost reports

    Cost projections based on historical data

    Notifications or reminders for meter readings

    Multi-currency support for broader audience

    Theming options (light/dark mode, custom colors)

📄 License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0).
See license.txt for full details.

👤 Author
Theocharis Anastopoulos © 2025

🖼️ Screenshots
<img src="screenshot1.png" alt="Screenshot 1" width="200" style="margin-right:10px;" />
<img src="screenshot2.png" alt="Screenshot 2" width="200" style="margin-right:10px;" />
<img src="screenshot3.png" alt="Screenshot 3" width="200" style="margin-right:10px;" />
<img src="screenshot4.png" alt="Screenshot 4" width="200" /> </p>

Thank you for using Viosimos — making energy and gas consumption sustainable, one meter reading at a time!

