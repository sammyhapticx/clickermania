# Button Clicker 🎮

A full-featured **idle clicker game** inspired by Opera GX's Spacebar Clicker, built with HTML, CSS, and JavaScript. [web:9][web:14]

Click the button to earn points, buy upgrades, unlock auto‑income, and **prestige** for permanent multipliers. Auto‑saves progress to localStorage.

## ✨ Demo

**[Play live on GitHub Pages](https://sammyhapticx.github.io/clickermania)**  


## 🎮 How to Play

1. **Click** the big green button (or press **Space/Enter**) to earn points.
2. Spend points on **upgrades** in the right panel:
   - **Click upgrades** → Bigger clicks
   - **Auto upgrades** → Passive income
3. **Prestige** when you have enough total points (bottom‑right):
   - Resets your run but gives permanent **+10% multiplier per prestige point**
4. Watch your empire grow exponentially!

**Pro tip**: Prestige around 10K+ total points for good gains.

## 🎨 Features

- ✅ **Responsive** (desktop + mobile)
- ✅ **Auto‑saving** (localStorage)
- ✅ **Prestige system** (permanent boosts)
- ✅ **Pixel art icons** (CC0 from [pixelart-icons](https://github.com/CornetPanique86/pixelart-icons)) [web:57]
- ✅ **Smooth animations** + particle effects
- ✅ **Keyboard controls** (Space/Enter to click)
- ✅ **Tabs** for Click vs Auto upgrades
- ✅ **Exportable** (single `index.html`)

## 🚀 Deploy on GitHub Pages

1. Fork this repo or create your own
2. Upload `index.html` to the root
3. Go to **Settings** → **Pages**
4. Source: `Deploy from branch` → `main` + `/ (root)`
5. Your game will be live at:  
   `https://yourusername.github.io/button-clicker`

Works great on Android with hotspot!

## 📱 Mobile‑Friendly

- Touch‑to‑click
- Full‑screen responsive
- Optimized for phones

## 🔧 Customization

Edit `index.html`:

- **Icons**: Swap URLs in `.pixel-icon-*` CSS classes
- **Prestige**: Change `1 + state.prestigePoints * 0.1` formula
- **Upgrades**: Add to `upgradeDefs` array
- **Theme**: Tweak colors in `<style>`

## 📊 Prestige Math
