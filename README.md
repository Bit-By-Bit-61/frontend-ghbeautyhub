# GH Beauty Hub - Frontend

This is the frontend application for the GH Beauty Hub project, built with React and Vite.

## Features

- Modern, responsive UI design
- User authentication and registration
- Service browsing and booking
- Stylist profiles and selection
- Payment integration
- Admin and customer dashboards
- Mobile-friendly interface

## Tech Stack

- **Framework**: React 18
- **Build Tool**: Vite
- **Styling**: CSS with modern design principles
- **State Management**: React Context API
- **Routing**: React Router
- **Payment**: Integration ready

## Project Structure

```
src/
├── components/       # Reusable UI components
├── pages/           # Page components
├── contexts/        # React contexts
├── utils/           # Utility functions
├── config.js        # Configuration
└── main.jsx         # App entry point
```

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

2. Set up environment variables:
   ```bash
   cp .env.example .env
   # Edit .env with your configuration
   ```

3. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Build for production:
   ```bash
   npm run build
   # or
   yarn build
   ```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Environment Variables

- `VITE_API_URL` - Backend API URL
- `VITE_SUPABASE_URL` - Supabase URL
- `VITE_SUPABASE_ANON_KEY` - Supabase anonymous key

## Features

- **Home Page**: Landing page with hero section
- **Services**: Browse and book beauty services
- **Stylists**: View stylist profiles and ratings
- **Booking**: Schedule appointments
- **Dashboard**: User-specific dashboards
- **Authentication**: Login/register system

## Contributing

This repository is part of the GH Beauty Hub project. Please refer to the main project documentation for contribution guidelines.
