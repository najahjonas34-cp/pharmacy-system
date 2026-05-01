# Pharmacy Management System

A complete offline-first pharmacy management system with web and desktop interfaces. Built for Admin and Employee management with MySQL backend.

## Features

- ✅ **Offline-First Architecture** - Works seamlessly without internet
- ✅ **Web & Desktop Apps** - React frontend with Electron desktop
- ✅ **Admin Interface** - Full management dashboard
- ✅ **Employee Interface** - POS and inventory access
- ✅ **MySQL Database** - Persistent storage with sync
- ✅ **Real-time Sync** - Auto-sync when connection returns
- ✅ **Multi-role Support** - Admin, Pharmacist, Cashier roles

## Project Structure

```
pharmacy-system/
├── backend/                 # Node.js/Express API
├── frontend/                # React web application
├── desktop/                 # Electron desktop app
├── database/                # MySQL schemas
├── docs/                    # Documentation
└── README.md
```

## Tech Stack

- **Frontend**: React 18 + Vite
- **Desktop**: Electron
- **Backend**: Node.js + Express
- **Database**: MySQL 8.0
- **Local Storage**: SQLite (offline)
- **Sync**: Custom offline-first sync engine

## Getting Started

### Prerequisites
- Node.js 16+
- MySQL 8.0+
- Git

### Installation

1. Clone the repository
```bash
git clone https://github.com/najahjonas34-cp/pharmacy-system.git
cd pharmacy-system
```

2. Install dependencies
```bash
# Backend
cd backend && npm install

# Frontend
cd ../frontend && npm install

# Desktop
cd ../desktop && npm install
```

3. Setup MySQL database
```bash
mysql -u root -p < database/schema.sql
```

4. Configure environment variables
```bash
# Copy .env.example to .env in backend, frontend, and desktop
cp backend/.env.example backend/.env
cp frontend/.env.example frontend/.env
cp desktop/.env.example desktop/.env
```

5. Start development servers
```bash
# Terminal 1 - Backend
cd backend && npm run dev

# Terminal 2 - Frontend
cd frontend && npm run dev

# Terminal 3 - Desktop
cd desktop && npm start
```

## API Endpoints

See `docs/API.md` for complete endpoint documentation.

## Database Schema

See `database/schema.sql` for database structure.

## Contributing

Please follow the contribution guidelines in `CONTRIBUTING.md`.

## License

MIT

## Support

For issues and questions, please create a GitHub issue.

---

**Built with ❤️ for pharmacy management**
