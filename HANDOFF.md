# HANDOFF: WICKED Candle Shop
Student: Shayne Erin M. Bandong
**Activity: Week 1 
Stage: Week 1 checkpoint (repository, design tokens, UX proposal)

---

UX Project Proposal

The user problem
Buying candles online is hard to do well. Product pages are often cluttered, the photos are small, and it is difficult to tell scents, shapes and wax melts apart or to compare them quickly. Gift buyers in particular want something small and pretty but don't know where to start, and many shops make adding an item to the cart take too many steps.

Target audience
- Primary: students and young adults (about 18 to 30) who buy candles for their room or study space.
- Secondary: gift buyers looking for small, pretty items (wax melts are made for this).
- Context of use:** mostly a laptop or desktop browser, with a stacked layout for smaller screens.

Chosen aesthetic theme (locked, no switching)
WICKED: a warm "evening glow" candle shop.** Dark plum backgrounds, soft cream text and a candle-flame amber accent. Large product photos fill the screen so the products carry the design.

Interface goals
1. Find products fast: four clear categories and always-visible next products.
2. One clear action:a single "Add to cart" button per product.
3. Give feedback: a short message and a cart count after every add.
4. Keep it calm: the Home page stays simple; products appear under Products.
5. Be accessible: real buttons and links, visible keyboard focus, readable contrast, labelled search.

Pages
Home · Products · Cart · Contact · Help

---

Design tokens
All tokens are declared in the `:root` block of `css/style.css`:
- Color scheme: `--color-bg-1/2/3`, `--color-text`, `--color-muted`, `--color-accent`, `--color-ink`
- Typography:`--font-body`, `--fw-*`, `--fs-*`, `--lh-body`
- Layout system:`--space-*`, `--space-page`, `--header-h`, `--radius-*`, `--max-width`

older structure
```
Week1_Bandong/
├── index.html
├── HANDOFF.md
├── css/
│   └── style.css
    └── images/
```

Next steps
- Week 2: multi-column sections and the Products layout.
- Week 3: Cart, Contact and Help pages, responsive testing, final cleanup.