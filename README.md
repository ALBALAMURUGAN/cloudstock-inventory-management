# CloudStock — Cloud-Based Inventory Management System

CloudStock is a premium, responsive front-end concept for a **cloud-based inventory management system**. It presents inventory intelligence, analytics, forecasting, multi-location synchronization, pricing, and a demo request experience through a polished enterprise-style interface.

> **Project type:** Front-end / UI-UX prototype  
> **Status:** Academic / demonstration project  
> **Year:** 2026

## ✨ Highlights

- Premium white, brown, amber and cream visual theme
- Responsive layout for desktop, tablet and mobile screens
- Animated hero section and loading screen
- Scroll-based reveal animations
- GSAP + ScrollTrigger animations
- Animated statistics and progress indicators
- Custom cursor interaction on desktop
- Scroll progress indicator
- Inventory dashboard-style visualizations
- AI-powered demand forecasting section
- Multi-location inventory concept
- Pricing section with Starter, Professional and Enterprise plans
- Demo request form UI
- FAQ / interactive content sections included in the interface
- Lucide icon system
- Google Fonts typography
- Smooth scrolling navigation

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript
- Tailwind CSS via CDN

### Animation & UI
- GSAP 3.12.2
- GSAP ScrollTrigger 3.12.2
- Lucide Icons
- Google Fonts
  - Playfair Display
  - Plus Jakarta Sans

The current project loads these libraries from CDNs directly inside `index.html`, so **Node.js, npm and a build step are not required** to run the current version.

## 📁 Project Structure

```text
CloudStock/
├── index.html
├── README.md
├── LICENSE
├── .gitignore
├── .nojekyll
└── assets/
    └── images/
```

The `assets/images` directory is reserved for future local images and media.

## 🚀 Run Locally

### Option 1 — Open directly

Double-click `index.html` and open it in a modern web browser.

### Option 2 — VS Code

Open the project folder in Visual Studio Code and use a local static-server extension such as Live Server if desired.

### Option 3 — Python local server

If Python is installed:

```bash
python -m http.server 5500
```

Then open:

```text
http://localhost:5500
```

## 🌐 External Resources

The current `index.html` references the following external resources:

- Tailwind CSS CDN
- GSAP CDN
- GSAP ScrollTrigger CDN
- Lucide CDN
- Google Fonts

An internet connection is therefore required for all CDN-hosted resources to load correctly.

## 📊 Project Concept

CloudStock is designed around the idea of bringing inventory operations into a centralized cloud platform. The interface communicates concepts such as:

- Real-time inventory visibility
- Demand forecasting
- Automatic reorder suggestions
- Multi-location synchronization
- Inventory analytics
- Stock optimization
- Enterprise inventory management

The project is currently a **front-end demonstration**. It does not claim to provide a production cloud database, authentication system, real-time inventory backend, or actual machine-learning forecasting engine unless those features are implemented separately.

## 🔮 Future Enhancements

Possible next versions can add:

1. User authentication
2. Admin and staff roles
3. Cloud database integration
4. Product CRUD operations
5. Supplier management
6. Purchase and sales records
7. Real-time stock updates
8. Low-stock notifications
9. Cloud storage
10. Real inventory analytics
11. Backend REST APIs
12. Real demand forecasting
13. Export to CSV/PDF
14. Dashboard filtering and search
15. Deployment with a custom domain

## ☁️ Suggested Production Stack

If this prototype is expanded into a complete cloud-computing project, a possible stack is:

- **Frontend:** React / TypeScript / Tailwind CSS
- **Backend:** Node.js / Express
- **Authentication:** Firebase Authentication or JWT
- **Database:** Firebase Firestore or MongoDB Atlas
- **Storage:** Firebase Storage or AWS S3
- **Hosting:** GitHub Pages for static front-end prototypes, or a cloud platform such as Render for a full-stack application

These are future implementation options, not dependencies of the current static version.

## 📌 GitHub Pages

This project can be hosted as a static website using GitHub Pages because the current version consists of HTML, CSS and client-side JavaScript.

After pushing the project to GitHub:

1. Open the repository.
2. Go to **Settings**.
3. Open **Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder.
6. Save the configuration.
7. Wait for GitHub Pages to publish the site.

## 👨‍💻 Academic Project

This project can be used as a front-end demonstration for a **Cloud Computing — Cloud-Based Inventory Management System** academic project.

The current interface is intended to demonstrate the system concept, user experience, visual design and front-end interactions. Backend/cloud functionality can be implemented as a separate phase.

## 📄 License

This project is provided under the MIT License. See `LICENSE` for details.
