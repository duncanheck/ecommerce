# 🛍️ E-Commerce Product Listing App

This project is a simple React-based e-commerce product listing page. Built for the Advanced JavaScript & Intro to React module at Coding Temple, this app demonstrates the use of React components, `useState`, and `props` to dynamically render a list of products in a clean, responsive layout — without using UI libraries like Bootstrap.

## 🚀 Features

- Built with [Vite](https://vitejs.dev/) and React
- Organized React component structure (App → ProductList → ProductItem)
- Dynamic rendering using `useState` and `props`
- Clean layout with custom CSS styling
- Responsive product cards

## 🧱 Component Structure

App
├── ProductList (receives products array via props)
│ └── ProductItem (receives single product via props)

markdown
Copy
Edit

- **App**: Manages product data state.
- **ProductList**: Maps over product data and renders `ProductItem` components.
- **ProductItem**: Displays individual product details (name, price, description).

## 🛠️ Tech Stack

- React + Vite
- JavaScript (ES6)
- CSS (custom)

## 📁 File Structure

ecommerce/
├── src/
│ ├── components/
│ │ ├── ProductList.jsx
│ │ ├── ProductItem.jsx
│ │ ├── ProductList.css
│ │ └── ProductItem.css
│ ├── App.jsx
│ ├── App.css
│ ├── main.jsx
│ └── index.css
├── index.html
└── package.json

bash
Copy
Edit

## 📦 Getting Started

Clone and run the project locally:

```bash
git clone https://github.com/duncanheck/ecommerce.git
cd ecommerce
npm install
npm run dev
Then visit: http://localhost:5173

✅ Requirements Met
 Uses useState to manage product data

 Passes data using props

 Renders list using .map()

 Modular React component structure

 Custom CSS layout and styling

 Fully responsive design

👨‍💻 Author
Duncan Hecker

GitHub: @duncanheck
