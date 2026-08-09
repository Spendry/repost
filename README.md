# Repost - keep it lit

> Part of my [portfolio](https://github.com/Spendry/portfolio).

A concept and working prototype for a gamified social network where **attention is survival**. Every post arrives with a lifespan and visibly decays toward deletion. A repost adds time on a diminishing curve, so people can sustain a post but never make it immortal, and how many *distinct* people keep it alive sets its clock. Saving something becomes a vote that it deserves to exist. The result is a feed with real stakes, built on one legible metaphor: a shared hearth the community keeps lit.

It is a deliberate counter to algorithmic feeds. Engagement stops being an additive vanity score and becomes the thing that decides what survives.

## Try the prototype

**[Live prototype →](https://spendry.github.io/repost/)** *(the full interactive prototype; best on a phone-width window)*

Walk the product from a user's perspective: the feed and its decay loop, messaging, settings, user profiles, onboarding, the ember economy, and branch mechanics. There is no sign-up; it is an experience of the app, not a live service. It renders client-side and loads React from a CDN, so it needs JavaScript and a network connection.

There is also a **[simpler static mockup](repost-mockup-static.html)**: an earlier, faster, fewer-features look at just the core loop, in pure HTML/CSS. It is a different and lighter demo, not the same design as the full prototype.

## What's here

| File | What it is |
|---|---|
| [index.html](index.html) | The full interactive prototype: feed, messaging, settings, user profiles, onboarding, the ember economy, decay loop, and branch mechanics, all live. A single self-contained React component. |
| [support.js](support.js) | The prototype's runtime (generated). `index.html` loads it and React to render in the browser. |
| [repost-mockup-static.html](repost-mockup-static.html) | An earlier, simpler static mockup: a faster, non-personalized view of just the core loop. Pure HTML/CSS, always renders. |
| [repost-design-schemas.html](repost-design-schemas.html) | The front-end design system: type, color, components, and the visual language behind the hearth metaphor. |
| [Repost_SellSheet.pdf](Repost_SellSheet.pdf) | The pitch. What the product is, why it matters now, and how the core loop works. |
| [Repost_Builder_Playbook.pdf](Repost_Builder_Playbook.pdf) | How to take the concept to a shipped product without cutting the parts that make it Repost, including the eight load-bearing rules a build must never break. |

## The idea in one sentence

A post is a dying ember, and the only thing that keeps it alive is people choosing to save it. If a change makes survival automatic, makes a few people matter more than many, or hides why something lived, it has stopped being Repost.

This is a design and product-thinking artifact: a prototype and a plan, not a shipped application.

## Credit

Concept and design: Sammuel Pendry, developed through guided AI collaboration. © 2026 Sammuel Pendry, all rights reserved.
