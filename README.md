# ATLAS Gymweb

## Overview

This project is a premium single-page gym marketing website for ATLAS — a private strength and performance club based in DHA, Karachi. Based on the UI copy and component structure, it is a modern landing page for a high-end fitness brand rather than a full backend application, e-commerce platform, or mobile app.

The site presents the club’s positioning, facilities, membership tiers, coaches, recovery offerings, location details, and an application-based enrollment flow. It is built as a Vite + React + TypeScript front-end and uses Tailwind CSS for styling.

## Project type

Type: marketing website / luxury gym landing page

This is not a multi-page SaaS app, API backend, or commerce storefront. The app is a client-side website built as a single-page experience with multiple animated sections and CTAs.

## Tech stack

The codebase clearly uses the following technologies:

- React 18
- TypeScript
- Vite 5
- Tailwind CSS 3
- ESLint
- PostCSS
- Node.js-based frontend tooling
- @supabase/supabase-js (installed dependency, but no visible usage in the current UI)

From package.json:

- React app scaffold: Vite
- Package manager: npm (package-lock.json present)
- Build tool: Vite
- Styling: Tailwind CSS
- Type-checking: TypeScript
- Linting: ESLint

## What the project does

The app is a polished gym landing page with sections such as:

- Hero section with a large fitness background image and invitation CTA
- Brand trust bar highlighting equipment and certification associations
- Philosophy section explaining the club’s performance-first training model
- Facility showcase with gym strength floor, recovery suite, and private training bay
- Membership pricing tiers: Initiate, Athlete, and Private
- Coach profiles with specialties
- Recovery and wellness offerings: infrared sauna, cold plunge, nutrition
- Coffee and protein bar area
- Testimonials from members
- Location and access details
- Footer with application CTA and contact information

The site is designed for a premium fitness audience and communicates a private-membership, by-application model.

## Main application structure

Key files and entry points:

- src/main.tsx — app bootstrap
- src/App.tsx — assembles the page sections
- src/index.css — Tailwind base styles and global theme definitions
- src/components/ — page sections and reusable animated UI pieces

Notable components:

- Hero.tsx — landing/intro hero
- TrustBar.tsx — brand/equipment trust list
- Philosophy.tsx — club value proposition
- Facilities.tsx — facility gallery and captions
- Membership.tsx — three-tier package pricing panel
- Coaches.tsx — trainer portraits and specialties
- Recovery.tsx — wellness and recovery story
- CoffeeBar.tsx — coffee/protein bar feature
- Testimonials.tsx — social proof
- Location.tsx — address, hours, and application steps
- Footer.tsx — final contact and CTA block
- Reveal.tsx — scroll-reveal animation helper

## Build and run

Prerequisites:

- Node.js and npm installed

Install dependencies:

```bash
npm install
```

Start the dev server:

```bash
npm run dev
```

Create a production build:

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

Run linting:

```bash
npm run lint
```

Run TypeScript checking:

```bash
npm run typecheck
```

## Scripts from package.json

- dev — starts the Vite development server
- build — packages the app for production
- lint — runs ESLint
- preview — serves the production build locally
- typecheck — runs TypeScript type checking

## Styling and design system

The project uses Tailwind CSS with a custom theme in tailwind.config.js. The site has a dark luxury aesthetic with:

- dark charcoal background colors
- warm brass accents
- bone/ivory text tones
- serif display typography with a premium, editorial feel

Global styling is defined in src/index.css, including smooth scrolling, scrollbar styling, and custom utility classes.

## Business and audience context

Based on the written content in the app, the project targets:

- high-end gym members in Karachi
- strength athletes and performance-focused clientele
- people seeking a private, premium, and application-based training environment

The brand name and copy consistently describe ATLAS as a private strength and performance club with restricted access and a methodical training philosophy.

## Important implementation notes

- There is no backend server or database layer configured in the project structure at the top level.
- There is no router configuration found in the app; it is a single-page landing page.
- A Supabase dependency is present, but the current codebase does not show any Supabase integration or database usage in the active screens.
- The site relies on remote Unsplash/Pexels images for the photography and branding visuals.
- Some footer/social links are placeholder anchors (href="#") and may be incomplete.

## Project status

This is a front-end promotional website for a gym/fitness club. It is ready for visual review and further customization, but it does not currently include a live booking backend, CMS, membership management system, or user authentication flow.

## Summary

ATLAS Gymweb is a luxury single-page fitness club website built with React, TypeScript, Vite, and Tailwind CSS. It presents a premium gym brand, membership structure, coaching roster, recovery features, and application-based access model aimed at a high-end strength and performance audience in Karachi.
