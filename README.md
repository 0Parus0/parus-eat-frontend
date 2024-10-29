# Enterprise-Level Food Ordering App
The app allows users to add or remove restaurants, place orders, track order status, and make payments securely using Stripe and Stripe webhooks. This project demonstrates my ability to build complex, scalable applications with robust payment integration and real-time data handling

## Demo
Check out the live demo [here](https://parus-food-ordering-app.netlify.app/).



## Features

- **User Auth/Registration/Profile:** Sign up, log in, and manage profile.
- **Search/Sort/Filter/Pagination:** Search a restuarant, sort on the bases of type of food.
- **Manage Restuarant & Image Upload:** Add or remove a restuarant, add image to a restuarant, add or remove menu items.
- **Real-Time Updates:** Add items to the cart and update orders in real-time.
- **Responsive Design:** Optimized for mobile, tablet, and desktop.
- **Secure Checkout:** Integrated with Stripe and Stripe Hooks for secure transactions.

## Technologies Used

- **Frontend:** TypeScript, React, React Query, React Hook Form, TailwindCss, and ShadcnUI.
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Others:** GitHub, Auth0 for authentication, Stripe, Cloudinary.

## Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

- Node.js and npm
- MongoDB (for the database)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/0Parus0/parus-eat-frontend.git
   cd food-ordering-app

2. **Install dependencies:**
  ```bash
  npm install
```
3. **Run:**
  ```bash
  npm run dev
  ```

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
