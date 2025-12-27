<div align="center">

  <img src="https://img.shields.io/badge/✨%20Vibe%20Coded-100%25-FBbf24?style=for-the-badge&logo=sparkles&logoColor=black" alt="Vibe Coded" />
  <br />
  <br />

  <h1>⚡ Auction Elite</h1>
  
  <p>
    <strong>The ultimate serverless bidding arena. Auction Elite lets you host high-stakes, real-time auctions with zero backend and maximum style.</strong>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Architecture-P2P%20Serverless-blueviolet?style=flat-square" alt="Architecture" />
    <img src="https://img.shields.io/badge/Tech-WebRTC%20%7C%20PeerJS%20%7C%20Confetti-blue?style=flat-square" alt="Tech Stack" />
    <a href="https://github.com/shubhambelbase">
      <img src="https://img.shields.io/github/stars/shubhambelbase?style=social" alt="Stars" />
    </a>
  </p>

  <h3>
    <a href="#">🔴 View Live Demo</a>
  </h3>
</div>

## ⚡ The Vibe

This isn't just an auction tool; it's a **digital bidding stadium**. Vibe coded to feel premium, responsive, and intense, Auction Elite reinvents the live selling experience.

Built entirely in the flow state, it pushes the limits of client-side technology—handling real-time bid synchronization, live leaderboards, and **victory celebrations** without a single backend server. It's just you, your bidders, and the thrill of the win.

## 💡 What It Does

**Auction Elite** establishes a secure, direct connection between a Host (Auctioneer) and unlimited Bidders via WebRTC.

* **The Problem:** Auction software is expensive, requires logins, and feels clunky and corporate.
* **The Solution:** A browser-based, instant collaboration tool. Open the link, create a room, and **let friends join via QR Code**. Bid instantly. **Celebration by design.**


## ✨ Key Features

| 🏆 **Host Experience** | 📱 **Bidder Experience** |
| :--- | :--- |
| **🔗 Smart QR Invite:** Auto-generates full join links | **Responsive Grid:** Optimized 3-column layout for mobile tapping |
| **🛑 Panic Button:** Host can force-end an auction instantly | **Smart Buttons:** Bids disable automatically if they exceed limits |
| **📊 Live Leaderboard:** Ranks top bidders in real-time | **🎉 Victory Confetti:** Massive visual explosion for winners |
| **🔔 Toast Notifications:** Smooth pop-up alerts for every action | **🌓 Vibe Themes:** Toggle between "Midnight Glass" & "Clean Day" |
| **🔊 Interactive SFX:** Audio cues for bids and wins | **Zero Lag:** Bids sync directly via WebRTC data channels |

## 🛠️ Built With

* **WebRTC (PeerJS):** For sub-second, encrypted P2P state synchronization.
* **Canvas Confetti:** For the physics-based celebration effects.
* **QRCode.js:** For instant mobile pairing and session sharing.
* **Glassmorphism CSS:** For the premium, translucent UI aesthetic.
* **Vanilla JS:** Zero framework bloat for maximum performance on any device.

## 🚀 How to Run

Because this app uses WebRTC, **it works best via HTTPS** or `localhost`.

### Option 1: The "It's Just One File" Method
1.  Download the `index.html` file.
2.  Open it in your browser.
3.  That's it. Seriously.

### Option 2: GitHub Pages / Netlify (Recommended for Mobile)
1.  Fork this repo.
2.  Deploy to **GitHub Pages** or **Netlify**.
3.  Open the site on your Laptop (Host).
4.  Scan the **QR Code** with your Phone (Bidder).

### Option 3: Local Network
1.  **Clone the repo:**
    ```bash
    git clone [https://github.com/shubhambelbase/AuctionElite.git](https://github.com/shubhambelbase/AuctionElite.git)
    ```
2.  **Run with a live server:**
    (VS Code "Live Server" extension is recommended)
    ```bash
    npx serve .
    ```

## 📖 How to Use

1.  **Host Mode (The Auctioneer):**
    * Open the app and click **"Create Host"**.
    * A **QR Code** will appear. Show this to your friends to auto-join.
    * Fill in the **"New Lot"** form (Item Name, Start Price, Buyout Limit).
    * Click **"Initialize Auction"** to start the timer.
    * Click **"End Now"** if you want to declare a winner immediately.

2.  **Join Mode (The Bidder):**
    * **Scan the QR Code** (or click the invite link).
    * Enter your **Alias** (Display Name).
    * Wait for the Host to start a lot.
    * Tap the bid buttons (`+5`, `+50`, etc.) to fight for the item.
    * If you win... enjoy the confetti! 🎉

## 🤝 Contributing

Got an idea to make the economy even more chaotic?
1.  Fork it.
2.  Create your Feature Branch (`git checkout -b feature/CryptoBidding`)
3.  Commit your Changes.
4.  Push to the Branch.
5.  Open a Pull Request.

---

<div align="center">
  <p>Vibe coded with ❤️ by <a href="https://github.com/shubhambelbase">Shubham Belbase</a></p>
</div>

