

![Github Forks](https://img.shields.io/github/forks/senli1073/academic-homepage-template?style=flat)
![Github Stars](https://img.shields.io/github/stars/senli1073/academic-homepage-template?style=flat)
![License](https://img.shields.io/github/license/senli1073/academic-homepage-template)
![Last Commit](https://img.shields.io/github/last-commit/senli1073/academic-homepage-template)

# A simple Github Pages template for personal academic websites.

> ⚠️ SECURITY NOTICE (2026-06)
> 
> Older versions of this template include a polyfill.io dependency
> which may cause malicious popups.
>
> Please update to the latest version immediately.

## Preview
[![Screenshot of the Website](https://raw.githubusercontent.com/senli1073/academic-homepage-template/main/screenshot_full.png)](https://senli1073.github.io/)


## Introduction

This personal academic website template is based on [startbootstrap](https://github.com/StartBootstrap/startbootstrap-new-age).

The template is designed to integrate Markdown files as content input.  There's no need to compile the webpage before deployment.  Upon loading, the Markdown files are automatically parsed and embedded into the page.

The homepage sections and navigation bar are configured in `contents/config.yml`. Each section loads its body from a matching Markdown file in `contents/`, such as `contents/publications.md`.

The top background supports multiple images. Add images under `static/assets/background/`, list them in `contents/config.yml`, and the page will pick a random first image on refresh before rotating through the list.

This template supports LaTeX formula input. You can use `$...$` and `\(...\)` as delimiters for inline-math, or use `$$...$$` and `\[...\]` as delimiters for display-math. Macros such as `\ref{...}`, `\eqref{...}`, and `\begin{equation}...\end{equation}` are also supported. See [MathJax](https://docs.mathjax.org/en/latest/index.html) for more details.

:milky_way: Demo: https://senli1073.github.io/

## License

Copyright Sen Li, 2023-2025. Licensed under an MIT license. You can copy and mess with this template.
