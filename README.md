# Manual

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

## How to build this documentation

In order to make HTML, PDF and ePub files from the source code (`.adoc` files), folow these steps:

- Install [asciidoctor](https://asciidoctor.org), [asciidoctor PDF](https://asciidoctor.org/docs/asciidoctor-pdf/) and [asciidoctor EPUB3](https://asciidoctor.org/docs/asciidoctor-epub3/)

- Run on the shell commands like these (adjusting paths as needed):

      asciidoctor -a '!notitle' -a toc=left -a author=ES -a "email=${fecha}" -o ".../manual_es.html" "Manual de neptUNO+.adoc"

      asciidoctor-pdf -a pdf-theme=style.yml -a pdf-themesdir="${mypath}/.." -o ".../Manual de neptUNO+.pdf" "Manual de neptUNO+.adoc"

      asciidoctor-epub3 -o ".../Manual de neptUNO+.epub" "Manual de neptUNO+.adoc"

---

## Construcción de esta documentación

Para poder generar desde el código fuente (archivos `.adoc`), ficheros PDF y ePub, se han de seguir estos pasos (ajustando las rutas a directorios y ficheros según sea necesario):

- Instalar [asciidoctor](https://asciidoctor.org), [asciidoctor PDF](https://asciidoctor.org/docs/asciidoctor-pdf/) y [asciidoctor EPUB3](https://asciidoctor.org/docs/asciidoctor-epub3/)

- Ejecutar unos comandos similares a los siguientes

      asciidoctor -a '!notitle' -a toc=left -a author=ES -a "email=${fecha}" -o ".../manual_es.html" "Manual de neptUNO+.adoc"

      asciidoctor-pdf -a pdf-theme=style.yml -a pdf-themesdir="${mypath}/.." -o ".../Manual de neptUNO+.pdf" "Manual de neptUNO+.adoc"

      asciidoctor-epub3 -o ".../Manual de neptUNO+.epub" "Manual de neptUNO+.adoc"

---

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
