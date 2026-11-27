# Day 1, Scene S02 — Approved prompts

Date: 27 Nov 2026
Scene: S02 — Luna leaning from the car window, Mittens ahead, Wayne in the car seat holding Old Fish's bowl. Monument Valley, Day 1.
Test rule: 5 seconds only, one day at a time, only ONE clip per test, then review.

Approved still (local):
`day1-test/media-generation-d1-s02-still-luna-light-fish-k-0-338a9af7-b159-4898-9a51-c1dca9a63d75.webp`

Approved video (local, exactly 5.000 seconds):
`day1-test/media-generation-d1-s02-approved-light-fish-eye-0-cb6de792-1c65-4632-a0a4-c36b7e8afc32.mp4`
Score: 84/100 — review-and-correct. Luna fur and Old Fish colour held, no leg on the door, eyes pale in frames 2-10. Faults: Luna's eyes are shut at 0s, Wayne smiles at 4.5s.

## Colour lock (measured, do not change)

- Luna fur: light pale silver-grey, about RGB 219, 216, 213 on her forehead. Very light, almost white with soft grey shading. White only on chest, belly and muzzle. Do NOT make it dark grey — a fix at RGB 175, 167, 164 was too dark and was corrected by the user.
- Old Fish: pale silver-grey, about RGB 195, 202, 205. Large round robot fish, two big black jelly eyes, tiny smile, one tiny brass gear at the base of his tail only. No other gears, no brown patch, no bright blue.
- Wayne: chubby white cat, one brown eyepatch over his right eye, open golden-amber eye, small neutral mouth, pale gold swirl on his back only, red Christmas scarf. User, 27 Nov 2026: make Wayne not so fat — in the S02 still he is fatter than the template, a huge wide blob. Make him narrower, back to template chubbiness, not slim. This was still pending after the video below.

## Image references (always use the actual cards, never text alone)

- `characters/luna-character-card.jpeg`
- `characters/wayne-character-card.jpeg`
- `characters/old-fish-character-card.webp` — Old Fish must be copied exactly from the Close-up view: large round pale silver-grey robot fish, two big black jelly eyes, tiny smile, one brass gear at the base of his tail only.

## Picture prompt — the exact steps that produced the approved picture

The approved still was made in three edits, in order. Keep the car, desert, Wayne and composition exactly the same in each edit.

### Step 1 — Fix Luna's grey, fix Old Fish, remove the leg

Base: leg/gear-fixed S02 still + Luna card + Old Fish card.

> Edit only this still, keep the car, desert, Wayne and composition exactly the same. Three corrections only, from the template cards.
>
> 1. Luna fur is GRAY, not white. Copy the Luna template: medium silver-grey fur all over her head, ears, body and arms, with darker grey shading. White only on her chest, belly and muzzle. Do not make her white. Her ears hang down, strawberry-red inner ears, pale pink-brown jelly eyes, tiny hematite pendant.
>
> 2. Old Fish must be copied exactly from the Close-up view on the Fish template card. Large, round, pale silver-grey metal robot fish filling most of his bowl, two big black jelly eyes, tiny happy smile, small side fins, one tiny brass gear at the base of his tail only. No other gears, no brown patch on his head, no bright blue colour, no small cartoon tropical fish shape. He is silver-grey, not blue.
>
> 3. Remove Luna's leg completely. There is no striped leg on the car door and no striped object in the door pocket. Luna's hind leg is hidden inside the car and is not visible in this scene. Do not draw any leg, any striped leg, or any striped object on the door.
>
> Soft watercolor storybook style, thin brown line art, muted pastel, full frame, no text.

Note: Step 1 made Luna's fur too dark (RGB 175, 167, 164). Step 2 corrected that.

### Step 2 — Put Luna's fur back to light (Old Fish stays)

Base: Step 1 still + leg/gear-fixed still.

> Edit only Luna's fur colour in this still. Keep everything else exactly the same — do not change Old Fish at all, do not change Wayne, the car, the desert, Luna's face, ears, eyes, pendant or scarf, and do not add any leg on the car door.
>
> Old Fish stays exactly as he is in this image: large round pale silver-grey robot fish, two big black jelly eyes, one brass gear at the base of his tail only.
>
> Luna's fur: change it back from dark grey to the light pale silver-grey in the second reference image. Her forehead and body fur should be about RGB 222, 215, 213 — very light silver-grey, almost white but with soft grey shading, not dark grey, not medium grey. White only on her chest, belly and muzzle. Her ears hang down, strawberry-red inner ears.
>
> Soft watercolor storybook style, thin brown line art, muted pastel, full frame, no text.

### Step 3 — Remove the striped object that came back in the door pocket

Base: Step 2 still.

> Remove only the small red-orange-white striped object in the car door pocket at the bottom centre, just left of Wayne. Fill that pocket with plain beige car door, exactly like the rest of the door. Do not change anything else — Luna's light pale silver-grey fur stays exactly as it is, Old Fish stays exactly as he is, Wayne, the car, the desert, Luna's face, ears, eyes and pendant stay exactly the same. No leg, no striped object, no foot in the door pocket. Soft watercolor storybook style, thin brown line art, muted pastel, full frame, no text.

## Video prompt — exact prompt used for the approved 5-second clip

Base image: the approved still above, image-to-video only.

> Animate this exact still image to video, 5 seconds only. This is an image-to-video animation, not a redesign.
>
> Freeze everything except Luna's mouth. Luna's eyes are completely frozen — do not blink, do not move, do not redraw her eyes. Her eyes stay pale soft pink-brown jelly eyes, big white highlights, no dark brown irises, no black lashes. Only her mouth opens and closes slightly, as if she is talking happily.
>
> Everything else is completely still: Wayne does not move, Old Fish does not move, the car, the desert, the background and the camera do not move. No camera pan, no zoom, no lighting change.
>
> Keep all colours exactly as in the first frame. Luna's fur stays light pale silver-grey, about RGB 219, 216, 213 — do not make it white, do not make it dark grey. Old Fish stays pale silver-grey, about RGB 195, 202, 205, large round robot fish, two big black jelly eyes, one brass gear at the base of his tail only. Do not change Old Fish's shape, colour, eyes or gears. Do not add any leg, striped leg, or striped object on the car door. Luna's hind leg stays hidden inside the car.
>
> Soft watercolor storybook style, thin brown line art, muted pastel, exactly as in the still.

## Workflow rules that apply to this clip

- Correct and approve the static starting scene before generating any animation.
- Eyes frozen in tests: mouth only, no blink.
- Frame-check every 0.5 seconds. Score per rubric: Luna facial 30, Wayne body 25, Wayne facial 15, temporal 15, style 10, costume 5. 90+ approve, 80-89 review and correct, below 80 regenerate.
- Reuse the same approved assets for every episode. Do not use the final frame of a generated video as the only reference for the next clip.
