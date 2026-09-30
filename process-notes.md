# No Fixed Form — Production notes

## Delivered work
A 30-second, 1920×1080, 24 fps AI-assisted literary short. Chinese and English captions are burned into the film; a separate SRT is provided. Sound uses an original synthesized Chinese-inspired R&B instrumental. There is no spoken narration.

## Source and authorship
- Literary source: Sun Tzu, *The Art of War*, chapter 6, 虛實篇. The quoted phrase is 「兵無常勢，水無常形」.
- English wording and the three preceding narrative captions were developed for this study. The water journey is a creative interpretation, not a historical reconstruction or a complete account of the chapter's military argument.
- Prepared for Jerry Lai's portfolio with AI assistance in concept development, bilingual writing, generation prompts, procedural sound, code, editing and presentation. Jerry's personal review and discussion of the work remain part of the application process.

## Actual production
1. Two Seedance 2.0 text-to-video jobs, 12 seconds each at 1080p, completed on 30 September 2026. Their exact submitted prompts are included.
2. The first clip follows ink spreading into a stream around stone. The second changes from a close stone-and-current view into a wider river landscape. The generated stone geometry and scale differ across clips; the transition is an editorial cut, not a claimed continuous camera take.
3. FFmpeg assembles the two clips with a three-second opening and three-second end card. Captions are typeset in postproduction.
4. An original Chinese-inspired R&B score combines pentatonic plucked-string and flute-like synthesis, electric-piano seventh/ninth harmonies, bass and swung drums. The revised mix targets −16 LUFS / −1.5 dBTP. Generated ambience is replaced.
5. The first render exposed missing Traditional Chinese glyphs in the local Songti font. The final render uses Noto Serif CJK TC; this is a documented postproduction correction, not an invented extra generation pass.

## Typography
Chinese: Noto Serif CJK TC (SIL Open Font License). English: Georgia, rendered locally into the video. Font files are not included in the public package.

## Verification
- Video and audio streams: both 30 seconds; H.264 video and AAC audio.
- Complete file decode and sampled frame inspection.
- Title and subtitle glyph checks after font replacement.
- Website and downloadable final MP4 checked after deployment.
- No claim of independent human listening review or paid client results is made.

## Deliverables
`assets/no-fixed-form.mp4`, `film-subtitles.srt`, bilingual case-study page, treatment, exact prompts, and this record.

## Environmental sound design — current release
墨滴、流動、遇阻、左右分流與遠景風聲。
The current soundtrack combines a quiet original score with original synthesized environmental sound and Foley-like effects. Subtle original melody, harmony and drums sit beneath the environmental bed, about 23 dB lower after independent loudness normalization, ducked a further 6 dB around picture/text cues. No voice-over, field recordings or song samples. Cues follow visible action, camera perspective and scene changes; water branches move left/right and wide views reduce close detail. Titles and endcards are quiet. Full file decode checked; perceived realism remains subject to listening review.

## Water emphasis revision
Water stream layers increased relative to room/wind, extra small droplet details added around flow and branching, and distant water retained under the wide shot. Environmental bed target raised from -21 to -18 LUFS; subtle musical layer unchanged. All water is synthesized sound design.
