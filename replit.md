# Overview

This is a Rubik's Cube solver application built with React and Express. The frontend provides an interactive 3D cube interface where users can input cube states and visualize solution steps. The backend is set up to serve the React application and provide API endpoints for cube solving operations. The application implements the Kociemba algorithm to find optimal solutions for scrambled Rubik's cubes.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
- **React with TypeScript**: Modern component-based UI using functional components and hooks
- **3D Visualization**: Three.js integration for interactive 3D cube rendering and manipulation
- **UI Components**: Comprehensive component library using Radix UI primitives with Tailwind CSS styling
- **State Management**: React hooks for local state management with TanStack Query for server state
- **Routing**: Wouter for lightweight client-side routing
- **Styling**: Tailwind CSS with CSS variables for theming support

## Backend Architecture
- **Express.js Server**: RESTful API server with TypeScript support
- **Modular Storage**: Abstract storage interface with in-memory implementation, designed for easy database integration
- **Development Setup**: Vite integration for development with hot module replacement
- **API Structure**: Route registration system with centralized error handling

## Data Storage Solutions
- **Current**: In-memory storage using Map-based implementation for user data
- **Database Ready**: Drizzle ORM configured for PostgreSQL with schema definitions
- **Migration Support**: Database migration system using Drizzle Kit

## Core Features
- **Cube State Management**: Comprehensive cube state validation and manipulation
- **Algorithm Implementation**: Kociemba two-phase algorithm for optimal cube solving
- **Interactive Input**: Both 2D grid and 3D cube interfaces for cube state input
- **Solution Visualization**: Step-by-step solution playback with move descriptions
- **Validation System**: Real-time cube state validation with error reporting

## Build and Development
- **Build System**: Vite for fast development and optimized production builds
- **TypeScript**: Full type safety across frontend and backend with shared types
- **Development Tools**: Hot reload, error overlays, and development-specific tooling
- **Path Aliases**: Organized import system with @ aliases for clean code organization

# External Dependencies

## Core Framework Dependencies
- **React**: Frontend framework with hooks and context
- **Express.js**: Backend web server framework
- **Three.js**: 3D graphics library for cube visualization
- **TypeScript**: Static type checking across the entire stack

## UI and Styling
- **Radix UI**: Accessible component primitives for complex UI elements
- **Tailwind CSS**: Utility-first CSS framework with custom design system
- **Lucide React**: Icon library for consistent iconography

## Database and ORM
- **Drizzle ORM**: Type-safe SQL toolkit with PostgreSQL support
- **Neon Database**: Serverless PostgreSQL integration
- **Connect PG Simple**: PostgreSQL session store for Express

## Development and Build Tools
- **Vite**: Fast build tool with development server
- **ESBuild**: JavaScript bundler for production builds
- **PostCSS**: CSS processing with Tailwind integration
- **TSX**: TypeScript execution for development server

## State Management and Data Fetching
- **TanStack Query**: Server state management with caching and synchronization
- **React Hook Form**: Form state management with validation
- **Zod**: Runtime type validation and schema parsing

## Additional Libraries
- **Wouter**: Lightweight routing library for React
- **Date-fns**: Date manipulation and formatting utilities
- **Nanoid**: Unique ID generation for client-side operations
- **Class Variance Authority**: Utility for component variant management