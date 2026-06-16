<div align="center">
  <img src="./Logo.png" alt="QueryHub Logo" width="160" />

  # QueryHub

  <b>Intelligent Multi-Database SQL Productivity Platform</b>

  <p>Generate, Validate, Optimize and Convert SQL Queries without memorizing syntax.</p>

  <p>
    🌍 <strong><a href="https://queryhub-web.vercel.app/">Official Website (Download)</a></strong> | 
    🖥️ <strong><a href="https://queryhub-sql.vercel.app/">Web Version</a></strong>
  </p>

  <!-- Badges -->
  <p>
    <a href="https://github.com/Rudra-Prasad-Nayak/QueryHub_DesktopApp/releases">
      <img src="https://img.shields.io/github/v/release/Rudra-Prasad-Nayak/QueryHub_DesktopApp?style=for-the-badge&color=blue" alt="Release" />
    </a>
    <a href="https://github.com/Rudra-Prasad-Nayak/QueryHub_DesktopApp/blob/main/LICENSE">
      <img src="https://img.shields.io/github/license/Rudra-Prasad-Nayak/QueryHub_DesktopApp?style=for-the-badge&color=green" alt="License" />
    </a>
    <a href="https://github.com/Rudra-Prasad-Nayak/QueryHub_DesktopApp/stargazers">
      <img src="https://img.shields.io/github/stars/Rudra-Prasad-Nayak/QueryHub_DesktopApp?style=for-the-badge&color=yellow" alt="Stars" />
    </a>
    <a href="https://github.com/Rudra-Prasad-Nayak/QueryHub_DesktopApp/issues">
      <img src="https://img.shields.io/github/issues/Rudra-Prasad-Nayak/QueryHub_DesktopApp?style=for-the-badge&color=orange" alt="Issues" />
    </a>
  </p>
</div>

<br />

## 📖 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Supported Databases](#-supported-databases)
- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [Development Setup](#-development-setup)
- [License](#-license)

---

## 🚀 Overview

**QueryHub** is a modern, offline-first desktop SQL productivity application built for developers, database engineers, students, analysts, and non-technical users who want to work with SQL faster and more efficiently.

Instead of manually remembering complex SQL syntax across multiple database systems, QueryHub provides a structured **no-code workflow** where users can generate advanced SQL queries through intuitive input forms. It also features validation, conversion, optimization, and formatting tools.

---

## ✨ Key Features

### 🧩 No-Code SQL Generation
Generate complex SQL queries simply by filling out intuitive forms. No need to memorize dialect-specific syntax.
- **DDL & DML Support**: `CREATE`, `ALTER`, `INSERT`, `UPDATE`, `DELETE`, `SELECT`, `MERGE`
- **Advanced Structures**: Indexes, Views, Materialized Views, Partitions, Subpartitions
- **Programmability**: Stored Procedures, Functions, Triggers
- **Control Commands**: TCL & DCL Commands
- **Schema Design**: Constraints & Relationships

### 🔄 Multi-Database Dialect Conversion
Seamlessly convert queries between different database systems with dialect-aware transformations.
- E.g., Oracle → MySQL, MySQL → PostgreSQL, SQL Server → Oracle.

### 🛡️ SQL Validation
Validate your SQL queries locally with robust, dialect-aware validation support before running them on your production database.

### ⚡ Query Optimization & Formatting
- **Analyze & Optimize**: Get suggestions for query improvements and index recommendations to enhance performance.
- **Formatter**: Beautify and format raw SQL queries into clean, readable code.

### 💾 Offline-First & Export
- **100% Offline**: Works completely independently as a native desktop app without requiring an internet connection.
- **Exporting**: Save and download generated queries directly as `.sql` files.

---

## 🗄️ Supported Databases

QueryHub supports query generation and conversion across major database dialects:

| Database | Supported |
| :--- | :---: |
| **PostgreSQL** | ✅ |
| **MySQL** | ✅ |
| **Oracle** | ✅ |
| **Microsoft SQL Server** | ✅ |

---

## 🛠️ Tech Stack

Built with modern web and desktop technologies:

- **Core & Desktop**: [Electron](https://www.electronjs.org/)
- **Frontend Framework**: [React 18](https://reactjs.org/) + [TypeScript](https://www.typescriptlang.org/)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **State Management**: [Zustand](https://github.com/pmndrs/zustand)
- **Visual Nodes**: [React Flow](https://reactflow.dev/)
- **Database Engine**: [SQL.js](https://sql.js.org/)

---

## 📦 Installation

### Windows Users
Download the latest pre-compiled installer from our Official Website or Releases page.

👉 **[Download from Official Website](https://queryhub-web.vercel.app/)** <br>
👉 **[Download Latest Release (GitHub)](https://github.com/Rudra-Prasad-Nayak/QueryHub_DesktopApp/releases)**

Once downloaded, simply run:
```bash
QueryHub Setup.exe
```

---

## 💻 Development Setup

If you wish to build QueryHub from source or contribute to the project:

### Prerequisites
- [Node.js](https://nodejs.org/) (v16 or higher)
- npm or yarn

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/Rudra-Prasad-Nayak/QueryHub_DesktopApp.git
   cd QueryHub_DesktopApp
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an issue for bugs, feature requests, or documentation improvements.

---

## 📄 License

This project is licensed under the terms of the **[MIT License](./LICENSE)**.

<div align="center">
  <br/>
  <sub>Built with ❤️ for better SQL productivity.</sub>
</div>