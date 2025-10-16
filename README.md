Goal
Build a Next.js (App Router) application that allows a user to browse, create, edit, view details, and delete products. Focus on polished UI/UX, solid validation, and clean code. Please use this color palette for your design.

Quick API notes
Authentication: send POST /auth with the same email you used on your job application, e.g., { "email": "you@example.com" } to get a JWT. Include the token as Authorization: Bearer on every request.

Required tech stack
Framework: Next.js (App Router)

Library: React

State management: Redux Toolkit

Styling: Tailwind CSS 

Functional requirements
Auth & session
Simple login screen that accepts an email, calls POST /auth, store the JWT in the redux store, and send it with product requests.

Provide logout functionality.

Products page
Display all products with pagination.

Real-time search by product name.

Delete product with a confirmation pop-up.

Cache data where necessary; ensure cache invalidation or updates after create/edit/delete.

Create & Edit pages
Single form for create and edit flows.

Create product with category and update product category.

Client-side validations on all fields: required fields, correct types (number/string), and custom validations (e.g., price > 0).

Show inline validation messages and error handling.

Details page
Full product information with actions: Edit, Delete (confirmation).

UX / UI expectations (very important)
Modern, visually consistent design with attention to spacing, typography.

Responsive layout (mobile, desktop).

Clear loading and error states for network operations.

Smooth user flows for primary actions (create, edit, delete).

Deployment (Mandatory)
You must deploy the project to Vercel, Netlify, or a similar hosting platform and provide the following:

Public GitHub repository URL

Live deployed link

What we will evaluate
Feature completeness — All core CRUD flows (products, search, pagination, create, edit, details, delete)

UX / UI design — Visual polish, layout consistency, and responsive behavior. (This is important)

Code quality & best practices — Component structure, modularity, readability, and use of Redux Toolkit.

Validation & error handling — Proper client-side validations and handling of server errors.

Extras/innovations — Thoughtful bonus features (e.g., filter products by category), micro-interactions, improvements, or thoughtful trade-offs.