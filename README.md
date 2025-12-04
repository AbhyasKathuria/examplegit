# examplegit
# 🎄 Christmas Pick-a-Gift Game 🎁

A fun, festive, single-page Christmas web game where players click on gift boxes to find the hidden surprise! Only **one box** contains the real gift — the rest are empty (or naughty coal 😈).

Perfect for Christmas websites, holiday greetings, or just spreading some interactive joy!

![Game Preview](preview.jpg)
*(Screenshot coming soon — or just open index.html!)*

## ✨ Features

- Full-screen Christmas video background (cozy fireplace vibe)  
 9 beautifully animated gift boxes in a 3×3 grid  
 One random winning box with a special gift inside  
 Glowing title & bouncing win message  
 Hover effects and smooth animations  
 Mobile-friendly & lightweight  

## 🚀 Live Demo

Play it now: [https://yourusername.github.io/your-repo-name](https://yourusername.github.io/your-repo-name)  
(Replace with your actual GitHub Pages link after deploying)

## 📂 Files in this Repository
├── index.html          # Main game (the file you just saw)
├── xmax.mp4            # Christmas fireplace background video
├── box.png             # Closed gift box image
├── yes.jpg             # The winning gift image (you can change this!)
├── empty.png           # (Optional) Image shown when wrong box is picked
└── README.md           # This file


> Note: Currently, wrong boxes turn into a placeholder online image. Replace the URL in the script with your own `empty.png` (like coal or "try again") for full offline use!

## 🛠️ How to Customize

1. **Change the prize** → Replace `yes.jpg` with your own image (e.g. g. a personal photo, coupon, love note, etc.)
2. **Change empty result** → Upload your own `empty.png` and update this line in the script:
   ```js
   this.style.background = "url('empty.png') no-repeat center center";
