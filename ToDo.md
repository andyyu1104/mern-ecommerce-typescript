# MERN + TypeScript E-commerce App -- Development Todo List

Tech stack: - React - TypeScript - Node.js - Express.js - MongoDB -
GitHub (version control)

------------------------------------------------------------------------

# 1. Project Setup

-   [ ] Create project folder
-   [ ] Initialize Git repository
-   [ ] Create repository on GitHub
-   [ ] Add `.gitignore`
-   [ ] Write initial `README.md`
-   [ ] Create folders

```
    backend/
    frontend/
```

-   [ ] Make first commit

---

# 2. Backend Setup (Node + TypeScript)

-   [ ] Initialize backend project

``` 
npm init -y 
```
    

-   [ ] Install dependencies
    -   Express
    -   Mongoose
    -   cors
    -   dotenv
-   [ ] Install TypeScript tools
    -   typescript
    -   ts-node
    -   @types packages
-   [ ] Initialize `tsconfig.json`
-   [ ] Create folder structure

```
    backend/src
    backend/src/models
    backend/src/routes
    backend/src/controllers
    backend/src/middleware
    backend/src/types
```

-   [ ] Create `server.ts`
-   [ ] Connect MongoDB database
-   [ ] Test API server

------------------------------------------------------------------------

# 3. Database Models

-   [ ] Create Product model
-   [ ] Create User model
-   [ ] Create Order model
-   [ ] Add TypeScript interfaces

Example models:

    Product
    User
    Order
    CartItem

-   [ ] Commit to GitHub

------------------------------------------------------------------------

# 4. Authentication System

-   [ ] Register user API
-   [ ] Login API
-   [ ] Password hashing with bcrypt
-   [ ] Token authentication using JWT
-   [ ] Create authentication middleware
-   [ ] Protect private routes

------------------------------------------------------------------------

# 5. Product API

Create routes:

    GET /products
    GET /products/:id
    POST /products
    PUT /products/:id
    DELETE /products/:id

-   [ ] Create admin-only product creation
-   [ ] Add product image field
-   [ ] Commit changes

------------------------------------------------------------------------

# 6. Order System

-   [ ] Create order schema

Routes:

    POST /orders
    GET /orders
    GET /orders/:id

-   [ ] Save user purchase history

------------------------------------------------------------------------

# 7. Frontend Setup

Create frontend with Vite:

-   [ ] Create React + TypeScript project
-   [ ] Install Axios
-   [ ] Create frontend folder structure

```
    src/
    components/
    pages/
    hooks/
    types/
    services/
```

-   [ ] Commit to GitHub

------------------------------------------------------------------------

# 8. UI Pages

-   [ ] Home page (product list)
-   [ ] Product details page
-   [ ] Login page
-   [ ] Register page
-   [ ] Cart page
-   [ ] Checkout page
-   [ ] Orders page
-   [ ] Admin dashboard

------------------------------------------------------------------------

# 9. Shopping Cart

-   [ ] Add cart state
-   [ ] Add "Add to cart" button
-   [ ] Remove items from cart
-   [ ] Change quantity
-   [ ] Calculate total price

Example cart structure:

    Product
    Quantity
    Subtotal

------------------------------------------------------------------------

# 10. Checkout & Payments

-   [ ] Create checkout page
-   [ ] Connect payment API
-   [ ] Integrate Stripe

Workflow:

    Cart → Checkout → Payment → Order saved

------------------------------------------------------------------------

# 11. Admin Dashboard

-   [ ] Admin login
-   [ ] Add product page
-   [ ] Edit product page
-   [ ] Delete product
-   [ ] View orders

------------------------------------------------------------------------

# 12. Testing

-   [ ] Test product API using Postman
-   [ ] Test login system
-   [ ] Test checkout flow
-   [ ] Fix bugs

------------------------------------------------------------------------

# 13. Deployment

-   [ ] Deploy backend to Render
-   [ ] Deploy frontend to Vercel
-   [ ] Use MongoDB Atlas for database

------------------------------------------------------------------------

# 14. Portfolio Polish

-   [ ] Add screenshots
-   [ ] Write documentation
-   [ ] Add demo link
-   [ ] Add setup instructions
-   [ ] Clean commit history

------------------------------------------------------------------------

# Final Feature Checklist

-   [ ] Authentication
-   [ ] Product catalog
-   [ ] Shopping cart
-   [ ] Checkout system
-   [ ] Order history
-   [ ] Admin panel
-   [ ] Payment system
-   [ ] Responsive UI

------------------------------------------------------------------------

# Suggested Timeline

Week 1 -- Project setup + backend\
Week 2 -- Authentication + product API\
Week 3 -- Frontend UI\
Week 4 -- Cart + checkout\
Week 5 -- Deployment + polishing
