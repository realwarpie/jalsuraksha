# JalSuraksha Design Guidelines

## Design Approach: Health System Interface
**Selected Approach**: Carbon Design System with healthcare-focused adaptations
**Justification**: Enterprise-grade data visualization requirements, government sector reliability needs, and complex dashboard interfaces align with Carbon's strengths in information-dense applications.

## Core Design Elements

### A. Color Palette
**Primary Brand Colors:**
- Deep Blue: 220 85% 25% (trust, reliability, medical professionalism)
- Teal Accent: 180 65% 45% (water association, health vitality)

**Status/Alert Colors:**
- Success Green: 140 60% 40%
- Warning Amber: 45 85% 55%
- Critical Red: 10 80% 50%
- Info Blue: 210 75% 60%

**Backgrounds:**
- Light mode: 0 0% 98% (clean, clinical)
- Dark mode: 220 15% 12% (reduced eye strain for long monitoring sessions)

### B. Typography
**Font Stack**: IBM Plex Sans (Carbon Design System standard)
- Headers: IBM Plex Sans Medium (24px, 20px, 18px)
- Body: IBM Plex Sans Regular (16px, 14px)
- Data/Metrics: IBM Plex Mono (for precise number alignment)

### C. Layout System
**Spacing Units**: Tailwind 4, 6, 8, 12 units
- Component spacing: p-4, m-6
- Section spacing: py-8, my-12
- Compact data views: p-2, gap-4

### D. Component Library

**Navigation:**
- Top navigation bar with role-based menu items
- Breadcrumb navigation for deep data views
- Sidebar navigation for dashboard sections

**Data Visualization:**
- Clean chart components with accessible color coding
- Interactive maps with district-level data
- Real-time status indicators with clear visual hierarchy
- Data tables with sorting and filtering capabilities

**Forms:**
- Multi-step forms for health case reporting
- Validation states with clear error messaging
- Multilingual toggle switches
- File upload areas for health reports

**Cards & Containers:**
- Alert cards with severity-based styling
- Metric dashboard cards with large numbers
- Information cards for PHC details
- Expandable accordion sections for detailed data

**Overlays:**
- Modal dialogs for critical alerts
- Drawer panels for detailed case information
- Tooltip overlays for data explanations

### E. Healthcare-Specific Considerations

**Accessibility:**
- High contrast ratios for clinical environments
- Large touch targets for field workers
- Clear iconography for low-literacy users
- Consistent dark mode for 24/7 monitoring

**Regional Adaptation:**
- Support for Assamese and Hindi scripts
- Cultural color sensitivity (avoiding negative associations)
- Mobile-first design for field health workers
- Offline-capable interface indicators

**Data Visualization:**
- Geographic heat maps with intuitive color coding
- Time-series charts for outbreak tracking
- Clear visual hierarchy for alert priorities
- Accessible chart legends and labels

## Images
**Hero Section**: No large hero image - focus on dashboard functionality immediately
**Supporting Images**: 
- Small icons representing different water-borne diseases
- Simple illustrations for empty states and onboarding
- Geographic region illustrations for context
- Health worker avatar placeholders for user profiles

This design system prioritizes clarity, accessibility, and efficient information processing essential for healthcare monitoring applications while maintaining professional aesthetics suitable for government health systems.