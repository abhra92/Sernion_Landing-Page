# Sernion Landing Page

This is a modern, responsive landing page built with Vite, Tailwind CSS, and vanilla JavaScript. It features smooth animations, a mobile-friendly navigation menu, and a contact form.

## Features

*   **Responsive Design**: Adapts to various screen sizes, from desktop to mobile.
*   **Smooth Animations**: Utilizes Intersection Observer for scroll-triggered animations and CSS transitions for a polished user experience.
*   **Mobile Navigation**: Hamburger menu for smaller screens with collapsible navigation.
*   **Contact Form**: A basic contact form with client-side validation and simulated submission.
*   **Vite**: Fast development server and build tool.
*   **Tailwind CSS**: Utility-first CSS framework for rapid UI development.
*   **Vanilla JavaScript**: Clean and efficient JavaScript for interactive elements.

## Technologies Used

*   [Vite](https://vitejs.dev/)
*   [Tailwind CSS](https://tailwindcss.com/)
*   HTML5
*   CSS3
*   JavaScript

## Setup and Installation

To get this project up and running on your local machine, follow these steps:

1.  **Clone the repository**:
    ```bash
    git clone <repository-url>
    cd sernion-landing-page
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    ```

3.  **Run the development server**:
    ```bash
    npm run dev
    ```
    The application will be accessible at `http://localhost:3000/` (or another available port).

4.  **Build for production**:
    ```bash
    npm run build
    ```
    This will generate optimized static assets in the `dist/` directory.

## Project Structure

```
.gitignore
README.md
index.html
package.json
postcss.config.js
tailwind.config.js
vite.config.js
src/
├── favicon.svg
├── input.css
└── main.js
```

## Contributing

Feel free to fork this repository and contribute. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

A modern, responsive landing page for Sernion AI Solutions built with HTML, CSS (Tailwind), and JavaScript.

## Features

### 🎨 **Responsive Design**
- Mobile-first approach with breakpoints for all screen sizes
- Collapsible mobile navigation menu
- Responsive typography and spacing
- Optimized for tablets, desktops, and mobile devices

### 🚀 **Performance & UX**
- Smooth scrolling navigation
- Intersection Observer animations
- Hover effects and micro-interactions
- Custom scrollbar styling
- Accessibility features (focus states, reduced motion support)

### 🎯 **Key Improvements Made**

#### **Navigation**
- Added mobile hamburger menu
- Smooth scroll to sections
- Dynamic navbar background on scroll
- Better responsive navigation structure

#### **Layout & Components**
- Responsive grid systems (1-4 columns based on screen size)
- Custom CSS utility classes for consistent spacing
- Card components with hover animations
- Better button styling with focus states

#### **Typography & Spacing**
- Responsive text sizes using Tailwind breakpoints
- Improved line heights and letter spacing
- Better content hierarchy
- Consistent spacing system

#### **Interactive Elements**
- Form validation and submission handling
- Animated gradient text effects
- Hover animations for cards and buttons
- Loading states for form submission

#### **Accessibility**
- Proper focus management
- ARIA labels and semantic HTML
- Reduced motion support for users with vestibular disorders
- Keyboard navigation support

## 🛠️ **Technical Stack**

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework
- **JavaScript (ES6+)** - Interactive functionality
- **Vite** - Fast build tool and dev server
- **PostCSS** - CSS processing

## 🚀 **Getting Started**

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Start development server:**
   ```bash
   npm run dev
   ```

3. **Build for production:**
   ```bash
   npm run build
   ```

## 📱 **Responsive Breakpoints**

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px  
- **Desktop**: > 1024px
- **Large Desktop**: > 1280px

## 🎨 **Design System**

### Colors
- Primary: Blue (#3B82F6)
- Secondary: Purple (#6366F1)
- Background: Dark gray (#111827)
- Text: White and gray variants

### Typography
- Font: Inter (system fallbacks)
- Responsive sizing: 2xl → 7xl for headings
- Consistent line heights and spacing

### Components
- Cards with backdrop blur effects
- Buttons with hover animations
- Form inputs with focus states
- Navigation with smooth transitions

## 🔧 **Custom CSS Classes**

```css
.btn-primary          /* Primary button styling */
.btn-secondary        /* Secondary button styling */
.card                 /* Card component */
.section              /* Section spacing */
.text-gradient        /* Gradient text effect */
.animate-fade-in      /* Fade in animation */
```

## 📋 **Browser Support**

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 **Performance Optimizations**

- CSS animations use `transform` and `opacity` for GPU acceleration
- Intersection Observer for efficient scroll animations
- Reduced motion support for accessibility
- Optimized bundle size with Vite

## 📝 **Future Enhancements**

- [ ] Add dark/light theme toggle
- [ ] Implement real form submission to backend
- [ ] Add more interactive animations
- [ ] Implement lazy loading for images
- [ ] Add SEO meta tags and structured data
- [ ] Implement analytics tracking

---

Built with ❤️ for Sernion AI Solutions