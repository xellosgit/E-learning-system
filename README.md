# Learning Management System

This project is a comprehensive **Learning Management System (LMS)** designed to facilitate online education. It provides a structured environment for managing courses, tracking student progress, and enabling interactive learning experiences.

## Features
- **User Authentication** – Secure login and registration.
- **Course Management** – Create, edit, and manage courses and materials.
- **Progress Tracking** – Monitor user engagement and completion status.
- **Interactive Components** – Quizzes and assignments for enhanced learning.
- **Responsive Design** – Fully functional across devices.

## Project Structure
The project is organized into two primary sections:

- **Client** – Frontend of the application, developed using **Next.js** for server-side rendering and static site generation.
- **Server** – Backend services handling API requests, user authentication, and data management.

### Key Files and Directories
- **client/** – Contains all frontend-related files.
  - `.env.example` – Environment configuration example.
  - `next.config.js` – Next.js configuration.
  - `package.json` – Project dependencies and scripts.
- **server/** – (Expected) Backend API and database configurations.
- `.gitignore` – Files and directories to exclude from version control.

## Technologies Used
- **Frontend**: Next.js, Redux Toolkit, Tailwind CSS, Shadcn, TypeScript, Framer Motion, React Hook Form, Zod, and Stripe.
- **Backend**: Node.js, Express.js, Docker, AWS Lambda, API Gateway, DynamoDB, S3, and CloudFront.
- **Authentication**: Simplified with Clerk.
- **Hosting**: Vercel for the frontend.

## Usage
- **Administrators** can manage courses and track user progress.
- **Students** can enroll in courses, take quizzes, and monitor their performance.

