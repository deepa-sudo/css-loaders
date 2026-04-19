# CSS Loaders 🌀
 
A collection of **12 pure CSS loading animations** — no JavaScript, no dependencies, no build step. Just copy a single file and drop it in.

### Open the showcase
 
Open `index.html` in your browser to see all 12 loaders live, browse by category, and copy the CSS + HTML for any loader with one click.

## 🎨 Customization
 
Every loader uses plain CSS custom properties or simple color values — easy to retheme:
 
```css
/* change the spin-ring color */
.spin-ring {
  border-color: rgba(255, 100, 100, 0.15);
  border-top-color: #ff6464;
}
 
/* change the speed */
.spin-ring {
  animation-duration: 0.5s; /* faster */
}
 
/* change the size */
.spin-ring {
  width: 64px;
  height: 64px;
  border-width: 5px;
}
```
---
 
## 🌙 Dark mode
 
Most loaders use color values that work on both light and dark backgrounds. For the skeleton shimmer, swap the gradient stops to suit your background:
 
```css
/* dark mode skeleton */
.sk-line {
  background: linear-gradient(
    90deg,
    #222 25%,
    #2e2e2e 50%,
    #222 75%
  );
}
```
 
---