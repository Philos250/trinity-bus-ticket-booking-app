# Trinity Bus Ticket Booking App

A modern mobile app for booking bus tickets built with Next.js and shadcn/ui components.

## Features

- User authentication (Login/Signup)
- Bus search and booking
- Seat selection
- Payment processing
- Booking confirmation with QR code
- Trip history
- Profile management

## Pages

- `/` - Onboarding page
- `/login` - Login page
- `/signup` - Sign up page
- `/home` - Home page with search form
- `/search-results` - Available buses listing
- `/select-seat/[id]` - Seat selection page
- `/payment` - Payment processing page
- `/booking-confirmation` - Booking confirmation with ticket details

## Components

- `Header` - Reusable header component with back navigation and menu
- `BottomNav` - Bottom navigation bar
- `TrinityLogo` - Logo component with different size variants

## Getting Started

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Tech Stack

- Next.js 14
- React
- TypeScript
- Tailwind CSS
- shadcn/ui components
- Geist Font
- Lucide Icons

## Design System

The app uses a consistent design system with:

- Primary color: #0066FF
- Font: Geist Sans
- Border radius: 0.625rem
- Spacing system: 4px grid
- Shadow system: Consistent elevation levels

## Project Structure

```
src/
  ├── app/                # Next.js pages
  ├── components/         # Reusable components
  │   ├── ui/            # shadcn/ui components
  │   ├── bottom-nav.tsx # Bottom navigation
  │   ├── header.tsx     # Header component
  │   └── trinity-logo.tsx # Logo component
  ├── lib/               # Utilities and configurations
  └── hooks/             # Custom React hooks
