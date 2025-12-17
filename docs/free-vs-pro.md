# Free vs Pro Marketing Content Plan

## Strategy: "Freemium Confidence"
Lead with FREE value, make features the hero, treat Pro as a natural progression for power users.

**Primary goal:** Get downloads (main page sells the app)
**Secondary goal:** Make Pro info discoverable (separate page for details)

## Files to Create/Modify
- `index.html` - Minor additions
- `pricing.html` - NEW: Full comparison page
- `css/styles.css` - Add pricing styles

---

## Part 1: Main Page Changes (index.html)

### 1.1 Hero Section - Add "Start FREE" badge
- Small badge near download button: "Start FREE"
- Non-intrusive, builds confidence
- No limits mentioned in hero

### 1.2 New Pricing Section (after Benefits, before CTA)
**Headline:** "Start Free, Upgrade When Ready"

Two-column card layout:

**FREE Card:**
- 3 prospecting spots
- 20 samples
- 1 photo per sample
- GPS tracking & auto IDs
- Real-time value calculation
- Offline-first

**PRO Card ($9.99 one-time):**
- Unlimited spots & samples
- Unlimited photos
- Sample Locator with compass
- CSV & GPX export
- Custom lists
- Multi-currency
- "No subscriptions ever"

**CTAs:** "Download Free" (primary) | "See Full Comparison" (link to pricing.html)

### 1.3 Footer - Add pricing link
Add "Pricing" link to footer-links

---

## Part 2: New Pricing Page (pricing.html)

### 2.1 Page Structure
1. Hero: "Flexible Pricing for Every Prospector"
2. Quick comparison cards (same as main page)
3. Detailed feature tables
4. Pro Features Deep Dive (Sample Locator, Export, Custom Lists)
5. Use Cases (Who needs Free vs Pro)
6. FAQ section
7. CTA: Download button

### 2.2 Feature Tables
- Core Prospecting Features
- Sample Tracking
- Photos & Media
- Navigation & Locating
- Settings & Customization
- Data Management

### 2.3 FAQ (6 questions)
1. Can I try Pro features before buying?
2. What happens to my data if I don't upgrade?
3. Can I get a refund?
4. What if I buy a new phone?
5. Will Pro features change?
6. Can I upgrade later?

---

## Part 3: CSS Additions (styles.css)

### New Styles Needed
- `.free-badge` - Small badge for hero
- `.pricing-section` - Section background
- `.price-cards` - Two-column card container
- `.price-card` - Individual card styling
- `.price-card--free` - Subtle styling
- `.price-card--pro` - Gold accent, featured
- `.price-tag` - Price display ($9.99)
- `.comparison-table` - Feature table with checkmarks
- `.faq-section` - FAQ container
- `.faq-item` - CSS-only collapsible accordion
- `.use-case-card` - Use case cards

### Design Notes
- Match existing gold/brown theme
- Pro card gets gold border/accent
- Checkmarks in gold, X marks in muted gray
- Tables with subtle row striping
- Mobile: cards stack, tables scroll horizontally

---

## Implementation Order

1. Add CSS styles to styles.css
2. Update index.html:
   - Add free-badge to hero
   - Add pricing section
   - Add footer link
3. Create pricing.html with full content
4. Test responsive behavior
5. Commit changes

---

## Key Messaging Principles
- FREE is genuinely useful (not a trial)
- PRO is for power users (not required)
- One-time payment (trust builder)
- "Download now, decide later"
- Never mention limits in feature descriptions
