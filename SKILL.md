---
name: ai-sales-video-creator
description: Create Vietnamese short-form product sales video production packages for TikTok and Facebook Reels with consistent AI characters, shot prompts, voiceover and publishing checklists.
---

# AI Sales Video Creator — Level 2 (v2.0)

## Goal
Produce two 9:16 vertical short-form video production packages per day for TikTok and Facebook Reels. Prioritize free or low-cost tools. Do not claim a rendered video or published post exists unless the corresponding tool has completed it.

## Input
Ask for product name, product photos or reference video, target buyer, truthful benefits, desired duration (default 30 seconds), price/offer if verified, call to action, and character reference. If details are missing, use clearly labeled assumptions; never fabricate product certifications, testimonials, prices or guarantees.

## Workflow
1. Analyze product, target customer, key problem, benefits, objections and proof.
2. Write a strong opening hook in the first 3 seconds, an engaging problem-solution narrative, and one clear purchase CTA.
3. Divide the script into timed scenes; ensure total scene durations equal requested runtime.
4. Define a CHARACTER LOCK from the first reference: age appearance, face, hair, clothing, voice, lighting and visual style. Reuse the same reference image and character specification in every scene. Warn that prompts alone cannot guarantee perfect facial identity; use image references and review outputs.
5. For every scene provide duration, framing, action, facial expression, camera movement, product interaction, spoken Vietnamese dialogue, and an English generation prompt for Flow/Veo where useful. Default vertical 9:16 and photorealistic motion.
6. Write one continuous Vietnamese voiceover with natural pause markers and estimated timing. Avoid on-screen words unless requested.
7. Prepare edit instructions: shot order, captions if requested, music/SFX suggestions, transitions, safe margins, and platform-specific descriptions/hashtags.
8. Run quality control: character identity, product fidelity, scene continuity, accurate claims, readable audio, timing, CTA, and platform policies.
9. Output a production checklist and distinguish ready-to-generate assets from actually generated files.

## Output structure
- Product positioning and buyer
- Hook + full script
- Timed scene table
- CHARACTER LOCK and reusable negative prompt
- Scene-by-scene Veo prompts
- Vietnamese voiceover
- Editing and export checklist
- TikTok caption and Facebook Reels caption
- Quality-control notes

## Rules
- Maintain one consistent AI character throughout all scenes.
- Never silently change the product's shape, brand, color or key features from the reference.
- Keep dialogue in natural Vietnamese, warm and clear; choose tone for the audience.
- Make the sales message persuasive without false urgency or unverified claims.
- Do not assume automatic video rendering, scheduling, or posting capabilities. Require supported integrations and user authorization for publishing.
- Default to two distinct videos per day: one problem-solution demonstration and one benefit-focused storytelling video.

## Voice continuity for separately generated scenes
When scene voices differ or dialogue is cut off, follow [references/voiceover-continuity.md](references/voiceover-continuity.md). Prefer one continuous Vietnamese voiceover track, verify actual clip durations, mute inconsistent source speech and synchronize narration after visual assembly. Do not claim that audio exists until it has been generated.

## V2.0 — Dynamic fashion, character, outfit and voice continuity
For fashion/model videos, **always** follow [references/dynamic-fashion-directing.md](references/dynamic-fashion-directing.md) before writing the storyboard or prompts. This reference is mandatory for requests involving people modeling clothes, walking, dancing, posing, or displaying outfits.

### Mandatory separate locks
- **IDENTITY LOCK:** Same approved face/reference image and appearance in every scene.
- **OUTFIT LOCK:** Same original garment photo, cut, colors, pattern, logo and details. Map each requested outfit to its intended scene; never silently swap garments.
- **VOICE LOCK:** Same Vietnamese voice and narration style across scenes; prefer one continuous voiceover track when editing.

### Motion-direction requirement
Every scene must specify a **distinct primary movement**, secondary gesture, natural expression, pacing, realistic weight shift, fabric motion, and camera movement. Favor energetic but believable actions such as lively steps, playful side steps, small bounces, quarter turns, skirt twirls and varied poses, tailored to the actual garment. Avoid stiff/robotic posture, identical repeated motions, fixed smiles and unnatural jumping. Keep movements feasible for short clips and full-body framing when showcasing an outfit.

### Timing and QC gate
Check actual generated clip and narration durations, not just word-count estimates. Never cut off a spoken word or claim verified sync without reviewing the output. Before delivery, explicitly check character identity, garment accuracy, expressive natural movement, voice continuity and clip-by-clip timing. Regenerate only the defective scene with the original references where possible. Explain that prompts improve consistency but cannot guarantee error-free generation.
