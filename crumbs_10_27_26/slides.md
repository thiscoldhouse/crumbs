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

# Your slides can have subsections

## subsection 1
a lot of words can go here. Maybe a quote from a book or something

## subsection 2
- alternatively, you can use bullets 
- like
- this

# What do you need installed?

- pandoc
- pdflatex (or any other latex compiler)

# Example reference

I wrote a paper on MBFC @ruiziglesias2026stop.

You can also include footnotes^[like this].

# Example of two-column slide with table (content taken from one of Ale's existing presentation)

```{=latex}
\begin{columns}
\begin{column}{0.6\textwidth}
\footnotesize

\textbf{Entire database}
\vspace{5px}
\begin{table}
\tiny
\begin{tabular}{|l|p{2cm}|p{2cm}|}
\hline
\cline{2-3}
& Papers with text & All papers \\
\hline
Papers with MBFC & 329 (5.01\%) & 372 (3.50\%) \\
Total papers     & 6,514        & 10,642 \\
\hline
\end{tabular}
\end{table}
\vspace{10px}
\textbf{Papers containing "misinformation"}
\vspace{5px}
\begin{table}
\tiny
\begin{tabular}{|l|p{2cm}|p{2cm}|}
\hline
\cline{2-3}
& Papers with text & All papers \\
\hline
Papers with MBFC & 259 (7.38\%) & 263 (6.49\%) \\
Total papers     & 3,509        & 4,051 \\
\hline
\end{tabular}
\end{table}
\vspace{10px}
```

**More text goes here**

\tiny
- little
- tiny
- bullets

```{=latex}
\end{column}
\begin{column}{0.39\textwidth}

\end{column}
\end{columns}

```

# Example figure (using latex)

```{=latex}
\begin{figure}
\includegraphics{img/repo.png}
\end{figure}
```

# References {.allowframebreaks}
\tiny
::: {#refs}
:::

