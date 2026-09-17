# Employee Management System

A system for managing employee records, including onboarding, roles, departments, attendance, and payroll information.

> Frontend is under active development; backend is not yet implemented.

## Features

- Admin and Employee login portals
- Dashboard overview
- Employee records management
- Attendance tracking
- Leave management
- Payslips, including a printable payslip view
- Settings

## Tech Stack

- **Frontend:** React 19 + Vite, React Router, Tailwind CSS, Lucide icons, React Hot Toast
- **Backend:** _TBD — not yet implemented_
- **Database:** _TBD — not yet implemented_

## Getting Started

### Prerequisites

- Node.js (LTS recommended) and npm

### Installation

```bash
# clone the repository
git clone <repo-url>
cd employeeManagmentSystem/client

# install dependencies
npm install
```

### Running the project

```bash
# from the client/ directory
npm run dev       # start the dev server
npm run build     # production build
npm run preview   # preview the production build
npm run lint      # run eslint
```

## Project Structure

```
employeeManagmentSystem/
├── README.md
└── client/                  # React frontend
    ├── public/
    └── src/
        ├── assets/
        ├── components/      # LoginForm, LoginLeftSide, Sidebar
        ├── pages/           # Dashboard, Employees, Attendance, Leave,
        │                    # Payslips, PrintPayslip, Settings, LoginLanding, Layout
        ├── App.jsx          # routes
        └── main.jsx
```

## Contributing

Contributions are welcome. Please open an issue or submit a pull request describing your changes.

## License

_Specify a license (e.g. MIT) or mark as private/proprietary._

