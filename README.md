# SchoolLama

SchoolLama is a comprehensive school management system built with modern web technologies. It provides a robust platform for managing students, teachers, classes, and various school activities.

## Features

-  User Management (Admin, Teachers, Students, Parents)
-  Class Management
-  Assignment Tracking
-  Performance Analytics
-  Event Calendar
-  Announcements
-  Attendance Management
-  Subject Management
-  Grade & Result Management
-  Lesson Scheduling

## Tech Stack

- **Framework**: Next.js 14
- **Language**: TypeScript
- **Database**: Prisma with PostgreSQL
- **Styling**: Tailwind CSS
- **Charts**: Recharts
- **Calendar**: React Big Calendar
- **Form Handling**: React Hook Form with Zod validation
- **Authentication**: Built-in auth system

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/your-username/SchoolLama.git
cd SchoolLama
```

2. Install dependencies:
```bash
npm install
```

3. Set up your database:
```bash
npx prisma migrate dev
```

4. Run the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
├── src/
│   ├── app/               # Next.js app directory
│   ├── components/        # Reusable components
│   └── lib/              # Utility functions and configurations
├── prisma/               # Database schema and migrations
├── public/              # Static assets
└── generated/           # Generated Prisma client
```

## Environment Variables

Create a `.env` file in the root directory and add the following:

```env
DATABASE_URL="your-database-connection-string"
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.