\documentclass[12pt,a4paper]{article}

% Packages
\usepackage{geometry}
\usepackage{graphicx}
\usepackage{array}
\usepackage{booktabs}
\usepackage{hyperref}

% Page setup
\geometry{margin=1in}

\title{Lab Report 4: Inductor Response to DC Switching}
\author{Your Name}
\date{\today}

\begin{document}

\maketitle

\section*{Introduction}
The purpose of this lab was to study the response of an inductor when a direct current (DC) source is applied and removed. Inductors are widely used in electronic circuits due to their ability to resist sudden changes in current. This experiment demonstrates the fundamental principle of inductors and their effect on current flow in DC switching.

\section*{GitHub Repository}
The project code and files were stored in a GitHub repository. A screenshot of the repository is shown below:

\begin{center}
    \includegraphics[width=0.8\textwidth]{github_screenshot.png} % Replace with actual screenshot
\end{center}

\section*{Theory: What is an Inductor?}
An inductor is a passive two-terminal electrical component that stores energy in its magnetic field when current flows through it. It is typically made of a coil of wire. The key property of an inductor is \textit{inductance}, which is the ability to oppose changes in current.  

The voltage across an inductor is defined by:
\[
V = L \frac{di}{dt}
\]
where:
\begin{itemize}
    \item $V$ = voltage across the inductor,
    \item $L$ = inductance in Henrys (H),
    \item $\frac{di}{dt}$ = rate of change of current.
\end{itemize}

When DC voltage is suddenly applied, the inductor resists the rapid rise in current, causing a delay. Similarly, when the voltage is removed, the inductor releases stored energy, maintaining the current for a short duration.

\section*{Project Description}
\subsection*{Apparatus}
\begin{itemize}
    \item 9V Battery
    \item 220$\Omega$ Resistor
    \item Inductor
    \item LED
    \item Pushbutton switch
    \item Connecting wires
\end{itemize}

\subsection*{Procedure}
\begin{enumerate}
    \item Construct the circuit:  
    9V Battery $\rightarrow$ 220$\Omega$ Resistor $\rightarrow$ Inductor $\rightarrow$ LED $\rightarrow$ Ground
    \item Insert a pushbutton to control the battery connection.
    \item Press and release the pushbutton to observe the LED response.
\end{enumerate}

\section*{Observations and Results}
\begin{center}
\begin{tabular}{|c|c|c|}
\hline
\textbf{Action} & \textbf{LED Behavior} & \textbf{Reason} \\
\hline
Button Pressed & LED turns on gradually & Inductor resists sudden current increase. \\
\hline
Button Released & LED dims gradually & Inductor releases stored energy to keep current flowing. \\
\hline
\end{tabular}
\end{center}

\section*{Proteus Simulation (if any)}
If Proteus software was used, the simulation screenshot of the circuit is shown below:  

\begin{center}
    \includegraphics[width=0.8\textwidth]{image.png} % Replace with actual simulation image
\begin{figure}
    \centering
    \includegraphics[width=0.5\linewidth]{image.png}
    \caption{Enter Caption}
    \label{fig:placeholder}
\end{figure}
\end{center}

\section*{Conclusion}
The experiment confirmed that inductors oppose sudden changes in current. When the circuit was switched on, the LED turned on gradually due to the inductor delaying current rise. When the circuit was switched off, the LED dimmed gradually as the inductor discharged its stored energy. This demonstrates the energy storage property of inductors and their importance in DC switching applications.

\end{document}

