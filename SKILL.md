---
name: kirby-plr-omnichannel-repurposer
description: "Cascades a single personalized PLR article or chapter into 12 platform-native social, audio-visual, and professional micro-assets."
category: workflow
triggers: [repurpose-plr, omnichannel-content, social-snippets-plr, content-cascade, cross-platform-repurposer, social-media-plr]
---

# SOP: Omnichannel Content Cascade & Repurposing Engine

> Standard Operating Procedure for taking a single personalized Private Label Rights (PLR) asset and systematically fragmenting it into 12 platform-native formats to maximize distribution velocity.

---

## 1. The Distribution Bottleneck

Creating or personalizing an authoritative long-form article is only 20% of the battle; the remaining 80% is **distribution**. 

Publishing a 1,500-word piece solely to a blog leaves 95% of its potential audience untouched. However, manually rewriting that article for Twitter, LinkedIn, Instagram, Pinterest, and YouTube is an exhausting operational drain.

Worse, lazy "cross-posting" (dumping the exact same text and links across all platforms) fails because each network possesses distinct algorithmic expectations, formatting rules, and audience mindsets.

This skill implements the **Content Cascade Protocol**: decomposing 1 core asset into 12 bespoke channel formats in a single pass.

```
┌─────────────────────────────────────────────────────────┐
│              1 Core Personalized PLR Asset              │
│                 (Blog Post / eBook Chapter)             │
└────────────────────────────┬────────────────────────────┘
                             │
                             ▼
┌─────────────────────────────────────────────────────────┐
│               The Content Cascade Engine                │
├────────────────────────────┬────────────────────────────┤
│ Professional & Long-Form   │ Visual & Algorithmic       │
│ - LinkedIn Post (Hook/List)│ - Pinterest Pins & Boards  │
│ - LinkedIn Pulse Essay     │ - YouTube Description/Tags │
│ - FB Group Value Post      │ - YouTube Community Update │
├────────────────────────────┼────────────────────────────┤
│ Short-Form Video & Audio   │ Community & Ephemeral      │
│ - TikTok / Reels Script    │ - Instagram Feed Carousel  │
│ - 60-Second Hook / Payoff  │ - Instagram Story Sequence │
└────────────────────────────┴────────────────────────────┘
```

---

## 2. The 12 Platform-Native Output Formats

### 1. Facebook Business Page Posts
* **Format:** 2-3 short paragraphs, conversational hook, direct value, engagement question at the end.
* **Objective:** Comment velocity and link click-through.

### 2. Facebook Group Community Posts
* **Format:** Unpolished, peer-to-peer tone. Zero outbound links in body (drop link in first comment).
* **Objective:** Spark debate and long discussion threads.

### 3. Instagram Feed Posts & Carousel Outlines
* **Format:** 5-7 slide carousel script (Slide 1: Contrarian Hook -> Slides 2-5: Step-by-step breakdown -> Slide 6: Summary -> Slide 7: Save & Share CTA) plus caption with hashtags.

### 4. Instagram Stories Scripts (4-part series)
* **Format:** Casual, selfie-video prompts or text-card overlays:
  - Card 1: The Poll / Question
  - Card 2: The Shocking Stat or Mistake
  - Card 3: The Fix
  - Card 4: Link sticker or DM trigger

### 5. Pinterest Pin Descriptions
* **Format:** Keyword-dense, 300-character description with 3 high-volume search tags. Designed for search intent rather than social feed scanning.

### 6. Pinterest Board Descriptions
* **Format:** Broad topical overview establishing category authority and keyword clustering.

### 7. YouTube Video Descriptions
* **Format:** Comprehensive SEO description with timestamps, summary of key insights, resources mentioned, and subscribe triggers.

### 8. YouTube Community Tab Posts
* **Format:** Image or text poll paired with a 2-paragraph thought piece teasing an upcoming video or blog post.

### 9. TikTok & Instagram Reels Scripts (60-90 Seconds)
* **Format:** Visual and spoken audio cues:
  - `[0-3s Hook]`: Visceral pattern interrupt
  - `[4-20s Agitation]`: Why conventional wisdom is failing
  - `[21-50s Breakdown]`: 3 rapid-fire actionable steps
  - `[51-60s Payoff & CTA]`: The final takeaway and follow trigger

### 10. LinkedIn Professional Posts
* **Format:** One-sentence line breaks, white space optimization, business-impact lens (ROI, efficiency, team morale).

### 11. LinkedIn Pulse Article Adaptations
* **Format:** 800-word authoritative editorial essay highlighting strategic industry implications.

### 12. Cross-Platform Syndication Series
* **Format:** A unified 5-day posting schedule synchronizing messaging across all active channels.

---

## 3. Master Prompt: The 12-Format Omnichannel Cascade

```markdown
You are a master social media content strategist and omnichannel distribution architect.
Deconstruct the provided personalized article into 12 platform-native assets.

### INPUT ARTICLE:
"""
{{INSERT_PERSONALIZED_ARTICLE_TEXT}}
"""

TARGET AUDIENCE: {{TARGET_AUDIENCE}}
CORE CTA / DESTINATION: {{TARGET_URL_OR_RESOURCE}}

### EXECUTION DIRECTIVES:
1. Generate each of the 12 platform assets specified in the SOP.
2. Adhere strictly to the native formatting, line-break style, and algorithm mechanics of each specific channel.
3. For short-form video scripts (TikTok/Reels), provide explicit [Visual Action] and [Spoken Audio] directions.
4. For carousel outlines, provide exact text for Slides 1 through 7.
5. Ensure no two platform outputs use identical opening hooks.
```

---

## 4. Quality Control Checklist

Before deploying social assets:
- [ ] Are LinkedIn line breaks optimized for mobile skimming?
- [ ] Are TikTok hooks under 3 seconds with immediate visual/auditory tension?
- [ ] Are outbound links removed from algorithmic penalties (e.g. FB Group bodies)?
- [ ] Are Pinterest descriptions optimized for search discovery rather than conversational banter?
