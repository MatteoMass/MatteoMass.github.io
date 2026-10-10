# CV

Basato sul template LaTeX [Awesome-CV](https://github.com/posquit0/Awesome-CV) di posquit0
(commit `6701180`, licenza LPPL v1.3c — vedi `LICENCE`).

## Struttura

- `awesome-cv.cls` — classe del template (stile, colori, comandi)
- `cv.tex` + `cv/` — CV completo (una sezione per file)
- `resume.tex` + `resume/` — versione breve (resume)
- `coverletter.tex` — lettera di presentazione
- `profile.png` — foto profilo (usata con `\photo`)

## Compilazione

Richiede una distribuzione TeX con LuaLaTeX o XeLaTeX (es. MacTeX: `brew install --cask mactex-no-gui`).

```sh
cd cv
make cv.pdf        # oppure: make (compila tutto)
```
