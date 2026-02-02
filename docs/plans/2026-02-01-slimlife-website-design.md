# SlimLife Website Design

## Overview

A 3-page marketing website for SlimLife, a body contouring and Brazilian lymphatic drainage massage studio. The site educates visitors on services, builds trust through the founder's story and testimonials, and drives phone calls for appointment bookings.

## Site Structure

```
SlimLife Website
├── Home (index.html)
├── Services (services.html)
└── About/Contact (about.html)
```

---

## Page Designs

### Home Page

**Hero Section**
- Full-width calming background image (spa environment or abstract wellness imagery)
- Gradient overlay for text readability
- Headline: Benefit-focused tagline (e.g., "Sculpt. Restore. Renew.")
- Subtext: "Specialized Brazilian Lymphatic Drainage & Body Contouring in [City]"
- Primary CTA: "Call to Book" button with phone number

**Services Overview Section**
- Section title: "Our Treatments"
- 3-4 preview cards of featured services
- Each card: image, service name, one-line description
- "View All Services" link to Services page
- Clean grid layout with subtle hover effects

**Testimonials Section**
- Section title: "What Our Clients Say"
- 2-3 curated Google review quotes
- Client first name attribution
- Quote styling with large quotation marks, italic text
- Optional star rating visual

**Call-to-Action Banner**
- Full-width soft green or lavender background
- Text: "Ready to feel your best?"
- Large phone number + "Call Now" button

---

### Services Page

**Page Header**
- Soft hero with title: "Our Services"
- Brief intro about SlimLife's approach to body contouring and lymphatic wellness

**Featured Services Section**
- Section title: "Signature Treatments"
- 7 premium services displayed prominently:
  1. Brazilian Lymphatic Drainage Massage (flagship, first position)
  2. Brazilian Face Lymphatic System
  3. Radio Frequency & Ultrasonic Cavitation
  4. Collagen Tornado
  5. Radio Frequency & Suction Therapy
  6. Wood Therapy
  7. Bellustone Abdominal Therapy
- Each service card includes:
  - Service image
  - Service name
  - Description (2-3 sentences on what it is and benefits)
  - Optional: duration, price range
- Layout: alternating left/right rows or uniform card grid

**Additional Services Section**
- Section title: "Additional Treatments"
- Compact list or smaller cards
- Service name + brief one-liner each
- Messaging: "Call to learn more about these treatments"

**Bottom CTA**
- Text: "Not sure which treatment is right for you? Call us for a consultation."
- Phone number + button

---

### About/Contact Page

**Page Header**
- Soft hero with title: "About SlimLife"

**Founder Story Section**
- Headline: "Meet [Founder Name]" or "Our Story"
- Founder photo (placeholder initially)
- 2-3 paragraphs covering:
  - Personal journey
  - Training in Brazilian techniques
  - Passion for helping clients feel confident
- Warm, personal tone

**Results & Science Section**
- Headline: "Why Lymphatic Drainage Works"
- Brief explanation of science/benefits:
  - Detoxification
  - Body contouring
  - Wellness and recovery
- Optional: icons representing benefits or before/after imagery

**Contact Section**
- Headline: "Visit Us"

*Contact Form:*
- Name (required)
- Email (required)
- Phone (optional)
- Message (required, textarea)
- Submit button: "Send Message"
- Success message: "Thanks! We'll get back to you soon."
- Powered by Formspree or Netlify Forms (no backend required)

*Contact Details:*
- Phone number (large, prominent)
- Address
- Hours of operation

*Map:*
- Embedded Google Map showing location

**Final CTA**
- Text: "Book Your Appointment Today"
- Phone number button

---

## Visual Design

### Color Palette
| Role | Color | Hex |
|------|-------|-----|
| Primary | Sage green | #8FAE8B |
| Secondary | Cream/off-white | #FAF9F6 |
| Accent | Soft lavender | #E6E6FA |
| Text | Dark charcoal | #2D2D2D |

### Typography
- **Headings:** Elegant serif (Playfair Display or Cormorant)
- **Body:** Clean sans-serif (Lato or Open Sans)
- **Hierarchy:** Large hero text > medium section headers > comfortable body text

### Visual Elements
- Soft, rounded corners on cards and buttons
- Subtle shadows for depth
- Gentle gradient overlays on hero images
- Generous white space throughout
- High-quality imagery

### Overall Feel
Airy, calming, professional - like walking into a high-end wellness studio.

---

## Technical Specifications

### File Structure
```
slimlife/
├── index.html
├── services.html
├── about.html
├── css/
│   └── styles.css
├── js/
│   └── main.js
└── images/
    ├── logo.png
    ├── hero/
    ├── services/
    └── about/
```

### Technology
- Plain HTML5, CSS3, vanilla JavaScript
- No frameworks or build tools
- Google Fonts for typography
- Formspree for contact form handling

### Responsive Design
- Mobile-first approach
- Breakpoints:
  - Mobile: <768px
  - Tablet: 768-1024px
  - Desktop: >1024px
- Hamburger menu on mobile
- Stacked layouts on mobile, grids on desktop

### Navigation
- Top nav bar on all pages
- Logo + page links (Home, Services, About/Contact)
- Prominent "Call Now" button
- Hamburger menu on mobile

### Footer
- Consistent across all pages
- Phone number, address, hours
- Social media links (if applicable)

### Performance
- Minimal dependencies
- Optimized/compressed images
- Efficient font loading
- Fast page loads

### Hosting
- Static files deployable to:
  - Netlify (free, includes form handling)
  - Vercel
  - GitHub Pages
  - Any static web host

---

## Content Requirements (Placeholders Needed)

- [ ] Logo
- [ ] Hero images (1-3 calming/wellness images)
- [ ] Service images (7 featured + additional services)
- [ ] Founder photo
- [ ] Service descriptions and pricing
- [ ] Founder bio/story
- [ ] 2-3 curated testimonial quotes
- [ ] Business address
- [ ] Phone number
- [ ] Hours of operation
- [ ] Google Maps embed code
