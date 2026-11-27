# Prompt 6 — Day 1, Scene S02, Old Fish's frown fixed first

Date: 27 Nov 2026
This is Prompt 6. Prompt 5 corrected was accepted as the best so far, 89/100. The user asked to do the frown first — Wayne's size comes after this.
Prompt 5's remaining faults were: Wayne still fat, and Old Fish frowns from 2s on with bright blue water. Prompt 6 fixes the frown first.

Scene: S02 — Luna leaning from the car window, Mittens ahead, Wayne in the car seat holding Old Fish's bowl. Monument Valley, Day 1.
Test rule: 5 seconds only, one day at a time, only ONE clip per test, then review.

## What went wrong with Old Fish in Prompt 5

Prompt 5 picture: Old Fish is smiling, tiny happy smile, two big black jelly eyes, pale silver-grey, one gear.
Prompt 5 video:
- 0s: Fish smiling, good.
- 2s onward: Fish's mouth turns down into a frown, his eyes turn brown, his water turns bright blue.
- 4.5s: Fish still frowning.

So the video model changes Fish's mouth and water colour over time. Prompt 6 locks both, and adds the same post-generation fix used in Prompts 4 and 5: if Fish frowns in the last frames, use the good smiling frame.

## Image references

- Luna: the uploaded Luna character pic, `workspace/user/media_library/image/LunaChracter.jpeg` — silver-grey fur with shading, large brown-grey jelly eyes, grey ears with bright red inside, dark hematite pendant.
- Wayne: `characters/wayne-character-card.jpeg`
- Old Fish: `characters/old-fish-character-card.webp` — Close-up view.
- Base picture: Prompt 5's approved picture, `day1-test/media-generation-d1-s02-prompt5-luna-true-templ-0-1f07c192-3ead-4f30-935d-8efbb0341dcf.webp` — use this picture exactly, do not regenerate Luna.

## Picture prompt — Prompt 6

> Use Prompt 5's picture exactly as the picture. Do not regenerate Luna, Wayne, Old Fish, the car, the desert, or the door. No leg on the car door.
>
> Old Fish is a large round pale silver-grey robot fish in his bowl, two big black jelly eyes, a tiny happy smile, exactly one tiny brass gear at the base of his tail only. His water is pale, almost clear, not bright blue.
>
> Soft watercolor storybook style, thin brown line art, muted pastel, warm desert light, full frame, no text.

## Video prompt — Prompt 6 (image-to-video, 5 seconds only)

> Animate this exact picture to video, 5 seconds only. This is an image-to-video animation, not a redesign.
>
> Old Fish does not move at all for the whole 5 seconds. His mouth stays a tiny happy smile, upturned, for the whole 5 seconds — do not frown, do not turn his mouth down, do not open his mouth, do not change his smile. His eyes stay two big black jelly eyes, do not turn brown, do not close. His water stays pale, almost clear, not bright blue. He keeps exactly one tiny brass gear at the base of his tail only.
>
> Luna's eyes are open at 0 seconds and stay open for the whole 5 seconds — do not blink, do not shut, do not laugh shut, do not move, do not redraw her eyes. Her eyes stay large soft brown-grey jelly eyes, big white highlights, no pink-red, no dark brown, no thick black eyeliner.
>
> Only Luna's lower mouth moves, in place, opening and closing slightly as if she is talking happily. Her face shape, eye shape and spacing, cheek proportions, nose, blush, fur colour and ears do not change at all. Her fur stays silver-grey with grey shading, not white.
>
> Everything else is completely still for the whole 5 seconds: Wayne does not move, his mouth stays closed and neutral, his eye stays golden-amber, the car, the desert, the background and the camera do not move. No camera pan, no zoom, no lighting change.
>
> Do not add any leg, striped leg, or striped object on the car door. Luna's hind leg stays hidden inside the car.
>
> Soft watercolor storybook style, thin brown line art, muted pastel, warm light, exactly as in the picture.

## After generation — check and fix (part of Prompt 6)

1. Frame-check every 0.5 seconds.
2. If Old Fish frowns, or his water turns bright blue, that frame fails.
3. If Luna's or Wayne's eyes shut in the last frames, use the best 5-second window / freeze the good open-eye smiling frame, as in Prompts 4 and 5.
4. Score with the same rubric (Luna facial 30, Wayne body 25, Wayne facial 15, temporal 15, style 10, costume 5; 90+ approve, 80-89 review, below 80 regenerate), scored against the Luna character pic.

## How to show the improvement later

Compare Prompt 5 corrected (89/100) vs Prompt 6 on the same checks, every 0.5 seconds:
- Old Fish mouth: tiny happy smile, or frown?
- Old Fish eyes: two big black jelly, or brown?
- Old Fish water: pale, or bright blue?
- Luna eyes: open brown-grey, or shut / pink?
- Wayne: still fat (to fix after the frown), eye golden-amber, mouth neutral?
- Leg on the car door: yes, or no?
