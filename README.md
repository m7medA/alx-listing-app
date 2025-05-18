# ALX Listing App

## 📌 Project Overview

The **ALX Listing App** is a modern web application designed as an Airbnb clone. This milestone focuses on **scaffolding the project** using **Next.js, TypeScript, TailwindCSS, and ESLint**, ensuring a solid foundation for scalable and maintainable development.

## 🔥 Technologies Used

- **Next.js** (Version 13+)
- **TypeScript** for type safety
- **TailwindCSS** for responsive styling
- **ESLint** for code consistency

## 📂 Folder Structure

│── components/ # Reusable UI components
│ └── common/ # Shared components across the app
│ ├── Card.tsx # Card component with TypeScript props
│ ├── Button.tsx # Custom button component
│── interfaces/ # TypeScript type definitions
│ └── index.ts # Interfaces for props and API responses
│── constants/ # Application constants
│ └── index.ts # API URLs, configuration values
│── public/ # Static assets
│ └── assets/ # Images, icons, fonts
│── pages/ # Application pages
│ └── index.tsx # Main landing page
│── README.md # Project documentation

## ⚙️ Setup Instructions

### 1️⃣ **Clone the Repository**

```bash
git clone https://github.com/your-username/alx-listing-app.git
cd alx-listing-app
```

```npm install
npm run dev
```

## Key Features

- **Type-Safe Components**: All components use TypeScript interfaces for props validation
- **Reusable UI**: Common components like `Card` and `Button` can be used throughout the app
- **Centralized Configuration**: All constants and URLs are managed in one place
- **Clean Architecture**: Separation of concerns with clear directory structure

## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Run the development server: `npm run dev`

## Component Documentation

### Card Component (`components/common/Card.tsx`)

A flexible card component with customizable content.

**Props:**

```typescript
interface CardProps {
  title: string;
  description: string;
  imageUrl?: string;
  onClick?: () => void;
}
```
