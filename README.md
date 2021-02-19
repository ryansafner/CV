# CV
Professional CV, [Latest version](https://raw.githubusercontent.com/ryansafner/CV/master/CV.pdf)



Not sure what I was doing wrong, but to get icons in the font awesome, I made some select edits to the `awesome-cv.cls` file.

Using `headcolor: e64173` in `yaml`

```{tex}
  linkcolor =, % CHANGED & ADDED REMAINDER
  colorlinks = true,
  urlcolor = cyan
```

Under configuration for styles:

```{tex}
\newcommand*{\sectionstyle}[1]{{\fontsize{16pt}{1em}\bodyfont\bfseries\color{awesome} #1}} % CHANGED \newcommand*{\sectionstyle}[1]{{\fontsize{16pt}{1em}\bodyfont\bfseries\color{text}\@sectioncolor #1}}
```