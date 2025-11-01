# 🚀 Futuristic Countdown Timer 🚀

A **sleek, animated “Coming Soon” page** featuring a **dynamic, generative particle background** and a **futuristic, sci-fi design**.  
Built entirely with **vanilla HTML, CSS, and JavaScript**, this lightweight project is perfect for **product launches, event announcements, or personal portfolios**.

---

## 🌟 Core Features

- **⏳ Dynamic JS Countdown:** Automatically counts down from a target date (default: 10 days from page load).  
- **✨ Animated Particle Background:** Custom HTML5 Canvas animation for a lively, generative effect.  
- **👾 Futuristic UI:**  
  - Glowing text effects using `text-shadow`.  
  - Glassmorphism design with `backdrop-filter`.  
  - Smooth entrance and pulse animations with CSS3.  
- **🧠 Sci-Fi Font:** Uses Google’s [Orbitron](https://fonts.google.com/specimen/Orbitron) for a techy aesthetic.  
- **📱 Fully Responsive:** Canvas and layout automatically adapt to all screen sizes.  
- **🚀 Completion State:** Displays **“Mission Launched!”** automatically when the countdown reaches zero.  

---

## 💻 Technologies Used

- **HTML5** — Page structure & `<canvas>` for the particle system  
- **CSS3** — Styling, animations, glassmorphism, and responsive layout  
- **JavaScript (ES6+)** — Countdown timer and particle generation logic  

---

## 📁 File Structure

```

/countdown-project
│
├── 📄 index.html       # Main HTML file
├── 🎨 style.css        # Styling & animations
├── ⚙️ script.js        # Countdown & particle logic
└── 📖 README.md        # Project documentation

````

---

## 🛠️ How to Use

No dependencies. No build steps. Just run it.

1. **Clone or download** this repository.  
2. **Open** `index.html` in your browser.  
3. **Enjoy** the futuristic countdown experience!  

---

## 🔧 Customization

### 🎯 1. Change the Countdown Target

In `script.js`, find this line:

```javascript
// Set the date we're counting down to: 10 days from now
const countdownDate = new Date().getTime() + (10 * 24 * 60 * 60 * 1000);
````

To set a **specific target date**, replace it with:

```javascript
// Example: Set to midnight, January 1, 2027
const countdownDate = new Date("Jan 1, 2027 00:00:00").getTime();
```

---

### 🎨 2. Change the Theme & Colors

Open `style.css` and edit the `:root` section to easily adjust theme colors:

```css
:root {
    --primary-color: #00ffff; /* Cyan glow */
    --background-start: #0a0a1a;
    --background-end: #1a1a3a;
    --text-color: #f0f0f0;
    --card-background: rgba(26, 26, 58, 0.6);
}
```

Tweak these variables to match your brand or style.
## 🧩 Future Improvements

* [ ] Add sound effects for countdown completion
* [ ] Add an optional logo or brand name animation
* [ ] Include a form for email notifications or subscriptions

---
