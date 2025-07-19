# TaskForge

TaskForge is a powerful, modern project management tool inspired by Jira. It helps teams organize, track, and manage their work efficiently with an intuitive interface and robust features for both agile and traditional workflows.

## Features

- **Intuitive Kanban Boards:** Visualize your workflow and optimize team productivity.
- **Sprint Planning:** Plan and manage sprints for agile teams.
- **Comprehensive Reporting:** Gain insights into your team's performance with detailed, customizable reports and analytics.
- **Multi-Project Management:** Manage multiple projects and switch between them easily.
- **Customizable Workflows:** Adapt TaskForge to your team's unique processes.
- **Team Collaboration:** Assign issues, track progress, and collaborate in real-time.
- **User Authentication & Organizations:** Secure sign-in and organization management powered by Clerk.
- **Responsive UI:** Built with React, Next.js, and Tailwind CSS for a seamless experience on any device.

## Tech Stack

- **Frontend:** React, Next.js, Tailwind CSS
- **Backend:** Next.js API routes, Prisma ORM
- **Database:** PostgreSQL (configurable via Prisma)
- **Authentication:** Clerk
- **Drag & Drop:** @hello-pangea/dnd
- **Forms & Validation:** React Hook Form, Zod
- **Other:** Radix UI, Sonner (toasts), Embla Carousel

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- npm
- PostgreSQL database
- Git

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SuvransuSD/taskforge.git
   cd taskforge
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure environment variables:**
   - Copy `.env.example` to `.env` and fill in your database and Clerk credentials.

4. **Set up the database:**
   ```bash
   npx prisma migrate deploy
   ```

5. **Run the development server:**
   ```bash
   npm run dev
   ```

6. **Open your browser:**
   - Visit [http://localhost:3000](http://localhost:3000)

## Project Structure

- `/app` - Next.js app directory (pages, layouts, API routes)
- `/components` - Reusable UI components
- `/actions` - Server actions for projects, issues, organizations, sprints
- `/prisma` - Prisma schema and migrations
- `/data` - Static data (companies, FAQs, status)
- `/hooks` - Custom React hooks

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is managed by Suvransu Mishra.
