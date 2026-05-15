# 🔵 gravity-balls

An interactive gravity simulation where 80 colorful balls cluster toward the center of the screen and scatter on hover & click — inspired by [Seeing Theory](https://seeing-theory.brown.edu/) by Brown University.

---

## ✨ Demo

> Open `index.html` in any browser — no install, no dependencies.

---

## 🎮 Interactions

| Action | Effect |
|--------|--------|
| **Hover** | Balls scatter away from your cursor |
| **Click** | Explosive burst — balls fly outward, then gravity pulls them back |
| **Hold click** | Stronger repulsion radius while held |
| **Touch** | Fully supported on mobile |

---

## ⚙️ How It Works

- **Central gravity** — every ball is continuously pulled toward the screen center, forming a tight organic cluster
- **Ball-ball collision** — physics-based position correction + velocity reflection prevents any overlap
- **Mouse repulsion** — cursor acts as a repulsion field; strength increases on click
- **Organic drift** — each ball has a unique slow drift angle so the cluster breathes naturally
- **Radial gradient rendering** — soft glow effect on each ball using Canvas 2D radial gradients
- **Dot grid background** — subtle grid for visual depth

---

## 🛠️ Built With

- Vanilla HTML, CSS, JavaScript
- Canvas 2D API
- Zero dependencies

---

## 📁 Structure

```
gravity-balls/
└── index.html   # everything in one file
└── README.md
```

---

## 🚀 Run Locally

```bash
git clone 
cd gravity-balls
open index.html
```

Or just drag `index.html` into your browser.

---

## 💡 Inspiration

Inspired by the beautiful ball animation on the [Seeing Theory](https://seeing-theory.brown.edu/) homepage — a visual introduction to probability and statistics by Daniel Kunin at Brown University.
