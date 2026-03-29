# 👟 Bubu Lifestyle - Full-Stack Omnichannel ERP, E-Commerce & POS Ecosystem

> 🔒 **Confidentiality Notice:** The source code is private to protect proprietary business logic and enterprise data. This repository serves as a technical showcase for the end-to-end architecture, omnichannel fulfillment, and marketing automation I engineered.

## 🚀 System Overview
Bubu Lifestyle is a production-grade, full-stack retail solution for a premium footwear brand. I architected and developed the entire ecosystem, including a high-conversion client-side e-commerce platform, a comprehensive Enterprise Admin Panel, and a multi-outlet POS system with real-time inventory synchronization and a custom loyalty engine.

## 🛠️ Tech Stack & Infrastructure
* **Frontend:** React (Vite), Tailwind CSS, Shadcn UI.
* **Backend & Auth:** Supabase (PostgreSQL) with **Custom Auth Hooks** for passwordless OTP.
* **Integrations:** BulkSMSBD (OTP/Alerts), Steadfast API (Logistics), BDCourier (Fraud Check), SSLCommerz (Payments).
* **Infrastructure:** Cloudinary (Media), Vercel (Hosting/Edge Runtime).

---

## 🧠 Full-Stack Engineering Highlights

### 1. High-Conversion E-Commerce Frontend (Client Side)
* **Frictionless Checkout:** Optimized 1-click variant selection and a simplified COD-only checkout flow for maximum conversion.
* **Passwordless Authentication:** Secure login via **Google OAuth** or **Phone OTP**. Developed a custom Supabase Auth Hook to handle BulkSMSBD OTP delivery.
* **Customer Dashboard:** Users can manage multiple addresses (Home/Work/Office), track real-time order status, and view detailed order history.
* **Abandoned Cart Recovery (Auto-Capture):** Engineered a high-impact feature that auto-saves customer data (Name/Phone) as soon as the 11-digit mobile number is typed, enabling sales recovery for incomplete checkouts.

### 2. Enterprise Admin Panel & Logistics
* **Omnichannel Order Management:** A unified dashboard to handle web orders and manual entries for social media (WhatsApp/FB) sales.
* **Real-time Fraud Detection:** Integrated **BDCourier API** to display courier fraud reports for each customer instantly, aiding in COD risk assessment.
* **Smart Fulfillment:** Admins can select fulfillment sources (Outlets) based on live stock levels. Online stock is a real-time aggregate of all physical locations.
* **Product & Catalog Management:** Features automated barcode generation, SKU management, and AI-assisted SEO metadata generation for every product.

### 3. Advanced Multi-Outlet POS & Loyalty Engine
* **PIN-Protected Operations:** Security-first approach for sensitive actions like Exchanges, Refunds, and Due Payments requiring a Branch Manager's unique PIN.
* **Custom Loyalty Program:** Automated rewards engine (100 BDT = 1 Point). Points (valued at 0.75 BDT) are redeemable for discounts or full purchases after reaching a 100-point threshold.
* **Inter-Outlet Inventory Transfer:** A robust module to manage and track stock movements between different physical branches.

### 4. Technical SEO & Data Growth Engine
* **Precision Tracking:** Full implementation of **Meta Conversions API (CAPI)** and **GA4** with event deduplication to ensure 100% data accuracy.
* **SEO Excellence:** Optimized `robots.txt` for security and dynamic `sitemap.xml` generation for real-time indexing in Google Search Console.
* **Media Optimization:** All high-resolution product images are hosted on **Cloudinary**, ensuring lightning-fast load times.

---

## 📊 Business Intelligence
The system generates automated **P&L Reports (PDF)**, accounting for Sales, Returns, Exchanges, Dues, and Branch Expenses (with receipt upload capability) to provide a clear view of net profit.

## 🤝 Let's Connect
I build complex, mission-critical systems that drive business revenue.
* 🌐 **Portfolio:** [shahnabil.com](https://shahnabil.com)
* ✉️ **Email:** hello@shahnabil.com
