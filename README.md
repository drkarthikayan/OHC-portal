# OHC Portal — Occupational Health Centre Management System

A comprehensive, single-file web application for managing employee occupational health in a manufacturing/industrial facility.

## Features

### 📊 Dashboard
- Live KPI cards (OPD today, pharmacy alerts, active injuries, campaigns)
- Canvas-based trend charts
- Customisable widget layout

### 👤 Employee Management
- Employee registration & search
- My OHC Profile (per-employee health history)
- Bulk import via Excel
- Health Status Board

### 🩺 Medical Examinations
- Pre-Employment Medical Register
- **Periodic Medical Examination (PME)** — 65+ parameters, Excel import, year-on-year trend comparison with clinical threshold flagging
- Vitals Monitor

### 🏥 Clinical
- **Daily OPD Register** — comprehensive history, vitals, smart medicine search with auto-quantity (days × timing), pharmacy verification workflow
- **Injury Register** — ILO C161 / OSHA 300 compliant, full edit/delete, month-based export
- Hospital Tracker — hospitalisation management with discharge planning
- Health Tracker — chronic disease management (13 conditions + custom), overdue review alerts
- Medical Certificates — saved certificate list, half-A4 print format

### 💊 Pharmacy
- Stock Management with FIFO batch tracking
- Bulk upload (8-column Excel)
- Dispensary Log
- Biomedical Waste Register

### 🏭 Field Activities *(New in v6)*
- **Field Rounds** — Shop Floor Visit, Creche Visit, Water Sample Collection (type-specific forms)
- **Audits** — Canteen Hygiene, Canteen Staff Grooming, Workplace Safety (auto-scored checklists, 10 items each)
- **Vaccination Register** — Factories Act compliant (Hep B, TT, Typhoid, etc.), auto dose scheduling, due date tracking
- **Work Permits** — Height Work Permit with integrated Medical Fitness Assessment checklist
- **Health Education** — Health Talks, Induction Classes, Workshops with attendance tracking

### ⚙️ Administration
- User Management (role-based: Doctor, Nurse, Pharmacist, Admin)
- Audit Log (last 3000 actions)
- Configurable settings

## Technical

- **Single HTML file** — no build step, no server required
- **LocalStorage persistence** — data survives page refresh
- **Excel export** — all modules export via SheetJS (XLSX)
- **Print-ready** — Medical Certificates print as half-A4
- Compliant with **ILO C161**, **OSHA 300**, **Factories Act (India)**

## Usage

Simply open `index.html` in a modern browser. No installation needed.

Default login: `admin@company.com` / `Admin@123`

---

*Built for internal use at industrial OHC facilities.*
