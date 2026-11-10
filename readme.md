# ⚡ MeterMonitor
### Smart Electricity Monitoring & Billing Dashboard

<p align="center">
  **Monitor. Analyze. Calculate. Save Energy.**
</p>

MeterMonitor is a web-based electricity monitoring and billing dashboard designed to help homeowners track their electricity consumption and help utility billing teams manage meter readings and estimated electricity bills.

---

## 📌 About the Project

MeterMonitor is a one-month On-the-Job Training (OJT) project focused on simplifying electricity consumption monitoring and estimated billing.

The application aims to provide users with a centralized dashboard where they can view electricity consumption summaries, analyze usage patterns, manage meter readings, and calculate estimated electricity bills.

The project uses sample customer and meter data to demonstrate how a smart meter analytics and billing system can work through a responsive web interface.

## 🎯 Project Objectives

- Monitor electricity consumption.
- Visualize daily and monthly electricity usage.
- Calculate estimated electricity bills automatically.
- Manage customer and meter information.
- Maintain billing records and history.
- Provide separate demo experiences for homeowners and utility billing teams.

## ✨ Key Features

| Feature | Description |
|---|---|
| 📊 Dashboard | View electricity consumption summaries and key statistics. |
| 📈 Consumption Analytics | Analyze daily and monthly electricity usage. |
| 🧮 Bill Calculator | Calculate estimated bills using meter readings and tariff rates. |
| 👥 Customer Management | Maintain customer records and associated meter information. |
| ⚡ Meter Readings | View and manage sample meter readings. |
| 🧾 Billing History | Access previously generated bills. |
| 💰 Tariff Settings | Manage electricity tariff configurations. |
| 👤 Demo Roles | Separate homeowner and utility billing team experiences. |
| 📱 Responsive UI | Access the dashboard on desktop and mobile devices. |

## 🛠️ Tech Stack

**Frontend**
- HTML5
- CSS3
- JavaScript
- Bootstrap 5

**Data Storage**
- Browser LocalStorage
- JSON sample data

**Development Tools**
- Git
- GitHub
- Visual Studio Code

**Optional Stretch Technologies**
- React
- Vite
- Chart.js
- Leaflet

## 🧮 Bill Calculation

MeterMonitor calculates estimated electricity bills using meter readings and configured tariff values.

**Basic Formula**

```text
Units Consumed = Current Reading - Previous Reading

Energy Charge = Units Consumed × Tariff Rate

Subtotal = Energy Charge + Fixed Charge

Tax = Subtotal × Tax Rate

Final Bill = Subtotal + Tax
```

**Calculation Example**

| Parameter | Value |
|---|---:|
| Previous Reading | 1200 |
| Current Reading | 1450 |
| Units Consumed | 250 |
| Tariff Rate | ₹6/unit |
| Energy Charge | ₹1,500 |
| Fixed Charge | ₹50 |
| Subtotal | ₹1,550 |
| Tax Rate | 5% |
| Tax Amount | ₹77.50 |
| **Estimated Bill** | **₹1,627.50** |

*Note: This is an illustrative calculation based on sample tariff values.*

## 🖥️ Application Modules

The planned application consists of the following modules:

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

## 🚀 Getting Started

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Navigate to the Project Directory

```bash
cd MeterMonitor
```

### 3. Open the Project

Open the `index.html` file in your browser.

Alternatively, use the **Live Server** extension in Visual Studio Code to run the project locally.

*Update these instructions if the project setup changes during development.*

## 📂 Project Structure

The following is the planned project structure:

```text
MeterMonitor/
│
├── index.html
│
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
```

*The actual folder structure may be updated as development progresses.*

## 📸 Screenshots

Screenshots of the application will be added here as development progresses.

| Dashboard | Consumption Analytics |
|---|---|
| Add dashboard screenshot here | Add analytics screenshot here |

| Bill Calculator | Billing History |
|---|---|
| Add calculator screenshot here | Add billing history screenshot here |

## 📋 Project Progress

Development progress will be updated throughout the OJT project.

- [ ] Project setup and initial structure
- [ ] Dashboard development
- [ ] Consumption analytics
- [ ] Bill calculator
- [ ] Customer and meter management
- [ ] Billing history
- [ ] Tariff settings
- [ ] Data persistence
- [ ] Testing and validation
- [ ] Responsive UI improvements
- [ ] Final deployment

## 🔮 Future Enhancements

- Advanced consumption analytics.
- Month-on-month usage comparison.
- Slab-based tariff calculations.
- CSV and PDF data export.
- Electricity consumption forecasting.
- Interactive maps using sample meter locations.
- React-based frontend architecture.

## ⚠️ Project Scope & Limitations

- The application uses sample customer and meter data.
- It does not connect to real smart meters or IoT devices.
- It does not integrate with actual electricity utility APIs.
- Bill calculations are estimates based on configured tariff values.
- It does not process real payments.
- It is a demonstration project, not a production utility billing system.

## 🎓 Project Information

| Detail | Information |
|---|---|
| Project Name | MeterMonitor |
| Project ID | PST_PD_022 |
| Track | Level 3 – Stretch |
| Duration | 4 Weeks |
| Project Type | On-the-Job Training (OJT) |
| Domain | Frontend Development & Smart Utility Analytics |

## 👨‍💻 Contributors

- **Shivanshu Kumar**
- **Ankita Maurya**

## 🤝 Contributions

This project is being developed collaboratively. Suggestions, feedback, and improvements are welcome.

## 📄 License

License details will be added if the project is released under an open-source license.

---

<p align="center">

  **⚡ MeterMonitor**

  *Making Electricity Consumption Easier to Understand.*

</p>
