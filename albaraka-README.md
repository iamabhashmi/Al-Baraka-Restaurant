# 🍛 Al-Baraka Restaurant

A rich, dark-themed restaurant website built with pure HTML, CSS, and JavaScript — featuring an interactive tabbed menu, photo gallery, Firebase-powered online order form, and WhatsApp ordering integration.

![Status](https://img.shields.io/badge/Status-Live-brightgreen) ![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)

---

## 🌐 Live Demo

👉 [View Live Site](https://iamabhashmi.github.io/albaraka-restaurant/)

---

## 📸 Preview

| Section | Description |
|---|---|
| Hero | Full-screen with restaurant stats |
| Menu | Tabbed menu — Desi, BBQ, Rice, Fast Food, Drinks |
| About | Restaurant story with 30-year history card |
| Gallery | 6-item visual food gallery |
| Order | Firebase order form + WhatsApp ordering |
| Contact | Location, hours, phone |

---

## ✨ Features

- ✅ Interactive tabbed menu (5 categories, 25+ items)
- ✅ Firebase Firestore order management
- ✅ WhatsApp direct ordering button with pre-filled message
- ✅ Dark rich theme — completely different from other portfolio sites
- ✅ Food gallery with hover overlays
- ✅ Mobile responsive
- ✅ No frameworks — pure HTML/CSS/JS
- ✅ GitHub Pages ready

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling, grid layout, animations |
| JavaScript (ES6) | Tab switching, form handling |
| Firebase Firestore | Order data storage |
| Google Fonts | Cormorant Garamond + Inter |
| GitHub Pages | Free hosting |

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/iamabhashmi/albaraka-restaurant.git
cd albaraka-restaurant
```

### 2. Set up Firebase

1. Go to [console.firebase.google.com](https://console.firebase.google.com)
2. Create a new project → Enable Firestore Database
3. Add a web app → copy config

### 3. Add Firebase config

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

### 4. Deploy to GitHub Pages

1. Push to GitHub
2. Settings → Pages → main branch
3. Live at: `yourusername.github.io/albaraka-restaurant`

---

## 📁 Project Structure

```
albaraka-restaurant/
│
├── index.html      # Complete website
└── README.md       # Documentation
```

---

## 🎨 Color Palette

| Color | Hex | Usage |
|---|---|---|
| Dark Background | `#0C0A08` | Main background |
| Surface | `#161310` | Cards, sections |
| Deep Red | `#C0392B` | Accents, buttons |
| Gold | `#D4A843` | Highlights, headings |
| Cream | `#F5EDD8` | Light text |

---

## 📋 Order Data (Firestore)

```json
{
  "name": "Muhammad Ali",
  "phone": "+92 309 6455356",
  "orderType": "Home Delivery",
  "address": "Main Road, Lahore",
  "items": "1x Chicken Karahi, 2x Seekh Kebab",
  "notes": "Extra spicy please",
  "status": "new",
  "createdAt": "Firestore Timestamp"
}
```

---

## 🔧 Customization

| What to change | Where |
|---|---|
| Restaurant name | Search `Al-Baraka` → replace |
| Phone number | Search `+92 309 6455356` → replace |
| Menu items & prices | Find `menu-panel` sections |
| Opening hours | Find `#contact` section |
| WhatsApp link | Find `wa.me/923096455356` → replace |
| Colors | Edit `:root` CSS variables |

---

## 👨‍💻 Built by Qubit Agency

- 📞 WhatsApp: +92 309 6455356
- 📧 Email: iamabhashmi@gmail.com

---

⭐ Star this repo if you found it useful!
