<h1 align="center">SaveRedGifs</h1>
<h3 align="center">Free Online RedGifs Video Downloader — HD Quality, No App Required</h3>

<p align="center">
  <a href="https://saveredgifs.com"><img src="https://img.shields.io/badge/Website-saveredgifs.com-blue?style=for-the-badge" alt="Website"></a>
  <img src="https://img.shields.io/badge/Node.js-18.x-green?style=for-the-badge&logo=node.js" alt="Node.js">
  <img src="https://img.shields.io/badge/Express-4.x-lightgrey?style=for-the-badge&logo=express" alt="Express">
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge" alt="PRs Welcome">
</p>

<p align="center">
  <a href="https://saveredgifs.com"><b>🌐 Visit Website</b></a> •
  <a href="#-features"><b>✨ Features</b></a> •
  <a href="#-how-to-use"><b>📖 How to Use</b></a> •
  <a href="#-tech-stack"><b>🛠️ Tech Stack</b></a> •
  <a href="#-faq"><b>❓ FAQ</b></a>
</p>

---

## 📖 About

**SaveRedGifs** is a fast, free, and user-friendly online RedGifs video downloader that lets you save RedGifs videos and GIFs directly to your device in full **HD quality**. Whether you're on a desktop, tablet, or mobile phone, SaveRedGifs works seamlessly in your browser — with no app installation, no signup, and no usage limits.

We built SaveRedGifs to solve a simple problem: existing RedGifs downloaders are often slow, cluttered with ads, riddled with redirects, or lock features behind paywalls. Our goal is to provide a clean, lightweight, ad-light experience that just works — every time.

👉 **Try it now:** [https://saveredgifs.com](https://saveredgifs.com)

---

## ✨ Features

| Feature | Description |
| :--- | :--- |
| 🆓 **100% Free** | No subscriptions, no hidden fees, no premium tiers |
| 🔐 **No Signup Required** | Start downloading instantly — no account creation |
| 🎥 **HD Video Downloads** | Save videos in their original highest available resolution |
| 📱 **Cross-Platform** | Works on Windows, macOS, Linux, Android, and iOS |
| ⚡ **Lightning Fast** | Optimized backend delivers downloads in seconds |
| 🧼 **Ad-Light Interface** | Minimal, non-intrusive UI focused on the task |
| 🔒 **Privacy First** | We don't store your URLs, downloads, or personal data |
| 🌐 **Browser-Based** | No software, plugins, or browser extensions needed |
| 🔄 **Unlimited Downloads** | No daily caps or rate limits for normal use |
| 🎨 **Clean UI/UX** | Simple, modern, mobile-first responsive design |

---

## 📖 How to Use

Downloading a RedGifs video with SaveRedGifs takes only a few seconds:

1. **Copy the video URL** from RedGifs (from your browser address bar or share menu).
2. **Open** [https://saveredgifs.com](https://saveredgifs.com) in any browser.
3. **Paste the URL** into the input box on the homepage.
4. **Click the Download button** — our servers will fetch the highest-quality version available.
5. **Save the file** to your device. That's it!

> 💡 **Tip:** SaveRedGifs also works with mobile share sheets — just tap "Share → Copy link" on the RedGifs app and paste it into our site.

---

## 🛠️ Tech Stack

SaveRedGifs is built with modern, battle-tested web technologies for performance, scalability, and reliability.

### Backend
- **Node.js (v18+)** — JavaScript runtime powering the server
- **Express.js** — Minimal and flexible web framework for routing and middleware
- **Axios** — Promise-based HTTP client for fetching media metadata
- **Cheerio** — Server-side HTML parsing for extracting video sources
- **CORS** — Cross-origin resource sharing configuration
- **Helmet** — Security middleware for HTTP headers
- **Rate-Limiter-Flexible** — Abuse prevention and fair-use enforcement

### Frontend
- **HTML5 / CSS3** — Semantic markup and modern styling
- **Vanilla JavaScript (ES6+)** — Lightweight, no heavy framework overhead
- **Tailwind CSS** — Utility-first CSS for rapid, consistent UI development
- **Responsive Design** — Mobile-first layout that scales to all screens

### Infrastructure & Tooling
- **Nginx** — Reverse proxy and static asset serving
- **PM2** — Production process manager for Node.js
- **Cloudflare** — CDN, DDoS protection, and SSL
- **Git & GitHub** — Version control and CI/CD
- **ESLint + Prettier** — Code quality and consistent formatting
- **Jest** — Unit and integration testing

---

## 🚀 Getting Started (Local Development)

### Prerequisites
- Node.js **v18.0.0** or higher
- npm **v9+** or yarn
- Git

### Installation

```bash
# Clone the repository
git clone https://github.com/aayush988/saveredgifs-downloader.git

# Navigate into the project directory
cd saveredgifs-downloader

# Install dependencies
npm install

# Copy environment variables template
cp .env.example .env

# Start the development server
npm run dev
```

The app will be available at `http://localhost:3000`.

### Available Scripts

| Command | Description |
| :--- | :--- |
| `npm run dev` | Run development server with hot reload |
| `npm start` | Run production server |
| `npm test` | Run the test suite |
| `npm run lint` | Lint the codebase |
| `npm run build` | Build assets for production |

---

## 📁 Project Structure

```
saveredgifs-downloader/
├── src/
│   ├── controllers/      # Route handlers
│   ├── services/         # Business logic & RedGifs API integration
│   ├── middleware/       # Express middleware (auth, rate-limit, etc.)
│   ├── utils/            # Helper utilities
│   └── routes/           # API route definitions
├── public/               # Static assets (CSS, JS, images)
├── views/                # HTML templates
├── tests/                # Unit and integration tests
├── .env.example          # Example environment variables
├── package.json
└── README.md
```

---

## ❓ FAQ

**Q: Is SaveRedGifs really free?**  
A: Yes — 100% free with no hidden fees, premium tiers, or paywalls.

**Q: Do I need to install anything?**  
A: No. SaveRedGifs runs entirely in your browser. No apps, plugins, or extensions required.

**Q: Does SaveRedGifs work on mobile?**  
A: Absolutely. The site is fully responsive and works on iOS, Android, and tablets.

**Q: Are my downloads private?**  
A: Yes. We do not log or store the URLs you submit or the videos you download.

**Q: What video quality can I download?**  
A: We always fetch the highest quality available from the source — typically full HD.

**Q: Is there a download limit?**  
A: No daily caps for normal use. Automated abuse is rate-limited to ensure fair access.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/aayush988/saveredgifs-downloader/issues).

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

## 🌐 Links

- **Website:** [https://saveredgifs.com](https://saveredgifs.com)
- **Repository:** [github.com/aayush988/saveredgifs-downloader](https://github.com/aayush988/saveredgifs-downloader)
- **Issues:** [Report a bug or request a feature](https://github.com/aayush988/saveredgifs-downloader/issues)

---

<p align="center">
  Made with ❤️ by the SaveRedGifs team
  <br>
  <a href="https://saveredgifs.com"><b>👉 Visit saveredgifs.com</b></a>
</p>
