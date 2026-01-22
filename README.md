# HomeHelp

<p>
  <img src="https://img.shields.io/badge/6%20Platforms-iOS%20%7C%20Android%20%7C%20Web%20%7C%20Windows%20%7C%20macOS%20%7C%20Linux-0891b2" alt="Platforms">
  <img src="https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter" alt="Flutter">
  <img src="https://img.shields.io/badge/Firebase-Firestore%20%7C%20Auth-FFA000?logo=firebase" alt="Firebase">
  <img src="https://img.shields.io/badge/Cloudinary-Image%20CDN-3448C5?logo=cloudinary" alt="Cloudinary">
  <img src="https://img.shields.io/badge/Tests-103%20Passing-22c55e" alt="Tests">
</p>

###  Two-sided home services marketplace with real-time chat and payment tracking

<p>
  <i>Customers book services, workers manage jobs — WhatsApp-style messaging, quote negotiation, one Flutter codebase.</i>
</p>

<p>
  <a href="https://homehelp-app.web.app">🌐 Live Demo</a> •
  <a href="https://github.com/shahinwahab/homehelp/releases/latest/download/homehelp.apk">📥 Download APK</a> •
  <a href="https://github.com/shahinwahab/homehelp/releases/latest/download/homehelp.exe">📥 Windows</a>
</p>

---

## 📱 App Preview

<p align="left">
    <img src="docs/ui/homehelp-thumbnail.webp" alt="Screenshots" width="600">
</p>

## ✨ Features

### For Customers
- 🔍 **Browse & Search** — Find workers across 6 categories (Plumber, Electrician, Carpenter, Painter, AC Repair, Cleaner)
- 📅 **Instant Booking** — Book service packages or request custom quotes with price negotiation
- 💬 **Real-Time Chat** — Full messaging with typing indicators, read receipts, image sharing, emoji reactions, and reply threads
- 💳 **Flexible Payments** — Cash or online (FIB, FastPay) with full payment status tracking
- ⭐ **Reviews & Ratings** — Rate completed jobs and read worker reviews

### For Workers
- 💼 **Service Management** — Create service packages with fixed pricing or accept custom quote requests
- 📋 **Job Requests** — Accept or decline bookings, respond to quote requests with pricing
- 📊 **Earnings Dashboard** — Track completed jobs, pending requests, and total earnings

### Technical Highlights
- 🔄 **Real-Time Sync** — Firestore streams for instant updates across all screens
- 💬 **Presence System** — Live online/offline status with typing indicators
- 🌙 **Dark Mode** — Full dark theme support
- 📱 **Adaptive Layout** — Master-detail views on tablet/desktop, responsive on mobile
- 🔐 **Secure Auth** — Email/password + Google Sign-In
- 🧪 **103 Unit Tests** — Comprehensive test coverage

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────────────┐
│                    Presentation Layer                   │
│         (Screens, Widgets, GetX Controllers)            │
├─────────────────────────────────────────────────────────┤
│                      Domain Layer                       │
│            (Entities, Use Cases, Repositories)          │
├─────────────────────────────────────────────────────────┤
│                       Data Layer                        │
│        (Models, Remote DataSources, Firestore)          │
└─────────────────────────────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────┐
│                    External Services                    │
│         Firebase Auth │ Firestore │ Cloudinary          │
└─────────────────────────────────────────────────────────┘
```

**Key Patterns:** Clean Architecture • Feature-based Modules • Repository Pattern • GetX State Management • GetIt DI • go_router Navigation

## 👨‍💻 Built by

**Shahin Wahab** — Software Engineer

#### <a href="https://shahinwahab.com">🌐 shahinwahab.com</a> • <a href="https://linkedin.com/in/shahinwahab">💼 LinkedIn</a>

---
> **Repository created on:** 2025-12-08, 22:33 (UTC+3)
