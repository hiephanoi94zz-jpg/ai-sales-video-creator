# Continuous Vietnamese Voiceover Workflow

## Trigger
Use this workflow whenever independently generated Veo scenes have mismatched voices, inconsistent tone, missing spoken words, or dialogue cut off by clip boundaries.

## Principle
Preserve approved video imagery. Remove or mute original generated dialogue. Record or synthesize ONE continuous narration track using ONE voice identity, then synchronize that track to the assembled visual sequence. A written prompt alone does not lock the voice across separate generations.

## Timing
- Inspect actual media durations with ffprobe rather than assuming requested durations.
- Calculate cumulative boundaries exactly. Example: 5 x 7.85 s = 39.25 s; scene starts 0, 7.85, 15.70, 23.55, 31.40.
- Allocate narration to each visual interval, including natural pauses. A script is not guaranteed to fit until the actual speech audio is rendered and timed.
- Keep narration continuous at boundaries; avoid cutting words, inhalations or sentence endings.
- If the narration is too long, shorten the script or adjust pause lengths before changing playback speed.
- Do not stretch speech unnaturally or fabricate a finished voice recording.

## Voice specification
Vietnamese adult female; warm, slightly low pitch, friendly and clear; consistent accent, timbre, pace, mic sound and loudness. Use a single TTS voice preset or one human recording session for all five scenes. Generate a single full-length file when possible.

## Editing
1. Order approved clips by storyboard.
2. Preserve original visuals and mute source audio.
3. Concatenate clips into a single video timeline.
4. Place one voiceover WAV/MP3 on a separate audio track; align the narration to actions and scene boundaries.
5. Add subtle background music only if properly licensed, keeping dialogue clear.
6. Verify duration, pronunciation, audio peak levels, transitions and CTA.
7. Export vertical 1080x1920 H.264/AAC; preview on a phone.

## Verification
Report separately: verified video duration; script prepared; actual voice file generated (yes/no); voice synchronized (yes/no); final exported video (yes/no). Never conflate a prepared script with a generated audio recording.
