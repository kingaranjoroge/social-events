
# Cursor Step-by-Step Build Plan (Recommended Workflow)

This document defines the **high-level phases** for building the Social Events Management & Planning website.
Use this as a **roadmap and checklist**, NOT as a prompt to paste into Cursor.

---

## Phase 0: Project Setup
- Initialize Next.js (App Router, TypeScript)
- Install Tailwind CSS
- Install shadcn/ui
- Install Framer Motion
- Create base layout with navbar and footer

---

## Phase 1: Design System & Layout
- Reusable UI components
- Typography system
- Spacing & layout wrappers
- Responsive navbar and footer

---

## Phase 2: Static Pages (No Backend)
- Home
- Services
- Event Types
- Gallery
- About
- Contact
- Book Consultation
- Add Framer Motion animations

---

## Phase 3: Supabase Backend Setup
- Create tables (event_inquiries, gallery, testimonials)
- Enable Row Level Security
- Write RLS policies
- Configure Supabase client

---

## Phase 4: Server Actions & Forms
- Implement booking form
- Persist inquiries to Supabase
- Add loading, success, error states

---

## Phase 5: Dynamic Content
- Fetch gallery from Supabase Storage
- Fetch testimonials
- Filtering by event type

---

## Phase 6: Polish & SEO
- SEO metadata
- Open Graph tags
- Accessibility improvements
- Performance optimizations

---

## Final Goal
A production-ready social events planning website suitable for real clients and portfolio use.
