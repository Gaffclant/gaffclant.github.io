---
alt_title: "Understanding LaTeX"
sub_title: "GaffHub"
introduction: |
    LaTeX is a tool used to generate PDF's easily from a little bit of LaTeX code. LaTeX allows packages and some logic as well, making it easy to write a complex PDF in only minutes.
actions:
  - label: "Download LaTeX"
    icon: download 
    url: "https://www.latex-project.org/get/"
---
# My experience with LaTeX

I use LaTeX for notetaking in my physics class simply because it is faster for me to type out the equation than to write it out. On top of that, LaTeX documents look really nice, and I can format them perfecty to align with how I study. I can write complex equations with a couple basic math commands in LaTeX, where in Word or libreoffice it would be tedious and take much longer than what LaTeX does. 

I think the only 'downside' of LaTeX is that you have to compile the PDF on your own, so a **really big** document could take a minute or two to compile before you can see the results, but you still get the PDF you wanted so thats what counts. 

```latex
\documentclass[11pt]{article}
\title{Vectors in LaTeX}
\author{Gaffclant}
\usepackage{tikz}
\usepackage{multicol}
\usepackage{gensymb}
\begin{document}
  \maketitle
    \begin{multicols} {2}
      \[
        \theta = \tan^{-1} {\frac{opp}{adj}}
      \] \[
        \theta = \tan^{-1} {\frac{2}{3}}
      \] \[
        \theta = 33.7\degree
      \]
      \begin{tikzpicture}
        \draw [-stealth] (0,0) -- (0,3) node[midway, anchor=west] {3m};
        \draw [-stealth] (0,3) -- (-2,3) node[midway, anchor=south] {2m};
        \draw [dashed] (-2,3) -- (0,0) node[midway, anchor=north east] {3.6m}
          node [anchor=north] {$\theta$};
      \end{tikzpicture}
      \textbf{3.6m@33.7\degree NW}
    \end{multicols}
\end{document}
```
Here I put an example of calculating the displacement of 2 vectors going directly east/west and north/south

## Goodbye
And that is my experience with LaTeX so far! I highly suggest everyone to use LaTeX for basic notetaking and writing essays. 
