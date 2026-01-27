%-------------------------
% Resume in Latex
% Author : Abey George
% Based off of: https://github.com/sb2nov/resume
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
\usepackage[hidelinks]{hyperref}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\usepackage{graphicx}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}

\RequirePackage{tikz}
\RequirePackage{xcolor}
\RequirePackage{fontawesome}
\usepackage{tikz}
\usetikzlibrary{svg.path}


\definecolor{cvblue}{HTML}{0E5484}
\definecolor{black}{HTML}{130810}
\definecolor{darkcolor}{HTML}{0F4539}
\definecolor{cvgreen}{HTML}{3BD80D}
\definecolor{taggreen}{HTML}{00E278}
\definecolor{SlateGrey}{HTML}{2E2E2E}
\definecolor{LightGrey}{HTML}{666666}
\colorlet{name}{black}
\colorlet{tagline}{darkcolor}
\colorlet{heading}{darkcolor}
\colorlet{headingrule}{cvblue}
\colorlet{accent}{darkcolor}
\colorlet{emphasis}{SlateGrey}
\colorlet{body}{LightGrey}



%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\classesList}[4]{
    \item\small{
        {#1 #2 #3 #4 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{\large#1} & \textbf{\small #2} \\
      \textit{\large#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

\newcommand\sbullet[1][.5]{\mathbin{\vcenter{\hbox{\scalebox{#1}{$\bullet$}}}}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{document}

%----------HEADING----------
\begin{center}
        {\Huge \scshape DEVIREDDY INDRASENAREDDY} \\ \vspace{1pt}
    \\ \vspace{1pt}
    \small 
    \href{tel:#}{\raisebox{-0.1\height}\faPhone\ \underline{+91-8019273394}} ~
    \href{mailto:indrareddy3425@gmail.com}
    {\raisebox{-0.2\height}\faEnvelope\ \underline{indrareddy3425@gmail.com}} ~
    \href{https://www.linkedin.com/in/indra3425/}{\raisebox{-0.2\height}\faLinkedinSquare\ \underline{LinkedIn}} ~
    \href{https://github.com/indrareddy3425}
    {\raisebox{-0.2\height}\faGithub\ \underline{GitHub}}
\end{center}
% \vspace{0.5mm}

% ------------------ CAREER OBJECTIVE ------------------
\section{CAREER OBJECTIVE}

A focused and dedicated individual with a positive mindset, committed to continuous learning and personal growth. 
Approaches responsibilities with sincerity and discipline, and is open to new opportunities that enhance technical 
and professional development.

% ------------------ EDUCATION ------------------
\section{EDUCATION}

\textbf{Bachelor of Engineering – Electronics Engineering (VLSI Design and Technology)}\\
R.M.K Engineering College, Chennai, Tamil Nadu \hfill 2023 – 2027\\
CGPA: 7.47 (Till 5\textsuperscript{th} Semester)

\vspace{4pt}

\textbf{Intermediate – MPC}\\
Sri Chaitanya Junior College, Vijayawada, Andhra Pradesh \hfill 2021 – 2023\\
Percentage: 90.5\%

\vspace{4pt}

\textbf{Secondary Education}\\
Sri Sai Vidyanikethan H School, Badvel, Kadapa(Dist), Andhra Pradesh \hfill 2020 – 2021\\
Percentage: 94\%

%-----------TECHNICAL SKILLS-----------
\section{TECHNICAL SKILLS}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{\normalsize{Languages:}}{  \normalsize{C , Verilog}} \\
     \textbf{\normalsize{Technologies/Frameworks:}}{  \normalsize{Excel, Ms Word}} \\
     \textbf{\normalsize{Tools:}}{  \normalsize{Xilinx , Vivado}} \\
     \textbf{\normalsize{Web Development: }}{  \normalsize{HTML, CSS.}} \\
    }}
 \end{itemize}
 \vspace{-15pt}

% ------------------ PROJECTS ------------------
\section{PROJECTS}
\vspace{-1pt}

\textbf{Solar Panel with Sun Position Tracking System}
\vspace{-3pt}
\begin{itemize}[leftmargin=0.35in, itemsep=2pt, topsep=2pt]
    \item Automated sun-tracking solar panel using Arduino, LDR sensors, and servo motors.
    \item Real-time adjustment to maximize solar energy absorption.
    \item Achieved 20–40 efficiency improvement over fixed panels.
    \item Low-power, stable, and cost-effective system.
    \item Scalable design with future scope for IoT-based monitoring.
\end{itemize}

\vspace{-1pt}



\vspace{-6pt}


% ------------------ INTERNSHIP ------------------
\section{INTERNSHIP}

\textbf{Technotron – Verilog Design Intern} \hfill June 2025 – July 2025
\begin{itemize}
    \item Completed a hands-on internship focused on Verilog HDL and digital system design.
    \item Designed and implemented an Optimized Reversible ALU using Reversible Logic Gates.
    \item Applied reversible logic principles to minimize information loss and power consumption.

\end{itemize}

% ------------------ CERTIFICATIONS ------------------
\section{CERTIFICATIONS}

\begin{itemize}
    \item Completed C Programming Basics from simplilearn.
    \item System Design Through Verilog (Elite), Digital Circuits, CMOS VLSI Design, Introduction to Semiconductor Devices– NPTEL.
    \item Digital Electronics – Udemy.
\end{itemize}

% ------------------ ACHIEVEMENTS ------------------
\section{ACHIEVEMENTS}
\begin{itemize}
    \item Completed 1200+ programming problems on SkillRack, strengthening problem-solving and logical thinking
skills.


\end{document}
