# ⏳ Exam Countdown Component

This project contains a lightweight, embeddable countdown timer that visually displays the time remaining until a target date — perfect for exam portals, event pages, or landing sites where urgency matters.

---

## 🎯 Purpose

Designed for easy embedding in WordPress (or any HTML-based CMS), this countdown timer features:

- A retro-glitch aesthetic (CRT-style)
- Countdown down to years, days, hours, minutes, seconds, and milliseconds
- Customizable target date (hardcoded)
- A pale green tile design with adjustable opacity
- Fully self-contained (no dependencies or external JS frameworks)

---

## 🚀 How to Use

1. Copy the contents of the `countdown.html` file.
2. Paste it into a **Custom HTML block** in your WordPress page or post.
3. Optionally tweak:
   - The `targetISO` variable to set your target date.
   - The `--tile-opacity` CSS variable to adjust background transparency.

---

## 📦 File Structure

📁 countdown/
└── countdown.html  # Full HTML block ready to embed


---

## 🛠️ Customization

| Feature              | How to Change                                     |
|----------------------|---------------------------------------------------|
| Target Date          | Update `targetISO` in the `<script>` section     |
| Tile Background      | Modify `rgba(204, 255, 204, var(--tile-opacity))` |
| Font Styles          | Change the font families in inline `<style>`     |
| Colors               | Tweak border/text/shadow colors as needed        |

---

## 💡 Look for this bit in the code...

```js
const targetISO = '2025-12-31T23:59:59Z';


