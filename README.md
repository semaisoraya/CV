# CV
voici mon cv 
% Resume in Latex
% Author : semai soraya
% Website: https://https://github.com/semaisoraya/CV/new/master?readme=1
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[pdftex]{hyperref}
\usepackage{fancyhdr}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.375in}
\addtolength{\evensidemargin}{-0.375in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

%-------------------------
% Custom commands
\def \ifempty#1{\def\temp{#1} \ifx\temp\empty }

\newcommand{\resumeItem}[2]{
  \item\small{
  	\ifempty{#1}#2\else\textbf{#1}{: #2 \vspace{-2pt}}\fi
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-1pt}\item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-5pt}
}

\newcommand{\resumeSubItem}[2]{\resumeItem{#1}{#2}\vspace{-4pt}}

\renewcommand{\labelitemii}{$\circ$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  CV STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING-----------------
\begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
  \textbf{\Large Name} & Email : \href{mailto:mail@mail.com}{sorayasemai@gmail.com}\\
  \href{https://website/}{https://website/} & Mobile : 0769912521 \\
\end{tabular*}


%-----------FORMATION-----------------
\section{Formation}
  \resumeSubHeadingListStart
    \resumeSubheading
      {University of Somewhere}{Somewhere}
      {Some course}{juillet 2019 - fevrier 2020}
	 \resumeItemListStart
        \resumeItem{Relevant Modules}
          {Modules...}
      \resumeItemListEnd
  \resumeSubHeadingListEnd


%-----------EXPERIENCE-----------------
\section{Experience}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Experience 1}{Some Place}
      {Short Description}{Avril. 2016A- Juin. 2017}
      \resumeItemListStart
      	\resumeItem{}
          {Some stuff}
        \resumeItem{}
          {More stuff}
      \resumeItemListEnd
        \resumeSubheading
      {Experience 2}{Some Place}
      {Short Description}{Avril. 2018 - Dec. 2018}
      \resumeItemListStart
      	\resumeItem{}
          {Some stuff}
        \resumeItem{}
          {More stuff}
      \resumeItemListEnd
    
  \resumeSubHeadingListEnd

\section{Some Section}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Some Stuff}{}
      {Some Description}{Avril. 2015}
      \resumeItemListStart
        \resumeItem{}
          {Some stuff}
        \resumeItem{}
          {More stuff}
      \resumeItemListEnd
  \resumeSubHeadingListEnd
  \end{document}


