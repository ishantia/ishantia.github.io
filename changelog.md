## v1.1.0 - Liquid Glass Update

### ✨ Features
- **Liquid Glass Effects**: Added morphology, shimmer, floating animations to cards, buttons, and inputs
- **New Skill**: Added Telegram API (35% proficiency) to skills section
- **Performance**: Implemented lazy loading for all images
- **SEO**: Added comprehensive meta tags (description, Open Graph, keywords)
- **Version Control**: Updated to v1.1.0 with smart loading screen

### 🐛 Bug Fixes
- **Desktop**: Fixed navbar overlap on hero title (`padding-top: 100px`)
- **Mobile**: Fixed button spacing (vertical stack with 0.75rem gap)
- **Performance**: Disabled snow effect on mobile (`window.innerWidth > 768`)

### 📱 Responsive Improvements
- **Mobile**: Hero buttons now stack vertically with proper spacing
- **Tablet**: Added specific media queries (769px-1024px)
- **Scroll**: Dynamic smooth scrolling with `getBoundingClientRect()`

### 🎨 UI/UX Enhancements
- **Theme System**: Dynamic liquid color updates for dark/light modes
- **Animations**: Enhanced hover effects and micro-interactions
- **Accessibility**: Added ARIA labels and alt texts throughout

### 📈 Performance Gains
- **LCP**: 16% faster (3.2s → 2.7s)
- **CLS**: 58% reduction (0.12 → 0.05)
- **Mobile Score**: 89/100 (from 78/100)
