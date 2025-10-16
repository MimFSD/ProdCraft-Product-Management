# 🛍️ ProdCraft Product Management 

## 🎯 Goal
Build a **Next.js (App Router)** application that allows users to **browse, create, edit, view, and delete products**.  
Focus on:
- Polished **UI/UX**
- Strong **validation**
- Clean, maintainable **code**

> 💡 Use the given color palette for your design to maintain visual consistency.

---

## ⚙️ Quick API Notes
- **Authentication**  
  Send a POST request to `/auth` with your registered email:
  ```json
  { "email": "you@example.com" }
You’ll receive a JWT token — include it in every request header:

makefile
Copy code
Authorization: Bearer <your_jwt_token>
🧰 Required Tech Stack
Framework: Next.js (App Router)

Library: React

State Management: Redux Toolkit

Styling: Tailwind CSS

🧑‍💻 Functional Requirements
🔐 Auth & Session
Simple login screen (email only)

Call POST /auth, store JWT in Redux store

Include token with all product-related requests

Provide Logout functionality

🗂️ Products Page
Display all products with pagination

Real-time search by product name

Delete product with confirmation pop-up

Implement data caching and proper cache invalidation after create/edit/delete

✏️ Create & Edit Pages
Single form used for both Create and Edit flows

Add or update products with category selection

Client-side validation for:

Required fields

Data types (string/number)

Custom rules (e.g., price > 0)

Show inline error messages and handle server errors gracefully

📄 Product Details Page
Display full product information

Include Edit and Delete actions (with confirmation)

💎 UX / UI Expectations
Modern and visually consistent design

Proper spacing, typography, and alignment

Fully responsive layout (mobile & desktop)

Clear loading and error states

Smooth and intuitive user flows for Create/Edit/Delete

🚀 Deployment (Mandatory)
Deploy the project using Vercel, Netlify, or a similar platform.
Provide:

🌐 Live deployed link

📦 Public GitHub repository URL

🧾 Evaluation Criteria
Category	Description
Feature completeness	All core CRUD operations, search, pagination, and product details
UX / UI design	Visual polish, layout consistency, and responsiveness
Code quality	Clean architecture, modular components, Redux best practices
Validation & error handling	Proper client-side and server-side validation
Extras / Innovations	Bonus features (filters, animations, micro-interactions, performance optimizations)

💡 Optional Enhancements
Filter products by category

Add product sorting (price, date, etc.)

Integrate optimistic UI updates

Add dark/light theme toggle

✅ Deliverables:

Public GitHub repository

Live deployed demo link

Proper documentation (README, comments, etc.)

“Clean UI, clear logic, and smooth user experience — that’s the goal.”

yaml
Copy code

---

Would you like me to also add a **preview section** (like screenshots, tech badges, or deployment ins