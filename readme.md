# HR System API

Backend API untuk **Internal HR Management System**.

Project ini dibangun sebagai bagian dari proses upgrade dari **Frontend Developer ke Full-Stack**, dengan fokus pada pembuatan sistem internal yang realistis dan sering ditemui di dunia kerja.

Use case saat ini adalah membantu karyawan dan HR dalam mengelola data karyawan dan proses cuti secara terpusat melalui API.

## Notion Bisnis flow
https://www.notion.so/Project-full-stack-v1-2e0802079820806394f6cc9b257b323a

## 🎯 Project Context

Sebagai karyawan, sering muncul pertanyaan sederhana seperti:
- sisa cuti berapa?
- status pengajuan cuti?
- siapa yang approve?

Project ini mencoba menjawab kebutuhan tersebut dengan membangun **HR System end-to-end**, yang nantinya akan digunakan oleh:
- **Web Admin (HR / Manager)**
- **Mobile App (Employee)**

Repository ini fokus pada **Backend API** sebagai pusat data dan business logic.

---

## 🧩 Scope (v1)

Fokus awal project ini adalah membangun fondasi backend yang solid.

Planned features:
- Authentication & role-based access (HR, Manager, Employee)
- Employee management
- Leave (cuti) management
- Leave approval workflow
- Leave balance calculation
- Audit log (basic)

---

## 🛠 Tech Stack

- **Node.js**
- **Express.js**
- **PostgreSQL** (planned)
- **JWT Authentication** (planned)

Project ini sengaja menggunakan **JavaScript (tanpa TypeScript)** di awal untuk fokus ke arsitektur dan flow backend terlebih dahulu.

---

## 🚀 Getting Started

### Prerequisites
- Node.js 20 >=

### Installation
```bash
git clone <repo-url>
cd hr-system-api
npm install
```

### Environment Variables
Buat file `.env` dengan mengikuti `.env.example`
```bash
cp .env.example .env
```
Run Development Server
```bash
npm run dev
```
Health Check
```bash
/api/health
```
