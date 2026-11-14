\\documentclass\[10pt,a4paper]{article}



\\usepackage\[T1]{fontenc}

\\usepackage\[utf8]{inputenc}

\\usepackage{lmodern}

\\usepackage\[a4paper,top=0.45in,bottom=0.45in,left=0.55in,right=0.55in]{geometry}

\\usepackage{enumitem}

\\usepackage{titlesec}

\\usepackage\[hidelinks]{hyperref}

\\usepackage{microtype}

\\usepackage{tabularx}



\\pagestyle{empty}

\\setlength{\\parindent}{0pt}

\\setlength{\\parskip}{0pt}

\\setlength{\\tabcolsep}{0pt}

\\urlstyle{same}

\\linespread{1.00}

\\emergencystretch=1em



\\titleformat{\\section}

&#x20; {\\bfseries\\small}

&#x20; {}{0pt}{}

&#x20; \[\\vspace{-2pt}\\titlerule]



\\titlespacing\*{\\section}{0pt}{5pt}{3pt}



\\setlist\[itemize]{

&#x20; leftmargin=13pt,

&#x20; itemsep=0pt,

&#x20; topsep=1pt,

&#x20; parsep=0pt,

&#x20; partopsep=0pt

}



\\newcommand{\\resumeSubheading}\[4]{%

&#x20; \\begin{tabular\*}{\\textwidth}{@{}l@{\\extracolsep{\\fill}}r@{}}

&#x20;   \\textbf{#1} \& \\textbf{#2} \\\\

&#x20;   \\textit{#3} \& \\textit{#4}

&#x20; \\end{tabular\*}\\vspace{-3pt}

}



\\newcommand{\\resumeProject}\[2]{%

&#x20; \\textbf{#1}\\hfill{\\small\\textit{#2}}\\vspace{-3pt}

}



\\begin{document}



\\begin{center}

&#x20; {\\LARGE\\bfseries SHUBHAM KUMAR}\\\\\[2pt]

&#x20; {\\small\\bfseries SOFTWARE ENGINEERING \\;|\\; BACKEND DEVELOPMENT \\;|\\; AI SYSTEMS}\\\\\[2pt]

&#x20; New Delhi, India \\;|\\; +91-7836878701 \\;|\\;

&#x20; \\href{mailto:shubham1sure@gmail.com}{shubham1sure@gmail.com}\\\\\[2pt]

&#x20; \\href{https://nothing0g.github.io/analyst/}{Portfolio}

&#x20; \\;|\\;

&#x20; \\href{https://github.com/Nothing0g}{GitHub}

&#x20; \\;|\\;

&#x20; \\href{https://www.linkedin.com/in/shubham-kumar-diff/}{LinkedIn}

\\end{center}



\\vspace{-8pt}



\\section\*{PROFILE}

Software-focused engineering student at Delhi Technological University building Python backend services and AI-assisted workflows. Led backend and integration for a three-person AI hackathon project using FastAPI and LangGraph. Built API-first prototypes with data validation, evidence retrieval, automated evaluation, and regression tests, with a focus on reliable, maintainable software.



\\section\*{EDUCATION}

\\resumeSubheading

&#x20; {Delhi Technological University}{New Delhi, India}

&#x20; {Bachelor of Technology in Mechanical Engineering}{Aug 2023 -- May 2027}



\\section\*{EXPERIENCE}



\\resumeSubheading

&#x20; {NTPC Dadri}{Gautam Buddh Nagar, Uttar Pradesh}

&#x20; {Summer Trainee -- Turbine Maintenance}{Jun 2026 -- Jul 2026}

\\begin{itemize}

&#x20; \\item Reviewed HP/LP turbine operation and maintenance data at a 2,000 MW plant, then documented energy-conversion patterns and maintenance workflows in a 40-page report linked to P\\\&ID references.

\\end{itemize}



\\resumeSubheading

&#x20; {CrackNonTech}{Delhi}

&#x20; {Analyst Fellow}{May 2026 -- Jul 2026}

\\begin{itemize}

&#x20; \\item Structured open-ended profitability, market-entry, and industry cases into clear analytical questions, assumptions, and decision criteria.

&#x20; \\item Used Python and SQL to analyze business datasets, validate findings, and translate results into recommendations and stakeholder-ready presentations.

\\end{itemize}



\\resumeSubheading

&#x20; {DRDO -- Solid State Physics Laboratory (SSPL)}{New Delhi, India}

&#x20; {Research Intern}{Dec 2025 -- Jan 2026}

\\begin{itemize}

&#x20; \\item Studied Pulse Tube and Dilution Refrigeration cycles for defense-electronics cooling below 4 K, interpreting cryogenic schematics and thermodynamic relationships for a team technical report.

