<div align="center">

  <br />
  <h1>🛡️ Fintact</h1>
  <p><strong>Tactical Financial Clarity for Your Money</strong></p>

  <p>
    A sleek, lightweight, offline-first Progressive Web App (PWA) built for modern expense tracking, envelope-style savings budgeting, and dynamic multi-currency management with real-time rate updates.
  </p>

  <p>
    <a href="#key-features">Key Features</a> •
    <a href="#live-demo--installation">Installation</a> •
    <a href="#technical-stack">Tech Stack</a> •
    <a href="#license">License</a>
  </p>

</div>

---

## 🚀 Key Features

- **💱 Live Exchange Rates & Conversion**
  - Connects to live exchange rate APIs to automatically convert and display estimates across all currencies into Philippine Pesos ($\approx\text{ ₱}$).
  - **Network Status Badge:** Displays a green **Live Rates Active** badge when connected, and gracefully switches to a red **Live Rates Inactive** badge with cached rates when offline.

- **🎯 Tactical Savings Buckets (Envelope Budgeting)**
  - Allocate total available funds across up to **10 custom savings buckets** (e.g., *Emergency Fund*, *Travel*, *Investments*).
  - Set optional target goals with visual real-time progress bars.
  - Seamlessly transfer funds between your main pool and specific savings buckets.

- **📱 Mobile-First & Swipe Navigation**
  - Smooth horizontal swipe gestures to easily slide between **Dashboard**, **Manage**, **History**, and **Settings** tabs on mobile devices.
  - Full PWA support—install directly to your iOS or Android home screen for a standalone native app experience.

- **📊 Expense Logging & Data Export**
  - Log categorized expenses directly against main funds or specific savings buckets.
  - Filter transaction history by daily spending or full historic logs.
  - **Export to CSV:** One-click spreadsheet download for offline archiving and analysis.

- **🎨 Themes & Privacy**
  - Built-in Dark Mode and Light Mode options.
  - **100% Client-Side Privacy:** All data is stored locally on your device via `localStorage`—no sign-ups, tracking, or external database required.

---

## 🛠️ Technical Stack

- **Frontend:** HTML5, CSS3 (Custom Variables & CSS Grid), Pure JavaScript (ES6+)
- **Storage:** `localStorage` for persistent local state
- **PWA Capabilities:** Dynamic Inline Service Workers & Web App Manifest
- **Graphics:** Embedded SVG with on-the-fly HTML5 Canvas generation for high-res Apple Touch Icons
- **API Integration:** Asynchronous Fetch API with `AbortController` timeout protection (`open.er-api.com`)

---

## 📦 Installation & Local Setup

Because **Fintact** is engineered as an all-in-one single-file application, running it locally requires no build steps or dependencies:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Toyyyitts/fintact.git](https://github.com/Toyyyitts/fintact.git)
