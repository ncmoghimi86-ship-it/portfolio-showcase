# 🏢 Kavir Motor HR Portal

**Enterprise Human Resources Management System**

---

## 📌 Overview

A comprehensive HR management platform built end-to-end for Kavir Motor Co. — designed, developed, and maintained solo. Handles the entire employee request lifecycle, from submission to HR validation, multi-level approval, and payment.

---

## ✨ Key Features

### 🔐 Permission-Based Access Control
- 47+ granular permissions across 16 modules
- Dynamic role creation from the UI — no code changes needed
- Real-time permission updates via 2-level cache invalidation

### 📋 Dynamic Request Builder
- 20+ field types (text, number, date, IBAN, national ID, dynamic tables, ...)
- Custom form builder with validation rules
- Configurable multi-level approval workflows

### 💳 Payment Tracking
- 4-state payment lifecycle (Pending / Scheduled / Paid / Cancelled)
- Three separate views for finance: Pending, Scheduled, Paid
- Real-time status updates across all dashboards

### 📊 Real-Time Dashboards
- Dynamic cards based on user permissions
- Auto-refresh every 30 seconds
- Version-based cache invalidation
- 6 chart types: status, type, department, trend, payments, role distribution

### 📢 Additional Modules
- Targeted announcements (all / departments / units / users)
- Dynamic surveys with aggregate + raw reports
- Birthday message system with custom HR messages
- Advanced report builder with dynamic columns
- File attachments with visibility control
- Excel export with multi-row merge

---

## 🛠️ Tech Stack

**Frontend:**
- React 19, TypeScript, Vite
- Tailwind CSS 4
- Zustand (state management)
- React Hook Form + Zod
- Recharts (charts)
- react-multi-date-picker (Persian calendar)

**Backend:**
- .NET 10, C#, ASP.NET Core
- Entity Framework Core 10
- SQL Server
- JWT + Refresh Token Rotation
- BCrypt password hashing
- ClosedXML (Excel export)

---

## 📸 Screenshots

### Dashboard
![Dashboard](./screenshots/01-dashboard.png)

### Request Detail with Approvals
![Request Detail](./screenshots/02-request-detail.png)

### Role & Permission Management
![Permissions](./screenshots/03-permissions.png)

### Dynamic Form Builder
![Form Builder](./screenshots/04-form-builder.png)

### Report Builder
![Reports](./screenshots/05-reports.png)

---

## 📈 Scale

- **18 controllers**, **20 entities**, **47 permissions**
- Built to support **1000+ users** with optimized caching
- Real-time updates across all user dashboards

---

## 📌 Note

Source code is **private** (proprietary to Kavir Motor Co.).

For questions or demo access, contact: nc.moghimi86@gmail.com
