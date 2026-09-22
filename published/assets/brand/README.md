# Brand assets

## Logo exports

Generated September 22, 2026 from the master file
`Bellas_Mountain_Vacation_Cleaning_Logo-e1784044119669-1536x1511.png`
(1536 x 1511, black on white, opaque).

**Why these exist:** the master file is **1.01 MB**, which is just over the 1 MB ceiling
that many platforms enforce on profile images. It cannot be uploaded anywhere with that
limit. These exports are all well under it.

### Two forms

| Form | What it is | Use it for |
|---|---|---|
| **mark** | The circular mountain emblem alone, no words | Avatars, favicons, app icons, anywhere the business name already appears next to it |
| **lockup** | The emblem plus "Bellas Mountain Vacation Cleaning" in two lines | Business profiles, directory listings, anywhere the name is not shown beside the image |

**Note on the mark at small sizes:** the river tapers out of the bottom of the circle, so
the mark is bottom-heavy by design. The 150 version carries a 5 percent margin so the tail
does not touch the frame.

**Note on the lockup at 150:** the two text lines land around 13 px tall. They are legible
but tight. If a platform renders the image smaller than it claims, prefer the mark version.

### Files

| File | Size | Dimensions |
|---|---|---|
| `bmvc-logo-mark-150.png` | 25 KB | 150 x 150 |
| `bmvc-logo-lockup-150.png` | 27 KB | 150 x 150 |
| `bmvc-logo-mark-300.png` | 70 KB | 300 x 300 |
| `bmvc-logo-lockup-300.png` | 73 KB | 300 x 300 |
| `bmvc-logo-mark-800.png` | 338 KB | 800 x 800 |
| `bmvc-logo-lockup-800.png` | 334 KB | 800 x 800 |

All PNG, RGB flattened onto white, LANCZOS resampled. No transparency, so no platform can
render the black wordmark on a black background.

### Canonical name check

**The logo is correct.** It reads "Bellas Mountain **Vacation** Cleaning" with **no
apostrophe**, which matches the canonical name rule. Verified September 22, 2026.

Note: a separate Mary Poppins themed ad graphic circulates with "Bella's" (apostrophe) in
both the headline and the logo lockup. That asset is being retired. The logo files in this
folder are unaffected and are the source of truth.

### Regenerating

The script that produced these lives in the private vault at
`pre-publish/live-posts/make_logo_final.py`. It uses measured pixel bounds for the circle
(x 246-1289, y 120-1172) and the full lockup (x 198-1339, y 127-1407), so it is
reproducible if the master ever changes.
