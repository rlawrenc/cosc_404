# COSC 404 - Database System Implementation - Winter T2 2021

## Instructor
Dr. Ramon Lawrence, ramon.lawrence@ubc.ca, 250-807-9390<br>
**Classroom Schedule:** Wednesday/Friday, 12:30 pm - 2:00 pm<br>
**Mode of Delivery:** In-person at Library 312<br>
**Office Hours:**	Wednesdays 2 to 4 p.m. or by an appointment<br>
**Office Location:** ASC 349<br>
**Calendar Course Description, from the UBCO Calendar:** http://www.calendar.ubc.ca/okanagan/courses.cfm?go=name&code=COSC

## TAs
TBD

## Course Description
**Official Calendar:** Fundamental concepts in constructing database systems including file organizations, storage management, system architectures, query processing/optimization, transaction management, recovery, and concurrency control. Additional topics may include distributed databases, mobile databases, and integration. 
**Prerequisite:** COSC 304 and third-year standing.

**Specific description:** This course provides an in-depth study of various approaches and techniques to data management including relational (SQL) databases, NoSQL systems, and techniques for indexing, query processing, and concurrency. Students completing the course will have experience in a wide variety of commerical systems (MySQL, PostgreSQL, MongoDB, Microsoft SQL Server, Snowflake) and the fundamental knowledge of data processing to make key decisions on selecting and optimizing data architectures and systems.

## Course Objectives
**Course Format:** Interactive online classes consisting of topic introduction, understanding evaluation using quick questions, and concept mastery with larger exercises.  Practical skills and applications of topics covered in assignments as well as practice using industrial database systems and software.

**Learning Outcomes:**
 - Experience using and developing on many different SQL and NoSQL databases.
 - Proficiency in manipulating data in memory and storage and using index structures for improved performance. 
 - Understanding of query processing including parsing, translation, optimization, and execution.
 - Applying principles of transactions, concurrency, recovery, and distribution for databases.
 - Using knowledge of database techniques to be better users with the ability to use different database systems, compare their properties, and adapt database techniques when developing software.

## Marking and Evaluation
| Item | Weighting | Description |
|------|-----------|-------------|
| Quizzes and Exercises | 10% | Online and during class time activities |
| Assignments | 25% | Weekly assignments |
| Midterm #1 | 15% | October 19th in class | 
| Midterm #2 | 15% | November 16th in class | 
| Final Exam | 35% | Cumulative, two and half hours, TBD |

**A student must receive a combined grade of at least 50% on the exams (midterms and final) to pass the course.  Otherwise, the student receives a maximum overall grade of 45.**

### COSC 504 - Graduate Student Evaluation
| Item | Weighting | Description |
|------|-----------|-------------|
| Quizzes and Exercises | 5% | Online and during class time activities |
| Assignments | 15% | Weekly assignments |
| Project | 15% | Research paper and presentation |
| Midterm #1 | 15% | October 19th in class | 
| Midterm #2 | 15% | November 16th in class | 
| Final Exam | 35% | Cumulative, two and half hours, TBD |

