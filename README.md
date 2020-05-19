<a name="top"></a>
# CS349: Machine Learning @ Northwestern
Spring 2020  

|[**Top**](#top)|  [**Calendar**](#calendar)| [**Links**](#links)| [**Slides**](#slides)|  [**Readings**](#readings)| [**Credits**](#credits)

### Course Description
Machine learning is the study of algorithms that improve automatically through experience. This is an overview class that tries to cover the fundamentals: classification, regression, and model training and evaluation across a variety of approaches both old and new. This course takes you from decision trees to state-of-the-art deep neural networks.

The assignments are structured via Github Classroom submissions. In each assignment, you implement a classic machine learning algorithm (e.g. decision trees, k-means). The algorithm is then determined to be correct via a set of automated test cases. Correctly implementing a machine learning algorithm is only part of each assignment. In the second half of each assignment, students take each algorithm and perform a series of experiments on them, testing them on different datasets, visualizing and interpreting the output of the algorithm, while also considering the concepts that underly the algorithm. Through this process, students thoroughly understand how the algorithm works, when to use it, and how to set up experiments to test their machine learning hypotheses.

### Time & Place 
CS349 lecture: All lectures will be pre-recorded and linked through canvas

### Instructors & Office Hours
[Oliver Cossairt](https://compphotolab.northwestern.edu/) - Office Hours: Thursday 3-5PM - signup for 10min slots at youcanbookme.com - see CANVAS for instructions 

#### Teaching assistants  & Office Hours

[Florian Schiffers](https://compphotolab.northwestern.edu/) - Office Hours:  Thursday @ 10AM-noon - signup for 10min slots at youcanbookme.com - see CANVAS for instructions
Mail: florian.schiffers (a) northwestern.edu


#### Peer Mentors & Office Hours (TBD)

| Group | Day | Time | Name | Contact |
|-------|-----|------|------|---------|
| 1     | Mon | 12pm - 2pm | Kevin | kevinmendozatudares2022 (at) u.northwestern.edu |
| 2     | Mon | 5pm - 7pm | Itay | itaygolan2021 (at) u.northwestern.edu |
| 3     | Tue | 11m - 1pm | Biraj | bparikh (at) u.northwestern.edu |
| 4     | Tue | 2pm - 4pm | David | DavidZane2021 (at) u.northwestern.edu |
| 5     | Wed | 10am - 12 pm| Bella | bellazhan2021 (at) u.northwestern.edu |
| 6     | Wed | 5pm - 7 pm | Kyle | kyleqian2021 (at) u.northwestern.edu |
| 7     | Thu | 1pm - 3pm | Joshua | joshuazhao2021 (at) u.northwestern.edu |
| 8     | Thu | 3pm - 5pm | Aaron | aaronkim2022 (at) u.northwestern.edu |
| 9     | Fri | 9am - 11am| Andreas | andreas (at) u.northwestern.edu |
| 10    | Fri | 1pm - 3pm | Amro | amroashmeik2020 (at) u.northwestern.edu |
| 11    | Tue | 10pm - 12am| Daniel | danielbang2021 (at) u.northwestern.edu |

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
| 04/06 | Mon | Intro to ML                    | 
|       | Wed | Decision trees                 |  
| 04/13 | Mon | Distances and nearest neighbor | 
|       | Wed | Linear regression              |
| 04/20 | Mon | Linear discriminants           |
|       | Wed | PCA and manifold larning       |
| 04/27 | Mon | Gradient descent               |
|       | Wed | Support vector machines        |
| 05/04 | Mon | K-Means clustering             |
|       | Wed | Gaussian Mixture Models        |
| 05/11 | Mon | Reinforcement learning         |
|       | Wed | Introduction to Deep Learning  |
| 05/18 | Mon | Convolutional Neural Networks  |
|       | Wed | Recurrent Neural Networks.     |
| 05/25 | Mon | Memorial Day (NO CLASS)        |
|       | Wed | Generative Adversarial Nets    | 
| 06/01 | Mon | Graph Neural Networks          | 
|       | Wed | Gaussian Processes             |
| 06/08 | Mon | Final Week (no Class)          |
|       | Wed | Final Due Date                 |

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

If you require accommodations to sit exams or take notes, please refer to AccessibleNU and feel free to talk to me (Ollie) about your needs.

<a name="links"></a>
### Helpful Programming Links 
[Anaconda: The most popular python distro for machine learning](https://www.continuum.io/downloads)

[Scikit Learn: the most popular machine learning python package](http://scikit-learn.org/stable/)

[Jupyter Notebook](http://jupyter.org/)

[Pytorch, the framework we'll use for our deep net labs](https://pytorch.org)

[Tensorflow: the other popular python DNN package](https://www.tensorflow.org/)

[Keras: A nice python API for Tensorflow](https://keras.io/)

<a name="slides"></a>
<a name="readings"></a>

### Lecture Slides & Course Reading 
#### Decision Trees
[lecture: first lecture ](lectures/cs349_fall2019_intro_to_ml.pdf)

[lecture: old first lecture ](lectures/eecs349_intro_to_ml.pdf)

[lecture: decision trees](lectures/eecs349_decision_trees.pdf)

[working through an ID3 example](lectures/recitation_DT.pdf)

[Definitely read this: Chapter 3 of Machine Learning](https://www.cs.princeton.edu/courses/archive/spring07/cos424/papers/mitchell-dectrees.pdf)

[Optional fun visualiztion: A visual introduction to Decision Trees](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)

#### Measuring Distance and Linear Regression
[lecture: distance measures](lectures/eecs349_measuring_distance.pdf) *updated April 29 2019*

[lecture: linear regression](lectures/eecs349_linear_regression.pdf) 

[The Wikipedia article on distance](https://en.wikipedia.org/wiki/Distance)

[Sections 2.1 and 2.2 of An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/)

[Sections 3.1, 3.2 of An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/)


#### Linear Discriminants and K nearest neighbor classification
[lecture: nearest neighbor classifiers/regressors](lectures/eecs349_nearest_neighbor.pdf)

[lecture: linear discriminants](lectures/eecs349_linear_discriminants.pdf) *updated 2019*

[Sections 4.2, 4.4 of An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/)


#### Evaluating Hypotheses and Collaborative Filtering

[lecture: collaborative filtering](lectures/eecs349_collaborative_filtering.pdf) *updated April 23 2019*

[lecture: evaluating hypotheses](lectures/eecs349_evaluating_hypotheses.pdf)  

[Machine Learning, Chapter 5: Evaluating Hypotheses](readings/chapter5-ml.pdf)

[Recommendor Systems, Chapter 2: Collaborative Filtering](readings/Recommender_Systems_An_Introduction_Chpt2.pdf)


#### Support Vector Machines 
[lecture: support vector machines](lectures/cs349_support_vector_machines.pdf) *updated May 7, 2019*

[A Tutorial on Support Vector Machines for Pattern Recognition](http://www.cs.northwestern.edu/~pardo/courses/eecs349/readings/support_vector_machines4.pdf) *Start reading in section 3*

[Chapter 9 of An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/)

[LibSVM](https://www.csie.ntu.edu.tw/~cjlin/papers/libsvm.pdf) describes the SVM implementation used in scikit learn. Only read this if you're seriously into the details of how they're practically implemented.

#### Reinforcement Learning

[lecture: Reinforcement Learning](lectures/eecs349_reinforcement_learning.pdf)

[Chapters 2, 3 and 6 of Reinforcement Learning: An Introduction](http://incompleteideas.net/book/RLbook2018.pdf)

#### Boosting and Active Learning 

[lecture: Boosting](lectures/eecs349_boosting.pdf)

[lecture: Active Learning](lectures/eecs349_active_learning.pdf)

[A brief introduction to Boosting](readings/intro_to_boosting.pdf)

[Improving Generaliation with Active Learning](readings/improving_generalization_with_active_learning_ML94.pdf)

#### Unsupervised clustering: K-means and Gaussian Mixture Models


[lecture: Clustering](lectures/cs349_clustering_intro.pdf) *updated May, 2019*

[lecture: Mixture models](lectures/mixture_models.pdf) *updated May, 2019*

[lecture: Gaussian Mixture Models](lectures/eecs349_gaussian_mixture_models.pdf)

[Expectation maximization - Bishop](http://www.rmki.kfki.hu/~banmi/elte/bishop_em.pdf)

[EM Demystified: An Expectation-Maximization Tutorial](https://www2.ee.washington.edu/techsite/papers/documents/UWEETR-2010-0002.pdf)

#### Gradient Descent and Perceptrons 
[lecture: Gradient Descent](lectures/cs349_gradient_descent.pdf) *updated May 25, 2019*

[Chapter 1 of Parallel Distributed Processing](http://cognet.mit.edu/book/parallel-distributed-processing)

#### Deep Learning, etc.
[lecture: Neural Networks](lectures/cs349_deep_nets.pdf)

[lecture: Recurrent Neural Networks](lectures/cs349_fall2019_rnn.pdf)

[lecture: Generative Adversarial Networks](lectures/cs349_fall2019_gan.pdf)

[Bhiksha Raj's slides on GANs](https://www.cs.cmu.edu/~bhiksha/courses/deeplearning/Fall.2015/slides/lec13.GAN.pdf)

[NeurIPS2016 Gan Tutorial](https://www.youtube.com/watch?v=9JpdAg6uMXs)


[Chapter 4 of Machine Learning ](http://www.cs.northwestern.edu/~pardo/courses/eecs349/readings/chapter4-ml.pdf)

[Chapter 6 of Deep Learning](http://www.deeplearningbook.org/)

[Blog: A hacker's guide to neural nets](http://karpathy.github.io/neuralnets/)

[Blog: On SoftMax and Cross Entropy](https://deepnotes.io/softmax-crossentropy)

|[**Top**](#top)|  [**Calendar**](#calendar)| [**Links**](#links)| [**Slides**](#slides)|  [**Readings**](#readings)|

# Materials provided by us

We will curate a list of material written by us that will be very helpful for this course. Essentially it is a list of important functions in numpy (and some other packages) that you will need to implement the homework.

Please have a look those material here: https://github.com/NUCS349/materials

# Credits

People who contributed to the design of this course and the homeworks:

- Bryan Pardo
- Prem Seetharaman
- Bongjun Kim
- Max Morrison
- Ethan Manilow
- Fatemeh Pishdadian
- Lukas Justen
- Oliver Coissart
- Florian Schiffers

and more to come!
