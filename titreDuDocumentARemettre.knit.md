---
titre: "Salut"
auteur: "Gros"
ni: "698"
professeur: "comment"
projet: "va"
cours: "tu"
faculte: "aujourd"
département: "hui"
output: 
  pdf_document:
    latex_engine: xelatex
bibliography: bib/references.json
csl: "https://www.zotero.org/styles/chicago-author-date-fr"
fontsize: 12pt
header-includes:
 - \usepackage{setspace}
 - \onehalfspacing
---
\titre{$titre$}
\auteur{$auteur$}
\ni{$ni$}
\professeur{$professeur$}
\projet{$projet$}
\cours{$cours$}
\faculte{$faculte$}
\departement{$departement$}
\def\titre#1{\gdef \@titre{#1}}
\def\@titre{\@latex@warning@no@line{No \noexpand\titre given}}
\def\auteur#1{\gdef \@auteur{#1}}
\def\@auteur{\@latex@warning@no@line{No \noexpand\auteur given}}
\def\ni#1{\gdef \@ni{#1}}
\def\@ni{\@latex@warning@no@line{No \noexpand\ni given}}
\def\professeur#1{\gdef \@professeur{#1}}
\def\@professeur{\@latex@warning@no@line{No \noexpand\professeur given}}
\def\projet#1{\gdef \@projet{#1}}
\def\@projet{\@latex@warning@no@line{No \noexpand\projet given}}
\def\cours#1{\gdef \@cours{#1}}
\def\@cours{\@latex@warning@no@line{No \noexpand\cours given}}
\def\faculte#1{\gdef \@faculte{#1}}
\def\@faculte{\@latex@warning@no@line{No \noexpand\faculte given}}
\def\departement#1{\gdef \@departement{#1}}
\def\@departement{\@latex@warning@no@line{No \noexpand\departement given}}

\begin{titlepage}
  \newpage
  \let\footnotesize\small
  \let\footnoterule\relax
  \let \footnote \thanks

  \baselineskip = 1.4\baselineskip

  \begin{center}
    \setcounter{page}{1}
    \includegraphics[height=20mm,keepaspectratio=true]{figures/logoULaval/ul_p}
    \null\vfil
    {\fontsize{16}{14}\selectfont \textbf{\@titre}}
    \vfil
    \textbf{\@auteur} \\
    \@ni
    \vfil
    \@projet \\\@cours
    \vfil
    Travail présenté à:\\
    \textbf{\@professeur} \\
    \vfil
    \@departement\\\@faculte\\Université Laval
    \vfil
    \vfil
    Québec, Canada \\
    \vfil
    \copyright \thinspace \@auteur, 20 mars 2023 \\
  \end{center}\par
\end{titlepage}

# Introduction

# Paragraphe 1

# Paragraphe 2

# Paragraphe 3

# Conclusion

# Bibliographie
