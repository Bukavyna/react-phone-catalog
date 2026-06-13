# Product Catalog - Modern Phone & Gadget Store

This project showcases a modern, fully responsive product catalog website designed to help users discover, filter, and purchase stylish tech gadgets and phones. The site provides detailed descriptions of product categories, a dynamic product details section, and an engaging user interface with local state persistence for user selections.

## 🚀 Live Preview

Experience the live website: [Phone Catalog Demo](https://bukavyna.github.io/react-phone-catalog/)

---

## Technologies Used

### Core
* **React** (v18.2.0) – UI framework
* **TypeScript** (v5.0.2) – Type safety
* **SCSS** (v7.0.3) – Styling

### State Management
* **Redux Toolkit** (v1.9.5) – Application state
* **Redux Persist** (v6.0.0) – State persistence (Favorites & Cart)

### UI/UX
* **React Router** (v6.14.2) – Navigation
* **Swiper** (v10.0.4) – Image galleries on product pages
* **use-react-router-breadcrumbs** (v4.0.1) – Navigation breadcrumbs
* **React Loading Skeleton** (v3.3.1) – Elegant loading states

### Development & Deployment
* **Vite** (v4.4.5) – Build tool
* **ESLint** (v8.45.0) – Code quality
* **GitHub Pages** – Hosting and deployment

---

## Features

* **Responsive Design:** Optimized for different screen sizes and devices, with breakpoints tailored for mobile, tablet, and desktop layouts (320px, 640px, 1200px, 1440px).
* **Navigation:** Built with `react-router-dom` to enable smooth navigation between multiple pages (Home, Catalog, Product Details, Cart, Favorites) with URL-based search parameters.
* **Favorites & Cart:** Easily add items to favorites or the shopping cart, featuring real-time price calculations and item quantity updates with persistence across page reloads.
* **Product Filtering:** Filter products dynamically by capacity and color directly inside the product details card.
* **Sorting:** Sort product lists based on criteria like release year, price, or alphabetically.
* **Search:** Quick and efficient product filtering using query parameters in the search bar.
* **Pagination:** Navigate through large lists of items with custom pagination, giving the option to choose items per page.
* **Sticky Header:** Keeps the navigation bar visible as you scroll down the page.
* **Scroll to Top Button:** Easily return to the top of the page with a single click.
* **Loader & Skeletons:** Premium user experience with smooth loading skeletons and indicators while processing data.

---

## Getting Started

Follow these instructions to set up the project locally:

### 1. Clone the repository:
```bash
git clone [https://github.com/Bukavyna/react-phone-catalog.git](https://github.com/Bukavyna/react-phone-catalog.git)
cd react-phone-catalog
