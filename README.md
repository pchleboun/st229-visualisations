# ST229 visualisations

Interactive visualisations for Warwick's **ST229 Probability for Mathematical Statistics**.

Live site: https://pchleboun.github.io/st229-visualisations/

| Visualisation | Notes | Folder |
| --- | --- | --- |
| Reversal of correlation in a Gaussian model | Chapter 5 | [`gaussian-conditioning/`](gaussian-conditioning/) |
| Fisher's Sampling Theorem: the proof as a rotation | Section 7.4 | [`fisher-sampling-theorem/`](fisher-sampling-theorem/) |

## Layout

Each visualisation is a single self-contained `index.html` in its own folder. The `index.html` at the root is the list students land on.

## Adding a visualisation

1. Create a folder with a short lower-case name, and put the page in it as `index.html`.
2. Add an entry to the list in the root `index.html` and a row to the table above.
3. Commit to `main`. GitHub Pages republishes within a minute or so.

## Publishing

Under **Settings → Pages**, choose **Deploy from a branch**, the `main` branch and the **/ (root)** folder.

## Notes

- The Fisher page loads its equation typesetting (MathJax) and fonts from public CDNs, so it needs an internet connection. The Gaussian conditioning page works offline.
