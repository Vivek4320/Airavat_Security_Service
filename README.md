# AIRAVAT Security Service

> **Your Security, Our Priority**

AIRAVAT Security Service is a professional security service website built to present security solutions, manage customer inquiries, showcase projects, and provide an administrative dashboard for managing website content.

The website is designed for AIRAVAT Security Service with a focus on professional presentation, responsive user experience, service inquiries, career inquiries, and secure administration.

## 🌐 Website

**Live Website:** https://airavatsecurity.in

## ✨ Features

### Public Website
- Professional AIRAVAT Security Service landing page
- Responsive navigation for desktop and mobile
- Hero section with service-focused call-to-action
- About and company information sections
- Security services presentation
- Client showcase / client logo carousel
- Projects portfolio with individual project pages
- Career page for career-related inquiries
- Contact and service inquiry form
- Success and inquiry detail pages
- Smooth scrolling and animated UI interactions
- Responsive and accessible interface
- SEO metadata, Open Graph metadata, sitemap, robots configuration, and structured data

### Inquiry Management
Customers can submit service or career inquiries through the website.

Each inquiry stores:
- Name
- Email
- Phone
- Inquiry type
- Message
- Status
- Created and updated timestamps

Inquiry statuses include:
- Pending
- Reviewed
- Completed

### Project Management
The website includes a project management system for administrators.

Administrators can:
- View projects
- Create new projects
- Edit existing projects
- Delete projects
- Manage project titles, slugs, dates, achievements, content, thumbnails, and project numbers
- Display project details through public project pages

### Admin Dashboard
The protected admin area provides:
- Dashboard statistics
- Recent inquiries
- Inquiry filtering and management
- Project management
- Project creation and editing
- Project deletion
- Admin authentication and logout

## 🛡️ Security Services

AIRAVAT Security Service presents professional security solutions including security guards, trained personnel, CCTV operators, and modern security equipment. The website is intended to support security service requirements across Gujarat.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Next.js 16 | Full-stack React framework |
| React 19 | User interface |
| TypeScript | Type-safe development |
| Tailwind CSS 4 | Styling and responsive UI |
| Framer Motion | Animations and interactions |
| Prisma | Database ORM |
| PostgreSQL | Database |
| bcryptjs | Password hashing |
| Zod | Data validation |
| Lucide React | UI icons |
| React Icons | Brand and interface icons |
| React Hot Toast | User notifications |

## 📁 Project Structure

```
Airavat_Security_Service/
├── api/
│   └── projects/
├── app/
│   ├── (auth)/
│   │   └── admin/login/
│   ├── admin/
│   │   ├── inquiries/
│   │   └── projects/
│   ├── api/
│   │   ├── auth/
│   │   ├── inquiries/
│   │   └── projects/
│   ├── career/
│   ├── components/
│   ├── inquiry/
│   ├── projects/
│   └── page.tsx
├── lib/
│   ├── auth.ts
│   ├── prisma.ts
│   └── utils.ts
├── prisma/
│   └── schema.prisma
├── public/
│   ├── logos
│   ├── security equipment images
│   └── website assets
├── scripts/
│   └── create-admin.ts
├── types/
├── next.config.ts
├── package.json
└── tsconfig.json
```

## 🗄️ Database

The application uses **PostgreSQL** with **Prisma ORM**.

The database contains models for:

- **Project** — stores public project information and portfolio content.
- **Inquiry** — stores service and career inquiries with their status.
- **Admin** — stores administrator credentials and account information.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Vivek4320/Airavat_Security_Service.git
cd Airavat_Security_Service
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env` file and configure the required database connection:

```env
DATABASE_URL="your-postgresql-database-url"
NEXT_PUBLIC_BASE_URL="https://airavatsecurity.in"
```

### 4. Generate Prisma Client

```bash
npm run db:generate
```

### 5. Push the database schema

```bash
npm run db:push
```

### 6. Create an admin account

```bash
npm run create-admin
```

### 7. Start the development server

```bash
npm run dev
```

Open **http://localhost:3000** in your browser.

## 📦 Production Build

Build the application:

```bash
npm run build
```

Start the production server:

```bash
npm start
```

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start the development server |
| `npm run build` | Create a production build |
| `npm start` | Start the production server |
| `npm run lint` | Run ESLint |
| `npm run create-admin` | Create an administrator account |
| `npm run db:generate` | Generate Prisma Client |
| `npm run db:push` | Push Prisma schema to the database |
| `npm run db:migrate` | Run Prisma database migrations |

## 📱 Responsive Design

The website is built to work across:
- Desktop
- Laptop
- Tablet
- Mobile devices

The navigation and major interface sections adapt for smaller screens while maintaining the core website experience.

## 🔐 Admin Access

Administrative functionality is separated from the public website and includes protected pages for managing:

- Dashboard statistics
- Customer inquiries
- Career inquiries
- Security service inquiries
- Projects and project content

## 🎯 Project Goal

The goal of the AIRAVAT Security Service website is to provide a modern digital presence for a professional security company while making it easier for customers to explore services, view completed projects, submit inquiries, and connect with the organization.

---

**AIRAVAT Security Service**  
*Your Security, Our Priority*
