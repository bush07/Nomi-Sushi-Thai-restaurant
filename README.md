# 🍣 Nomi Sushi & Thai — Restaurant Website

A modern, responsive restaurant website for **Nomi Sushi & Thai**, built with Next.js, TypeScript, Tailwind CSS, and Framer Motion.

The project focuses on creating a polished digital restaurant experience with interactive menus, gallery browsing, multilingual support, dynamic opening hours, responsive layouts, animations, and mobile-friendly interactions.

🌐 **Live Demo:** https://swedish-sushi.vercel.app/

---

## ✨ Features

### 🕐 Dynamic Opening Hours

- Real-time restaurant opening status
- Swedish timezone support (`Europe/Stockholm`)
- Displays whether the restaurant is currently open or closed
- Shows upcoming opening/closing information
- Automatically refreshes the displayed status

### 🍱 Interactive Menu

- Categorized restaurant menu
- Responsive menu cards
- Food imagery and detailed menu information
- Reusable menu components
- Mobile-friendly browsing experience

### 🖼️ Interactive Gallery

- Responsive image gallery
- Full-screen lightbox experience
- Keyboard navigation
- Touch/swipe support on mobile
- Image navigation controls

### 🌍 English & Swedish Language Support

- English and Swedish interface
- Persistent language selection
- Centralized translation system
- React Context-based language management
- Easy-to-extend translation structure

### 🎨 Modern Glassmorphism UI

- Frosted glass visual effects
- Gradient backgrounds
- Layered shadows
- Rounded cards and interactive elements
- Modern restaurant-focused visual design

### ✨ Animations & Micro-interactions

- Framer Motion animations
- Scroll-based reveal effects
- Smooth page transitions
- Hover interactions
- Animated backgrounds
- Responsive motion behavior

### 📱 Responsive Design

Designed for:

- 📱 Mobile
- 📲 Tablet
- 💻 Desktop
- 🖥️ Large screens

The interface adapts navigation, menus, galleries, CTAs, and interactive components to different screen sizes.

### 🚀 Progressive Web App Features

- Web app manifest
- Install prompt UI
- Mobile-friendly experience
- App shortcuts
- Local storage based preferences

### ⚡ Floating Action System

Quick access to important restaurant actions through responsive floating controls.

Includes actions such as:

- Ordering
- Calling
- Contacting
- Reservations
- Navigation/directions

### 🔔 Toast Notifications

Uses Sonner for contextual user feedback such as:

- Copying contact information
- Order actions
- User interactions
- Confirmation messages

### 📩 Contact & Reservation Experience

- Contact information
- Reservation form
- FAQ section
- Newsletter section
- Restaurant location information
- Mobile-friendly contact actions

### 📝 Blog Pages

The project also includes reusable blog components and pages for:

- Blog listing
- Blog details
- Sidebar
- Related posts
- Social sharing
- Tags

---

## 🛠️ Tech Stack

### Frontend

- **Next.js 15**
- **React 19**
- **TypeScript**
- **Tailwind CSS 4**
- **Framer Motion**

### UI & Components

- Radix UI
- Lucide React
- Class Variance Authority
- Tailwind Merge
- Yet Another React Lightbox

### State & UX

- React Context API
- Local Storage
- Next Themes
- Sonner

### Development Tools

- ESLint
- Prettier
- PostCSS
- Autoprefixer
- Vercel

---

## 🏗️ Project Structure

```text
Nomi-Sushi-Thai-restaurant/
│
├── public/
│   └── Static assets and images
│
├── src/
│   ├── app/
│   │   ├── about/
│   │   ├── blog/
│   │   ├── blog-details/
│   │   ├── blog-sidebar/
│   │   ├── contact/
│   │   ├── gallery/
│   │   ├── menu/
│   │   ├── signin/
│   │   ├── signup/
│   │   └── page.tsx
│   │
│   ├── components/
│   │   ├── About/
│   │   ├── Blog/
│   │   ├── Contact/
│   │   ├── Header/
│   │   ├── home/
│   │   ├── layout/
│   │   ├── menu/
│   │   ├── navigation/
│   │   ├── gallery/
│   │   └── ui/
│   │
│   ├── config/
│   │   └── site configuration
│   │
│   ├── data/
│   │   ├── gallery.ts
│   │   ├── homeImages.ts
│   │   ├── menu.ts
│   │   └── menuImages.ts
│   │
│   ├── lib/
│   │   ├── i18n/
│   │   ├── openingHours.ts
│   │   └── toast.ts
│   │
│   ├── types/
│   │   └── TypeScript interfaces
│   │
│   └── styles/
│       └── Global styles
│
├── .env.local.example
├── .gitignore
├── next.config.js
├── package.json
├── tailwind.config.ts
├── tsconfig.json
└── README.md
