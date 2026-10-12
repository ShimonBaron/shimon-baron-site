# Build prompt — Shimon Baron personal website

## Role
You are a senior front-end developer. Build a personal professional website for **Shimon Baron** in this folder (`/Users/shimonbaron/Documents/10X/lesson-7`).

## Goal
A professional profile / online CV aimed at recruiters, executives and peers looking for a CMO / VP Marketing in fintech, trading & brokerage. A visitor should understand within 5 seconds who Shimon is, what he has achieved, and how to reach him.

## Hard constraints
- Plain **HTML + CSS + minimal vanilla JS**. No frameworks, no build step, no npm. Must work by opening `index.html` directly and on GitHub Pages.
- Files: `index.html`, `styles.css`, `script.js` (only if needed), `README.md`, `.gitignore`, `assets/` (favicon SVG, Open Graph image SVG/PNG optional).
- **English only.**
- **Privacy:** do NOT publish phone number, email address, home address, or the CV PDF. Contact = LinkedIn + GitHub links only.
- `.gitignore` must exclude `*.pdf`, `.claude/`, `.DS_Store`.
- Use **only facts from the content below**. Do not invent numbers, employers, quotes, testimonials or awards.
- **Do NOT push, do NOT create a GitHub repo, do NOT run `gh`.** Only `git init`, `git add`, `git commit` locally on branch `main`. Stop after the local commit.

## Design
- Minimal & clean: generous white space, one accent color (deep blue, e.g. `#1f4e8c` family), strong typography (system font stack or one Google Font such as Inter).
- Light and dark mode via `prefers-color-scheme`, colors defined as CSS custom properties on `:root`.
- Fully responsive (mobile first, ~360px up to wide desktop), no horizontal scroll.
- Sticky slim top nav with anchor links; smooth scroll; subtle fade-in on scroll (respect `prefers-reduced-motion`).
- Profile image: a circular **"SB" initials avatar** made in CSS/SVG, built so it can later be swapped for `assets/photo.jpg` by changing one line (leave an HTML comment explaining how).

## Sections (in order)
1. **Hero** — name, headline "CMO | VP Marketing | Trading & Brokerage", location Tel Aviv, one-sentence pitch, buttons: "View experience" (anchor) and "Connect on LinkedIn".
2. **Key numbers** strip — 15+ years in marketing · $30M+/year budgets managed · Crypto became eToro's #1 revenue engine (2021) · Team of 9 built from scratch at XBO.
3. **About** — 2 short paragraphs based on the summary below.
4. **Experience** — vertical timeline, newest first, company · title · years, 2–4 bullets each (condense, keep the strongest facts). "Previous roles" as a compact list at the end.
5. **Skills & Tools** — grouped chips/tags by category.
6. **Education & more** — education, military service, languages.
7. **Contact / footer** — LinkedIn and GitHub icon links, "© 2026 Shimon Baron".

## Quality bar
- Semantic HTML5 (`header`, `nav`, `main`, `section`, `footer`), one `h1`, logical heading order.
- Accessibility: alt text / aria-labels, visible focus states, AA color contrast, skip-to-content link.
- SEO: `<title>`, meta description, Open Graph + Twitter card tags, JSON-LD `Person` schema (name, jobTitle, address locality Tel Aviv, sameAs LinkedIn + GitHub), canonical URL `https://shimonbaron.github.io/shimon-baron-site/`.
- Inline SVG icons (no icon CDN). Favicon as SVG with "SB".
- All links to external sites use `target="_blank" rel="noopener"`.
- Validate mentally: no broken anchors, no console errors.

## README.md
Short: what the site is, live URL placeholder `https://shimonbaron.github.io/shimon-baron-site/`, how to run locally (open `index.html`), how to swap in a real photo, tech used. Mention it was built for the 10X course, lesson 7, with Claude Code.

## Links
- LinkedIn: https://www.linkedin.com/in/shimonbaron/
- GitHub: https://github.com/ShimonBaron

## Content (source: Shimon's CV, Sep 2026)

**Summary:** CMO / VP Marketing who builds acquisition engines from zero. Led marketing for eToro's crypto vertical as it became the company's #1 revenue engine, and built XBO's marketing department from the ground up. 15+ years in marketing, including 5 in regulated trading and brokerage. Managing marketing budgets of $30M+/year, full-funnel ownership — onboarding optimization, CRM automation, and performance marketing. Building agentic AI systems that run real marketing work — research, content, reporting, and campaign operations — and training teams to work the same way. Managing cross-functional teams, agencies, and partnerships in global B2C, B2B, and Web3 environments.

