# CSCI 1230 Course Missive

Welcome to CSCI 1230, the longest-running computer graphics course in the known universe! This document will get you started with the course.

## Course Staff & Essential Info
* Professor: Daniel Ritchie (dritchi1)
* Head TAs: Zack Cheng (zcheng12), Logan Dooley (ldooley)
* UTAs: Yiwen Chen (ychen485), Adrian Chang (achang57), Jianxin Gu (jgu26), Nick Huang (yhuan170), Helen Huang (hhuang65), Mehek Jethani (mjethani), Marc Mapeke (mmapeke), Derick Toth (dtoth1), Sean Zhan (xzhan2), Anna Zhao (azhao26)
* Lectures: Tues & Thurs 10:30am -- 11:50am, Metcalf Auditorium. Lectures will be recorded and promptly available online.
* Course website: https://csci1230.graphics
* TA mailing list: cs1230tas@cs.brown.edu
* Ed discussion board: https://edstem.org/us/courses/12828

## Public Health

Unless otherwise announced, masks are required in lecture, labs, TA hours, and the professor's office hours.

Feeling sick? Please do not come to lecture or use public computer labs. Ask a friend to fill you in on details from class, and review the lecture slides + recording online. We would like to keep everyone in good health. 

## Registration

For those confused by the different choices for this course on C@B, we've put together this handy guide:

**CSCI 1230 S01:** The main section of the course. You should sign up for this, unless any of the below circumstances apply to you.

**CSCI 1230 S02:** This section is for students who really want to take the course but have an unavoidable time conflict with another course; since this section is marked as "ONLINE" on C@B, it will not trigger a schedule conflict with any other course. If you need to enroll in this section, you are still welcome (and encouraged!) to come to lecture, conflicts permitting. At minimum, you should watch the lecture recordings soon after they are posted.

**CSCI 2230:** This course is for graduate students who wish to earn 2000-level credit. Graduate students enrolled in this course attend the same lectures and complete the same assignments as students in CSCI 1230; however, they will be expected to implement some extra features for each assignment. Undergraduates cannot enroll in this course.

**CSCI 1234:** This half-credit course (to be taken in addition to CSCI 1230 S01 or CSCI 1230 S02) is for undergraduates who wish to challenge themselves to complete the same extra requirements as grad students taking CSCI 2230. CSCI 1234 can be taken for a letter grade or S/NC, regardless of the grading option chosen for CSCI 1230. Students who wish to use CSCI 1230 as their capstone are required to take this extra half-credit course for a letter grade.

## Prerequisites

The official **course** prerequisite for CSCI 1230 is to have completed a CS intro sequence: CSCI 0150 + 0200, 0170 + 0200, 0111 + 0112 + 0200, or 0190.

CSCI 0330, because it uses C, can be helpful but is not strictly required. CSCI 0320, for its software design, is additionally helpful but not required. Some familiarity with C++ will be helpful, but help sessions, gear ups, and extra support will be offered to students who don't have any prior C++ experience. Most students take the class without any prior C++ experience. Some knowledge of basic linear algebra (i.e., vector and matrix multiplication, dot and cross products) is also helpful, but none is required or assumed; we will cover all the basics that are needed during class.

There are some **software and infrastructure prerequisites** as well:
* You need to be able to access Github, esp. Github classroom.
* You need to be able to compile and run the course projects on your own computer, or have a *very* fast internet connection to the department machines. Most laptop computers post-2015 should have no problem with compiling and running projects. More specifically, we use OpenGL 4.0 for many of our projects, which is supported on Intel, AMD, and NVIDIA graphics hardware that most common computers have newer than 2012.
* You need a lot of free space on your machine to dedicate to  CSCI 1230. Qt Creator (the IDE we use) requires ~6GB, and the C++ developer tools for your OS may require considerably more than that (e.g. on macOS, the Xcode developer tools use about 30GB of disk space).

## Learning Goals

Students who complete this course will:
* Be familiar with different ways 3D shapes can be represented in graphics applications.
* Understand mathematical models for calculating the amount of light reflected from an object in a scene.
* Be able to implement the ray tracing rendering algorithm, which produces pseudo-realistic images with reflections, refractions, and other effects.
* Be comfortable writing real-time graphics programs using OpenGL and the GLSL shading language.
* Know how to create and control virtual cameras which can convert 3D scenes to 2D images using linear algebra.
* Know how to process images by applying filters and transformations while minimizing artifacts such as aliasing (a.k.a. “jaggies”).
* Understand the fundamentals of human color perception, the abilities of displays to reproduce colors, and the impact of color choice on viewer experience.

The full list of CSCI 1230 topics can be found on the course website at https://csci1230.graphics/lectures.

## Materials

