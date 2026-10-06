# Gunjan's BiteBox — Website Worklog & Handoff

## Project
- Brand: **Gunjan's BiteBox**
- Customer service area: **Entire Indore**
- Kitchen/base: Gokul Nagar / Kanadia Road, Indore
- Ordering: **Swiggy and Zomato only**
- Delivery: Platform delivery; owner does not personally deliver
- Website: Static landing page
- Main file: `index.html`
- Hosting direction: GitHub Pages
- Version control: GitHub is the source of truth

## Critical business rule
The kitchen location is not the customer-facing service area. Always position the brand as **serving Indore / across Indore**, not only Gokul Nagar or Kanadia Road.

Use wording such as:
- Serving Indore
- Across Indore
- Delivery across Indore

Do not imply neighborhood-only delivery unless explicitly requested.

## Current website architecture

```text
gunjans-bitebox-website/
├── index.html
└── WORKLOG.md
```

`index.html` currently contains:
- HTML structure
- Embedded CSS
- No backend
- No database
- No framework
- No JavaScript dependency

The current design is modern, minimal, mobile-first, warm and food-oriented.

## Current page sections

### 1. Header
Brand: `Gunjan's BiteBox`

Location label:
`Serving Indore`

The temporary brand mark displays `B`. Replace it with the final logo when available.

### 2. Hero
Current headline:
`Good food. Coming soon.`

The hero explains that Gunjan's BiteBox is preparing fresh, tasty and thoughtfully packed food for delivery across Indore.

Current CTA:
`Discover BiteBox ↓`

The CTA scrolls to the About section.

### 3. About
Heading:
`Who we are`

Positioning:
Gunjan's BiteBox is a delivery-first food kitchen focused on fresh, satisfying food and repeat orders.

### 4. Promise
Current points:
- Freshly prepared
- Packed with care
- Made for repeat orders

### 5. Value cards
Current cards:
- Everyday Food
- Quality First
- Coming to Your Door

The delivery card references Swiggy and Zomato intentionally.

### 6. Launch section
Current status:
`Launching soon in Indore`

It communicates that the menu, launch offers and Swiggy/Zomato ordering links are coming soon.

### 7. Footer
Current:
`© 2026 Gunjan's BiteBox · Serving Indore`

## Intended customer workflow

```text
Customer discovers website
        ↓
Understands Gunjan's BiteBox
        ↓
Sees "Serving Indore"
        ↓
Views menu / offers
        ↓
Clicks Swiggy or Zomato
        ↓
Order + payment + delivery handled by platform
```

The website is NOT intended to process orders or payments itself.

## Swiggy / Zomato rules

At launch, add real platform links:
- `Order on Swiggy`
- `Order on Zomato`

Do **not** invent URLs. Use the actual restaurant listing URLs once the restaurant is live.

Do not add WhatsApp ordering unless the owner explicitly changes the ordering strategy.

## Future launch changes

Before launch:
- Coming-soon messaging
- Brand introduction
- Quality/freshness messaging
- Indore-wide service positioning
- Upcoming Swiggy/Zomato availability

At launch:
- Real food photography
- Menu preview
- Prices where appropriate
- Signature dishes
- Swiggy button
- Zomato button
- Launch offer
- Business hours
- Food categories

Possible later additions:
- Customer reviews
- Instagram link
- FAQ
- Google Business link
- SEO improvements
- Analytics
- Structured data/schema

## Design system

Current CSS uses a warm food-brand palette:
- Ink: `#21150f`
- Muted: `#6e625b`
- Cream: `#fff9ef`
- Orange: `#ef5b2a`
- Dark orange: `#c93f16`
- Gold: `#f5b841`

Keep the site:
- Responsive
- Mobile-friendly
- Fast-loading
- Accessible
- Simple to maintain

Do not add a framework or large dependency for a simple change.

## Brand rules

Brand name must remain:
**Gunjan's BiteBox**

Possible tagline directions discussed:
- Har Bite Mein Mazaa
- Good Food. Packed with Love.
- Freshness in Every Box
- Made Fresh. Packed Right.

No tagline is final unless the owner explicitly chooses one.

## GitHub workflow — IMPORTANT

**GitHub is the source of truth.**

For every meaningful website change:

1. Pull/check the latest GitHub version.
2. Make the requested change.
3. Test the website locally.
4. Check responsive/mobile layout.
5. Review the changed code.
6. Update `WORKLOG.md` if project knowledge or architecture changed.
7. Commit the change to GitHub.
8. Push the commit.
9. Confirm GitHub Pages deployment when applicable.

Suggested commit messages:
- `Update homepage messaging for Indore-wide delivery`
- `Add Swiggy and Zomato ordering buttons`
- `Update menu section`
- `Improve mobile responsive layout`

Avoid vague commit messages such as `changes`, `update`, `final`, or `test`.

### GitHub Pages
Expected configuration:
- Source: Deploy from a branch
- Branch: `main`
- Folder: `/ (root)`
- Entry file: `index.html`

Never claim a change was committed/pushed unless the GitHub operation actually succeeded.

If GitHub access is unavailable, say clearly that the local file was changed but the GitHub commit could not be completed.

## Multi-location / multi-agent handoff

When another agent receives `WORKLOG.md` and `index.html`, it should:

1. Read this worklog completely.
2. Read `index.html`.
3. Check the latest GitHub state.
4. Understand whether the requested change is content, design, business logic, or technical.
5. Preserve existing behavior unless the owner requests otherwise.
6. Test the result.
7. Update this worklog when a project-level decision changes.
8. Commit and push the relevant changes to GitHub.
9. Report exactly what was changed and the commit status.

## What NOT to do

- Do not rename the brand without approval.
- Do not change Indore-wide positioning back to neighborhood-only positioning.
- Do not invent Swiggy/Zomato links.
- Do not add WhatsApp ordering without approval.
- Do not remove existing functionality just to simplify the page.
- Do not introduce unnecessary frameworks.
- Do not claim GitHub commit/push completion without actually doing it.

## Current confirmed decisions

- Brand: Gunjan's BiteBox
- Market: Indore
- Service area: Entire Indore
- Kitchen/base: Gokul Nagar / Kanadia Road
- Ordering: Swiggy + Zomato
- Delivery: Platform delivery
- Website: Static HTML
- Main file: `index.html`
- Hosting: GitHub Pages
- Version control: GitHub commits

## Not yet finalized

- Final logo
- Final tagline
- Final menu
- Food photography
- Swiggy restaurant URL
- Zomato restaurant URL
- Launch date
- Launch offers
- Business hours
- Social media links
- Final SEO keywords

## Worklog maintenance rule

This file documents project knowledge and decisions, not every tiny CSS edit.

Update it when any of these change:
- Brand positioning
- Delivery model
- Ordering platform
- Menu strategy
- Page structure
- Design system
- File structure
- Technology stack
- GitHub deployment
- Important business rules
- Customer workflow

Detailed individual changes belong in Git commit history.
