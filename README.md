# Core Methods in Educational Data Mining: Syllabus 

Introduction class - Yay! Best class eva!

* **Course:** [HUDK 4050, Teachers College, Columbia](http://www.columbia.edu/~rsb2162/EDM2015/index.html)
* **Instructor:** Charles Lang, [charles.lang@tc.columbia.edu](lang2@tc.columbia.edu), Twitter: @learng00d
* **Course Assistants:** Anna Lizarov, [al38684@tc.columbia.edu](al3868@tc.columbia.edu), Aidi Bian, [ab4499@tc.columbia.edu](ab4499@tc.columbia.edu)
* **Day/Time:** Tuesdays/Thursdays, 5:10pm - 6:50pm  
* **Location:** TH 136
* **Instructor Office Hours:** Thursdays, 3:00pm - 5:00pm in GDH 454 - **[Please make an appointment to attend office hours here](https://calendar.google.com/calendar/selfsched?sstoken=UUNxY1RIY01kNmJZfGRlZmF1bHR8M2U5ODgxZmNiOWQ0NDc2N2VmNWQ0NThiM2JmMGRmZmQ)** 
**(If no appointments are available or you cannot attend those that are please send an email to charles.lang@tc.columbia.edu and CC amy@x.ai)**   

*  **Prerequisite:** HUDM 5122 *or* HUDM 5126 *or* approved statistics/computer science data mining course.
*  **Credits:** 3
*  **Required Technology:** Laptop with RStudio installed, Phone with the Sensor Kinetics Pro app installed

## Course Description

The Internet and mobile computing are changing our relationship to data. Data can be collected from more people, across longer periods of time, and a greater number of variables, at a lower cost and with less effort than ever before. This has brought opportunities and challenges to many domains, but the full impact on education is only beginning to be felt. Core Methods in Educational Data Mining provides an overview of the use of new data sources in education with the aim of developing students’ ability to perform analyses and critically evaluate their application in this emerging field. It covers methods and technologies associated with Data Science, Educational Data Mining and Learning Analytics, as well as discusses the opportunities for education that these methods present and the problems that they may create.

## Course Goals

The overarching goal of this course is for students to acquire the knowledge and skills to be intelligent producers and consumers of data mining in education. By the end of the course students should:

 * Systematically develop a line of inquiry utilizing data to make an argument about learning
 * Be able to evaluate the implications of data science for educational research, policy, and practice 

This necessarily means that students become comfortable with the educational applications of three domain areas: computer science, statistics and the context surrounding data use. There is no expectation for students to become experts in any one of these areas but rather the course will aim to: enhance student competency in identifying issues at the level of data acquisition, data analysis and application of analyses to the educational enterprise.

## Assessment

In HUDK4050 students will be attempting several data science projects, however, unlike most courses, students will not be asssessed based on how successful they are in completing these projects. Rather students will be assessed on two key components that will contribute to their future sucess in the field: contribution and organization. **Contribution** reflects the extent to which students participate in the course, whether or not students complete assignments and quizzes, attend class, etc. **Organization** reflects how well students document their process and maintain data and software resources. For example, maintaining a well organized bibliographic library with notes, maintaining a well organized Github account and maintaining organized data sets that are labelled appropriately. To do well in HUDK 4050 requires that students finish the course with the resources to sucessfully use data science in education *in the future*. Do the work and stay organized and all will be well!

Tasks that need to be completed during the semester:

Weekly:
 * Attend class
 * Weekly readings
 * Notes on weekly readings
 * Complete Swirl course
 * Maintain documentation of work (Github, R Markdown)

One time only:
 * Ask one question on Stack Overflow
 * Attend office hours once
 * 8 short assignments (including one group assignment)
 * Group presentation of group assignment, 3-5 students each


## Week-by-week

<A HREF="#unit1">Unit 1: Introduction</A>

<A HREF="#unit2">Unit 2: Data Sources & Their Manipulation</A>

<A HREF="#unit3">Unit 3: Structure Discovery</A>

<A HREF="#unit4">Unit 4: Prediction</A>

# <A NAME="unit1:">Unit 1: Introduction

## Class 1 - Introduction (9/5/18)
### Learning Objectives

* Be familiar with course philosophy, logic & structure
* Install and be familiar with the software to be used in the course
* Appreciate the importance of tightly defining educational goals

## Class 2 - LA, EDM and the Learning Sciences (9/10/18)

### Learning Objectives

* Be familiar with the kinds of work done in the fields of LA and EDM

### Tasks to be completed:

Read/watch:
  * [Siemens, George. and Baker, Ryan S.J. d. 2012. Learning Analytics and Educational Data Mining: Towards Communication and Collaboration. Proceedings of the 2nd International Conference on Learning Analytics and Knowledge (New York, NY, USA, 2012), 252–254.](http://www.upenn.edu/learninganalytics/ryanbaker/LAKs%20reformatting%20v2.pdf)
  
Read chapter 1-3:
  * [Grolemund, Garrett. 2014. Hands-On Programming with R](https://d1b10bmlvqabco.cloudfront.net/attach/ighbo26t3ua52t/igp9099yy4v10/igz7vp4w5su9/OReilly_HandsOn_Programming_with_R_2014.pdf)

#### Due: Assignment 1 - Set up

## Class 3 - Data Sources (9/12/18)

* Be familiar with a range of data sources, formats and extraction processes
* Be familiar with R & Github & markdown

### Tasks to be completed:

Read:
* [Bergner, Yoav. (2017). Measurement and its Uses in Learning Analytics. In C. Lang, G. Siemens, A. F. Wise, & D. Gaševic (Eds.), The Handbook of Learning Analytics (1st ed., pp. 34–48). Vancouver, BC: Society for Learning Analytics Research.](http://solaresearch.org/hla-17/hla17-chapter1)
* [The R Markdown Cheat sheet: 2014.](http://shiny.rstudio.com/articles/rm-cheatsheet.html)

Swirl:
* Unit 1 - Introduction

# <A NAME="unit2">Unit 2: Data Sources & their Manipulation

## Class 4 - Data Wrangling (9/17/18)

### Learning Objectives:

 * Understand the importance of workflow and recording workflow

### Tasks to be completed:

Read:
* [Prinsloo, Paul, & Slade, Sharon (2017). Ethics and Learning Analytics: Charting the (Un)Charted. In C. Lang, G. Siemens, A. F. Wise, & D. Gaševic (Eds.), The Handbook of Learning Analytics (1st ed., pp. 49–57). Vancouver, BC: Society for Learning Analytics Research.](https://solaresearch.org/hla-17/hla17-chapter4/)
* [Greller, Wendy, & Drachsler, Hendrik. (2012). Translating Learning into Numbers: A Generic Framework for Learning Analytics. Journal of Educational Technology & Society, 15(3), 42–57.](https://www.jstor.org/stable/jeductechsoci.15.3.42?seq=1#page_scan_tab_contents)
 
## Class 5 - Data Wrangling (9/19/18)

### Learning Objectives:

 * Be able to perform a data tidying workflow

### Tasks to be completed:

Read:
* [Saturday Morning Breakfast Cereal: 2016.](http://www.smbc-comics.com/index.php?id=3978)

* [Data Wrangling Cheatsheet: 2015.](http://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf)

## Class 6 - Data Wrangling (9/24/18)

Read:
* [Clow, Doug. 2014. Data wranglers: human interpreters to help close the feedback loop. Proceedings of the Fourth International Conference on Learning Analytics And Knowledge (2014), 49–53.](http://oro.open.ac.uk/40608/2/Clow-DataWranglers-final.pdf)
* [Young, Jeffrey R. 2014. Why Students Should Own Their Educational Data. The Chronicle of Higher Education Blogs: Wired Campus.](http://chronicle.com/blogs/wiredcampus/why-students-should-own-their-educational-data/54329)

## Class 7 - Data Wrangling (9/26/18)

### Learning Objectives:

 * Be familiar with a range of data manipulation commands

### Tasks to be completed:

Read:
* [Data Wrangling Cheatsheet: 2015.](http://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf)

Swirl:
* Unit 2 - Data Sources & Manipulation  

# <A NAME="unit3">Unit 3: Structure Discovery

## Class 8 - Teachley Class Visit (10/1/18)

## Class 9 - Start Social Networks (10/3/18)

## Class 10 - Check-in Exam (10/8/18)

### Learning Objectives:

 * Understand the place of data visualization in the data analysis cycle
 * Be familiar with a range of data simulation commands

## Class 11 - Visualization (10/10/18)

### Learning Objectives:

 * Be able to generate basic visualizations during on-the-fly analysis

Read:
* [Gelman, A., & Unwin, A. (2012). Infovis and Statistical Graphics: Different Goals, Different Looks (with discussion)](http://www.stat.columbia.edu/~gelman/research/published/vis14.pdf)  
* [Fung, K. (2014). Junkcharts Trifecta Checkup: The Definitive Guide](http://junkcharts.typepad.com/junk_charts/junk-charts-trifecta-checkup-the-definitive-guide.html)  

## Class 12 - Networks (10/15/18)

### Learning Objectives:

 * Understand the basic premise of graph theory applied to social networks

### Tasks to be completed:

Read:
* [Grunspan, D. Z., Wiggins, B. L., & Goodreau, S. M. (2014). Understanding Classrooms through Social Network Analysis: A Primer for Social Network Analysis in Education Research. CBE-Life Sciences Education, 13(2), 167–178.](http://www.lifescied.org/content/13/2/167.full.pdf)

## Class 13 - Networks (10/17/18)

### Learning Objectives:

 * Conceptualize a data structure suitable for network analysis, generate a network and produce basic summary metrics

### Tasks to be completed:

Read:

* [Hanneman, R.A. and Riddle, M. Chapter 1: Social Network Data. Introduction to Social Network Methods.](http://faculty.ucr.edu/~hanneman/nettext/C1_Social_Network_Data.html)

#### Due: Assignment 2 - Social Network

## Class 14 - Clustering (10/22/17)
### Learning Objectives:

 * Understand the basic principle and algorithm behind cluster analysis

### Tasks to be completed:

Read:
* [Bowers, A.J. (2010) Analyzing the Longitudinal K-12 Grading Histories of Entire Cohorts of Students: Grades, Data Driven Decision Making, Dropping Out and Hierarchical Cluster Analysis. Practical Assessment, Research & Evaluation (PARE), 15(7), 1-18.](http://pareonline.net/pdf/v15n7.pdf)

## Class 15 - Clustering (10/24/17)

### Learning Objectives:

 * Create a suitable data structure and perform clustering on a sample

### Tasks to be completed:

Watch:
* Chapter 7 in Baker, R. (2014). Big Data in Education: [video 1](https://youtu.be/mgXm3AwLxP8), [video 2](https://youtu.be/B9dvJYwBfmk)

## Class 16 - Principal Component Analysis (10/29/18)

### Learning Objectives:

 * Be familiar with the basic ideas behind dimension reduction and the reasons for needing it
 * Understand the basic principles behind Principal Component Analysis

### Tasks to be completed:

Read:
* [Visually Explained](http://setosa.io/ev/principal-component-analysis/)
* [Konstan, J. A., Walker, J. D., Brooks, D. C., Brown, K., & Ekstrand, M. D. (2015). Teaching Recommender Systems at Large Scale: Evaluation and Lessons Learned from a Hybrid MOOC. ACM Trans. Comput.-Hum. Interact., 22(2), 10:1–10:23.](https://dl.acm.org/citation.cfm?id=2728171)

## Class 17 - Principal Component Analysis (10/31/18)

### Learning Objectives:

 * Perform principal component analysis 

### Tasks to be completed:

Watch:
* [Georgia Tech 2015. Feature Selection. Youtube.](https://www.youtube.com/watch?v=8CpRLplmdqE)

## Class 18 - Domain Structure Discovery (11/5/18)

### Learning Objectives:

 * Be familiar with the range of strategies for mapping domains and skills

### Tasks to be completed:

Read:
* [Matsuda, N., Furukawa, T., Bier, N., & Faloutsos, C. (2015). Machine Beats Experts: Automatic Discovery of Skill Models for Data-Driven Online Course Refinement. International Educational Data Mining Society.](http://eric.ed.gov/?id=ED560513) 

#### Due: Assignment 3 - Clustering

## Class 19 - Domain Structure Discovery (11/7/18)

### Learning Objectives:

 * Be familiar with the Q-matrix method

### Tasks to be completed:

Watch:
* Chapter 7 in Baker, R. (2014). Big Data in Education:[video 6](https://youtu.be/oFSV6-opnws)

Swirl:
* Unit 3 - Structure Discovery

# <A NAME="unit4">Unit 4: Prediction

## Class 20 - Prediction (11/12/18)

##### Due: Assignment 4 - Principal Component Analysis

### Learning Objectives:

 * Understand why prediction is desireable goal, the various meanings of the word and general strategies employed across statistics, machine learning and experimental psychology

### Tasks to be completed:

Read:
* [Kucirkova, N. and FitzGerald, E. 2015. Zuckerberg is Ploughing Billions into “Personalised Learning” – Why? The Conversation.](https://theconversation.com/zuckerberg-is-ploughing-billions-into-personalised-learning-why-51940)
* [Brooks, C., & Thompson, C. (2017). Predictive Modelling in Teaching and Learning. In The Handbook of Learning Analytics (1st ed., pp. 61–68). Vancouver, BC: Society for Learning Analytics Research.](https://solaresearch.org/hla-17/hla17-chapter5/)

## Class 21 - Prediction (11/14/18)

### Learning Objectives:

 * Employ a linear prediction model 

### Tasks to be completed:

Watch:
* Chapter 1 in Baker, R. (2014). Big Data in Education: [video 1](https://youtu.be/dc5Nx3tyR8g)

## Class 22 - Classification (11/19/18)

### Learning Objectives:

 * Understand the concept of classification and its relationship to modeling

### Tasks to be completed:

Read:

* [Liu, R., & Koedinger, K. (2017). Going Beyond Better Data Prediction to Create Explanatory Models of Educational Data. In The Handbook of Learning Analytics (1st ed., pp. 69–76). Vancouver, BC: Society for Learning Analytics Research.](https://solaresearch.org/hla-17/hla17-chapter6/)

#### Due: Assignment 5 - Prediction

## Class 23 - Classification (11/21/18) - Thanksgiving No Class

### Learning Objectives:

 * Implement a CART model

### Tasks to be completed:

Watch:
* Chapter 1 in Baker, R. (2014). Big Data in Education: [video 3](https://youtu.be/k9Z4ibzH-1s) & [video 4](https://youtu.be/8X0UlMShss4)

## Class 24 - Diagnostic Metrics (11/26/18)

### Learning Objectives:

 * Understand and apply the following diagnostic metrics to models: Kappa, A', correlation, RMSE, ROC

### Tasks to be completed:

Read:
* [Zheng, A. 2015. Evaluating Machine Learning Models. O’Reily Media. Chapter 2: Evaluation Metrics p.7-18](http://www.oreilly.com/data/free/evaluating-machine-learning-models.csp?intcmp=il-data-free-lp-lgen_free_reports_page)

Watch:
* Chapter 2 in Baker, R. (2014). Big Data in Education: [video 2](https://youtu.be/fGMFYTHhcHg), [video 3](https://youtu.be/9PDwRdyb6Sw) and [video 4](https://youtu.be/7r3hfJW1gz0)
* Chapter 2 in Baker, R. (2014). Big Data in Education: [video 5](https://youtu.be/1P34cxpEdKA)
* [Georgia Tech 2015. Cross Validation. Youtube.](https://youtu.be/sFO2ff-gTh0)

## Class 25 - Knowledge Tracing (11/28/18)

### Vectr Class Visit

### Learning Objectives:

 * Understand the concepts behind Bayesian Knowledge Tracing 

### Tasks to be completed:

Read:
[Corbett, A.T., Anderson, J.R. (1995) Knowledge Tracing: Modeling the Acquisition of Procedural Knowledge. User Modeling and User-Adapted Interaction, 4, 253-278.](https://link.springer.com/article/10.1007/BF01099821)

Swirl:
* Unit 4 - Prediction


## Class 26 - Knowledge Tracing (12/3/18)

### Learning Objectives:

 * Understand Bayesian Knowledge Tracing 

### Tasks to be completed:

Watch:
* Chapter 4 in Baker, R. (2014). Big Data in Education: [video 1](https://youtu.be/_7CtthPZJ70)

#### Due: Assignment 6 - CART Models

## Class 27 - Work Session: Assignment 8, Group Project (12/5/18)

## Class 28 - Work Session: Assignment 8, Group Project (12/10/18)

##### Due: Assignment 7 - Diagnostic Metrics

## Class 29 - Rate video presentations (12/12/18)

## Class 30 - Rate video presentations (12/17/18)

## EVERYTHING DUE - 12/19/18

----------------------------------------------------

# Fine Print

1. All examinations, papers, and other graded work and assignments are to be completed in conformance with the [Academic Integrity Policy](http://www.tc.columbia.edu/administration/diversity/index.asp? Id=Civility+Resources+and+Policies&Info=Civility+Resources+and+Policies&Area=Studen t+Miscon duct+Policy). Students who intentionally submit work either not their own or without clear attribution to the original source, fabricate data or other information, engage in cheating, or misrepresentation of academic records may be subject to charges. Sanctions may include dismissal from the college for violation of the TC principles of academic and professional integrity fundamental to the purpose of the College.

2. The College will make reasonable accommodations for persons with documented disabilities. Students are encouraged to contact the Office of Access and Services for Individuals with Disabilities for information about registration (166 Thorndike Hall). Services are available only to students who are registered and submit appropriate documentation. As your instructor, I am happy to discuss specific needs with you as well.

3. The grade of Incomplete will be assigned only when the course attendance requirement has been met but, for reasons satisfactory to the instructor, the granting of a final grade has been postponed because certain course assignments are outstanding. If the outstanding assignments are completed within one calendar year from the date of the close of term in which the grade of Incomplete was received and a final grade submitted, the final grade will be recorded on the permanent transcript, replacing the grade of Incomplete, with a transcript notation indicating the date that the grade of Incomplete was replaced by a final grade. If the outstanding work is not completed within one calendar year from the date of the close of term in which the grade of Incomplete was received, the grade will remain as a permanent Incomplete on the transcript. In such instances, if the course is a required course or part of an approved program of study, students will be required to re-enroll in the course including repayment of all tuition and fee charges for the new registration and satisfactorily complete all course requirements. If the required course is not offered in subsequent terms, the student should speak with the faculty advisor or Program Coordinator about their options for fulfilling the degree requirement. Doctoral students with six or more credits with grades of Incomplete included on their program of study will not be allowed to sit for the certification exam.

4. Teachers College students have the responsibility for activating the Columbia University Network ID (UNI) and a free TC Gmail account. As official communications from the College – e.g., information on graduation, announcements of closing due to severe storm, flu epidemic, transportation disruption, etc. -- will be sent to the student’s TC Gmail account, students are responsible for either reading email there, or, for utilizing the mail forwarding option to forward mail from their account to an email address which they will monitor.

5. It is the policy of Teachers College to respect its members’ observance of their major religious holidays. Students should notify instructors at the beginning of the semester about their wishes to observe holidays on days when class sessions are scheduled. Where academic scheduling conflicts prove unavoidable, no student will be penalized for absence due to religious reasons, and alternative means will be sought for satisfying the academic requirements involved. If a suitable arrangement cannot be worked out between the student and the instructor, students and instructors should consult the appropriate department chair or director. If an additional appeal is needed, it may be taken to the Provost.

