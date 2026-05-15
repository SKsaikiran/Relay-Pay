<div align="center">

<img src="Creatives/banner.svg" alt="Relay Pay Banner" width="100%"/>

<br/>
<br/>

<p>
  <a href="https://creativecommons.org/licenses/by-nc/4.0/"><img src="https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg" alt="License"/></a>
  <img src="https://img.shields.io/badge/Type-Product%20Feature%20Concept-5B3FD9?style=flat" alt="Type"/>
  <img src="https://img.shields.io/badge/Platform-UPI-orange?style=flat" alt="Platform"/>
  <img src="https://img.shields.io/badge/Built%20with-HTML%20%2B%20CSS%20%2B%20JS-blue?style=flat" alt="Stack"/>
  <img src="https://img.shields.io/badge/Status-Live%20Demo-green?style=flat" alt="Status"/>
</p>

<p>
  <a href="https://sksaikiran.github.io/Relay-Pay/"><img src="https://img.shields.io/badge/Try%20the%20Prototype-Live%20Demo%20%E2%86%92-5B3FD9?style=for-the-badge" alt="Live Demo"/></a>
</p>

<br/>

</div>

---

## The Problem

You are at a shop. Your UPI bank shows a server error. People in the queue are staring. You have no cash. Your phone has full signal. But you still cannot pay.

India processes over **16 billion UPI transactions every month.** Millions still fail or get abandoned because there is no native way to get help from someone you trust without leaving the app.

---

## The Concept

Relay Pay adds a **3-way toggle** to the existing UPI payment screen. One toggle. Three ways to always get through.

<br/>

<div align="center">

| &nbsp;&nbsp;&nbsp;Toggle&nbsp;&nbsp;&nbsp; | What it does |
|:---:|---|
| **Bank** | Standard UPI bank payment |
| **Relay Pay** | Ask a trusted contact to pay on your behalf via a live UPI collect request |
| **Relay Wallet** | Pay instantly from a pre-loaded wallet funded by family or trusted contacts |

</div>

<br/>

No new app. No new habit. Just a smarter toggle inside the UPI app you already use every day.

---

## Feature Flows

### Flow 1: Relay Pay

```
Scan QR  -->  Bank server error  -->  Switch to Relay Pay toggle -->  Pick a trusted contact  -->  Slide to send request -->  Contact receives notification  -->  Contact taps Pay -->  Payment confirmed at merchant
```

### Flow 2: Relay Wallet

```
Scan QR  -->  Bank server error  -->  Switch to Wallet toggle -->  Tap Pay via Wallet  -->  Enter 4-digit MPIN -->  Payment confirmed from pre-loaded funds
```

---

## Why This Fits UPI

- **No new payment rail needed.** Built on UPI collect requests that already exist today.
- **Works across apps.** The payer and requester do not need to use the same UPI app.
- **Adds dignity.** No public phone calls, no WhatsApp QR screenshots, no awkward waits.
- **Relay Wallet is already proven.** FamApp by Trio lets teenagers pay at merchant QRs via a locked wallet. Relay Pay brings this model to every UPI user of all ages.

---

## What is Inside the Prototype

```
index.html  (single file, zero dependencies)
```

| Screen | Description |
|--------|-------------|
| Home | Balance card, quick actions, recent activity, feature tour |
| Scan QR | Camera scanner simulation |
| Pay | Amount input, 3-way toggle, bank and contact and wallet panels |
| Waiting | Live request sent, simulate contact notification |
| Notification | Contact Pay and Decline popup |
| Success | Confirmed payment with vendor QR |
| Failed | Declined or timed out request screen |
| Wallet | Pre-loaded funds, daily spending cap, transaction history |
| History | Full log with payment method icons |
| Contacts | Trusted contacts list |
| Profile | Settings and feature tour replay |

**Interactive feature guide included.** Click-through tutorial with two branches covering both flows, spotlight highlighting, and step-by-step tooltips.

---

## How to Run

**In browser (no install needed)**
```
Download index.html and open it in Chrome, Safari or Firefox
```

**Live hosted version**
```
https://SKsaikiran.github.io/relay-pay
```

---

## Tech

- Pure HTML, CSS and JavaScript
- Zero dependencies, zero frameworks, zero build step
- Single self-contained file
- DM Sans and DM Mono via Google Fonts
- Responsive on mobile and desktop

---

## Important Note

This is a **product feature concept and interactive prototype.** It is not a real application and is not affiliated with NPCI, PhonePe, Google Pay, Paytm, CRED or any other UPI provider. It is shared as a portfolio piece to explore how existing UPI infrastructure could support a native payment delegation layer.

---

## Author

<div align="center">

**Sai Kiran J**

*Product Feature Concept and Interactive Prototype*

[![Email](https://img.shields.io/badge/Email-Saikiranj2002%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:Saikiranj2002@gmail.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sksaikiranj)

</div>

---

## License

Copyright (c) 2025 Sai Kiran J

Licensed under [Creative Commons Attribution-NonCommercial 4.0 International.](https://creativecommons.org/licenses/by-nc/4.0/)

Shared for portfolio and educational purposes. Commercial use requires written permission from the author.

Contact: Saikiranj2002@gmail.com
