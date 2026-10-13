# Malabar
A modern, premium furniture website featuring an elegant green-inspired design, interactive product collections, custom furniture solutions, showroom locations, project galleries, and responsive layouts with smooth animations.

---

# Grand Malabar Furniture
Static site (no build step). Works on GitHub Pages: Settings → Pages → Deploy from branch → main / root.

## Add your content
- `products.js` – add real products (name, category, image, description, optional price).
- `assets/` – drop in photos using these exact names:
  hero.jpg, cat-sofas.jpg, cat-beds.jpg, cat-dining.jpg, cat-wardrobes.jpg, cat-office.jpg, about.jpg, gallery-1..4.jpg
  Missing images are hidden gracefully; the hero falls back to a walnut/forest gradient.
- Product images: `assets/products/…` and reference them in products.js.
