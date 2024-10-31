
# 🌿 Paradise Nursery - Houseplant Shopping App 🌿

Welcome to **Paradise Nursery**, your ultimate destination for browsing and purchasing beautiful houseplants! This front-end application allows users to seamlessly browse, add to cart, and manage their selections of indoor plants. 🌱

![Paradise Nursery Banner](./assets/banner.jpg)

---

## 🚀 Project Overview

Paradise Nursery is designed to offer a smooth shopping experience where users can explore a variety of houseplants, view detailed product listings, and manage their cart effortlessly. The app includes essential features like a landing page, product listing page, and a functional shopping cart to enhance the user experience from browsing to checkout.

### Project Features:

1. **Landing Page**
   - Company introduction and an engaging background image.
   - "Get Started" button to initiate the shopping experience.

2. **Product Listing Page**
   - Displayed plant categories with add-to-cart functionality.
   - Quick access to all plants to encourage exploration.

3. **Shopping Cart Page**
   - View all selected items with quantity adjustments.
   - Dynamic subtotal and total calculations.
   - Checkout button for a seamless transition to payment.

## 📂 Folder Structure

```
paradise-nursery/
├── src/
│   ├── components/
│   │   ├── App.js
│   │   ├── AboutUs.js
│   │   ├── CartItem.js
│   │   ├── ProductList.js
│   │   ├── CartSlice.js
│   │   └── ...other components
│   └── styles/
│       ├── app.css
│       └── ...other styles
└── README.md

```

## ⚙️ Redux Integration

The project leverages **Redux** for managing the cart state, which provides an efficient, centralized way to track and update items as users interact with the cart.

### `CartSlice.js`

This slice contains actions for:
- **Adding Items**: When users add a plant, it’s pushed to the cart.
- **Updating Quantity**: Adjust the quantity of each item as desired.
- **Removing Items**: Delete items from the cart.
- **Clearing Cart**: Empty the cart with a single action.

## 📋 Task Breakdown

The project involved various tasks to create a cohesive shopping experience, including:

1. **Component Creation**:
   - Developed reusable components such as `App`, `AboutUs`, `CartItem`, and `ProductList`.

2. **State Management**:
   - Set up Redux store with `CartSlice.js` for managing cart operations.

3. **Add-to-Cart Functionality**:
   - Implemented `addItem`, `updateQuantity`, and `removeItem` actions in the cart to provide full control over the cart’s contents.

4. **Responsive Styling**:
   - Ensured that components and pages are styled responsively using CSS, providing a consistent experience across devices.

## 🛠️ Technologies Used

- **JavaScript**
- **React.js**
- **Redux Toolkit**
- **CSS**
  
## 📸 Screenshots

### Landing Page
![Landing Page](./assets/banner.png)

### Product Listing Page
![Product Listing](./assets/plant_list.png)

### Cart Page
![Cart Page](./assets/cart.png)

## 📈 Future Enhancements

The following features could be added to improve the app further:
- **Product Filtering**: Allow users to filter plants by categories or care level.
- **Wishlist Feature**: Provide an option for users to save items they want to buy later.
- **Checkout Integration**: Connect the app with a payment gateway for a complete checkout experience.

## 💻 Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Mayur-nimkande-20/e-plantShopping.git
   ```
2. Navigate to the project folder:
   ```bash
   cd paradise-nursery
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```


