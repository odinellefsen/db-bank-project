# DB BANK PROJECT

## Getting Started

### 1. Database Setup

Start the Docker container containing the Postgres database:

```bash
docker compose up -d
```

Connection details:

- String: `postgresql://db_bank_user:app_password_1234@localhost:5432/db_bank_project`

### 2. Application Setup

Install dependencies and run the development server:

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the bank interface.
