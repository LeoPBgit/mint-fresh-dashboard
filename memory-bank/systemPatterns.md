# System Patterns: Mint Fresh Application

## Architecture Overview
The Mint Fresh application follows a component-based architecture with a shared design system, implementing modern web standards and responsive design patterns.

## Design System Architecture

### Theme System
- **CSS Custom Properties**: Centralized design tokens in `login_theme_1.css`
- **OKLCH Color Space**: Modern color system for better perceptual uniformity
- **Semantic Naming**: Color variables named by purpose (primary, secondary, muted, etc.)
- **Consistent Scaling**: Typography, spacing, and shadow systems with mathematical relationships

### Component Patterns

#### Layout Components
- **Dashboard Container**: Flexbox-based layout with sidebar and main content
- **Sidebar Navigation**: Fixed-width sidebar with collapsible mobile behavior
- **Header Bar**: Consistent header with search and profile components
- **Content Grid**: CSS Grid for responsive card layouts

#### UI Components
- **Stat Cards**: Reusable metric display components with hover animations
- **Chart Cards**: Standardized containers for data visualizations
- **Data Tables**: Responsive table components with status indicators
- **Form Components**: Consistent input styling with focus states

## Responsive Design Patterns

### Breakpoint Strategy
```css
/* Mobile-first approach */
@media (max-width: 640px)  { /* Mobile */ }
@media (max-width: 768px)  { /* Tablet */ }
@media (max-width: 1024px) { /* Desktop */ }
```

### Adaptive Behaviors
- **Sidebar Collapse**: Desktop sidebar becomes mobile overlay
- **Grid Adaptation**: Multi-column grids become single-column on mobile
- **Typography Scaling**: Font sizes adjust for different screen sizes
- **Touch Optimization**: Larger touch targets on mobile devices

## Animation System

### Entry Animations
- **Staggered Loading**: Sequential component appearance with delays
- **Card Entry**: Slide-up animation with opacity fade-in
- **Chart Loading**: Scale and opacity animations for data visualization

### Interaction Animations
- **Hover Effects**: Transform and shadow changes on interactive elements
- **Focus States**: Ring animations for accessibility
- **Button Feedback**: Scale animations for press feedback
- **Form Validation**: Shake animation for error states

## State Management Patterns

### Client-Side State
- **Form State**: Local form validation and submission handling
- **UI State**: Mobile menu toggle, sidebar collapse states
- **Chart State**: Dynamic chart data and interaction states
- **Animation State**: CSS class-based animation triggers

### Data Flow
- **Static Data**: Hardcoded sample data for demonstration
- **Event Handling**: DOM event listeners for user interactions
- **State Updates**: Direct DOM manipulation for state changes

## Code Organization Patterns

### CSS Architecture
- **Component Scoping**: CSS organized by component functionality
- **Utility Integration**: Tailwind CSS for rapid styling
- **Custom Properties**: Design tokens for consistent theming
- **Progressive Enhancement**: Base styles with enhanced interactions

### JavaScript Patterns
- **Module Pattern**: Self-contained functionality blocks
- **Event Delegation**: Efficient event handling
- **Progressive Enhancement**: Core functionality without JavaScript
- **Library Integration**: External library initialization and configuration

## Accessibility Patterns

### Semantic Structure
- **HTML5 Semantics**: Proper use of nav, main, aside, section elements
- **ARIA Labels**: Screen reader support for interactive elements
- **Keyboard Navigation**: Tab order and focus management
- **Color Contrast**: WCAG-compliant color combinations

### Interactive Accessibility
- **Focus Indicators**: Visible focus states for keyboard users
- **Screen Reader Support**: Proper labeling and descriptions
- **Touch Targets**: Minimum 44px touch target sizes
- **Motion Preferences**: Respect for reduced motion preferences

## Performance Patterns

### Loading Strategy
- **Critical CSS**: Inline critical styles for above-the-fold content
- **CDN Resources**: External libraries loaded from CDN
- **Lazy Initialization**: Charts initialized after DOM ready
- **Efficient Animations**: Hardware-accelerated transforms

### Optimization Techniques
- **CSS Efficiency**: Minimal specificity and efficient selectors
- **JavaScript Optimization**: Event listener cleanup and efficient DOM queries
- **Asset Optimization**: SVG icons and optimized font loading
- **Caching Strategy**: Leverage browser caching for static assets

## Integration Patterns

### External Libraries
- **Chart.js Integration**: Modular chart configuration and initialization
- **Icon System**: Lucide icons with consistent sizing and styling
- **Font Loading**: Google Fonts with fallback font stacks
- **CSS Framework**: Tailwind CSS utility integration

### Component Communication
- **Event-Driven**: DOM events for component interaction
- **Shared State**: CSS custom properties for theme sharing
- **Configuration Objects**: JavaScript objects for component setup
- **Callback Patterns**: Event handlers for user interactions

## Scalability Considerations

### Maintainability
- **Consistent Naming**: BEM-inspired CSS class naming
- **Modular Structure**: Separable component styles
- **Documentation**: Clear code comments and structure
- **Version Control**: Organized file structure for team collaboration

### Extensibility
- **Theme Flexibility**: Easy color and typography customization
- **Component Reusability**: Modular component design
- **Feature Addition**: Clear patterns for new functionality
- **Framework Migration**: Structure supports future framework adoption
