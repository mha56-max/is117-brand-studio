# Brand Studio decisions

This is the durable agreement between the learner and agent. Keep it concise and update it only with agreed choices or actual evidence. `Not chosen yet` is a valid status. Persona cards are hypotheses unless supported by real research.

[LEARNING.md](LEARNING.md) holds the short, reviewable record of learner explanations and help received. Keep the brand decisions and implementation evidence here; link rather than duplicate them.

## Current stage

- Stage: Baseline ready to try; brand decisions pending.
- Current feature: `BRAND-001` — first branded storefront and live style guide.
- Status: Pending learner scope agreement.
- Next small decision: Confirm the first slice after trying the neutral storefront.

## Product boundary

The product is the same white T-shirt throughout the comparison. The baseline offers a size selector and temporary demo bag. No real orders, payment, accounts, or persistence. Keep product facts stable between directions; do not add unsupported claims about materials, manufacturing, sustainability, fit, delivery, scarcity, reviews, or sales.

## Audience hypotheses

The primary need guides the page. Give the secondary card one contrasting need to check that same page; keep both cards brief.

| Tiny card                             | Primary audience          | Secondary audience        |
| ------------------------------------- | ------------------------- | ------------------------- |
| Person in a concrete situation        | Not chosen yet            | Not chosen yet            |
| Goal or meaning they seek             | Not chosen yet            | Not chosen yet            |
| Concern before choosing               | Not chosen yet            | Not chosen yet            |
| What the page should help them decide | Not chosen yet            | Not chosen yet            |
| Evidence or assumption                | Assumption; not validated | Assumption; not validated |

## Early brand brief

| Decision                                 | Agreement      |
| ---------------------------------------- | -------------- |
| Brand name                               | Not chosen yet |
| One-sentence promise                     | Not chosen yet |
| Primary archetype: the brand's character | Not chosen yet |
| Three voice traits                       | Not chosen yet |
| One example line in this voice           | Not chosen yet |
| Learner's predicted audience effect      | Not chosen yet |

## Visual decision

Compare two small hero previews before building the whole page. Hold the product, headline, supporting copy, and action identical. Use specific real design references and annotate visual choices, intended effect, and risk.

A simple original SVG wordmark is enough. Show small-size and one-color presentations; they may use the same asset when it works.

| Item                                              | Agreement or evidence |
| ------------------------------------------------- | --------------------- |
| Shared headline / support / action                | Not chosen yet        |
| Modernist preview, reference, and annotations     | Not chosen yet        |
| Postmodernist preview, reference, and annotations | Not chosen yet        |
| Chosen direction and reason                       | Not chosen yet        |
| Original SVG logo                                 | Not chosen yet        |
| Monochrome and small-size variants                | Not chosen yet        |
| Logo review at actual use size                    | Not checked yet       |
| Shared palette, typography, spacing, and assets   | Not chosen yet        |

## Ethical persuasion

Choose two applications that help the visitor make a voluntary, informed decision. Record their real implementation and mechanism rather than a principle name alone. Required size selection or validation alone does not establish consistency. Do not invent social proof, scarcity, authority, or product facts.

| Principle      | Actual copy or interaction | Visitor benefit / factual support |
| -------------- | -------------------------- | --------------------------------- |
| Not chosen yet | Not chosen yet             | Not chosen yet                    |
| Not chosen yet | Not chosen yet             | Not chosen yet                    |

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

| Spec ID   | Files           | Issue / PR      | Actual checks and observations            |
| --------- | --------------- | --------------- | ----------------------------------------- |
| BRAND-001 | Not changed yet | Not created yet | Not run yet; learner observations pending |

## Later

No follow-up is selected. After keeping `BRAND-001`, choose one next cycle: perhaps a brand story, a supported fit guide, or richer demo-bag behavior. Agree its scope and add one new spec ID at that time.

## My decisions (Michelle Ayala)

- Primary audience: A college student who wants one good basic white tee that looks clean and holds its shape.
- Secondary audience (to check the page): A gift buyer unsure of size who wants reassurance before buying.
- Brand name: Clean Cut
- Promise: A plain white tee, made simple to choose.
- Archetype: Sage. It fits because the brand should feel grounded, so a student can trust a plain white tee without hype.
- Voice: Calm, clear, honest.
- Audience cards are hypotheses, not research.
- Help received: Claude suggested the audiences, name, promise, and voice traits. The archetype choice and the "grounded" reason are mine.

## Hero direction

- Chosen: Preview A, modernist.
- References: Swiss/International Typographic Style (Josef Muller-Brockmann) and the Bauhaus idea that form follows function. The postmodernist option I compared it with was inspired by the Memphis Group (Ettore Sotsass, 1981).
- Why: I chose Preview A because its calm, uncluttered layout feels comfortable to look at, like a hug for a busy student, so she can choose a size without feeling overwhelmed.
- Help received: Claude explained both styles, drew the two previews, and wrote this sentence from my words. The choice of A and the "comfy like a hug" idea are mine.

## Logo

- Chosen: boxed CC monogram next to the Clean Cut wordmark, one color, saved as public/logo.svg.
- Why: The plain box and two letters feel calm and tidy like the Sage voice, and the box alone still works at small size.
- Help received: Claude drew three options and wrote the file and this sentence. I picked option 3 and approved the wording.

## Persuasion (two truthful applications of Cialdini)

- Commitment and consistency: the shopper chooses a size first, then adds it to the bag, so one small step leads to the next. No false claims.
- Liking: a calm, honest, friendly voice (Choose your size. Add it to the bag.) so a busy student feels at ease. No invented reviews, scarcity, or product facts.
- Help received: Claude suggested both principles. I approved them.

## My browser checks (Nov 12)

- Mouse: I chose M and clicked Add to demo bag, and the Demo bag count went up.
- Keyboard: I tabbed to the size buttons and the add button, saw an outline on each one, and Enter added the shirt.
- Narrow window: the page stayed readable, the buttons still worked, and it did not scroll sideways.
- Something I noticed: the lime-green banner and the lime "Who this is for" block are leftovers from the starter. They do not match the calm black-and-white look I chose, so I want to change them.
- Prepared checks: npm run test:e2e passed all 10 tests, including adding a size to the bag, the keyboard test, and the narrow-screen tests.
- Help received: Claude wrote the page edits and walked me through these checks. I ran them and reported what I saw.
