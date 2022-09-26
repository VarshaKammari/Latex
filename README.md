%Creating a simple Title Page in Beamer
\documentclass{beamer}
\usepackage{graphicx}

% Theme choice:
%\usetheme{AnnArbor}
%\usetheme{CambridgeUS}
 \usetheme{Antibes}

% Title page details: 
\title{My First \LaTeX{} Presentation}
% \subtitle{My-subtitle}
\author{Varsha Kammari}

\date{\today}

\begin{document}

% Title page frame
\begin{frame}
    \titlepage
\end{frame}
% Outline frame
\begin{frame}{Outline}
    \tableofcontents
   
\end{frame}

% Presentation structure

    \section{Introduction}
    \section{Semester Marks}
    \section{Photograph}

% % Outline frame
\begin{frame}{Introduction:}
\begin{block}{\textbf{Personal Details:}}
    Name:K.Varsha \\
    ID:B191437 \\
    Branch:COMPUTER SCIENCE AND ENGINEERING
 \end{block}
 \begin{alertblock}{\textbf{Hostel Address:}}
   Hostel Name:Ganga Girl's Hostel \\
   Room Number:E-218 
 \end{alertblock}
 \begin{exampleblock}{\textbf{Personal Address:}}
   Village:Naleshwar \\
   Mandal:Navipet \\
   District:Nizamabad
 \end{exampleblock}

\end{frame}
\begin{frame}{Semester Marks:}
\centering
\begin{tabular}{|c |c |c |}
\hline
    S.No. & Subject & Marks \\ 
\hline
    1 & Maths & 95 \\
\hline
    2 & Physics & 93 \\ 
\hline
    3 & Chemistry & 94 \\ 
\hline
    4 & PPS & 96 \\
\hline
\end{tabular}
\end{frame}

\begin{frame}{Photograph:}
    \begin{figure}
        \centering
        \includegraphics[scale=0.25]{nature.jpg}
        \caption{Beauty of Nature}
        \label{fig:my_label}
    \end{figure}
\end{frame}
\end{document}
