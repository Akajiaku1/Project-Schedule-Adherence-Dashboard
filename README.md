# 📊 Project Schedule Adherence Dashboard

A web-based dashboard to monitor and visualize project schedule performance, built with **Dash**, **Plotly**, and **Pandas**. This tool helps project managers track planned vs. actual durations, adherence rates, and task completion progress with interactive charts.

---

## 🚀 Features

- 📅 **Gantt Chart** for visualizing task timelines and delays
- 📊 **Bar Charts** comparing planned vs. actual task durations
- ✅ **Schedule Adherence Rate** summary
- 📈 **Progress Tracker** for task completion (0–100%)
- 🔍 **Phase Filter** to explore specific project stages
- 🖨️ Export via **browser print to PDF**

---

## 🗃️ Sample Dataset Format

`data/project_schedule.csv`:

```csv
Task,Start_Date,Planned_End_Date,Actual_End_Date,Progress,Phase
Requirement Gathering,2025-01-01,2025-01-10,2025-01-09,100,Initiation
Design,2025-01-11,2025-01-20,2025-01-23,100,Planning
Development,2025-01-21,2025-02-15,2025-02-18,80,Execution
Testing,2025-02-16,2025-02-28,2025-02-25,50,Execution
Deployment,2025-03-01,2025-03-05,2025-03-07,30,Closure

🛠️ Setup Instructions
1. Clone the Repository

git clone https://github.com/your-username/project-schedule-adherence-dashboard.git
cd project-schedule-adherence-dashboard

2. Install Dependencies

pip install dash plotly pandas dash-bootstrap-components

3. Run the App

python app.py

Visit http://127.0.0.1:8050 in your browser.
📦 Project Structure

project_schedule_adherence/
│
├── app.py                      # Main dashboard application
├── data/
│   └── project_schedule.csv    # Project schedule data file
├── assets/                     # Optional CSS or JS
│   └── custom.css
├── README.md                   # Project documentation

📤 Export Report

To export the dashboard as a PDF:

    Click the "🖨️ Export Report" button.

    Use your browser’s Print option.

    Select "Save as PDF" to export the current view.

🧩 Possible Extensions

    📡 Connect to live project management tools (e.g., Jira, Trello)

    🧠 Integrate prediction for task delays using machine learning

    🧾 Email scheduled PDF reports weekly

    🔐 Add user authentication and roles

    📊 Add pie charts for task status (e.g., delayed, completed)

👨‍💻 Author

Your Name
GitHub | LinkedIn
📄 License

MIT License – feel free to use, modify, and distribute.


---

Would you like me to:

- Create a GitHub repository structure with this?
- Add a badge for Heroku or Render deployment?
- Include test data for CI/CD or unit testing?

Let me know, and I’ll help you extend it.
