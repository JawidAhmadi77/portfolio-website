# Flagship Projects — Case Notes

## 🏥 Hospital PRO
Complete hospital & clinic management: patient registration with lifetime MRN, OPD token queue, doctor workbench, laboratory and radiology, pharmacy stock with batch/expiry (FEFO), inpatient beds, billing with per-cashier shifts, company/insurance credit (khata) and an owner dashboard.
**Stack:** Django REST + React, MySQL/SQLite, Flutter/PWA mobile. Bilingual English/Dari, offline-first.
**Showcase:** https://github.com/JawidAhmadi77/hospital-pro

## 🎓 Institute PRO
Institute & course management: programmes → levels → batches with price snapshots, a full enrolment lifecycle, a fees engine with printable receipts and defaulters tracking, books & materials, attendance, exams and certificates.
**Stack:** Django REST + React, SQLite/MySQL, Flutter/PWA mobile. Bilingual with a Shamsi calendar, offline-first.

## 🛒 SuperMarket PRO
Supermarket management: multi-till POS with barcode/PLU, inventory from a movement ledger with 30/7-day expiry alerts, purchases and supplier khata, customer loyalty and khata, promotions, per-cashier shifts with Z-reports and owner profit reports. Security from day one: hashed PINs, weak-PIN rejection, and cashier roles that cannot see revenue or profit.
**Stack:** Django REST + React, MySQL (multi-till), Flutter/PWA mobile. Bilingual, offline-first.

---
All three systems are commercial products of Wakhan Technologies. Their source code is private; recruiters and clients can request a live demo or a guided walkthrough.

## 🏛️ Maison Élégance — Fine Dining
A complete luxury fine-dining platform built to an international design standard: modular Django backend (restaurant, menu, reservations, gallery, reviews, contact) behind a versioned REST API (/api/v1/) with JWT staff auth, and a React + TypeScript front end in a charcoal-and-champagne-gold editorial design. Reservations are driven by the restaurant's real opening hours — slots are generated per day, every table is held for a 2-hour seating, and overlapping bookings are rejected inside a database transaction, so a table can never be promised twice. Guests get an ME-XXXXXX confirmation code and can cancel with it; staff manage the book from a secured API and Django admin.
**Stack:** Django + Django REST Framework + PostgreSQL (SQLite locally), React + TypeScript + Vite + Tailwind CSS, TanStack Query, Framer Motion, React Hook Form + Zod.
**Live demo:** https://maison-elegance-brown.vercel.app (API: https://maison-elegance-api.vercel.app/api/v1/)
**Concierge chatbot:** built into the site — it answers from the live menu and opening hours and books or cancels a table inside the chat, with a real ME confirmation code.
A demonstration brand — menu and reviews are editable sample content, marked as such in the product; the engineering is real, with 31 backend tests covering the booking rules.
