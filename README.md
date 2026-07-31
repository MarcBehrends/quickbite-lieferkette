# QuickBite – Lieferketten App

Inspiriert von Lieferando. Gebaut mit Next.js 14 + Neon Postgres + Tailwind CSS.

## Setup

1. Füge in Vercel eine **Neon Postgres** Datenbank hinzu (Storage → Create → Neon)
2. Verknüpfe sie mit dem Projekt → `DATABASE_URL` wird automatisch gesetzt
3. Rufe einmalig `GET /api/setup` auf um die Tabellen zu erstellen

## Features
- 🍕 6 Restaurants mit Menü
- 🛒 Warenkorb & Checkout
- 📦 Bestellverfolgung
- 🔐 Admin Dashboard (Passwort: admin123)
- 🗄️ PostgreSQL Datenbank (Kunden + Bestellungen)

## Routen
- `/` – Startseite / Restaurant-Auswahl
- `/cart` – Kasse
- `/track` – Bestellung verfolgen
- `/admin` – Admin Dashboard
- `/api/setup` – Datenbank initialisieren
