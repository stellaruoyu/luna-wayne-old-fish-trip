# Prompt 3 — Day 1, Scene S02, Luna's eyes and fur locked

Date: 27 Nov 2026
This is Prompt 3. Prompt 1 is `prompts/prompt1.md` (84/100). Prompt 2 is `prompts/prompt2.md` (56/100 — picture better for Old Fish, video worse).
Prompt 3 is made because Luna's eyes and fur colour are still drifting in the videos.

Scene: S02 — Luna leaning from the car window, Mittens ahead, Wayne in the car seat holding Old Fish's bowl. Monument Valley, Day 1.
Test rule: 5 seconds only, one day at a time, only ONE clip per test, then review.

## What Prompt 3 fixes, compared to Prompt 1 and Prompt 2

1. **Luna's eyes — drifting.** Prompt 1: eyes shut at 0s. Prompt 2: eyes open at 0s, then both Luna and Wayne laugh with eyes shut at 4.5s, and Luna's eyes turn dark brown in earlier tests when she blinks. Prompt 3 locks her eyes to the picture: pale soft pink-brown jelly eyes, big white highlights, no dark brown irises, no black lashes, no closing, no laughing shut. Eyes are open at 0s and stay open for the whole 5 seconds.
2. **Luna's fur — drifting.** In video her light pale silver-grey fur washes out to white, or goes lavender. Prompt 3 locks her fur colour to the picture with an exact RGB value, and adds a post-generation colour check: if the video fur is whiter or more lavender than the picture, correct it back to the picture before showing it.
3. **Wayne's eye — drifting in Prompt 2.** His golden-amber eye turned pink at 2s in Prompt 2. Prompt 3 locks it: golden-amber, not pink, not brown.
4. **Old Fish's gears — drifting in Prompt 2.** He grew a second gear in Prompt 2. Prompt 3 locks it: exactly one tiny brass gear at the base of his tail only.
5. **Luna's pendant and inner ears — lost in Prompt 2.** Her hematite teardrop pendant became a bell, and her strawberry-red inner ears became paisley. Prompt 3 restores them from Prompt 1's picture: tiny dark hematite teardrop pendant, strawberry-red inner ears with a phoenix pattern.
6. **Picture — do not regenerate Luna.** Prompt 2's fresh picture changed Luna's ears, pendant and Wayne's size. Prompt 3 uses Prompt 1's approved picture as the base picture, unchanged. Only the video prompt changes.

## Colour lock (measured, do not change)

- Luna fur: light pale silver-grey, about RGB 219, 216, 213 on her forehead. Very light, almost white with soft grey shading, not pure white, not lavender, not dark grey (RGB 175 was too dark). White only on chest, belly and muzzle.
- Luna eyes: pale soft pink-brown jelly, big white highlights. No dark brown irises, no black lashes, no almond / slanted shape.
- Wayne eye: golden-amber, about RGB 200, 150, 60. Not pink, not brown.
- Old Fish: pale silver-grey, about RGB 195, 202, 205. Large round robot fish, two big black jelly eyes, tiny smile, one tiny brass gear at the base of his tail only.
- Wayne: chubby white cat, still pending — make him not so fat, back to template chubbiness, not slim. Body about 1.5x his head wide, not 2x.

## Image references (always use the actual cards, never text alone)

- `characters/luna-character-card.jpeg`
- `characters/wayne-character-card.jpeg`
- `characters/old-fish-character-card.webp`
- Base picture: Prompt 1's approved picture, `day1-test/media-generation-d1-s02-still-luna-light-fish-k-0-338a9af7-b159-4898-9a51-c1dca9a63d75.webp` — use this picture exactly, do not regenerate Luna.

## Picture prompt — Prompt 3

> Use Prompt 1's approved picture exactly as the picture. Do not regenerate Luna, do not change her face, eyes, fur, ears, pendant or scarf. Do not change Old Fish, Wayne, the car, the desert, or the door. No leg on the car door.
>
> If any detail must be restored, restore only these two from the template cards: Luna's tiny dark hematite teardrop pendant (not a bell), and her strawberry-red inner ears with a phoenix pattern (not paisley).
>
> Soft watercolor storybook style, thin brown line art, muted pastel, full frame, no text.

## Video prompt — Prompt 3 (image-to-video, 5 seconds only)

> Animate this exact picture to video, 5 seconds only. This is an image-to-video animation, not a redesign.
>
> Luna's eyes are open at 0 seconds and stay open for the whole 5 seconds — do not blink, do not shut, do not laugh shut, do not move, do not redraw her eyes. Her eyes stay pale soft pink-brown jelly eyes, big white highlights, no dark brown irises, no black lashes, no almond shape.
>
> Only Luna's lower mouth moves, in place, opening and closing slightly as if she is talking happily. Her face shape, eye shape and spacing, cheek proportions, nose, blush, fur colour and ears do not change at all. Nothing else about her face changes.
>
> Everything else is completely still for the whole 5 seconds: Wayne does not move, his mouth stays closed and neutral, his eye stays golden-amber and does not turn pink, Old Fish does not move and keeps exactly one gear, the car, the desert, the background and the camera do not move. No camera pan, no zoom, no lighting change.
>
> Keep all colours exactly as in the first frame. Luna's fur stays light pale silver-grey, about RGB 219, 216, 213 — do not make it white, do not make it lavender, do not make it dark grey. Old Fish stays pale silver-grey, about RGB 195, 202, 205, large round robot fish, two big black jelly eyes, one brass gear at the base of his tail only. Do not add any leg, striped leg, or striped object on the car door. Luna's hind leg stays hidden inside the car.
>
> Soft watercolor storybook style, thin brown line art, muted pastel, exactly as in the picture.

## After generation — colour check (do this before showing the clip)

- Frame-check every 0.5 seconds.
- If Luna's fur is whiter than RGB 219, 216, 213, or more lavender, or if her eyes have turned dark brown or closed, or if Wayne's eye has turned pink, the clip fails — do not show it as a pass.
- If Old Fish has turned bright blue or grown a second gear, correct the colour back to the picture, or regenerate.
- Score with the same rubric (Luna facial 30, Wayne body 25, Wayne facial 15, temporal 15, style 10, costume 5; 90+ approve, 80-89 review, below 80 regenerate).

## How to show the improvement later

Compare Prompt 1 (84/100) vs Prompt 2 (56/100) vs Prompt 3 on the same checks, every 0.5 seconds:
- Luna's eyes at 0s and 4.5s: open, or shut?
- Luna's eyes colour: pale pink-brown, or dark brown?
- Luna's fur: RGB vs the picture, white / lavender drift?
- Wayne's eye: golden-amber, or pink?
- Old Fish: one gear, or two? Pale silver-grey, or bright blue?
- Leg on the car door: yes, or no?