The primary text for this course is the most recent edition of *Computer Graphics: Principles and Practice, by John Hughes, Andy van Dam, Morgan McGuire, David Sklar, Jim Foley, Steve Feiner, and Kurt Akeley*.
**The book is not required**, as the lecture slides for CS1230 are nearly comprehensive. These slides do not replace the textbook, but they are the best source of information that is directly relevant to the assignments.

The course website has a wealth of information that will be useful to you throughout the semester:
* TA hours schedule and contact information: https://csci1230.graphics/
* Instructions and stencil code for each project: https://csci1230.graphics/projects
* Instructions and stencil code for each lab: https://csci1230.graphics/labs
* Links to PDF and PowerPoint versions of each class and accompanying videos and/or demos: https://csci1230.graphics/lectures
* Documentation for the support code, help session slides, and links to external sources for help
with OpenGL: https://csci1230.graphics/docs

## Required Coursework

### Projects
There are six programming projects, divided into three units (raster graphics, raytracing, realtime graphics), as well as an open-ended final project. The final project can be completed in groups; all remaining projects must be done individually.

### Algos
Each programming assignment will be accompanied by a written algorithm (“algo”) assignment to get you started thinking about how to approach the assignment mathematically and algorithmically. Algo answers should be clear and succinct. If we ask you to describe a section of the project’s algorithm, you should probably go with a description, or pseudo code, rather than actual C++.

Algos make up 10% of your final grade. They are graded on effort/completion, with a small amount of extra credit awarded for correct answers. Algorithm worksheets are returned the same day as the deadline so you can begin coding with confidence right away. Because we release the solutions immediately after the deadline, ***late algo submissions are not accepted*** (so be sure to turn them in on time!)

### Labs
In addition to the projects, a series of labs will provide hands-on experience with various graphics programming topics and tools. Each lab is designed such that the code you write will be helpful for one of the programming projects (or for the final project).

## Work Expectations

Over 13 weeks, students will spend 3 hours per week in class (39 hours total), and approximately 2 hours per week in labs (20 hours total). Homeworks, which consists of 1-2 week projects and the accompanying algorithm assignments, usually take 15-20 hours per week, though they can also require somewhat more or less time depending on how much extra credit a student chooses to implement. In any case, students will spend a minimum of 8.5 hours per week and 120 hours total on homework by the end of the semester.

## Grading

Your CSCI 1230 grade consists of 1 tiny written homework, 6 rigorously graded projects, 12 labs that are given completion grades (one of the three final labs is optional), and a final project that is graded according to your presentation to the class during finals period. There are no exams or quizzes, and final grades are not curved; if the work meets specification, it deserves an A, and that is the most common grade. HW0 (which is about the collaboration policy) is critical: you must do it correctly or fail the course.
* **HW0** ***(must be done correctly to pass course)***
* **Projects**:
  * **Raster/Brush**: 8%
  * **Raster/Filter**: 12%
  * **Ray/1**: 13%
  * **Ray/2**: 11%
  * **Realtime/1**: 10%
  * **Realtime/2**: 11%
* **"Algo" assignments for projects**: 10%
* **Final Project**: 15%
* **11 out of 12 Labs**: 10%

Daniel doesn't use a curve and would be delighted to hand out As to the entire class. Indeed, the majority of students traditionally have worked hard and gotten As. In borderline cases (e.g. 89-91), Daniel will take attendance and class participation into account, as well as your perceived effort and dedication.

### Extra Credit

There is ample room for bells, whistles, and other credit-garnering efforts on the part of ambitious programmers. You are invited to get creative, as long as it does not make you late. Rewarding bells and whistles with extra credit is left to the discretion of the course staff, so we strongly encourage you to discuss your creative plans with a TA before you forge ahead to make sure that they are considered appropriate for credit. If you are not enrolled in CSCI 2230 or CSCI 1234, completing any of the enhancements required for those courses will count as extra credit for you.

### Regrade Requests

Sometimes you may feel that you have been graded unfairly. If you ever feel this way, please request a regrade on Gradescope. Once your request is evaluated, you will be provided with an explanation and possibly points back. If you are not satisfied with the regrade decision please talk to the Head TA. If there is still a problem, Daniel is the final word in grading and will be happy to hear what you have to say.

If you decide to challenge a grade, you must do so ***within one week of its receipt***. In the past, students have tried to get points back on all of their assignments in the last week of classes; this places an unfair burden on TAs at the end of the semester and is unfair to other students. If you discover that you handed in the wrong work after you get your grade back, or if you fix your program after getting its grade back, we are unable to take those fixes into account for grading purposes.

## Late Policy
A late algo or lab checkoff will receive ***no credit***. Each day a project is turned in late will be penalized 10% of the possible total points. (If you are 25 hours late in handing in, that’s a 20%, even though you hand in during the first hour of that ‘extra day’).

