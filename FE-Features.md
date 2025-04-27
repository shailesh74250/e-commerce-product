- Project Setup & Architecture
  - Set up frontend project (Next.js + TailwindCSS or SCSS)
  - Configure ESLint, Prettier, Husky, and commit hooks
  - Set up absolute imports and alias paths (@components, @utils, etc)
  - Set up Jest + React Testing Library for unit tests
  - Layout System: Header, Footer, Container Components
  - Theme Setup (dark/light mode toggle if needed)

- Sprint 2: Authentication & User Management
  - Build login and signup pages
  - Implement email/password authentication (connect with backend)
  - Store tokens (securely in HttpOnly cookies or localStorage)
  - Create User Profile Page (edit profile, change password)
  - Handle protected/private routes (AuthGuard HOC)

- Product Listing & Category Pages
  - Build dynamic product listing pages
  - Implement category and subcategory filters
  - Build product search functionality
  - Pagination / Infinite Scroll (frontend pagination)
  - Skeleton loaders & Shimmer effects for UX

- Product Details & Cart System
  - Build a dynamic product detail page (with SEO meta tags)
  - Add to cart functionality
  - Manage cart quantity, remove item, update item
  - Persist cart across sessions (localStorage + backend sync)
  - Write unit tests for CartContext or Redux Cart Slice

- Checkout & Address Management 
  - Build a multi-step checkout process (Address → Payment → Summary)
  - Address CRUD (Add, Edit, Delete addresses)
  - Payment integration (frontend capture + redirect to success page)
  - Checkout the order confirmation page
  - Clear cart on successful order

- Reviews, Ratings, and Wishlist
  - Build review submission form (rating + comment)
  - Show average product rating on product cards
  -  Wishlist add/remove (connect with backend)
  - Wishlist Page (View and manage wishlist)
  - Wishlist is available only to logged-in users

- Notifications & Order History
  - Show order status notifications (placed, shipped, delivered)
  - Build Order History page
  - Order detail view (items, address, payment info)
  - In-app notifications (Optional for promo/sale alerts)

- Admin Dashboard (Frontend if Admin Panel Needed)
  - Product management (list/add/update/delete products)
  - Category management
  - View basic sales stats dashboard (orders today, monthly revenue) 
  - Admin authentication and protected routes
  - Role-based component rendering (admin vs. normal user)

- QA, Security & Optimization
  - Write component/unit tests (80%+ coverage target)
  - Add frontend validations (Yup, Zod)
  - Implement security headers (via Next.js middleware)
  - Lazy load components (dynamic import)
  - Bundle size analysis (using next-bundle-analyzer)
  - Optimize Core Web Vitals (LCP, FID, CLS)
