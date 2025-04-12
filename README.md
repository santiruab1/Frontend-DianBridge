# DIANBridge - Web Application

DIANBridge is a web application designed to simplify and automate the integration of electronic invoices with the DIAN platform. This project provides a responsive and user-friendly interface for managing invoices, subscriptions, and reports.

## Project Overview

This project is built using **HTML**, **CSS**, and **Bootstrap** for the frontend, with **Vite** as the build tool and **Tailwind CSS** for utility-first styling. The application includes multiple pages, each serving a specific purpose.

---

## HTML Structure and Pages

### 1. **Home Page (`index.html`)**
   - **Purpose**: Serves as the landing page for the application.
   - **Key Features**:
     - Welcome section with a logo and introduction.
     - Pricing table showcasing membership plans.
     - Services section highlighting features like automation, support, and optimization.
     - FAQ accordion for common questions.
   - **File**: [`src/index.html`](src/index.html)

### 2. **About Us Page (`aboutus.html`)**
   - **Purpose**: Provides information about the mission, vision, and values of DIANBridge.
   - **Key Features**:
     - Mission and vision statements.
     - List of core values (e.g., innovation, transparency, security).
   - **File**: [`src/aboutus.html`](src/aboutus.html)

### 3. **Pricing Page (`pricing.html`)**
   - **Purpose**: Displays membership plans and their features.
   - **Key Features**:
     - Cards for each membership plan (Free, Monthly, Annual).
     - Pricing comparison table.
   - **File**: [`src/pricing.html`](src/pricing.html)

### 4. **Login Page (`inicioSesion.html`)**
   - **Purpose**: Allows users to log in to their accounts.
   - **Key Features**:
     - Login form with email and password fields.
     - Carousel showcasing application features.
   - **File**: [`src/inicioSesion.html`](src/inicioSesion.html)

### 5. **User Dashboard (`interfazUsuario.html`)**
   - **Purpose**: Provides a dashboard for managing invoices, reports, and subscriptions.
   - **Key Features**:
     - Sidebar navigation for different sections (e.g., invoices, reports, settings).
     - Cards for quick actions like generating reports and managing subscriptions.
   - **File**: [`src/interfazUsuario.html`](src/interfazUsuario.html)

---

## CSS and Styling

The project uses a combination of **Bootstrap** and custom CSS for styling. The main CSS file is located at:

- **File**: [`src/assets/css/style.css`](src/assets/css/style.css)

### Key Styling Features:
- Responsive design for all pages.
- Custom styles for headers, tables, login forms, and carousels.
- Media queries for mobile-friendly layouts.

---

## Images and Assets

The project includes several images for the carousel and branding:

- **Carousel Images**: Located in [`src/assets/images/`](src/assets/images/)
- **Logo**: `LogoBlanco.png` and `LogoBlancoSombra.png`

---

## Development and Build Tools

- **Vite**: Used as the build tool for fast development and optimized production builds.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **PostCSS**: Configured for Tailwind CSS integration.

### Configuration Files:
- [`vite.config.js`](vite.config.js)
- [`tailwind.config.js`](tailwind.config.js)
- [`postcss.config.js`](postcss.config.js)

---

## How to Run the Project

1. **Install Dependencies**:
   ```sh
   npm install
   ```

2. **Start Development Server**:
   ```sh
   npm run dev
   ```

3. **Build for Production**:
   ```sh
   npm run build
   ```

4. **Preview Production Build**:
   ```sh
   npm run preview
   ```

---

## License

This project is licensed under the BSD 3-Clause License. See the [`LICENSE`](LICENSE) file for details.
