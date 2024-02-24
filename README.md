\documentclass{article}
\usepackage{fontawesome}
\usepackage{enumitem}
\usepackage{amsfonts}
\usepackage{amssymb}
\begin{document}

\begin{itemize}[label=\faHandORight]
    \item First item
\end{itemize}
In LaTeX, you can customize the bullet style using the `itemize` environment provided by the `enumitem` package. Here's an example demonstrating various bullet styles:

```latex


\begin{itemize}[label={$\bullet$}]
    \item Item 1
\end{itemize}

\begin{itemize}[label={\textendash}]
    \item Item 1
\end{itemize}

\begin{itemize}[label={\textasteriskcentered}]
    \item Item 1
\end{itemize}

\begin{itemize}[label={$\circ$}]
    \item Item 1
\end{itemize}

\begin{itemize}[label={$\triangleright$}]
    \item Item 1
\end{itemize}

\begin{itemize}[label={$\diamond$}]
    \item Item 1
\end{itemize}
\begin{itemize}[label={$\ast$}]
    \item[\checkmark] Item 1
    \item[$\heartsuit$] Item 3
    \item Item 3SS
\end{itemize}



\end{document}
