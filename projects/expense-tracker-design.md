# Expense Tracker Design — "Cashflow"

**Status:** Design Complete ✅  
**Created:** Feb 15, 2026  
**Design Tool:** HTML/CSS/JS (Production-ready)

## Design Philosophy

**Name:** Cashflow  
**Tagline:** "Track every rupee. Control your spending."

**Aesthetic:** Modern, purposeful, premium feel without being ostentatious
- **Tone:** Clean minimalism with intentional depth
- **Color Palette:** Dark theme with emerald accent (trust, growth) + warm orange (warnings)
- **Typography:** Syne (bold headlines), Inter (body text) — distinctive but readable
- **Motion:** Subtle hover effects, staggered animations, satisfying interactions

## Key Design Elements

### 1. **Dashboard Stats** (3-column cards)
- **Balance:** ₹45,230 (primary metric)
- **Spent This Month:** ₹12,840 (with trend indicator)
- **Budget Left:** ₹7,160 (remaining runway)
- Cards have animated top border on hover for visual feedback

### 2. **Weekly Spending Chart**
- 7-day bar visualization showing daily spending
- Color-coded: Green (income), Orange (large expenses), Purple (other)
- Interactive bars with hover scale effect
- Shows spending pattern at a glance

### 3. **Top Categories**
- Food & Dining (₹3,240)
- Travel (₹2,180)
- Entertainment (₹1,890)
- Icons + transaction count for quick context
- Hover effect highlights category

### 4. **Recent Transactions**
- Latest 5 transactions with emoji icons
- Shows: Name, category, location, amount, timestamp
- Green for income, orange for expenses
- Smooth hover state with slight translate and background change
- Mobile-responsive transaction layout

### 5. **Add Button (FAB)**
- Fixed-position floating action button
- Rotates on hover (delightful micro-interaction)
- Links to "Add expense" modal

## Color System

```css
--primary: #1a472a (Deep teal — trust, stability)
--accent: #00d084 (Emerald — growth, income)
--accent-warm: #ff6b4a (Coral — caution, expenses)
--bg-dark: #0f1419 (Near-black background)
--bg-card: #1a1f26 (Card layer)
--text-primary: #f5f5f5 (Primary text)
--text-secondary: #a0aec0 (Secondary text)
```

## Responsive Design

✅ Desktop (1400px+)  
✅ Tablet (1024px)  
✅ Mobile (768px)  
✅ Small Mobile (480px)

Grid adjusts from 12-column to stacked layout on mobile.

## Implementation Status

- [x] Design mockup created (HTML/CSS/JS)
- [x] All components functional
- [x] Animations implemented
- [x] Dark theme optimized
- [x] Responsive layout tested
- [ ] Backend integration (Next.js API)
- [ ] Database schema (PostgreSQL)
- [ ] Authentication (JWT)
- [ ] Real data integration

## Next Steps

1. **Create Figma design file** (export this HTML as design reference)
2. **Setup backend API** (Node.js/Express or Next.js)
3. **Build database schema** (expenses, categories, users)
4. **Implement authentication** (Google OAuth or email)
5. **Connect frontend to API**
6. **Add data export features** (CSV, PDF)

## File Location

- **Design HTML:** `/data/.openclaw/workspace/expense-tracker-design.html`
- **Live preview:** Open in browser
- **Figma export:** Can be recreated from HTML using design system

---

*This design is production-grade and can serve as both a design reference and functional prototype. Build the backend and connect it for a fully working expense tracker.*
