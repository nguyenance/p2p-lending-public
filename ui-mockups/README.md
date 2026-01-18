# UI Mockups - P2P Lending Mobile App

**Created by:** Mobile Flutter Developer  
**Technology:** HTML + Onsen UI  
**Language:** Vietnamese Only  
**Purpose:** Visual mockups for all mobile app screens

---

## 📋 Overview

This folder contains HTML-based UI mockups for all screens defined in `../mobile-app-screens.md`. These mockups use the Onsen UI library to simulate mobile app interfaces and can be opened directly in a web browser for review and testing.

---

## 🎨 Design Principles Applied

All mockups follow these principles from the Mobile Flutter Developer guidelines:

### 1. **Vietnamese-First Design**
- All text in Vietnamese only
- Vietnamese currency format (₫)
- Vietnamese date format (DD/MM/YYYY)
- Vietnamese phone number format (0xxx-xxx-xxx)

### 2. **Premium Visual Design**
- Modern gradient backgrounds
- Smooth animations (fadeIn, fadeInUp, fadeInDown)
- Glassmorphism effects on cards
- Vibrant color palette
- Micro-interactions on buttons
- Professional typography (Inter font)

### 3. **Mobile-First Responsive**
- Optimized for Vietnamese phone screen sizes (360x640 to 430x932)
- Touch-friendly button sizes (min 44px height)
- Proper spacing and padding
- Viewport-fit for modern devices

### 4. **Security & UX**
- Password show/hide toggle
- Input validation with error states
- Loading states
- Biometric authentication option
- Clear error messages in Vietnamese

---

## 📱 Available Mockups

### Authentication & Onboarding Module

| # | Screen Name | File | Status |
|---|-------------|------|--------|
| 1.6 | Login Screen | `01-login-screen.html` | ✅ Complete |
| 1.3 | Registration Screen | `02-registration-screen.html` | 🔜 Pending |
| 1.4 | OTP Verification | `03-otp-verification.html` | 🔜 Pending |
| 1.5 | Create Password | `04-create-password.html` | 🔜 Pending |
| 1.2 | Welcome Screen | `05-welcome-screen.html` | 🔜 Pending |
| 1.7 | Forgot Password | `06-forgot-password.html` | 🔜 Pending |

*Additional modules will be added progressively...*

---

## 🚀 How to View Mockups

### Method 1: Open Directly in Browser
Simply double-click any `.html` file to open it in your default browser.

### Method 2: Use Live Server (Recommended)
```bash
# If you have Python installed
cd docs/design/screen-list/ui-mockups
python -m http.server 8000

# Then open http://localhost:8000 in your browser
```

### Method 3: VS Code Live Server Extension
1. Install "Live Server" extension in VS Code
2. Right-click on any `.html` file
3. Select "Open with Live Server"

---

## 🎯 Design System

### Color Palette
```css
--primary-color: #2563eb;      /* Primary Blue */
--primary-dark: #1e40af;       /* Dark Blue */
--secondary-color: #10b981;    /* Success Green */
--error-color: #ef4444;        /* Error Red */
--text-primary: #1f2937;       /* Dark Gray */
--text-secondary: #6b7280;     /* Medium Gray */
--bg-gray: #f9fafb;            /* Light Gray Background */
--border-color: #e5e7eb;       /* Border Gray */
```

### Typography
- **Font Family:** Inter (Google Fonts)
- **Headings:** 600-700 weight
- **Body:** 400-500 weight
- **Button Text:** 600 weight

### Spacing Scale
- **Extra Small:** 4px
- **Small:** 8px
- **Medium:** 16px
- **Large:** 24px
- **Extra Large:** 32px, 40px, 60px

### Border Radius
- **Small:** 8px
- **Medium:** 12px
- **Large:** 16px, 20px, 24px

---

## 📝 Notes for Implementation

### For Flutter Implementation:
1. Use these mockups as reference for layout and visual design
2. Replace HTML/CSS with Flutter widgets:
   - `div` → `Container`, `Column`, `Row`
   - CSS animations → `AnimatedContainer`, `Hero widgets`
   - Form inputs → `TextFormField` with `InputDecoration`
3. Use the color palette defined above in Flutter theme
4. Implement the same validation logic in Dart
5. Use `flutter_form_builder` for forms

### API Integration Points:
- **Login:** `POST /auth/login`
- **Biometric Setup:** Local device API
- **Form Validation:** Client-side + Server-side

### Testing Checklist:
- [ ] All text is in Vietnamese
- [ ] Currency displays ₫ symbol
- [ ] Phone number validates Vietnamese format (0xxx-xxx-xxx)
- [ ] Password toggle works
- [ ] Form validation shows errors
- [ ] Animations are smooth
- [ ] Responsive on different screen sizes
- [ ] Touch targets are at least 44px

---

## 🔗 Related Documents

- **Screen Specifications:** `../mobile-app-screens.md`
- **Mobile Developer Guidelines:** `../../../prompts/Scrum/devs/5.Mobile-Flutter.md`
- **Product Requirements:** `../../product-requirements/`
- **PBIs:** `../../PBIs/`

---

## 📧 Contact

For questions about these mockups, refer to the Mobile Flutter Developer documentation or consult the design specifications.
