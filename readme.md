<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:0f3460&height=180&section=header&text=Resultify&fontSize=60&fontColor=58a6ff&animation=fadeIn&fontAlignY=40&desc=Student%20Result%20Viewing%20Platform&descAlignY=62&descSize=16&descColor=8b949e" width="100%"/>

<br/>

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Resultify-58a6ff?style=for-the-badge)](https://test-frontend-one-coral.vercel.app/)
&nbsp;
[![Made with React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
&nbsp;
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
&nbsp;
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

<br/>

> **A smart, dual-portal result management platform —**
> **officials upload in bulk, students access instantly.**

</div>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Usage](#-usage)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [Author](#-author)

---

## 🧠 Overview

**Resultify** is a clean and efficient result management platform built for educational institutions. It eliminates the chaos of manual result distribution by providing:

- 📁 **Officials** can upload student results in **bulk via CSV or Excel**
- 🔍 **Students** can instantly access their results using their **roll number**
- ⚡ Fast, responsive, and built for real institutional workflows

No login required for students — just enter a roll number and get results instantly.

---

## ✨ Features

### 👤 Student Portal
- 🔎 Search results by **roll number**
- 📊 View subject-wise marks, grades, and result status
- ⚡ Instant access — no registration needed
- 📱 Fully responsive on all devices

### 🏛️ Official Portal
- 📂 **Bulk upload** results via **CSV / Excel** file
- ✅ Data validation on upload (catches errors before saving)
- 📋 View and manage uploaded result records
- 🔐 Secure access for authorized personnel

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| ⚛️ Frontend | React + TypeScript |
| 🎨 Styling | Tailwind CSS + shadcn/ui |
| ⚡ Build Tool | Vite |
| 🌐 Deployment | Vercel |

---

## 🚀 Getting Started

### Prerequisites

Make sure you have **Node.js** and **npm** installed.
> Recommended: use [nvm](https://github.com/nvm-sh/nvm#installing-and-updating) to manage Node versions.

```bash
node -v   # v18+ recommended
npm -v
```

### Installation

```bash
# 1️⃣ Clone the repository
git clone https://github.com/Gaziwahab/resultify_frontend.git

# 2️⃣ Navigate into the project
cd resultify_frontend

# 3️⃣ Install dependencies
npm install

# 4️⃣ Start the development server
npm run dev
```

The app will be running at **http://localhost:5173** 🎉

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

---

## 📁 Project Structure

```
resultify_frontend/
├── public/                 # Static assets
├── src/
│   ├── components/         # Reusable UI components
│   │   ├── ui/             # shadcn/ui components
│   │   ├── StudentPortal/  # Student result lookup
│   │   └── OfficialPortal/ # Bulk upload interface
│   ├── pages/              # Route-level pages
│   ├── lib/                # Utility functions
│   ├── types/              # TypeScript type definitions
│   ├── App.tsx             # Root component
│   └── main.tsx            # Entry point
├── index.html
├── tailwind.config.ts
├── tsconfig.json
├── vite.config.ts
└── package.json
```

---

## 📖 Usage

### For Students
1. Visit the [live platform](https://test-frontend-one-coral.vercel.app/)
2. Enter your **Roll Number** in the search field
3. Instantly view your result 📊

### For Officials
1. Navigate to the **Official Portal**
2. Prepare your CSV/Excel file in the required format:

```
roll_number | student_name | subject | marks | total | grade
```

3. Upload the file — results are immediately accessible to students ✅

---

## 🤝 Contributing

Contributions are welcome! Here's how:

```bash
# 1. Fork the repository
# 2. Create your feature branch
git checkout -b feature/your-feature-name

# 3. Commit your changes
git commit -m "feat: add your feature"

# 4. Push to your branch
git push origin feature/your-feature-name

# 5. Open a Pull Request 🚀
```

Please keep PRs focused and well-described. Bug reports and feature suggestions via [Issues](https://github.com/Gaziwahab/resultify_frontend/issues) are always appreciated.

---

## 👤 Author

<div align="center">

**Gazi Wahab**
*Full Stack Developer · AI Systems Builder*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gazi-wahab/)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Gaziwahab)
&nbsp;
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gaziwahab58@gmail.com)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,100:1a1a2e&height=100&section=footer&text=Made%20with%20%E2%9D%A4%EF%B8%8F%20by%20Gazi%20Wahab&fontSize=13&fontColor=8b949e&animation=fadeIn&fontAlignY=65" width="100%"/>

</div>
