<div align="center">

# ✨ Vertex Web

### AI-Powered Study Plan Generator

[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-5-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![.NET](https://img.shields.io/badge/.NET-8-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)

*Study smarter, not harder*

[Demo](#demo) • [Features](#-features) • [Installation](#-installation) • [Contributing](#-contributing)

</div>

---

## 📖 About

**Vertex Web** is an intelligent study planning platform powered by AI to help students:

- 🎯 **Auto-generate study plans** tailored to your personal schedule
- 👥 **Distribute group tasks** fairly and efficiently  
- ⏰ **Track deadlines** with timely reminders
- 💡 **Get AI suggestions** to optimize your learning

> 🎓 Developed by FPT University students as part of the EXE101 course

---

## 🏗 Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                        Vertex Web                           │
├─────────────────────────────┬───────────────────────────────┤
│       🎨 Frontend           │         🔧 Backend            │
│                             │                               │
│  • React + Vite             │  • ASP.NET Core Web API      │
│  • State Management         │  • Entity Framework Core      │
│  • Axios HTTP Client        │  • OpenAI Integration         │
│  • TailwindCSS              │  • SQL Server                 │
│                             │                               │
│  📦 Repo: Vertex-web-FE     │  📦 Repo: Vertex-web-BE       │
└─────────────────────────────┴───────────────────────────────┘
```

| Repository | Description | Link |
|------------|-------------|------|
| **Frontend** | User interface, UI/UX handling | [Vertex-web-FE](https://github.com/KoiZ0-Khoa/Vertex-web-FE) |
| **Backend** | API, business logic, AI integration | [Vertex-web-BE](https://github.com/KoiZ0-Khoa/Vertex-web-BE) |

---

## ✨ Features

| Feature | Description | Status |
|---------|-------------|--------|
| 📅 Study Plan Generation | AI auto-generates schedules based on input | ✅ Done |
| 👥 Group Management | Distribute tasks among team members | 🚧 In Progress |
| 🔔 Deadline Notifications | Email/push notification reminders | 📋 Planned |
| 📊 Analytics Dashboard | Track learning progress | 📋 Planned |
| 🔐 Authentication | Login/Register with JWT | 🚧 In Progress |

---

## 🛠 Tech Stack

<table>
<tr>
<td align="center" width="50%">

### Frontend

![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/-TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Axios](https://img.shields.io/badge/-Axios-5A29E4?style=flat-square&logo=axios&logoColor=white)

</td>
<td align="center" width="50%">

### Backend

![.NET](https://img.shields.io/badge/-.NET%208-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/-C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![SQL Server](https://img.shields.io/badge/-SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Swagger](https://img.shields.io/badge/-Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)

</td>
</tr>
</table>

---

## 🚀 Installation

### Prerequisites

- **Node.js** >= 18.0
- **.NET SDK** >= 8.0
- **SQL Server** 2019+

### Frontend

```bash
# Clone repository
git clone https://github.com/KoiZ0-Khoa/Vertex-web-FE.git
cd Vertex-web-FE

# Install dependencies
npm install

# Create .env file
cp .env.example .env

# Run development server
npm run dev
```

### Backend

```bash
# Clone repository
git clone https://github.com/KoiZ0-Khoa/Vertex-web-BE.git
cd Vertex-web-BE

# Restore packages
dotnet restore

# Update connection string in appsettings.json

# Run migrations
dotnet ef database update

# Start server
dotnet run
```

### Environment Variables

```env
# Frontend (.env)
VITE_API_URL=http://localhost:5000/api

# Backend (appsettings.json)
# ConnectionStrings:DefaultConnection=<your-connection-string>
# OpenAI:ApiKey=<your-openai-key>
```

---

## 📁 Project Structure

```
vertex-web-fe/
├── 📂 src/
│   ├── 📂 components/     # Reusable UI components
│   ├── 📂 pages/          # Page components
│   ├── 📂 services/       # API service calls
│   ├── 📂 hooks/          # Custom React hooks
│   ├── 📂 utils/          # Helper functions
│   ├── 📂 assets/         # Images, fonts, etc.
│   └── 📄 App.jsx         # Root component
├── 📄 package.json
├── 📄 vite.config.js
└── 📄 README.md
```

---

## 🤝 Contributing

We welcome all contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for more details.

```bash
# Fork the repo
# Create a new branch
git checkout -b feature/amazing-feature

# Commit your changes
git commit -m "feat: add amazing feature"

# Push and create a Pull Request
git push origin feature/amazing-feature
```

---

## 👨‍💻 Team

<table>
<tr>
<td align="center">
<strong>KoiZ0-Khoa</strong><br/>
<sub>Project Lead</sub>
</td>
</tr>
</table>

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">

**⭐ If you find this useful, give us a star!**

Made with ❤️ by **FPT University Students**

</div>
