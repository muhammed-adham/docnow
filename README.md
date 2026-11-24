# Healthcare Appointment Booking System

A modern web application for booking medical appointments, built with React and enhanced with AI-powered development tools.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup Instructions](#setup-instructions)
- [AI Tool Usage](#ai-tool-usage)
- [Current Limitations](#current-limitations)
- [Next Steps](#next-steps)

## Features

- **Doctor Search & Filtering**
  - Search by specialty, location, and availability
  - Detailed doctor profiles with ratings and reviews
  - Availability shown per doctor (static demo data)

- **Appointment Booking**
  - Easy-to-use booking interface
  - Multiple time slot selection
  - Appointment confirmation after booking

- **User Management**
  - Appointment history (saved in the browser with localStorage)
  - Login page UI (authentication is not implemented yet)

- **Accessibility**
  - ARIA labels and roles on interactive elements
  - Keyboard navigation support
  - Responsive design for all devices

## Tech Stack

- **Frontend**
  - React 18
  - Vite
  - Tailwind CSS
  - React Router
  - React Icons

- **Development Tools**
  - Cursor IDE with AI assistance
  - ESLint
  - Git for version control

## Setup Instructions

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- Git

### Installation

1. Clone the repository:
```bash
git clone https://github.com/muhammed-adham/healthcare-app.git
cd healthcare-app
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open [http://localhost:5173](http://localhost:5173) in your browser.

### Production Build
```bash
npm run build
```

## AI Tool Usage

During development, Cursor IDE's AI capabilities were used for:

1. **Code Generation**
   - Component structure and boilerplate
   - Accessibility improvements
   - Mock data creation

2. **Code Refactoring**
   - Component optimization

3. **Bug Fixing**
   - Error detection and resolution
   - Logic validation

## Current Limitations

1. **Data Management**
   - Uses static mock data (no backend)
   - No real-time updates
   - Appointments persist only in the browser (localStorage)

2. **Authentication**
   - Not implemented yet (the login page is UI only)
   - No social login
   - No session management

3. **Performance**
   - No code splitting
   - No caching layer

4. **Features**
   - No video consultation
   - No payment integration
   - No notification system

## Next Steps

- [ ] Connect a backend with real authentication
- [ ] Real-time availability updates
- [ ] Run a formal accessibility audit (WCAG 2.1)
- [ ] Add automated tests
- [ ] Code splitting and bundle optimization
- [ ] Multi-language support
