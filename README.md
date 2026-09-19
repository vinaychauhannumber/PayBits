# PayBits ⚡ Smart UPI Payment Splitter

<p align="center">
  <img src="logo.png" width="120" height="120" alt="PayBits Logo" style="border-radius: 28px; box-shadow: 0 8px 24px rgba(208, 135, 46, 0.35);" />
</p>

<p align="center">
  <b>Split large UPI payments into smart, manageable sub-₹2,000 PayBits.</b><br/>
  Each chunk gets an instant UPI QR code, 1-tap mobile app deep links, and live payment status tracking.
</p>

---

## ✨ Key Features

- **⚡ Sub-₹2,000 PayBits Engine**: Automatically chunks transactions into balanced amounts under ₹2,000 (default ₹1,999 max). Paise are precisely allocated to the final chunk so not a single paisa is lost to rounding.
- **📱 1-Tap UPI App Launchers**:
  - **Universal UPI**: Direct system intent (`upi://pay`) to launch any installed UPI application on mobile.
  - **Google Pay (GPay)** shortcut
  - **PhonePe** shortcut
  - **Paytm** shortcut
- **💬 WhatsApp Sharing**: Instantly generate and share a clean receipt breakdown with individual payment links directly on WhatsApp.
- **📊 Live Payment Progress Tracker**: Track completed payments in real-time with an interactive progress bar, "Mark Paid" status toggles, and celebratory confetti upon full settlement.
- **🌓 Dark & Light Mode**: Clean, glassmorphic UI matching PayBits' signature golden amber and obsidian black palette with persistent theme storage.
- **🚀 1-Click Preset Chips**: Rapidly populate common bill amounts (₹2,500, ₹3,500, ₹5,000, ₹7,500, ₹10,000).
- **🔒 100% Client-Side Privacy**: Zero servers, zero trackers, zero databases. No financial data or UPI IDs ever leave your browser.
- **🔗 Shareable Links**: Deep-link support via URL query parameters (e.g. `?amount=5000&vpa=merchant@upi&name=Store`).
- **🤖 AEO & GEO Optimized**: Schema.org `FAQPage` and `HowTo` graphs, native `llms.txt` and `llms-full.txt` context files, and India geotargeting for AI answer engines (Perplexity, ChatGPT, Google AI Overviews).

## ⚡ Deploy to Vercel

Deploy your own instance of PayBits in one click:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/vinaychauhannumber/PayBits)

## 🚀 Running Locally

Static single-page application. Open `index.html` directly in any web browser, or serve it locally:

```bash
# Using npx serve
npx serve .

# Or using Python 3
python3 -m http.server 4321
```

## ⚖️ Disclaimer
 
PayBits is an independent utility. No payments are processed through this website, and no financial data or credentials leave your browser. Always verify the payee UPI ID and amount in your UPI application before authorizing with your UPI PIN. Provided as-is.
