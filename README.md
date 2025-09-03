# Overview

Fynally is a career development platform that serves as a life companion for students and professionals, guiding them through their career journey from student to successful employee. The application features a modern React frontend with a Node.js Express backend, providing resources, mentorship, and career programs including internships, job placement, and skill development bootcamps.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
- **Framework**: React 18 with TypeScript and Vite for development tooling
- **Routing**: Wouter for lightweight client-side routing
- **UI Components**: Shadcn/ui component library built on Radix UI primitives
- **Styling**: Tailwind CSS with custom design tokens and CSS variables
- **State Management**: TanStack Query for server state management
- **Forms**: React Hook Form with Zod validation for type-safe form handling

## Backend Architecture
- **Runtime**: Node.js with Express.js framework
- **Language**: TypeScript with ES modules
- **API Design**: RESTful API with JSON responses
- **Error Handling**: Centralized error middleware with proper HTTP status codes
- **Logging**: Custom request/response logging middleware for API endpoints

## Data Storage Solutions
- **Database**: PostgreSQL with Drizzle ORM for type-safe database operations
- **Connection**: Neon Database serverless PostgreSQL for cloud hosting
- **Schema Management**: Drizzle Kit for migrations and schema management
- **Development Storage**: In-memory storage implementation for development/testing
- **Data Validation**: Shared Zod schemas between frontend and backend for consistent validation

## Authentication and Authorization
- **Session Management**: Express sessions with PostgreSQL session store (connect-pg-simple)
- **Data Protection**: Form validation and sanitization on both client and server
- **CORS**: Configured for cross-origin requests with credentials support

## Project Structure
- **Monorepo Layout**: Shared schema definitions between client and server
- **Client Directory**: React application with organized components, pages, and utilities
- **Server Directory**: Express application with routes, storage, and middleware
- **Shared Directory**: Common TypeScript interfaces and Zod schemas

# External Dependencies

## Core Technologies
- **React Ecosystem**: React 18, React DOM, React Hook Form, TanStack Query
- **UI Framework**: Radix UI primitives for accessible components
- **Styling**: Tailwind CSS with PostCSS and Autoprefixer
- **Development**: Vite build tool with TypeScript support

## Backend Services
- **Database**: Neon Database (PostgreSQL serverless)
- **ORM**: Drizzle ORM with PostgreSQL dialect
- **Session Store**: PostgreSQL-backed session storage

## Development Tools
- **Build System**: Vite for frontend, esbuild for backend bundling
- **Type Safety**: TypeScript across the entire stack
- **Validation**: Zod for runtime type validation and schema generation
- **Replit Integration**: Custom Vite plugins for Replit development environment

## UI and Design
- **Component Library**: Shadcn/ui with comprehensive component coverage
- **Icons**: Lucide React for consistent iconography
- **Fonts**: Google Fonts integration (Inter, DM Sans, Fira Code, etc.)
- **Responsive Design**: Mobile-first approach with Tailwind breakpoints
