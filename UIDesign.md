# UI Design Requirements — Microsoft Metro Design Language

## Design Direction

Use the **Microsoft Metro Design Language**, as seen in Windows Phone 7 and Windows Phone 8, as the primary visual reference for the application's UI.

The goal is to reproduce the distinctive Metro design philosophy, not merely apply a generic flat design style.

## Core Design Principles

- **Content First** — Prioritize meaningful content over decorative UI elements

- **Typography First** — Use typography, font size, weight, and spacing to establish visual hierarchy

- **Authentic Flat Design** — Prefer solid colors, clean geometric shapes, and simple surfaces

- **Grid-Based Layout** — Organize content using consistent alignment, spacing, and rectangular regions

- **Generous Whitespace** — Keep layouts clean, readable, and uncluttered

- **Motion with Purpose** — Use restrained transitions and animations to communicate navigation, state changes, and feedback

## Visual Style

- Use large, expressive headings inspired by Windows Phone 7/8 typography

- Use clean sans-serif fonts with clear typographic hierarchy

- Prefer solid-color backgrounds and accent colors

- Use simple rectangular tiles and content blocks where appropriate

- Keep borders, shadows, gradients, textures, and decorative effects to a minimum

- Use simple, consistent icons with a coherent visual language

- Maintain strong contrast and clear visual separation between content sections

## Layout and Interaction

- Use consistent grids, alignment, spacing, and margins

- Make navigation and information hierarchy immediately understandable

- Provide clear hover, pressed, focused, selected, disabled, and loading states

- Use subtle animations only when they improve usability

- Preserve keyboard accessibility and appropriate focus indicators

- Adapt the layout to different window sizes without losing the Metro visual identity

## Avoid

- Generic modern SaaS dashboard aesthetics

- Excessive rounded cards and pill-shaped controls

- Heavy drop shadows, glassmorphism, and excessive transparency

- Decorative gradients and skeuomorphic textures

- Unnecessary borders, separators, and ornamental icons

- Mixing unrelated design systems without a clear reason

## Implementation Requirements

- Inspect the existing project structure, UI framework, components, and styling conventions before making changes

- Reuse existing components and styles where appropriate

- Establish consistent design tokens for colors, typography, spacing, and component states

- Apply the design consistently across all relevant screens and components

- Preserve existing functionality unless a change is explicitly required

- Avoid unrelated refactoring

- Verify the final UI for visual consistency, responsiveness, accessibility, and usability

## Reference and Fidelity

Use authentic Windows Phone 7/8 interfaces as the primary visual reference.

Do not confuse the original Metro aesthetic with later Microsoft Fluent Design, Windows 11 styling, Material Design, or generic flat UI.

When a design decision is ambiguous, prioritize typography, content hierarchy, geometric simplicity, bold color blocking, and functional clarity.

## Authentic Metro Fidelity

Aim for a faithful Windows Phone 7/8 aesthetic rather than a modern reinterpretation.

- Prefer edge-aligned rectangular layouts over floating card-based layouts

- Use large, lightweight page headings and strong typographic hierarchy

- Use panoramic or pivot-style navigation only when appropriate for the information architecture

- Use square or rectangular tiles instead of rounded dashboard cards

- Prefer dark or light solid backgrounds with a restrained accent palette

- Keep interface chrome minimal and let content dominate the screen

- Avoid introducing Windows 11 Fluent visual effects or contemporary SaaS dashboard conventions