**Experience**
- **Ogen** — Marketing Manager, Business Division — 2025–Present
  - Leading marketing for the business division of a regulated non-bank lender — SME and agricultural credit.
  - End-to-end marketing for four units concurrently: advisor-led credit, digital self-service credit, business mentoring, and community management — each with its own funnel, targets and audience.
  - Working closely with legal and compliance so campaigns, landing pages and credit messaging clear review the first time.
  - Built an internal AI compliance agent trained on the lender's regulatory rules, screening marketing copy before legal review.
- **Posteam (Startup)** — VP Marketing / CMO — 2023–2025
  - Led strategic planning and GTM for an AI-based social media marketing platform.
  - Developed AI-driven marketing solutions with R&D: automation, predictive analytics, personalization.
  - Built strategic commercial partnerships and new distribution channels.
  - Delivered AI lectures and workshops at schools and educational institutions.
- **XBO FinTech** — CMO / VP Marketing — 2022–2023
  - Built the marketing department from scratch: team of 9 across Cyprus, Poland, Ukraine and Germany.
  - Comprehensive marketing strategy; annual budget of $3M+.
  - Launched an XP-based gamification system to improve retention and engagement.
  - Built and ran the affiliate program; owned digital, global PR, influencer programs and brand partnerships.
  - Made tracking and attribution a precondition for scaling any channel (app vs. web source identification).
  - 20% growth in customer acquisition and 30% increase in website traffic in the first year.
- **eToro FinTech** — Crypto & eToro Money Marketing Manager — 2020–2022
  - Built eToro's crypto marketing operation from the ground up; crypto became eToro's #1 revenue engine in 2021, surpassing stock trading.
  - Managed a monthly media budget of $3M+ across digital channels.
  - Ran the funnel end to end on CPL, CPA, CAC, FTD, LTV and ROAS.
  - B2C marketing across regulated entities — UK (FCA), Europe (CySEC), Australia (ASIC), Gibraltar (GFSC).
  - Large-scale UK campaigns: football sponsorships, TV, out-of-home and underground, plus full digital mix.
  - Three business lines in parallel: B2C crypto, B2B via eToro X, and eToro Money (FCA e-money).
  - Led new coin launches and partnerships with external coin communities.
- **Cisco Israel** — Digital Marketing Manager — 2018–2020
  - Built Cisco Israel's digital infrastructure from scratch, aligned with global strategy.
  - Developed customer touchpoints, improved UX, and grew e-commerce.
- **ZAP Group – Yellow Pages** — Division Manager — 2017–2018
  - Managed a $28M business unit — marketing, analytics, content and technology teams.
  - Led rebranding, implemented self-service to grow e-commerce, developed new products.
- **Cue.AD** — Founder & CEO — 2012–2017
  - Founded and managed a technology-driven online radio advertising startup.
- **Previous roles:** Shufersal — Digital Marketing & eCommerce Manager (established "Shufersal Online") · Pelephone — Marketing Manager · EURO RSCG Digital — Digital Account Manager

**Skills & Tools**
- AI & Automation: Claude Code, ChatGPT, Claude, Gemini, Grok, GenSpark, Make, n8n, Buzz, Midjourney, Leonardo, Flux, Kling, Seedream, Nano Banana
- Analytics & BI: Google Analytics, Mixpanel, Power BI, Tableau, Looker
- Tracking & Attribution: Google Tag Manager, AppsFlyer, Hotjar, Microsoft Clarity, Smartlook
- CRM & Automation: HubSpot, Salesforce, Oracle Eloqua, Marketo, ActiveCampaign, Mailchimp
- Paid Media: Google Ads, Facebook Ads, Taboola
- Web3: Discord, Telegram, Dune, Galxe

**Education**
- BA in Business Administration — University of Derby
- Strategic Marketing & Advertising — "HaBatzper"
- Industrial Engineering & Management — IDF Air Force College

**Military service:** Regular & career service, IDF Air Force — Team Commander, Mitzpe Ramon
**Languages:** Hebrew (native), English (highly proficient)

## Done when
- All files exist, `index.html` renders correctly on mobile and desktop in light and dark mode.
- `git status` is clean after one local commit on `main` with message "Initial personal website".
- The CV PDF is NOT tracked (`git ls-files` shows no .pdf).
- Finish with a short summary: files created, anything you were unsure about.
