⚡ MeterMonitor — Smart Electricity Monitoring & Billing Dashboard

<p align="center">
  <strong>Monitor. Analyze. Calculate. Save Energy.</strong>
</p><p align="center">
  A web-based electricity monitoring and billing dashboard designed to help homeowners track their electricity consumption and help utility billing teams manage meter readings and estimated bills.
</p>---

📌 About the Project

MeterMonitor is a smart electricity monitoring and automated billing dashboard developed as part of a one-month On-the-Job Training (OJT) project.

The application aims to simplify electricity consumption tracking by providing consumption summaries, visual analytics, meter reading management, and automated electricity bill calculations.

The project uses sample data to demonstrate how a smart meter analytics and billing system can work through a responsive web interface.

🎯 Project Objectives

- Monitor electricity consumption.
- Visualize daily and monthly usage patterns.
- Calculate estimated electricity bills automatically.
- Manage customer and meter information.
- Maintain billing history.
- Provide separate demo experiences for homeowners and utility billing teams.

✨ Key Features — MVP Scope

Feature| Description
📊 Dashboard| View electricity consumption summaries and key statistics.
📈 Consumption Analytics| Analyze daily and monthly electricity usage.
🧮 Bill Calculator| Calculate estimated bills using meter readings and tariff rates.
👥 Customer Management| Maintain customer records and associated meter information.
⚡ Meter Readings| View and manage sample meter readings.
🧾 Billing History| Access previously generated bills.
💰 Tariff Settings| Manage electricity tariff configurations.
👤 Demo Roles| Separate homeowner and utility billing team experiences.
📱 Responsive UI| Access the dashboard on desktop and mobile devices.

🛠️ Tech Stack

Frontend

- HTML5
- CSS3
- JavaScript
- Bootstrap 5

Data Storage

- Browser LocalStorage
- JSON sample data

Development Tools

- Git
- GitHub
- VS Code

React + Vite and other advanced technologies may be explored as optional stretch goals.

🧮 Bill Calculation

MeterMonitor uses meter readings and tariff configurations to estimate electricity bills.

Basic calculation:

Units Consumed = Current Reading - Previous Reading

Energy Charge = Units Consumed × Tariff Rate

Subtotal = Energy Charge + Fixed Charge

Tax = Subtotal × Tax Rate

Final Bill = Subtotal + Tax

Example:

Parameter| Value
Previous Reading| 1200
Current Reading| 1450
Units Consumed| 250
Tariff Rate| ₹6/unit
Fixed Charge| ₹50
Tax Rate| 5%
Estimated Bill| ₹1,627.50

🖥️ Application Modules

1. Home / Landing Page
2. Dashboard
3. Consumption Analytics
4. Bill Calculator
5. Bill Details
6. Billing History
7. Customer Management
8. Meter Readings
9. Tariff Settings
10. About / Help

🚀 Getting Started

Follow these steps to run the project locally.

1. Clone the repository

git clone YOUR_REPOSITORY_URL

2. Navigate to the project folder

cd MeterMonitor

3. Open the project

Open "index.html" in your browser, or use the VS Code Live Server extension.

If the project structure or setup changes during development, update these instructions accordingly.

📂 Project Structure

The planned project structure:

MeterMonitor/
│
├── index.html
├── css/
│   └── style.css
│
├── js/
│   ├── app.js
│   ├── dashboard.js
│   ├── billing.js
│   └── analytics.js
│
├── assets/
│   └── images/
│
├── data/
│   └── sample-data.json
│
└── README.md

📸 Screenshots

Screenshots of the application will be added here as development progresses.

Add your dashboard screenshot here

🔮 Future Enhancements

- Advanced consumption analytics.
- Month-on-month usage comparison.
- Slab-based tariff calculations.
- Data export functionality.
- Consumption forecasting.
- Interactive maps using sample meter locations.
- React-based frontend architecture.

⚠️ Project Scope & Limitations

- This project uses sample meter and customer data.
- It does not connect to real smart meters or IoT devices.
- It does not integrate with actual electricity utility APIs.
- Bill calculations are estimates based on configured tariff values.
- It does not process real payments.

🎓 Project Information

Detail| Information
Project Name| MeterMonitor
Project ID| PST_PD_022
Track| Level 3 — Stretch
Duration| 4 Weeks
Project Type| OJT Project
Domain| Frontend Development & Smart Utility Analytics

👨‍💻 Contributors

- Shivanshu Kumar
- Ankita Maurya

🤝 Contributions

This project is being developed collaboratively. Contributions, suggestions, and feedback are welcome.

📄 License

License details will be added if the project is released under an open-source license.

---

<p align="center">
  <strong>MeterMonitor — Making Electricity Consumption Easier to Understand.</strong>
</p>
