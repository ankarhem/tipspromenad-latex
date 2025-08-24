# Generera tipspromenad med LaTeX

1. Kopiera tipspromenad.sty till din LaTeX-mapp
2. Se [tipspromenad.tex](tipspromenad.tex) för exempel
3. Kolla [tipspromenad.pdf](tipspromenad.pdf) för att se exempelresultatet.

## Syntax

```latex
\begin{document}

\setpromenadtitel{\textbf{\LARGE Julquiz 2025}}

\tipspromenadfraga{stockholm.jpg}{Vilken stad är Sveriges huvudstad?}
{Stockholm}{Göteborg}{Malmö}
\tipspromenadfraga{vinklar.png}{Hur många grader är en rät vinkel?}
{45}{90}{180}
\tipspromenadfraga{moon.jpg}{Vilket år landade människan på månen?}
{1965}{1969}{1972}
\tipspromenadfraga{oxygen.jpg}{Vilket grundämne har kemiska beteckningen O?}
{Guld}{Syre}{Silver}
\tipspromenadfraga{iphone-1.jpg}{Vilket år uppfanns den första iPhonen?}
{2004}{2005}{2006}
\tipspromenadfraga{blaval.jpg}{Vilket djur är världens största däggdjur?}
{Elefant}{Blåval}{Kaskelot}
\tipspromenadfraga{kebnekaise.jpg}{Vad heter Sveriges högsta berg?}
{Kebnekaise}{Helagsfjället}{Sarektjåkkå}

% Generera svarsblankett
\svarsblanketter

\end{document}
```

## Generera pdf

```
pdflatex tipspromenad.tex
```
