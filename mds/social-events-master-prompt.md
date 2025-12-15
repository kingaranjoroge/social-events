
# Master Prompt: Social Events Management & Planning Website

## Role
You are a **senior full-stack engineer and product designer**.

Build a **modern, elegant social events management & planning website** focused on **weddings, birthdays, baby showers, graduations, and private social events**.

This is a **real production-ready web app**, not a demo.

---

## Tech Stack (Strict)

### Frontend
- Next.js (App Router)
- React 19
- Tailwind CSS
- shadcn/ui
- Framer Motion

### Backend
- Next.js Server Actions
- Supabase (Auth, Database, Storage, RLS)

### Deployment
- Vercel
- Environment variables via `.env.local`

---

## Product Goal
Create a **premium, emotionally appealing social events planning platform** that:
- Attracts clients
- Explains services clearly
- Collects event inquiries
- Showcases past events
- Allows admin management via Supabase

---

## Site Structure

### Public Pages
- Home
- Services
- Event Types (Weddings, Birthdays, Baby Showers, Graduations)
- Gallery
- About
- Contact
- Book Consultation

### Utility
- Privacy Policy
- Terms of Service

---

## Core Features (MVP)

### Homepage
- Hero section with emotional copy
- Event types grid
- How it Works (3 steps)
- Featured gallery
- Testimonials
- CTA to Book Consultation

### Services
- Full Event Planning
- Partial Planning
- Day-of Coordination
- Décor & Styling
- Vendor Sourcing

### Event Pages
- Description
- Gallery
- What’s included
- CTA

### Gallery
- Supabase Storage images
- Filter by event type
- Responsive layout

### Booking & Contact
- Event inquiry form
- Persist to Supabase
- Success & error states

---

## Supabase Schema

### event_inquiries
- id (uuid, pk)
- name
- email
- phone
- event_type
- event_date
- location
- budget_range
- message
- created_at

### gallery
- id
- image_url
- event_type
- created_at

### testimonials
- id
- client_name
- event_type
- rating
- comment
- created_at

---

## Security
- Supabase Auth (admin only)
- Public read for gallery & testimonials
- RLS enabled
- Public insert allowed for inquiries
- Admin-only write for gallery & testimonials

---

## UI / UX
- Elegant, warm, celebratory design
- shadcn/ui components
- Tailwind spacing system
- 2xl rounded corners
- Soft shadows

### Animations
- Framer Motion page transitions
- Scroll reveal animations
- Hover micro-interactions

---

## Architecture Rules
- App Router only
- Server Components by default
- Client Components only when required
- Server Actions for forms
- Clean, reusable component structure
- Strong TypeScript typing

---

## Expected Folder Structure

app/
components/
lib/
styles/
types/

---

## SEO & Performance
- Page metadata
- Open Graph tags
- Optimized images
- Lazy loading

---

## Quality Bar
- No lorem ipsum
- No hardcoded data
- Mobile-first
- Clean, readable code

---

## Deliverables
1. Working Next.js app
2. Supabase SQL schema
3. RLS policies
4. Env variable setup
5. README instructions

---

## Final Goal
A **professional social events planning platform** ready for real clients, portfolio use, and future scaling.
