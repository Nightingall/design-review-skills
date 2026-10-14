---
name: dieter-rams-review
description: A product-judgement design review skill based on Dieter Rams' ten principles of good design. Pairs with the ui-craft-review skill: where ui-craft-review interrogates *whether the execution respects the craft*, this skill interrogates *whether the design respects the user*. Use when the user asks for a "design review", "Rams review", "does this deserve to exist", "is this honest", "is there too much here", when deciding whether to build or cut a feature on design grounds, when a screen feels bloated or gimmicky, or when evaluating a product/feature/screen at the concept level before polishing it. Also use when comparing two product directions on purpose and restraint grounds.
---

# Dieter Rams Design Review

## The Principles

In the late 1970s, Rams grew troubled by "an impenetrable confusion of forms, colours and noises" and asked himself whether his own work was good design. His answer became ten principles — written for radios and shelving, but adopted wholesale by digital product design (Jony Ive credited them as the starting point for Apple's design language) because they interrogate judgement, not medium.

Where the ui-craft-review skill asks *is it built with care?*, this skill asks *should this exist, and does it serve the user?*. Not every principle bites equally on every review — focus on the four or five that matter most for what's being reviewed.

### 1. Good design is innovative

Rams: "The possibilities for innovation are not, by any means, exhausted. Technological development is always offering new opportunities for innovative design."

Innovation means the design does something genuinely better because the technology now allows it — not novelty for its own sake. A feature that exists because a competitor shipped it, or because the tech is fashionable (AI chat bolted onto everything), fails this principle even if it's well built. Real innovation is usually quiet: a flow with one fewer step, a decision the user no longer has to make. *In digital product: what can this do that was impossible or painful before? If the answer is "nothing, but it looks current", that's fashion, not innovation.*

### 2. Good design makes a product useful

Rams: "A product is bought to be used. It has to satisfy certain criteria, not only functional, but also psychological and aesthetic."

Usefulness is the licence for everything else. Every element on the screen should advance the job the user came to do; anything that merely advances the roadmap, the brand, or the metrics dashboard is clutter wearing a lanyard. Note Rams includes *psychological* usefulness — reassurance, confidence, and orientation are real utility. *In digital product: name the user's job in one sentence. Does every element on this screen serve it? What is here for the business but disguised as being for the user?*

### 3. Good design is aesthetic

Rams: "The aesthetic quality of a product is integral to its usefulness because products we use every day affect our person and our well-being."

Beauty is not decoration on top of function — it is part of function, because people live inside these screens for hours. But the aesthetic argument only holds for well-executed things; Rams is explicit that only quality earns the right to be called beautiful. This principle asks whether the design cares about the user's daily experience, not whether it's trendy. (How well the aesthetic is executed is ui-craft-review's territory.) *In digital product: would you enjoy being in this interface for an hour a day? Does it treat the user's attention as something valuable?*

### 4. Good design is understandable

Rams: "It clarifies the product's structure. Better still, it can make the product talk. At best, it is self-explanatory."

The product should explain itself. If it needs a tooltip tour, an onboarding carousel, or a help doc to be operated, the design has outsourced its job to documentation. Structure should be legible: what this screen is, what can be done here, what will happen next. The best test is a first-time user with no introduction. *In digital product: could someone who has never seen this screen say what it does and take the primary action without help? Where does the interface rely on labels to compensate for unclear structure?*

### 5. Good design is unobtrusive

Rams: "Products fulfilling a purpose are like tools. They are neither decorative objects nor works of art."

The product is a tool; the user's content, task, and goals are the subject. Design that demands admiration — splash screens, gratuitous animation, interfaces that perform their own cleverness — is competing with the user for the stage. Restraint here is what leaves room for the user's own expression and content. *In digital product: is the interface the frame or the painting? What here exists to be noticed rather than to be used?*

### 6. Good design is honest

Rams: "It does not make a product more innovative, powerful or valuable than it really is."

The design must not manipulate. Dark patterns are the digital-native violation: fake urgency, confirm-shaming, buried unsubscribe flows, "free" trials engineered to be forgotten, AI features promising intelligence they don't have. Honesty also covers quieter lies: empty-state marketing that oversells, progress bars disconnected from progress, badges engineered to fabricate urgency. *In digital product: does this screen ever try to get the user to do something they wouldn't choose with full information? Does it promise more than the product delivers?*

### 7. Good design is long-lasting

Rams: "It avoids being fashionable and therefore never appears antiquated."

Fashion has a shelf life; utility doesn't. A design built on this season's visual trend (glassmorphism, gradient meshes, whatever replaces them) will look dated in three years and demand a redesign the user never asked for. Long-lasting digital design also means stable mental models — layouts and flows users can invest learning in without the rug being pulled each quarter. *In digital product: which choices here will look embarrassing in five years? Is this design worth the user's investment in learning it?*

### 8. Good design is thorough down to the last detail

Rams: "Nothing must be arbitrary or left to chance. Care and accuracy in the design process show respect towards the user."

For Rams this is an ethical principle: thoroughness is *respect*. At the product level it means the whole journey is designed, not just the happy path on the demo screen — the empty state, the error state, the offline state, the cancellation flow, the account deletion, the edge of the funnel where no one is watching. A product that is polished where it sells and careless where it retains has failed this principle. (Pixel-level thoroughness — states, spacing, motion timing — is ui-craft-review's half of this principle.) *In digital product: find the least glamorous flow in this product — deletion, errors, refunds. Was it designed with the same care as the home screen?*

### 9. Good design is environmentally-friendly

Rams: "Design makes an important contribution to the preservation of the environment."

The digital translation: respect for finite resources — the user's battery, bandwidth, storage, device lifespan, and above all their *attention*. A 10MB JavaScript bundle, a video autoplaying under the fold, an app that demands engagement it doesn't deserve, notification spam — these pollute the user's environment. In a native app the costs are binary size and bundled media, notification cadence, background refresh, and permission prompts asked before they're earned. Frugality with resources is a design decision, not an infrastructure afterthought. *In digital product: what does this cost the user beyond money — battery, data, interruptions, attention? Is each cost buying them something they value?*

### 10. Good design is as little design as possible

Rams: "Less, but better — because it concentrates on the essential aspects."

The summary principle, and the sharpest knife in a review. Every feature, option, setting, and element must justify its existence; the burden of proof is on inclusion, not omission. "Less, but better" is not minimalism as an aesthetic — it is concentration on the essential so the product isn't burdened with the non-essential. The hardest and most valuable output of a Rams review is usually a list of things to *remove*. *In digital product: if you had to cut 30% of this screen, what would go? Why is it still here?*

## When To Use This Skill

Trigger when:
- The user asks for a design review, product design critique, or "Rams review"
- The user is deciding whether a feature or element should exist at all
- A screen or product feels bloated, gimmicky, or dishonest and the user wants to know why
- The user is comparing two product directions on purpose/restraint grounds
- A concept or spec needs a design-judgement pass before anyone polishes pixels

Do not use when:
- The question is about pixel-level execution — typography, grid, colour, motion, states. That's the ui-craft-review skill
- The user wants new UI generated from scratch — that's a UI-generation skill such as frontend-design
- The question is purely commercial or strategic with no design-judgement component

The two reviews compose: run this skill first (should it exist? does it serve?), then ui-craft-review (is it built with care?). A screen can pass Rams and fail craft, or pass craft and fail Rams — the second failure is worse.

## Workflow

### Phase 1: Understand the product intent

1. Identify what's being reviewed: a whole product, a feature, a flow, a single screen, or a change (diff/PR). For a change, review what was added against the screen it landed on — "did this earn its place?" is a different question from "does this screen work?". If no surface is named, review the screen or feature most recently discussed in the conversation; failing that, the UI changes in the current diff.
2. Name the user's job in one sentence — what did they come here to do?
3. Look at the thing, not a description of it: a design file → screenshot it through the design tool's MCP if one is connected (Figma, Paper); an app screen → simulator or emulator screenshot; a web page → browser tools; code or a spec → read enough to understand what exists and why.
4. Weight the principles for the surface being reviewed — these are the ones that usually bite:
   - **Whole product / app**: 10 (as little as possible), 7 (long-lasting), 8 (beyond the happy path), 9 (attention and resources)
   - **New feature or build-vs-cut decision**: 1 (innovative), 2 (useful), 10; add 6 (honest) if it touches monetisation
   - **Single screen**: 2, 4 (understandable), 5 (unobtrusive), 10
   - **Persuasion surfaces** (onboarding, paywall, permission prompts, notifications): 6, 2, 4 — honesty findings here are non-negotiable
   - **Unglamorous flows** (settings, deletion, errors, cancel, refunds): 8, 4, 6
   - **Two directions compared**: see the variant below Phase 3

### Phase 2: Apply the principles

Walk through the ten principles. For each one that clearly bites on this surface, provide:

- **Verdict**: Pass / Tension / Fail
- **Observation**: A specific statement of what's there and who it serves
- **Recommendation**: The smallest change that would resolve it — noting that for this skill, the recommendation is often *removal*

Scoring (shared with ui-craft-review):
- **Pass**: The design satisfies this principle
- **Tension**: Partial — there's a specific conflict worth naming
- **Fail**: The design actively violates the principle

Skip principles that don't bite. Be ruthless about relevance; an over-long review is itself a failure of "less, but better".

### Phase 3: Synthesise

1. **Headline verdict** — one sentence on whether this design respects the user
2. **What's already working** — two or three specific things; vague praise reads as filler
3. **Actions** — ranked, highest impact first, each tagged **Cut**, **Change**, or **Keep** (keep = fine as is, but name what to watch). The top item *is* the one thing to fix and the Cut items *are* the removal list — don't restate them as separate sections.

### Variant: Comparing two directions

When the question is "A or B?" rather than "is this good?":

1. Name the user's job once — it is the same for both
2. Score both directions on the same three or four principles (usually 2, 7, 10), side by side, one line each
3. Recommend one. Say what it gives up, and what the losing direction was *trying* to do so the need isn't lost with it
4. Prefer the direction that wins on 10 unless it loses on 2 — restraint is the tie-breaker, usefulness is the veto

## Tone

- **Interrogate purpose, not pixels.** "Why does this element exist?" before "is this element well made?" — the second question belongs to ui-craft-review.
- **Reference the principle.** "Principle 6 (Honest): the countdown timer resets on refresh — it's fabricated urgency" is more useful than naked opinion.
- **Champion removal without being precious.** "Cut it" is a recommendation, not an insult. But name what the element was *trying* to do, so the underlying need isn't lost with it.
- **Name trade-offs honestly.** Business goals vs. user goals, discoverability vs. restraint, innovation vs. longevity — these are real tensions. A Tension verdict with a clear articulation beats a dishonest Pass or a lazy Fail.
- **Hold the ethical line quietly.** Honesty and respect-for-attention findings are non-negotiable in a way aesthetic findings aren't — flag them as such without sermonising.
- **Less is more.** Six sharp findings beat thirty bullets. Rams would cut the review too.

## Example application

When reviewing a subscription upgrade screen:

**Principle 2 (Useful): Tension** — Of the nine elements on screen, six serve the user's decision (plan comparison, price, billing cadence) and three serve only conversion (social-proof ticker, "most popular" badge on the most expensive plan, testimonial carousel). The badge might be genuine guidance — but only if it reflects actual purchase data.

**Principle 4 (Understandable): Fail** — The difference between the Pro and Team plans is expressed in feature-flag jargon ("advanced workflows", "priority compute"). A first-time viewer cannot say which plan fits them. Rewrite the comparison in terms of user jobs, not SKU names.

**Principle 6 (Honest): Fail** — The "Offer ends tonight" banner resets for every visitor. This is fabricated urgency and it contaminates trust in every other claim on the page. Remove it; no craft improvement can redeem it.

**Principle 10 (As little as possible): Tension** — The testimonial carousel, the ticker, and the FAQ accordion are all competing to close the sale. Pick the strongest single trust element and cut the other two.

---

**Headline:** The screen knows what the business wants but not what the user needs — it persuades where it should inform.

**What's already working:** The plan comparison table leads the visual hierarchy; pricing is stated plainly with no asterisks; the downgrade path is visible rather than hidden.

**Actions:**
1. **Cut** the countdown banner (Principle 6) — the only finding that damages trust in everything else
2. **Change** the plan comparison to user jobs, not SKU names (Principle 4)
3. **Cut** the social-proof ticker and testimonial carousel; **Keep** the strongest quote as a single static element if data shows it helps (Principle 10)
