[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

# Relay Pay

**A UX concept that adds payment delegation natively into UPI apps.**

Live Demo → [relay-pay.github.io](https://your-username.github.io/relay-pay)

---

## What is Relay Pay?

Relay Pay is a product design concept exploring a single question:

> What if you could ask someone else to pay for you — without leaving your UPI app?

Today when your bank server is down, your balance is low, or you simply need a family member to cover a payment, the workaround is manual and fragmented: call someone, read out a QR, screenshot, WhatsApp, wait. Relay Pay solves this with one toggle inside the payment screen.

---

## The Problem

India processes over 16 billion UPI transactions every month. Millions still fail or get abandoned due to:

- Bank server errors at point of sale
- Insufficient balance at checkout
- No way to ask a trusted person to pay without leaving the app

The infrastructure is ready. The habit is set. What is missing is a native way to get help paying.

---

## The Solution — A 3-Way Toggle

At the payment screen, instead of one option (your bank), Relay Pay gives you three:

| Toggle | What it does |
|--------|-------------|
| **Bank** | Standard UPI bank payment |
| **Relay Pay** | Ask a trusted contact to pay on your behalf via a live UPI collect request |
| **Relay Wallet** | Pay instantly from a pre-loaded wallet funded by family or trusted contacts |

---

## Feature Flows

### Flow 1 — Relay Pay
```
Scan QR → Bank server error → Switch to Relay Pay toggle
→ Pick a trusted contact → Slide to send request
→ Contact receives notification → Contact taps Pay
→ Payment confirmed at merchant
```

### Flow 2 — Relay Wallet
```
Scan QR → Bank server error → Switch to Wallet toggle
→ Tap Pay via Wallet → Enter 4-digit MPIN
→ Payment confirmed from pre-loaded funds
```

---

## Why This Fits UPI Perfectly

- **No new payment rail needed** — built on UPI collect requests that already exist
- **Any UPI app can implement it** — payer and requester don't need the same app
- **Adds dignity** — no public phone calls, no WhatsApp QR screenshots
- **Relay Wallet is proven** — FamApp by Trio already does this for teenagers paying at merchant QRs. Relay Pay brings it to everyone.

---

## What's Inside the Prototype

- Full interactive mobile UI (420px phone shell)
- Working 3-way payment toggle
- Contact search and selection
- Live request waiting screen with simulate button
- Notification popup with Pay / Decline
- Payment failed screen (declined flow)
- Relay Wallet with MPIN keypad
- Transaction history with payment method icons
- Interactive feature guide (Call of Duty style — user clicks through)
- Two guide branches: Relay Pay flow and Wallet flow

---

## How to Run

**Option 1 — Open directly**
Download `index.html` and open it in any browser. No server needed.

**Option 2 — Live hosted version**
Visit the GitHub Pages link at the top of this README.

---

## Tech Stack

- Pure HTML, CSS, JavaScript — zero dependencies, zero frameworks
- Single file, fully self-contained
- DM Sans + DM Mono via Google Fonts
- Works on mobile and desktop browsers

---

## Screens

| Screen | Description |
|--------|-------------|
| Home | Balance, quick actions, recent activity, feature tour button |
| Scan QR | Camera scanner simulation |
| Pay | Amount input, 3-way toggle, contact/bank/wallet panels |
| Waiting | Live request sent, simulate contact notification |
| Notification | Contact's Pay / Decline popup |
| Success | Confirmation with vendor QR |
| Failed | Declined or timed out request |
| Wallet | Pre-loaded funds, daily cap, transaction history |
| History | Full transaction log with payment method icons |
| Contacts | Trusted contacts list |
| Profile | Settings and feature tour replay |

---

## Concept Context

This is not a real application. It is a UX proposal demonstrating how existing UPI infrastructure could be extended with a delegation layer — enabling payments to flow through trusted relationships rather than breaking when a single bank fails.

The concept is relevant to any UPI app: PhonePe, Google Pay, Paytm, CRED, or a future NPCI-native implementation.

---

## Author

**Sai Kiran J**

Built as a UX concept and interactive prototype.

Connect on LinkedIn → [your LinkedIn URL]

Email → Saikiranj2002@gmail.com

---

## License

© 2025 Sai Kiran J

Licensed under Creative Commons Attribution-NonCommercial 4.0 International.
Shared for portfolio and educational purposes. Commercial use requires written permission.

Contact: Saikiranj2002@gmail.com
