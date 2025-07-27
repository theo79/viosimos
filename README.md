Viosimos - Βιώσιμος (a Greek word for Sustainable)

Viosimos is a simple, client-side web application designed to help users track their energy (electricity) and gas consumption. It provides an intuitive interface to input meter readings, calculate usage and costs over time, visualize trends with charts, and manage data through local browser storage, CSV, and JSON export/import.

The goal of Viosimos is to empower individuals to better understand their consumption patterns, identify areas for savings, and contribute to a more sustainable lifestyle by being mindful of their energy and gas usage.
✨ Features

    Energy Consumption Tracking: Record electricity meter readings, tariffs, and dates.

    Gas Consumption Tracking: Record gas meter readings, tariffs, and dates.

    Automated Calculations: Automatically calculates usage (kWh/m³) and cost (€) between consecutive entries.

    Data Visualization: Interactive line charts powered by Chart.js to display usage and cost trends over time.

    Summary Statistics: Shows total days tracked and total accumulated cost.

    Data Persistence: Stores your entries securely in your browser's local storage using LocalForage for asynchronous and robust data management.

    CSV Export: Export your energy or gas data to a CSV file for spreadsheet analysis.

    JSON Export/Import: Manually back up your data to a JSON file or restore it from a previously exported JSON file, providing a simple way to transfer data or recover from browser cache clears.

    Responsive Design: Optimized for viewing and interaction on various devices (desktop, tablet, mobile).

    Simple & Intuitive UI: Clean and easy-to-use interface for quick data entry and review.

🚀 How to Use

To run Viosimos locally, simply clone this repository and open the index.html file in your web browser.

    Clone the repository:

    git clone https://github.com/theo79/viosimos.git

    Navigate to the project directory:

    cd viosimos

    Open index.html:
    Locate the index.html file in the cloned directory and open it with your preferred web browser (e.g., Chrome, Firefox, Edge).

Once opened, you can:

    Click "Energy" or "Gas" to navigate to the respective tracking pages.

    Enter your meter readings, tariffs, and dates.

    View your usage and cost in the table and charts.

    Use "Export CSV" to download your data as a spreadsheet.

    Use "Export Data (JSON)" to create a backup JSON file.

    Use "Import Data (JSON)" to load data from a JSON file (you can choose to replace or append).

📁 Project Structure

    index.html: The main landing page with navigation to Energy and Gas tracking.

    energy.html: Page for tracking electricity consumption.

    gas.html: Page for tracking gas consumption.

    style.css: Contains the global styles for the entire application.

    viosimos.png: The application's logo.

💻 Technologies Used

    HTML5: For structuring the web pages.

    CSS3: For styling and responsive design.

    JavaScript (ES6+): For all interactive logic and data handling.

    Chart.js: A popular JavaScript library for creating interactive charts.

    LocalForage: A wrapper for IndexedDB, WebSQL, and localStorage, providing asynchronous and robust client-side data storage.

💡 Future Improvements

    User Authentication: Implement a backend for user accounts to store data in a cloud database, allowing access across multiple devices and preventing data loss from browser clears.

    Monthly/Annual Reports: Add features to generate summarized reports for specific periods.

    Cost Projections: Implement basic forecasting based on past consumption.

    Notifications/Reminders: Set up reminders for regular meter readings.

    Multi-currency Support: Allow users to select their preferred currency.

    Theming: Add options for light/dark mode or custom color schemes.

©️ License & Author

Viosimos - Βιώσιμος<br />
Theocharis Anastopoulos © 2025
