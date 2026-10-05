# 🍣 Nomi Sushi & Thai — Restaurant Web Platform

A modern, responsive restaurant web application built with **Next.js, TypeScript, React, and Tailwind CSS**, designed to provide a premium digital dining experience across desktop, tablet, and mobile devices.

The project focuses on modern UI/UX, reusable components, responsive layouts, restaurant information, menu browsing, gallery experiences, online ordering flows, and production-ready frontend architecture.

---

## ✨ Overview

**Nomi Sushi & Thai** is a full-featured restaurant website designed to provide customers with a seamless way to:

- Explore the restaurant and its offerings
- Browse food menus and categories
- View restaurant images through an interactive gallery
- Check opening hours and restaurant status
- Access contact and location information
- Navigate to online ordering
- Switch between supported languages
- Use the website comfortably on mobile and desktop
- Install the website as a Progressive Web App (PWA)

The project combines a polished visual design with reusable architecture and interactive frontend features.

---

## 🎯 Problem & Solution

### Problem

Traditional restaurant websites can often provide a limited digital experience:

- Static restaurant information
- Poor mobile responsiveness
- Difficult menu navigation
- Unclear opening hours
- Limited visual presentation
- Cumbersome access to ordering and contact options

### Solution

Nomi Sushi & Thai provides a centralized digital restaurant experience with:

- Responsive and mobile-first design
- Dynamic restaurant opening-hour information
- Interactive menu and gallery experiences
- Online ordering access
- Reusable UI components
- Smooth animations and transitions
- PWA capabilities
- Multi-language support
- Accessible navigation and interactions

---

# 🚀 Key Features

## 🕐 Live Opening Hours

The application includes a dynamic restaurant status system.

### Features

- Calculates restaurant status using the restaurant's configured timezone
- Displays whether the restaurant is currently open or closed
- Shows upcoming opening/closing information
- Automatically refreshes the status
- Handles different opening schedules

### Example States

```text
🟢 Open Now
🟡 Closing Soon
🔴 Closed
```

This gives customers quick access to important restaurant availability information.

---

## 🎨 Modern Glassmorphism UI

The application uses a modern glassmorphism-inspired design system.

### Design Elements

- Frosted glass surfaces
- Backdrop blur
- Layered transparency
- Gradient overlays
- Soft shadows
- Rounded cards
- Interactive hover states
- Depth-based visual hierarchy

The design is intended to provide a premium restaurant experience while remaining usable across different screen sizes.

---

## 🌊 Smooth Animations

Interactive animations are implemented using **Framer Motion**.

### Animation Patterns

- Hero section entrance animations
- Staggered content reveals
- Scroll-triggered animations
- Hover animations
- Spring-based interactions
- Background decorative animations
- Modal and sheet transitions

Animations are designed to enhance the user experience without interfering with navigation or accessibility.

---

## 📱 Progressive Web App

The project includes Progressive Web App functionality.

### PWA Features

- Web app manifest
- Installable application experience
- Application icons
- App shortcuts
- Mobile-friendly interface
- Local storage based preferences
- Foundation for offline capabilities

### App Shortcuts

Users can quickly access important sections such as:

- Menu
- Gallery
- Order
- Contact

---

## 🖼️ Interactive Gallery

The restaurant gallery provides an immersive way to explore images.

### Features

- Full-screen image viewing
- Lightbox interface
- Keyboard navigation
- Previous/next navigation
- Mobile swipe gestures
- Image sharing
- Image download support
- Responsive gallery layout

The gallery uses **yet-another-react-lightbox**.

---

## 🛒 Online Ordering

The website provides clear access to online ordering.

### Ordering Experience

- Order Online CTAs
- Clear navigation to ordering
- Toast feedback
- Order-related UI states
- Persistent order interaction state

The goal is to make the ordering journey easy to discover from different sections of the website.

---

## 📍 Contact & Restaurant Information

The contact experience provides customers with essential restaurant information.

Includes:

- Restaurant address
- Phone number
- Email/contact options
- Opening hours
- Directions
- WhatsApp/contact actions
- Reservation-related actions

---

## ⚡ Floating Action System

The application includes a context-aware floating action system.

### Desktop

A floating speed-dial interface provides quick access to important actions.

### Mobile

A mobile-friendly action dock provides prioritized actions.

