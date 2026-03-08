Using **Conventional Commits** makes your **Git** history clean and professional, which is important when hosting your project on **GitHub**. Many teams follow this format, and tools can automatically generate changelogs from it.

---

# 📘 Conventional Commit Format

Basic structure:

```text
type(scope): short description
```

Example:

```text
feat(auth): add user login API
```

Structure:

| Part            | Meaning             |
| --------------- | ------------------- |
| **type**        | Kind of change      |
| **scope**       | Part of the project |
| **description** | What changed        |

---

# 1️⃣ Common Commit Types

These are the most useful for your **MERN + TypeScript e-commerce project** using **React**, **Express.js**, and **MongoDB**.

### `feat`

New feature

```text
feat(products): add product listing API
```

---

### `fix`

Bug fix

```text
fix(cart): correct total price calculation
```

---

### `docs`

Documentation changes

```text
docs(readme): add installation instructions
```

---

### `style`

Formatting changes (no logic change)

```text
style(frontend): format code with prettier
```

---

### `refactor`

Code improvement without changing behavior

```text
refactor(auth): simplify JWT middleware
```

---

### `test`

Adding or modifying tests

```text
test(products): add product API tests
```

---

### `chore`

Maintenance tasks

```text
chore(deps): install axios and cors
```

---

### `build`

Changes related to build tools

```text
build(backend): configure TypeScript compiler
```

---

### `ci`

Changes to CI/CD pipelines

```text
ci(github): add GitHub actions workflow
```

---

# 2️⃣ Useful Scopes for Your Project

Scopes describe the part of the app:

```text
backend
frontend
auth
products
cart
orders
checkout
admin
database
api
ui
```

Example commits:

```text
feat(auth): implement user registration
feat(products): add product schema
feat(cart): implement add to cart
feat(orders): create order API
feat(checkout): integrate stripe payments
```

---

# 3️⃣ Example Commit History for Your Project

A realistic commit timeline:

```text
chore(project): initialize MERN ecommerce repository

build(backend): configure TypeScript backend

feat(database): connect MongoDB using mongoose

feat(auth): implement user registration API

feat(auth): add JWT authentication middleware

feat(products): create product model and routes

feat(products): implement product listing endpoint

feat(cart): add cart state management

feat(cart): implement add to cart functionality

feat(orders): create order schema and API

feat(checkout): integrate stripe checkout

feat(admin): create admin product dashboard

fix(cart): correct cart total calculation

docs(readme): add project documentation
```

This kind of history looks **very professional on GitHub**.

---

# 4️⃣ Multi-line Commit Example

For bigger changes:

```text
feat(checkout): integrate stripe payment system

- create payment intent API
- connect frontend checkout page
- store completed orders in database
```

---

# 5️⃣ Commit Frequency

Good practice:

✔ Commit **small logical changes**
✔ Commit **multiple times per day**
✔ Avoid huge commits like:

```text
update project
```

---

# ⭐ Example Workflow While Coding

Typical day:

```bash
git checkout -b feature/product-api
git add .
git commit -m "feat(products): add product schema"
git commit -m "feat(products): create product routes"
git commit -m "feat(products): implement get products API"
git push origin feature/product-api
```

Then open a pull request on **GitHub**.

---

✅ If you'd like, I can also give you a **ready-to-follow commit plan with ~70 commits** that match each step of your e-commerce build.

Following it will make your **GitHub history look like a real professional project**.
