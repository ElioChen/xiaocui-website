# Xiaocui Zheng — Personal Academic Website

Personal academic website for **Xiaocui Zheng (郑小翠)**, Ph.D. candidate in Chemical Biology at Nanjing University.

**Live site:** https://eliochen.github.io/xiaocui-website/

---

## About

Xiaocui's research focuses on glycoenzyme engineering and precise chemical tools for spatiotemporal control of cell-surface glycan modifications. She is a member of the [Xie Lab](https://www.nju.edu.cn/) at Nanjing University, advised by Prof. Ran Xie.

- ORCID: [0000-0003-4083-4440](https://orcid.org/0000-0003-4083-4440)
- LinkedIn: [郑小翠](https://www.linkedin.com/in/%E5%B0%8F%E7%BF%A0-%E9%83%91-b25149262/)
- Bluesky: [@xiaocuizheng.bsky.social](https://bsky.app/profile/xiaocuizheng.bsky.social)
- Email: zxc20190412@163.com

---

## Tech

Single-page static HTML — no build tools or frameworks required. Deployed via GitHub Pages from the `main` branch root.

- **Font:** Inter (body) + Lora (headings) via Google Fonts
- **Colors:** Teal/navy academic palette
- **Sections:** About · Research · Education · Publications · Awards & Conferences · Contact

---

## File structure

```
xiaocui-website/
├── index.html                      # Main page (edit this to update content)
├── avatar.jpg                      # Profile photo
├── Xiaocui Zheng-CV-20260605.docx  # CV download
└── README.md
```

---

## How to update

All content lives in `index.html`. Common updates:

**Add a new publication** — find the nearest `<div class="pub-year-group">` block and copy a `<div class="pub">` card. Update the year badge if needed.

**Update the CV** — replace `Xiaocui Zheng-CV-20260605.docx` with the new file, then update the filename in the two `href="..."` attributes referencing it in `index.html`.

**Change the profile photo** — replace `avatar.jpg` (keep the same filename, or update the `src` in the `<img class="avatar">` tag).

After any edit, commit and push to deploy:

```bash
git add -A
git commit -m "update: <what changed>"
git push
```

GitHub Pages rebuilds automatically within ~1 minute.

---

## DOI links

The DOI links in the publications section were inferred from journal citation data. Verify each one before sharing:

| Paper | DOI (verify) |
|-------|--------------|
| JACS 2026 (photoactivatable platform) | https://doi.org/10.1021/jacs.5c01298 |
| JACS 2023 (traceless labeling) | https://doi.org/10.1021/jacs.3c08388 |
| ChemBioChem 2023 (review) | https://doi.org/10.1002/cbic.202200778 |
| Angew. 2023 (nanopores) | https://doi.org/10.1002/anie.202216115 |
| Angew. 2023 (proximity labeling) | https://doi.org/10.1002/anie.202407109 |

To correct a DOI, search for `doi.org/` in `index.html` and replace the relevant URL.
