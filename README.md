# IdeasPRO

A curated collection of validated, buildable project ideas designed to generate revenue. Each idea includes a product overview, monetization model, tech stack, competitive analysis, and a Figma schematic.

---

## Ideas Index

| # | Project | Model | Est. MRR Potential | Difficulty |
|---|---------|-------|-------------------|------------|
| 1 | [ReceiptAI](#1-receiptai) | SaaS Subscription | $5K–$50K | Medium |
| 2 | [LocalLaunch](#2-locallaunch) | Agency-as-a-SaaS | $10K–$100K | Medium-High |
| 3 | [SkillBridge](#3-skillbridge) | Marketplace Commission | $8K–$80K | High |
| 4 | [AutoEntrepreneur.ai](#4-autoentrepreneurai) | SaaS Subscription | €5K–€30K | Low-Medium |
| 5 | [ContratIA](#5-contratia) | Pay-per-use + Subscription | €3K–€20K | Low |
| 6 | [AssociatIA](#6-associatia) | SaaS Subscription | €8K–€55K | Medium |
| 7 | [AideMax](#7-aidemax) | Pay-per-report + Subscription | €4K–€25K | Low |
| 8 | [DécoDPE](#8-décodpe) | Pay-per-report + B2B SaaS | €5K–€30K | Low |
| 9 | [LeBonCoinIA](#9-leboncoinia) | Freemium + Pay-per-use | €3K–€18K | Low |
| 10 | [LoyerCheck](#10-loyercheck) | Freemium + Pay-per-report | €4K–€22K | Low |
| 11 | [EtatDesLieux.ai](#11-etatdeslieuxai) | Pay-per-document | €5K–€28K | Low |
| 12 | [ImpotsSimple](#12-impotssimple) | Freemium + Pay-per-use | €8K–€60K | Low-Medium |
| 13 | [RecoursFacile](#13-recoursfacile) | Pay-per-letter + Upsell | €3K–€16K | Low |
| 14 | [PermisIA](#14-permisia) | Freemium + Subscription | €6K–€45K | Medium |
| 15 | [VintedPro](#15-vintedpro) | Pay-per-listing + Subscription | €4K–€30K | Low |
| 16 | [RénovSimple](#16-rénovsimple) | Pay-per-report + B2B SaaS | €6K–€40K | Low-Medium |
| 17 | [HéritageFacile](#17-héritagefacile) | Pay-per-report + Upsell | €5K–€35K | Low |
| 18 | [CVFrançais.ai](#18-cvfrançaisai) | Pay-per-dossier + Subscription | €5K–€40K | Low |
| 19 | [VTCPro](#19-vtcpro) | SaaS Subscription | €6K–€35K | Low |
| 20 | [AlloDevis](#20-allodevis) | SaaS Subscription | €5K–€28K | Low |
| 21 | [GîteBoost](#21-gîteboost) | SaaS Subscription | €8K–€50K | Low-Medium |
| 22 | [CoPro.ai](#22-coproai) | Pay-per-report + Subscription | €4K–€22K | Low |
| 23 | [MenuSaisonnier](#23-menusaisonnier) | SaaS Subscription | €3K–€18K | Low |

---

## 1. ReceiptAI

> **AI-powered receipt scanner & tax prep tool for freelancers and solopreneurs**

### Problem
Freelancers lose thousands in unclaimed deductions each year because manual expense tracking is tedious. Accountants charge $200–$500/hr to sort through a shoebox of receipts. Existing apps (Expensify, Wave) are clunky and not built for solo operators.

### Solution
A mobile-first app where users snap a photo of any receipt. AI (OCR + LLM) extracts vendor, amount, date, and category instantly. A dashboard tracks spending by category, surfaces missed deductions, and exports a clean PDF/CSV at tax time.

### Revenue Model
| Tier | Price | Features |
|------|-------|----------|
| Free | $0/mo | 10 receipts/mo, basic dashboard |
| Pro | $9/mo | Unlimited receipts, tax export, AI suggestions |
| Business | $29/mo | Team accounts, accountant sharing, API |

**Target users:** 59M freelancers in the US alone. Even 0.1% = 59,000 users → $531K MRR at Pro.

### Tech Stack
- **Mobile:** React Native (iOS + Android from one codebase)
- **OCR:** Google Vision API or AWS Textract
- **AI categorization:** Claude API (claude-sonnet-4-6)
- **Backend:** Node.js + Supabase
- **Payments:** Stripe

### Go-to-Market
1. Reddit communities: r/freelance, r/smallbusiness, r/digitalnomad
2. ProductHunt launch
3. Partner with accountants — white-label or referral program
4. YouTube SEO: "how to track freelance expenses"

### Competitive Moat
- Faster onboarding than Expensify (no corporate approval needed)
- AI that learns your categories over time
- Tax-law-aware suggestions (e.g. "50% of meals are deductible")

### Figma Schematic
[View ReceiptAI Product Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/9942eb69-062b-45fc-9a51-45d53351dcde)

---

## 2. LocalLaunch

> **Done-for-you digital presence platform for brick-and-mortar local businesses**

### Problem
73% of local businesses (plumbers, salons, restaurants, gyms) have no usable website or are lost on Google. They can't afford a $3K website build and don't have time to learn Squarespace. They lose customers daily to competitors with better online presence.

### Solution
A platform where a local business owner fills out a 5-minute form (name, type, location, services, hours, photos). Within 60 seconds, AI generates a professional website, writes SEO-optimized content, sets up Google My Business, and activates an online booking system. Then it runs itself — the owner just logs in to see their monthly performance report.

### Revenue Model
| Tier | Price | What They Get |
|------|-------|---------------|
| Starter | $49/mo | AI website, GMB setup, booking system |
| Growth | $99/mo | + review management, social posts auto-generated |
| Pro | $199/mo | + local SEO campaigns, competitor tracking |

**Unit economics:** CAC ~$50 (Facebook ads targeting local biz owners), LTV ~$1,200 at $99/mo × 12mo. **LTV:CAC = 24x.**

### Tech Stack
- **Website generation:** Next.js templates + Claude API for copy
- **GMB integration:** Google My Business API
- **Booking:** Cal.com embed or Calendly API
- **SEO content:** Claude API with local keyword injection
- **Backend:** Supabase + Vercel

### Go-to-Market
1. Cold outreach to local business Facebook Groups ("I'll build your website for free for 30 days")
2. Partner with local business coaches and accountants (referral fee)
3. Google Ads targeting "get my business online" keywords
4. Franchise the model: hire local "reps" on commission to sign up businesses in their city

### Competitive Moat
- Faster than any agency (60 seconds vs weeks)
- Cheaper than any agency ($49 vs $3K+)
- Self-managing — owner does nothing after signup
- Network effects as reviews and bookings accumulate

### Figma Schematic
[View LocalLaunch Onboarding Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/f0a37187-a54c-442a-962d-e95f302d3ee9)

---

## 3. SkillBridge

> **Micro-mentorship marketplace — book a 30-minute paid session with a real expert**

### Problem
People pay $500 for online courses but never finish them. What they actually need is 30 minutes with someone who solved their exact problem. Existing options (MentorCruise, Clarity.fm) are either too expensive, too commitment-heavy, or too hard to find the right expert.

### Solution
A two-sided marketplace where experts list 30-minute sessions at any price ($25–$300). Learners search by skill, read reviews, and book instantly with a credit card. A built-in video call happens in-browser. After the call, both sides leave reviews. Experts get paid out automatically (85% to expert, 15% platform fee).

### Revenue Model
**15% commission on every session.**

| Metric | Conservative | Optimistic |
|--------|-------------|-----------|
| Monthly sessions | 2,000 | 20,000 |
| Avg session price | $75 | $100 |
| Platform revenue | $22,500 | $300,000 |

Additional revenue: featured expert placement ($29/mo), analytics dashboard for experts ($19/mo).

### Tech Stack
- **Frontend:** Next.js + Tailwind
- **Video:** Daily.co API or Whereby embed
- **Payments & payouts:** Stripe Connect
- **Search:** Algolia
- **Backend:** Supabase (auth, DB, storage)

### Go-to-Market
1. **Supply first:** Recruit 50 high-quality experts for free during beta (offer 100% payout for first 3 months)
2. **Demand follows:** Launch publicly once supply is solid
3. Twitter/X: target communities like #buildinpublic, #indiehackers
4. Partner with bootcamps — graduates need mentorship from working engineers

### Competitive Moat
- Lower friction than Clarity.fm (no phone calls, video-native)
- Faster booking than MentorCruise (no trial period, instant scheduling)
- Reviews create compounding trust for top experts
- Niche verticals: start with "software engineers helping bootcamp grads"

### Figma Schematic
[View SkillBridge Marketplace Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/b90c1cc5-8855-4592-9a76-f54fbca43aad)

---

---

## 4. AutoEntrepreneur.ai

> **AI dashboard pour les 4 millions d'auto-entrepreneurs en France**

### Problem
France has 4M+ registered auto-entrepreneurs (micro-entrepreneurs) who manage their business alone. The URSSAF portal is confusing, most don't know their exact charges sociales until it's too late, and missing a quarterly declaration triggers penalties. Existing accounting tools (QuickBooks, Pennylane) are overkill and too expensive for a one-person business earning €500–€3K/month.

### Solution
A dead-simple web app where an auto-entrepreneur enters their revenue each month. The app automatically tracks their CA against their legal plafond (€77K for services, €188K for commerce), calculates exactly how much they'll owe in cotisations sociales, and sends reminders before URSSAF deadlines. A built-in AI chat answers questions like "Puis-je déduire mon téléphone ?" in plain French with legal citations.

### Revenue Model
| Tier | Price | Features |
|------|-------|----------|
| Gratuit | €0/mo | 3-month history, basic CA tracker |
| Solo | €7/mo | Unlimited history, deadline alerts, charges calculator |
| Pro | €14/mo | AI advisor, declaration pre-fill PDF, accountant sharing |

**Target:** 4M auto-entrepreneurs in France. 0.1% at €7/mo = 4,000 users → **€28K MRR**. Startup cost: Claude API + Supabase free tier = ~€0 until 100+ users.

### Tech Stack
- **Frontend:** Next.js + Tailwind (deployed on Vercel — free tier)
- **Auth + DB:** Supabase (free tier covers first 500 users)
- **AI advisor:** Claude API (claude-sonnet-4-6)
- **Payments:** Stripe (no monthly fee, 1.5% + €0.25/transaction)
- **Notifications:** Resend (free up to 3K emails/mo)

### Go-to-Market (zero budget)
1. Post on r/france, r/AutoEntrepreneur, and forums like **Forum-Auto-Entrepreneur.fr**
2. TikTok/YouTube Shorts: "J'ai créé un outil pour ne jamais rater ma déclaration URSSAF"
3. Partenariat avec des influenceurs freelance francophones (David Legroux, etc.)
4. SEO long-tail : "calculer charges auto entrepreneur", "plafond micro entreprise 2026"

### Competitive Moat
- No existing tool does this specifically for auto-entrepreneurs in France
- URSSAF deadlines + plafond tracking is a genuine legal risk = strong retention
- French tax law updates become a moat (complex to maintain = hard to copy)
- AI in French with correct legal context is rare

### Figma Schematic
[View AutoEntrepreneur.ai Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/7a4cbfa9-5ec9-4dd4-9788-8ffc87376c68)

---

## 5. ContratIA

> **Analyse instantanée de vos contrats en français — bail, CDI, CGV, et plus**

### Problem
Every person in France signs contracts they don't fully understand: a 40-page bail d'habitation full of abusive clauses, a CDI with a non-compete buried on page 12, or e-commerce CGV that waive all warranty rights. Lawyers charge €150–€300/hr for a basic review. Most people just sign, then discover problems too late.

### Solution
Users paste or upload a contract (PDF or text). The AI reads it, produces a clear summary in plain French, assigns a risk score (1–10), highlights potentially abusive or non-standard clauses, and compares them against the relevant French law (loi Alur for leases, Code du travail for employment, etc.). The entire analysis takes under 30 seconds.

### Revenue Model
| Option | Price | Details |
|--------|-------|---------|
| Analyse à l'unité | €5–€9 | One contract, full report, exportable PDF |
| Abonnement Essentiel | €12/mo | 5 analyses/mo + history |
| Abonnement Pro | €24/mo | Unlimited analyses, priority processing, lawyer referral |

**Unit economics:** €0.10–€0.30 per analysis in Claude API costs → 95%+ gross margin on pay-per-use.

### Tech Stack
- **Frontend:** Next.js (Vercel free tier)
- **Document parsing:** pdf-parse (free npm library) + plain text input
- **AI analysis:** Claude API with a specialized French contract prompt
- **Payments:** Stripe one-time charges + subscriptions
- **Storage:** Supabase Storage (for uploaded contracts)

### Go-to-Market (zero budget)
1. Launch on **Product Hunt** with French community outreach
2. TikTok: "J'ai lu votre bail avec l'IA — voici les 3 clauses abusives"
3. Partner with French tenant associations (UNPI, CLCV) as a free tool for their members
4. SEO: "bail clause abusive", "comprendre son contrat de travail", "CGV consommateur droits"

### Competitive Moat
- No French-language contract AI exists at this price point
- Legal specificity (Alur, Code civil, RGPD) is hard to replicate for non-French teams
- Network of verified lawyer partners for upsell = strong differentiation
- RGPD compliance by design (contracts never stored without consent) = trust moat

### Figma Schematic
[View ContratIA Analysis Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/cdacd969-8b07-4df1-9b62-b7a1903c291a)

---

## 6. AssociatIA

> **La plateforme tout-en-un pour les associations loi 1901**

### Problem
France has **1.5 million associations loi 1901** — sports clubs, cultural groups, charities, parent committees — and 80% of them are managed by volunteers with zero budget. They struggle with: tracking members and their cotisations, generating legally compliant fiscal receipts (reçus fiscaux for 66% tax deduction), organizing general assemblies, and doing basic accounting. They use Excel, paper, or outdated €500/year software.

### Solution
A modern SaaS built specifically around French association law. One dashboard to manage members (import via CSV or invite by email), track paid dues and send automated reminders, generate certified reçus fiscaux in one click, run elections and AGO/AGE with digital minutes, and produce a simplified bilan comptable ready for the fisc.

### Revenue Model
| Tier | Price | For |
|------|-------|-----|
| Starter | €0/mo | Up to 30 members, basic tracking |
| Essentiel | €19/mo | Up to 200 members, reçus fiscaux, AGO tools |
| Pro | €39/mo | Unlimited members, multi-admin, comptabilité export, API |

**Target:** Even 2,000 associations at €19/mo = **€38K MRR**. The free tier drives viral growth — treasurers recommend it to other associations.

### Tech Stack
- **Frontend:** Next.js + Tailwind
- **Auth + DB + Storage:** Supabase
- **PDF generation:** react-pdf (reçus fiscaux, PV d'assemblée)
- **Email:** Resend (relances cotisations, convocations)
- **Payments:** Stripe
- **AI (optional v2):** Claude API to draft statuts, PV templates

### Go-to-Market (zero budget)
1. Reach out directly to federations (FFBB, clubs sportifs locaux) — one federation = hundreds of clubs
2. Partner with **Mairies** — they advise new associations and can recommend the tool
3. Facebook Groups: "Trésorier d'association", "Gestion association France" (100K+ members)
4. SEO: "logiciel gestion association gratuit", "reçu fiscal association modele"

### Competitive Moat
- French association law compliance built-in (a foreign competitor can't copy this easily)
- Reçus fiscaux automation is a massive admin pain solved in one click
- Free tier creates bottom-up adoption — no sales team needed
- Federations as distribution channel = low CAC at scale

### Figma Schematic
[View AssociatIA Management Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/54a56228-91cf-4520-9b06-448cfb257b82)

---

## 7. AideMax

> **Calculateur d'aides sociales — trouvez en 2 minutes toutes les aides auxquelles vous avez droit**

### Problem
France has 1,200+ national and local benefit programs (APL, RSA, prime d'activité, MaPrimeRénov, CEE, aide à la garde d'enfants, etc.). The average French household leaves €4,000/year unclaimed simply because they don't know they qualify. The official simulateurs (CAF, URSSAF, impots.gouv.fr) are siloed — you need to visit 8 different sites to get the full picture, and most require creating accounts before showing any results.

### Solution
A single 2-minute questionnaire (income, age, housing status, family situation, location) powers a calculation engine that cross-references every major benefit program. The user sees a ranked list of aids they qualify for, with estimated monthly amounts. A paid PDF report unlocks the complete application guide: exact documents to gather, where to send them, legal deadlines, and direct links to official portals.

### Revenue Model
| Option | Price | Details |
|--------|-------|---------|
| Simulation gratuite | €0 | Top 3 aides + estimated total |
| Rapport complet | €4.99 | All eligible aids, PDF, step-by-step guides, document checklist |
| Abonnement Suivi | €7/mo | Re-simulation on law changes, deadline alerts, unlimited reports |

**Unit economics:** Claude API cost per simulation ~€0.05 → 99% gross margin on the €4.99 report. The free tier acts as the funnel — anyone who sees €800/mo in unclaimed benefits will pay €5 for the full guide.

### Tech Stack
- **Frontend:** Next.js + Tailwind (Vercel free tier)
- **Data source:** data.gouv.fr open datasets + manually maintained benefit rules
- **Calculation engine:** Server-side JS rules + Claude API for eligibility edge cases
- **PDF export:** react-pdf
- **Payments:** Stripe one-time + subscriptions
- **Backend:** Supabase

### Go-to-Market (zero budget)
1. TikTok/Reels: "J'ai trouvé €400/mois d'aides que je touchais pas — voici comment"
2. Facebook Groups: "Maman solo France", "Jeunes actifs Paris", "RSA et insertion"
3. SEO: "aide logement étudiant", "prime activité simulation", "aides rénovation maison"
4. Partner with social workers (assistants sociaux) — they refer dozens of clients/week

### Competitive Moat
- One-stop-shop vs 8+ government silos is an instant win on UX
- Data updated with each Finance law (PLF) → recurring moat
- Personalized PDF report is genuinely hard to replicate with a free government tool
- Trust built via official data sources (data.gouv.fr) + RGPD compliance

### Figma Schematic
[View AideMax Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/e2d7a13c-e334-4d50-8983-35196b6d20fd)

---

## 8. DécoDPE

> **Décodeur de diagnostics immobiliers — comprenez votre DDT avant de signer**

### Problem
Every rental and property sale in France requires a Dossier de Diagnostic Technique (DDT): DPE, loi Carrez, amiante, plomb, termites, ERP (risques et pollutions), installation électrique/gaz. These documents total 40–80 pages of technical and legal jargon. 95% of renters and buyers sign without reading them. Yet a bad DPE can mean €200+/month in extra heating bills; a missed asbestos report can cause a health hazard; an incorrect surface measurement can legally void a lease.

### Solution
Upload the DDT as a PDF (or photograph the pages). The tool extracts every diagnostic section, runs an AI analysis on each, and returns a clean dashboard: energy class + estimated annual cost, health risk flags (amiante/plomb), legal validity check (loi Carrez surface), flood/earthquake zone risk, and a global risk score from 1–10. The full report is exportable as a PDF the user can keep or send to their lawyer.

### Revenue Model
| Tier | Price | For |
|------|-------|-----|
| Analyse particulier | €5 | One DDT, full dashboard, PDF report |
| Pack acheteur | €12 | Up to 5 DDT analyses (for visits) |
| Agent immobilier | €29/mo | Unlimited analyses, agency branding on reports, API |

**Unit economics:** ~€0.15 API cost per DDT analysis → 97% gross margin. Agents pay monthly — strong B2B recurring revenue.

### Tech Stack
- **Frontend:** Next.js + Tailwind (Vercel)
- **PDF parsing:** pdf-parse + Tesseract.js for scanned docs
- **AI analysis:** Claude API with specialized DDT prompt per section
- **PDF report generation:** react-pdf
- **Payments:** Stripe
- **Storage:** Supabase Storage (auto-delete after 30 days)

### Go-to-Market (zero budget)
1. Reddit/forums: r/immobilier_france, SeLoger forum, PAP forum
2. TikTok: "J'ai scanné mon DDT avec l'IA — le DPE était illégal"
3. Cold email to agents immobiliers independants (IAD, CapiFrance) — €29/mo is nothing vs. their liability
4. SEO: "comprendre diagnostic DPE", "DDT location explication", "classe énergie F charges"

### Competitive Moat
- No French tool explains DDT in plain language at this price
- Agents have real legal liability if they misrepresent diagnostics → strong B2B pull
- Scanned-doc support (Tesseract) covers the majority of real-world files that aren't clean PDFs
- RGPD compliance: documents auto-deleted after 30 days = trust differentiator

### Figma Schematic
[View DécoDPE Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/76ced214-5a7f-41f5-affd-0da7f6c68f38)

---

## 9. LeBonCoinIA

> **Optimisez vos annonces LeBonCoin avec l'IA — vendez plus vite, au meilleur prix**

### Problem
LeBonCoin is used by 28 million French people monthly. Yet most sellers write vague titles, underestimate their item's value, and receive lowball offers they can't counter. A "Samsung TV" listed for €80 might fetch €180 with the right title, description, and price positioning. Conversely, overpriced or badly described items sit for months. There is no tool today that helps individual sellers optimize their listings.

### Solution
The user describes their item (name, condition, a few details) and optionally uploads photos. The AI generates: an optimized title using LeBonCoin's search algorithm patterns, a compelling description in natural French, a suggested price range based on current market data, the best category and attributes to select, and a negotiation response template if buyers lowball. The final listing is ready to copy-paste in 60 seconds.

### Revenue Model
| Tier | Price | Features |
|------|-------|----------|
| Gratuit | €0 | 1 annonce/semaine, titre + description uniquement |
| Solo | €2/annonce | Full optimization: titre, description, prix, catégorie, template réponse |
| Boost | €9/mo | Annonces illimitées, historique, "best time to post" tips, prix dynamique |

**Unit economics:** Claude API cost ~€0.04/annonce → 98% gross margin on €2 plan.
**Viral loop:** A user who sells their bike for €160 instead of €80 tells everyone.

### Tech Stack
- **Frontend:** Next.js + Tailwind (Vercel free tier)
- **AI optimization:** Claude API (claude-sonnet-4-6) with LeBonCoin-specific prompting
- **Price benchmarking:** Scraped LBC price distributions (public data) stored in Supabase
- **Auth + DB:** Supabase
- **Payments:** Stripe

### Go-to-Market (zero budget)
1. TikTok/YouTube Shorts: "J'ai vendu mon canapé 3x plus cher grâce à l'IA"
2. Reddit: r/france, r/vinted, r/consommation — share the free tier
3. SEO: "rédiger annonce leboncoin", "prix vente occasion france", "optimiser annonce vente"
4. Referral program: get 3 free annonces for each friend who signs up

### Competitive Moat
- LeBonCoin is uniquely French — no global competitor will build this
- Price benchmarking database becomes more accurate with every user (data moat)
- Negotiation templates are a unique feature no other tool offers
- Free tier creates massive top-of-funnel with near-zero marginal cost

### Figma Schematic
[View LeBonCoinIA Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/6b26ce60-bece-43df-832a-62e1f6a69ab2)

---

## 10. LoyerCheck

> **Vérifiez en 30 secondes si votre loyer respecte l'encadrement des loyers**

### Problem
Paris, Lyon, Bordeaux, Montpellier et une dizaine d'autres villes appliquent l'encadrement des loyers depuis 2019–2022. Pourtant, une étude OLAP estime que **30–40% des logements parisiens sont loués au-dessus du loyer de référence majoré** — ce qui est illégal. Les locataires ne savent pas qu'ils sont surpayés, ne connaissent pas le loyer légal exact, et ne savent pas comment agir. Les propriétaires ne savent pas non plus s'ils sont en conformité.

### Solution
L'utilisateur entre l'adresse, le type de logement (meublé/non meublé), le nombre de pièces, la surface et la date du bail. En 30 secondes, LoyerCheck interroge les données officielles (DRIHL pour Paris, ADIL pour les autres villes), calcule le loyer de référence + majoration légale, et affiche si le loyer actuel est légal ou illégal. Si le loyer est trop élevé, un rapport PDF payant donne la lettre de mise en demeure prête à envoyer, le montant récupérable, et les contacts ADIL/Tribunal.

### Revenue Model
| Option | Price | Details |
|--------|-------|---------|
| Vérification gratuite | €0 | Résultat légal/illégal + montant du dépassement |
| Rapport complet | €4.99 | PDF : lettre de mise en demeure, montant récupérable sur 12 mois, guide recours ADIL |
| Propriétaire conforme | €2.99 | Certificat de conformité officieux + conseils révision annuelle |

**Unit economics:** Claude API cost ~€0.05/analyse → 99% gross margin. Un locataire qui apprend qu'il surpaye €120/mois paiera volontiers €5 pour le rapport.

### Tech Stack
- **Frontend:** Next.js + Tailwind (Vercel free tier)
- **Data sources:** DRIHL Open Data (Paris), ADIL datasets, data.gouv.fr (zones encadrées)
- **Geocoding:** Adresse.data.gouv.fr API (gratuit, officiel)
- **AI letter generation:** Claude API (claude-sonnet-4-6)
- **PDF:** react-pdf
- **Payments:** Stripe
- **Backend:** Supabase

### Go-to-Market (zero budget)
1. TikTok/Reels : "J'ai découvert que mon loyer parisien était illégal — voici comment vérifier"
2. Reddit/Forums : r/paris, r/france, SeLoger forum, PAP forum
3. Partenariat avec associations de locataires (CLCV, CNL, UNPI) — outil gratuit pour leurs membres
4. SEO : "encadrement des loyers paris vérifier", "loyer de référence majoration 2026", "loyer illégal recours"

### Competitive Moat
- Aucun outil grand public n'existe à ce prix point en France
- Les données officielles sont publiques mais inaccessibles aux non-techniciens → valeur réelle
- Génération automatique de la lettre de mise en demeure = action directe vs simple information
- Extension facile vers toutes nouvelles villes rejoignant l'encadrement (marché en expansion)

### Figma Schematic
[View LoyerCheck Compliance Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/e37c37d1-88a4-4c93-9526-de1a96920de0)

---

## 11. EtatDesLieux.ai

> **Générez un état des lieux professionnel avec l'IA — en 10 minutes, depuis votre téléphone**

### Problem
En France, 3 millions de locations changent de locataire chaque année. L'état des lieux d'entrée et de sortie est le document le plus litigieux de la relation bailleur/locataire : mal rédigé, il entraîne des conflits sur la caution qui peuvent aller jusqu'au tribunal. Les professionnels facturent €120–€200 pour un état des lieux. Les particuliers se débrouillent avec un formulaire Word imprimé et des photos floues sur WhatsApp — et perdent systématiquement au tribunal faute de preuves structurées.

### Solution
L'utilisateur crée un état des lieux pièce par pièce via son téléphone : il prend des photos de chaque élément (murs, sols, équipements, compteurs). L'IA décrit automatiquement l'état observé en termes juridiquement corrects (« traces d'usure normale », « rayure de 5 cm sur le parquet »). À la sortie, l'outil compare les photos entrée/sortie pièce par pièce et identifie les dégradations nouvelles. Le rapport PDF final est valable comme preuve légale, signable numériquement par les deux parties.

### Revenue Model
| Tier | Price | For |
|------|-------|-----|
| Etat des lieux simple | €4.99 | PDF complet, photos intégrées, signatures numériques |
| Pack locataire | €9.99 | Entrée + sortie, comparaison IA, rapport de dégradation |
| Propriétaire bailleur | €19/mo | États des lieux illimités, dashboard multi-biens, export comptable |

**Unit economics:** ~€0.10 API + ~€0.05 stockage = €0.15 coût → 97% gross margin sur le plan €4.99. **Marché total :** 3M de déménagements/an → même 0.05% = 1,500 états = **€7,500/mois** dès l'an 1.

### Tech Stack
- **Frontend:** Next.js + Tailwind (mobile-first)
- **AI description:** Claude API avec vision (claude-sonnet-4-6) — analyse photo et génère la description
- **Photo comparison:** Claude vision pour diff entrée/sortie
- **Signatures:** DocuSeal (open-source, auto-hébergeable) ou HelloSign API
- **PDF:** react-pdf avec photos intégrées
- **Storage:** Supabase Storage (auto-delete 30 jours après signature)
- **Payments:** Stripe

### Go-to-Market (zero budget)
1. Forums : SeLoger, PAP.fr, r/immobilier_france — présenter comme outil anti-litige
2. TikTok : "Voici pourquoi vous perdez TOUJOURS sur la caution — et comment l'éviter"
3. Partenariat avec agences immobilières indépendantes (IAD, CapiFrance) — option marque blanche
4. SEO : "état des lieux gratuit modele", "modèle état des lieux PDF", "litige caution locataire"

### Competitive Moat
- Vision IA qui génère la description automatiquement = 10x plus rapide que remplir un formulaire
- Comparaison photo entrée/sortie est unique sur le marché français
- Valeur légale du PDF structuré + signature numérique = vrai avantage face aux photos WhatsApp
- Propriétaires multi-biens = client récurrent fidèle (€19/mo × LTV 24 mois = €456 LTV)

### Figma Schematic
[View EtatDesLieux.ai Inspection Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/3f9f9c3f-aea3-4904-8026-b6fcfd20aeb1)

---

## 12. ImpotsSimple

> **Votre déclaration de revenus guidée par l'IA — trouvez toutes vos déductions en 15 minutes**

### Problem
40 millions de Français déclarent leurs revenus chaque mai sur impots.gouv.fr. 70% ne savent pas qu'ils laissent de l'argent sur la table : frais réels non déclarés, dons aux associations (66% de crédit d'impôt), frais de garde d'enfant, travaux MaPrimeRénov, déficit foncier, investissement Pinel... Les experts-comptables coûtent €150–€400 pour une déclaration simple. Les simulateurs gratuits (impots.gouv.fr) ne conseillent pas, ils calculent seulement.

### Solution
L'utilisateur répond à 8 questions de profil (situation familiale, type de revenus, logement, dépenses de l'année). L'IA identifie toutes les déductions applicables, explique chacune en français simple, et génère un guide case par case pour remplir sa déclaration sur impots.gouv.fr. Le tout sans jamais toucher les données fiscales réelles de l'utilisateur — juste un guide intelligent.

### Revenue Model
| Tier | Price | Features |
|------|-------|----------|
| Simulation gratuite | €0 | Top 3 déductions + estimation du gain |
| Guide complet | €9.99 | Toutes déductions, guide case par case, PDF récapitulatif |
| Vérification Pro | €14.99 | Guide complet + 1 question répondue par un fiscaliste partenaire |

**Timing :** campagne de déclaration = mai–juin en France = pic de trafic naturel de 40M de personnes. **SEO saisonnier** extrêmement puissant. Même 50,000 utilisateurs payants à €9.99 = **€500K sur 6 semaines.**

### Tech Stack
- **Frontend:** Next.js + Tailwind (Vercel)
- **AI:** Claude API — connaît le CGI (Code Général des Impôts) et les cases 2025/2026
- **PDF:** react-pdf
- **Payments:** Stripe
- **Backend:** Supabase (aucune donnée fiscale stockée — RGPD by design)

### Go-to-Market (zero budget)
1. SEO agressif dès janvier : "déductions impôts 2026", "frais réels ou abattement 10%", "case 7UF déclaration"
2. TikTok/YouTube en avril : "Les 5 déductions que 90% des Français oublient"
3. Partenariats avec influenceurs finance perso (Heu?reka, Graham Stephan FR, etc.)
4. Email marketing à la base utilisateurs AideMax (même profil démographique)

### Competitive Moat
- Timing annuel crée une audience captive de 40M de personnes chaque mai
- Guide case-par-case en français simple = UX imbattable vs impots.gouv.fr
- Fiscaliste partenaire en upsell = moat de confiance
- Pas de stockage de données fiscales = avantage RGPD majeur sur les concurrents

### Figma Schematic
[View ImpotsSimple Declaration Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/21992570-1bbf-41e6-97a9-b2fb336dfba8)

---

## 13. RecoursFacile

> **Générez en 3 minutes la lettre de recours parfaite contre n'importe quel service public**

### Problem
Chaque année, des millions de Français reçoivent des décisions injustes de la CAF, CPAM, Pôle Emploi, Fisc, Mairie, ou d'autres services publics : allocation coupée sans raison, remboursement refusé, amende contestable, permis de construire rejeté. Faire un recours est leur droit — mais 80% abandonnent parce qu'ils ne savent pas comment rédiger une lettre administrative formelle, quelle autorité saisir, ou dans quel délai agir. Les avocats en droit administratif coûtent €200–€400/hr pour des dossiers souvent gagnables seul.

### Solution
L'utilisateur sélectionne l'organisme adversaire et décrit son problème en langage courant. L'IA identifie le type de recours approprié (recours gracieux, recours hiérarchique, saisine du Médiateur de la République, Défenseur des Droits), la base légale, et le délai légal de réponse. Elle génère une lettre formelle en style administratif correct, avec références légales, prête à envoyer en recommandé.

### Revenue Model
| Option | Price | Details |
|--------|-------|---------|
| Diagnostic gratuit | €0 | Type de recours + autorité compétente + délai |
| Lettre complète | €3.99 | Lettre Word + PDF, adresse destinataire, conseils envoi recommandé |
| Pack suivi | €5.99 | Lettre initiale + lettre de relance (si pas de réponse en 2 mois) |

**Unit economics:** Claude API cost ~€0.08/lettre → 98% gross margin. **Volume naturel :** 100,000+ décisions administratives contestables par semaine en France.

### Tech Stack
- **Frontend:** Next.js + Tailwind (Vercel)
- **AI:** Claude API avec connaissance du Code des Relations entre le Public et l'Administration (CRPA)
- **Templates:** Base de données de recours types par organisme (CAF, CPAM, Pôle Emploi, Fisc)
- **Export:** .docx (docx npm) + react-pdf
- **Payments:** Stripe

### Go-to-Market (zero budget)
1. Facebook Groups : "Droits sociaux France", "CAF problèmes solutions", "Impôts réclamation" (200K+ membres combinés)
2. TikTok : "La CAF t'a coupé tes aides ? Voici exactement quoi envoyer"
3. SEO : "lettre recours CAF refus", "contester décision CPAM", "recours gracieux modèle"
4. Partenariat avec AideMax (idea #7) — cross-sell naturel : trouver ses aides → les contester si refusées

### Competitive Moat
- Aucun service digital n'existe pour la rédaction de recours administratifs en France
- Base de données de recours types par organisme est une barrière à l'entrée après quelques mois
- Le cross-sell avec AideMax crée un écosystème (find benefits → claim benefits → appeal denials)
- RGPD by design : aucune donnée personnelle stockée après génération

### Figma Schematic
[View RecoursFacile Appeal Generator Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/c95c4440-2ed3-4604-876b-625a4e8cc272)

---

## 14. PermisIA

> **Préparez le Code de la Route avec une IA qui s'adapte à vos points faibles**

### Problem
1.4 million de Français passent le Code de la Route chaque année. Le taux de réussite est de seulement 58% — ce qui signifie que 590,000 personnes échouent et doivent repayer €30 d'inscription + mois supplémentaires d'auto-école. Les applications existantes (iPermis, En Voiture Simone) utilisent des QCM statiques sans adaptation. Aucune ne dit à l'élève *pourquoi* il se trompe, ni ne priorise ses vrais points faibles. L'auto-école coûte €1,200–€2,000 en France — les élèves sont très motivés à réduire le nombre d'essais.

### Solution
Un test de placement initial identifie les thèmes faibles de l'élève (priorité à droite, distances de freinage, alcool/drogues, signalisation...). Un algorithme d'apprentissage adaptatif (type Anki mais pour le Code) présente chaque jour 10 questions ciblées sur ses lacunes. Pour chaque mauvaise réponse, l'IA explique la règle de droit concernée avec un exemple visuel et 3 questions similaires pour ancrer la notion. Un simulateur d'examen final prédit le résultat avant le vrai passage.

### Revenue Model
| Tier | Price | Features |
|------|-------|----------|
| Gratuit | €0 | Test de placement + 3 jours d'accès complet |
| Mensuel | €9.99/mo | Apprentissage adaptatif illimité, simulateurs, explications IA |
| Pack examen | €19.99 | Accès 3 mois + 5 simulations d'examen complètes + rapport de préparation |

**Market size:** 1.4M candidats/an × €9.99 × même 0.5% = **€70K MRR** en régime de croisière. Coût d'acquisition quasi nul via SEO et bouche-à-oreille dans les auto-écoles.

### Tech Stack
- **Frontend:** Next.js + Tailwind (PWA — fonctionne sur mobile sans appli)
- **Question bank:** Base de données officielle ONISR (Code de la Route officiel) + questions générées par IA
- **Adaptive algorithm:** Algorithme SM-2 (type Anki) côté serveur
- **AI explanations:** Claude API — génère l'explication pédagogique à chaque erreur
- **Auth + DB:** Supabase
- **Payments:** Stripe

### Go-to-Market (zero budget)
1. SEO massif : "code de la route gratuit 2026", "entrainement code de la route en ligne", "test code de la route adaptatif"
2. TikTok : "J'ai réussi le Code du premier coup avec cette méthode — pas iPermis"
3. Partenariats avec auto-écoles indépendantes — outil recommandé aux élèves (commission de 20%)
4. Discord/Reddit : r/france, communautés jeunes conducteurs

### Competitive Moat
- L'adaptation en temps réel aux points faibles est absente de tous les concurrents
- Explications IA en français pédagogique (pas juste "bonne réponse / mauvaise réponse")
- Algorithme de répétition espacée = meilleure mémorisation à long terme = meilleur taux de réussite = bouche-à-oreille
- Base officielle ONISR + questions IA = contenu plus exhaustif que les apps statiques

### Figma Schematic
[View PermisIA Exam Prep Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/75aeb08e-6c93-4bd0-bcc2-65e20117fb57)

---

## 15. VintedPro

> **Optimisez vos annonces Vinted avec l'IA — vendez plus vite, au meilleur prix**

### Problem
Vinted compte 23 millions d'utilisateurs en France. Pourtant, la plupart des vendeurs sous-estiment la valeur de leurs vêtements : une veste Zara "en bon état" listée €8 peut se vendre €22 avec le bon titre, la bonne description et le bon prix selon la marque, la taille et la saison. Les acheteurs font systématiquement des offres basses aux annonces mal rédigées. Contrairement à LeBonCoin (idée #9), Vinted est 100% mode — les règles de valorisation (marques, matières, coupes tendance, saison) sont radicalement différentes et demandent une IA spécialisée mode.

### Solution
L'utilisateur décrit son article (marque, état, taille, matière, quelques mots) et optionnellement uploade des photos. L'IA génère : un titre optimisé avec les mots-clés de recherche Vinted (marque + style + taille + état), une description convaincante en français naturel, un prix recommandé basé sur les transactions réelles du marché Vinted pour cet article, la meilleure heure/jour pour publier, et un template de réponse aux offres basses.

### Revenue Model
| Tier | Price | Features |
|------|-------|----------|
| Gratuit | €0 | 1 analyse/semaine, titre + description uniquement |
| Solo | €2/annonce | Analyse complète : titre, description, prix, timing, template réponse |
| Boost | €9/mo | Annonces illimitées, suivi prix marché, alertes tendances saisonnières |

**Unit economics:** Claude API cost ~€0.04/annonce → 98% gross margin. **Boucle virale :** un vendeur qui passe de €8 à €22 pour un pull parle à ses amis.

### Tech Stack
- **Frontend:** Next.js + Tailwind (Vercel free tier)
- **AI optimization:** Claude API (claude-sonnet-4-6) avec prompt mode/Vinted spécialisé
- **Price benchmarking:** Données marché Vinted scrapées (public) stockées en Supabase
- **Auth + DB:** Supabase
- **Payments:** Stripe

### Go-to-Market (zero budget)
1. TikTok/Reels : "J'ai vendu mon manteau 3x plus cher grâce à l'IA — sans changer les photos"
2. Instagram/Pinterest : communautés mode seconde main, thrifting, capsule wardrobe
3. Reddit : r/france, r/vinted, groupes Facebook "Vinted astuces France" (300K+ membres)
4. Parrainage : 3 analyses gratuites pour chaque ami inscrit

### Competitive Moat
- Vinted est 100% français/européen — aucun outil global ne s'y spécialisera
- Base de prix marché par marque/taille/état devient un data moat après 3 mois
- Spécialisation mode (saison, tendances, marques premium vs fast fashion) absente de LeBonCoinIA
- Boucle virale extrêmement forte : chaque vente réussie génère un témoignage partageable

### Figma Schematic
[View VintedPro AI Listing Optimizer Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/8234caf3-b646-4099-90a8-72223c7ac8dd)

---

## 16. RénovSimple

> **Simulez la rentabilité de vos travaux de rénovation énergétique — MaPrimeRénov, CEE et ROI en 5 minutes**

### Problem
La France compte **5 millions de logements classés F ou G** (passoires énergétiques). La loi Climat impose leur interdiction progressive à la location : DPE G interdit depuis 2025, DPE F interdit en 2028, DPE E en 2034. Les propriétaires sont sous pression mais ne savent pas par où commencer : quels travaux prioriser ? Combien de MaPrimeRénov exactement ? Quel est le vrai ROI en économies de chauffage ? Les artisans gonflent les devis, les dossiers sont complexes. DécoDPE (#8) lit le diagnostic — RénovSimple dit quoi faire ensuite.

### Solution
L'utilisateur entre la classe DPE actuelle, la surface du logement, le type de chauffage, et son budget. L'IA calcule le meilleur scénario de travaux (isolation combles/murs, pompe à chaleur, double vitrage) pour atteindre la classe D ou C, avec pour chaque option : le montant exact de MaPrimeRénov, les Certificats d'Économies d'Énergie (CEE) disponibles, les aides régionales (Île-de-France, Occitanie, etc.), le ROI en économies annuelles, et les artisans RGE certifiés dans le département.

### Revenue Model
| Tier | Price | For |
|------|-------|-----|
| Simulation gratuite | €0 | Classe DPE cible atteignable + estimation totale des aides |
| Rapport complet | €9.99 | PDF : scénarios travaux, montants aides par organisme, guide dossier, contacts RGE |
| Agent/Notaire | €29/mo | API illimitée, rapports en marque blanche, intégration dans l'annonce immobilière |

**Unit economics:** ~€0.15 API + €0.05 génération PDF = €0.20 coût → 98% gross margin sur €9.99. **Urgence légale :** 5M de propriétaires ont une deadline légale — le trafic SEO est structurellement croissant jusqu'en 2034.

### Tech Stack
- **Frontend:** Next.js + Tailwind (Vercel)
- **Data aides:** API MaPrimeRénov (ANAH), barèmes CEE publics, data.gouv.fr aides régionales
- **AI simulation:** Claude API — calcule scénarios, explique en langage clair
- **Artisans RGE:** Annuaire RGE officiel ADEME (open data)
- **PDF:** react-pdf
- **Payments:** Stripe
- **Backend:** Supabase

### Go-to-Market (zero budget)
1. SEO urgent : "DPE G interdit location 2025", "MaPrimeRénov montant simulateur", "travaux isolation aides 2026"
2. TikTok/YouTube : "Mon propriétaire a 3 ans pour rénover ou ne peut plus louer — voici exactement ce qu'il doit faire"
3. Cold email aux agents immobiliers (IAD, CapiFrance) — l'outil valorise leur conseil client
4. Partenariats avec DécoDPE (#8) — cross-sell naturel : lire le DPE → simuler la rénovation

### Competitive Moat
- L'interdiction légale progressive crée une urgence non négociable pour 5M de propriétaires
- Agrégation MaPrimeRénov + CEE + aides régionales en une seule simulation n'existe pas
- Artisans RGE locaux intégrés = valeur actionnable, pas juste informationnelle
- Synergie avec DécoDPE (#8) crée un écosystème complet "diagnostic → action → financement"

### Figma Schematic
[View RénovSimple Renovation ROI Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/83a5257e-e134-48cb-b5a0-b4e85ec8d750)

---

## 17. HéritageFacile

> **Calculez vos droits de succession et optimisez vos donations — sans notaire, en 10 minutes**

### Problem
La France enregistre **600 000 successions par an**. Pour une succession simple (maison + épargne entre enfants), un notaire facture €1 500–€4 000 minimum — et souvent, la majorité du travail se résume à calculer les droits, appliquer les abattements légaux, et conseiller sur l'assurance-vie. La plupart des familles ne savent pas : que chaque parent peut donner €100 000 par enfant tous les 15 ans sans impôts, que l'assurance-vie est exonérée jusqu'à €152 000 par bénéficiaire, ou qu'un testament mal rédigé peut diviser l'abattement. Des familles paient des milliers d'euros d'impôts évitables.

### Solution
Un questionnaire de profil (liens de parenté, patrimoine immobilier, épargne, assurances-vie, dons déjà effectués, testament existant). L'IA calcule pour chaque héritier : les droits de succession bruts, les abattements applicables (€100K enfant, €80K conjoint survivant, etc.), le montant net à payer. Elle propose ensuite des stratégies de donation-partage pour réduire légalement la facture fiscale future, avec une simulation "si vous donnez €X maintenant vs dans 15 ans".

### Revenue Model
| Option | Price | Details |
|--------|-------|---------|
| Estimation gratuite | €0 | Droits par héritier + abattements identifiés |
| Rapport complet | €9.99 | PDF : simulation détaillée, stratégies de donation, calendrier optimal |
| Pack famille | €19.99 | Rapport + mise en relation notaire partenaire (honoraires négociés) |

**Unit economics:** Claude API ~€0.10/simulation → 99% gross margin sur €9.99. **Marché :** même 0.05% des 600K successions annuelles = 300 rapports/mois → **€3K MRR dès le lancement.**

### Tech Stack
- **Frontend:** Next.js + Tailwind (Vercel)
- **AI + droit:** Claude API avec connaissance du Code Civil, CGI (barèmes droits de succession 2026), régimes matrimoniaux
- **PDF:** react-pdf
- **Payments:** Stripe (one-time + pack)
- **Backend:** Supabase (aucune donnée patrimoniale stockée — RGPD by design)

### Go-to-Market (zero budget)
1. SEO : "simulateur droits de succession", "abattement succession enfant 2026", "donation 100000 euros impôts"
2. YouTube/TikTok : "Voici pourquoi 80% des familles françaises paient trop d'impôts à la succession"
3. Facebook : groupes "Investissement immobilier France", "Retraite et patrimoine", "Gestion patrimoine senior"
4. Partenariats avec ImpotsSimple (#12) — même profil utilisateur (soucieux de l'optimisation fiscale)

### Competitive Moat
- Le notaire est cher mais souvent peu pédagogique — l'IA explique chaque règle en français clair
- La simulation "donation maintenant vs plus tard" est unique et crée une valeur immédiate
- Base de barèmes CGI mise à jour annuellement = maintenance moat (les concurrents doivent aussi la maintenir)
- Partenariat notaires = upsell naturel sans SAV pour l'outil

### Figma Schematic
[View HéritageFacile Succession Guide Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/b7a0ada9-dc85-4c07-bbe9-bf6e96a81df5)

---

## 18. CVFrançais.ai

> **Générez en 3 minutes un CV et une lettre de motivation parfaits — adaptés au style français et à l'offre ciblée**

### Problem
La France a **3.5 millions de demandeurs d'emploi** actifs et des millions de salariés en recherche discrète. Le marché du travail français a ses codes très spécifiques : CV chronologique inversé d'une page, lettre de motivation obligatoire (inconnue dans la plupart des pays), ton formel attendu dans les grands groupes, pas de photo (RGPD mais usage encore ambigu), phrases d'accroche soignées. Les outils globaux (Resume.io, Canva CV) génèrent des formats anglophones inadaptés. Et rédiger une lettre de motivation convaincante pour chaque offre prend 1–2 heures à quelqu'un qui n'est pas à l'aise à l'écrit.

### Solution
L'utilisateur colle son profil (depuis LinkedIn ou texte libre) et l'offre d'emploi ciblée. Il sélectionne le type d'entreprise (startup, grand groupe, PME, administration). L'IA génère un CV d'une page au format français correct avec des verbes d'action et des chiffres pour quantifier les réalisations, et une lettre de motivation adaptée au ton de l'entreprise — le tout en moins de 3 minutes. L'utilisateur peut demander des variantes jusqu'à être satisfait avant de payer.

### Revenue Model
| Tier | Price | Features |
|------|-------|----------|
| Aperçu gratuit | €0 | Voir les 5 premières lignes du CV + ouverture de la lettre |
| Dossier complet | €4.99 | CV PDF + Word + Lettre de motivation PDF + Word |
| Abonnement | €14.99/mo | Dossiers illimités + suivi candidatures + relances IA |

**Timing :** les pics de recherche d'emploi en France sont janvier–février (après fêtes) et septembre–octobre (rentrée). SEO saisonnier puissant. **Unit economics :** Claude API ~€0.08/dossier → 98% gross margin.

### Tech Stack
- **Frontend:** Next.js + Tailwind (Vercel)
- **AI generation:** Claude API (claude-sonnet-4-6) — maîtrise les codes du CV français
- **Export:** docx (npm officepegen) + react-pdf
- **Auth + DB:** Supabase
- **Payments:** Stripe

### Go-to-Market (zero budget)
1. SEO : "modèle CV français gratuit", "lettre de motivation exemple 2026", "CV reconversion professionnelle"
2. TikTok/LinkedIn : "Mon CV généré par IA a décroché 4 entretiens en 2 semaines — voici le prompt"
3. Pôle Emploi/France Travail : partenariats avec conseillers qui orientent les demandeurs vers des outils
4. Reddit : r/france, r/emploi_france, r/reconversion

### Competitive Moat
- Seul outil 100% français (codes culturels, langue, format légal)
- Adaptation au type d'entreprise est absente de tous les générateurs globaux
- La lettre de motivation est une barrière uniquement française — aucun outil global ne la priorise
- Suivi candidatures → relances IA = fonctionnalité de rétention forte sur l'abonnement

### Figma Schematic
[View CVFrançais.ai Job Application Generator Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/69461fc4-b89a-4267-adcd-57c75493cb7a)

---

## 19. VTCPro

> **Le dashboard tout-en-un pour les 40 000 chauffeurs VTC auto-entrepreneurs en France**

### Problem
La France compte **40 000 chauffeurs VTC** (Uber, Bolt, Heetch, etc.) enregistrés comme auto-entrepreneurs. Ils travaillent sur 2–4 plateformes simultanément, reçoivent leurs revenus en vrac depuis des apps différentes, et ont du mal à : savoir exactement combien ils gagnent réellement (après commission plateforme), surveiller leur CA vs le plafond auto-entrepreneur (€77K), calculer leurs cotisations URSSAF trimestrielles, déduire les frais réels (carburant, entretien, LLD, péages), et générer les factures clients si nécessaire. En pratique ils découvrent leur facture URSSAF le jour de l'échéance — et parfois n'ont pas mis de côté.

### Solution
Un dashboard unique qui agrège les données de toutes les plateformes (import CSV ou connexion API là où disponible). Chaque course est automatiquement comptabilisée. L'outil affiche en temps réel : le CA du mois vs le plafond AE, la provision à mettre de côté pour les cotisations du prochain trimestre, les frais déductibles saisis, la marge nette réelle. Une alerte prévient 30 jours avant chaque échéance URSSAF. En fin d'année, un bilan comptable simplifié est exportable pour le comptable ou la déclaration annuelle.

### Revenue Model
| Tier | Price | Features |
|------|-------|----------|
| Gratuit | €0 | 3 mois d'historique, résumé CA mensuel |
| Pro | €9.99/mo | Tout illimité, alertes URSSAF, export comptable, provisions automatiques |
| Expert | €19.99/mo | + Déclaration URSSAF pré-remplie, gestion TVA franchise, bilan annuel PDF |

**Unit economics:** Supabase + Claude API ~€0.50/utilisateur/mois → 95% gross margin à partir de 200 users. **Marché captif :** 40K chauffeurs, tous auto-entrepreneurs, tous avec le même problème fiscal.

### Tech Stack
- **Frontend:** Next.js + Tailwind (PWA — optimisé mobile, le chauffeur est sur son téléphone)
- **Import données:** CSV Uber/Bolt/Heetch + parsing IA des relevés PDF
- **Calculs:** Moteur de règles AE (cotisations, plafonds, TVA franchise) + Claude API pour edge cases
- **Alertes:** Resend (emails) + notifications push PWA
- **PDF comptable:** react-pdf
- **Auth + DB:** Supabase
- **Payments:** Stripe

### Go-to-Market (zero budget)
1. Facebook Groups : "Chauffeurs VTC France", "Uber France chauffeurs", "VTC indépendants" (50K+ membres combinés)
2. TikTok/YouTube : "Voici pourquoi tu rates probablement €200/mois en ne traçant pas tes frais VTC"
3. Forums : VTC-info.fr, discussion.uber.com — présenter comme outil anti-mauvaise surprise URSSAF
4. Bouche-à-oreille : les chauffeurs se connaissent entre eux (files d'attente aéroports, groupes WhatsApp)

### Competitive Moat
- AutoEntrepreneur.ai (#4) est généraliste — VTCPro est hyperspécialisé VTC (frais kilométriques, déduction LLD, multi-plateformes)
- Agrégation multi-plateformes (Uber + Bolt + Heetch) est un problème non résolu que les chauffeurs mentionnent constamment
- La communauté VTC est très soudée — un early adopter satisfait = 10 nouveaux clients organiques
- Après 6 mois, les données agrégées permettent des benchmarks sectoriels uniques (revenu moyen/heure par ville)

### Figma Schematic
[View VTCPro Driver Dashboard Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/e3c5e7e6-7eea-4555-824e-61c540719dc8)

---

## 20. AlloDevis

> **Générez un devis professionnel en 2 minutes — l'outil des artisans qui détestent la paperasse**

### Problem
La France compte **600 000 artisans** (plombiers, électriciens, peintres, maçons, menuisiers) dont la grande majorité sont des TPE ou auto-entrepreneurs. La plupart rédigent leurs devis à la main, sur un carnet, ou par message WhatsApp. Résultat : devis non conformes (manque mentions légales obligatoires), image non professionnelle, délai de validation allongé, et zéro traçabilité des impayés. Les logiciels existants (Batappli, Dolibarr) coûtent €30–€100/mois et ont une courbe d'apprentissage de plusieurs heures — un plombier entre deux chantiers n'a ni le temps ni l'envie.

### Solution
L'artisan décrit sa prestation en langage courant sur son téléphone ("remplacement chauffe-eau électrique 300L, fourniture + pose, Paris 11e"). L'IA génère en 30 secondes un devis PDF professionnel avec toutes les mentions légales obligatoires (n° SIRET, TVA, garantie décennale, délai validité). Le client reçoit un lien SMS/email, signe numériquement, et la signature déclenche automatiquement la création de la facture correspondante.

### Revenue Model
| Tier | Price | Features |
|------|-------|----------|
| Gratuit | €0 | 3 devis/mois, PDF basique, envoi email |
| Pro | €9/mo | Devis illimités, signature numérique, conversion facture auto, relances impayés |
| Expert | €19/mo | + Logo/couleurs personnalisés, conditions générales sur mesure, export comptable |

**Unit economics:** Claude API ~€0.05/devis → 99% gross margin. **Marché :** 600K artisans × 0.1% au plan Pro = 600 clients → **€5 400 MRR**. Un artisan qui fait 3 devis/jour = €3 600 de CA mensuel géré — il paiera €9 sans hésiter.

### Tech Stack
- **Frontend:** Next.js + Tailwind (PWA — fonctionne sur mobile, sans installation)
- **AI generation:** Claude API (claude-sonnet-4-6) — connaît les mentions légales CAPEB/FFB
- **Signatures:** DocuSeal (open-source, auto-hébergeable) ou Yousign API
- **PDF:** react-pdf
- **Auth + DB:** Supabase
- **Payments:** Stripe

### Go-to-Market (zero budget)
1. Facebook Groups : "Plombiers France", "Électriciens indépendants", "Artisans du BTP" (200K+ membres combinés)
2. TikTok/YouTube : "J'ai montré à un plombier comment créer un devis pro en 2 minutes avec son téléphone"
3. Partenariats avec fournisseurs matériaux (Point.P, Leroy Merlin Pro) — ils ont accès à des milliers d'artisans
4. SEO : "logiciel devis artisan gratuit", "devis plombier modèle légal", "application facture artisan mobile"

### Competitive Moat
- Mobile-first + 30 secondes vs 30 minutes avec un logiciel traditionnel
- Mentions légales CAPEB/FFB intégrées → zéro risque de litige client sur la conformité
- La signature numérique intégrée supprime la friction principale du processus de vente artisan
- Un artisan satisfait = tout son réseau : les artisans se recommandent entre eux via WhatsApp

### Figma Schematic
[View AlloDevis Artisan Quote Generator Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/fb3adc08-77cd-432e-988e-981f85be7884)

---

## 21. GîteBoost

> **L'outil de revenue management pour les gîtes et chambres d'hôtes — réduisez vos commissions Airbnb de moitié**

### Problem
La France compte **60 000 gîtes ruraux** et **40 000 chambres d'hôtes** — le plus grand parc de tourisme rural d'Europe. La plupart passent par Airbnb, Booking.com, ou Gîtes de France et paient **15–20% de commission par réservation**. Sur une propriété à €80/nuit avec 60% d'occupation, ça représente €3 500–€5 000 perdus par an. Pourtant, ces propriétaires n'ont aucun outil pour : optimiser leurs tarifs selon la saison et la demande locale, générer des réservations directes (zéro commission), ou automatiser la communication avec les voyageurs (confirmations, instructions arrivée, avis post-séjour). Ils utilisent un agenda papier et répondent aux messages à toute heure.

### Solution
En 10 minutes, le propriétaire crée son mini-site de réservation directe (URL personnalisée, photos, calendrier, paiement Stripe). L'IA analyse son historique de réservations et propose des tarifs dynamiques par période (saint-valentin, vacances scolaires, événements locaux). Un système de messagerie automatique gère confirmations, rappels J-3, guide d'arrivée, et demande d'avis post-séjour — sans que le propriétaire touche son téléphone.

### Revenue Model
| Tier | Price | Features |
|------|-------|----------|
| Starter | €0/mo | Mini-site réservation directe, calendrier, 1% de commission sur réservations directes |
| Pro | €29/mo | Prix dynamiques IA, messages automatiques, sync calendrier Airbnb/Booking, 0% commission |
| Business | €49/mo | + Multi-propriétés, analytics avancés, channel manager (màj tarifaire sur toutes les plateformes) |

**Unit economics:** Coût infra ~€2/mois/user → 93% gross margin. **Pitch économique :** le plan à €29 se rembourse si l'IA évite une seule nuit vide par mois (€80) OU génère une réservation directe (économise €12–€16 de commission). **ROI en 48h pour le propriétaire.**

### Tech Stack
- **Frontend:** Next.js + Tailwind (mini-site public généré par propriétaire + dashboard privé)
- **Calendrier:** ical sync (Airbnb/Booking.com exportent en .ics)
- **AI pricing:** Claude API — analyse saisonnalité, événements locaux, taux occupation
- **Messages automatiques:** Resend (emails) + Twilio (SMS) — triggers sur événements calendrier
- **Paiements réservations:** Stripe (le propriétaire reçoit directement, 0% commission GîteBoost sur plan Pro)
- **Auth + DB:** Supabase
- **Abonnements:** Stripe

### Go-to-Market (zero budget)
1. Facebook Groups : "Propriétaires Airbnb France", "Gîtes et chambres d'hôtes", "Tourisme rural France" (150K+ membres)
2. TikTok/YouTube : "J'ai économisé €4 200 en un an en arrêtant de passer uniquement par Airbnb — voici comment"
3. Partenariats avec Gîtes de France, Clévacances — ces fédérations cherchent des outils pour leurs adhérents
4. SEO : "logiciel gestion gite rural", "réservation directe chambres hôtes", "prix dynamique location saisonnière"

### Competitive Moat
- Le plan freemium avec mini-site gratuit (1% commission) crée une adoption massive sans risque
- La sync .ics avec Airbnb/Booking évite la double réservation — problème numéro 1 des propriétaires
- Messages automatiques en français (spécificités françaises : horaires check-in légaux, taxe de séjour) = différenciation vs outils anglophones
- Réseau de propriétaires ruraux très soudé = bouche-à-oreille puissant dans les villages et fédérations

### Figma Schematic
[View GîteBoost Revenue Management Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/a7842420-9d5e-4c8e-b641-e4b77951a09b)

---

## 22. CoPro.ai

> **Comprenez et contestez vos charges de copropriété — l'IA contre les syndics opaques**

### Problem
La France compte **10 millions d'appartements en copropriété**, soit 30% du parc résidentiel. Chaque trimestre, les copropriétaires reçoivent un appel de fonds ou un relevé de charges qu'ils signent sans vraiment comprendre. Pourtant : une étude UFC-Que Choisir estime que **30% des charges de copropriété contiennent des erreurs ou surfacturations**. Un copropriétaire parisien lambda paie €3 000–€8 000/an de charges sans savoir si c'est normal, ce que couvre exactement chaque poste, ni si le syndic respecte la loi (délais de convocation, devis obligatoires, fonds de travaux loi Alur). Contester nécessite de connaître la loi du 10 juillet 1965 — ce que 99% des copropriétaires ne font pas.

### Solution
Le copropriétaire uploade son appel de fonds ou son relevé de charges annuel (PDF ou photo). L'IA décompose chaque poste en langage clair, compare les montants aux moyennes nationales par type d'immeuble et taille de lot (données ANIL/ADIL), vérifie la conformité avec la loi du 10 juillet 1965 et le décret de 2019, et signale les anomalies. Si une anomalie est détectée (poste gonflé, absence de devis obligatoire, fonds de travaux manquant), l'outil génère une lettre de contestation formelle au syndic, avec base légale.

### Revenue Model
| Option | Price | Details |
|--------|-------|---------|
| Analyse gratuite | €0 | Décomposition des postes + score de conformité global |
| Rapport complet | €5.99 | PDF : comparaison nationale, anomalies détaillées, base légale par poste |
| Pack contestation | €9.99 | Rapport + lettre de contestation au syndic + guide procédure tribunal |
| Abonnement Copropriétaire | €7/mo | Analyses illimitées, alertes convocations AG, historique sur 3 ans |

**Unit economics:** Claude API ~€0.08/analyse → 99% gross margin. **Marché :** 10M copropriétaires × 0.05% = 5 000 rapports/mois → **€30K MRR**. La colère contre son syndic est un des moteurs de conversion les plus puissants qui soient.

### Tech Stack
- **Frontend:** Next.js + Tailwind (Vercel)
- **PDF parsing:** pdf-parse + Tesseract.js (les relevés sont souvent scannés)
- **AI analysis:** Claude API — connaît la loi du 10 juillet 1965, décret 2019, barèmes ANIL
- **Données comparatives:** Baromètre charges ADIL/ANIL (open data) + données agrégées anonymisées
- **PDF export:** react-pdf
- **Payments:** Stripe
- **Backend:** Supabase

### Go-to-Market (zero budget)
1. Facebook Groups : "Copropriétaires France", "Problèmes syndic France", "Droits des copropriétaires" (100K+ membres)
2. TikTok/YouTube : "Mon syndic me facturait €400/an en trop — voici comment je l'ai découvert"
3. SEO : "charges copropriété trop élevées recours", "lettre contestation syndic", "appel de fonds illégal"
4. Partenariats avec UFC-Que Choisir et associations de copropriétaires (ARC, UNARC) — outil recommandé à leurs membres

### Competitive Moat
- Aucun outil grand public ne permet d'analyser ses charges avec base légale en France
- Les données comparatives ANIL agrégées deviennent un avantage exclusif après 6 mois
- La colère contre les syndics est structurelle (marché en croissance permanente)
- L'abonnement mensuel crée un revenu récurrent fort : un copropriétaire reste client aussi longtemps qu'il est en copropriété (LTV 5–10 ans)

### Figma Schematic
[View CoPro.ai Charges Analyzer Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/9c2013ce-f70d-4881-aa56-a89731e765c2)

---

## 23. MenuSaisonnier

> **Planifiez vos repas de la semaine avec des produits de saison et de votre région — zéro gaspillage, liste de courses automatique**

### Problem
72% des Français déclarent vouloir manger plus local et saisonnier, mais seulement 30% le font régulièrement — par manque de temps et de connaissances. Ils ne savent pas exactement ce qui pousse en avril dans leur région, comment structurer une semaine de repas autour de ces produits, ni quoi acheter au marché vs au supermarché. Les applications de recettes existantes (Marmiton, Cookcooking) proposent des plats en vrac sans tenir compte de la saisonnalité locale, ce qui génère frustration (légumes absents en magasin) et gaspillage (acheter trop sans plan cohérent). La France perd **30 kg de nourriture par personne et par an** — la moitié dans les foyers.

### Solution
L'utilisateur indique sa région, le nombre de personnes, ses préférences alimentaires (végétarien, sans gluten, budget serré) et deux contraintes de temps (cuisiner < 20 min en semaine, OK pour mijoter le week-end). L'IA génère un menu complet pour la semaine — 5 dîners + 5 déjeuners — 100% basé sur les produits actuellement de saison dans la région. Une liste de courses est automatiquement divisée en deux : produits à acheter au **marché local** (légumes, fruits, viande/poisson de saison) et produits à compléter au supermarché. L'utilisateur peut remplacer un repas en un clic, et l'IA garde la cohérence saisonnière.

### Revenue Model
| Tier | Price | Features |
|------|-------|----------|
| Gratuit | €0 | 1 menu semaine/mois, liste de courses basique |
| Mensuel | €3.99/mo | Menus illimités, préférences sauvegardées, liste de courses divisée marché/supermarché |
| Famille | €5.99/mo | + Jusqu'à 6 personnes, planning mois entier, intégration app de courses (Bring!) |

**Unit economics:** Claude API ~€0.08/menu → 98% gross margin. **Marché :** 30M de foyers français. Même 0.03% au plan Mensuel = 9 000 abonnés → **€36K MRR**. Le prix de 2 cafés par mois pour ne plus jamais se demander "qu'est-ce qu'on mange cette semaine?"

### Tech Stack
- **Frontend:** Next.js + Tailwind (PWA — sauvegardable sur écran d'accueil mobile)
- **Données saisonnalité:** Base de données calendrier saisonnier par région (92 départements) — maintenable manuellement, enrichissable via open data INRAE
- **AI menu generation:** Claude API — génère des menus cohérents, équilibrés, contraintes respectées
- **Shopping list:** Algorithme de consolidation des ingrédients + classification marché vs supermarché
- **Auth + DB:** Supabase
- **Payments:** Stripe

### Go-to-Market (zero budget)
1. Instagram/Pinterest : communautés "zéro déchet", "manger local France", "famille écoresponsable" (1M+ abonnés combinés)
2. TikTok : "J'ai arrêté le gaspillage alimentaire avec cette méthode — menu de la semaine en 30 secondes"
3. Partenariats avec Réseaux AMAP (Associations pour le Maintien d'une Agriculture Paysanne) — 1 700 AMAP en France
4. SEO : "menu semaine produits saison", "que manger de saison en avril", "recette légumes saison région"

### Competitive Moat
- Saisonnalité par région française est un avantage de localisation que les apps globales (Yummly, Mealime) ne peuvent pas répliquer
- L'intégration AMAP crée un partenariat de distribution naturel avec 1 700 points de contact
- La liste de courses divisée marché/supermarché est une fonctionnalité unique sur le marché français
- Le calendrier saisonnier par département devient un asset SEO fort (longue traîne par mois + région)

### Figma Schematic
[View MenuSaisonnier Seasonal Meal Planner Flow on FigJam](https://www.figma.com/online-whiteboard/create-diagram/b3eccc9b-d056-44ee-b365-d6e73cebebfc)

---

## How to Evaluate an Idea

Before building, validate with this checklist:

- [ ] **Pain is real:** Can you find 10 people who have this exact problem today?
- [ ] **Willingness to pay:** Have 3 people pre-paid or put a card down?
- [ ] **You can reach them:** Is there a clear, affordable channel to acquire users?
- [ ] **Defensible over time:** Does it get harder to copy as you grow?
- [ ] **You can build v1 in 4–6 weeks:** Scope is tight enough to ship fast.

---

*Last updated: 2026-04-20 — Ideas 20–23 added (France-specific, ultra-low-budget: AlloDevis, GîteBoost, CoPro.ai, MenuSaisonnier)*
