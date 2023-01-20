# Website for JHU Biostat Journal/Computing Club 2022-2023

1. [Install Hugo](https://gohugo.io/installation/).
2. Clone repo to your computer.
3. Modify main page in `content/_index.md` and styling in `themes/hugo-bearblog/layouts/partials/style.html`. The site title is in `config.toml`. Any static files like pdfs or other html pages should be in the `static` folder and can be referenced by the path _from the static directory_, e.g. to access `/static/images/myimage.png`, you would use `/images/myimage.png` in the markdown or html.
4. Run `hugo server` from the top level directory to host locally.