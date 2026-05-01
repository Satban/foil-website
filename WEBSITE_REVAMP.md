# Foil Website Revamp Plan

## Brand Tagline Options

### Primary Candidates
- **Use** what's fresh.
- **Use** what's ripe.
- **Use** what you buy.
- **Use** at its peak.
- **Use** it all.

### Secondary / Contextual
- **Use** what's ready.
- **Use** first.
- **Use** well.
- **Use** everything.
- Every **use**, on time.
- Made to be **used**.
- Nothing un**used**.
- Buy it. **Use** it.

### Recommended Primary
> **Use** what's fresh.

---

## Design Inspirations

| Brand | What We're Extracting |
|-------|----------------------|
| **Superhuman** | Cinematic motion on app screens, dark/light elegance, obsessive whitespace |
| **Whispr Flow** | Subtle microanimations that feel alive — UI that breathes |
| **Whoop** | Data as narrative, lifestyle integration |
| **Kinfolk** | Warm editorial photography — hands, light, texture, lived-in kitchens |
| **Oatly** | Copy that talks *with* you, not *at* you — self-aware, witty, never patronizing |

---

## Core Principles

### Voice
- Empowering, never guilt-inducing
- Conspiratorial, not condescending — "we're in this together"
- Confident, not preachy
- Playful about the *product*, never about user habits

### Motion
- Scroll-linked opacity: elements fade in, never pop
- Stagger delays: lists animate item-by-item (50ms between each)
- Custom easing: `cubic-bezier(0.16, 1, 0.3, 1)` — fast in, slow out
- Subtle parallax: 10-20% speed differential
- Hover states: buttons lift with soft shadow, cards tilt toward cursor

### Animation Specifications

| Element | Animation | Duration | Trigger |
|---------|-----------|----------|---------|
| Hero phone | Float + subtle rotate | 6s loop | On load |
| Hero phone | Rotate toward scroll | Continuous | Scroll position |
| Section headings | Fade up 20px | 600ms | Scroll into view |
| Feature cards | Stagger fade + slide | 400ms each, 100ms delay | Scroll into view |
| App screen demos | Video/Lottie loop | 4-8s | Scroll into view |
| CTA buttons | Lift + shadow | 200ms | Hover |
| Images | Blur-up reveal | 400ms | Lazy load complete |
| Page transitions | Crossfade | 300ms | Navigation |

### Micro-interactions
- **Button hover**: Scale 1.02, lift 2px, shadow spreads
- **Card hover**: Tilt 2° toward cursor, shadow deepens
- **Link hover**: Underline draws left-to-right
- **Input focus**: Border color transitions, label floats up
- **Download badge hover**: Subtle glow pulse

---

## Site Structure

### 1. Hero Section — The Flow Demo

**Layout**: Full-viewport, clean background

**Visual**: Single phone screen with continuous flow animation (Whispr Flow-inspired)

The animation shows the complete journey in one looping sequence:
1. **Scan** — Camera captures receipt, items fly into the app
2. **Track** — Items organize by freshness (green → yellow → red indicators)
3. **Nudge** — Notification slides in: "Your avocados are ready"
4. **Cook** — Recipe card appears using those ingredients
5. **Loop** — Smooth transition back to start

This single screen demonstrates all core capabilities without scrolling.

**Copy**:
> **Use** what's fresh.
>
> Foil tracks what you buy and helps you **use** it all.

**CTA**: Get Foil — Free

**Platform badges**: iOS + Android (side by side)

---

### 2. The Transformation — Before/After