Every student has five late passes that can each be used to waive a day that a project was turned in late (and the opportunity to earn an extra late pass by filling out a mid-semester course feedback survey). These late passes will automatically be applied optimally (to maximize your grade) at the end of the semester. You may ***not*** use ***any*** late days at all on the Final project.

Late days are expected to cover clustering of due dates and job interviews. For sickness and other issues of wellbeing, please obtain a note from health services or a Dean and communicate with Daniel; the TAs will not be involved in handling these.

As projects build upon each other, it is important to start early and quickly recover from late handins.

## Academic Integrity & Collaboration Policy

Collaborating with your fellow students is an important part of a rich and rewarding learning experience. However, Brown's academic code also requires that we evaluate you based on ***your own work***: “Academic achievement is evaluated on the basis of work that a student produces independently. A student who obtains credit for work, words, or ideas that are not the products of his or her own effort is dishonest and in violation of Brown’s Academic Code.” With the above in mind, we've designed a collaboration policy that we think strikes a reasonable balance between appropriate collaboration and rigorous independent work.

**The tl;dr is that you should generally feel free to discuss concepts and work through ideas with your classmates, but you must produce your own code and written solutions to assignments.**

More specifically, follow these guidelines for different parts of the course:

**Labs**: You are encouraged to work together with others on labs and to help each other debug them.

**Algos**: You are welcome to discuss the algo assignments with others. If you do discuss an algo with other students, you should retain no notes (paper, typed, whiteboard photos, etc.) from the discussion. After the discussion is over and all records of it are gone, you should then write up the solution on your own. Please also ***write down the names and/or CS logins of each student you collaborated with*** next to each question. Your solution should contain only your own work. If you're not sure what this means, consider answering a question like this about a solution in which you wrote some code: "If I changed line 3 of this code to have `2 * i` instead of `i`, what would the output look like? Would the code still compile? Would there be new error-cases to check for?" If you can't answer that kind of question, then the code isn't really *yours*. The same goes for formulas you derive.

**Programming Projects**: You are welcome to discuss the requirements, concepts behind, and general design strategies for the programming projects. However, all code you write must be your own. You should not look at, use, or otherwise refer to code written by another student (with or without their consent), nor code you found online (in a Github repository, Stack Overflow post, solutions from a previous offering of the course, etc.) On the opposite side of the same coin, you should not share your own code with others (including by having it posted in a publicly-visible online repository or in your CS home directory with insufficient permissions). If you do discuss project strategy with another student, ***please include their name and/or CS login in your submission README***. 

**The Final Project**: The final project can be completed in groups of 2-4, and we encourage you to do a group final project! Because the final project can be big and open-ended, there may be cases where it makes sense for you to make use of some third-party software/library. If you think this is necessary and appropriate for your project, please check with your mentor TA. If they approve it, then be sure to cite the software/library in your final project submission.

**Edstem**: You're welcome to ask for help on projects from your peers on Edstem, provided you have tried your best to solve the problem on your own. All public Edstem posts asking for help resolving an issue must include a description of the steps you have already tried to solve the problem. Feel free to post images/videos of your program's output, but under no circumstances should you show any of your code. On a related note: if you are responding to a question on Edstem, you should not include any code (even pseudocode) in your response. Diagrams and mathematical expressions are fine, though.


## Diversity and Inclusion

