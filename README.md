# 🪙 Crypto Logo CDN

This repository provides a **collection of cryptocurrency logos** in **SVG format**, hosted publicly on GitHub and served globally via **jsDelivr CDN**. 🚀  
It’s perfect for web developers who want to easily embed crypto logos without hosting them manually.

---

## 📦 How to Use

Access any logo directly from jsDelivr CDN using this URL format:

```
https://cdn.jsdelivr.net/gh/madenix/Crypto-logo-cdn@main/Logos/<FileName>.svg
```

Example:

```html
<img src="https://cdn.jsdelivr.net/gh/madenix/Crypto-logo-cdn@main/Logos/BTC.svg" alt="Bitcoin Logo" width="64" />
```

or in CSS:

```css
background: url("https://cdn.jsdelivr.net/gh/madenix/Crypto-logo-cdn@main/Logos/ETH.svg") no-repeat center / contain;
```

---

## 💎 Available Logos

| Coin | Preview | CDN Link |
|------|----------|----------|
| **ADA** | <img src="https://cdn.jsdelivr.net/gh/madenix/Crypto-logo-cdn@main/Logos/ADA.svg" width="40"/> | [ADA.svg](https://cdn.jsdelivr.net/gh/madenix/Crypto-logo-cdn@main/Logos/ADA.svg) |
| **AVALANCHE (AVAX)** | <img src="https://cdn.jsdelivr.net/gh/madenix/Crypto-logo-cdn@main/Logos/AVAX.svg" width="40"/> | [AVAX.svg](https://cdn.jsdelivr.net/gh/madenix/Crypto-logo-cdn@main/Logos/AVAX.svg) |
| **Bitcoin (BTC)** | <img src="https://cdn.jsdelivr.net/gh/madenix/Crypto-logo-cdn@main/Logos/BTC.svg" width="40"/> | [BTC.svg](https://cdn.jsdelivr.net/gh/madenix/Crypto-logo-cdn@main/Logos/BTC.svg) |
| **Ethereum (ETH)** | <img src="https://cdn.jsdelivr.net/gh/madenix/Crypto-logo-cdn@main/Logos/ETH.svg" width="40"/> | [ETH.svg](https://cdn.jsdelivr.net/gh/madenix/Crypto-logo-cdn@main/Logos/ETH.svg) |
| **HYPE** | <img src="https://cdn.jsdelivr.net/gh/madenix/Crypto-logo-cdn@main/Logos/HYPE.svg" width="40"/> | [HYPE.svg](https://cdn.jsdelivr.net/gh/madenix/Crypto-logo-cdn@main/Logos/HYPE.svg) |
| **Ripple (XRP)** | <img src="https://cdn.jsdelivr.net/gh/madenix/Crypto-logo-cdn@main/Logos/XRP.svg" width="40"/> | [XRP.svg](https://cdn.jsdelivr.net/gh/madenix/Crypto-logo-cdn@main/Logos/XRP.svg) |
| **BNB** | <img src="https://cdn.jsdelivr.net/gh/madenix/Crypto-logo-cdn@main/Logos/BNB.svg" width="40"/> | [BNB.svg](https://cdn.jsdelivr.net/gh/madenix/Crypto-logo-cdn@main/Logos/BNB.svg) |

> 🧩 Add more logos in the same format under the `/Logos` directory and update this table.

---

## ⚙️ How to Add New Logos

1. **Fork or clone** the repository:
   ```bash
   git clone https://github.com/madenix/Crypto-logo-cdn.git
   ```
2. Add your new SVG logo inside the `Logos/` folder.
3. Commit and push changes:
   ```bash
   git add .
   git commit -m "Added new logo"
   git push
   ```
4. (Optional) Create a tag version:
   ```bash
   git tag v1.0.1
   git push origin v1.0.1
   ```

---

## ⚡ Alternative CDN Options

If jsDelivr is temporarily unavailable, you can use one of these backup links:

- **Statically CDN**
  ```
  https://cdn.statically.io/gh/madenix/Crypto-logo-cdn/main/Logos/BTC.svg
  ```
- **Raw GitHub (slower, but works)**
  ```
  https://raw.githubusercontent.com/madenix/Crypto-logo-cdn/main/Logos/BTC.svg
  ```

---

## 🧠 Notes

- All logos are **vector-based SVGs** for infinite scalability.
- Each SVG is optimized and stripped of unnecessary metadata.
- Logos include proper `viewBox` attributes for responsive rendering.
- Optimize your own SVGs easily using [SVGOMG](https://jakearchibald.github.io/svgomg/).

---

## 🧑‍💻 Contributing

Contributions are welcome!  
You can add new cryptocurrency logos, improve existing ones, or submit optimizations.  
Simply open a **pull request**, and your contribution will be credited here. 🙌

---

## 📄 License

This project is released under the **MIT License**.  
You are free to use, modify, and distribute these assets for personal or commercial use.

---

**Maintainer:** [@madenix](https://github.com/madenix)  
🌐 _“Fast, simple, open-source crypto asset CDN.”_