**Layout**: Split screen comparison (like Whispr's speech → polished text)

**Visual**:
| Before Foil | With Foil |
|-------------|-----------|
| Cluttered fridge, mystery containers | Organized fridge, everything labeled |
| "What did I buy last week?" | Clear list sorted by freshness |
| Wilted greens in the drawer | Notification: "Use your spinach today" |
| Throwing food away | Dinner on the table |

**Copy**:
> From "I forgot I had that" to "I know exactly what's ready."

**No stats or claims** — just the visual transformation.

---

### 3. The Flow — How It Works

**Layout**: Three horizontal panels, scroll-triggered

#### Panel A: Scan
**Visual**: Receipt being photographed → items appearing one by one with satisfying stagger
**Copy**: 
> Point your phone at a receipt.
> Everything you bought, tracked in seconds.

#### Panel B: Know
**Visual**: App screen with color-coded items, one pulsing gently
**Copy**:
> See what's fresh, what's ready, what needs attention.
> Your kitchen, at a glance.

#### Panel C: **Use**
**Visual**: Notification + recipe card appearing together
**Copy**:
> Get a nudge at the right moment.
> Turn what's ready into what's for dinner.

---

### 4. Moments — When Foil Helps

**Layout**: Lifestyle-focused cards (Kinfolk imagery + short copy)

Instead of role-based tabs (like Whispr), we show **moments**:

| Moment | Image | Copy |
|--------|-------|------|
| **After grocery shopping** | Bags on counter, phone scanning receipt | "Home from the store? Scan once, done." |
| **Midweek check-in** | Person opening fridge, morning light | "What should I **use** first?" |
| **The 'what's for dinner' moment** | Ingredients on cutting board | "Recipes from what you already have." |
| **Sharing a kitchen** | Two people cooking together | "Everyone sees the same list." |

**Copy intro**:
> Foil fits into the moments that matter.

---

### 5. The Details — Feature Deep Dive

**Layout**: Expandable cards or accordion (like Whispr's AI Auto Edits section)

| Feature | What it does | Why it matters |
|---------|--------------|----------------|
| **Smart expiry dates** | AI predicts when items expire based on what they are | No manual date entry |
| **Freshness indicators** | Color-coded: green (fresh), yellow (use soon), red (use today) | Know at a glance |
| **Gentle notifications** | Reminds you before things expire, not after | You choose when and how |
| **Recipe suggestions** | AI generates ideas from what's expiring | Turn "about to go" into dinner |
| **Household sync** | Share your kitchen with family or roommates | Everyone on the same page |
| **Siri + Alexa** | "What's expiring in Foil?" | Hands-free when cooking |

**Copy intro**:
> Everything you need to **use** what you buy.

---

### 6. The Why — Without Preaching

**Layout**: Single impactful statement + subtle supporting context

**Copy**:
> Most of us buy food with good intentions.
> Foil just helps you follow through.

**Visual**: Warm lifestyle image — a meal being shared, not a statistic.

**No guilt. No stats about global food waste. Just the personal benefit.**

If we want supporting context, keep it light:
> More meals from what you buy. More money in your pocket. Less "I forgot about that."

---

### 7. Final CTA

**Layout**: Clean, centered, breathing room

**Copy**:
> Ready to **use** what you buy?

**CTA**: Download Foil — Free

**Platform badges**: iOS + Android

**Micro-copy below**: "Free to start. No credit card needed."

---

### Future: Social Proof Section (Phase 2)

*Placeholder for when we have traction:*
- App Store rating + review count
- Select user quotes (3-5, short and specific)
- Press mentions or notable users
- Outcome metrics ("Users save an average of $X/month")

For now: **skip this section entirely**.

---

## Typography

| Element | Font Style |
|---------|------------|
| Headlines | Bold geometric sans (GT Walsheim, Circular, or similar) |
| Body | Clean, readable (Inter, system sans) |
| Accent | Handwritten or quirky for playful moments |

---

## Color Palette

### Light Mode
- Background: Warm off-white `#FEFBF6`
- Primary: Rich forest green `#2D5A3D`
- Accent/CTA: Soft coral `#E8836B`
- Text: Deep charcoal `#1A1A1A`

### Dark Mode
- Background: Deep charcoal `#1A1A1A`
- Primary: Sage green `#8BA888`
- Accent/CTA: Soft coral `#E8836B`
- Text: Warm off-white `#FEFBF6`

---

## Copy Examples

| Context | Copy |
|---------|------|
| Hero tagline | **Use** what's fresh. |
| Hero alt | **Use** what's ripe. |
| Hero alt | **Use** it all. |
| Subhead | Know what's ready. **Use** it at its peak. |
| Subhead alt | Your kitchen, organized. Everything **used**. |
| Feature intro | Everything you need to **use** what you buy. |
| Scanning | Scan once. **Use** everything. |
| Notifications | Know when to **use** it. |
| Recipes | **Use** what's ready. Make something great. |
| CTA button | Start **using** Foil |
| CTA alt | **Use** Foil free |
| Footer | Made for people who **use** what they have. |
| Footer alt | For kitchens where everything gets **used**. |
| App Store | **Use** what you buy. |
| Social | **Use** at its peak. |

---

## Technical Stack

- **Framework**: HTML/CSS/JS or Next.js for page transitions
- **Animations**: GSAP + ScrollTrigger
- **3D elements**: Spline or Three.js for phone mockups
- **Video**: WebM/MP4, lazy-loaded with poster frames
- **Performance target**: 90+ Lighthouse score

---

## Additional Pages

### Our Values
**Purpose**: Mission, brand depth, emotional connection

**Current state**: Uses "waste" 10+ times, some guilt-adjacent language ("No more guilt")

**Revised structure**:

1. **Hero stat** (reframed positively):
> Americans buy more food than any country on Earth.
> Foil helps you **use** all of it.

2. **The Opportunity** (not "The Problem"):
> Life moves fast. Groceries add up.
> Foil is your kitchen's memory — so everything gets **used**.

3. **Why It Matters** (keep the 3 pillars, revise copy):

| Pillar | Current | Revised |
|--------|---------|---------|
| Wallet | "Most food waste is avoidable" | "**Use** what you buy. Keep what you save." |
| Planet | "Food waste is 8% of emissions" | "Every meal **used** is a small win for the planet." |
| Table | "Ingredients deserve to be meals, not landfill" | "Those ingredients were meant to be **used**. Let's make something." |

4. **Mission statement**:
> To help every household **use** what they buy, enjoy what they cook, and feel good doing it.
>
> **Use** it at its peak.

**Visual**: Kinfolk-style imagery — organized fridge, hands cooking, shared meal

---

### About / Story
**Purpose**: Human connection, founder narrative

**Copy direction**:
> We built Foil because we love food — buying it, cooking it, sharing it.
> We just wanted a better way to **use** it all.
> Now there is.

**Visual**: Team photo or founder story, warm and authentic

---

### Blog
**Purpose**: SEO, content marketing, recipe inspiration

**Design**: Clean cards, large imagery, easy scanning
**Integration**: Pull from existing blog system at getfoilapp.com/blog

---

### Support / FAQ
**Purpose**: Self-service help, reduce support load

**Tone**: Helpful, clear, same voice as rest of site
**Structure**: Accordion or searchable list

---

### Download
**Purpose**: Deep-link destination for campaigns

**Visual**: Large app mockup, both store badges
**Copy**: Single tagline + immediate action

---

## Download Experience

### Store Badges
- Custom-styled badges matching site palette (not default black)
- Side-by-side on desktop, stacked on mobile
- Hover: Subtle lift + glow

### QR Code Option
- For desktop users: scan to download
- Clean design, matches brand colors
- Caption: "Scan to get Foil"

### Deep Links
- `/download` → Smart redirect based on device
- `/ios` → App Store direct
- `/android` → Play Store direct

---

## Mood & Feel

### Superhuman "Futuristic" Elements
- **Precision**: Every pixel intentional, nothing arbitrary
- **Speed**: Animations feel fast but smooth, never sluggish
- **Depth**: Subtle shadows and layers create hierarchy
- **Contrast**: Dark backgrounds make content pop
- **Polish**: Transitions so smooth they feel inevitable

### Kinfolk "Warmth" Elements
- **Texture**: Real materials — wood, linen, ceramic
- **Light**: Golden hour, soft shadows
- **Humanity**: Hands, faces, lived-in spaces
- **Imperfection**: Not sterile, not over-styled
- **Calm**: Breathing room, no visual clutter

### The Balance
Superhuman's precision + Kinfolk's warmth = **Controlled comfort**

The site should feel like a beautifully designed kitchen:
organized but inviting, modern but warm, capable but calm.

---

## Navigation — Persistent Mast Band

**Inspired by**: Whispr Flow's always-visible download CTAs

### Desktop Layout
| Left | Center | Right |
|------|--------|-------|
| Logo (home link) | Our Values, Features, Blog | **Download buttons always visible** |

The download buttons (App Store + Play Store badges) remain in the nav at all times — no need to scroll to CTA sections.

### Mast Band Specs
- **Position**: Fixed top, persists across all pages
- **Background**: Frosted glass effect (`backdrop-filter: blur(20px)`)
- **Height**: 72px desktop, 64px mobile
- **Shadow**: Subtle bottom shadow on scroll (`box-shadow: 0 1px 0 rgba(0,0,0,0.05)`)
- **Download badges**: Compact versions, side-by-side, always visible

### Mobile Layout
| Left | Center | Right |
|------|--------|-------|
| Logo | — | Download button (single) + Hamburger |

On mobile, show a single "Get Foil" button that opens a sheet with both store options.

### Behavior
- **On scroll**: Slight background opacity increase for better contrast
- **On pages**: Same nav across Home, Our Values, Features, Blog
- **Download action**: 
  - Desktop: Direct links to App Store / Play Store
  - Mobile: Smart redirect based on device (iOS → App Store, Android → Play Store)

### Why This Works
- **Zero friction**: User never has to hunt for download
- **Persistent reminder**: CTA visible throughout entire session
- **Clean execution**: Badges integrated into nav, not floating awkwardly

---

**Mobile**: Hamburger menu, slide-in from right, same warm palette

---

## Component Details

### Buttons
- **Primary**: Coral `#E8836B`, white text, rounded pill (40px radius)
- **Secondary**: Transparent, green border, green text
- **Hover**: Lift 2px with soft shadow, slight scale (1.02)
- **Active**: Press down 1px, darker shade

### Cards
- Rounded corners: 16px
- Subtle shadow: `0 4px 20px rgba(0,0,0,0.08)`
- Hover: Lift with increased shadow

### Icons
- Style: Outlined, 2px stroke weight
- Corners: Rounded
- Source: Phosphor Icons or custom

### Spacing System
- Base unit: 8px
- Section padding: 80px (desktop), 48px (mobile)
- Element gaps: 16px, 24px, 32px, 48px

### Grid
- Max width: 1200px
- Columns: 12
- Gutter: 24px
- Mobile: Single column, 16px margins

---

## Responsive Breakpoints

| Breakpoint | Width | Notes |
|------------|-------|-------|
| Mobile | < 640px | Single column, stacked layout |
| Tablet | 640-1024px | Two columns, adjusted spacing |
| Desktop | > 1024px | Full layout, max animations |

---

## Image Guidelines

### Photography Style (Kinfolk)
- Natural light, warm tones
- Real kitchens, lived-in spaces
- Hands in frame — human connection
- Fresh produce as hero, not the app
- Avoid: sterile, overly styled, stock-photo feel

### Image Treatment
- Rounded corners: 12px
- Optional warm overlay: `rgba(254, 251, 246, 0.05)`
- Lazy loading with blur-up placeholder

### Required Shots
1. Hero: Hands holding phone with Foil, kitchen background
2. Fridge interior: organized, morning light
3. Cooking scene: ingredients being prepped
4. Family/lifestyle: dinner table or grocery unpacking
5. Close-up: fresh produce, texture detail

---

## Footer

**Layout**: Three columns + bottom bar

| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Logo + tagline | Features, About, Blog | App Store, Play Store badges |

**Bottom bar**: 
- Left: © 2026 Foil. All rights reserved.
- Right: Privacy, Terms, Support

**Copy** (above footer):
> For kitchens where everything gets **used**.

---

## States & Edge Cases

### Loading States
- Skeleton screens with subtle shimmer animation
- Never show spinners — feels slow
- Images: blur-up placeholder from tiny base64

### 404 Page
**Visual**: Illustrated empty fridge or confused avocado

**Copy**:
> This page got **used** up.
> (Or maybe it never existed.)
>
> Let's get you back to something fresh.

**CTA**: Go Home

### Error States
**Form errors**: Inline, coral color, friendly tone

**Copy examples**:
- "That email doesn't look quite right"
- "We couldn't connect — try again?"

### Empty States (in-app, for consistency)
- "Nothing here yet. Scan a receipt to get started."
- "Your kitchen awaits."

---

## SEO & AEO Analysis

### Current State Audit

| Element | Homepage | Blog Posts | Values Page |
|---------|----------|------------|-------------|
| Meta title | ✅ | ✅ | ✅ |
| Meta description | ✅ | ✅ | ✅ |
| OG tags | ❌ Missing | ✅ | ❌ Missing |
| Twitter cards | ❌ Missing | ✅ | ❌ Missing |
| Canonical tag | ❌ Missing | ❌ Missing | ❌ Missing |
| Organization schema | ❌ Missing | ❌ Missing | ❌ Missing |
| SoftwareApplication schema | ❌ Missing | N/A | N/A |
| Article schema | N/A | ✅ | ❌ Missing |
| FAQPage schema | ❌ Missing | ✅ (some) | ❌ Missing |
| BreadcrumbList | ❌ Missing | ❌ Missing | ❌ Missing |
| Speakable markup | ❌ Missing | ❌ Missing | ❌ Missing |

**Sitemap gaps:**
- values.html not included
- No lastmod dates
- Duplicate entry (reduce-food-waste-save-money.html appears twice)

**robots.txt:** ✅ Good (includes sitemap reference)

---

### AEO (Answer Engine Optimization) Gap Analysis

AI engines (ChatGPT, Perplexity, Google AI Overviews) prioritize:

| What AI Needs | Current State | Gap |
|---------------|---------------|-----|
| Clear entity definition | ❌ No "What is Foil?" content | High priority |
| Answer-first content | ❌ Feature-focused, not answer-focused | High priority |
| Structured comparisons | ❌ No comparison tables | Medium priority |
| FAQ content | ⚠️ Only on some blog posts | High priority |
| Author/org authority | ❌ No Organization schema | High priority |
| Citeable statistics | ❌ No original data | Medium priority |
| Topic clusters | ⚠️ Blog exists but not clustered | Medium priority |

---

### Best-in-Class Benchmarks

**App Landing Pages (Notion, Linear, Superhuman):**
- Sub-1s LCP performance
- Clear problem/solution framing
- Use case pages for different personas
- Changelog as SEO content engine
- SoftwareApplication + AggregateRating schema

**Content/AEO Leaders (Wirecutter, Healthline, NerdWallet):**
- "Our pick" / TL;DR summaries at top
- Clear comparison tables (AI extracts these)
- Expert author attribution with Person schema
- "Last updated" dates prominent
- Methodology/source transparency

---

## SEO & AEO Implementation Plan

### Priority 1: Schema Stack (Week 1)

**Homepage — Add these schemas:**

```json
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "Organization",
      "@id": "https://getfoilapp.com/#organization",
      "name": "Foil",
      "url": "https://getfoilapp.com",
      "logo": "https://getfoilapp.com/images/foil_icon.png",
      "sameAs": [
        "https://instagram.com/getfoilapp",
        "https://facebook.com/getfoilapp"
      ]
    },
    {
      "@type": "WebSite",
      "@id": "https://getfoilapp.com/#website",
      "url": "https://getfoilapp.com",
      "name": "Foil",
      "publisher": {"@id": "https://getfoilapp.com/#organization"}
    },
    {
      "@type": "SoftwareApplication",
      "name": "Foil",
      "applicationCategory": "LifestyleApplication",
      "operatingSystem": "iOS, Android",
      "offers": {
        "@type": "Offer",
        "price": "0",
        "priceCurrency": "USD"
      },
      "description": "Foil tracks what you buy and helps you use it all. Scan receipts, get expiry reminders, find recipes.",
      "author": {"@id": "https://getfoilapp.com/#organization"}
    }
  ]
}
```

**All pages — Add:**
- Canonical tags: `<link rel="canonical" href="...">`
- BreadcrumbList schema
- OG tags + Twitter cards

---

### Priority 2: AEO Content Structure (Week 2)

**Add to homepage — "What is Foil?" section:**

```html
<section id="what-is-foil">
  <h2>What is Foil?</h2>
  <p><strong>Foil is a food tracking app</strong> that helps you use everything you buy. 
  Scan a grocery receipt, and Foil tracks expiration dates, sends reminders before 
  things go bad, and suggests recipes based on what's ready to use.</p>
</section>
```

This single paragraph is **AI citation bait** — a clear, extractable definition.

**Add FAQ section to homepage:**

| Question | Answer |
|----------|--------|
| How does Foil work? | Scan your grocery receipt, and Foil automatically tracks what you bought with smart expiration dates. |
| Is Foil free? | Yes, Foil is free to download and use. Premium features are available for households. |
| What devices does Foil support? | Foil is available on iPhone (iOS 15+) and Android. |
| How does Foil know when food expires? | Foil uses AI to predict expiration dates based on the type of food and how it's stored. |

Implement as collapsible FAQ with FAQPage schema.

---

### Priority 3: Content for AI Citation (Week 3-4)

**Create these high-AEO pages:**

| Page | Target Query | Structure |
|------|--------------|-----------|
| `/how-it-works` | "how does food tracking app work" | Step-by-step with HowTo schema |
| `/vs-alternatives` | "best food expiration app" | Comparison table (Foil vs spreadsheets vs nothing) |
| `/food-expiry-guide` | "how long does X last" | Comprehensive guide, link to blog posts |

**Blog content clusters:**

| Cluster | Hub Page | Spoke Posts |
|---------|----------|-------------|
| **Food storage** | /blog/food-storage-guide | Chicken, dairy, produce, leftovers |
| **Meal planning** | /blog/meal-planning-101 | Weekly planning, batch cooking, freezer meals |
| **Kitchen organization** | /blog/organized-kitchen | Fridge setup, pantry, labeling |

Each hub links to spokes; spokes link back to hub. AI sees topical authority.

---

### Priority 4: Technical SEO Fixes (Week 1-2)

**Immediate fixes:**

- [ ] Add OG tags to homepage + values page
- [ ] Add Twitter cards to all pages
- [ ] Add canonical tags site-wide
- [ ] Fix sitemap (add values.html, remove duplicate, add lastmod)
- [ ] Add BreadcrumbList schema to all pages
- [ ] Create /blog/index.html schema (ItemList of articles)

**Performance targets:**

| Metric | Current | Target |
|--------|---------|--------|
| LCP | ~2.5s (estimate) | <1.5s |
| INP | Unknown | <200ms |
| CLS | Low (good) | <0.1 |

**Quick wins:**
- Preload hero image with `fetchpriority="high"`
- Subset fonts (only needed weights/characters)
- Lazy load below-fold images
- Inline critical CSS

---

### Priority 5: Speakable & Voice (Phase 2)

Add Speakable schema to key content sections:

```json
{
  "@type": "WebPage",
  "speakable": {
    "@type": "SpeakableSpecification",
    "cssSelector": [".what-is-foil", ".faq-answer", ".key-takeaway"]
  }
}
```

This marks content suitable for voice assistants and audio AI responses.

---

### AEO Content Patterns to Follow

**Definition pattern** (for AI extraction):
> "Foil is a food tracking app that helps households use everything they buy."

**Comparison pattern**:
> "Unlike spreadsheets, Foil automatically tracks expiration dates from receipt scans."

**Step pattern**:
> "To track your groceries with Foil: 1) Open the app, 2) Scan your receipt, 3) Review and save."

**Statistic pattern** (when we have data):
> "Foil users report using 30% more of what they buy compared to before."

---

### Competitive AEO Queries to Target

| Query | Current Ranking | Opportunity |
|-------|-----------------|-------------|
| "food expiration tracking app" | Not ranking | High — SoftwareApplication schema + content |
| "how long does chicken last in fridge" | Blog post exists | Medium — add HowTo schema |
| "best app to reduce food waste" | Not ranking | High — comparison page |
| "grocery receipt scanner app" | Not ranking | Medium — feature page |
| "meal planning from what I have" | Not ranking | Medium — recipe feature content |

---

## Meta & SEO (Revised)

### Page Titles
- Home: "Foil — **Use** what's fresh"
- Our Values: "Our Values — Foil"
- Features: "Features — Foil"
- About: "Our Story — Foil"
- Blog: "Blog — Foil"
- How It Works: "How Foil Works — Food Tracking Made Simple"
- Food Expiry Guide: "How Long Does Food Last? Complete Guide — Foil"

### Meta Descriptions

| Page | Description |
|------|-------------|
| Home | Foil tracks what you buy and helps you use it all. Scan receipts, get expiry reminders, find recipes. Free for iOS and Android. |
| Blog | Tips on meal planning, food storage, and making the most of what you buy. From Foil. |
| How It Works | Scan a receipt, track expiration dates, get reminders, find recipes. Here's how Foil helps you use everything you buy. |

### OG Image
- App mockup on warm background
- Tagline: "**Use** what's fresh."
- Size: 1200x630px

### Canonical URL Structure
- Homepage: `https://getfoilapp.com/`
- Blog index: `https://getfoilapp.com/blog/`
- Blog posts: `https://getfoilapp.com/blog/posts/[slug].html`
- Values: `https://getfoilapp.com/values.html`

---

## Accessibility

- Color contrast: WCAG AA minimum (4.5:1 for text)
- Focus states: Visible outline on all interactive elements
- Alt text: Descriptive, not decorative
- Reduced motion: Respect `prefers-reduced-motion`
- Keyboard navigation: Full site navigable without mouse
- Screen reader: Semantic HTML, ARIA labels where needed

---

## Performance Budget

| Metric | Target |
|--------|--------|
| Lighthouse Performance | 90+ |
| First Contentful Paint | < 1.5s |
| Largest Contentful Paint | < 2.5s |
| Total page weight | < 2MB |
| Images | WebP, lazy-loaded |
| Fonts | Subset, preloaded |

---

## Browser Support

- Chrome (last 2 versions)
- Safari (last 2 versions)
- Firefox (last 2 versions)
- Edge (last 2 versions)
- iOS Safari (last 2 versions)
- Chrome Android (last 2 versions)

---

## Analytics & Tracking

- Tool: Plausible or Fathom (privacy-focused)
- Events: Download clicks, feature section views, scroll depth
- No: Invasive tracking, cookie banners

---

## Phases (Revised)

| Phase | Scope | Timeline |
|-------|-------|----------|
| 1: Foundation | Sitemap, wireframes, copy deck, color/type system | Week 1 |
| 2: Design | High-fidelity mockups (Figma), all pages | Week 2 |
| 3: Development | HTML/CSS/JS build, basic animations | Week 3 |
| 4: Motion | GSAP animations, 3D mockups, scroll effects | Week 4 |
| 5: Content | Photography, final copy, SEO meta | Week 5 |
| 6: Polish | Dark mode, performance tuning, accessibility audit | Week 6 |
| 7: Launch | DNS, redirects, analytics, monitoring | Week 7 |

---

## Asset Requirements

### Claude Can Produce

| Asset | Notes |
|-------|-------|
| **All code** | HTML, CSS, JS, animations (GSAP), responsive layout |
| **Copy** | All headlines, body text, microcopy, meta descriptions |
| **Animation implementation** | Scroll effects, hover states, page transitions |
| **SVG icons** | Custom or from Phosphor Icons |
| **Color system** | CSS variables, dark mode |
| **Component library** | Buttons, cards, nav, footer |
| **Wireframes** | In code or markdown |
| **404 page** | Illustrated with CSS/SVG |
| **Placeholder mockups** | Basic phone frames with app screenshots |

### Required From User

| Asset | Why |
|-------|-----|
| **Photography** | Kinfolk-style lifestyle shots (kitchen, hands, produce, meals) — 4-5 hero images |
| **Hero flow animation** | Screen recording or Lottie of app in action (scan → track → nudge → cook) |
| **App screenshots** | Current high-res screens for mockups |
| **Logo files** | SVG preferred |
| **Final tagline decision** | Which **Use** variant to lead with |
| **Copy approval** | Review before launch |

### Either Way (Decide Later)

| Asset | Option A (User) | Option B (Claude) |
|-------|-----------------|-------------------|
| **Photography** | Commission original shoots | Source premium stock (Unsplash+, Stocksy) |
| **Flow animation** | Screen record the app | Build Lottie/video from screenshots |
| **3D phone mockup** | Provide Figma/Spline file | Create in Spline or use CSS 3D |

**Biggest dependency**: Photography — sets the Kinfolk tone. Everything else can be built or approximated.

---

## Open Questions

- [ ] Commission original photography or source premium stock?
- [ ] Dark mode as default, toggle, or system preference?
- [ ] Video vs pure animation for hero (performance tradeoff)?
- [ ] Localization needs (multi-language)?
- [ ] Blog: migrate to new design or keep separate?
- [ ] Newsletter signup integration?
- [ ] Testimonials: source from App Store reviews or request new?
