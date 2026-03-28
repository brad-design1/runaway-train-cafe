# Runaway Train Café — Website Redesign Brief

**Client:** Kim B. (owner)  
**Location:** 3600 Stephen F. Austin Dr, Brownwood, TX 76801  
**Phone:** (325) 646-3333  
**Current Site:** http://www.runawaytraincafe.com (Weebly, dated)

---

## The Story

Brad worked here in college. Loves the place, loves the owner. This is a personal project — make it awesome.

## What They Are

- **Unique concept:** Authentic 1940s dining train car converted into a café
- **Vibe:** Nostalgic, family-friendly, small-town Texas charm
- **Food:** Half-pound fresh burgers, sandwiches, homemade soup, Blue Bell ice cream
- **Famous items:** Bacon cheeseburger w/ jalapeño bacon, mushroom Swiss burger, soup + half sandwich combo
- **Reviews:** 181 reviews on Yelp, 114 photos — clearly beloved local spot

## Hours

- Tue–Thu: 11am–3pm
- Fri–Sat: 11am–8pm
- Sun–Mon: Closed

## Current Site Issues

1. **Weebly-based** — outdated tech, slow, not mobile-optimized
2. **Dark theme** — hard to read, doesn't match the warm diner vibe
3. **Menu is a PDF or image** — not accessible, not SEO-friendly
4. **No online ordering** — missing revenue opportunity
5. **No Google Business integration** — reviews not leveraged
6. **Too many nav items** — Yelp, TripAdvisor, FourSquare all in main nav (clutter)
7. **No call-to-action** — no "Order Now" or "Call Us" button
8. **Images not optimized** — slow load, not responsive

## Brand Assets Available

- Hamburger hero image: `/uploads/5/7/7/9/5779136/hamburger_orig.jpg`
- Logo/wordmark: `/uploads/5/7/7/9/5779136/8215572.png`
- Header background: `/uploads/5/7/7/9/5779136/header_images/1383277711.jpg`
- 114+ photos on Yelp (gold mine for content)

## Design Direction

**Warm, nostalgic, train-themed:**
- Cream/warm white backgrounds (not dark)
- Deep red accents (#8D2424 from current site — keep it)
- Vintage train typography (but readable)
- Full-bleed food photography
- Mobile-first responsive design

**Emotional tone:** "Step back in time. The best burger in Brownwood."

---

## Recommended Stack

**Option A: Astro + Tailwind (Brad's current stack)**
- Same as IBC Academy site
- Fast static site, Vercel deploy
- Fully custom, no platform lock-in
- Good for SEO

**Option B: Square Online (if owner wants to self-manage)**
- Built-in POS integration for orders
- Easy menu management
- Monthly fee but low maintenance

**Recommendation:** Astro + Tailwind (Brad builds it, gift to Kim)

---

## Page Structure

1. **Home** — Hero image, tagline, hours, location, CTA buttons
2. **Menu** — Searchable/filterable, with prices and photos
3. **Our Story** — The train car history, photos of interior
4. **Gallery** — Food + atmosphere photos (pull from Yelp/Facebook)
5. **Contact** — Address, phone, embedded Google Map, hours
6. **Order Online** (future) — If she wants it

## Quick Wins

- [ ] Mobile-responsive design
- [ ] Google Business schema markup (rich snippets)
- [ ] Optimized images (WebP, lazy loading)
- [ ] Clear CTA: "Call Now" / "Get Directions"
- [ ] Menu as HTML (not PDF) — SEO + accessibility
- [ ] Social proof section (Yelp rating badge, recent reviews)

---

## Timeline

This is a gift, so scope is flexible. Estimate:
- Design mockup: 1–2 hours (Saoirse could help)
- Build: 4–6 hours
- Content migration: 1–2 hours
- Total: Weekend project

## Next Steps

1. Brad confirms he wants to do this (yes, confirmed)
2. Get high-res images from Kim or scrape from Yelp/FB
3. Get current menu (prices, items)
4. Design homepage mockup
5. Build in Astro
6. Deploy to Vercel, point domain

---

## Build Status: ✅ COMPLETE (First Draft)

**Dev server:** http://localhost:4324/

**Pages built:**
- `/` — Homepage with hero, featured burger, train car story, food sections, Yelp reviews
- `/menu` — Full menu (burgers, sandwiches, soups, sides, ice cream, drinks)
- `/about` — Our Story with images and train car history
- `/gallery` — Photo gallery with lightbox-ready images
- `/contact` — Contact info, hours, embedded Google Map

**Assets downloaded from current site:**
- hamburger_orig.jpg (hero burger)
- 8215572.png (logo)
- 1383277711.jpg (header/hero background)
- 7 gallery images

**Design features:**
- Warm cream background (#FDF8F3)
- Deep red accents (#8D2424) 
- Brown text (#3D2314)
- Gold highlights (#C9A227)
- Mobile-first responsive
- Sticky header with CTA
- Schema.org restaurant markup
- Open Graph tags

**Next steps:**
1. Brad reviews first draft
2. Loop in Saoirse for visual polish (hero image, typography refinement)
3. Get actual menu with prices from Kim
4. Test on mobile
5. Set up Vercel deploy
6. Point domain when ready

---

*Created: March 28, 2026*
*For: Brad Raschke / Kim B.*
