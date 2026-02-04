# SlimLife Website - Owner Todo List

## Before Launch

### 1. Replace Placeholder Content

- [ ] **Phone number**: Replace `(555) 123-4567` with your real phone number
  - Files: `index.html`, `services.html`, `about.html` (multiple locations in each)

- [ ] **Address**: Replace `123 Wellness Ave, Suite 100, City, ST 12345` with your real address
  - Files: `index.html`, `services.html`, `about.html` (footer), `about.html` (contact section)

- [ ] **Hours of operation**: Update `Mon-Sat: 9AM-7PM` with your actual hours
  - Files: `index.html`, `services.html`, `about.html` (footer), `about.html` (contact section)

- [ ] **City name**: Replace "Your City" in the hero subtitle with your actual city
  - File: `index.html` (hero section)

### 2. Set Up Contact Form

- [ ] Create a free account at [Formspree.io](https://formspree.io)
- [ ] Create a new form and copy your form ID
- [ ] Replace `YOUR_FORM_ID` in `about.html` with your actual Formspree form ID
  - Line to find: `action="https://formspree.io/f/YOUR_FORM_ID"`

### 3. Add Google Maps

- [ ] Go to [Google Maps](https://maps.google.com)
- [ ] Search for your business address
- [ ] Click "Share" → "Embed a map"
- [ ] Copy the iframe code
- [ ] Replace the placeholder in `about.html` (look for `<!-- Replace with actual Google Maps embed -->`)

### 4. Add Images

**Hero Image** (optional - currently using gradient):
- [ ] Add a calming spa/wellness image to `images/hero/hero-bg.jpg`

**Service Images** (for Services page):
- [ ] `images/services/lymphatic-drainage.jpg`
- [ ] `images/services/face-lymphatic.jpg`
- [ ] `images/services/radio-frequency.jpg`
- [ ] `images/services/collagen-tornado.jpg`
- [ ] `images/services/suction-therapy.jpg`
- [ ] `images/services/wood-therapy.jpg`
- [ ] `images/services/bellustone.jpg`

**Founder Photo**:
- [ ] Add your photo to `images/about/founder.jpg`

**Logo** (optional):
- [ ] Add logo to `images/logo.png`

### 5. Update Testimonials

- [ ] Replace the 3 placeholder testimonials in `index.html` with real Google reviews
- [ ] Update client names (or use initials for privacy)

### 6. Review & Customize Content

- [ ] Update founder bio in `about.html` with your personal story
- [ ] Review service descriptions and adjust as needed
- [ ] Update copyright year if needed (currently 2026)

---

## Deployment

### Option A: Netlify (Recommended - Free)
- [ ] Create account at [netlify.com](https://netlify.com)
- [ ] Drag and drop the `slimlife` folder to deploy
- [ ] Set up custom domain (optional)
- [ ] Note: Netlify Forms can replace Formspree if preferred

### Option B: GitHub Pages (Free)
- [ ] Push code to GitHub repository
- [ ] Enable GitHub Pages in repository settings
- [ ] Set up custom domain (optional)

### Option C: Vercel (Free)
- [ ] Create account at [vercel.com](https://vercel.com)
- [ ] Import from GitHub or drag and drop
- [ ] Set up custom domain (optional)

---

## Optional Enhancements

- [ ] Add a favicon (`favicon.ico` in root folder)
- [ ] Add Open Graph meta tags for social sharing
- [ ] Set up Google Analytics
- [ ] Add schema.org structured data for local business
- [ ] Optimize images (compress before uploading)
