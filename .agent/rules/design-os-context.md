# Design OS Context

When working in Design OS, be aware of two distinct contexts:

## 1. Design OS Application

The React application that displays and manages planning files. When modifying the Design OS UI itself:

- Files live in `src/` (components, pages, utilities)
- Uses the Design OS design system (stone palette, DM Sans, etc.)
- Provides the interface for viewing specs, screen designs, exports, etc.

## 2. Product Design (Screen Designs & Exports)

The product you're planning and designing. When creating screen designs and exports:

- Screen design components live in `src/sections/[section-name]/` and `src/shell/`
- Product definition files live in `product/`
- Exports are packaged to `product-plan/` for integration into a separate codebase
- Follow the design requirements specified in each section's spec
