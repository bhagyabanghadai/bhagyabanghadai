\documentclass[10pt,a4paper,ragged2e,withhyper,normalphoto]{altacv}
\DeclareUnicodeCharacter{202F}{~}

\geometry{top=0.6cm,bottom=0.3cm,left=1.25cm,right=1.25cm,columnsep=1.0cm}

\iftutex
  \setmainfont{Lato}
\else
  \usepackage[default]{lato}
\fi

\definecolor{SpaceBlue}{HTML}{002244}
\definecolor{SlateGrey}{HTML}{2E2E2E}
\definecolor{LightGrey}{HTML}{666666}

\colorlet{heading}{SpaceBlue}
\colorlet{headingrule}{SpaceBlue}
\colorlet{accent}{SpaceBlue}
\colorlet{emphasis}{SlateGrey}
\colorlet{body}{LightGrey}

\renewcommand{\cvItemMarker}{{\small\textbullet}}
\renewcommand{\cvsectionfont}{\large\bfseries}
\renewcommand{\cvsubsectionfont}{\normalsize\bfseries}
\renewcommand{\namefont}{\Large\bfseries}

\begin{document}

\name{Bhagyaban Ghadai}

\personalinfo{
  \email{bhagyabang1999@gmail.com}
  \phone{+1 (313) 751 0020}
  \location{Ypsilanti, MI}
  \linkedin{bhagyabanghadai}
  \homepage{github.com/bhagyabanghadai}
}

\makecvheader

% =======================
% PROFESSIONAL SUMMARY
% =======================
\cvsection{Professional Summary}
\begin{itemize}
  \item Full-stack developer specializing in \textbf{Java 17, Spring Boot microservices, React, TypeScript, PostgreSQL, and AWS}. 
  \item Built and optimized \textbf{high-throughput APIs} with Redis caching, async pipelines, and database indexing to improve latency and scalability.
  \item Designed component-based UIs with \textbf{React + TypeScript}, integrating REST/GraphQL layers for internal dashboards and multi-tenant systems.
  \item Strong experience deploying cloud-native systems using \textbf{Docker, Terraform, ECS/EKS, CloudWatch, and CI/CD pipelines}.
\end{itemize}

% =======================
% TECHNICAL SKILLS
% =======================
\cvsection{Technical Skills}
\begin{itemize}
  \item \textbf{Frontend:} React, TypeScript, Component Architecture, State Management, API Integration
  \item \textbf{Backend:} Java 11–17, Spring Boot, REST APIs, GraphQL (Resolvers), Node.js, Redis
  \item \textbf{Cloud \& DevOps:} AWS (EC2, ECS/EKS, S3, CloudWatch, IAM), Docker, Jenkins, GitHub Actions, Terraform
  \item \textbf{Databases:} PostgreSQL, MySQL (indexes, partitions, query optimization)
  \item \textbf{Observability:} OpenTelemetry, Grafana, Log Aggregation, API Profiling
\end{itemize}

% =======================
% WORK EXPERIENCE
% =======================
\cvsection{Work Experience}

\textbf{Software Developer Intern \textbar{} LidVizion LLC (Remote)} \hfill Jul 2025 -- Present
\begin{itemize}
  \item Built internal analytics dashboards using \textbf{React + TypeScript}, reducing UI duplication by \textbf{40\%} through reusable component design.
  \item Engineered \textbf{Spring Boot microservices} for multi-tenant workloads, cutting p99 latency by \textbf{38\%} through Redis caching and async handlers.
  \item Implemented \textbf{GraphQL resolvers} to eliminate REST over-fetching, reducing payload size by \textbf{45\%}.
  \item Automated cloud deployments with \textbf{Terraform + ECS/EKS}, decreasing release-related incidents by \textbf{50\%}.
  \item Added \textbf{OpenTelemetry traces + Grafana dashboards}, improving debugging and triage time by \textbf{50\%}.
\end{itemize}

\vspace{0.5em}

\textbf{Associate Consultant \textbar{} Ernst \& Young LLP} \hfill Oct 2021 -- Jun 2023
\begin{itemize}
  \item Built workflow modules using \textbf{React + Spring Boot APIs}, increasing regulatory task throughput by \textbf{22\%}.
  \item Developed \textbf{high-volume microservices} for 50+ enterprise clients, improving query performance by \textbf{28\%} using Redis caching + indexed queries.
  \item Built automation utilities in \textbf{Node.js} for validation and batch operations, reducing manual workload by \textbf{30\%}.
  \item Performed \textbf{JMeter load testing + JVM profiling} (GC, heap, thread tuning), improving peak-load stability by \textbf{32\%}.
  \item Implemented CloudWatch + Grafana dashboards, reducing incident diagnosis time by \textbf{30\%}.
\end{itemize}

\vspace{0.5em}

\textbf{Software Engineer \textbar{} Datapro IT Pvt. Ltd.} \hfill Jan 2019 -- Sep 2021
\begin{itemize}
  \item Delivered customer-facing web modules using \textbf{React + Spring Boot}, reducing user-input errors by \textbf{15\%}.
  \item Built microservices supporting financial workflows with \textbf{99.9\% uptime} across peak processing loads.
  \item Optimized PostgreSQL using \textbf{BTREE indexes, RANGE partitioning}, improving reporting latency by \textbf{30\%}.
  \item Implemented distributed caching and retry patterns, reducing downstream timeout failures by \textbf{25\%}.
  \item Automated CI/CD using \textbf{Docker + Jenkins}, cutting deployment cycle time by \textbf{50\%}.
\end{itemize}

% =======================
% PROJECTS
% =======================
\cvsection{Projects}
\begin{itemize}
  \item \textbf{MemVra – Full-Stack Memory Platform} \\
  Designed React UI + Spring Boot backend with Redis caching; added GraphQL edges for structured metadata. Achieved <\textbf{300ms} average API latency.

  \item \textbf{Echo – Real-Time Sync System} \\
  Built React frontend with WebSocket-based live updates; deployed backend to AWS ECS, enabling multi-region synchronization with \textbf{near-zero downtime}.

  \item \textbf{SOMA – Sustainability Analytics} \\
  Built ingestion pipelines using Spring Boot + Node utilities and created React dashboards for performance metrics and visualizations.
\end{itemize}

% =======================
% EDUCATION
% =======================
\cvsection{Education}
\begin{itemize}
  \item M.S. in Computer Science, University of South Dakota (GPA 3.6/4.0)
  \item B.Tech in Computer Science, JNTUH (GPA 3.3/4.0)
\end{itemize}

% =======================
% CERTIFICATIONS
% =======================
\cvsection{Certifications}
\begin{itemize}
  \item AWS Certified Solutions Architect – Associate
  \item Oracle Certified Professional: Java SE 17 Developer
  \item OCI 2025 Generative AI Professional
\end{itemize}

\end{document}
