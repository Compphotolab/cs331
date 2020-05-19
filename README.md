<a name="top"></a>
# CS331: Introduction to Computational Photography @ Northwestern
Fall 2020  

|[**Top**](#top)|  [**Calendar**](#calendar)| [**Links**](#links)| [**Slides**](#slides)|  [**Readings**](#readings)| [**Credits**](#credits)

### Course Goals

To teach the fundamentals of modern camera architectures and give students hand-on experience acquiring, characterizing, and manipulating data captured using a modern camera platform. For example, students will learn how to estimate scene depth from a sequence of captured images.

### Course Description
This course is the first in a two-part series that explores the emerging new field of Computational Photography. Computational photography combines ideas in computer vision, computer graphics, and image processing to overcome limitations in image quality such as resolution, dynamic range, and defocus/motion blur. This course will first cover the fundamentals of image sensing and modern cameras.  We will then continue to explore more advanced topics in computer vision. We will then use this as a basis to explore recent topics in computational photography such as motion/defocus deblurring cameras, light field cameras, and computational illumination.

This course will consist of six homework assignments and no midterm or final exam. We will provide a Nvidia Tegra tablet for each student in the course. Students will write programs that run on the phone to capture photos. Enrollment is limited to 30 students.

### Prerequisites

EECS 211 and/or 230 or permission from instructor. Students should have experience with C/C++ and MATLAB programming. If you are interested, please contact the instructor to discuss!

### Time & Place 
CS331 lecture: All lectures will be pre-recorded and linked through canvas

### Instructors & Office Hours
[Oliver Cossairt](https://compphotolab.northwestern.edu/)
Office Hours: Thursday 3-5PM - signup for 10min slots at youcanbookme.com - see CANVAS for instructions 
Office: Rm 3511, Seeley Mudd
Office Phone: (847) 491-0895.
Mail: oliver.cossairt (@) northwestern.edu

#### Teaching assistants  & Office Hours

[Florian Schiffers](https://compphotolab.northwestern.edu/) - Office Hours:  Thursday @ 10AM-noon - signup for 10min slots at youcanbookme.com - see CANVAS for instructions
Mail: florian.schiffers (a) northwestern.edu


#### Peer Mentors & Office Hours (TBD)

| Group | Day | Time | Name | Contact |
|-------|-----|------|------|---------|
| 1     | Mon | 12pm - 2pm | Kevin | kevinmendozatudares2022 (at) u.northwestern.edu |
| 2     | Mon | 5pm - 7pm | Itay | itaygolan2021 (at) u.northwestern.edu |

### Policies 
* *Grading:* Homeworks 0 through 8, and the final exam are each worth 10 points. They sum to 100. You're graded on a basis of 100 points.  In other words, under normal grading policy ... 93-100 is an A, 90 - 92 is an A-, 87-89 is a B+, 83-86 is a B, 80-82 is a B-...and so on. DUE TO THE COVID-19 SITUATION THIS SPRING, THERE WILL BE NO LETTER GRADES ASSIGNED FOR THE COURSE. ALL UNDERGRADUATE GRADES WILL BE PASS/FAIL (P/N) - 60 POINTS OR GREATER WILL RESULT IN A PASSING GRADE. GRADUATE STUDENTS MAY REQUEST A LETTER GRADE AT THE END OF THE COURSE, BUT THE DEFAULT GRADE WILL BE PASS/FAIL. 

* *Extra Credit:* Campus Wire interaction is encouraged and a maximum amount of 10 points will be given depending on the amount of your interaction. Obvious gaming of the system will punished by removing extra points and removing 5 points from your total credits. There will be no special extra credit for individual students who request additional extra credit beyond the extra credit we already provide. 

* *When and Where to Submit Assignments:*  Free responses are due on [Canvas](http://www.it.northwestern.edu/education/login.html) 
by 11:59pm on the due date.  Code is due in your individual GitHub Classroom code repository, also at 11:59pm on the due date. 

* *Late Policy:*  If there is nothing on Canvas by 11:59pm on the due date, the free response grade is 0. If there is nothing in your github repository by 11:59pm on the due date, the coding grade is 0. The most recent code on github at 11:59pm on the due date is the code we will grade. The most recent submission in Canvas at that point, is the one we grade. A good approach is to continually check in and push to GitHub as you work. Also, put up a "safety" submission on Canvas with what you currently have, an hour prior to the deadline. 

* *Cheating & Academic Dishonesty:* Do your own work. This includes free response answers and code. Penalties include failing the class and can be more severe than that. If you have a question about whether something may be considered cheating, ask, prior to submitting your work. We will be checking for code duplication. Academic dishonesty will be dealt with as laid out in the student handbook.

* *Attendance* is not graded.

* *Announcements* and discussions will take place on [CampusWire](https://campuswire.com/p/G63AA7CEA). You can sign up for the page at that link using the sign-up code 3680.

<a name="calendar"></a>
### Lecture Calendar

This is a prediction of what will be covered in each week but the schedule is 
subject to change as the course progresses.

| Week of| Lecture of week | Topic             | 
|------|-----|---------------------------------|
| 04/06 | Mon | Introduction                   | 
|       | Wed | Image Formation                 |  
| 04/13 | Mon | Image Sensing | 
|       | Wed | Image Processing I             |
| 04/20 | Mon | Image Processing II           |
|       | Wed | Flash and Lighting       |
| 04/27 | Mon | No Class               |
|       | Wed | Radiometry        |
| 05/04 | Mon | K-Means clustering             |
|       | Wed | HDR Imaging        |
| 05/11 | Mon | Photometric Stereo         |
|       | Wed | Shape from Shading  |
| 05/18 | Mon | Structured Light  |
|       | Wed | Depth from Focus     |
| 05/25 | Mon | No Class        |
|       | Wed | SIFT    | 
| 06/01 | Mon | Stereo         | 
|       | Wed | Light Fields           |
| 06/08 | Mon | Thanksgiving (No Class)          |
|       | Wed | Light Transport                 |

### Homework Calendar

Homework is due and assigned on the dates below. It is a fairly tight schedule 
to ensure we cover many different topics. 

NOTE: The final is take-home! While there is a meeting time for the final, we won't administer anything that day. Just turn in the take-home final online via Canvas by the end of finals week.

| Date | Assigned | Due | Points |
|------|----------|-----|--------|
| 04/06 | HW 0: Setting up |  | 10 |
| 04/13 | HW 1: Decision trees | HW 0: Setting up | 10 |
| 04/15 | HW 2: KNN & Distance | HW 1: Decision trees | 10 |
| 04/22 | HW 3: Linear regression| HW 2: KNN & Distance | 10 |
| 04/29 | HW 4: Gradient descent| HW 3: Linear regression | 10 |
| 05/06 | HW 5: Clustering | HW 4: Gradient descent | 10 |
| 05/13 | HW 6: Reinforcement learning | HW 5: Clustering | 10 |
| 05/20 | HW 7: Deep Learning| HW 6: Reinforcement learning | 10 |
| 05/27 | HW 8: Eigenfaces| HW 7: Deep Learning | 10 |
| 06/03 | FINAL | HW 8: Eigenfaces | 10 |
| 06/10 | | FINAL | 10 |
| Total | | | 100 |

### AccessibleNU

|[**Top**](#top)|  [**Calendar**](#calendar)| [**Links**](#links)| [**Slides**](#slides)|  [**Readings**](#readings)|

# Materials provided by us

# Credits

Many of the course materials are modified from the excellent class notes of similar courses offered in other schools by [Shree Nayar](http://www1.cs.columbia.edu/~nayar/), [Marc Levoy](http://www.graphics.stanford.edu/~levoy/), [Jinwei Gu](http://www.cis.rit.edu/jwgu/), [Fredo Durand](http://people.csail.mit.edu/fredo/), and others. The instructor is extremely thankful to the researchers for making their notes available online. 
