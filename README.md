# 🌱 **Nourish Laredo — Nonprofit Food Aid Platform**

### *React Frontend · Django REST API · PostgreSQL · Figma Prototype*

Nourish Laredo is a full-stack web application built to support a youth-led nonprofit organization in Laredo, Texas.
The platform helps coordinate meal drives, food distribution programs, youth volunteer efforts, community partnerships, and donations.

This project demonstrates end-to-end software engineering: requirements gathering, prototyping, UX design, API architecture, and full-stack implementation.

---

# 📌 **Table of Contents**

1. Overview
2. Features
3. Tech Stack
4. Architecture
5. Figma Prototype
6. Backend: Django REST
7. Frontend: React
8. Database Models
9. Documentation
10. Project Setup
11. Future Enhancements
12. License

---

# 🧭 **Overview**

Nourish Laredo is a community-driven nonprofit dedicated to reducing food insecurity in Laredo, TX.
This platform gives the organization a modern, scalable system for:

* Sharing its mission and programs
* Highlighting impact
* Recruiting and managing youth volunteers
* Partnering with local businesses
* Accepting one-time and monthly donations
* Listing and managing events
* Communicating with the public

The project is built to be maintainable, mobile-friendly, accessible, and easy for the nonprofit to grow with.

---

# 🚀 **Features**

### **🖥 Public Website**

* Homepage with mission, CTAs, and impact metrics
* About page with origin story, mission, vision, and youth-led identity
* Programs page (Meal Drives, Food Distribution, Youth Volunteering)
* Get Involved page with volunteer roles and signup form
* Partners page with partner directory + inquiry modal
* Contact page with contact form and social links
* Events system (upcoming, past events, detail pages)
* Donation page (one-time or monthly giving)

### **📦 Backend Functionality**

* API endpoints for all content types
* Volunteer application management
* Event volunteer sign-ups
* Partner inquiry workflow
* Donation logging (Stripe-ready)
* Django Admin interface for data management

### **🎨 Frontend Functionality**

* Fully responsive React UI
* Component-driven architecture
* API integration with DRF
* Smooth navigation & modals
* Clean, youth-friendly branding

---

# ⚙️ **Tech Stack**

### **Frontend**

* React (Vite or CRA)
* JavaScript/TypeScript
* CSS / Styled Components / Tailwind (optional)

### **Backend**

* Django
* Django REST Framework
* PostgreSQL
* Django Admin
* (Stripe integration planned)

### **Tools**

* Figma (UX/UI design + prototyping)
* GitHub / Git
* Postman or Thunder Client for API testing

---

# 🏗 **Architecture**

```
frontend/          → React application (UI)
backend/
  ├── nourish_backend/   → Django project (settings, routing)
  └── core/              → Django app (models, views, serializers)

PostgreSQL         → Relational database
Django Admin       → Content management
React              → Public-facing site
```

---

# 🎨 **Figma Prototype**

The complete high-fidelity prototype used for planning and development:

👉 **Figma Prototype Link** (replace with actual link)

Includes all pages:

* Home
* About
* Programs
* Get Involved
* Partners
* Contact
* Donate
* (Events — backend-ready for future UI)

---

# 🗄 **Backend: Django REST**

The backend provides API endpoints for:

* Programs
* Events
* Partners
* Volunteers
* Partner Inquiries
* Contact Messages
* Newsletter Subscriptions
* Donations
* Stories / Testimonials

It uses:

* Django REST Framework serializers
* Viewsets / routers
* PostgreSQL models
* Django Admin for data editing
* Token/Auth-ready structure for future admin dashboard

---

# 🎛 **Frontend: React**

The frontend implements the full Figma prototype using:

* Reusable components
* State management
* Form validation
* API calls to Django REST
* Responsive layout (mobile-first)
* Smooth modals and UI interactions

---

# 🗃 **Database Models**

Includes models for:

* Program
* Event, EventCategory, EventVolunteerSignup
* Partner, PartnerCategory, PartnerInquiry
* VolunteerRole, VolunteerApplication
* ContactMessage
* NewsletterSubscription
* Donation
* Story

Designed for scalability, clean relationships, and admin usability.

---

# 📚 **Documentation**

This project includes full software engineering documentation:

* Project Overview / Charter
* Requirements Specification
* User Stories & Epics (Product Backlog)
* Acceptance Criteria
* Entity Relationship Models
* API Routes & Data Models
* Sprint Plan
* Figma Design System

---

# 🛠 **Project Setup**

### **Backend Setup**

```
cd backend
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows

pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

### **Frontend Setup**

```
cd frontend
npm install
npm run dev
```

---

# 🔮 **Future Enhancements**

* Admin dashboard (React or Django Admin customization)
* Automated volunteer scheduling and reminders
* Donor portal with recurring payment management
* SMS alerts for events or urgent meal drives
* Full events page UI matching backend functionality
* Multi-language support (English/Spanish)

---

# 📄 **License**

This project is created for the Nourish Laredo nonprofit organization and for educational/portfolio use.
Contact the project owner for reuse permissions.
