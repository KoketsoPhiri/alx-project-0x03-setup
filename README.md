# 🚀 Splash App: Next.js Boilerplate with Shared Layout & Routing

Welcome to **Splash App**, a foundational Next.js project designed as a boilerplate for building modern web applications. This project focuses on implementing core features such as a shared layout, global styling with Google Fonts, imperative routing, and a well-organized codebase with centralized interfaces.

This repository serves as the setup for `alx-project-0x03`, demonstrating best practices for structuring a Next.js application using the **App Router**.

## ✨ Features

* **Shared Layout (DRY Principle):** Implements a reusable `Layout` component that wraps all pages, providing a consistent `Header` and `Footer` across the application, adhering to the Don't Repeat Yourself (DRY) principle.
* **Reusable Button Component:** A highly customizable `Button` component with support for different sizes, background colors, and action handlers.
* **Google Fonts Integration:** Globally imports and applies the "Montserrat" font from Google Fonts using Tailwind CSS, ensuring a consistent and appealing typography throughout the application.
* **Imperative Routing:** Demonstrates programmatically navigating between pages using the `useRouter` hook from `next/navigation`, particularly useful for navigation triggered by user interactions (e.g., button clicks).
* **Centralized Interfaces:** All TypeScript interfaces (`ButtonProps`, `LayoutProps`, `PageRouteProps`) are consolidated into a single `interface/index.ts` file, promoting better code organization and maintainability.
* **Custom 404 Page:** A custom and user-friendly "Page Not Found" (`404`) error page (`app/not-found.tsx`) to enhance the user experience for non-existent routes.

## 🛠️ Technologies Used

* **Next.js 14+ (App Router):** A React framework for production-ready applications.
* **React 18+:** The core JavaScript library for building user interfaces.
* **TypeScript:** A strongly typed superset of JavaScript that enhances code quality and developer experience.
* **Tailwind CSS:** A utility-first CSS framework for rapidly building custom designs.
* **React Icons (`react-icons/fa`):** A library for including popular icon packs in your React projects.

## 🚀 Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

* Node.js (v20.x or higher recommended, as the project was initialized with v24.3.0 in mind)
* npm (comes with Node.js)
* Git

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_GITHUB_USERNAME/alx-project-0x03-setup.git](https://github.com/YOUR_GITHUB_USERNAME/alx-project-0x03-setup.git) # Replace with your actual repo URL
    cd alx-project-0x03-setup/alx-project-0x03 # Navigate into the project directory
    ```
    *Note: The project structure is `alx-project-0x03-setup/alx-project-0x03` as per the initial setup instructions.*

2.  **Install dependencies:**
    ```bash
    npm install
    ```

### Running the Development Server

To start the development server:

```bash
npm run dev