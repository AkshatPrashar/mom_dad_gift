# 💝 Interactive Anniversary Surprise

A single-page, interactive website designed as a digital anniversary gift. This project features a "gamified" love counter that triggers visual and audio changes, culminating in a beautiful letter reveal set against a scenic background.

## ✨ Features

- **Interactive Love Meter:** Tapping the heart button increases the "Love %" from 0 to 100.
- **The "Pinkening" Effect:** The background color dynamically transitions from neutral to deep pink based on the current percentage.
- **Antigravity Memory Lane:** On every click, Polaroid-style photos spawn and float upwards (defying gravity), rotating and scaling randomly for a natural feel.
- **Dynamic Audio:** Background music volume increases linearly with the love percentage (starts quiet, ends at full volume).
- **Heartbeat Animation:** The central heart beats faster as the user gets closer to 100%.
- **Grand Reveal:** At 100%, a glassmorphism-styled letter overlay slides down over a beautiful scenery background.

## 🛠️ Tech Stack

- **HTML5** (Structure)
- **CSS3** (Animations, Glassmorphism, Transitions)
- **Vanilla JavaScript** (Logic, DOM Manipulation, Audio Control)
- **Zero Dependencies** (No frameworks required)

## 🚀 How to Run

1. Clone or download this repository.
2. Simply open `index.html` in any modern web browser (Chrome, Safari, Firefox).
3. **Note:** Due to browser autoplay policies, the music will only start after the user interacts with the page (first click).

## ⚙️ How to Customize

If you are using this template for your own gift, here is how to personalize it:

### 1. Change the Floating Photos (Antigravity)
Open `index.html` and look for the JavaScript section. Find the `memoryImages` array:
```javascript
const memoryImages = [
    '[https://link-to-photo-1.jpg](https://link-to-photo-1.jpg)',
    '[https://link-to-photo-2.jpg](https://link-to-photo-2.jpg)',
    // Add your own image URLs here
];
