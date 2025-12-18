# HomeHelp

<p>
  <img src="https://img.shields.io/badge/6%20Platforms-iOS%20%7C%20Android%20%7C%20Web%20%7C%20Windows%20%7C%20macOS%20%7C%20Linux-0891b2" alt="Platforms">
  <img src="https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter" alt="Flutter">
  <img src="https://img.shields.io/badge/Firebase-Firestore%20%7C%20Auth-FFCA28?logo=firebase" alt="Firebase">
  <img src="https://img.shields.io/badge/Tests-103%20Passing-22c55e" alt="Tests">
</p>

<p>
  <b>On-demand home services marketplace connecting customers with trusted professionals</b>
</p>

<p>
  <i>Book plumbers, electricians, cleaners, and more — with real-time chat, instant booking, and secure payments.</i>
</p>

<p>
  <a href="https://homehelp-app.web.app">🌐 Live Demo</a> •
  <a href="https://github.com/shahinwahab/homehelp/releases/latest/download/homehelp.apk">📥 Download APK</a>
</p>

---

## 📱 App Preview

<p align="center">
  <a href="https://youtube.com/watch?v=YOUR_VIDEO_ID">
    <img src="docs/ui/homehelp-thumbnail.webp" alt="Watch Demo" width="600">
  </a>
</p>

## ✨ Features

### For Customers
- 🔍 **Browse & Search** — Find workers by service category, rating, and availability
- 📅 **Instant Booking** — Select date, time, and service with real-time confirmation
- 💬 **Real-Time Chat** — Live messaging with typing indicators, online/offline presence, and instant delivery
- 💳 **Flexible Payments** — Pay via cash or online (FIB, FastPay)
- ⭐ **Reviews & Ratings** — Rate completed jobs and read worker reviews

### For Workers
- 💼 **Service Management** — List and manage offered services with pricing
- 📋 **Job Requests** — Accept or decline incoming booking requests
- 📊 **Earnings Dashboard** — Track completed jobs and earnings

### Technical Highlights
- 🔄 **Real-Time Sync** — Firestore streams for instant updates across all screens
- 💬 **Presence System** — Live online/offline status with typing indicators
- 🌙 **Dark Mode** — Full dark theme support
- 📱 **Responsive** — Adapts from mobile to desktop
- 🔐 **Secure Auth** — Email/password + Google Sign-In
- ✅ **103 Unit Tests** — Comprehensive test coverage

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

**Key Patterns:** Clean Architecture • Feature-based Modules • Repository Pattern • GetX State Management

## 👨‍💻 Built by

**Shahin Wahab** — Software Engineer

[![Portfolio](https://img.shields.io/badge/Portfolio-shahinwahab.com-0891b2?style=for-the-badge)](https://shahinwahab.com) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/shahinwahab)

---
> **Repository created on:** 2025-12-08, 22:33 (UTC+3)
