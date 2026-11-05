# lunarradiomapchallenge.github.io

Website for **The First Lunar Pathloss Radio Map Prediction Challenge** (IEEE ICASSP 2027 Signal
Processing Grand Challenge).

Live at <https://lunarradiomapchallenge.github.io/>.

## Structure

Static HTML, no build step. GitHub Pages serves `main` from the repository root.

| File | Page |
| --- | --- |
| `index.html` | Home / Call for Participation |
| `dataset.html` | Dataset & Instructions |
| `timeline.html` | Timeline |
| `registration.html` | Registration |
| `results.html` | Results (placeholder + commented-out ranking table) |
| `assets/` | CSS, JS, webfonts (ZeroFour by HTML5 UP) |
| `images/header.jpg` | Banner background, referenced from `assets/css/main.css` |

## Editing

Edit the HTML directly and push to `main`; Pages redeploys in a minute or so. The nav block and the
footer are duplicated in every page, so update all of them together.

Dates appear in `timeline.html`, `registration.html` (registration deadline), and two places in
`index.html` (the intro and the paragraph above Organizers). Change them together.

Placeholders still to fill in:

- remaining TBD dates in `timeline.html`

Final submission rules (emailed to the organizers, evaluated off Kaggle) are in the Final Submission
section of `dataset.html`.

Kaggle links use the invite URL (`kaggle.com/t/...`), and the plain competition URL can return 404
to visitors who have not joined.

## Evaluation metric

The ranking metric is **RMSE in dB over valid (ray-traced) pixels only**; gap-filled pixels are
excluded. This is documented in `index.html` (Evaluation Criteria), `dataset.html` (Validity Masks
and Scoring) and the commented ranking-table template in `results.html`. If the metric ever changes
again, those three places must move together.

## Credits

Template: [ZeroFour by HTML5 UP](https://html5up.net) (CCA 3.0, see `README.txt` and `LICENSE.txt`).
