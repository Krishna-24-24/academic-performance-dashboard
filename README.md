# 📊 EduAnalytic — Academic Performance Dashboard

> A React-based interactive dashboard that transforms raw academic data into clear, meaningful insights for students, faculty, and department heads.

![React](https://img.shields.io/badge/React-18+-61DAFB?style=flat&logo=react)
![Vite](https://img.shields.io/badge/Vite-7.x-646CFF?style=flat&logo=vite)
![Recharts](https://img.shields.io/badge/Recharts-2.x-22B5BF?style=flat)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

---

## 🌐 Live Demo

**[https://Krishna-24-24.github.io/academic-performance-dashboard/](https://Krishna-24-24.github.io/academic-performance-dashboard/)**

---

## 📌 About the Project

**EduAnalytic** is a web-based analytical dashboard built for **B.Tech CSE — Semester IV** at Vellore Institute of Technology. Instead of looking at plain mark sheets and raw numbers, the system takes structured JSON result data and turns it into interactive visualizations — bar charts, pie charts, radar charts, and scatter plots.

It calculates key academic metrics such as:
- Class average and pass percentage
- Subject-wise performance and grade distribution
- Individual student rankings and attendance correlation
- At-risk student identification and subject health scoring

---

## 🧭 Dashboard Views

### 🏠 Overview
A high-level summary of the entire class including:
- Class average, distinction count, at-risk count, and full pass rate
- Subject-wise average score bar chart
- Class performance radar chart
- Score distribution and grade distribution charts
- Subject pass rate & averages with HOD insights panel

### 👨‍🎓 Student Dashboard
Individual performance intelligence for each student:
- Search and filter students by name or roll number
- Sort by rank, name, or attendance
- Subject-wise marks with visual progress bars and grade pills
- Subject radar chart and comparison against class average
- Attendance vs. Performance scatter plot
- Full class rank table (top 10)

### 👩‍🏫 Faculty Dashboard (Subject Deep Dive)
Granular subject-level analysis for teachers:
- Per-subject score distribution and grade breakdown
- Key metrics: average score, highest, lowest, pass rate
- All-subjects min/avg/max comparison chart
- Subject cards with pass/fail/distinction counts

### 🏛️ HOD Dashboard (Department Analytics)
Strategic overview for department heads:
- Executive summary KPIs
- Subject performance trend (avg score & pass rate line chart)
- At-risk students table (below 50%)
- Subject health scorecard (Good / Average / Poor)
- Class rank progression area chart

---

## 📸 Screenshots

| Overview | Student Dashboard |
|----------|------------------|
| Class avg, radar chart, grade distribution | Individual profiles, scatter plot, rank table |

| Faculty View | HOD View |
|-------------|---------|
| Subject deep dive, score & grade breakdown | Department analytics, subject health scorecard |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **React 18+** | UI framework |
| **Vite** | Build tool & dev server |
| **Recharts** | Charts (Bar, Radar, Scatter, Line, Area) |
| **IBM Plex Sans / Mono** | Typography |
| **Playfair Display** | Display headings |
| **GitHub Pages** | Deployment |

---

## 📂 Project Structure

```
academic-performance-dashboard/
├── public/
│   └── index.html
├── src/
│   ├── App.jsx        # Main component with all dashboard views
│   ├── App.css        # Global styles and design tokens
│   └── main.jsx       # React entry point
├── vite.config.js
├── package.json
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js v18+
- npm v9+

### Installation

```bash
# Clone the repository
git clone https://github.com/Krishna-24-24/academic-performance-dashboard.git

# Navigate into the project
cd academic-performance-dashboard

# Install dependencies
npm install

# Start development server
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) to view it in your browser.

---

## 📦 Build & Deploy

```bash
# Build for production
npm run build

# Deploy to GitHub Pages
npm run deploy
```

The live site will be available at:
**`https://Krishna-24-24.github.io/academic-performance-dashboard/`**

---

## 📊 Dataset

The dashboard uses a hardcoded JSON dataset embedded in `App.jsx` representing:

- **Institution:** Vellore Institute of Technology
- **Department:** Computer Science & Engineering
- **Class:** B.Tech CSE — Semester IV (2025–26)
- **Students:** 22 students with marks, attendance, and roll numbers
- **Subjects:** DAA, DBMS, OS, CN, SE, TOC (6 subjects, max marks: 100, pass marks: 40)

---

## ✨ Key Features

- ✅ Zero backend — fully client-side with JSON data
- ✅ Four role-based views: Overview, Student, Faculty, HOD
- ✅ Search, sort, and filter students in real time
- ✅ Interactive charts with custom tooltips
- ✅ Grade color coding (S → F) with visual pills
- ✅ Responsive and clean UI with warm paper-tone design
- ✅ Attendance vs. performance correlation scatter plot
- ✅ Subject health scoring and at-risk student detection

---

## 👨‍💻 Author

**Krishna**
Registration No: 24BCE0592
Course: Web Programming (BCSE203E)
Vellore Institute of Technology

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
