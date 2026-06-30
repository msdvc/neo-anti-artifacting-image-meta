

## ⚡ The Problem
Every time you upload a pristine JPG or PNG to Instagram or Facebook, their CDN servers put your file through a brutal, lossy compression meat grinder. The results?
* **Compression Artifacting:** Jagged edges around high-contrast areas and text.
* **Color Shifting & Desaturation:** Colors looking washed out or completely inaccurate due to ignored or converted ICC profiles (like AdobeRGB or CMYK).
* **Forced Conversion:** Massive PNG files converted into low-bitrate JPGs automatically.

---

## 🟢 The Solution: Total Control, Locally.
NEO scans your images **before** you upload them, acting as a diagnostic shield. It points out exactly what will trigger Meta's compression traps and provides a clear traffic-light verdict (**Green** / **Yellow** / **Red**).

### 🔒 Privacy-First Architecture (No Servers, No Leaks)
Unlike bloated online converters, NEO does not have a backend. It features **Zero persistent storage, zero cookies, and zero server uploads**. 
* Every single byte of your image is processed entirely inside your browser's local sandbox (via HTML5 File API and Canvas processing).
* Your client data remains yours. The code runs completely in your RAM. If you disconnect your internet, NEO still works.

---

## 🛠️ Tech Stack & Open-Source Code
NEO is built with minimalism, performance, and transparency in mind:
* **Vanilla JavaScript** (Zero heavy framework overhead, rendering directly via the client GPU/CPU).
* **Tailwind CSS** (For a sleek, responsive, Matrix-inspired brutalist UI).
* **HTML5 Canvas & FileReader API** (For instant, secure local file binary parsing).

### 🤝 Open Source & Contributions
This project is **100% open-source**. No tracking scripts, no ads, no paywalls. 

We believe that creators deserve to keep control over their digital art without sacrificing privacy. If you want to audit the code, add new social media preset boundaries (e.g., LinkedIn, Twitter/X compression rules), or improve the local profile ICC parser, feel free to fork the repo and submit a PR!
