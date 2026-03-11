# Project Documentation

## Tech Stack Overview
The project is a modern Frontend web application built with a robust and modern stack.

### Core Frameworks
*   **React 18**: The core UI library.
*   **Vite**: The build tool and development server, utilizing the SWC plugin for highly optimized compilation speeds.
*   **TypeScript**: Used for static type-checking and robust development.
*   **React Router DOM**: Handles client-side routing and navigation.

### Styling & UI Library
*   **Tailwind CSS**: A utility-first CSS framework for rapid and customizable styling.
*   **Shadcn UI**: An accessible and customizable component system built on top of Radix UI primitives. It integrates seamlessly with Tailwind CSS.
    *   **Radix UI Primitives**: Powers many accessible headless components like Accordions, Dialogs (Modals), Dropdown Menus, Select inputs, Tabs, Tooltips, and more.
*   **Lucide React**: The primary icon library used throughout the application.
*   **Framer Motion**: Used for declarative and smooth UI animations.
*   **Embla Carousel**: A lightweight slider/carousel library used for media galleries or image sliders.

### State Management & Data Fetching
*   **TanStack React Query**: Manages server state, caching, synchronization, and data fetching operations efficiently.
*   **React Hook Form**: Handles complex form state, validation, and submissions.
*   **Zod**: Used in tandem with React Hook Form for strict schema declaration and validation.

### Testing & Linting
*   **Vitest**: A blazing fast unit test framework powered by Vite.
*   **React Testing Library**: Used alongside Vitest for testing React components.
*   **ESLint**: Configured with React and TypeScript plugins to enforce code quality and stylistic rules.

---

## Development Scripts
You can run the following commands using your package manager (`npm`, `yarn`, or `bun` given the presence of `bun.lockb`):

*   `npm run dev` - Starts the Vite development server with Hot Module Replacement (HMR).
*   `npm run build` - Builds the application for production, outputting optimized static assets into the `dist/` directory.
*   `npm run preview` - Locally previews the production build locally before deployment.
*   `npm run test` - Runs Vitest test suites.
*   `npm run lint` - Runs ESLint to check for code issues.

---

## Project Structure
Standard Vite + React folder structure:
- `src/`: Contains the main source code, components, hooks, utilities, and assets.
- `public/`: Contains static assets that are served directly.
- `dist/`: The output folder containing the production build.
- `tailwind.config.ts`: Configuration for Tailwind CSS tokens and themes.
- `vite.config.ts`: Configuration for the Vite bundler.
- `components.json`: Configuration for the Shadcn UI components setup.
