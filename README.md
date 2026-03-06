# 🏦 Minimalist Bankist

A lightweight, front‑end banking demo.  
This simple app showcases UI updates, date/number formatting, and basic account operations using plain HTML, CSS and vanilla JavaScript.

---

## 🚀 Features

- ✅ **Login/Logout** with PIN authentication
- 🧾 Display account **balance**, **transactions (movements)** and **summary**
- 💸 **Transfers** to other users
- 💰 **Loan requests** (with simple approval logic)
- ❌ **Close account** functionality
- ⏱ **Auto-logout timer** for security
- 📅 Date and currency formatting via `Intl` APIs
- 🔀 Sort transactions ascending/descending
- No frameworks—just HTML/CSS/JS

---

## 📁 Project Structure

```
minimalistBankist/
├── index.html      ← Main markup & nav/forms
├── style.css       ← Basic styling (fonts, layout, colors)
└── script.js       ← All app logic and event handlers
```

---

## 🛠 Getting Started

1. **Clone or download** this repository.

2. Open `index.html` in your browser (double‑click or serve via a simple HTTP server):

   ```bash
   # from project root
   npx serve   # or: python3 -m http.server
   ```

3. Use one of the pre‑defined accounts to log in:

   | Username | PIN  |
   | -------- | ---- |
   | `js`     | 1111 |
   | `jd`     | 2222 |

4. Explore the UI: transfer money, request loans, sort movements, and close accounts.

---

## ✍️ Customization

- Edit `script.js` to add more accounts, tweak interest rates, or modify logic.
- Styles can be changed via `style.css` (uses Google Font _Poppins_).
- Replace placeholder assets (`logo.png`, `/icon.png`) with your own.

---

## 💡 Notes

- This is a **front‑end only demo**; data isn’t persisted.
- PIN fields on the login form are currently plain text for simplicity—switch to `type="password"` in production.
- Portions of the code (e.g. date creation) contain commented examples for learning purposes.

---

## 📚 Learning Resources

This repo is ideal for:

- Practicing DOM manipulation and event handling.
- Understanding `Intl.DateTimeFormat` and `Intl.NumberFormat`.
- Building small interactive prototypes without libraries.

---

Enjoy tinkering with your minimalist bank! 😊
