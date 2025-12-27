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
<img src="https://img.shields.io/badge/Tech-WebRTC%20%7C%20PeerJS%20%7C%20Canvas--Confetti-blue?style=flat-square" alt="Tech Stack" />
<img src="https://img.shields.io/badge/Size-Single%20HTML%20File-success?style=flat-square" alt="Lightweight" />
</p>
<h3>
<a href="#">🔴 View Live Demo (Deploy to see)</a>
</h3>
</div>
⚡ The Vibe
This isn't just an auction tool; it's a digital bidding stadium. Vibe coded to feel premium, responsive, and intense, Auction Elite reinvents the live selling experience.
Built entirely for the browser, it pushes the limits of Peer-to-Peer technology—handling real-time bid synchronization, live leaderboards, and victory celebrations without a single database. It's just you, your bidders, and the thrill of the win.
💡 What It Does
Auction Elite establishes a direct, low-latency connection between a Host (Auctioneer) and unlimited Bidders.
 * The Problem: Auction software is expensive, requires logins, and feels clunky and corporate.
 * The Solution: A futuristic, single-file web app. Open the link, create a room, and let friends join via QR Code. Bid instantly. Celebration by design.
✨ Key Features
| 🏆 Host Control & Experience | 📱 Bidder & Mobile Experience |
|---|---|
| 🔗 Smart QR Invite: Auto-generates join links for instant mobile access | Responsive UI: Optimized 3-column grid for mobile tapping |
| 🛑 Panic Button: Host can force-end an auction instantly | Smart Buttons: Bids disable automatically if they exceed limits |
| 📊 Live Leaderboard: Ranks top bidders in real-time | 🎉 Victory Confetti: Massive visual explosion for winners |
| 🔔 Toast Notifications: Smooth pop-up alerts for every action | 🌓 Vibe Themes: Switch between "Midnight Glass" & "Clean Day" |
| 🔊 Sound FX: Interactive audio cues (with Mute toggle) | Zero Lag: Bids sync directly via WebRTC data channels |
🛠️ Built With
 * WebRTC (PeerJS): For sub-second, encrypted P2P state synchronization.
 * Canvas Confetti: For the physics-based celebration effects.
 * QRCode.js: For instant mobile pairing and session sharing.
 * Glassmorphism CSS: For the premium, translucent UI aesthetic.
 * Vanilla JS: No frameworks, no build steps, just raw performance.
🚀 How to Run
Because this app uses WebRTC (camera/mic permissions aren't used, but P2P data is), it works best via HTTPS or localhost.
Option 1: The "It's Just One File" Method
 * Download the index.html file.
 * Open it in your browser.
 * That's it. Seriously.
Option 2: GitHub Pages / Netlify (Recommended for Mobile)
 * Fork this repo.
 * Deploy to GitHub Pages or Netlify.
 * Open the site on your Laptop (Host).
 * Scan the QR Code with your Phone (Bidder).
Option 3: Local Network
 * Clone the repo:
   git clone https://github.com/shubhambelbase/AuctionElite.git

 * Run with a live server:
   (VS Code "Live Server" extension is recommended)
   npx serve .

📖 How to Use
👑 Host Mode ( The Auctioneer )
 * Open the app and click "Create Host".
 * A QR Code will appear. Show this to your friends (or copy the Invite Link).
 * Fill in the "New Lot" form (Item Name, Start Price, Buyout Limit).
 * Click "Initialize Auction".
 * Watch the bids fly in! Click "End Now" if you want to sell immediately.
💸 Join Mode ( The Bidder )
 * Scan the QR Code or click the invite link.
 * Enter your Alias (Display Name).
 * Wait for the Host to start a lot.
 * Tap the bid buttons (+5, +50, etc.) to fight for the item.
 * If you win... enjoy the confetti! 🎉
🤝 Contributing
Got an idea to make the economy even more chaotic?
 * Fork it.
 * Create your Feature Branch (git checkout -b feature/CryptoBidding)
 * Commit your Changes.
 * Push to the Branch.
 * Open a Pull Request.
<div align="center">
<p>Vibe coded with ⚡ by <a href="https://github.com/shubhambelbase">Shubham Belbase</a></p>
</div>
