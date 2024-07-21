instalar latex para arch linux

```bash
sudo pacman -S texlive-core texlive-bin texlive-latex texlive-latexrecommended texlive-latexextra
```

y no se muy bien que hace esto pero tienes mas funcionalidades

```bash
sudo fmtutil-sys --all
```

y ejecuta esto para transformarlo en pdf tu archivo .tex desde tu terminar

```bash
pdflatex hola_mundo.tex
```

y es todo lo que tengo
