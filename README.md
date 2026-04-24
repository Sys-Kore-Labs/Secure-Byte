# Secure-Byte

# 🔐 SECUREBYTE

A small password / key generator I built using HTML, CSS and JavaScript.  
It generates random bytes and lets you view them as hex, spaced hex or base64.

I made this because I realized most of my passwords were weak or reused, and I wanted to understand how randomness actually works in a more “real” way. Also, I like anything related to hex and low-level stuff, so this felt like a good starting point.

---

## ✨ Features

- 🔢 Generate random bytes
- 🔡 Output in:
  - Hex
  - Spaced hex (`aa bb cc`)
  - Base64
- 📋 Copy to clipboard
- 💾 Export key as `.txt`
- 🔁 Auto-regenerate mode
- 📊 Simple entropy indicator
- 🧠 History of generated keys
- 🌑 Dark mode (grey man style)

---

## ⚙️ How it works

It uses the browser’s built-in `crypto.getRandomValues()` to generate secure random bytes.

Then:
- JavaScript converts those bytes into the selected format
- The entropy indicator gives a rough idea of how strong the output is (based on length)
- Extra features like history and auto-generate are handled with simple DOM updates

Nothing fancy, just trying to understand the basics properly.

---

## 🚀 How to run

Just open:
