# Brand Studio decisions

This is the durable agreement between the learner and agent. Keep it concise and update it only with agreed choices or actual evidence. `Not chosen yet` is a valid status. Persona cards are hypotheses unless supported by real research.

[LEARNING.md](LEARNING.md) holds the short, reviewable record of learner explanations and help received. Keep the brand decisions and implementation evidence here; link rather than duplicate them.

## Current stage

- Stage: Modernist storefront and live guide implemented; learner decisions and observations recorded; LEARNING.md reviewed; full checks pass; commit and PR pending.
- Current feature: `BRAND-001` — first branded storefront and live style guide.
- Status: Scope agreed; issue [#1](https://github.com/mishkhurshid/is-117-brand-studio/issues/1) created; working branch `feature/brand-001`.
- Next small decision: Review the BRAND-001 pull request, then decide whether to keep and merge it into `main`.

## Product boundary

The product is the same white T-shirt throughout the comparison. The baseline offers a size selector and temporary demo bag. No real orders, payment, accounts, or persistence. Keep product facts stable between directions; do not add unsupported claims about materials, manufacturing, sustainability, fit, delivery, scarcity, reviews, or sales.

## Audience hypotheses

The primary need guides the page. Give the secondary card one contrasting need to check that same page; keep both cards brief.

| Tiny card                             | Primary audience                                                                                                                   | Secondary audience                                                                                                         |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| Person in a concrete situation        | College students and young adults around 18–25; wearing it to class, coffee shops, casual outings, and everyday activities         | Young working professionals around 23–30; wearing it in a casual work setting with trousers or a blazer, or when going out |
| Goal or meaning they seek             | Simple, timeless clothing that can be styled in different ways while still looking put together                                    | Simple, classy clothing to dress up or down; a polished, professional appearance with comfort                              |
| Concern before choosing               | Whether it is versatile enough for different outfits, looks put together without being too formal, and how it fits before purchase | Not chosen yet                                                                                                             |
| What the page should help them decide | Whether the shirt suits different casual outfits and what fit information they need before deciding to buy                         | Not chosen yet                                                                                                             |
| Evidence or assumption                | Learner's design hypothesis; not validated                                                                                         | Learner's design hypothesis; not validated                                                                                 |

## Early brand brief

| Decision                                 | Agreement                                                                                                                                                                                                                                                                                         |
| ---------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Brand name                               | STAR; learner changed from AUREOLE because STAR is simpler, easier to remember, and fits the intended minimalist and classy aesthetic.                                                                                                                                                            |
| One-sentence promise                     | "STAR creates timeless everyday essentials that make looking effortlessly put together feel simple."                                                                                                                                                                                              |
| Primary archetype: the brand's character | Ruler; learner wants STAR to feel elegant, sophisticated, and timeless, with simple, minimal designs that help customers feel confident and put together.                                                                                                                                         |
| Three voice traits                       | Elegant, confident, and simple; learner wants sophisticated but not overly formal or complicated writing, with clear, minimal copy that makes the clothing feel timeless and stylish.                                                                                                             |
| One example line in this voice           | "Effortlessly Simple. Always Elegant."; learner chose this to express simple, timeless clothing that helps people feel confident and put together without trying too hard.                                                                                                                        |
| Learner's predicted audience effect      | Learner predicts that an elegant, confident, simple voice will help college students and young adults judge whether the shirt fits their personal style, see its versatility across outfits, and feel they can look put together without trying too hard. This remains an unvalidated hypothesis. |

## Visual decision

Compare two small hero previews before building the whole page. Hold the product, headline, supporting copy, and action identical. Use specific real design references and annotate visual choices, intended effect, and risk.

Keep the annotated comparison as project evidence; do not display its reference notes or design explanations on the customer-facing storefront.

A simple original SVG wordmark is enough. Show small-size and one-color presentations; they may use the same asset when it works.

| Item                                              | Agreement or evidence                                                                                                                                                                                                                                                                                                    |
| ------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Shared headline / support / action                | Headline: "Effortlessly Simple. Always Elegant." Supporting copy: "A timeless everyday essential that brings simplicity and elegance to everyday outfits." Action: "Explore the Collection"; scroll to the T-shirt product section so visitors can learn more and choose a size.                                         |
| Modernist preview, reference, and annotations     | [Preview page](public/explorations/index.html): Herbert Bayer, "Poster for Kandinsky exhibition honoring the artist's 60th birthday," 1926, Harvard Art Museums, BR48.107. The exploration uses a measured grid, direct type hierarchy, and red rules; intended effect is faster scanning; risk is a stiff, formal feel. |
| Postmodernist preview, reference, and annotations | [Preview page](public/explorations/index.html): Paula Scher, _The Diva is Dismissed_, 1994, The Museum of Modern Art. The exploration uses offset color planes, a diagonal band, and serif display type; intended effect is expressive styling; risk is competition with the copy.                                       |
| Chosen direction and reason                       | Modernist; learner prefers the clean structure, neutral colors, and simple typography because they fit STAR's minimalist, elegant, and classy identity. Keep references and design explanations on the comparison page, not the customer-facing storefront.                                                              |
| Original SVG logo                                 | Learner approved [STAR wordmark](public/assets/star-wordmark.svg), saying its simple, clean look matches the minimalist, classy aesthetic they want.                                                                                                                                                                     |
| Monochrome and small-size variants                | Same one-color SVG is used in the header and live guide; learner approved the current wordmark.                                                                                                                                                                                                                          |
| Logo review at actual use size                    | Learner approved the current wordmark as simple and clean; no trademark clearance is claimed.                                                                                                                                                                                                                            |
| Shared palette, typography, spacing, and assets   | Implemented through shared tokens in `public/styles.css`; storefront and live guide use the same wordmark asset and type/color tokens. Agent reviewed both at 1440px and 375px without horizontal overflow.                                                                                                              |

## Ethical persuasion

Choose two applications that help the visitor make a voluntary, informed decision. Record their real implementation and mechanism rather than a principle name alone. Required size selection or validation alone does not establish consistency. Do not invent social proof, scarcity, authority, or product facts.

| Principle                | Actual copy or interaction                                                                                                                | Visitor benefit / factual support                                                                                                                                                                                    |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Reciprocity              | Complimentary styling guide shown without size selection or demo-bag addition: three outfit suggestions for class, coffee, and going out. | Gives visitors useful ways to style the white T-shirt before deciding; no signup, size selection, or purchase is required.                                                                                           |
| Commitment / consistency | Optional Relaxed, Layered, or Polished preference; choosing one immediately displays a matching outfit suggestion.                        | The visitor voluntarily identifies a style direction, then receives a relevant next suggestion. Learner says this helps visitors find outfits matching personal style; the choice does not affect size or bag state. |

## BRAND-001 — first branded storefront and live style guide

**Scope:** turn the working neutral storefront into the chosen brand's first coherent page. Keep the existing size selector and demo bag usable. Do not add checkout or all future features.

Keep when:

- The learner has chosen the audience hypotheses, brief, visual direction, and logo; the page visibly expresses those choices.
- Two annotated hero directions compare modernist/postmodernist thinking with the same content and real source links.
- The selected SVG logo works at small size and in one color; the presentations may share one asset.
- The storefront and live style guide share CSS variables, typography, components, and assets; they do not drift into separate identities.
- Two ethical persuasion applications are visible and their claims are supportable.
- Prepared checks pass, the agent has reviewed the slice and discussed one actual check, and the learner has reported a browser impression plus keyboard/mobile observations.
- The issue, branch, commit, and PR explain this feature in the learner's repository; agreed decisions and actual evidence are saved here. The learner has approved keeping and merging the change, and the merge into `main` is verified. Publishing is a separate choice.

## Evidence

Write a short result and link only evidence that exists. A passing browser check is evidence for its assertions, not customer research or proof of full accessibility.

| Spec ID   | Files                                                                                                                                                                                                                                  | Issue / PR                                                                                           | Actual checks and observations                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| --------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BRAND-001 | [Storefront](public/index.html), [live guide](public/styleguide.html), [STAR wordmark](public/assets/star-wordmark.svg), [comparison evidence](public/explorations/index.html), [preview styles](public/explorations/explorations.css) | [Issue #1](https://github.com/mishkhurshid/is-117-brand-studio/issues/1); branch `feature/brand-001` | `npm run check` passed: formatting, lint, 7 server tests, and 13 Chromium browser tests. Reciprocity test verifies the three styling ideas are present while the bag stays at 0. Consistency test selects Layered, asserts its matching suggestion appears, and confirms the bag remains at 0. Learner explains that this would catch a wrong suggestion or unintended bag addition. Agent inspected storefront, guide, and studio at 1440px and 375px; the learner separately reported the two earlier previews readable at desktop and narrow widths, described the current storefront as "very simple and easy readable," confirmed keyboard navigation felt straightforward, and said the narrow view's background/colors are simple/basic without too much spacing. Those are learner-reported impressions. |

## T-shirt Research — November 9, 2026

**Research status:** Initial desk research and design interpretation, not customer interviews or proof of sales. The competitor notes below describe broad merchandising approaches; specific page layouts, inventory, and prices can change. The links are sources to revisit during review.

### Three clothing-site comparisons

**Method:** Desk review of three specific white/basic T-shirt product pages on November 9, 2026. Observations below refer to features shown on the linked pages at review time, not claims about STAR's own product. Prices and page details may change.

| Source / review date | Specific observation | What it suggests for STAR |
| --- | --- | --- |
| [UNIQLO — Crew Neck T-Shirt](https://www.uniqlo.com/us/en/products/E424873-000/00?colorDisplayCode=31&nodeeplink=true&sizeDisplayCode=006), Nov. 9, 2026 | The product page shows selectable sizes, a size guide with body measurements, customer reviews, and styling photos with model heights and sizes. It also explains the shirt's fabric and fit. | Clear size information and real outfit examples help shoppers evaluate a basic tee. STAR already has a size selector and styling ideas; a verified size chart is a possible future improvement, but measurements must not be invented. |
| [Everlane — The Box-Cut Tee in Essential Cotton](https://assets.everlane.com/products/f-t-ctn-orgn-box-wnt), Nov. 9, 2026 | The page names the cut, labels the fit as relaxed, includes a model's height and worn size, and offers a size guide that distinguishes relaxed from slim and oversized fits. The description focuses on the silhouette, including cropped length and short sleeves. | Even a simple tee benefits from concrete fit explanations. STAR should explain the intended styling clearly, but should not claim a specific cut or fabric until product specifications are established. |
| [COS — Clean Cut T-Shirt, White](https://www.cos.com/en-us/women/womenswear/tshirts/regular/product/clean-cut-t-shirt-white-1325526001), Nov. 9, 2026 | The product page offers a size guide, specific garment details, and a styling suggestion pairing the white tee with tailored clothing or denim. It presents a basic item as something that can be dressed up or down. | STAR can use polished yet relatable outfit suggestions to support its minimalist-elegant positioning, while keeping the demo product's unverified materials and fit out of its claims. |

**Comparison takeaway:** UNIQLO makes everyday purchasing decisions easier with sizing, reviews, and styling context; Everlane gives explicit fit-language; COS connects a plain white tee with more polished styling. STAR can combine easy navigation and styling inspiration now, while leaving detailed sizing and fabric claims for when reliable product data exists.

### Two possible positions

- **Position A — Everyday basic:** An easy white T-shirt for routine wear, with practical and casual styling. Advantage: immediately approachable. Risk: could feel interchangeable with many basics brands.
- **Position B — Minimalist elegance (chosen):** A simple white T-shirt presented as a versatile, polished wardrobe piece. Advantage: fits STAR's existing elegant, confident, simple voice and modernist visual direction. Risk: may feel too formal or expensive for students if the wording is overly luxurious.

**Choice:** Position B, with approachable language and styling ideas for everyday situations. This is a proposed brand position, not a validated market finding.

### Two short persona hypotheses

1. **Primary — college student / young adult (about 18–25):** Wants one easy top that can work for class, coffee, and going out; worries about whether it will look polished and fit their style. **Assumption:** outfit examples will help them judge versatility.
2. **Secondary — early-career professional (about 23–30):** Wants a simple top that can be dressed up with a blazer or trousers; worries about whether it feels appropriate for a casual workday. **Assumption:** a polished styling example will help them picture that use.

**Chosen audience:** College students and young adults 18–25. The professional persona remains a secondary hypothesis. Neither persona has been confirmed through interviews or analytics.

### Look, character, and honest persuasion

- **Look:** Modernist structure, generous whitespace, neutral colors, simple typography, and the existing one-color STAR wordmark.
- **Character:** Ruler archetype expressed as elegant, confident, and simple — not exclusive or intimidating.
- **Honest persuasion:** Offer free outfit ideas before asking visitors to select a size or add the demo item to a bag (reciprocity). Let visitors optionally choose Relaxed, Layered, or Polished to see a matching suggestion (commitment/consistency). Do not invent scarcity, customer reviews, sustainability credentials, materials, fit measurements, or checkout capability.
- **Open question:** Do actual students find the polished styling appealing, or would they prefer more casual imagery? Ask a classmate to check whether the intended audience is obvious from the homepage.

### Peer-review record

- **Review given:** Reviewed Clara's Off Hours project and filed four specific GitHub issues: [#7](https://github.com/cf344/is117-brand-studio/issues/7), [#8](https://github.com/cf344/is117-brand-studio/issues/8), [#9](https://github.com/cf344/is117-brand-studio/issues/9), and [#10](https://github.com/cf344/is117-brand-studio/issues/10).
- **Review received:** Awaiting Clara's feedback issues on STAR. Record each incoming issue, response (implement, investigate, defer, or decline), and any evidence of a change here once available.
- **Current decision:** Keep the existing minimalist-elegant direction for now; revisit after peer feedback.

## Later

No follow-up is selected. After keeping `BRAND-001`, choose one next cycle: perhaps a brand story, a supported fit guide, or richer demo-bag behavior. Agree its scope and add one new spec ID at that time.
