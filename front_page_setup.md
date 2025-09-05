<pre> ```latex \documentclass[a4paper, 12pt, twoside]{book}
\usepackage[demo]{graphicx}
\usepackage{array}

\begin{document}

\begin{titlepage}
    \begin{center}
        \includegraphics[width=0.5\textwidth]{BlackBox}\\
        \vspace{3em}
        \Large\scshape
        University something\\
        ``Some Name''       \\
        \vspace{1em}
        Faculty of Engineering, Information Technology and Statistics\\
        \vspace{1em}
        \small
        Master of Science in Engineering in Computer Science        \\
        \vspace{3em}
        \normalsize
        Master of Science presentation \\
        \vspace{2em}
        \normalfont\bfseries\LARGE
            This Is My Very Long Title Analysis from
            Advertisements for Characterizing Industry Differences.
    \end{center}
    \vspace{1.5 cm}
    \begin{center}
    \renewcommand\arraystretch{1.2}
        \begin{tabular*}{\linewidth}{l @{\extracolsep{\fill}} r}
            \textbf{Candidate}          &   \textbf{Supervisor}     \\
            \large Name Surname         &   \large Name Surname     \\
                                        &   \textbf{External Supervisor} \\
                                        &   \large Name Surname     \\
            \footnotesize ID 1234567    &
        \end{tabular*}

        A.y. 2016/2017
    \end{center}


\end{titlepage}
%\maketitle
\end{document} </prep>