Depending on the page, actions can include:

- Call
- WhatsApp
- Directions
- Order
- Reservation
- Contact
- Menu
- Gallery

This makes important restaurant actions easily accessible without requiring users to navigate through multiple pages.

---

## 💬 Toast Notifications

The project uses **Sonner** for user feedback.

Toast notifications are used for actions such as:

- Copying phone numbers
- Copying email addresses
- Copying addresses
- Order interactions
- Navigation feedback
- User actions requiring confirmation

The notification system also supports theme-aware presentation and accessible interaction patterns.

---

## 💀 Skeleton Loading States

Content-aware skeleton loaders are used to improve the perceived loading experience.

Implemented for areas such as:

- Gallery
- Menu cards
- Dynamic content sections

Skeleton layouts preserve the expected content dimensions and help minimize layout shifts.

---

## 🌐 Multi-Language Support

The project includes support for multiple languages.

### Currently Supported

- 🇬🇧 English
- 🇸🇪 Swedish

### Features

- Language selection
- Persistent language preference
- Local storage persistence
- Translation context
- Reusable translation structure
- Easy extension for additional languages

---

# 🧩 Technical Architecture

The application follows a component-based architecture using the Next.js App Router.

```text
Nomi-Sushi-Thai-restaurant/
│
├── app/
│   ├── about/
│   ├── contact/
│   ├── gallery/
│   ├── menu/
│   └── ...
│
├── components/
│   ├── ui/
│   ├── layout/
│   ├── navigation/
│   └── ...
│
├── lib/
│   ├── openingHours.ts
│   ├── toast.ts
│   └── ...
│
├── public/
│   ├── images/
│   ├── icons/
│   └── ...
│
├── .env.local.example
├── next.config.ts
├── package.json
├── tsconfig.json
└── README.md
```

---

# 🛠️ Tech Stack

## Frontend

- **Next.js 15**
- **React 19**
- **TypeScript**
- **Tailwind CSS**
- **HTML5**
- **CSS3**

## UI & Animation

- **Framer Motion**
- **Radix UI**
- **Lucide React**
- **next-themes**
- **clsx**
- **tailwind-merge**
- **class-variance-authority**

## Gallery

- **yet-another-react-lightbox**

## Notifications

- **Sonner**

## Development Tools

- ESLint
- Prettier
- PostCSS
- Autoprefixer
- Git
- GitHub
- VS Code
- Vercel

---

# 🏗️ Architecture Highlights

### Next.js App Router

The application uses the Next.js App Router architecture with reusable layouts and components.

### TypeScript

TypeScript is used throughout the application for:

- Type safety
- Component props
- Data models
- Configuration
- Translation structures
- Utility functions

### Reusable Components

The application is structured around reusable UI components to reduce duplication and improve maintainability.

### Centralized Configuration

Restaurant information and configuration can be managed through centralized configuration files rather than being duplicated throughout the application.

### Responsive Design

The application follows a mobile-first responsive approach.

```text
Mobile
   ↓
Tablet
   ↓
Desktop
   ↓
Large Desktop
```

---

# ♿ Accessibility

Accessibility has been considered throughout the application.

### Implemented Practices

- Semantic HTML
- ARIA labels
- Keyboard navigation
- Accessible interactive controls
- Focus management
- Screen-reader-friendly notifications
- Reduced-motion considerations
- Accessible UI primitives through Radix UI

---

# ⚡ Performance Considerations

The application uses several frontend performance techniques.

### Image Optimization

Next.js Image optimization is used where applicable.

### Lazy Loading

Heavy or non-critical UI can be loaded only when required.

### Code Splitting

Dynamic imports can be used for larger interactive components.

### Animation Optimization

Animations primarily rely on transform and opacity properties where possible.

### Intersection Observer

Scroll-triggered content can be revealed when it enters the viewport.

---



# 👩‍💻 About Me

## Bushra Inamdar

**Computer Engineering Graduate | Full-Stack Developer**


# 🔗 Connect With Me

### GitHub

🔗 https://github.com/bush07

### LinkedIn

🔗 https://www.linkedin.com/in/bushra-inamdar07

---

# ⭐ Project

If you find this project interesting, feel free to explore the repository and check out my other projects.

---


### Built with ❤️ using Next.js, React, TypeScript and Tailwind CSS.
