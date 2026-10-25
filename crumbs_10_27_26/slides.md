---
title: "How I make presentations in markdown with pandoc"
author: Alejandro Javier Ruiz Iglesias
institute: Computational Story Lab, Vermont Complex Systems Institute, University of Vermont
csl: ieee.csl
theme: metropolis
fonttheme: serif
fontsize: 13pt
aspectratio: 169
header-includes:
- \usepackage{xcolor}
- \usepackage{tikz}
- \usepackage{multirow}
- \usetikzlibrary{positioning,shapes.geometric,arrows.meta}
- \definecolor{darkbg}{HTML}{171D1C}
- \definecolor{lighttext}{HTML}{FFFFFF}
- \definecolor{darktext}{HTML}{171D1C}
- \definecolor{accent}{HTML}{DB9D47}
- \definecolor{accent2}{HTML}{8CC084}
- \setbeamercolor{background canvas}{bg=lighttext}
- \setbeamercolor{normal text}{fg=darktext,bg=lighttext}
- \setbeamercolor{title}{fg=darkbg,bg=accent!80}
- \setbeamercolor{frametitle}{fg=darktext,bg=accent!80}
- \setbeamercolor{structure}{fg=accent}
- \setbeamercolor{alerted text}{fg=accent}
- \setbeamercolor{item}{fg=accent}
- \setbeamercolor{subitem}{fg=accent2}
- \setbeamercolor{section in toc}{fg=accent}
- \setbeamercolor{subsection in toc}{fg=accent2}
- \setbeamercolor{block title}{fg=darkbg,bg=accent!60}
- \setbeamercolor{block body}{fg=darktext,bg=accent!10}
- \setbeamercolor{block title alerted}{fg=darkbg,bg=accent2}
- \setbeamercolor{block body alerted}{fg=darktext,bg=accent2!10}
- \setbeamercolor{block title example}{fg=lighttext,bg=darkbg}
- \setbeamercolor{block body example}{fg=darktext,bg=darkbg!5}
- \setbeamercolor{footline}{fg=darktext,bg=accent!40}
- \setbeamertemplate{navigation symbols}{}
- \setbeamertemplate{itemize item}{\color{accent}\large\textbullet}
- \setbeamertemplate{itemize subitem}{\color{accent!85}\small\textbullet}
- \setbeamertemplate{itemize subsubitem}{\color{accent!70}\tiny\textbullet}
- \metroset{progressbar=none}
- \metroset{progressbar=none}
- \setbeamertemplate{footline}{}

---

# You can find this presentation in this github repo

\centering

![](img/repo.png)

# Example reference

I wrote a paper on MBFC @ruiziglesias2026stop.

# References {.allowframebreaks}
\tiny
::: {#refs}
:::

