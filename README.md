# 🌶️ Swaadica Spices - Digital Storefront

A premium, highly responsive, and modular single-page e-commerce catalog developed for **Swaadica**. This storefront showcases premium organic spices crafted in India and provides a seamless, friction-free ordering process directly integrated with WhatsApp.

---

## ✨ Features

* **Premium Glassmorphism Navigation:** A modern transparent navbar that seamlessly floats over the hero section and smoothly morphs into a solid blurred panel upon scrolling to maximize readability.
* **Dual-Image Interactive Catalog:** Product cards built with a custom CSS hover-flip mechanism, displaying both the front and back of the spice packaging to establish immediate ingredient and brand trust.
* **Dynamic Multi-Weight Pricing:** An interactive dropdown weight-selector (50g to 1kg) built dynamically via JavaScript that instantly updates product pricing on the frontend without reloading.
* **Automated WhatsApp Order Generation:** The "Buy Now" button utilizes the WhatsApp API to pre-fill an exact order slip (including item name, specific weight, and calculated price) directly into the chat.
* **Integrated Premium Brand Sections:** Includes an elegant, dark glassmorphism "Connect With Us" location & contact module, an "Our Story" section, and a custom gradient Instagram link button.
* **Fully Mobile-Optimized:** Designed with a mobile-first philosophy using flexible CSS layouts to guarantee an application-like feel on all screen dimensions.

---

## 📂 Project Structure

```text
Swaadica-Website/
├── index.html       # Main HTML entry point (Structure & Sections)
├── css/
│   └── style.css    # Premium Glassmorphism styling & animations
├── js/
│   └── script.js    # Modular product data, dynamic template rendering, & scroll logic
└── img/             # Local optimized directory for high-resolution brand assets
    ├── swaadica-logo-transparent.png
    ├── chilli-front img.jpg
    ├── chilli-back img.jpg
    ├── coriander-front img.jpg
    ├── ... (Remaining product images)
