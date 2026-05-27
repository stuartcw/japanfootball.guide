# Japan Football Guide

Source for [japanfootball.guide](https://japanfootball.guide/) — an in-progress guide to supporting football in Japan in and from overseas.

## Contributing

Content lives in the `docs/` folder as Markdown files. Edit them directly on GitHub or clone and submit a pull request.

Report issues or suggestions at the [issue tracker](https://github.com/stuartcw/japanfootball.guide/issues/new).

## Building locally

Install [Zensical](https://zensical.org/) and run:

```sh
pip install zensical
zensical serve
```

The site will be available at `http://localhost:8000`.

## Deployment

Pushes to `main` automatically build and deploy to GitHub Pages via the workflow in `.github/workflows/docs.yml`.
