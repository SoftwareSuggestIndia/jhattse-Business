# Jhattse Business

Jhattse Business is an all-in-one restaurant operating system built for the Indian market — more than a billing app, it removes "tablet chaos" and gives restaurants a single source of truth for orders, inventory, payments and customer engagement.

> Enterprise features, small-business friendly pricing. Works offline, syncs to cloud, and integrates with major aggregators & payment systems.

---

## Table of Contents

- [Key Highlights](#key-highlights)  
- [Features](#features)  
- [Integrations](#integrations)  
- [Pricing](#pricing)  
- [Why Jhattse?](#why-jhattse)  
- [Quick Start](#quick-start)  
- [Deployment & Installation](#deployment--installation)  
- [Configuration & Integrations](#configuration--integrations)  
- [Screenshots & Assets](#screenshots--assets)  
- [Contributing](#contributing)  
- [Roadmap](#roadmap)  
- [FAQ](#faq)

---

## Key Highlights

- Unified aggregator order capture (Zomato, Swiggy, Shopify) directly into POS/KDS.  
- Recipe/BOM-level inventory consumption for accurate food cost analysis.  
- WhatsApp Business API + SMS/Email for bills, order updates and promos.  
- Table QR ordering for contactless dining and reduced staff workload.  
- Offline-first design: continues operating during connectivity loss, syncs when online.  
- Multi-outlet management dashboard for real-time oversight.

---

## Features

- POS with configurable menu, modifiers, taxes and discounts  
- Kitchen Display System (KDS) with order routing & prep timers  
- Unified Aggregator Sync (Zomato, Swiggy, Shopify)  
- Bill of Materials (BOM) / recipe-level inventory consumption & wastage tracking  
- Table QR ordering and digital menus  
- WhatsApp Business API integration for e-bills & updates  
- GST-compliant invoicing & exportable reports (GSTR-1, P&L, Sales Register)  
- Loyalty programs, coupons and promotions engine  
- Role-based users and staff management  
- Multi-outlet real-time reporting dashboard  
- Thermal printer support (ESC/POS) and hardware-agnostic operation  
- Offline-first data store with conflict resolution and cloud sync

---

## Integrations

| Category | Platforms / Examples |
| --- | --- |
| Food Aggregators | Zomato, Swiggy (Direct API Sync) |
| Marketplaces | Shopify, Amazon, Flipkart, ONDC (planned) |
| Payments | UPI, PhonePe, Paytm, major payment gateways |
| Communication | WhatsApp Business API, SMS Gateways, Email |
| Hardware | Thermal Printers (ESC/POS), Android/iOS tablets, desktops |

---

## Pricing (India)

- Basic — ₹4,799 + GST / year  
  - Order management, QR menu, basic inventory

- Standard / Super — ₹7,999 + GST / year  
  - All Basic features + Table management, Loyalty, Advanced customization

- Free Trial — 7 days (no credit card required)

Contact sales for enterprise/multi-outlet pricing and custom SLAs.

---

## Why Jhattse?

1. Offline-first stability for locations with unreliable internet.  
2. Eliminates manual re-entry — aggregator orders flow straight into KDS/POS.  
3. Accurate food-costing (BOM) reduces waste and improves margins.  
4. GST autopilot: invoice generation & export-ready tax reports.  
5. Centralized multi-outlet management for chains and franchise operations.

---

## Quick Start

1. Sign up for a trial or request a demo via the website/contact.  
2. Create your first Outlet and Menu.  
3. Define recipes and BOMs for each menu item (grams, units).  
4. Connect aggregator accounts (Zomato, Swiggy) under Integrations.  
5. Configure payment gateways and WhatsApp Business API credentials.  
6. Install POS/KDS on devices and set up printers.

---

## Deployment & Installation

Depending on your preference, Jhattse can be deployed in different modes:

- Cloud-hosted (SaaS): Managed by Jhattse — easiest for most customers.  
- On-premises / Self-hosted: For enterprises requiring local control.  
- Hybrid: Local offline operation with secure cloud sync.

Recommended system components:
- Devices: Android tablets, iPads, desktops
- Network: Local LAN for printers + internet for sync & aggregator APIs
- Printer: ESC/POS compatible thermal printers

(If you maintain deployment scripts or Docker files here, add links and commands to this section.)

---

## Configuration & Integrations

- Aggregator integration flow:
  1. Obtain API credentials from Zomato/Swiggy/Shopify.
  2. Add credentials in the Integrations page.
  3. Map aggregator menu items to local menu SKUs.
  4. Configure routing rules for printers/KDS.

- WhatsApp Business API:
  - Provide WhatsApp Business account and phone number.
  - Configure message templates for bills, order status and promos.

- Payment Gateways:
  - Provide merchant credentials.
  - Configure callback/notification URLs.

(Add specific screenshots and step-by-step guide once credentials page UI is available.)

---

## Screenshots & Assets

Add visual assets under `/assets`:
- POS main screen
- KDS screen
- Inventory & BOM page
- Multi-outlet dashboard

Include image references here once assets are added:

```markdown
![POS Screenshot](assets/pos.png)
![KDS Screenshot](assets/kds.png)
```

---

## Contributing

We welcome contributions. Please follow these steps:

1. Fork the repository.  
2. Create a branch: `git checkout -b feature/your-feature`.  
3. Commit your changes with clear messages.  
4. Open a Pull Request describing the change, testing steps, and screenshots if UI changes.  

Code style, testing and release guidelines:
- Follow existing linting and formatting rules.  
- Add unit/integration tests for new functionality.  
- Ensure sensitive credentials are not committed (use environment variables / secrets).

---

## Roadmap

Planned and high-priority items:
- ONDC marketplace integration  
- Deeper marketplace-inventory reconciliation (Amazon/Flipkart)  
- Advanced predictive analytics & demand forecasting  
- Role-based access with granular permissions  
- Additional payment gateway integrations & settlement reporting

---

## FAQ

Q: Does Jhattse work offline?  
A: Yes — core POS and KDS functions work offline and sync to the cloud when connectivity returns.

Q: How do aggregator orders appear?  
A: Orders from Zomato/Swiggy are fetched via direct API sync and are routed to the POS/KDS automatically (no manual entry).

Q: Is Jhattse GST-compliant?  
A: Yes — it generates GST-compliant invoices and exportable tax reports (GSTR-1 ready).
Here is a comprehensive FAQ guide for **Jhattse Business Restaurant Software**, designed to answer the most common questions from restaurant owners, cloud kitchen operators, and cafe managers.

---

### **General Questions**

**Q1: What is Jhattse Business?**
Jhattse Business is an all-in-one GST billing and restaurant management software. It acts as a central "Operating System" for your business, combining billing, inventory, table management, and delivery aggregator integrations into a single dashboard.

**Q2: What types of food businesses is this software suitable for?**
It is designed for a wide range of establishments, including:

* Fine Dining & Casual Dining Restaurants
* Cloud Kitchens
* Cafes and Bakeries
* QSRs (Quick Service Restaurants)
* Hotels (via the PMS suite)
* Food Trucks and Pizzerias

**Q3: Does the software work offline?**
Yes. Jhattse features a **Hybrid-Cloud** model. You can continue taking orders and printing bills even if your internet goes down. Once the connection is restored, the data automatically syncs to the cloud.

---

### **Features & Functionality**

**Q4: Can I manage Zomato and Swiggy orders from one screen?**
Absolutely. One of Jhattse’s standout features is its **Direct Aggregator Integration**. Online orders flow directly into your POS, where you can accept them and automatically print Kitchen Order Tickets (KOTs) without using separate tablets.

**Q5: How does the Inventory & Recipe Management (BOM) work?**
Jhattse uses a **Bill of Materials (BOM)** system. You can link raw ingredients to menu items. For example, if you sell a "Paneer Pizza," the system will automatically deduct the specific amount of flour, cheese, and paneer from your stock in real-time.

**Q6: Does it support QR-code-based ordering?**
Yes. You can generate unique QR codes for each table. Customers can scan the code to view your digital menu, place orders, and even make payments, which significantly reduces the workload for your waitstaff.

**Q7: Can I send bills via WhatsApp?**
Yes. Jhattse is a leader in **WhatsApp Integration**. Instead of just paper bills, you can send automated digital invoices, order confirmations, and even promotional offers directly to a customer’s WhatsApp number.

---

### **Pricing & Plans**

**Q8: How much does Jhattse Business cost?**
The pricing is designed to be highly affordable for Indian SMBs:

* **Basic Plan:** Starting at **₹4,799 + 18% GST per year** (Best for small cafes/QSRs).
* **Super/Standard Plan:** Approximately **₹7,999 + 18% GST per year** (Includes advanced features like Table Management and Loyalty Programs).

**Q9: Is there a free trial available?**
Yes, Jhattse typically offers a **7-day free trial** so you can explore all the features before making a commitment.

**Q10: Are there any hidden setup fees?**
No. There are no setup fees for the web-based plans. You only pay the annual subscription fee. If you require physical on-site installation by a technician, a small one-time fee may apply.

---

### **Technical & Compatibility**

**Q11: What devices can I run the software on?**
Jhattse is **Hardware Agnostic**, meaning it works on:

* Windows Laptops and Desktops
* Android Tablets and Smartphones
* iPhones and iPads (iOS)
* Web Browsers (Chrome/Edge)

**Q12: How many users can access the software under one license?**
Standard plans usually support up to **5 users** per subscription, with customizable roles (e.g., Admin, Manager, Biller, Captain) to control access permissions.

**Q13: Is the software GST compliant?**
Yes. It automatically calculates GST, generates GSTR-compliant reports, and supports **E-Invoicing and E-Way Bills** for larger operations.

---

### **Support**

**Q14: How do I get help if the software stops working?**
Jhattse provides **24/7 Customer Support** via phone, email, and WhatsApp. They offer support in multiple languages, including English and Hindi.

**Q15: Can I manage multiple restaurant outlets?**
Yes. Jhattse is built for scalability. You can manage and monitor multiple outlets from a single "Master Dashboard," allowing you to see consolidated sales and inventory reports across all locations.

---

For demos, sales or support:
- Email: contact@jhattse.com  
- Website: [Jhattse Business](https://business.jhattse.com "Best Restaurant Software in India")  
- Sales: contact@jhattse.com

---
