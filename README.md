```latex

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\input{glyphtounicode}


%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
\usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
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

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
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
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & #2 \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------
% \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
%   \textbf{\href{x@x.com}{\Large Name}} & Email : \href{mailto:x@x.com}{email}\\
%   \href{site.com}{site.com} & Mobile : +1-123-456-7890 \\
% \end{tabular*}

\newcommand\NAME{Uday Y. Patel}
\newcommand\EMAIL{uday3patel@gmail.com}
\newcommand\LINKEDIN{linkedin.com/in/uday3patel}
\newcommand\GITHUB{github.com/udaypatel1}
\newcommand\UNIVERSITY{Rutgers University}
\newcommand\UNIVERSITYLOCATION{New Brunswick, NJ}

\begin{center}
    \textbf{\Huge \scshape \NAME} \\ \vspace{1pt}
    \href{mailto:\EMAIL}{\underline{\EMAIL}} $|$ 
    \href{https://www.\LINKEDIN}{\underline{\LINKEDIN}} $|$
    \href{https://\GITHUB}{\underline{\GITHUB}}
\end{center}


%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {\UNIVERSITY}{\UNIVERSITYLOCATION}
      {Master of Business \& Science (MS + MBA), Computer \& Information Science | GPA: 3.9}{Jan. 2023 -- Dec. 2025}
    \resumeSubheading
      {\UNIVERSITY}{\UNIVERSITYLOCATION}
      {Bachelor of Arts, Computer Science}{Sept. 2019 -- Dec. 2022}
  \resumeSubHeadingListEnd


%-----------EXPERIENCE-----------
\section{Experience}
  \resumeSubHeadingListStart

    \resumeSubheading
      {Software Engineer}{Jan. 2023 -- Present}
      {\href{https://guardianlife.com}{Guardian Life}}{New York, NY}
      \resumeItemListStart
        \resumeItem{Built internal tooling in Typescript on the Growth Team to track authenticated users across Direct-To-Consumer Member Portals, fueling a backend ML service to enhance personalization resulting in a 15\% increase in product cross-sales}
        \resumeItem{Developed and owned a Release Management Service using a Jenkins cluster, Groovy, Python, FastAPI, and GitOps to reduce the probability of deployment rollbacks by only allowing QA tested code in production, resulting in 98\% uptime}
        \resumeItem{Implemented and owned a robust API service on the Dental Pre-Sales Core Platform, facilitating the persistence of Group Benefit proposal documents on AWS S3 and enabling efficient migration of over 1,000,000 on-premises data records}
        \resumeItem{Collaborated with leadership to help define engineering culture and fortify the existing new-grad pipeline program by creating content for live Demo Days at top universities which increased competitive application rates by $\mathtt{\sim}$ 20\% }
      \resumeItemListEnd
      
% -----------Multiple Positions Heading-----------
%    \resumeSubSubheading
%     {Software Engineer I}{MM YYYY - MM YYYY}
%     \resumeItemListStart
%        \resumeItem{Apache Beam}
%          {lorem ipsum}
%     \resumeItemListEnd
%    \resumeSubHeadingListEnd
%-------------------------------------------

    \resumeSubheading
      {Data Science Fellow}{July 2022 -- Nov. 2022}
      {\href{https://www.bluebonnetdata.org/}{Bluebonnet Data}}{Washington, D.C.}
      \resumeItemListStart
        \resumeItem{Provided campaign analysis to \href{https://lisaforga.com/}{Lisa Campbell}, Democratic Nominee of the Georgia State House District 35}
        \resumeItem{Coordinated with local political staff to create an executive dashboard with voter metrics on Google Data Studio}
        \resumeItem{Ingested data from the \href{https://www.ngpvan.com/}{NGP VAN Software} to build a heat-map of critical regions, improving campaign strategy}
    \resumeItemListEnd

    \resumeSubheading
      {Teaching Assistant}{July 2021 -- Jan. 2022}
      {Rutgers University, Department of Computer Science}{New Brunswick, NJ}
      \resumeItemListStart
        \resumeItem{Lead recitation sections and content delivery for the 01:198:111 course taught by Dr. Lars Sorensen}
        \resumeItem{Curated 5+ new problem sets for weekly assignments and held office hours to provide individualized explanations}
        \resumeItem{Facilitated bi-weekly stand-up meetings with the professor to be aligned on semester goals and student OKRs}
      \resumeItemListEnd

    \resumeSubheading
      {Data Engineering Intern}{June 2021 -- Aug. 2021}
      {\href{https://www.dnb.com/}{Dun \& Bradstreet}}{Short Hills, NJ}
      \resumeItemListStart
        \resumeItem{Improved documentation on data integrity for the Global Operations \& Strategy Team, evangelizing Snowflake}
        \resumeItem{Developed ETL jobs in Python to ingest customer analytics data, refining a 3rd party conversational AI service}
        \resumeItem{Performed end-to-end testing on the production container and implemented an email-on-failure feature for all jobs}
      \resumeItemListEnd


  \resumeSubHeadingListEnd


%-----------PROJECTS-----------
\section{Projects}
    \resumeSubHeadingListStart
      \resumeProjectHeading
          {\textbf{\href{https://github.com/udaypatel1/nba-live-rust}{NBA Live}} $|$ \emph{Rust, Homebrew, Ruby, Github}}{Jan. 2024 -- Feb. 2024}
          \resumeItemListStart
            \resumeItem{Built an open source CLI tool using Rust to view live game data in the terminal, wrapping an ESPN API endpoint}
            \resumeItem{Packaged the application as a Homebrew Tap with Ruby, available for public installation on ARM-based machines} 
            \resumeItem{Gained 200+ unique user downloads for the package and managed version deployments with new features}
          \resumeItemListEnd
      \resumeProjectHeading
          {\textbf{NYC Big Data Analytics} $|$ \emph{Hadoop, Pig, Hive, Linux, Python3}}{Nov 2023 -- Jan. 2024}
          \resumeItemListStart
            \resumeItem{Used Hadoop Distributed File System to persist raw NYC 2023-2024 Social Services data across 5 pseudo distributed nodes}
            \resumeItem{Wrote Pig Latin code to clean raw data files, structuring them by relevant columns using MapReduce jobs for performance}
            \resumeItem{Discovered trends using linear regression after building queries in Hive for data ingestion and processing}
          \resumeItemListEnd
    \resumeSubHeadingListEnd
%
%-----------PROGRAMMING SKILLS-----------
\section{Technical Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Languages}{: Java, Python3, JavaScript, TypeScript, Terraform, Zsh/Bash, Rust, Go, SQL} \\
     \textbf{Frameworks}{: Spring Boot, Nest.js, Next.js, React, FastAPI, Django, Playwright, Jest, GraphQL, JPA, Prisma, boto3} \\
     \textbf{Developer Tools}{: Git, Docker, Bitbucket, Jenkins, AWS (Lambda, S3, ELB, ECS, EC2, VPC, API Gateway)} \\
     \textbf{Software}{: Redis, MongoDB, CassandraDB, NGINX, Kafka, Spark, Tableau, Figma, Okta, Twilio Segment, Jira, Slack, ServiceNow}
    }}
 \end{itemize}


%-------------------------------------------
\end{document}

```