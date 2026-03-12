# Amazon Mini Clone 🛒

A high-performance e-commerce front-end implementation built with **Vanilla JavaScript**, **HTML5**, and **CSS Grid**. This project demonstrates scalable DOM manipulation, state management, and automated testing without the use of external frameworks like React or Vue.

## 🚀 Key Features

* **Dynamic Product Rendering**: Generates product grids using data-driven JavaScript objects and classes.
* **Persistent Shopping Cart**: Full cart functionality (Add, Update, Remove) powered by `LocalStorage` to keep data after page reloads.
* **Interactive Checkout**: Real-time delivery date selection using **DayJS**, with automatic price and tax recalculation.
* **Object-Oriented Design**: Utilizes JS Classes to manage product types (e.g., handling specific attributes for clothing vs. appliances).
* **Automated Testing**: Comprehensive unit and integration tests using the **Jasmine** testing framework to ensure cart logic and UI rendering are bug-free.
* **Responsive Design**: Built with a "Mobile First" approach using CSS Grid and Flexbox for a seamless experience across devices.

## 🛠️ Tech Stack

* **HTML5 & CSS3**: Semantic layout and advanced CSS Grid systems.
* **JavaScript (ES6+)**: Modules, Classes, and Async logic.
* **DayJS**: Library for complex date manipulations.
* **Jasmine**: Behavioral-driven development (BDD) testing framework.

## 📂 Project Structure

```text
├── data/               # Product and Cart data logic (State Management)
├── scripts/            # Main application logic and UI rendering
│   ├── checkout/       # Checkout page specific modules
│   └── utils/          # Formatting and helper functions (e.g., money.js)
├── tests.jasmine/      # Automated test suites
├── images/             # UI icons and product assets
├── styles/             # Modular CSS files
└── amazon.html         # Main entry point
```
## 🧪 Testing

This project prioritizes code reliability and automated verification:

* **Framework**: Uses **Jasmine** for Behavioral-Driven Development.
* **Unit Tests**: Verified currency utility functions (`money.js`) to handle rounding and zero-edge cases.
* **Integration Tests**: Simulated the **Order Summary** lifecycle, ensuring the DOM updates correctly when items are removed or shipping options change.
* **Mocking**: Implemented `spyOn` for `localStorage` to ensure tests don't pollute actual user data.

To run the tests, simply open the `tests.html` (or your spec runner file) in a browser via Live Server.

## 📖 What I Learned

Throughout this build, I strengthened several core Full-Stack engineering concepts:

* **State Persistence**: Mastered the use of `localStorage` to maintain a consistent user experience across page refreshes.
* **Modular Architecture**: Leveraged **ES6 Modules** to separate data (products/cart) from UI logic, making the codebase scalable.
* **Object-Oriented Programming (OOP)**: Transitioned from procedural code to **Classes**, allowing for cleaner management of different product types and methods like `getPrice()` and `getStarsUrl()`.
* **The DOM Lifecycle**: Gained deep experience in dynamic re-rendering, specifically how to trigger specific UI updates without a full page reload.

## 👷 How to Run Locally

Follow these steps to get the project running on your local machine:

1. **Clone the Repo**
   ```bash
   git clone https://github.com/ShreyashMishra10/Amazon-Mini-Clone.git
