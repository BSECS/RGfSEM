# RGfSEM
R GUI for SEM - R based Web application for Structural Equation Modelling 

RGfSEM is an open source web application for Structural Equation Modeling (SEM). SEM is widely used technique for research related to social sciences like Economics, Commerce and Business Administration. SEM practice is widely increasing in academics and industry particularly for research related to beahavioral sciences. 

Read more about SEM at https://en.wikipedia.org/wiki/Structural_equation_modeling

This web application is created using R + Shiny. Shiny is one of the very good web frameworks available for R programmers to create network based server level statistical applications. Thanks to creators of Shiny particularly RStudio team. 

This app has SEM implemented through both EFA & CFA. It is possible for users to obtain path diagrams for both EFA and CFA. 

I specially would like to thank Prof. WILLIAM REVELLE of NorthWestern University for creating a wounderful library "psych" which is widely used in psychometrics. It might not be possible for me to create this app, if he had not done such a commendable work. He is inspiration to budding statisticians like me. Read more about "psych" at https://cran.r-project.org/web/packages/psych/index.html. If you are new to SEM, you definitely have to read his vignette https://personality-project.org/r/book/psych_for_sem.pdf. Salutes to Prof. W. Revelle from bottom of my heart. 

This application is not an alternative to AMOS like GUI based SEM applications. Moreover, it is rather more simpler than such applications while performing SEM. The implementation model for RGfSEM is very simple, (1) upload data, (2) click options and (3) get results (inlcuding numerical analysis and visuals). 

This application depends on few libraries such as (1) shiny, (2) shinydashboard, (3) nortest, (4) mvnormtest, (5) MASS, (6)   lavaan, (7) psych and (8) sem. You need to install these packages in RStudio well before starting this application. If you don't know as how to install R packages, read https://www.r-bloggers.com/installing-r-packages/ for details. For instace, to install "psych" at R prompt execute "install.packages("psych")" [without quotes]. 

For queries and consultancy contact me: +919177573730; kamakshaiah.m@gmail.com
