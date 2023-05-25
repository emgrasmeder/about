# Emma Grasmeder
#### Code Witch

[Speaking Engagements](speaking-engagements.md)

I'm a functional programming enthusiast with a background in data science. I'm currently spending my days thinking about category theory, phenomenology, game development, and fixing up a rusty old sailboat while I look for a job. I'm comfortable in the role of technical lead and am drawn towards conversations around business goals and product vision, but happiest writing code most of the time. I believe that almost all the times when a tech endeavor fails, it's not because the technology was too complicated but because _people are complicated_. I think it's vital to focus on the humans - from the customers to the development team to management structures. 

Whether in a position of leadership or not, I try to approach problems the same way: as an anarchist. I believe in the power of consensus, accountability, taking personal responsibility, and asking, "what are the systemic problems?" and "how can we make this better for everyone?"

## Relevant Experience
### Software Developer, StackOverflow - Teams Product (October 2022-May 2023)
Overview: Develop features in to support StackOverflow for Teams users to create, find, and collaborate on content

Core Responsibilities:
- Develop frontend and backend systems that build on top of 10+ year old legacy systems which service 100+ million visitors per month
- Write code in a modular fashion to extend the capabilities in a large code monolith
- Code review, planning, prioritization with the rest of this fast moving team
- Work with Product Managers to understand and prioritize tech debt and remove unnecessary work from the backlog in order to move more quickly

Interesting Challenges:
- Finally learning Object Oriented Programming
- Working on a 14 year old code base
- Developing in a monolith to be deployed on premise
- Supporting 100+ million visitors each month.
###### Core technologies involved: C#, .NET, Microsoft SQL Server, Playwright


### Software Developer, WeFarm - Agriculture E-Commerce Platform (May 2022-July 2022)
Overview: Transition from legacy system to modern system without interruption of hundreds of regular daily active users workflow. 

Core Responsibilities:
- Shut down the convoluted spreadsheet based workflow for store management
- Plan and execute gradual changes that allowed for continuous integration of newly developed backend system
- Build alternative workflows for test users to interact with, allowing for simultaneous use of two workflows on two systems
- Code review, planning, prioritization with the rest of this fast moving team

Interesting Challenges:
- Learning ClojureScript on the go
- Building a new living system inside / behind the old system. We needed to continue writing to the old system for the entirety of the project for accounting reasons, and the new system could only be fully relied upon after the entire transition was ready to go.
###### Core technologies involved: Clojure, ClojureScript


### Technical Lead/Tech Principal, ThoughtWorks - Chemical Production Company (November 2020-September 2021)
Overview: The client hired us to develop a workflow which enabled their data scientists to track and version their data, code, and models in a comprehensive way.

Core Responsibilities:
- Introduce and cultivate an agile mindset for a diverse team of infrastructure engineers, data scientists, and fullstack developers
- Contribue code to (TypeScript) front end
- Develop data visualizations for data models
- Improving infrastructure through Helm Charts or Azure Pipeline definitions
- Define, prioritize, and plan work for the team
- Develop automatic pipeline for training, versioning, and deploying data science models from any number of data scientists at the company

Interesting Challenges:
- Developing a technical vision within a large company that's ready to invest in modernization
- Bridging the communication gap between research scientists and infrastructure engineers
- Architecting a solution for versioning data science models, versioning multiple data sources, and making insights of the models accessible and data readily available
###### Core technologies involved: Python, Javascript + TypeScript, Azure


### Technical Lead, ThoughtWorks - Retail and Logistics (August 2020 - October 2020)
Overview: The goal of this project was to convert a complicated and outdated system of emails and Excel tables into an automated, tested, validated data pipeline in 3 months, with a team of 4.

Core Responsibilities: 
- Identify critical workflows to automate, understand business context, and produce sustainable but minimal working product
- Onboard 3 team members to exploratory data analysis, feature engineering, and data transformations with an eye on testing and performance 
- Consulting stakeholders on future planning, coming up with different roadmaps depending on what funding becomes available 
Interesting Challenges:
- Having 3 months from inception to product delivery handover of a production system
- Applying functional programming paradigms to data processing workflow
###### Core technologies involved: Python, pandas

