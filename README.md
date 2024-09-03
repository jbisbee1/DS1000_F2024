# DS 1000-01: How Data Shape Our World (Fall 2024)
Course Material for DS1000: How Data Shape our World

## Table of Contents

1. [Overview](#overview)
2. [Required Applications](#required-applications)
3. [Evaluation & Responsibilities](#evaluation--responsibilities)
4. [Course Policies](#course-policies)
5. [Office Hours](#office-hours)
6. [Syllabus](#syllabus)
7. [Helpful Resources](#helpful-resources)
8. [Acknowledgements](#acknowledgements)

## Overview
The target audience is someone who is interested in Data Science, but who has no prior experience. The class is designed to be application-forward -- demonstrating what you can do with the tools of data science in the hopes of motivating and encouraging students to go deeper and further. As an introductory class with no prerequisites, the statistical and programming fundamentals behind what we do is only briefly mentioned; the goal is to provide a sense of what can be done with data science rather than to provide a comprehensive foundation on a smaller set of topics. The contents of this repository represent a work-in-progress and revisions and edits are likely frequent.

The main text for the course is "R For Data Science" which can accessed free online [here](https://r4ds.had.co.nz/introduction.html). 

Students are expected to have a free ChatGPT account which can be accessed [here](https://chat.openai.com/)

*[Back to ToC](#table-of-contents)*

## Required Applications

### Brightspace
This is the course management software used at Vanderbilt to support course learning. I will use this to post readings, lectures, assignments, and news for the course. I will post announcements and changes to the home page of the site; though I will always announce changes in class, please keep an eye out. *If a change to the syllabus or requirements is posted in the announcements on this site, you are responsible for those changes.*

Don’t forget to download the related app, which is called Pulse, to your phone and set it to alert you if there are new content or announcements for the course.

### Campuswire
I have set up a Campuswire workspace for our use this semester to help us better communicate with each other and the TAs. You will need to create an account and join our workspace by following [this link](https://campuswire.com/p/GB59CA361). **The secret PIN can be found on the first announcement on Brightspace.** You are encouraged to adopt these [Slack etiquette tips](https://slack.com/blog/collaboration/etiquette-tips-in-slack). 

Here is the list of channels you should see upon joining the Campuswire workspace:

- **Class feed**: A space to post questions and respond to other posts.

- **#announcements**: A space for all course announcements.
	
- **#general**: A space for you to share and discuss stories you've seen in the news or on social media that are relevant to our class.

- **Calendar**: A calendar containing all lectures, due dates, office hours, and labs.

- **Files**: A space for course materials (**NOT USED. VISIT BRIGHTSPACE INSTEAD.**)

- **Grades**: A space for grades (**NOT USED. VISIT BRIGHTSPACE INSTEAD.**)
	
### GitHub
I have created a [`GitHub`](https://github.com/jbisbee1/DS1000_F2024) repository to prepare and share all course-related content. This very syllabus is available as the repository's README and all links below are connected to the appropriate folders, sub-folders, and files in this repository. 

You are expected to adopt the following workflow for this class:

1. Prior to each lecture, download the appropriate `.Rmd` file, open it in `RStudio`, and read through it. **This is your primary homework assignment!** As you work through it, try to tweak some of the code and answer the toy examples where provided. Each time you make a change, click the `knit` button in `RStudio` to see if everything still loads.
	
2. During each lecture, create a new `.Rmd` file to take notes in. As with the homework, you should be tweaking and adjusting things on your own, extending your learning beyond what is covered in lecture.
	
3. After each lecture, tweak the notes `.Rmd` file further to test out new ideas that you come up with which were not covered in class. Each lecture's slides will be made available as `PDF` for you use to help you review. Thinking creatively about how to modify and extend what we do together might mean you already guess some of the exam questions!

*[Back to ToC](#table-of-contents)*

## Evaluation & Responsibilities

Given the nature of the material, as well as the size of the class, participation is not part of your grade. Instead, you will be assigned weekly problem sets beginning with Topic 3 which will test your ability to apply what you've learned in class, and to think creatively about your own data science ideas. These problem sets are assigned on the Monday of each week and are due by **11:59PM Nashville time the following Friday**. You are welcome to collaborate on these problem sets, and are encouraged to ask questions on the **Class feed** on `Campuswire`.

There are also two exams. The first is a mid-term exam that is scheduled for October 8th (Tuesday before fall break) and will take place in class. The second exam is a cumulative final that is scheduled for December 10th.

The final grade is calculated as a weighted average of these components with the following weights:

- **Problem sets:** 9 in total, only 8 of which are worth 5 points each for a total of 40 points. This effectively means you can miss a problem set without it hurting your final grade.
- **Exams:** Midterm and final. The midterm is worth 20 points and is in-class, and the final worth 25 points and is a take-home.
- **Quizzes:** There are 19 quizzes over the course of the semester which can only be taken if you attend class. Each consist of several questions plus an attendance statement. 0.5 points comes from accurately answering all five questions, and 0.5 points comes from signing the attendance statement. Each quiz is worth 1 point of your final grade, and combined comprise the final 15 points, meaning that 4 are not counted toward your final grade.
- **Extra Credit:** There is one extra credit point on each problem set, and five extra credit points on the midterm and final. Thus the maximum total points you can receive in this class is 128, meaning that if you ace every problem set, the midterm, and every quiz, you will have 98 points before the final exam. Achieving a perfect score requires a lot of effort, but would theoretically allow you to skip the final exam if you so chose.

See the table below for a breakdown of the percentages, points, and extra credit. 

![rubric](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/figs/rubric.png?raw=true)
	
Letter grades are determined as per the standard Vanderbilt grading system, reproduced below:

- A: 94+
- A-: 90-93
- B+: 87-89
- B: 84-86
- B-: 80-83
- C+: 77-79
- C: 74-76
- C-: 70-73
- D+: 67-69
- D: 64-66
- D-: 60-63
- F: <60

*[Back to ToC](#table-of-contents)*

## Course Policies

### Late Assignments

Every problem set is assigned on a Monday, and due on Brightspace by **11:59PM Nashville time on the following Friday**. Problem sets should be submitted via Brightspace. The problem sets are designed to require no more than two hours in total to complete. Late submissions will be **penalized 1 point off for each day late**. After three days, problem sets will no longer be accepted and will be scored 0. (But also remember that your lowest scoring problem set will not be counted toward your final grade, effectively giving you one "freebie".) Answer keys for the preceding week's problem set are posted on Thursdays after lecture.

### Cell Phones, Laptops, Tablets, etc.

You are expected to bring your laptop to class in order to work through the `.Rmd` file during the lecture. These `.Rmd` files will be posted to the GitHub repository at least 24 hours prior to the lecture. Students are encouraged to download these files and work through them prior to class.

You are asked to silence your cell phone / tablet / smart watch before class begins.

### Academic Honor Code

Students are assumed to have read and agreed with the Vanderbilt University Academic Honesty policy, found at URL: https://www.vanderbilt.edu/student_handbook/the-honor-system/

Collaboration is the heart of data science, but your work on your assignments should be your own. Please be careful not to plagiarize. The Undergraduate Honor Council has a very helpful guide to understanding plagiarism. **In particular, while students are invited to work on problem sets together, collaboration is prohibited on the midterm and final exams.**

Academic misconduct includes, but is not limited to, cheating, fabrication, plagiarism, altering graded examinations for additional credit, having another person take an examination for you, falsification of results, or facilitating academic dishonesty or as further specified in the university policy found at the website above. These and other forms of cheating are all potentially grounds for penalties including failure of the assignment or the course, as well as program- or university-level disciplinary action.

ChatGPT and related Large Language Models (LLMs) are essential tools in the data scientist's toolkit, and acceptable resources for completing the assignments and learning concepts at a deeper level. However, graded assignments cannot be generated purely by these tools. All assignments must include a log of the ChatGPT prompts and resulting output used to complete the assignment.

### Accommodations for Learning or Access Disabilities

This class respects and welcomes students of all backgrounds, identities, and abilities. If there are circumstances that make our learning environment and activities difficult, if you have medical information that you need to share with me, or if you need specific arrangements in case the building needs to be evacuated, please let me know. I am committed to creating an effective learning environment for all students, but I can only do so if you discuss your needs with me as early as possible. I promise to maintain the confidentiality of these discussions. If appropriate, also contact the Vanderbilt Student Access office to get more information about specific accommodations; please visit https://www.vanderbilt.edu/student-access/ as soon as possible to become registered and ensure that accommodations are implemented in a timely fashion. Requests for academic accommodations are to be made during the first three weeks of the semester, except for unusual circumstances.

### COVID-19 Policies
As per Vanderbilt's [F22 Covid Plan](https://news.vanderbilt.edu/2022/08/11/everything-you-need-to-know-about-covid-19-health-and-safety-for-the-start-of-the-2022-23-academic-year/), we are conducting class in as normal an environment as we’ve had since before the start of the COVID-19 pandemic. In general, this means:
* We will return fully to in-person instruction.
* Restrictions have been lifted on meetings and gathering sizes. 
* Mask mandates are no longer in place.
* Asymptomatic testing has been suspended.
* Isolation guidelines only apply to those who have tested positive for COVID-19.

As such, DS1000 will be meeting in-person. Lectures will not be hybrid or remote. For students affected by COVID-19, this means that you are responsible for obtaining any course material you missed. As you'll see below, I make all materials available on the course GitHub repository. In addition, I will be recording all lectures and posting these the evening following the lecture. **NB: this does not mean that students are permitted to skip the lectures.**

I will be holding my office hours in-person in The Commons Center Room #348. The TAs are free to determine how best to hold their office hours, and their choices will be communicated to the students as soon as they are decided.

### If You Need Help

There are many things that you might be dealing with that can hinder your ability to succeed in this course, your college career, and your life. You might be struggling with illness, socioeconomic issues, or personal issues that make it hard to concentrate, to work, or to attend class. If any of these or other things begin to hinder your ability to do your best, you can reach out to the office of Student Care Coordination for programs, training, accommodations, and assistance (find more information or make an appointment here: https://www.vanderbilt.edu/carecoordination/). The Student Care Coordination can help guide you to whatever assistance you might need, whether it be short term or long term. *If you specifically need help or accommodation in this course due to your difficulties, please come meet with me so we can find a solution that allows you to succeed while being fair to others.*

### Mandatory Reporting

Title IX makes it clear that violence and harassment based on sex and gender are Civil Rights offenses subject to the same kinds of accountability and the same kinds of support applied to offenses against other protected categories such as race, national origin, etc. If you or someone you know has been harassed or assaulted, you can call the Project Safe 24-hour crisis/support hotline at 615-322-7233 and you can find a list of resources at Project Safe. You may also contact the University’s Title IX Coordinator (615-322-4705) and you can find the appropriate contacts for resources and confidence here: https://www.vanderbilt.edu/title-ix/

As a faculty member, one of my responsibilities is to help create a safe learning environment on our campus, no matter their identity or circumstances. I also have a mandatory reporting responsibility. It is my goal that you feel able to share information related to your life experiences in classroom discussions, in your written work, and in our one-on-one meetings. I will seek to keep information you share private to the greatest extent possible. However, I must note that I am a representative of an institution that we want to make safer for all people, therefore I am a mandatory reporter. University faculty, many staff members, and some student leaders are required to report incidents of sexual assault, sexual harassment, dating violence, domestic violence, stalking, and child abuse, as well as any suspected discrimination (about age, race, color, creed, religion, ancestry, national or ethnic origin, sex/gender, sexual orientation, disability, genetic information, military status, familial status or other protected categories under local, state or federal law) to the University’s Title IX Coordinator (615-322-4705), as required by University policy and state and federal law. If you disclose an experience of interpersonal violence and/or child abuse to me or to classmates with mandatory reporting, whether in class discussion, through a course assignment, or in private communication with me, your disclosure will be kept as private as possible but may not be able to be kept confidential.

### Diversity Statement

Data science is, at its core, about thinking creatively to answer challenging questions. Creative thinking requires exposure to different perspectives, which are themselves borne of diverse experiences. I value diversity in all its forms including age, ability or disability, ethnicity, national origin, race, religion, sex, gender, sexual orientation, and family and marital status. I expect that all students participating in this class will respect differences and strive to understand how other peoples' perspectives, behaviors, and worldviews may be different from their own.

### Religious Holidays
The observance of religious holidays (activities observed by a religious group of which a student is a member) and cultural practices are an important reflection of diversity. As your instructor, I am committed to providing equivalent educational opportunities to students of all belief systems. At the beginning of the semester, you should review the course requirements to identify foreseeable conflicts with assignments, exams, or other required attendance. If at all possible, please contact me within the first two weeks of the first class meeting to allow time for us to discuss and make fair and reasonable adjustments to the schedule and/or tasks.

*[Back to ToC](#table-of-contents)*

## Office Hours
* Prof. Bisbee: T & Th from 11AM-12PM in Commons #348
* TA OH: please see Campuswire calendar

All these can also be found on the [Campuswire calendar](https://campuswire.com/c/calendar), along with the Zoom links for those hosting their office hours remotely.

*[Back to ToC](#table-of-contents)*

## Syllabus

| Date | Topic | Learning Goal | Materials | HW | Pset 
| ---: | :--- | :--- | --- | --- | --- 
08/22 | Introduction | Scientific method, camps of analysis | [Lecture 1](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_1_slides.html#1)<br/>[Notes 1](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_1_notes.Rmd)<br/>[Recording](https://brightspace.vanderbilt.edu/d2l/le/content/509408/viewContent/3428604/View) | [HW 1](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_1.Rmd)<br/>[PDF](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_1.pdf) | [PS 0](https://github.com/jbisbee1/DS1000_F2024/blob/main/Psets/ds1000_pset_0.Rmd)
08/27 | Intro to R 1 | Objects, functions, and code | [Lecture 2](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_2_slides.html#1)<br/>[Notes 2](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_2_notes.Rmd)<br/>[Recording](https://brightspace.vanderbilt.edu/d2l/le/content/509408/viewContent/3438044/View) | [HW 2](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_2.Rmd)<br/>[PDF](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_2.pdf) | [PS 1](https://github.com/jbisbee1/DS1000_F2024/blob/main/Psets/ds1000_pset_1.Rmd)<br/>[AK 1](https://github.com/jbisbee1/DS1000_F2024/blob/main/Psets/ds1000_pset_1_AK.pdf)
08/29 | Intro to R 2 | Visualization in R | [Lecture 3](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_3_slides.html#1)<br/>[Notes 3](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_3_notes.Rmd)<br/>[No Recording!]() | [HW 3](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_3.Rmd)<br/>[PDF](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_3.pdf) | 
09/03 | Intro to R 3 | More visualization | [Lecture 4](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_4_slides.html#1)<br/>[Notes 4](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_4_notes.Rmd)<br/>[Recording](https://brightspace.vanderbilt.edu/d2l/le/content/509408/viewContent/3447372/View) | [HW 4](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_4.Rmd)<br/>[PDF](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_4.pdf) | [PS 2](https://github.com/jbisbee1/DS1000_F2024/blob/main/Psets/ds1000_pset_2.Rmd)<br/>[AK 2](https://github.com/jbisbee1/DS1000_F2024/blob/main/Psets/ds1000_pset_2_AK.pdf)
09/05 | NO CLASS |  |  |  | 
09/10 | Data Wrangling | Replicability and tabular data | [Lecture 5](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_5_slides.html#1)<br/>[Notes 5](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_5_notes.Rmd)<br/>[Recording]() | [HW 5](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_5.Rmd)<br/>[PDF](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_5.pdf) | [PS 3](https://github.com/jbisbee1/DS1000_F2024/blob/main/Psets/ds1000_pset_3.Rmd)<br/>[AK 3](https://github.com/jbisbee1/DS1000_F2024/blob/main/Psets/ds1000_pset_3_AK.pdf)
09/12 | Univariate Analysis | Summaries of a single variable | [Lecture 6](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_6_slides.html#1)<br/>[Notes 6](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_6_notes.Rmd)<br/>[Recording]() | [HW 6](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_6.Rmd)<br/>[PDF](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_6.pdf) | 
09/17 | Multivariate 1 | Summaries of multiple variables | [Lecture 7](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_7_slides.html#1)<br/>[Notes 7](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_7_notes.Rmd)<br/>[Recording]() | [HW 7](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_7.Rmd)<br/>[PDF](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_7.pdf) | [PS 4](https://github.com/jbisbee1/DS1000_F2024/blob/main/Psets/ds1000_pset_4.Rmd)<br/>[AK 4](https://github.com/jbisbee1/DS1000_F2024/blob/main/Psets/ds1000_pset_4_AK.pdf)
09/19 | Multivariate 2 | Visualizations of multiple variables | [Lecture 8](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_8_slides.html#1)<br/>[Notes 8](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_8_notes.Rmd)<br/>[Recording]() | [HW 8](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_8.Rmd)<br/>[PDF](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_8.pdf) | 
09/24 | Multivariate 3 | Visualizations of multiple variables | [Lecture 9](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_9_slides.html#1)<br/>[Notes 9](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_9_notes.Rmd)<br/>[Recording]() | [HW 9](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_9.Rmd)<br/>[PDF](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_9.pdf) | [PS 5](https://github.com/jbisbee1/DS1000_F2024/blob/main/Psets/ds1000_pset_5.Rmd)<br/>[AK 5](https://github.com/jbisbee1/DS1000_F2024/blob/main/Psets/ds1000_pset_5_AK.pdf)
09/26 | Review Session | Uni/Multivariate | [Lecture R1](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_R1_slides.html#1)<br/>[Notes R1](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_R1_notes.Rmd)<br/>[Recording]() |  | 
10/01 | Uncertainty 1 | Uncertainty and bootstrapping | [Lecture 10](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_10_slides.html#1)<br/>[Notes 10](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_10_notes.Rmd)<br/>[Recording]() | [HW 10](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_10.Rmd)<br/>[PDF](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_10.pdf) | [PS 6](https://github.com/jbisbee1/DS1000_F2024/blob/main/Psets/ds1000_pset_6.Rmd)<br/>[AK 6](https://github.com/jbisbee1/DS1000_F2024/blob/main/Psets/ds1000_pset_6_AK.pdf)
10/03 | Uncertainty 2 | Confidence statements | [Lecture 11](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_11_slides.html#1)<br/>[Notes 11](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_11_notes.Rmd)<br/>[Recording]() | [HW 11](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_11.Rmd)<br/>[PDF](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_11.pdf) | 
10/08 | Midterm Exam |  |  |  | 
10/10 | BREAK |  |  |  | 
10/15 | Regression 1 | Interpreting output and evaluating model | [Lecture 12](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_12_slides.html#1)<br/>[Notes 12](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_12_notes.Rmd)<br/>[Recording]() | [HW 12](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_12.Rmd)<br/>[PDF](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_12.pdf) | [PS 7](https://github.com/jbisbee1/DS1000_F2024/blob/main/Psets/ds1000_pset_7.Rmd)<br/>[AK 7](https://github.com/jbisbee1/DS1000_F2024/blob/main/Psets/ds1000_pset_7_AK.pdf)
10/17 | Regression 2 | Interpreting output and evaluating model | [Lecture 13](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_13_slides.html#1)<br/>[Notes 13](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_13_notes.Rmd)<br/>[Recording]() | [HW 13](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_13.Rmd)<br/>[PDF](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_13.pdf) | 
10/22 | Regression 3 | Multiple regression, categorical Xs | [Lecture 14](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_14_slides.html#1)<br/>[Notes 14](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_14_notes.Rmd)<br/>[Recording]() | [HW 14](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_14.Rmd)<br/>[PDF](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_14.pdf) | 
10/24 | Review Session | Regression | [Lecture R2](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_R2_slides.html#1)<br/>[Notes R2](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_R2_notes.Rmd)<br/>[Recording]() |  | 
10/29 | Classification 1 | The concept of a logistic regression | [Lecture 15](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_15_slides.html#1)<br/>[Notes 15](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_15_notes.Rmd)<br/>[Recording]() | [HW 15](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_15.Rmd)<br/>[PDF](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_15.pdf) | [PS 8](https://github.com/jbisbee1/DS1000_F2024/blob/main/Psets/ds1000_pset_8.Rmd)<br/>[AK 8](https://github.com/jbisbee1/DS1000_F2024/blob/main/Psets/ds1000_pset_8_AK.pdf)
10/31 | Classification 2 | Interpreting output and evaluating model | [Lecture 16](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_16_slides.html#1)<br/>[Notes 16](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_16_notes.Rmd)<br/>[Recording]() | [HW 16](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_16.Rmd)<br/>[PDF](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_16.pdf) | 
11/05 | Classification 3 | Interpreting output and evaluating model | [Lecture 17](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_17_slides.html#1)<br/>[Notes 17](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_17_notes.Rmd)<br/>[Recording]() | [HW 17](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_17.Rmd)<br/>[PDF](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_17.pdf) | 
11/07 | NO CLASS |  |  |  | 
11/12 | Clustering | k-means clustering | [Lecture 18](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_18_slides.html#1)<br/>[Notes 18](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_18_notes.Rmd)<br/>[Recording]() | [HW 18](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_18.Rmd)<br/>[PDF](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_18.pdf) | [PS 9](https://github.com/jbisbee1/DS1000_F2024/blob/main/Psets/ds1000_pset_9.Rmd)<br/>[AK 9](https://github.com/jbisbee1/DS1000_F2024/blob/main/Psets/ds1000_pset_9_AK.pdf)
11/14 | NLP 1 | k-means clustering on text | [Lecture 19](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_19_slides.html#1)<br/>[Notes 19](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_19_notes.Rmd)<br/>[Recording]() | [HW 19](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_19.Rmd)<br/>[PDF](https://github.com/jbisbee1/DS1000_F2024/blob/main/Homeworks/ds1000_hw_19.pdf) | 
11/19 | NLP 2 | Sentiment analysis | [Lecture 20](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_20_slides.html#1)<br/>[Notes 20](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_20_notes.Rmd)<br/>[Recording]() |  | 
11/21 | Review Session | Clustering | [Lecture R3](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_R3_slides.html#1)<br/>[Notes R3](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_R3_notes.Rmd)<br/>[Recording]() |  | 
11/26 | BREAK |  |  |  | 
11/28 | BREAK |  |  |  | 
12/03 | Ethics | The risks of rapid technological change | [Lecture 21](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_21_slides.html#1)<br/>[Notes 21](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_21_notes.Rmd)<br/>[Recording]() |  | 
12/05 | Review Session | Cumulative | [Lecture R4](https://www.jamesbisbee.com/DS1000_F2024/Lectures/ds1000_lecture_R4_slides.html#1)<br/>[Notes R4](https://github.com/jbisbee1/DS1000_F2024/blob/main/Lectures/ds1000_lecture_R4_notes.Rmd)<br/>[Recording]() |  | 
12/10 | Final Exam |  |  |  | 


## Helpful Resources

[Rstudio Cheat Sheet: Data Wrangling](https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf)

[Rstudio Cheat Sheet: ggplot2 ](https://github.com/rstudio/cheatsheets/raw/master/data-visualization.pdf)

[R-graphics Cookbook](http://www.cookbook-r.com/Graphs/)

[... And the full list of Rstudio cheat sheets](https://www.rstudio.com/resources/cheatsheets/)

[Tidymodels Resources](https://www.tidymodels.org/learn/)

*[Back to ToC](#table-of-contents)*

## Acknowledgements
The contents of this course and of my teaching pedagogy are influenced and inspired by:
* Emily Hencken Ritter, Vanderbilt University
* Andrew Princep, MarketWatch & Oxford University
* Josh Clinton, Vanderbilt University
* William Doyle, Vanderbilt University
* Matthew Salganik, Princeton University

This course is modeled on the course of the same name, taught by Professors Josh Clinton and William Doyle in the spring of 2022 at Vanderbilt University. The lectures on data science & ethics are inspired by content prepared for the Summer Institutes for Computational Social Sciences ([SICSS](https://sicss.io/about)), and by presentations on machine learning and ethics prepared by Andrew Princep ([@AJPrincep](https://twitter.com/AJPrincep)). The syllabus is heavily inspired by [Emily Hencken Ritter](https://www.emilyhenckenritter.com/)'s syllabi for PSCI 3270, Politics of Human Rights.

*[Back to ToC](#table-of-contents)*