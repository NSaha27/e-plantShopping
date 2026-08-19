# e-plantShopping

---

# 🌿 Paradise Nursery (e-plantShopping)

A responsive single-page React application for an online houseplant nursery. This project allows users to browse a variety of plants, add them to a shopping cart, manage cart quantities, and view real-time cost calculations. 

It demonstrates the practical application of React Hooks (`useState`, `useEffect`) and global state management using **Redux Toolkit**.

## ✨ Features

* **Landing Page:** A welcoming landing page featuring a background image, company description, and a "Get Started" button to navigate to the store.
* **Product Catalog:** Displays a diverse selection of houseplants grouped into distinct categories.
* **Shopping Cart Management:** 
  * Add plants to the cart (buttons disable dynamically once an item is added to prevent duplicates).
  * Increase or decrease the quantity of specific items in the cart.
  * Delete items entirely from the cart.
* **Real-Time Calculations:** Dynamically calculates and displays the total number of items in the cart, the subtotal for each plant type, and the grand total cost.
* **Global Header:** A persistent navigation bar featuring a dynamic cart icon that updates the item count in real-time.

## 🛠️ Technologies Used

* **Frontend Framework:** [React](https://react.dev/) (via Vite)
* **State Management:** [Redux Toolkit](https://redux-toolkit.js.org/) & React-Redux
* **Routing:** React Router (or Conditional Component Rendering)
* **Styling:** Vanilla CSS 

## 🚀 Getting Started

To run this project locally on your machine, follow these steps:

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) and `npm` installed on your machine.

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/NSaha27/e-plantShopping.git](https://github.com/NSaha27/e-plantShopping.git)

2. **Navigate to the project directory:**
    ```bash
    cd e-plantShopping

3. **Install dependencies:**
    ```bash
    npm install

4. **Start the development server:**
    ```bash
    npm run dev

5. Open your browser and visit http://localhost:5173 (or the port specified in your terminal) to view the app!

## 📂 Project Structure Highlights
* **src/store.js:** Configures the Redux store.

* **src/CartSlice.jsx:** Contains the Redux slice for cart management, including reducers for addItem, removeItem, and updateQuantity.

* **src/ProductList.jsx:** Renders the plant catalog and handles the "Add to Cart" dispatch logic.

* **src/CartItem.jsx:** Renders the interactive shopping cart, handles quantity adjustments, and calculates totals.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.