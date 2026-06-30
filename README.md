# TrustCLIP

Project page for **TrustCLIP: Learning Private Visual Features via Adversarial Reconstruction** (ECCV 2026).

🔗 Live page (once published): https://atnikos.github.io/trustclip/

This is a static site (plain HTML/CSS, no build step) intended for GitHub Pages.

## Structure

```
.
├── index.html              # project page
└── static/
    ├── css/style.css       # styles
    └── images/teaser.png   # teaser figure (from the paper)
```

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Publish on GitHub Pages

1. Create a GitHub repo named `trustclip` and push this folder.
2. In **Settings → Pages**, set the source to the `main` branch, root (`/`).
3. The site will be served at `https://<user>.github.io/trustclip/`.

## TODO before release

- Replace the placeholder `#` links in `index.html` (Paper, arXiv, Code) with real URLs.
- Confirm author ORCIDs / affiliations.
- Optionally add qualitative result galleries and a video.

## Citation

```bibtex
@inproceedings{athanasiou2026trustclip,
  title     = {TrustCLIP: Learning Private Visual Features via Adversarial Reconstruction},
  author    = {Athanasiou, Nikos and Petrov, Ilya A. and Yao, Angela and Ma, Shugao
               and Sauser, Eric and Remelli, Edoardo and Hampali, Shreyas
               and Sch{\"o}nberger, Johannes and Sener, Fadime and Tekin, Bugra},
  booktitle = {European Conference on Computer Vision (ECCV)},
  year      = {2026}
}
```
