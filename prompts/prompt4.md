# Prompt 4 — Day 1, Scene S02, Luna's colours locked and corrected after generation

Date: 27 Nov 2026
This is Prompt 4. Prompt 1 is `prompts/prompt1.md` (84/100). Prompt 2 is `prompts/prompt2.md` (56/100). Prompt 3 is `prompts/prompt3.md` (71/100).
Prompt 4 is made because Luna's fur, ear and eye colours are all wrong in Prompt 3's video, and the user asked to upgrade it until it is in the 90 section.

Scene: S02 — Luna leaning from the car window, Mittens ahead, Wayne in the car seat holding Old Fish's bowl. Monument Valley, Day 1.
Test rule: 5 seconds only, one day at a time, only ONE clip per test, then review.

## What went wrong in Prompt 3 — measured

Prompt 1 picture (correct):
- Luna fur forehead: RGB 219, 216, 213 — warm light silver-grey, R > G > B.
- Luna inner ear: bright strawberry-red, saturated, with a white phoenix pattern.
- Luna eyes: pale soft pink-brown jelly, big white highlights, brown, not pink.

Prompt 3 video, frame 5 (2 seconds):
- Luna fur forehead: RGB 209, 200, 205 — cool lavender-grey, B > G, warm grey lost.
- Luna inner ear: pale pink, washed out, strawberry-red saturation lost.
- Luna eyes: pink-red, not pale brown, smaller highlights.
- At 4.5s Luna, Wayne and Old Fish all laugh with eyes shut, again.

So the video model cools the picture, desaturates the reds, and shifts warm grey to lavender. A text prompt alone has not stopped this in Prompts 1-3. Prompt 4 therefore does two things: a stronger colour lock in the prompt, AND a colour correction after generation, back to the picture.

## Colour lock — exact, warm, do not cool

- Luna fur: warm light silver-grey, RGB 219, 216, 213. R > G > B. Warm, not lavender, not cool blue-grey, not pure white, not dark grey.
- Luna inner ear: bright strawberry-red, saturated red, RGB about 200, 80, 70, with a white phoenix pattern. Not pale pink, not paisley, not washed out.
- Luna eyes: pale soft pink-brown jelly, brown, RGB about 190, 150, 130 in the iris, big white highlights. Not pink-red, not dark brown, no black lashes, no almond shape.
- Wayne eye: golden-amber, not pink.
- Old Fish: pale silver-grey, RGB 195, 202, 205, two big black jelly eyes, one tiny brass gear at the base of his tail only.
- Wayne: chubby white cat, still pending — make him not so fat, back to template chubbiness, not slim.

## Image references (always use the actual cards, never text alone)

- `characters/luna-character-card.jpeg`
- `characters/wayne-character-card.jpeg`
- `characters/old-fish-character-card.webp`
- Base picture: Prompt 1's approved picture, `day1-test/media-generation-d1-s02-still-luna-light-fish-k-0-338a9af7-b159-4898-9a51-c1dca9a63d75.webp` — use this picture exactly, do not regenerate Luna.

## Picture prompt — Prompt 4

> Use Prompt 1's approved picture exactly as the picture. Do not regenerate Luna, do not change her face, eyes, fur, ears, pendant or scarf. Do not change Old Fish, Wayne, the car, the desert, or the door. No leg on the car door.
>
> Luna's fur is warm light silver-grey, RGB 219, 216, 213. Her inner ears are bright strawberry-red, saturated. Her eyes are pale soft pink-brown jelly. Her pendant is a tiny dark hematite teardrop.
>
> Soft watercolor storybook style, thin brown line art, muted pastel, warm desert light, full frame, no text.

## Video prompt — Prompt 4 (image-to-video, 5 seconds only)

> Animate this exact picture to video, 5 seconds only. This is an image-to-video animation, not a redesign.
>
> Warm desert light only — do not cool the picture, do not add a lavender or blue tint, do not desaturate the reds.
>
> Luna's eyes are open at 0 seconds and stay open for the whole 5 seconds — do not blink, do not shut, do not laugh shut, do not move, do not redraw her eyes. Her eyes stay pale soft pink-brown jelly, brown not pink-red, big white highlights, no dark brown irises, no black lashes.
>
> Only Luna's lower mouth moves, in place, opening and closing slightly as if she is talking happily. Her face shape, eye shape and spacing, cheek proportions, nose, blush, fur colour and ears do not change at all.
>
> Luna's fur stays warm light silver-grey, RGB 219, 216, 213, R > G > B. Do not make it white, lavender, cool grey, or dark grey. Her inner ears stay bright strawberry-red, saturated, not pale pink. Her eyes stay pale brown, not pink-red.
>
> Everything else is completely still for the whole 5 seconds: Wayne does not move, his mouth stays closed and neutral, his eye stays golden-amber, Old Fish does not move and keeps exactly one gear, the car, the desert, the background and the camera do not move. No camera pan, no zoom, no lighting change.
>
> Old Fish stays pale silver-grey, RGB 195, 202, 205, large round robot fish, two big black jelly eyes, one brass gear at the base of his tail only. Do not add any leg, striped leg, or striped object on the car door. Luna's hind leg stays hidden inside the car.
>
> Soft watercolor storybook style, thin brown line art, muted pastel, warm light, exactly as in the picture.

## After generation — colour correction and selection (this is part of Prompt 4, not optional)

1. Frame-check every 0.5 seconds.
2. If Luna's fur has gone lavender (B > G) or white, warm it back to the picture: increase red, decrease blue, until fur is RGB about 219, 216, 213 again.
3. If Luna's inner ears have gone pale pink, restore the strawberry-red saturation.
4. If Luna's eyes have gone pink-red or dark brown, or closed, that frame fails.
5. If the last frames laugh shut, use the best 5-second window where eyes are open — like the earlier 91/100 eyes-frozen test, which was trimmed from a longer generation.
6. Score with the same rubric (Luna facial 30, Wayne body 25, Wayne facial 15, temporal 15, style 10, costume 5; 90+ approve, 80-89 review, below 80 regenerate). Keep upgrading Prompt 4 until it is 90+ — do not show a below-90 clip as a pass.

## How to show the improvement later

Compare Prompt 1 (84/100) vs Prompt 2 (56/100) vs Prompt 3 (71/100) vs Prompt 4 on the same checks, every 0.5 seconds:
- Luna fur: RGB vs the picture, warm or lavender/white?
- Luna ear: bright strawberry-red, or pale pink?
- Luna eye: pale brown, or pink-red / dark brown / shut?
- Wayne eye: golden-amber, or pink?
- Old Fish: one gear, pale silver-grey, or bright blue / two gears?
- Leg on the car door: yes, or no?