## Textbook and Reference Material
 - All notes are online.
 - A textbook is not required. Students can get supplemental material from any database textbook.
 - The course uses iClicker Cloud (free). [Setup instructions for iClicker Cloud Student Account](https://lthub.ubc.ca/guides/iclicker-cloud-student-guide/). [iClicker Cloud (REEF) Login](http://app.reef-education.com/)

## Expectations
 - Attend all classes and prepare before attending class. 
 - Review the material before the class time. **Expect to spend about five hours per week in out-of-class preparation.**
 - Learn the material in the course by completing all assignments. **No late assignments are accepted.**
 - Enjoy attending class activities and participate according to your personality.  Ask questions by posting on chat or raising your hand.
 - Please actively participate in class discussions, questions, and problem solving exercises.
 - **I want all students to pass the course, receive a good grade, and feel the course was beneficial.**

## Schedule

|   Date | Topic  | Reading and Resources |
|------------|------|-----------|
| January&nbsp;12&nbsp;(W) 	| First day of classes.  Introduction to course.  Database architecture. | |
| January 14&nbsp;(F)	| Storage: Accessing/Representing Data on Devices (SSD,RAID) using Records/Blocks | |
| January 19 (W)	| Indexing I: Index Types, Primary Indexes, Multi-level Indexes, Secondary Indexes | |
| January 21 (F)	| Indexing II: B-Trees (insertion, deletion), B+-Trees | |
| January 26 (W)	| Indexing III: B+-Trees, R-Trees | |
| January 28 (F)	| Indexing IV: Hash Indexes, SQL Indexing in Practice | |
| February 2 (W)	| Query processing I: SQL/RA Review, Types of Operators, Iterators, One-pass Algorithms | |
| February 4 (F)	| Query processing II: Nested-Loop Joins, External Sorting, Two-Pass Sorting Algorithms, Sort-Join, Sort-Merge-Join | |
| February 9 (W)	| Query processing III: Hash Partitioning, Two-Pass Hash Algorithms, Hybrid Hash Join | |
| February 11 (F)	| Query optimization I: Query Parsing/Translation, Relational Algebra Laws | |
| February 16 (W)	| **Midterm exam #1** | |
| February 18 (F)	| Query optimization II: Heuristic Optimization, Physical Query Plans | |
| February&nbsp;23&nbsp;(W)	| No classes during Midterm Break. | |
| February 25 (F)	| No classes during Midterm Break. | |
| March 2 (W) 		| Query optimization III: Cost-based Query Optimization | |
| March 4 (F) 		| Transaction processing I: ACID Properties, Schedules, Conflict Serializablity | |
| March 9 (W)		| Transaction processing II: View Serializablity, Schedule Properties | |
| March 11 (F)		| Concurrency control I: Two-Phase Locking (2PL), Multiple Granularity Locking, Deadlock Handling, Wait-for Graphs | |
| March 16 (W)		| Concurrency control II: Timestamp Protocols, Validation Protocols, Multi-versioning, Snapshot isolation | |
| March 18 (F)		| **Midterm exam #2** | |
| March 23 (W)		| Concurrency control III: SQL Isolation Levels, Phantom Phenomenon, CC in systems | |
| March 25 (F)		| Recovery I: Types of Failures, Log-Based Recovery | |
| March 30 (W)		| Recovery II: Undo/Redo Logging | |
| April 1 (F)		| Distribution I: Architectures, Semi-joins, Two-Phase Commit | |
| April 6 (W)		| Distribution II: Fragmentation, Partitioning | |
| April 8 (F)		| Distribution III: Replication: Primary-Primary and Primary-Secondary, CAP Theorem<br>Architecture I: Comparison of database architectures: Relational, Key-Value, In-Memory | |


## Labs

|  Lab  |  Date  |  Topic  |
|----|------|-------|
|  		 | January 10 - 14 	| **No Lab during First Week of Class** |
| [1](labs/lab1) | January 17 - 21 	| Lab 1: MySQL vs. PostgreSQL – Creating and Querying Data |
| [2](labs/lab2) | January 24 - 28 	| Lab 2: MySQL vs. PostgreSQL – Indexing for Performance |
| [3](labs/lab3) | Jan. 31 - Feb. 4 	| Lab 3: Implementing a Text Database and JDBC Driver |
| [4](labs/lab4) | February 7 - 11 	| Lab 4: Query Processing with Iterators |
| [5](labs/lab5) | February 14 - 18 	| Lab 5: Query Parsing with JavaCC |
|  		 | February 21 - 25 	| Midterm Break — No Labs |
| [6](labs/lab6) | Feb. 28 - Mar. 4 	| Lab 6: Storing JSON Documents: MongoDB and PostgreSQL |
| [7](labs/lab7) | March 7 - 11 	| Lab 7: Map-Reduce using MongoDB |
| [8](labs/lab8) | March 14 - 18 	| Lab 8: Transactions with Microsoft SQL Server |
| [9](labs/lab9) | March 21 - 25 	| Lab 9: Cloud Data Analysis with Snowflake |
| [10](labs/lab10) | March 28 - Apr. 1 	| Lab 10: Recovering from a Database Failure  |
| [11](labs/lab11) | April 4 - 8 	| Lab 11: Scaling Databases with MySQL and MongoDB |


## Final Examinations
The Final Exam date is TBD.  Except in the case of examination clashes and hardships (three or more formal examinations scheduled within a 24-hour period) or unforeseen events, students will be permitted to apply for out-of-time final examinations only if they are representing the University, the province, or the country in a competition or performance; serving in the Canadian military; observing a religious rite; working to support themselves or their family; or caring for a family member.  Unforeseen events include (but may not be limited to) the following: ill health or other personal challenges that arise during a term and changes in the requirements of an ongoing job.  
Further information on Academic Concession can be found under Policies and Regulation in the Okanagan Academic Calendar http://www.calendar.ubc.ca/okanagan/index.cfm?tree=3,48,0,0

## Missing an Exam
Only students who miss the final exam for a reason that corresponds to the University of British Columbia Okanagan's policy on excused absences from examinations will be permitted to take the final exam at a later time. A make-up exam may have a question format different from the regular exam. There will be no make-up midterm exams.  If the reason for absence is satisfactory, the student’s final exam will be worth more of the final grade.  Further information on Academic Concession is in the Academic Calendar http://www.calendar.ubc.ca/okanagan/index.cfm?tree=3,48,0,0.

## Copyright Disclaimer   
Diagrams and figures included in lecture presentations adhere to Copyright Guidelines for UBC Faculty, Staff and Students http://copyright.ubc.ca/requirements/copyright-guidelines/ and UBC Fair Dealing Requirements for Faculty and Staff http://copyright.ubc.ca/requirements/fair-dealing/.  Some of these figures and images are subject to copyright and will not be posted to Canvas.   All material uploaded to Canvas that contain diagrams and figures are used with permission of the publisher; are in the public domain; are licensed by Creative Commons; meet the permitted terms of use of UBC’s library license agreements for electronic items; and/or adhere to the UBC Fair Dealing Requirements for Faculty and Staff. Access to the Canvas course site is limited to students currently registered in this course. Under no circumstance are students permitted to provide any other person with means to access this material. Anyone violating these restrictions may be subject to legal action. Permission to electronically record any course materials must be granted by the instructor. Distribution of this material to a third party is forbidden.


## Grievances and Complaints Procedures
A student who has a complaint related to this course should follow the procedures summarized below:<br>
- The student should attempt to resolve the matter with the instructor first. Students may talk first to someone other than the instructor if they do not feel, for whatever reason, that they can directly approach the instructor. 
If the complaint is not resolved to the student's satisfaction, the student should e-mail the Associate Head, Dr. Yves Lucet at yves.lucet@ubc.ca  or the Department Head pro tem, Dr. Andrew Jirasek at andrew.jirasek@ubc.ca.

 
## Your Responsibilities
Your responsibilities to this class and to your education as a whole include attendance and participation. You have a
responsibility to help create a classroom environment where all may learn. At the most basic level, this means you will
respect the other members of the class and the instructor and treat them with the courtesy you hope to receive in return.
Inappropriate classroom behavior may include: disruption of the classroom atmosphere, engaging in non-class activities,
talking on a cell-phone, inappropriate use of profanity in classroom discussion, use of abusive or disrespectful language
toward the instructor, a student in the class, or about other individuals or groups.

## Academic Integrity
The academic enterprise is founded on honesty, civility, and integrity.  As members of this enterprise, all students are expected to know, understand, and follow the codes of conduct regarding academic integrity.  At the most basic level, this means submitting only original work done by you and acknowledging all sources of information or ideas and attributing them to others as required.  This also means you should not cheat, copy, or mislead others about what is your work.  Violations of academic integrity (i.e., misconduct) lead to the breakdown of the academic enterprise, and therefore serious consequences arise and harsh sanctions are imposed.  For example, incidences of plagiarism or cheating may result in a mark of zero on the assignment or exam and more serious consequences may apply if the matter is referred to the President’s Advisory Committee on Student Discipline.  Careful records are kept in order to monitor and prevent recurrences. 
A more detailed description of academic integrity, including the University’s policies and procedures, may be found in the Academic Calendar at:  http://okanagan.students.ubc.ca/calendar/index.cfm?tree=3,54,111,0.
  If you have any questions about how academic integrity applies to this course, please consult with your professor.


## Academic Integrity Course Policies
Academic integrity is critical to being a professional developer and a respected person. This is a guide to what is and is not acceptable behaviors in this course.

### In-Class Participation and Quizzes and Teamwork Collaboration
#### Allowed
- Collaboration in groups of up to 4 on Canvas quizzes and in-class exercises

#### Not Allowed
 - One person providing all answers for a quiz/exercise to a group of people of any size
 - Sharing, posting, or distributing answers to other students or websites for quizzes/exercises
 - Answering questions for another student or submitting answers on their behalf
 - Requesting help from previous students in the course or other individuals outside of the course
 - Relying on others to do work for me or not contributing reasonable effort to group activities
 - Dividing up the work for a quiz or exercise between members of an approved group (*Not Recommended*)

### Assignments
#### Allowed
- Collaborating with your approved group members (usually two) and submitting a shared answer to the assignment
- Request help from the TA or instructor and use the answer/code that they provide
- Answer general questions about assignments in chat or discussion forums (*Allowed with care*)

#### Not Allowed
 - Working on an individual assignment with a group of people and submitting minor variations of work developed together
 - For group assignment, completing all work independently and providing answer to rest of group
 - Sharing solutions to assignments with other students or on the Internet	
 - Receiving solutions to assignments from other sources (students, web, tutors)	
	
### Exams
#### Allowed
- Using course material including assignments, notes, and quizzes in an open book exam

#### Not Allowed
- Using any non-approved resource (people, web, etc.) for exams **(severe)**
- Allowing another person to write or complete any part of any exam **(severe)**
- Posting or providing answers to students who have not yet completed the exam
- Requesting help from other people or web services for open book exams
- Posting or providing exam questions and answers after exam has been completed

### Grading Practices   
Faculties, departments, and schools reserve the right to scale grades in order to maintain equity among sections and conformity to University, faculty, department, or school norms. Students should therefore note that an unofficial grade given by an instructor might be changed by the faculty, department, or school. Grades are not official until they appear on a student's academic record. http://www.calendar.ubc.ca/okanagan/index.cfm?tree=3,41,90,1014  If you have any questions about how academic integrity applies to this course, please consult with your professor.

### Disability Assistance
The Disability Resource Centre ensures educational equity for students with disabilities, injuries or illness. If you are disabled, have an injury or illness and require academic accommodations to meet the course objectives, e-mail us or visit our website for more information.
Web:   http://students.ok.ubc.ca/drc/welcome.html	E-mail DRC at:  drc.questions@ubc.ca


### Equity, Human Rights, Discrimination and Harassment
UBC Okanagan is a place where every student, staff and faculty member should be able to study and work in an environment that is free from human rights-based discrimination and harassment.  If you require assistance related to an issue of equity, discrimination or harassment, please contact the Equity Office, your administrative head of unit, and/or your unit’s equity representative.      UBC Okanagan Equity Advisor:   ph. 250-807-9291
Web:  https://equity.ok.ubc.ca/ 				E-mail:  equity.ubco@ubc.ca   


### Health & Wellness
At UBC Okanagan health services to students are provided by Health and Wellness.  Nurses, physicians and counsellors provide health care and counselling related to physical health, emotional/mental health and sexual/reproductive health concerns. As well, health promotion, education and research activities are provided to the campus community.  If you require assistance with your health, please contact Health and Wellness for more information or to book an appointment.  
Web: www.students.ok.ubc.ca/health-wellness 		Email: healthwellness.okanagan@ubc.ca  


### Sexual Violence Prevention and Response Office (SVPRO)
A safe and confidential place for UBC students, staff and faculty who have experienced sexual   violence regardless of when or where it took place. Just want to talk? We are here to listen and help you explore your options. We can help you find a safe place to stay, explain your reporting options (UBC or police), accompany you to the hospital, or support you with academic accommodations. You have the right to choose what happens next. We support your decision, whatever you decide.    Visit svpro.ok.ubc.ca or call us at 250-807-9640
 
### Independent Investigations Office (IIO)
If you or someone you know has experienced sexual assault or some other form of sexual misconduct by a UBC community member and you want the Independent Investigations Office (IIO) at UBC to investigate, please contact the IIO. Investigations are conducted in a trauma informed, confidential and respectful manner in accordance with the principles of procedural fairness. You can report your experience directly to the IIO by calling 604-827-2060.  
Web:  https://investigationsoffice.ubc.ca/  		E-mail:  director.of.investigations@ubc.ca

### The Hub
The Student Learning Hub (LIB 237) is your go-to resource for free math, science, writing, and language learning support. The Hub welcomes undergraduate students from all disciplines and year levels to access a range of supports that include tutoring in math, sciences, languages, and writing, as well as help with study skills and learning strategies.  Web: (https://students.ok.ubc.ca/student-learning-hub/)  Ph: 250-807-9185.

### SAFEWALK
Don't want to walk alone at night?  Not too sure how to get somewhere on campus?  Call Safewalk at 250-807-8076.
For more information:  https://security.ok.ubc.ca/safewalk/  or download the UBC SAFE – Okanagan app.


## Reference Material