Our intent is that this course provide a welcoming environment for all students who satisfy the prerequisites. Our TAs have undergone training in diversity and inclusion, and all members of the CS community, including faculty and staff, are expected to treat one another in a professional manner. If you feel you have not been treated in a professional manner by any of the course staff, please contact either the instructor, [Ugur Cetintemel](mailto:ugur@cs.brown.edu) (Dept. Chair), [Tom Doeppner](mailto:twd@cs.brown.edu) (Vice Chair) or [Laura Dobler](mailto:laura_dobler@brown.edu) (diversity & inclusion staff member). We will take all complaints about unprofessional behavior seriously. Prof. Krishnamurthi has [good notes](http://cs.brown.edu/courses/cs019/2016/professionalism.html) on this area. To access student support services and resources, and to learn more about diversity and inclusion in CS, please visit [this webpage](http://cs.brown.edu/about/diversity/resources/).

Brown welcomes students from all around the country and the world, and their unique perspectives enrich our learning community. To empower students whose first language is not English, an array of support is available on campus, including language and culture workshops and individual appointments. For more information, contact the English Language Learning Specialists at [ellwriting@brown.edu](ellwriting@brown.edu).

## Accommodations

Brown University is committed to full inclusion of all students. Please inform Daniel if you have a disability or other condition that might require accommodations or modification of any of these course procedures. You may email Daniel, come to office hours, or speak with him after class, and your confidentiality is respected. We will do whatever we can to support accommodations recommended by SEAS. For more information contact Student and Employee Accessibility Services ([SEAS](https://www.brown.edu/campus-life/support/accessibility-services/)) at 401-863-9588 or SEAS@brown.edu. Students in need of short-term academic advice or support can contact one of the deans in the Dean of the College office.

## Mental Health

Being a student can be very stressful. If you feel you are under too much pressure or there are psychological issues that are keeping you from performing well at Brown, we encourage you to contact Brown’s Counseling and Psychological Services [CAPS](https://www.brown.edu/campus-life/support/counseling-and-psychological-services/). They provide confidential counseling and can provide notes supporting extensions on assignments for health reasons.

## Incomplete Policy

We expect everyone to complete the course on time. However, we certainly understand that there may be factors beyond your control, such as health problems and family crises, that prevent you from finishing the course on time. If you feel you cannot complete the course on time, please discuss with the instructor the possibility of being given a grade of Incomplete for the course and setting a schedule for completing the course in the upcoming year.

*Thanks to Tom Doeppner and Laura Dobler for the text on accommodation, mental health, and incomplete policy.*

## Getting Help

CS 1230 is a challenging course, both conceptually and practically: there are new ideas to wrap your head around, and the programming work expected of you has a non-trivial learning curve (especially if you've never seen C++ before). Because of this, it is completely normal to struggle on some of the assignments! We're here to help :) This section has more information about how to ask for course-related help when you need it. 

Before we get started, keep in mind: your TAs are all students, too. They have their own courses and other obligations; being a TA is just one of their many time commitments. TA time is a finite resource, so please be respectful of it. Before asking for TA help, make a good faith effort to solve a problem on your own (or seek help from a friend/classmate, within the boundaries of our collaboration policy). And always remember: getting help from a TA is a privilege, not a right to which you are entitled. "I wasn't seen by a TA" is not a valid reason for handing in work late. At the end of the day, you and you alone are responsible for your performance in the course.

### Where to go to get your questions answered

Your first stop when you have a question should be the course website. You are responsible for checking the web site frequently, as we will be updating it with important information as the semester progresses. Most updates to the website will be accompanied by an announcement to Edstem.

If you can't find the answer to your question on the course website, you should next check Edstem.
On Edstem, always first check if someone has asked a similar to question to the one you have--with luck, it might already have an answer.
If you've confirmed that no one else has asked (a variant of) your question, then you can go ahead and make a new post.
There are set times throughout the week during which a TA will be monitoring Edstem and answering questions; these can be found on the course website. Outside of these times, you should not expect a prompt response from a TA. However, your fellow students may be monitoring Edstem as well, and they can be a great resource! We encourage you to post answers to questions on Edstem; your record of helping out your fellow students here is something we factor in when determining final grades for borderline cases.

For more involved course-related questions, you can come to TA hours; the schedule for these is also on the course website.
You may not ask TAs course-related questions when they are not on hours. All TAs are prohibited by department and university policy from answering course-related questions when not on official TA hours. TAs may answer general administrative questions when not on TA hours.
Thank you for helping us comply with departmental and university regulations (which reflect applicable federal and state labor laws). If you have any questions about this policy, please contact mta@cs.brown.edu.

### TA Hours

The schedule of TA hours is available on the course website. We will make every effort to maintain these hours without exception. On rare occasion, we might need to cancel or reschedule a TA hour session. When TA hours are rescheduled or exceptions are made, these will be announced on Edstem.

TA hours are often very busy, and many times there will be a waiting list. You may sign up on the waiting list when TA hours are in progress, but not before TA hours start. The TA will clear the waiting list at the start of TA hours each day. If the waiting list is very long and the end of TA hours is approaching, the TA may close the waiting list so that all people on the waiting list can be helped before TA hours are over.

### Sending mail to the TAs

If there is a problem with an assignment that affects the entire class (such as a bug in the support code), you may e-mail the TAs at cs1230tas@lists.brown.edu. TAs will respond to course-related e-mail during their office hours. For administrative questions or if there is a problem with a TA, you can e-mail the head TA at cs1230headtas@lists.brown.edu.

Questions related to coding the projects or concepts explained in class should be asked at TA hours or TA help sessions, or on Edstem. We are not able to respond to these types of questions via e-mail.

## Feedback for us?

CSCI 1230 is a continually evolving course. As such, we are bound to have our own 'bugs' hiding in the corners. Please read everything we hand out very carefully. If there is something which you do not understand, or which is not stated very clearly, please let us know so we can fix it right away. This applies to the material discussed in lecture as well. Give us constructive criticism on all aspects of the course. The more feedback there is, the better we can make this course for you as the semester progresses, and the better we can make it for the next twenty-five years of Brown computer graphics students!
