# josefbengtson.github.io

Personal website of Josef Bengtson, built on Keunhong Park's
[template](https://github.com/keunhong/keunhong.github.io) (Jekyll + Tailwind).

## Editing
- Bio, email, Scholar ID: `_config.yml`
- Papers: `_data/publications.yml` (authors are keys into `_data/authors.yml`)
- Top cards: `_data/highlights.yml`
- CV page: `_data/cv.yml` (mirrors the PDF CV in `CV/Josef_CV_2026/main.tex`)
- Images and hover videos: `images/` (square, e.g. 600×600; `.mp4` for `image_mouseover` / `video`)
- PDF CV: `files/Josef_Bengtson_CV.pdf`

## Deploying
Push to a repo named `josefbengtson.github.io`, then set Settings → Pages → Source to
**GitHub Actions**. `.github/workflows/jekyll.yml` builds and deploys on every push to `main`.

Local preview (needs Ruby ≥ 3.1 with dev headers): `bundle install && bundle exec jekyll serve`.

# License
Template by Keunhong Park, licensed under
[CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).
