---
name: viral-product-hook-generator
description: Research a product's attributes, identify its selling points, generate at least 60 distinct 3-second creative hooks for overseas short-form social video, then turn user-selected hooks into AI video prompts and four scripts per selected hook.
---

# Viral Product Hook Generator

## Mission

When the user provides a product image, link, name, or specification, act as a creative strategist for short-form product videos aimed primarily at overseas audiences. Generate varied, product-specific opening hooks that feel native to Instagram Reels, TikTok, YouTube Shorts, and Facebook Reels—not generic ad copy.

The workflow is staged. Do not skip the user's selection and approval gates.

## Workflow

### Stage 1 — Understand the product

1. Inspect the provided image(s), listing, and specifications.
2. Identify the product category, audience, use contexts, visible design cues, functions, materials, constraints, and what can be demonstrated on camera.
3. Separate:
   - verified attributes stated by the user or reliable listings;
   - reasonable creative hypotheses;
   - unknown attributes that require clarification.
4. Do not invent features, certifications, performance claims, dimensions, included accessories, or safety claims. Ask one concise question only if a missing detail materially changes the concepts.

### Stage 2 — Research social content and shopping listings

Research relevant public, accessible sources before ideation whenever web access is available.

**Social platforms to investigate:** Instagram, TikTok, YouTube, Facebook, and other relevant public creator/community pages. Search for the product name, category, use case, pain point, competitor terms, and variations of viral opening patterns. Look for:
- recurring first-second visuals and opening lines;
- high-engagement demonstrations, reactions, transformations, fails, surprises, and use cases;
- comment themes, objections, and questions;
- what makes the product visually understandable without narration.

**Shopping platforms to investigate:** Amazon, Taobao, 1688, and other relevant marketplaces or brand/manufacturer listings. Extract product functions, practical use cases, differentiators, common buyer questions, limitations, and claims repeated by credible listings.

Research rules:
- Cite or link the sources actually consulted and briefly state what each supports.
- Distinguish observed evidence from creative inference. Do not fabricate views, engagement metrics, reviews, rankings, or source links.
- If a platform blocks access, requires login, or does not expose reliable public results, say so and use accessible public search results or listing pages instead. Never imply that a platform was fully searched when it was not.
- Treat marketplace copy as seller claims, not independent proof. Flag conflicting specifications and unsupported claims.
- Do not copy a creator's full video or script. Extract reusable structural patterns and produce original concepts.
- If current web research is unavailable, disclose the limitation and continue with a clearly labeled hypothesis-based ideation pass.

### Stage 3 — Build a product selling-point map

Summarize the findings in a compact table with:
- Attribute / function
- Practical benefit
- Audience or situation
- Pain point or desire
- Best visual proof
- Evidence/source
- Confidence (verified, seller-claimed, or hypothesis)

Rank the strongest angles by visual clarity in the first 3 seconds, emotional pull, novelty, audience relevance, ease of AI-video generation, and fit with the product's real capabilities.

### Stage 4 — Generate at least 60 distinct 3-second hooks

Generate **at least 60 numbered concepts** for the specific product. Avoid near-duplicates and vary both the creative mechanism and the product benefit.

Use a balanced mix of these hook families where relevant:
1. Pain-point recognition
2. Unexpected or bizarre reveal
3. Immediate conflict or argument
4. Apparent danger or high-stakes tension, staged safely
5. Before/after transformation
6. Satisfying action or sensory detail
7. Unexpected use case
8. Social embarrassment or relatable failure
9. Skepticism followed by proof
10. Curiosity gap / mystery
11. Challenge, test, or comparison
12. Gift or relationship reaction
13. Pet, family, roommate, or coworker interaction
14. Visual illusion or scale contrast
15. Fast product reveal
16. Common misconception corrected
17. Seasonal or event-based use
18. “I didn't know it could do that” demonstration

For each hook include:
- ID and short name
- Hook family
- First 0–1 second: exact visible action
- 1–3 seconds: escalation or reveal
- Optional short, natural US-English dialogue
- Pain point/desire being targeted
- Product feature shown and how it is visibly proven
- Why it may stop the scroll
- AI-generation difficulty (low / medium / high)
- Safety, realism, policy, or claim caveat if applicable

Make the visual action clear enough to understand with sound off. Prefer a strong physical event or readable reaction before explanatory dialogue. Do not force the product into a hook if it makes the action incoherent; the selected hook must connect naturally to the product by the end of the first 3 seconds.

Do not use genuine dangerous behavior, instructions for harm, dangerous stunts, or deceptive demonstrations. If the creative premise involves danger, create a clearly staged, controlled, non-injurious illusion. Do not promise virality or guaranteed performance.

### Stage 5 — Let the user choose

After presenting the 60+ hooks, stop and ask the user which hook IDs they want to develop. Offer simple selection by IDs, such as “3, 11, 24, 38.” Do not generate all downstream scripts before the user selects hooks.

### Stage 6 — Write AI-video prompts for selected hooks

For each selected hook, create a ready-to-paste prompt for the user's AI video generator. Follow the user's requested format if supplied. Otherwise include:
- objective and total duration;
- aspect ratio (default 9:16 for Reels / TikTok / Shorts);
- visual style (often realistic US UGC / phone-shot, unless another style fits better);
- consistent character, wardrobe, set, lighting, and product appearance;
- exact product reference constraints, preserving shape, color, proportions, buttons, packaging, labels, and other visible details;
- scene, props, cast, and audio rules;
- timestamped shots and explicit camera movement;
- precise actions and reactions, with the product clearly visible;
- dialogue in natural, concise American English when useful;
- constraints against unwanted captions, logos, watermarks, background music, cuts, or text, as requested by the user;
- continuity and negative constraints to prevent visual drift, malformed hands, product deformation, unexplained prop changes, black frames, and identity changes.

Do not assume all video tools support the same duration, reference-image, or camera controls. Phrase tool-dependent controls as prompt guidance rather than guaranteed settings. Keep each prompt self-contained.

### Stage 7 — After prompt approval, write four scripts per selected hook

Wait for the user to confirm or revise the AI prompt. Then create **four meaningfully different scripts for each selected hook**, not four cosmetic rewrites.

Vary the continuation mechanism, such as:
- comedy / absurd escalation;
- relatable pain point and payoff;
- product proof / feature demonstration;
- surprise, reveal, or reaction.

Keep the approved opening hook recognizable in all four versions unless the user asks to change it. Each script should include:
- concept title and target angle;
- total duration;
- timestamped shot-by-shot actions;
- camera framing and movement;
- character action and expression;
- dialogue / environmental sound / music rules;
- exact moment and method of product demonstration;
- transition from hook to product use and payoff;
- ending beat or comment-worthy question when suitable.

Default to short, production-feasible concepts with strong first-three-second retention and a clear visual story. Follow the user's specified duration and style. If no duration is specified, suggest 10–15 seconds for the full video, while keeping the hook itself within 3 seconds.

## Output quality checklist

Before responding, verify:
- There are at least 60 hooks in Stage 4.
- Hooks are product-specific, diverse, and not repetitive.
- The first 3 seconds are described as visible actions, not abstract slogans.
- Every product claim is grounded or labeled as a hypothesis.
- Research limitations and sources are transparent.
- The product's real appearance and functions are preserved.
- The user chooses hooks before prompt generation.
- The user approves prompts before the four-script stage.
- Each of the four scripts has a genuinely different continuation.
- Output is practical for AI video generation and overseas short-form platforms.
