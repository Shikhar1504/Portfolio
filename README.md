# Personal Portfolio Website

This repository contains the frontend source code for a personal portfolio website, built with React and Vite. It showcases projects, skills, and provides contact information, featuring a modern design with animations and responsive layouts.

## Features

- **Modern UI/UX:** Built with React, Tailwind CSS, and Radix UI for a clean, responsive, and accessible user interface.
- **Smooth Animations:** Utilizes `framer-motion` for engaging and fluid animations, enhancing user experience.
- **Typewriter Effect:** Incorporates a dynamic typewriter effect for engaging text display.
- **Space Background:** Features a dynamic space background for visual appeal.
- **Project Showcase:** Dedicated sections to display personal projects with details.
- **Skills Section:** Highlights technical skills and proficiencies.
- **Contact Form:** Provides a way for visitors to send messages, likely integrated with a backend API.
- **Responsive Design:** Optimized for various screen sizes, from desktops to mobile devices.
- **Toast Notifications:** Uses `react-toastify` and `@radix-ui/react-toast` for user feedback and notifications.
- **Routing:** Implements client-side routing with `react-router-dom` for seamless navigation.
- **API Integration:** Uses Axios for making HTTP requests, likely to a backend for contact form submissions or project data.

## Technologies Used

- **React:** A JavaScript library for building user interfaces.
- **Vite:** A fast build tool that provides a lightning-fast development experience.
- **Tailwind CSS:** A utility-first CSS framework for rapidly building custom designs.
- **Framer Motion:** A production-ready motion library for React.
- **Radix UI:** A collection of unstyled, accessible UI components.
- **React Router DOM:** Declarative routing for React.
- **Axios:** Promise-based HTTP client for the browser and Node.js.
- **Typewriter Effect:** A library for creating typewriter-like text animations.
- **Space Background:** A library for generating dynamic space backgrounds.
- **Lucide React:** A collection of beautiful, customizable SVG icons.
- **React Toastify:** A library for adding toast notifications to your React apps.
- **@fontsource/poppins:** Self-hosting Poppins font for consistent typography.
- **lodash.debounce:** A utility for debouncing functions, often used for performance optimization.

## Setup and Installation

To get this project up and running on your local machine, follow these steps:

### Prerequisites

- Node.js (LTS version recommended)

### 1. Clone the repository

```bash
git clone <repository-url>
cd beautiful-portfolio # or the name of your cloned directory
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Running the Application

#### Development Mode

To run the application in development mode with Vite's hot-reloading:

```bash
npm run dev
```

This will start the development server, usually at `http://localhost:5173`.

#### Building for Production

To build the application for production:

```bash
npm run build
```

This will create a `dist` directory with the optimized production build.

#### Previewing Production Build

To preview the production build locally:

```bash
npm run preview
```