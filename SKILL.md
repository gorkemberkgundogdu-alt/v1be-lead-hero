---
name: v1be-lead-hero
description: Visually audit a live v1be studio prospect website, develop two brand-specific hero concepts, and turn the selected direction into a near-final desktop and mobile comp. Implement in Framer only on the user's explicit instruction.
metadata:
  author: gorkemberkgundogdu-alt
---

# v1be lead hero

Take a verified product truth and make it visible in the first viewport. Work one brand at a time. A batch must keep a checkpoint per brand so it can resume without rebuilding or duplicating drafts.

## 1. Ground the brief

- Load `website-lead-audit` and use its evidence-first method. Verify the official domain, homepage and the product, help, or demo page that substantiates the main promise.
- A live visual audit is required before ideation. Open the official site in a browser and inspect the rendered hero and primary action at both desktop and mobile viewport widths. Record the URLs, date, viewport widths and distinct visual observations for both sizes. Keep screenshots when supported. Indexed text, source code and desktop-only views cannot satisfy this requirement. If either live viewport cannot be inspected, mark the brand blocked at visual audit, explain the access issue and pause that brand before ideation.
- Label visual observations, interpretations and unknowns separately.
- State who arrives, what they need to understand, what the product demonstrably does, what the existing brand already does well, and the appropriate primary action. Keep one central promise. Use first-party assets or original visual material. Identify concept branding and any illustrative data as such.
- Find one or two specific references when they improve the brief. State the principle each contributes. Derive imagery, copy, and composition from the subject.

## 2. Design two directions with Anthropic frontend-design

Load the installed `frontend-design` skill for this phase. Produce two directions for the same audience, promise and CTA. Each must change the composition or the way the proof is revealed. Color changes alone do not count.

For each direction specify:
- First-view reading order and focal object, gesture or product state.
- Actual headline, supporting sentence and CTA, with English copy when the prospect site uses English.
- One compact wireframe, named typefaces with roles, and four to six named palette colors with roles.
- The product evidence shown, mobile reading order, and one real weakness or tradeoff.

The studio prefers a clear point of view, real product objects and intentional typography. Let the product determine the composition. A split layout, oversized metric or card grid must earn its place by doing a job the alternatives cannot do as clearly. Reject a concept if a competitor could use its first screen with only a logo and name change.

## 3. Select and lock

First disqualify unsupported claims, confusing identities, inaccessible essential content or a CTA disconnected from the user journey. Compare viable directions on product specificity, clarity at first glance, strength of composition, brand fit and mobile feasibility. Explain the winner and name the tradeoff accepted. In delegated selection mode, the agent chooses and records the decision. Honor any existing user choice. Present and save both concepts and the selection rationale. Selection and Framer implementation are separate decisions.

Calibration: for Biller Genie, the first revisions changed the invoice illustration while retaining the old text-first order, Manrope and petrol palette. The chosen direction reorganized the entire hero around one angled document, with the merchant invoice and the posting record on the same sheet. The condensed headline closes the scene. Carry forward the decision principle and derive a new form for each brand.

## 4. Art-direct the selected hero with Taste Skill

After the Anthropic `frontend-design` concept pass and v1be selection, load Leonxlnx's `design-taste-frontend` (Taste Skill). Use its relevant guidance on assets, product visuals, backgrounds, components and responsive composition to develop the selected direction. The brief and chosen concept govern this pass. Keep the selected promise, visual idea and reading order. Treat Taste's layout dealer, starter and full-page rules as resources for compatible work, without applying them by default to a single hero. In a batch, compare the new comp with recent comps and change repeated visual treatments when their resemblance comes from a reusable recipe.

Produce a near-final visual comp of the full first viewport at a representative desktop width and a phone width. Use a permitted design canvas or a standalone visual artifact outside Framer. Show the actual composition with the chosen typography, palette, headline, supporting copy and CTA. A wireframe or written art direction is not the comp.

- **Lead visual.** Make or source the central asset that shows the product's specific mechanism. Choose an authored illustration, product view, photograph, diagram or other form that fits the story. Use verified first-party material or original assets, and label illustrative states and data.
- **Background.** Define how the surface frames the focal point and guides the eye. Choose color, texture, depth or negative space for a reason tied to this brand and subject.
- **Components.** Draw the pieces the viewer actually sees with plausible content and a consistent visual language. Define the details that communicate their role, such as document rules, data alignment, boundaries or state indicators. Use only the pieces that help the viewer understand the promise.
- **Mobile.** Compose the phone view deliberately. Resolve the order, asset crop, headline wrapping, legibility of product detail and visibility of the primary action.

Review both rendered views against the chosen brief. Check that the asset and components make the idea recognizable even without the headline, that the visual proof and CTA are easy to find, and that the same comp would not suit a competitor after a name swap. Fix material issues before handing off. Deliver the two comps with a short note on the key art-direction decisions and any asset limitations. If a visual comp cannot be produced, report the blocker and leave the brand at `selected`.

## 5. Choose an implementation lead and verify

**Framer gate.** Proceed only when the user explicitly instructs you to implement in Framer for the named brand or batch. Running this skill, delegating concept selection, or approving a direction or comp does not authorize Framer work. Until that instruction arrives, deliver the comp and stop before opening, creating or editing Framer projects.

Use the desktop and phone comps as the visual contract for the lead asset, background, components, layout, copy and type. Choose one implementation lead based on what the design needs and the target tools can support. Record the reason and the scope of any secondary skill:

- **Impeccable leads by default for native Framer work.** Load its current implementation and verification playbooks and read the craft floor before UI edits. Use Taste alongside it for a specific pass when useful, such as improving the lead asset or checking the component system. If Impeccable's launcher fails, follow its documented fallback and record the gap.
- **Taste Skill can lead in place of Impeccable** when the main implementation work is visual assets, product components or a supported browser-rendered prototype and its methods fit the chosen comp. In Framer, translate the applicable techniques into native editable structures through the connector. Use its browser checks only on supported targets. Record any unavailable check and verify the Framer renders directly.

The approved comp governs both routes. Keep secondary guidance scoped to its assigned pass. Resolve conflicting layout, visual or motion defaults in favor of the brief and comp.

Use the Framer connector and its project docs. Reuse the requested draft or create an unpublished prospect draft in the authorized workspace. Check for existing project IDs before creating. Keep useful content editable and keep the single primary CTA linked to a verified destination. Check desktop and phone together, plus tablet when available. Fix material issues in one pass and confirm. Compare actual screenshots with the selected concept, including the expected font, text contrast and reading order. Mark a missing or failed check explicitly. Keep publication, external sharing and outreach separate from draft creation.

## 6. Record and advance

For each brand save the live visual audit evidence, both directions, the chosen rationale, desktop and phone comps, and any unresolved issue. Record state as `researched`, `selected`, `comp-ready`, `built`, `verified`, or `blocked`. Without explicit Framer instruction, stop each brand at `comp-ready` and continue through the comp phase for the next brand. When implementation is authorized, save the project URL as soon as it exists and retain available viewport captures. A verified entry needs both concepts, both comps, a rendered project and desktop/mobile review. Retry recoverable problems within the skill's bounded checks. Keep a blocked brand visible and continue in order with the next brand. Close with a concise linked index.
