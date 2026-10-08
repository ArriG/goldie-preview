# Goldie v5 image credits

All stock photos come from **Pexels** under the [Pexels License](https://www.pexels.com/license/):
- Free for commercial use.
- No attribution required (credit is appreciated).
- Restrictions:
  - Don't sell unaltered copies.
  - Don't imply that identifiable people endorse Goldie.
  - Don't show people in a bad light.
  - Don't use trademarks shown in a photo.

Each file was downloaded from the Pexels CDN (images.pexels.com) into `img/`, then resized and saved as WebP with Pillow. Nothing is hotlinked.

**Photographer names.** Pexels photo pages block automated fetching (Cloudflare), so I couldn't confirm every name on its page. Each name below is marked with where it came from:
- *page*: shown in the Pexels page text returned by search.
- *index*: a search-engine summary only.
- *EXIF*: the Artist tag embedded in the downloaded file.

Please check any name not marked *page* before publishing visible credits.

| File | Used in | Pexels page | Photographer | Licence |
|---|---|---|---|---|
| `img/hero-chair.webp` (2200×1466, 171 KB) | Hero, full-bleed | https://www.pexels.com/photo/view-of-clinic-305568/ | Daniel Frank (*index*) | Pexels License |
| `img/leak-reviews.webp` (1800×1200, 121 KB) | Leak 02, 97% reviews | https://www.pexels.com/photo/smiling-patient-at-dentist-5622014/ | Gustavo Fring (*index*); EXIF artist "FaustFoto" | Pexels License |
| `img/leak-calls.webp` (1200×1800, 71 KB) | Leak 04, 42hrs slow replies | https://www.pexels.com/photo/close-up-shot-of-a-person-holding-a-cellphone-7120126/ | cottonbro studio (*index*) | Pexels License |
| `img/leak-consult.webp` (1800×1200, 157 KB) | Leak 05, 54% consults | https://www.pexels.com/photo/young-woman-sitting-in-dentist-chair-4971499/ | EXIF artist "FaustFoto"; check the Pexels account name | Pexels License |
| `img/reception.webp` (1800×1718, 152 KB) | Leak 03, 62% missed calls | https://www.pexels.com/photo/the-woman-in-the-reception-counter-is-talking-to-a-man-in-white-long-sleeves-6812427/ | Pavel Danilyuk (*page*) | Pexels License. Reused from v3; cropped to the left 70% so the clinic's wall logo isn't shown. |
| `img/aligners.webp` (1200×1800, 101 KB) | Pilot intro | https://www.pexels.com/photo/hands-of-a-person-holding-clear-retainers-and-teeth-mould-13207280/ | Not confirmed; check on page | Pexels License |

## Unsplash photos (from Ari's Claude artifact)

These are free to use under the [Unsplash License](https://unsplash.com/license): commercial use is fine and no attribution is required. They're credited here anyway, using the photographers named in the artifact's footer. All three files were converted from the artifact's captured JPGs (`/workspace/claude-artifact/saved/img/`) to WebP. Nothing new was downloaded.

| File | Used in | Unsplash page | Photographer | Licence |
|---|---|---|---|---|
| `img/busy-team.webp` (1200×1500, 175 KB) | "Your team isn't the leak." | https://unsplash.com/photos/woman-in-blue-denim-jacket-sitting-on-chair-diuh-gxaL64 | Nate Johnston | Unsplash License |
| `img/consult.webp` (1400×1050, 69 KB) | Leak 06, 70% sales training | https://unsplash.com/photos/man-in-white-dress-shirt-sitting-beside-woman-in-black-long-sleeve-shirt-uqveD8dYPUM | Caroline LM | Unsplash License |
| `img/full-chair.webp` (1200×1800, 181 KB) | "Where is your practice leaking?" ("Back in the chair.") | https://unsplash.com/photos/a-woman-standing-next-to-a-person-in-a-hospital-bed-tU51A2WWwxw | Ozkan Guner | Unsplash License |

The artifact's footer lists four photographers without saying which credit belongs to which file. I matched each file to a credit using the page titles: "woman in blue denim jacket sitting on chair" is the dentist mid-treatment, "a woman standing next to a person in a hospital bed" is the laughing dentist next to the patient, and "man in white dress shirt sitting beside woman in black long sleeve shirt" is `consult.webp` (the artifact's `consult.jpg`).

## Original mockup (not a photo)

| File | Used in | What it is |
|---|---|---|
| `img/leak-website.webp` (1200×1500, 41 KB) | Leak 01, Website | An original HTML/CSS mockup made for this page and rendered to an image with Playwright. Source: `v5/mockup/leak-website.html` (not deployed). A phone shows a half-loaded, unbranded dental clinic page (grey placeholder blocks, a spinner, "Loading…", a progress bar stuck at about a third) with a back-swipe gesture leaving it. There's no clinic name, URL, logo or claim. The blurred background is the Pexels photo `woman-apple-iphone-smartphone-4009363` by Anna Avilova (*EXIF*, Pexels License), darkened and blurred. It isn't a real website or a real user's session. |

## Goldie's own photos (not stock)

These are reused from v2 (`v2/assets/`), originally from getgoldie.ai, and converted to WebP:

| File | Used in |
|---|---|
| `img/practi-uk-team.webp` | Founder collage. Ari with the Practi UK team. |
| `img/practi-dentistry-show.webp` | Founder collage. Ari and colleagues at a dentistry show. |
| `img/practi-team-dentistry-show.webp` | Founder collage. Ari and colleagues at the Practi stand. |

Before publishing, confirm that Ari has permission to use these photos, which show Practi colleagues and Practi branding.

## Notes

- The people in the stock photos are models in stock shoots. The page doesn't present them as Goldie clients or patients, and none of them has a quote or result attached.
- The leak 01 image is a mockup, not a photo of a real website, and is labelled as an illustration in its alt text.
- The three notification cards in "Your team isn't the leak." are HTML, not part of the photo.
