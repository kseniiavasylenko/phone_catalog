## Overview
Welcome to the Phone Catalog, a comprehensive e-commerce application designed, according to [Figma Design](https://www.figma.com/design/T5ttF21UnT6RRmCQQaZc6L/Phone-catalog--V2--Original?node-id=15875-34649&t=LqrQOgkUU02jXi4e-0), with a focus on user experience and modern web practices. This project includes a product catalog, shopping cart, favorites page, and various other features. It supports multiple themes, smooth UI transitions, and advanced features like search and pagination.

## Demo
You can view a live demo of the application [Demo](https://kseniiavasylenko.github.io/phone_catalog/).

## Key Features

* PictureSlider: Customizable hero images with automatic 5-second transitions and manual navigation dots.

* ProductsSlider: Hot prices block with horizontal scrolling functionality.

* Shop by Category: Direct links to Phones, Tablets, and Accessories.

* Brand New Products: Display of new items sorted by release year.

* Loading and Error Handling: Select dropdowns for sorting and pagination controls with appropriate error fallback messages and loaders.

* Product Details: Detailed product information page with interactive color/capacity options, image gallery selection, technical specs, and breadcrumb navigation.

* Shopping Cart Management: Ability to add, remove, and update product quantities with localStorage persistence and a checkout confirmation modal.

* Favorites Management: Wishlist system with localStorage support and live header counter badge.

* Error Handling: Dedicated NotFoundPage for unknown URLs and product not found states.

## Challenges
Developing the application involved several challenges, particularly around implementing complex features and ensuring a seamless user experience.

## Key Challenges
* Feature Integration: Integrating multiple features such as sliders, sorting, URL-synced pagination, and product details required careful planning and coordination.

* Responsive Design: Ensuring that all components and features work seamlessly across various devices and screen sizes demanded extensive testing and adjustments.

* State Management: Efficiently managing application state for shopping cart, favorites, and product details—including localStorage interactions—required robust state management strategies.

* Error Handling: Handling errors gracefully in various parts of the application, including loading states, missing products, and API interactions, was crucial for a smooth user experience.

* User Experience: Implementing smooth transitions, responsive layout shifts, and interactive elements like sliders and modals required attention to detail to ensure a fluid experience.

* Performance Optimization: Ensuring that the application performs well with efficient data handling and smooth animations was essential for maintaining high quality.

These challenges were addressed through careful design, iterative development, and thorough testing to deliver a high-quality, feature-rich application.

## Installation & Setup
To install the project and run it locally, follow these steps:

1. Clone the repository:

git clone https://github.com/kseniiavasylenko/phone_catalog.git

2. Navigate to the project directory:

cd react_device-catalog

3. Install dependencies:

npm install

4. Start the local development server:

npm start

5. Build & deploy:

npm run build
npm run deploy

## Technologies Used
* React: For building the user interface.
* TypeScript: For type safety and better development experience.
* Vite: For fast and optimized build tooling.
* pnpm: For package management.
* CSS Modules: For scoped and modular CSS styling.
* React Context / Redux: For state management of cart and favorites.
* Sass: For advanced CSS styling capabilities.
* React Router: For routing and navigation.
* @vitejs/plugin-react-swc: For React and TypeScript support.
* vite-svg-sprite-wrapper: For handling SVG sprites.
* Husky: For Git hooks to enforce code quality.
* ESLint: For linting JavaScript and TypeScript code.
* Prettier: For code formatting.
