# TaskFlow Manager

A modern, full-stack task management application built with React, Vite, Express, and Tailwind CSS.

## Features

- **Dashboard**: Overview of task statistics and critical focus items.
- **Task Management**: Create, edit, delete, and filter tasks.
- **Authentication**: Secure login and session management.
- **Modern UI**: Bento Grid layout, glassmorphism effects, and smooth animations.

## Demo Screenshots

Here is a look at the modern UI of TaskFlow Manager:

### 1. Modern Login Experience
A sleek, split-screen login page with dynamic gradients and glassmorphism effects.
![Login Page](https://picsum.photos/seed/taskflow-login/1200/600?blur=1)

### 2. Bento Grid Dashboard
An intuitive overview of your productivity with real-time statistics and critical focus items.
![Dashboard](https://picsum.photos/seed/taskflow-dashboard/1200/600)

### 3. Task Management
A clean and organized grid layout for managing your daily tasks with ease.
![Tasks List](https://picsum.photos/seed/taskflow-tasks/1200/600)

## Tech Stack

- **Frontend**: React 19, Vite, Tailwind CSS, Motion (framer-motion).
- **Backend**: Express.js.
- **Icons**: Lucide React.
- **Language**: TypeScript.

## Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v18 or higher)
- [npm](https://www.npmjs.com/)

## Getting Started

### 1. Clone the Repository

```bash
git clone <repository-url>
cd taskflow-manager
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Environment Configuration

Create a `.env` file in the root directory and add the necessary environment variables. You can use `.env.example` as a template.

```bash
cp .env.example .env
```

### 4. Run the Development Server

Start the application in development mode:

```bash
npm run dev
```

The application will be available at `http://localhost:3000`.

### 5. Build for Production

To create a production-ready build:

```bash
npm run build
```

### 6. Start Production Server

After building, start the production server:

```bash
npm start
```

## VS Code Setup

For the best development experience, we recommend using [Visual Studio Code](https://code.visualstudio.com/) with the following extensions:

- **ESLint**: For code linting and consistency.
- **Prettier**: For automatic code formatting.
- **Tailwind CSS IntelliSense**: For utility class autocompletion.
- **TypeScript Vue Plugin (Volar)**: If applicable, or standard TypeScript support.

### Recommended Settings

Create or update `.vscode/settings.json`:

```json
{
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit"
  },
  "tailwindCSS.emmetCompletions": true
}
```

## Project Structure

- `src/`: Frontend source code.
  - `components/`: Reusable UI components.
  - `context/`: React Context providers (Auth, etc.).
  - `hooks/`: Custom React hooks.
  - `pages/`: Page-level components.
  - `types.ts`: TypeScript interfaces and types.
- `server.ts`: Express server entry point.
- `vite.config.ts`: Vite configuration.
- `tailwind.config.js`: Tailwind CSS configuration.

## License

This project is licensed under the MIT License.