\\end{itemize}



\\resumeSubheading

&#x20; {Engineers India Limited (EIL)}{Gurugram, Haryana}

&#x20; {Plant Design Intern}{Jun 2025 -- Jul 2025}

\\begin{itemize}

&#x20; \\item Prepared and revised AutoCAD plant layouts and piping drawings, translating engineering requirements and design-review feedback into accurate technical deliverables.

&#x20; \\item Applied ASME/IS piping standards, GD\\\&T principles, and CAESAR II pipe-stress concepts while reviewing fabrication-readiness requirements.

&#x20; \\item Automated a recurring Excel expenditure-reporting workflow and received an ``Excellent'' final internship evaluation.

\\end{itemize}



\\section\*{PROJECTS}



\\resumeProject

&#x20; {\\href{https://nothing0g.github.io/analyst/projects/truestack-ai-assistant/}{TrueStack -- AI-Powered University Services Assistant}

&#x20; \\hspace{3pt}\\textnormal{\\textit{\[\\href{https://github.com/Nothing0g/TrueStack\_HCLTech\_aiHackathon}{GitHub}]}}}

&#x20; {Python, FastAPI, LangGraph, SQLite}

\\begin{itemize}

&#x20; \\item Led backend and integration for a three-person hackathon team, defining shared interfaces and connecting retrieval with deterministic tools through a central LangGraph workflow.

&#x20; \\item Built FastAPI/Pydantic endpoints and integrated cited policy retrieval, SQLite-backed tools, structured responses, trace IDs, audit logging, and local Docker execution.

&#x20; \\item Added routing and validation for policy versus data-dependent questions, access checks, and explicit handling of unsupported requests.

\\end{itemize}



\\resumeProject

&#x20; {\\href{https://nothing0g.github.io/analyst/projects/turbine-maintenance-copilot/}{Turbine Maintenance Intelligence Copilot}

&#x20; \\hspace{3pt}\\textnormal{\\textit{\[\\href{https://github.com/Nothing0g/turbine-maintenance-copilot}{GitHub}]}}}

&#x20; {Python, FastAPI, pandas, Testing}

\\begin{itemize}

&#x20; \\item Built a FastAPI decision-support service for telemetry validation, rolling z-score anomaly detection, and procedure retrieval, returning structured recommendations with uncertainty and human-review flags.

&#x20; \\item Added reproducible evaluation, API/data-quality checks, logging, and regression tests; fixed a timestamp-window selection bug and retained a test to prevent recurrence.

&#x20; \\item Evaluated anomaly detection, retrieval hit rate, response validity, missing-data abstention, and latency using generated telemetry and documented procedures rather than confidential plant records.

\\end{itemize}



\\resumeProject

&#x20; {\\href{https://nothing0g.github.io/analyst/projects/pid-engineering-document-intelligence/}{P\\\&ID Engineering-Document Intelligence}

&#x20; \\hspace{3pt}\\textnormal{\\textit{\[\\href{https://github.com/Nothing0g/pid-engineering-document-intelligence}{GitHub}]}}}

&#x20; {Python, FastAPI, Graph Modeling}

\\begin{itemize}

&#x20; \\item Developed a revision-aware service that converts synthetic P\\\&ID metadata into typed entities and graph relationships, validates connections, and compares document revisions.

&#x20; \\item Added source-linked answers and review flags; fixed a revision-comparison bug that missed deleted entities and retained regression coverage.

\\end{itemize}



\\section\*{SKILLS}

\\textbf{Programming:} Python, SQL, OOP fundamentals, data structures and algorithms\\\\

\\textbf{Backend Engineering:} FastAPI, Django, REST APIs, Pydantic, request validation, API testing\\\\

\\textbf{Data \\\& AI Systems:} pandas, NumPy, scikit-learn, RAG, embeddings, LangGraph, ChromaDB, SQLite\\\\

\\textbf{Engineering Practices:} Git/GitHub, debugging, regression testing, CI, logging, Docker, documentation\\\\

\\textbf{Additional Tools:} Excel, AutoCAD, SolidWorks, Siemens NX



\\section\*{CERTIFICATIONS \\\& ACHIEVEMENTS}

{\\fontsize{9.2pt}{10.2pt}\\selectfont

\\textbf{Certifications:} Python for Data Science, AI \\\& Development; Git/GitHub -- 2024.\\\\\[-1pt]

\\textbf{Achievements:} Dell Aspire Scholar 2023 -- Michael \\\& Susan Dell Foundation; NCC ``A'' Certificate; School House Captain.

}



\\end{document}

