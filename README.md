# PSK Services - Event Management Platform 🎉

A modern, responsive event management website built with React and Vite, featuring a sleek dark theme and interactive booking system.

## 🌟 Features

### 🎨 **Modern UI/UX**
- **Dark Theme Design**: Professional dark theme with green accent colors
- **Glassmorphism Effects**: Modern glass-like components with backdrop blur
- **Responsive Layout**: Fully responsive design that works on all devices
- **Custom Typography**: Beautiful font combination (Boldonse & Sansita Swashed)

### 📅 **Interactive Booking System**
- **Calendar Component**: Custom-styled calendar for date selection
- **Time Slot Selection**: Available time slots for event booking
- **Event Type Management**: Multiple event types (Concerts, Weddings, Corporate Events, etc.)
- **Contact Forms**: Comprehensive booking forms with validation
- **Toast Notifications**: Real-time feedback for user actions

### 🎵 **Event Services**
- **Professional Audio Services**: High-quality sound systems and equipment
- **DJ Services**: Professional DJ services for various events
- **Event Planning**: Complete event management solutions
- **Technical Support**: On-site technical support and setup

### 📱 **Pages & Features**
- **Homepage**: Hero section with services overview
- **Services**: Detailed service offerings
- **Blog**: Event tips and company updates
- **References**: Portfolio and client testimonials
- **Booking**: Interactive booking system
- **404 Page**: Custom not found page

## 🛠️ Technology Stack

### **Frontend Framework**
- **React 19.1.0**: Latest React with modern features
- **Vite 7.0.4**: Fast build tool and development server
- **React Router DOM**: Client-side routing

### **UI Components & Styling**
- **Tailwind CSS 3.4.15**: Utility-first CSS framework
- **Radix UI**: Accessible component primitives
- **Lucide React**: Beautiful icon library
- **React Day Picker**: Calendar component
- **Sonner**: Toast notifications

### **Form Handling & Data**
- **React Hook Form**: Efficient form management
- **TanStack Query**: Data fetching and caching
- **Date-fns**: Date utility functions
- **Class Variance Authority**: Component variant management

### **Development Tools**
- **ESLint**: Code linting and quality
- **PostCSS**: CSS processing
- **Autoprefixer**: CSS vendor prefixes

## 🚀 Quick Start

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd events
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open in browser**
   ```
   http://localhost:5173
   ```

## 📜 Available Scripts

```bash
# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview

# Run ESLint
npm run lint
```

## 🎨 Design System

### **Colors**
- **Primary Green**: `#10b981` (psyco-green-DEFAULT)
- **Dark Backgrounds**: `#1a1a1a` (psyco-black-DEFAULT)
- **Card Backgrounds**: `#2a2a2a` (psyco-black-card)
- **Text**: White and gray variants

### **Typography**
- **Primary Font**: Boldonse (Google Fonts)
- **Secondary Font**: Sansita Swashed
- **Fallback**: Inter

### **Components**
- **Glassmorphism Cards**: Semi-transparent backgrounds with blur effects
- **Gradient Elements**: Green gradient accents
- **Interactive States**: Hover and focus animations
- **Responsive Grid**: CSS Grid and Flexbox layouts

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── ui/             # Base UI components (Radix UI based)
│   ├── BlogPost.jsx    # Blog post card component
│   ├── BookingCalendar.jsx  # Main booking calendar
│   ├── Footer.jsx      # Site footer
│   ├── HeroSection.jsx # Homepage hero
│   ├── Navbar.jsx      # Navigation bar
│   └── ServiceCard.jsx # Service display card
├── pages/              # Page components
│   ├── Index.jsx       # Homepage
│   ├── Services.jsx    # Services page
│   ├── Blog.jsx        # Blog listing
│   ├── BlogDetail.jsx  # Individual blog post
│   ├── References.jsx  # Portfolio/testimonials
│   ├── Booking.jsx     # Booking page
│   └── NotFound.jsx    # 404 page
├── hooks/              # Custom React hooks
├── lib/                # Utility functions
└── styles/             # Global styles
```

## 🎯 Key Features Explained

### **Booking System**
The booking system allows users to:
- Select event dates using an interactive calendar
- Choose from available time slots
- Select event types (Concert, Wedding, Corporate, etc.)
- Fill out contact information
- Submit booking requests with validation

### **Responsive Design**
- Mobile-first approach
- Breakpoint-based layouts
- Touch-friendly interfaces
- Optimized performance on all devices

### **Accessibility**
- ARIA labels and roles
- Keyboard navigation support
- Screen reader compatibility
- Color contrast compliance

## 🔧 Customization

### **Styling**
The project uses Tailwind CSS with custom configuration:
- Custom color palette in `tailwind.config.ts`
- Custom font families
- Extended spacing and sizing scales

### **Components**
All components are modular and can be easily customized:
- Props-based configuration
- CSS variable theming
- Variant-based styling with CVA

## 🚀 Deployment

### **Build for Production**
```bash
npm run build
```

### **Deployment Options**
- **Vercel**: Zero-config deployment
- **Netlify**: Continuous deployment from Git
- **GitHub Pages**: Static site hosting
- **Traditional Hosting**: Upload `dist` folder

## 🐛 Troubleshooting

### **Common Issues**
1. **Port conflicts**: Change port in `vite.config.ts`
2. **Node version**: Ensure Node.js v18+
3. **Dependencies**: Clear `node_modules` and reinstall
4. **Build errors**: Check ESLint output

## 📝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is private and proprietary to PSK Services.

## 🎵 About PSK Services

PSK Services (Psycotik Crew) is a professional event management company specializing in:
- High-quality audio equipment and sound systems
- Professional DJ services for all event types
- Complete event planning and coordination
- Technical support and equipment setup

For more information, visit our website or contact us through the booking system.

---

**Built with ❤️ by the PSK Services team**
  {
    files: ['**/*.{ts,tsx}'],
    extends: [
      // Other configs...
      // Enable lint rules for React
      reactX.configs['recommended-typescript'],
      // Enable lint rules for React DOM
      reactDom.configs.recommended,
    ],
    languageOptions: {
      parserOptions: {
        project: ['./tsconfig.node.json', './tsconfig.app.json'],
        tsconfigRootDir: import.meta.dirname,
      },
      // other options...
    },
  },
])
```
