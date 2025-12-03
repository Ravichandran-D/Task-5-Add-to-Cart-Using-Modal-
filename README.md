# NOW🛒HERE

A modern e-commerce web application built with React and Vite, featuring a responsive design with Tailwind CSS.

## Technologies Used

- React 19
- Vite 7
- Tailwind CSS 4
- Headless UI
- React Icons
- Axios for API calls

## Project Structure

```
NOWHERE/
├── public/
├── src/
│   ├── Components/
│   │   ├── CartCard.jsx
│   │   ├── CartFooterSection.jsx
│   │   ├── CartSection.jsx
│   │   ├── CustomToast.jsx
│   │   ├── DialogModel.jsx
│   │   ├── HeaderSection.jsx
│   │   ├── ProductCard.jsx
│   │   └── Products.jsx
│   ├── hooks/
│   │   ├── useApiCall.jsx
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── index.html
├── vite.config.js
├── eslint.config.js
└── package.json
```

## Getting Started

### Prerequisites

- Node.js (Latest LTS version recommended)
- npm or yarn package manager

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Ravichandran-D/Task-5-Add-to-Cart-Using-Modal-.git
   cd webstore
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

### Development

To start the development server:

```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:5173` by default.

### Building for Production

To create a production build:

```bash
npm run build
# or
yarn build
```

To preview the production build:

```bash
npm run preview
# or
yarn preview
```

## Features

- Modern React components using functional components and hooks
- Responsive design with Tailwind CSS
- Shopping cart functionality
- Product catalog display
- Toast notifications
- Modal dialogs
- Header section with navigation
