
\documentclass[a4paper,20pt]{article}
\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[pdftex]{hyperref}
\usepackage{fancyhdr}
\usepackage{fontawesome5}
\usepackage{tabularx}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

\newcolumntype{L}{>{\raggedright\arraybackslash}X}%
\newcolumntype{R}{>{\raggedleft\arraybackslash}X}%
\newcolumntype{C}{>{\centering\arraybackslash}X}%

% Adjust margins
\addtolength{\oddsidemargin}{-0.530in}
\addtolength{\evensidemargin}{-0.375in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.45in}
\addtolength{\textheight}{1in}

\urlstyle{rm}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-10pt}\scshape\raggedright\Large \bfseries
}{}  {0em}{}[\color{black}\titlerule \vspace{-6pt}]

%-------------------------
% Custom commands
\newcommand{\resumeItem}[2]{
  \item\small{
    \textbf{#1}{#2 \vspace{-2pt}}
  }
}

\newcommand{\resumeItemWithoutTitle}[1]{
  \item\small{
    {\vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-1pt}\item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{#3} & \textit{#4} \\
    \end{tabular*}\vspace{-5pt}
}


\newcommand{\resumeSubItem}[2]{\resumeItem{#1}{#2}\vspace{-3pt}}

\renewcommand{\labelitemii}{$\circ$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-----------------------------
%%%%%%  CV STARTS HERE  %%%%%%

\newcommand{\name}{Akshay Mohite} % Your Name
\newcommand{\course}{Software Development Engineer - II} % Your Program
\newcommand{\phone}{7066819936} % Your Phone Number
\newcommand{\emaila}{mohiteakshay2020@gmail.com} %Email 1

\begin{document}

\fontfamily{cmr}\selectfont
%----------HEADING-----------------

{
\begin{tabularx}{\linewidth}{L r} \\
  \textbf{\huge \name} & {\raisebox{0.0\height}{\footnotesize \faPhone}\ +91-\phone}\\
  \course & \href{mailto:\emaila}{\raisebox{0.0\height}{\footnotesize \faEnvelope}\ {\emaila}} \\  
  {Bengaluru, India} & \href{https://linkedin.com/in/akshaym3255/}{\raisebox{0.0\height}{\footnotesize \faLinkedin}\ {linkedin.com/in/akshaym3255/}} \\ & \href{https://github.com/akshaym-3255}{\raisebox{0.0\height}{\footnotesize \faGithub}\ {github.com/akshaym-3255}}
\end{tabularx}
}

% %----------HEADING-----------------
% \begin{center}
%   \textbf{{\Huge Akshay Mohite }} \\
%   \vspace{10pt}
% Bangalore, Karnataka, India
% mohiteakshay2020@gmail.com
% ~+91-7066819936~~ 
% % https://www.linkedin.com/in/akshaym3255/
% % https://github.com/akshaym-3255
% % https://leetcode.com/akshaym3255/
% \href{https://www.linkedin.com/in/akshaym3255/}{linkedin.com/in/akshaym3255/} \\ \href{https://github.com/akshaym-3255}{github.com/akshaym-3255}
% % \href{https://leetcode.com/akshaym3255/}{leetcode.com/akshaym3255/}

% %
% % \href{https://www.linkedin.com/in/akshaym3255/}
% % \href{https://github.com/akshaym-3255}
% % \href{https://leetcode.com/akshaym3255/}
% % % \par\noindent\rule{\textwidth}{0.1pt}
% \end{center}

%----------HEADING----------------- 
\vspace{2pt}






\section{Experience}
  \resumeSubHeadingListStart
    \resumeSubheading
		{NUTANIX }{Bangalore, India}
		{Member Of Technical Staff 2 (Nutanix Security Central)}{Apr 2023 - Present}
		\resumeItemListStart

        \resumeItem{}{\textbf{Graph Pipeline Security Central} 
        Led development of the extensible graph data pipeline powering Nutanix security central by modeling all critical infrastructure entities in Neo4j and enabling graph-driven detection of ~350 security issues through automated ingestion and query logic
        }
          \resumeItem{}{\textbf{Benchmarked read and write performance} of various graph databases  like ApacheAge, Neo4J, OngDB, Nebula Graph from \textbf{50 thousand entities scale to 10 million entities scale}. 
          }
          
          \resumeItem{}{Significantly \textbf{reduced pipeline cloud costs by 75\%} by building a metrics data ingestion pipeline that leverages Apache Avro for efficiently processing large amount of data from Parquet files, replacing the more expensive AWS Athena service and ingesting the processed data into Druid. \textbf{This pipeline processes 20 GB data daily.}
          }
          
          \resumeItem{}{Owning complete responsibility cost configuration part of cost governance. Designed and developed  high level and low level for cost config changes which includes api design , database design. \textbf {Api latency decresaed to almost less than 1s from 15s} 
          }
          
          \resumeItem{}{Designed and developed the monthly tco calculation logic for various cost components such as software, hardware, telecom, facilities, people and services for nutanix private cloud
          }

          
          
          % \resumeItem{}{Improved system monitoring by integrating \textbf{Slack alerts and StatsD metrics} collection for visualization in \textbf{Grafana dashboards.}}
          
          \resumeItem{}{Contributed to system stability and reliability by working on various \textbf{improvements and bug fixes} throughout
          the system. Undertook the duties and responsibilities of the on-call engineer.
          }
          
		\resumeItemListEnd
\vspace{2pt}
     
    \resumeSubheading{TERADATA}{Pune, India}
    {Software Engineer (Backup as a Service) (Full-time)}{Sep 2020 - Apr 2023}
    \resumeItemListStart
        % \resumeItem {Teradata Backup As a Service}{} 
        \resumeItem{}
          {Developed a standalone custom cron scheduler micro-service in \textbf {GoLang} which reads the cron schedules across all jobs of all baas customers and triggers them when due}
          \vspace{1pt}
         \resumeItem{}
          {Developed a containerized api microservice in \textbf {GoLang} using \textbf{Gin, Gorm} to reconcile with new Teradata architecture for providing backup and recovery}
          \vspace{1pt}
        \resumeItem{}
          {Contributed to the orchestration of snapshot-based backups and retention management using\textbf{ AWS step-functions, ~~ Lambda(Python)} and Teradata cloud data protection API's which reduced backup time of Teradata database by 2-3 hours and \textbf {improved recovery time objective (RTO) from 24 hours to 2 hours.} }
          \vspace{1pt}
          \resumeItem{}{Successfully \textbf{resolved 95\% incident/case}s assigned. Provided Root Cause Analysis, Mitigation plans, and Actions on the engineering team for various customer issues. Worked with various related teams to get customer commitments on time and faster.}
          \resumeItem{}{Streamlined the CI-CD for service. Restructured code in monorepo which spread across 12 git repositories which made change tracking easy and service deployment time from 3 hours to 30 min's which is fully automated}
      \resumeItemListEnd
      
% \vspace{2pt}
%     \resumeSubheading
% 		{Myrsa Technologies}{Remote}
% 		{Web Developer Intern}{June  2019 - July 2019}
% 		\resumeItemListStart
%         \resumeItem{}
%           {Developed a website in \textbf{Angular and Node JS} for corporate post login for the insurance company. Where users have the capability to  manage their policies, documents, endorsement, and claims.View companies' new policies.}
% 		\resumeItemListEnd
% \vspace{2pt}
%     \resumeSubheading
% 		{VESIT Renaissance Cell (VRC)}{Mumbai, India}
% 		{Web Developer Intern}{Dec  2018 - Jan 2019}
% 		\resumeItemListStart
%         \resumeItem{}
%           {Configured a \textbf{HaProxy} load balancer for college cms website which distributed load across 3 web servers}
%          \resumeItem{}
%           {Configured \textbf{mysql(master-slave) replication} for the database availability and Backup.}
          
%         % \resumeItem{Staff Profile Page}
%         %   {Created a staff profile page where staff can add, delete, edit the information like  paper publication,patents,research grants,courses,industry interaction}
% 		\resumeItemListEnd
\resumeSubHeadingListEnd
\vspace{1pt}


%-----------PROJECTS-----------------
\vspace{-5pt}
\section{Projects}
\resumeSubHeadingListStart
\resumeSubItem  {Distributed Key Value Database \href{https://github.com/akshaym-3255/practicle-raft}{\faIcon{external-link-alt}} }{\linebreak Built an Distributed key value database in golang using \textbf{raft consensus algorithm} which has features such as \textbf{log replication, safety, fault tolerance and consistency}}
\vspace{2pt}
\resumeSubItem{MyGrep: \href{https://github.com/akshaym-3255/mygrep}{\faIcon{external-link-alt}} }{ \linebreak This is the unix grep command implementation in \textbf{golang} using goroutines which supports mutliple command line options}
\vspace{2pt}

% \resumeSubItem  {Currency Recognition System For Visually Impaired People: \href{https://github.com/akshaym-3255/CRS}{\faIcon{external-link-alt}} }{\linebreak Built an android app for visually impaired people for recognition of currency of various denominations by stationing the currency in front of the mobile camera giving its value in the form of a voice output}
% \vspace{2pt}
% \resumeSubItem{Smart Agriculture: \href{https://github.com/akshaym-3255/Smart-Agriculture-1}{\faIcon{external-link-alt}} }{ \linebreak Built an E-commerce  website for farmers where they can sell and promote their goods. The project's main goal is to remove the gap between farmers and consumers by providing a direct platform between them.}
% \vspace{2pt}
\vspace{2pt}
\resumeSubHeadingListEnd
\vspace{-5pt}


\section {Technical Skills}
	\resumeSubHeadingListStart
	\resumeSubItem{Languages}{\hspace{4mm} Golang, Java, Python}
	\resumeSubItem{Database}{ \hspace{6mm}PostgreSQL, Apache Druid, Neo4j, MongoDb, Redis}
	\resumeSubItem{Platforms}{\hspace{6mm} Linux, Windows}
	\resumeSubItem{Tools}{\hspace{13mm} Docker, Kubernetes, AWS, Git ArgoCD, Flyway, Temporal,  Netflix Conductor, Locust, Jira, gRPC, Jenkins }
    % SpingBoot, Pytest, unittest, junit , gin , gorm
	\resumeSubItem{IT constructs}{ \hspace{0mm}Design patterns and principles, Distributed systems, Event-Driven Application, REST}
% (lambda,s3, ec2, vpc,iam, sns, sqs, step functions, dynamodb, cloud formation, cloudwatch, rds, api gateway, secrets manager)}

\resumeSubHeadingListEnd
\vspace{1pt}




%-----------EDUCATION-----------------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {VESIT, Mumbai University}{Mumbai, India}
      {Bachelor of Engineering - Computer Engineering;  CGPA: 9.40/10 }{July 2016 - June 2020}
    
    \resumeSubHeadingListEnd


    



   
%-----------co-curricular and  extra-curricular activities-----------------
% \section{Achievements} 
% \begin{description}[font=$\bullet$]
% \item {Winner of VES Shrestha Award 2018}
% \vspace{-5pt}
% \item {GATE 2020 qualified}
% \vspace{-5pt}
% \item {Runner up in techtrix ISTE VESIT}
% \end{description}


%-----------certifications----------------

\vspace{-5pt}
\section{Certifications And Achievements} 
\begin{description}[font=$\bullet$]
\item {AWS Certified Developer - Associate \href{https://www.credly.com/badges/1c5d3469-d108-4aba-af14-84162744265c/public_url}{\faIcon{external-link-alt}}}
\vspace{-5pt}
\item {Secured position in top 5 teams in Nutanix Capture the Flag competition for two consecutive years.}
\vspace{-5pt}
\item {Winner of \textbf{VES SHRESHTATHA} award.}
\end{description}




% \vspace{-5pt}
% \section{Volunteer Experience}
%   \resumeSubHeadingListStart
% 	\resumeSubheading
%     {Volunteer Aai Caretaker}{Mumbai, India}
%     {Conducted a 2 month computer science awareness program for students of class 5th to 9th}{Aug 2018 - Sep 2018}
%     \item {Placement coordinator for the academic year 19-20, Part of organizing team various placement related activities}
% \vspace{-5pt}
% \resumeSubHeadingListEnd
\end{document}
