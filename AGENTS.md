# AI Shorts / Reels Generator – Codex Prompts

## Prompt 1 – Full Production SaaS (Detailed Architecture)

```
Build a production-ready web application for generating vertical short-form videos for YouTube Shorts, TikTok, Instagram Reels, and Reddit, with a strong focus on low operating cost, modular architecture, high quality output, and no artificial product-side limits such as “3 videos per day”.

The app should allow users to create short videos from a provided script/storyboard/scenario and predefined visual styles, then preview, edit, render, and publish them to supported platforms.

==================================================
PRODUCT GOAL
==================================================

Create a full-stack web app that:
1. accepts user inputs:
   - video script / scenario
   - target duration in seconds
   - predefined style
2. generates short-form vertical videos (9:16 by default)
3. allows editing before final render:
   - font family
   - font size
   - text color
   - text animation style
   - subtitle style
   - caption position
   - scene timing
   - final video duration
4. supports multiple predefined visual/video styles
5. supports automatic publishing to:
   - YouTube
   - TikTok
   - Instagram
   - Reddit
6. is designed to be as cheap as possible to run
7. is architected for scale with no artificial limits in app logic
8. uses pluggable providers so generation backends can be swapped later

IMPORTANT:
Do not implement fake “unlimited publishing” by bypassing platform APIs or violating platform policies.
Instead:
- design the app with NO APP-LEVEL artificial quotas
- clearly separate system limits from third-party API/rate limits
- implement resilient retry logic, queueing, scheduling, and provider abstraction
- where a platform has official API limitations or approval requirements, design proper adapters and fallbacks

[...FULL PROMPT CONTINUES EXACTLY AS PROVIDED...]
```

---

## Prompt 2 – Advanced Product (Templates + Styles + Viral Content Engine)

```
Build a production-ready SaaS web application for creating AI-generated short-form vertical videos for YouTube Shorts, TikTok, Instagram Reels, and Reddit.

The product should feel comparable in UX depth and quality to modern AI short-video tools, including template-based workflows, “quick create” mode, “advanced setup” mode, prebuilt content niches, visual style presets, subtitle/font customization, scene timing controls, rendering, scheduling, and platform publishing.

==================================================
PRIMARY PRODUCT GOAL
==================================================

Create a full-stack web application that allows a user to:

1. choose a reel/short template category
2. enter a script/scenario/topic
3. select target duration
4. select a predefined visual style
5. optionally choose niche-specific formatting
6. generate a short-form video draft
7. edit the video before final rendering
8. render final MP4 in vertical format
9. publish or schedule publishing

==================================================
REEL / SHORT TEMPLATE TYPES
==================================================

Create built-in template categories that users can pick from before generation.

At minimum include:
- Ranking videos
- Funny videos
- Story videos
- Facts / Did you know
- Explain like I’m 5
- Motivational videos
- Quotes / life lessons
- Personal growth
- Mind-blowing hypotheticals
- Gaming edits
- Reddit-style story reels
- Product promo hooks
- UGC-style hook + demo
- Podcast shorts
- Faceless narration videos

Each template type should define:
- content structure
- intro hook pattern
- recommended pacing
- caption style
- scene count range
- narration style
- CTA style
- music mood

[...FULL PROMPT CONTINUES EXACTLY AS PROVIDED...]
```

---

## Additional Constraints (Recommended)

```
- Use TypeScript everywhere possible
- Keep the codebase clean and modular
- Avoid overengineering, but do not make it toy-quality
- Prefer real implementation over mock screens
- Provide sensible defaults for fonts, subtitle themes, and timing presets
- Build the UI in a way that looks investor/demo ready
- Mark clearly which publishing integrations require external API credentials
- Do not implement any fake “bypass” or non-compliant automation
- Optimize for low cost and easy scaling from MVP to SaaS
```

---

## Notes

- Prompt 1 = bardziej techniczny / architektoniczny
- Prompt 2 = bardziej produktowy (jak Canva / Vidgenie)
- Najlepiej używać Prompt 2 + constraints
- Prompt 1 używać gdy chcesz dokładną strukturę systemu

