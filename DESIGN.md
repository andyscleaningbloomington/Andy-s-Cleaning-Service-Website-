---
name: Andy's Cleaning Website
version: 1.0.0
description:
  Andy's Cleaning Website design system embodies clean professionalism with
  warm, earthy undertones. The visual identity balances clean minimalism with
  organic, human-centered warmth through a carefully curated earth-tone palette
  paired with spacious, Lato typography. The system prioritizes
  legibility and trust through generous whitespace, elevated typography that
  conveys heritage and craftsmanship, and a restrained colour strategy that lets
  imagery and content breathe. Imagery plays a central role—cleaning supplies
  and team members occupy the visual stage, grounded by subtle, neutral
  backgrounds that recede. 

colors:
  primary: "#2665fd"
  secondary: "#475569"
  surface: "#0b1326"
  on-surface: "#dae2fd"
  error: "#ffb4ab"
typography:
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: 400
rounded:
  md: 8px
---

# Design System

## 1. Overview
**Purpose:** This website is for a small local business. It is a simple 4 page website with information about the business for prospective customers.

### Core Principles

- WCAG 2.1 AA compliance
- Based on Material Design 3 principles 
- Structured, systematic, and scalable
- Clear hierarchy through elevation and color roles
- Consistent behavior across components
- Emphasize usability and predictability


## 2. Colors
- Primary: #513229 (Mother Earth)

CTAs, active states, key interactive elements

* On Primary: #F4F1E2 (Lucky Dice)

* Primary Container: #FCE6B7 (The Bay)

* Background: #F4F1E2 (Lucky Dice)

* Surface: #F0EACF (Faded Chamomile)

Page backgrounds

* Text Primary: #352E2A (Garden Soil)

* Text Secondary: #543F2B (Dark Walnut)

* Outline: #7C7B50 (Wild Olive)

* Divider: #D3CCAB (Garden Remnant)


## 3. Typography

* Font Family:

  * Lato (https://fonts.google.com/specimen/Lato?preview.script=Latn)

### Scale (Material-based)

* Display: 32 / Regular
* Headline: 24 / SemiBold
* Title: 20 / Medium
* Body: 14–16 / Regular
* Label: 12–14 / Medium

### Rules

* Follow Material type scale hierarchy
* Use labels for buttons and small UI
* Maintain consistent usage across screens
* Line height: 1.4 – 1.5

---

## 4. Spacing System

Base unit: 4

* xs: 4
* sm: 8
* md: 12
* lg: 16
* xl: 24
* xxl: 32

### Rules

* Use consistent spacing tokens
* Align components to grid
* Maintain predictable layout rhythm

---

## 5. Layout & Safe Area

* Respect safe area
* Use structured layout sections
* Follow Material layout guidelines
* Use consistent margins (16–24)

---

## 6. Touch & Interaction

* Minimum touch target:

  * Android: 48dp
  * iOS: 44pt

* Feedback:

  * Ripple effect (Android)
  * Opacity/scale fallback (iOS)

* Maintain consistent interaction patterns

---

## 7. Navigation Patterns

### Bottom Navigation

* 3–5 items
* Icons + labels
* Active state clearly indicated

### Top App Bar

* Standard Material header
* Title + actions

### Navigation Behavior

* Stack-based navigation
* Modal for dialogs and temporary actions

---

## 8. Components

### 8.1 Button

Variants:

* Filled
* Outlined
* Text

Rules:

* Height: 40–48
* Radius: 8–12
* Use semantic color roles
* Ripple feedback required on Android

---

### 8.2 Card

* Background: Surface or Surface Variant
* Radius: 12–16
* Padding: 16
* Elevation-based hierarchy

---

### 8.3 List

* Structured rows
* Optional leading/trailing icons
* Divider-based separation
* Consistent alignment

---

### 8.4 Input (Text Field)

* Filled or outlined variants
* Label + helper text
* Clear error state
* Focus: primary color

---

## 9. Motion

* Duration: 150–300ms

### Style

* Standard Material easing curves
* Consistent transitions
* Motion communicates hierarchy and state

---

## 10. Elevation & Depth

* Use elevation levels:

  * 0 (background)
  * 1–2 (cards)
  * 3+ (dialogs, overlays)

* Shadows define hierarchy

* Maintain consistency across screens

---

## 11. Iconography

* Material Icons (preferred)
* Consistent stroke and style
* Sizes:

  * Small: 18
  * Default: 24
  * Large: 32

---

## 12. Accessibility

* Follow Material accessibility guidelines
* Ensure contrast compliance
* Support screen readers
* Provide clear labels and states

---

## 13. Platform Adaptation

### Android

* Full Material behavior (ripple, elevation)
* Native feel prioritized

### iOS

* Replace ripple with opacity/scale
* Slightly increase spacing
* Reduce strict Material visual density

---

## 14. Do / Don't

### Do

* Follow Material system consistently
* Use semantic tokens
* Maintain predictable behavior

### Don't

* Mix non-Material styles
* Override system patterns arbitrarily
* Use inconsistent elevation or color roles

---