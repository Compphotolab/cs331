<a name="top"></a>
# CS331: Introduction to Computational Photography @ Northwestern
Winter 2022  

|[**Top**](#top)|  [**Calendar**](#calendar)| [**Links**](#links)| [**Slides**](#slides)|  [**Readings**](#readings)| [**Credits**](#credits)

### Course Goals

To teach the fundamentals of modern camera architectures and give students hand-on experience acquiring, characterizing, and manipulating data captured using a modern camera platform. For example, students will learn how to estimate scene depth from a sequence of captured images.

### Course Description
This course is the first in a two-part series that explores the emerging new field of Computational Photography. Computational photography combines ideas in computer vision, computer graphics, and image processing to overcome limitations in image quality such as resolution, dynamic range, and defocus/motion blur. This course will first cover the fundamentals of image sensing and modern cameras.  We will then continue to explore more advanced topics in computer vision. We will then use this as a basis to explore recent topics in computational photography such as motion/defocus deblurring cameras, light field cameras, and computational illumination.

### Prerequisites

EECS 211 and/or 230 or permission from instructor. Students should have experience with Python programming. If you are interested, please contact the instructor to discuss!

### Time & Place 
Monday & Wednesday 12:30-1:50. The first two weeks will be online classes via zoom. The rest of the quarter will be in person.

### Instructors & Office Hours
Florian Willomitzer Office Hours: write an email to florian.willomitzer@northwestern.edu to book a 10min slot.

#### Teaching assistants  & Office Hours
Aniket Dashpute -  email : aniketdashpute2025@u.northwestern.edu 
Jiazhang Wang -  email : jiazhangwang2024@u.northwestern.edu 
Office hours are replaced with increased Campuswire activity on myside. For coding questions that involve your own code, please make a private thread that is only visibile to TA/Instructor.

### Policies 
* *Grading:* Homeworks 1 through 7 are each graded Pass/Fail. Each homework consists of a coding and a technical writeup. Your coding must be correct, and your writeup must be clearly written  in order to receive a passing grade. For each assignment that you fail, your grade gets lowered by one letter. So if you pass all seven assignments you get an A, if you fail one assignment you get a B, if you fail two you get a C, and so on. You can resubmit up to three homework assignments that you received a failing grade for. We plan to stick closely to these grading guidelines, but some exceptions may be made for partial credit (e.g. A-/B+, etc.).

* *When and Where to Submit Assignments:*  A writeup report for each assignment must be submitted on Canvas by 11:59pm on the due date. Your code must be pushed to your individual GitHub Classroom code repository, also at 11:59pm on the due date.

* *Late Policy:* If EITHER there is nothing on Canvas OR your code has not been pushed to by 11:59pm on the due date, you fail the assignment. The most recent code on github at 11:59pm on the due date is the code we will grade. The most recent submission in Canvas at that point, is the one we grade. A good approach is to continually check in and push to GitHub as you work. Also, put up a “safety” submission on Canvas with what you currently have, an hour prior to the deadline. You can resubmit up to three homework assignments that you received a failing grade for.

* *Cheating & Academic Dishonesty:* Do your own work. This includes free response answers and code. Penalties include failing the class and can be more severe than that. If you have a question about whether something may be considered cheating, ask, prior to submitting your work. We will be checking for code duplication. Academic dishonesty will be dealt with as laid out in the student handbook.

* *Attendance* is not graded.

* *Announcements* and discussions will take place on [CampusWire](https://campuswire.com/p/G45D7003E). You can sign up for the page at that link using the sign-up code 6624.

<a name="calendar"></a>
### Lecture Calendar

This is a prediction of what will be covered in each week but the schedule is 
subject to change as the course progresses

| Week of| Lecture of week | Topic             | 
|------|-----|---------------------------------|
| 01/03 | Mon | No lecture                     | 
| 01/05 | Wed | Introduction                   |  
| 01/10 | Mon | Image Formation                |  
| 01/12 | Wed | Spatial domain image processing|
| 01/17 | Mon | No lecture - MLK Day           |
| 01/19 | Wed | Fourier domain image processing|
| 01/24 | Mon | Image Sensing                  |
| 01/26 | Wed | Flash and Lighting             |
| 01/31 | Mon | Image Segmentation             |
| 02/02 | Wed | Radiometry                     |
| 02/07 | Mon | HDR Imaging                    |
| 02/09 | Wed | Photometric Stereo             |
| 02/14 | Mon | Depth from Focus               |
| 02/16 | Wed | Structured Light 3D Imaging    |
| 02/21 | Mon | SIFT                           |
| 02/23 | Wed | Camera Calibration             | 
| 02/28 | Mon | Light Fields                   | 
| 03/02 | Wed | Stereo                         |
| 03/07 | Mon | Optical Flow                   |
| 03/09 | Wed | Light Transport                |

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

### USEFUL LINKS

Similar Courses in Other Universities
- [Computational Photography (Gu, RIT)](http://www.cis.rit.edu/jwgu/teach/compphoto/compphoto_201301.htm)
- [Computational Photography SIGGRAPH Course (Raskar & Tumblin)](http://web.media.mit.edu/~raskar/photo/)
- [Computational Camera and Photography (Raskar, MIT)](http://cameraculture.media.mit.edu/Fall2010ComputationalCamera)
- [Digital and Computational Photography (Durand & Freeman, MIT)](http://groups.csail.mit.edu/graphics/classes/CompPhoto06/)
- [Computational Photography (Levoy & Wilburn, Stanford)](http://www.cis.rit.edu/people/faculty/jwgu/teach/compphoto/compphoto_201301.htm)
- [Computational Photography (Belhumeur, Columbia)](http://www.cs.columbia.edu/~belhumeur/courses/compPhoto/compPhoto4.html)
- [Computational Photography (Efros, CMU)](http://graphics.cs.cmu.edu/courses/15-463/2010_fall/463.html)
- [Computational Photography (Essa, Georgia Tech)](http://www.cc.gatech.edu/classes/AY2005/cs4803cp_summer/)
- [Computational Photography (Fergus, NYU)](http://cs.nyu.edu/~fergus/teaching/comp_photo/index.html)
- [Computer Vision (Seitz, U of Washington)](http://www.cs.washington.edu/education/courses/cse576/09sp/)
- [Computer Vision (Zhang, U of Wisconsin)](http://pages.cs.wisc.edu/~lizhang/courses/cs766-2010f/)
- [Computer Vision (Snavely, Cornell)](http://www.cs.cornell.edu/courses/cs6670/2011sp/)
- [Introduction to Visual Computing (Kutulakos, U of Toronto)](http://www.cs.toronto.edu/~kyros/courses/320/index.2011s.html)

### MORE LINKS

More Links

- [What is Computational Camera](http://www1.cs.columbia.edu/CAVE/projects/what_is/), [Shree Nayar](http://www1.cs.columbia.edu/CAVE/projects/what_is/), [Columbia](http://www1.cs.columbia.edu/CAVE/projects/what_is/)
- Columbia Projects, [Shree Nayar](http://www1.cs.columbia.edu/CAVE/projects/cc.php), [Peter Belhumeur](http://www.cs.columbia.edu/~belhumeur/)
- MIT Projects, [Fredo Durand](http://projects.csail.mit.edu/photo/), [William Freeman](http://projects.csail.mit.edu/photo/), [Edward Adelson](http://projects.csail.mit.edu/photo/), [Antonio Torralba](http://projects.csail.mit.edu/photo/), [Raskar Ramesh](http://cameraculture.media.mit.edu/projects)
- Stanford Projects, [Marc Levoy and collaborators](http://graphics.stanford.edu/projects/lightfield/)
- USC Projects, [Paul Debevec](http://ict.debevec.org/~debevec/) and collaborators
- CMU Projects, [Narasimhan](http://www.cs.cmu.edu/~ILIM/projects/), [Efros](http://www.cs.cmu.edu/~efros/)
- [Jack Tumblin's 'Questions' for the field](http://www.cs.northwestern.edu/~jet/research.html)

Conferences: [ICCP 2011](http://www.cs.cmu.edu/~ICCP2011/), ICCP 2010, ICCP 2009, SIGGRAPH, SIGGRAPH Asia, CVPR, ICCV, ECCV, ..

|[**Top**](#top)|  [**Calendar**](#calendar)| [**Links**](#links)| [**Slides**](#slides)|  [**Readings**](#readings)|

# Materials provided by us

# Credits

Many of the course materials are modified from the excellent class notes of similar courses offered in other schools by [Shree Nayar](http://www1.cs.columbia.edu/~nayar/), [Marc Levoy](http://www.graphics.stanford.edu/~levoy/), [Jinwei Gu](http://www.cis.rit.edu/jwgu/), [Fredo Durand](http://people.csail.mit.edu/fredo/), and others. The instructor is extremely thankful to the researchers for making their notes available online. 
