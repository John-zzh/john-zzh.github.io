# Zehao Zhou's Academic Homepage

Personal academic website for **Zehao Zhou (周泽浩)**, an AI4S Researcher at Zhongguancun Academy.

Website: https://john-zzh.github.io/

## Introduction

This website is built on the [academic personal website template](https://github.com/senli1073/senli1073.github.io) by [Sen Li](https://github.com/senli1073), which is based on [Bootstrap](https://github.com/StartBootstrap/startbootstrap-new-age).

The template integrates Markdown files as content input. There's no need to compile the webpage before deployment -- upon loading, the Markdown files are automatically parsed and embedded into the page.

LaTeX formula input is supported. Use `$...$` and `\(...\)` for inline math, or `$$...$$` and `\[...\]` for display math. See [MathJax](https://docs.mathjax.org/en/latest/index.html) for more details.

## Project Structure

```
.
├── contents/          # Page content in Markdown & YAML
│   ├── config.yml     # Site title, copyright, etc.
│   ├── home.md        # Home section
│   └── publications.md
├── static/
│   ├── assets/img/    # Background image & photo
│   ├── css/
│   └── js/
└── index.html
```

## How to Update

1. Edit page content in `contents/*.md`.
2. Adjust title, copyright, and other metadata in `contents/config.yml`.
3. Replace images in `static/assets/img/` as needed.
4. Push changes:

```bash
git commit -am 'update content'
git push
```

## License

The original template is by [Sen Li](https://github.com/senli1073/senli1073.github.io), licensed under the [MIT License](LICENSE).