### Technical Lead, ThoughtWorks - Railway Industry (May 2019 - March 2020)
Overview: The client hired us to design a product, prototype it, and find a market for the product in an experiment to find new business models for the company.

Core Responsibilities:
- Develop a cloud solution suitable for analyzing millions of records of data from moving trains all around the world
- Design railway-certifiable hardware (i.e. the "black box" for a train) which uploads train sensor data under conditions of uncertain internet connectivity. (Where losing or leaking a single data point could likely result in legal consequenes)
- Collaborated with C-Suite in product and customer strategy. The product my team designed is currently running in trains for several customers
- Train the team of 5, most of whom had never written code professionally, into a team full of effective, confident, and capable developers.
Interesting Challenges:
- Stakeholder management of an hundred year old hardware company, working regularly with sales, hardware development teams, and the CEO and CTO. 
- Designing a product while prototyping, gathering customer feedback, and generally bringing a product to market
###### Core technologies involved: Clojure, Javascript, React, AWS, PostgreSQL

### Developer, ThoughtWorks - Automotive (April 2017 - April 2019)
Overview: We had a large contract for building an app to help car salespeople make sales from on the lot. We build everything from the payment process to the car configuration. 
Core Responsibilities:
- Fullstack developer on several teams for the same product, core contributor for several micro-frontend and micro-backend services.
- Heavy emphasis on core functionalities as well as development of contract tests, integration tests, functional tests, and maintenance of the CI/CD pipelines and the 3 deployment environments. 
- Served as security champion for the account for 2 years, inlcuding overseeing a transition to GDPR compliance as the new laws came out
Interesting Challenges:
- Onboarding new team members every few months, and even once a whole new team
- Coordinating safe/reliable deployment of multiple services
###### Core technologies involved: Clojure, Javascript, React + Redux, Openshift, PostgreSQL

### Mapbox, Data Scientist (March 2016 - November 2016)
Overview: I worked as a data scientist on the data-operations team aiming to predict travel tims for cars, bikes, and pedestrians traveling all around the world
- Measured street traffic patterns based on millions of miles of telemetry data (in GeoJSON format)
- Maintained road intersection analysis suite, a custom map-reduce algorithm to accumulate and analyze behavior of cars maneuvering through intersections
- Created statistics libraries to measure confidence for samples of data
        https://github.com/mapbox/sample-sizer
        https://github.com/mapbox/stats-online
- Made feature-engineering decisions for the company's modality filter, a neural net designed to identify GeoJSON linestrings from walking, driving, or biking traffic.
- Managed Amazon EC2 cluster to run analysis on the planet's road network, triggered by a Cron job and a AWS Lambda

### Solebrity, Inc, Chief Data Scientist (Jan 2015 – Jan 2016)
Overview: I was the chief architect and data lead for a budding start up, working with Natural Language Processing (NLP) and recommendation engines to match customers with needs
- Developed REST API and recommendation service in Go for making queries to 2 million product nodes on Neo4j server
    - Makes recommendations based on node relationships and machine learning algorithms with GoML and GoLearn.
- Mentored and trained data science apprentice from “hello world” to deployment of Flask microservice in 3 months
    - Microservice determines major colors of products by first identifying and removing anything in the image except clothing
    - Service was version controlled, tested, bench marked for speed, multithreaded, and deployed on Docker
- Constructed a scalable product recommendation engine using sparse matrices to rapidly calculate the Jaccard similarity coefficient of user purchase histories
    - Originally delivered using Apache Spark
- Tagged 3,500,000 products with gender, style, and product-type tags
- Cross validated several multi-label machine learning classifiers using scikit-learn's Pipeline framework
- Produced training data by finding regex matches to descriptions with highly predictive keywords


### Tech Stuff I'm Proficient in
- Clojure
- Python (Data Science and backend web dev stuff) 
- JavaScript (React, Redux, Node, also some data science)
- Bash (I actually really like Bash for some reason)
- C#
- AWS, Azure


#### Education
- *Ph.D. coursework in Economics, George Mason University* (2012 - 2014)
  - Emphasis on experimental and behavioral economics, statistical programming, decision theory, and information economics
- *B.A. in Philosophy and Religion, James Madison University* (2010)
  -  Two years studying math, two studying philosophy

##### Languages: 
- Native: English
- Advanced/Conversational: German
- Basic: Spanish, Hebrew
