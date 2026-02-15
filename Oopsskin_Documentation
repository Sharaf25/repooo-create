# Oopsskin E-Commerce Platform - Complete Documentation

## 📋 Table of Contents
1. [Project Overview](#project-overview)
2. [Technology Stack](#technology-stack)
3. [Completed Features](#completed-features)
4. [Project Structure](#project-structure)
5. [Current Status](#current-status)
6. [Upcoming Work](#upcoming-work)
7. [Deployment Guide](#deployment-guide)
8. [API Documentation](#api-documentation)

---

## 🎯 Project Overview

**Oopsskin** is a modern beauty e-commerce platform built with Next.js, featuring a complete shopping experience with bilingual support (English/Arabic), authentication, cart management, and an admin panel.

### Key Information
- **Project Name**: Oopsskin
- **Type**: E-commerce Beauty Products Platform
- **GitHub Repository**: https://github.com/Sharaf25/Oopsskin
- **Current Version**: 1.0.0 (Frontend Complete)
- **Deployment Target**: cPanel (Static Export)

---

## 🛠️ Technology Stack

### Frontend
- **Framework**: Next.js 15+ (App Router with Static Export)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **State Management**: React Context API
- **Package Manager**: npm

### Backend (In Development)
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MySQL
- **ORM**: Native MySQL2 Driver
- **API Architecture**: RESTful

### Development Tools
- **Version Control**: Git & GitHub
- **Code Editor**: VS Code
- **Linting**: ESLint
- **Type Checking**: TypeScript

---

## ✅ Completed Features

### 1. **Frontend Application** (100% Complete)

#### A. User-Facing Pages
- ✅ **Home Page** ([`src/app/page.tsx`](src/app/page.tsx))
  - Hero section with call-to-action
  - Best Sellers product carousel (renamed from Trending Now)
  - Community section
  - Featured banners
  
- ✅ **All Products Page** ([`src/app/all-products/page.tsx`](src/app/all-products/page.tsx))
  - Category filtering sidebar
  - Product grid with 25+ sample products
  - Sorting functionality
  - Category-based URL filtering
  - Color selection for products
  - Add to cart functionality
  
- ✅ **Category Pages**
  - Best Sellers → Links to home page #best-sellers section
  - New Products ([`src/app/new/page.tsx`](src/app/new/page.tsx))
  - Makeup ([`src/app/makeup/page.tsx`](src/app/makeup/page.tsx))
  - Packages ([`src/app/packages/page.tsx`](src/app/packages/page.tsx))
  - Skincare ([`src/app/skincare/page.tsx`](src/app/skincare/page.tsx))

#### B. Shopping Features
- ✅ **Shopping Cart** ([`src/app/cart/page.tsx`](src/app/cart/page.tsx))
  - Add/remove items
  - Quantity adjustment
  - Persistent storage (localStorage)
  - Real-time total calculation
  - Free shipping over $100
  - Voucher/discount code system (Frontend only - Mock data)
  - Cart count badge in navbar
  
- ✅ **Checkout Process** ([`src/app/checkout/page.tsx`](src/app/checkout/page.tsx))
  - Customer information form
  - Delivery address form
  - Order summary with discount
  - Cash on Delivery payment method
  - Order confirmation page

#### C. Authentication System
- ✅ **User Registration** ([`src/app/register/page.tsx`](src/app/register/page.tsx))
  - Full name, email, phone, password fields
  - Form validation
  - Password visibility toggle
  - Auto-login after registration
  
- ✅ **User Login** ([`src/app/login/page.tsx`](src/app/login/page.tsx))
  - Email/password authentication
  - Demo account pre-configured
  - Password visibility toggle
  - Remember me functionality
  
- ✅ **Authentication Protection**
  - Cart page requires login
  - Checkout requires login
  - Add to cart requires login
  - User menu in navbar

#### D. Admin Panel (Frontend Complete)
- ✅ **Dashboard** ([`src/app/admin/page.tsx`](src/app/admin/page.tsx))
  - Statistics cards (Products, Orders, Vouchers, Revenue, Pending)
  - Recent orders table
  - Quick action buttons
  - Mock data display
  
- ✅ **Products Management** ([`src/app/admin/products/page.tsx`](src/app/admin/products/page.tsx))
  - Product listing
  - Add/Edit/Delete products (UI ready)
  - Search and filter
  
- ✅ **Orders Management** ([`src/app/admin/orders/page.tsx`](src/app/admin/orders/page.tsx))
  - Order listing
  - Order details view
  - Status management (UI ready)
  - Filtering and search
  
- ✅ **Vouchers Management** ([`src/app/admin/vouchers/page.tsx`](src/app/admin/vouchers/page.tsx))
  - Voucher CRUD interface
  - Discount types (percentage/fixed)
  - Usage limits and tracking
  - Expiration dates
  - Status toggle

#### E. Components
- ✅ **Navbar** ([`src/app/components/Navbar.tsx`](src/app/components/Navbar.tsx))
  - Responsive navigation
  - Category dropdown menu (All Products)
  - Search icon
  - Cart icon with count badge
  - User menu (Login/Register or Profile/Logout)
  - Language switcher (EN/AR)
  - Mobile menu
  
- ✅ **Footer** ([`src/app/components/Footer.tsx`](src/app/components/Footer.tsx))
  - Newsletter signup
  - About Us links
  - Contact Us links
  - Legal links
  - Social media icons
  - Fully translated
  
- ✅ **Hero Section** ([`src/app/components/HeroSection.tsx`](src/app/components/HeroSection.tsx))
  - Full-width hero banner
  - Call-to-action button
  - Animated background
  
- ✅ **Product Carousel** ([`src/app/components/ProductCarousel.tsx`](src/app/components/ProductCarousel.tsx))
  - Best Sellers section
  - Product cards with colors
  - Add to cart functionality
  - Smooth scrolling navigation
  
- ✅ **Community Section** ([`src/app/components/CommunitySection.tsx`](src/app/components/CommunitySection.tsx))
  - Social proof section
  - Call-to-action

#### F. Context Providers
- ✅ **CartContext** ([`src/app/context/CartContext.tsx`](src/app/context/CartContext.tsx))
  - Add/remove/update cart items
  - Persistent storage (localStorage)
  - Cart count and total calculation
  - Clear cart functionality
  
- ✅ **AuthContext** ([`src/app/context/AuthContext.tsx`](src/app/context/AuthContext.tsx))
  - User registration
  - User login/logout
  - Session persistence
  - Demo account: demo@oopsskin.com / demo123
  
- ✅ **LanguageContext** ([`src/app/context/LanguageContext.tsx`](src/app/context/LanguageContext.tsx))
  - Bilingual support (English/Arabic)
  - RTL/LTR automatic switching
  - 80+ translations
  - Persistent language preference

### 2. **Backend API** (Structure Ready - Not Connected)

#### Backend Files Created
- ✅ **Server Setup** ([`backend/server.js`](backend/server.js))
  - Express.js server
  - CORS configuration
  - JSON body parsing
  - Route registration
  - Port: 5000
  
- ✅ **Database Configuration** ([`backend/config/database.js`](backend/config/database.js))
  - MySQL connection pool
  - Environment variables support
  
- ✅ **Database Initialization** ([`backend/initDatabase.js`](backend/initDatabase.js))
  - Creates `oopsskin_db` database
  - Creates tables: products, orders, users, vouchers
  - Inserts 20 sample products
  - Bilingual product data (EN/AR)
  
- ✅ **API Routes**
  - Products API ([`backend/routes/products.js`](backend/routes/products.js))
    - GET /api/products (list with filters)
    - GET /api/products/:id
    - GET /api/products/category/:category
    - POST /api/products (create)
    - PUT /api/products/:id (update)
    - DELETE /api/products/:id
  
  - Orders API ([`backend/routes/orders.js`](backend/routes/orders.js))
    - GET /api/orders
    - GET /api/orders/:id
    - GET /api/orders/number/:orderNumber
    - POST /api/orders (create)
    - PUT /api/orders/:id/status
    - PUT /api/orders/:id
    - DELETE /api/orders/:id
    - GET /api/orders/stats/summary
  
  - Vouchers API ([`backend/routes/vouchers.js`](backend/routes/vouchers.js))
    - GET /api/vouchers
    - GET /api/vouchers/:id
    - POST /api/vouchers (create)
    - PUT /api/vouchers/:id (update)
    - DELETE /api/vouchers/:id
    - POST /api/vouchers/apply (validate and apply)
    - GET /api/vouchers/stats/summary

### 3. **Internationalization (i18n)**
- ✅ Complete English translations
- ✅ Complete Arabic translations
- ✅ RTL layout support for Arabic
- ✅ Language switcher in navbar (🌐 icon)
- ✅ Persistent language selection

### 4. **Product Categories**
```
├── FACE
│   ├── Foundation
│   ├── Powder & Setting Spray
│   ├── Primer
│   ├── Concealer & Corrector
│   └── Contour & Highlight
├── EYES
│   ├── Eyeshadow
│   ├── Eyebrows
│   ├── Eyeliner
│   ├── Mascara
│   └── Fake Eyelashes
├── LIPS
│   ├── Jelly Stained Lips
│   ├── Lip Gloss
│   ├── Lipstick
│   ├── Lip Liner
│   └── Lip Balm
├── CHEEK
│   ├── Blush
│   └── Bronzer
├── BRUSHES & TOOLS
│   ├── Brushes
│   └── Tools & Accessories
└── MINIS
    └── Mini Products
```

### 5. **Documentation Files**
- ✅ [`README.md`](README.md) - Project setup and overview
- ✅ [`CART_SYSTEM_GUIDE.md`](CART_SYSTEM_GUIDE.md) - Cart implementation details
- ✅ [`AUTHENTICATION_GUIDE.md`](AUTHENTICATION_GUIDE.md) - Auth system documentation
- ✅ [`LANGUAGE_SYSTEM_GUIDE.md`](LANGUAGE_SYSTEM_GUIDE.md) - i18n implementation
- ✅ [`VOUCHER_SYSTEM_GUIDE.md`](VOUCHER_SYSTEM_GUIDE.md) - Voucher feature documentation
- ✅ [`CPANEL_DEPLOYMENT.md`](CPANEL_DEPLOYMENT.md) - Deployment instructions
- ✅ [`backend/README.md`](backend/README.md) - Backend API documentation

---

## 📁 Project Structure

```
oopsskin/
├── src/
│   └── app/
│       ├── admin/                    # Admin panel pages
│       │   ├── page.tsx             # Dashboard
│       │   ├── products/page.tsx    # Products management
│       │   ├── orders/page.tsx      # Orders management
│       │   ├── vouchers/page.tsx    # Vouchers management
│       │   ├── customers/page.tsx   # Customers page (placeholder)
│       │   └── settings/page.tsx    # Settings page (placeholder)
│       ├── all-products/            # All products page
│       │   └── page.tsx
│       ├── best-sellers/            # Redirects to home#best-sellers
│       │   └── page.tsx
│       ├── cart/                    # Shopping cart
│       │   └── page.tsx
│       ├── checkout/                # Checkout process
│       │   └── page.tsx
│       ├── components/              # React components
│       │   ├── Navbar.tsx
│       │   ├── Footer.tsx
│       │   ├── HeroSection.tsx
│       │   ├── ProductCarousel.tsx
│       │   ├── CommunitySection.tsx
│       │   └── FeaturedBanner.tsx
│       ├── context/                 # React Context providers
│       │   ├── CartContext.tsx
│       │   ├── AuthContext.tsx
│       │   └── LanguageContext.tsx
│       ├── login/                   # Login page
│       │   └── page.tsx
│       ├── makeup/                  # Makeup category page
│       │   └── page.tsx
│       ├── new/                     # New products page
│       │   └── page.tsx
│       ├── packages/                # Packages page
│       │   └── page.tsx
│       ├── register/                # Registration page
│       │   └── page.tsx
│       ├── skincare/                # Skincare page
│       │   └── page.tsx
│       ├── layout.tsx               # Root layout
│       ├── page.tsx                 # Home page
│       └── globals.css              # Global styles
├── backend/                         # Backend API (Not connected yet)
│   ├── config/
│   │   └── database.js              # MySQL connection
│   ├── routes/
│   │   ├── products.js              # Products API routes
│   │   ├── orders.js                # Orders API routes
│   │   └── vouchers.js              # Vouchers API routes
│   ├── server.js                    # Express server
│   ├── initDatabase.js              # Database setup script
│   ├── package.json
│   ├── .env                         # Backend environment variables
│   └── README.md                    # Backend documentation
├── public/                          # Static assets
├── .github/                         # GitHub configurations
├── node_modules/                    # Frontend dependencies
├── .next/                           # Next.js build output
├── out/                             # Static export output (for cPanel)
├── next.config.ts                   # Next.js configuration
├── tailwind.config.ts               # Tailwind CSS configuration
├── tsconfig.json                    # TypeScript configuration
├── package.json                     # Frontend dependencies
├── .gitignore                       # Git ignore rules
├── .env.local                       # Frontend environment variables
└── README.md                        # Project documentation
```

---

## 🎯 Current Status

### ✅ Completed (100%)
1. **Frontend UI/UX**
   - All pages designed and implemented
   - Fully responsive design
   - Smooth animations and transitions
   - Professional styling with Tailwind CSS

2. **User Features**
   - Complete shopping flow (Browse → Cart → Checkout)
   - User authentication (Registration/Login)
   - Cart management with persistence
   - Voucher application (frontend mock)

3. **Admin Panel UI**
   - Dashboard with statistics
   - Products management interface
   - Orders management interface
   - Vouchers management interface

4. **Internationalization**
   - Full English support
   - Full Arabic support with RTL
   - Language switcher

5. **Backend Structure**
   - Express server setup
   - MySQL database schema
   - API routes defined
   - Sample data scripts

### ⚠️ Current Limitations
- Frontend runs with **mock/sample data**
- Backend APIs are **not connected** to frontend
- Admin panel CRUD operations are **UI only** (no database persistence)
- Orders are **not saved** to database
- User authentication uses **localStorage** only (no database validation)
- Vouchers use **hardcoded array** instead of database

---

## 🚀 Upcoming Work

### Phase 1: Backend Integration (Priority: HIGH)

#### 1.1 Database Setup
- [ ] Install MySQL on development machine
- [ ] Run database initialization script
  ```bash
  cd backend
  npm install
  npm run init-db
  ```
- [ ] Verify database tables created
- [ ] Insert sample data
- [ ] Test database connection

#### 1.2 Backend API Development
- [ ] Start backend server
  ```bash
  cd backend
  npm start
  ```
- [ ] Test all API endpoints with Postman/Thunder Client
- [ ] Add error handling and validation
- [ ] Implement API authentication (JWT tokens)
- [ ] Add request logging middleware
- [ ] Set up CORS for frontend-backend communication

#### 1.3 Frontend-Backend Connection
- [ ] Create API service layer ([`src/app/services/api.ts`](src/app/services/api.ts))
- [ ] Replace mock data with API calls
- [ ] Update environment variables with backend URL
- [ ] Implement error handling for API calls
- [ ] Add loading states for all API requests

### Phase 2: Feature Implementation (Priority: HIGH)

#### 2.1 Products Management
- [ ] **Frontend Updates:**
  - [ ] Fetch products from API instead of hardcoded array
  - [ ] Implement real-time search
  - [ ] Add pagination
  - [ ] Connect category filtering to API
  - [ ] Add loading skeletons

- [ ] **Admin Panel:**
  - [ ] Connect product creation form to POST /api/products
  - [ ] Connect product editing to PUT /api/products/:id
  - [ ] Connect product deletion to DELETE /api/products/:id
  - [ ] Add image upload functionality
  - [ ] Implement product stock management

#### 2.2 Orders Management
- [ ] **Checkout Process:**
  - [ ] Save orders to database on checkout
  - [ ] Generate unique order numbers
  - [ ] Send order confirmation emails
  - [ ] Update product stock after order

- [ ] **Admin Panel:**
  - [ ] Fetch orders from database
  - [ ] Implement order status updates
  - [ ] Add order search and filtering
  - [ ] Generate order reports
  - [ ] Print order invoices

#### 2.3 Authentication System
- [ ] **Backend:**
  - [ ] Implement JWT-based authentication
  - [ ] Create user registration API
  - [ ] Create user login API
  - [ ] Add password hashing (bcrypt)
  - [ ] Implement session management
  - [ ] Add password reset functionality

- [ ] **Frontend:**
  - [ ] Connect registration form to API
  - [ ] Connect login form to API
  - [ ] Store JWT tokens securely
  - [ ] Implement auto-logout on token expiry
  - [ ] Add "Remember Me" functionality
  - [ ] Implement password reset flow

#### 2.4 Vouchers System
- [ ] **Frontend:**
  - [ ] Connect voucher application to API
  - [ ] Real-time voucher validation
  - [ ] Display remaining voucher uses
  - [ ] Show voucher expiry warnings

- [ ] **Admin Panel:**
  - [ ] Connect voucher CRUD to API
  - [ ] Add usage analytics
  - [ ] Implement bulk voucher generation
  - [ ] Add voucher expiration notifications

### Phase 3: Advanced Features (Priority: MEDIUM)

#### 3.1 User Dashboard
- [ ] Create user profile page
- [ ] Order history page
- [ ] Track order status
- [ ] Wishlist functionality
- [ ] Saved addresses

#### 3.2 Product Features
- [ ] Product reviews and ratings
- [ ] Product recommendations
- [ ] Related products
- [ ] Product comparison
- [ ] Recently viewed products

#### 3.3 Admin Analytics
- [ ] Sales reports
- [ ] Customer analytics
- [ ] Product performance metrics
- [ ] Revenue tracking
- [ ] Inventory alerts

#### 3.4 Additional Features
- [ ] Email notifications (order confirmations, shipping updates)
- [ ] SMS notifications
- [ ] Social media sharing
- [ ] Product filtering (price range, brand, rating)
- [ ] Advanced search with suggestions

### Phase 4: Testing & Optimization (Priority: MEDIUM)

#### 4.1 Testing
- [ ] Unit tests for components
- [ ] Integration tests for API
- [ ] End-to-end testing
- [ ] Cross-browser testing
- [ ] Mobile responsiveness testing
- [ ] Performance testing

#### 4.2 Optimization
- [ ] Image optimization
- [ ] Code splitting
- [ ] Lazy loading
- [ ] Caching strategies
- [ ] SEO optimization
- [ ] Accessibility improvements

### Phase 5: Deployment (Priority: HIGH)

#### 5.1 Frontend Deployment (cPanel)
- [ ] Build static export
  ```bash
  npm run build
  ```
- [ ] Test static build locally
- [ ] Upload `out/` folder to cPanel
- [ ] Configure .htaccess for routing
- [ ] Set up custom domain
- [ ] Configure SSL certificate
- [ ] Test production build

#### 5.2 Backend Deployment
- [ ] **Option A: VPS/Cloud Server**
  - [ ] Set up Node.js server (DigitalOcean/AWS/Heroku)
  - [ ] Install MySQL
  - [ ] Configure environment variables
  - [ ] Set up PM2 for process management
  - [ ] Configure Nginx reverse proxy
  - [ ] Set up SSL certificate

- [ ] **Option B: cPanel with Node.js Support**
  - [ ] Check if cPanel supports Node.js apps
  - [ ] Deploy backend to cPanel
  - [ ] Configure MySQL database in cPanel
  - [ ] Set up cron jobs if needed

#### 5.3 Post-Deployment
- [ ] Update frontend API URLs to production backend
- [ ] Test all features in production
- [ ] Set up monitoring and logging
- [ ] Create backup strategy
- [ ] Document deployment process

### Phase 6: Marketing & Launch (Priority: LOW)

#### 6.1 Content
- [ ] Add real product images
- [ ] Write product descriptions
- [ ] Create about page
- [ ] Add terms and conditions
- [ ] Add privacy policy
- [ ] Create FAQ page

#### 6.2 SEO & Marketing
- [ ] Set up Google Analytics
- [ ] Configure meta tags
- [ ] Create sitemap
- [ ] Submit to search engines
- [ ] Social media integration
- [ ] Email marketing setup

---

## 📝 API Documentation

### Base URLs
- **Development**: `http://localhost:5000/api`
- **Production**: `https://yourdomain.com/api`

### Products API

#### Get All Products
```http
GET /api/products
Query Parameters:
  - search (string): Search by name or description
  - category (string): Filter by category
  - min_price (number): Minimum price
  - max_price (number): Maximum price
  - sort (string): Sort field (price, name, created_at)
  - order (string): Sort order (asc, desc)
  - limit (number): Results per page (default: 20)
  - offset (number): Pagination offset
```

#### Get Product by ID
```http
GET /api/products/:id
```

#### Get Products by Category
```http
GET /api/products/category/:category
```

#### Create Product (Admin)
```http
POST /api/products
Body: {
  "name": "Product Name",
  "name_ar": "اسم المنتج",
  "description": "Product description",
  "description_ar": "وصف المنتج",
  "category": "Foundation",
  "category_ar": "كريم اساس",
  "price": 48.00,
  "original_price": 60.00,
  "stock": 100,
  "colors": ["#FFE4E1", "#F5DEB3"],
  "images": ["image1.jpg", "image2.jpg"],
  "rating": 4.9,
  "badge": "NEW",
  "discount": "20%"
}
```

#### Update Product (Admin)
```http
PUT /api/products/:id
Body: (same as create)
```

#### Delete Product (Admin)
```http
DELETE /api/products/:id
```

### Orders API

#### Get All Orders
```http
GET /api/orders
Query Parameters:
  - status (string): Filter by status
  - customer_email (string): Filter by email
  - start_date (date): Start date filter
  - end_date (date): End date filter
  - limit, offset: Pagination
```

#### Get Order by ID
```http
GET /api/orders/:id
```

#### Get Order by Number
```http
GET /api/orders/number/:orderNumber
```

#### Create Order
```http
POST /api/orders
Body: {
  "customer_name": "John Doe",
  "customer_email": "john@example.com",
  "customer_phone": "1234567890",
  "customer_address": "123 Main St",
  "customer_city": "Cairo",
  "customer_postal_code": "12345",
  "delivery_notes": "Ring doorbell",
  "items": [
    {
      "id": 1,
      "name": "Product Name",
      "price": 48.00,
      "quantity": 2,
      "color": "#FFE4E1"
    }
  ],
  "subtotal": 96.00,
  "shipping": 10.00,
  "discount": 0.00,
  "voucher_code": "",
  "total": 106.00,
  "payment_method": "cash_on_delivery"
}
```

#### Update Order Status
```http
PUT /api/orders/:id/status
Body: {
  "status": "processing" | "completed" | "cancelled"
}
```

#### Get Order Statistics
```http
GET /api/orders/stats/summary
Response: {
  "totalOrders": 150,
  "pendingOrders": 25,
  "processingOrders": 40,
  "completedOrders": 80,
  "cancelledOrders": 5,
  "totalRevenue": 25600.50
}
```

### Vouchers API

#### Get All Vouchers
```http
GET /api/vouchers
Query Parameters:
  - status (string): Filter by status (active, inactive, expired)
```

#### Get Voucher by ID
```http
GET /api/vouchers/:id
```

#### Create Voucher
```http
POST /api/vouchers
Body: {
  "code": "WELCOME10",
  "description": "10% off first order",
  "discount_type": "percentage" | "fixed",
  "discount_value": 10,
  "minimum_purchase": 50,
  "maximum_discount": 50,
  "usage_limit": 100,
  "expires_at": "2024-12-31",
  "status": "active"
}
```

#### Apply Voucher
```http
POST /api/vouchers/apply
Body: {
  "code": "WELCOME10",
  "order_total": 150.00
}
Response: {
  "valid": true,
  "voucher": {...},
  "discount": 15.00
}
```

#### Update Voucher
```http
PUT /api/vouchers/:id
Body: (same as create)
```

#### Delete Voucher
```http
DELETE /api/vouchers/:id
```

---

## 🚀 Deployment Guide

### Prerequisites
- Node.js 18+ installed
- MySQL database
- cPanel hosting account (or VPS)
- Domain name

### Frontend Deployment to cPanel

1. **Build Static Export**
   ```bash
   npm run build
   ```

2. **Upload to cPanel**
   - Compress the `out/` folder
   - Upload via cPanel File Manager to `public_html/`
   - Extract files

3. **Configure Routing**
   Create `.htaccess` in `public_html/`:
   ```apache
   RewriteEngine On
   RewriteBase /
   
   # Handle client-side routing
   RewriteCond %{REQUEST_FILENAME} !-f
   RewriteCond %{REQUEST_FILENAME} !-d
   RewriteRule ^ index.html [L]
   
   # Enable gzip compression
   <IfModule mod_deflate.c>
     AddOutputFilterByType DEFLATE text/html text/plain text/xml text/css text/javascript application/javascript
   </IfModule>
   ```

4. **Set Environment Variables**
   Create `.env.production`:
   ```env
   NEXT_PUBLIC_API_URL=https://api.yourdomain.com
   ```

### Backend Deployment

#### Option A: VPS/Cloud (Recommended)

1. **Server Setup**
   ```bash
   # Install Node.js
   curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
   sudo apt-get install -y nodejs
   
   # Install MySQL
   sudo apt-get install mysql-server
   
   # Install PM2
   sudo npm install -g pm2
   ```

2. **Deploy Backend**
   ```bash
   # Clone repository
   git clone https://github.com/Sharaf25/Oopsskin.git
   cd Oopsskin/backend
   
   # Install dependencies
   npm install
   
   # Set up environment
   cp .env.example .env
   nano .env  # Edit with production values
   
   # Initialize database
   npm run init-db
   
   # Start with PM2
   pm2 start server.js --name oopsskin-api
   pm2 save
   pm2 startup
   ```

3. **Configure Nginx**
   ```nginx
   server {
       listen 80;
       server_name api.yourdomain.com;
       
       location / {
           proxy_pass http://localhost:5000;
           proxy_http_version 1.1;
           proxy_set_header Upgrade $http_upgrade;
           proxy_set_header Connection 'upgrade';
           proxy_set_header Host $host;
           proxy_cache_bypass $http_upgrade;
       }
   }
   ```

4. **Set Up SSL**
   ```bash
   sudo certbot --nginx -d api.yourdomain.com
   ```

#### Option B: cPanel with Node.js

1. Check if your cPanel supports Node.js apps
2. Create Node.js application in cPanel
3. Upload backend files
4. Configure environment variables
5. Start application

### Database Setup

```sql
-- Create database
CREATE DATABASE oopsskin_db;

-- Run initialization script
cd backend
npm run init-db
```

### Post-Deployment Checklist

- [ ] Frontend loads correctly
- [ ] All pages are accessible
- [ ] API endpoints respond
- [ ] Database connection works
- [ ] User can register/login
- [ ] Products display correctly
- [ ] Cart functionality works
- [ ] Checkout process completes
- [ ] Admin panel is accessible
- [ ] SSL certificate is active
- [ ] Domain points to correct server

---

## 📧 Support & Contact

### Development Team
- **Developer**: Mostafa Amer
- **Email**: mostafaamrmedia@gmail.com
- **GitHub**: https://github.com/Sharaf25

### Resources
- **Repository**: https://github.com/Sharaf25/Oopsskin
- **Documentation**: See individual guide files
- **Issues**: Use GitHub Issues for bug reports

---

## 📄 License

This project is proprietary and confidential.

---

## 🔄 Version History

### Version 1.0.0 (Current)
- ✅ Complete frontend UI
- ✅ User authentication (localStorage)
- ✅ Shopping cart system
- ✅ Admin panel UI
- ✅ Bilingual support
- ✅ Backend API structure
- ⏳ Backend integration pending

### Upcoming Version 1.1.0
- Backend API integration
- Real database persistence
- JWT authentication
- Image uploads
- Email notifications

---

**Last Updated**: February 15, 2024
**Status**: Frontend Complete | Backend Integration In Progress
