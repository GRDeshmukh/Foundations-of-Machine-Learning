# Machine Learning Foundations

This repo is home to the code that accompanies Jon Krohn's *Machine Learning Foundations* curriculum, which provides a comprehensive overview of all of the subjects — across mathematics, statistics, and computer science — that underlie contemporary machine learning approaches, including deep learning and other artificial intelligence techniques.

There are eight subjects in the curriculum, organized into four subject areas. See the "Machine Learning House" section below for detail on why these are the essential foundational subject areas: 

* **Linear Algebra**
   * 1: [Intro to Linear Algebra](https://github.com/jonkrohn/ML-foundations/blob/master/notebooks/1-intro-to-linear-algebra.ipynb)
   * 2: [Linear Algebra II: Matrix Operations](https://github.com/jonkrohn/ML-foundations/blob/master/notebooks/2-linear-algebra-ii.ipynb)
* **Calculus**
   * 3: [Calculus I: Limits & Derivatives](https://github.com/jonkrohn/ML-foundations/blob/master/notebooks/3-calculus-i.ipynb)
   * 4: [Calculus II: Partial Derivatives & Integrals](https://github.com/jonkrohn/ML-foundations/blob/master/notebooks/4-calculus-ii.ipynb)
* **Probability and Statistics**
   * 5: [Probability & Information Theory](https://github.com/jonkrohn/ML-foundations/blob/master/notebooks/5-probability.ipynb)
   * 6: [Intro to Statistics](https://github.com/jonkrohn/ML-foundations/blob/master/notebooks/6-statistics.ipynb)
* **Computer Science**
   * 7: [Algorithms & Data Structures](https://github.com/jonkrohn/ML-foundations/blob/master/notebooks/7-algos-and-data-structures.ipynb)
   * 8: [Optimization](https://github.com/jonkrohn/ML-foundations/blob/master/notebooks/8-optimization.ipynb)
   
Later subjects build upon content from earlier subjects, so the recommended approach is to progress through the eight subjects in the order provided. That said, you're welcome to pick and choose individual subjects based on your interest or existing familiarity with the material. In particular, each of the four subject areas are fairly independent so could be approached separately. 

### Where and When

The eight *ML Foundations* subjects were initially offered by [Jon Krohn](jonkrohn.com) as live online trainings in the [O'Reilly learning platform](oreilly.com) from May-Sep 2020. To suit your preferred mode of learning, the content is now available via several channels: 

* **YouTube**
    * All the Linear Algebra videos are live: [playlist here](https://www.youtube.com/playlist?list=PLRDl2inPrWQW1QSWhBU0ki-jq_uElkh2a) and [detailed blog post here](https://www.jonkrohn.com/posts/2021/5/9/linear-algebra-for-machine-learning-complete-math-course-on-youtube)
    * As of May 2021, Calculus videos are being published every Monday and Thursday: [playlist here](https://www.youtube.com/playlist?list=PLRDl2inPrWQVu2OvnTvtkRpJ-wz-URMJx)
* **O'Reilly**
    * [Linear Algebra videos](https://learning.oreilly.com/videos/linear-algebra-for/9780137398119/) published in Dec 2020 ([free sample](https://www.youtube.com/watch?v=uG_wjmuigGg))
    * [Calculus videos](https://learning.oreilly.com/videos/calculus-for-machine/9780137398171/) published in Jan 2021 ([free sample](https://youtu.be/ZDAX17OGMAM))
    * [Probability and Stats videos](https://learning.oreilly.com/videos/probability-and-statistics/9780137566273/) published in May 2021 ([free sample](https://youtu.be/uJcGj-k50iE))
    * [Computer Science videos](https://learning.oreilly.com/videos/data-structures-algorithms/9780137644889/) published in June 2021
    * Live training: The entire series [will be taught online](https://www.oreilly.com) by Jon Krohn from Jul-Dec 2021 (see [jonkrohn.com/talks](https://www.jonkrohn.com/talks) for individual lecture dates).
* **Udemy**: All the Linear Algebra content has been [live in a course](https://www.udemy.com/course/machine-learning-data-science-foundations-masterclass/) since Apr 2021; all of the Calculus content is being added over Spring 2021. At that point, the first four subjects could stand alone as a *Mathematical Foundations of ML* course, but we will nevertheless continue to add Subjects 5-8 as quickly as we can.
* **Open Data Science Conference**: The entire series was taught live online from Dec 2020 to Jun 2021. On-demand recordings of all these trainings are now available in the [Ai+ Platform](https://aiplus.odsc.com/pages/mlbootcamp).
* **Book**: Chapter drafts to begin appearing in 2021

*(Note that while YouTube contains 100% of the taught content, the paid options -- e.g., Udemy, O'Reilly, and ODSC -- contain comprehensive solution walk-throughs for exercises that are not available on YouTube. Some of the paid options also include exclusive, platform-specific features such as interactive testing, "cheat sheets" and the awarding of a certificate for successful course completion.)*

### Push Notifications

To stay informed of future live training sessions, new video releases, and book chapter releases, consider signing up for Jon Krohn's [email newsletter via his homepage](https://www.jonkrohn.com/).

### Notebooks

All code is provided within Jupyter notebooks [in this directory](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/). 

These notebooks are intended for use within the (free) [Colab cloud environment](https://colab.research.google.com) and that is the only environment currently actively supported. That said, if you're keen to run the notebooks locally, you're welcome to do so (for the Jupyter and Docker uninitiated, check out [the installation instructions here](https://github.com/jonkrohn/DLTFpT/tree/master/installation)). 


### The Machine Learning House

<p align="center">
  <img src="https://github.com/jonkrohn/ML-foundations/blob/master/img/ML-house.png" width="500" align="center">
</p>

To be an outstanding data scientist or ML engineer, it doesn't suffice to only know how to use ML algorithms via the abstract interfaces that the most popular libraries (e.g., scikit-learn, Keras) provide. To train innovative models or deploy them to run performantly in production, an in-depth appreciation of machine learning theory (pictured as the central, purple floor of the "Machine Learning House") may be helpful or essential. And, to cultivate such in-depth appreciation of ML, one must possess a working understanding of the foundational subjects.

When the foundations of the "Machine Learning House" are firm, it also makes it much easier to make the jump from general ML principles (purple floor) to specialized ML domains (the top floor, shown in gray) such as deep learning, natural language processing, machine vision, and reinforcement learning. This is because, the more specialized the application, the more likely its details for implementation are available only in academic papers or graduate-level textbooks, either of which typically assume an understanding of the foundational subjects.

The content in this series may be particularly relevant for you if: 

* **You use high-level software libraries** to train or deploy machine learning algorithms, and would now like to understand the fundamentals underlying the abstractions, enabling you to expand your capabilities
* You’re a **data scientist** who would like to reinforce your understanding of the subjects at the core of your professional discipline
* You’re a **software developer** who would like to develop a firm foundation for the deployment of machine learning algorithms into production systems
* You’re a **data analyst** or **A.I. enthusiast** who would like to become a data scientist or data/ML engineer, and so you’re keen to deeply understand the field you’re entering from the ground up (very wise of you!) 
* You're simply keen to understand the essentials of linear algebra, calculus, probability, stats, algorithms and/or data structures

The foundational subjects have largely been unchanged in recent decades and are likely to remain so for the coming decades, yet they're critical across all machine learning and data science approaches. Thus, the foundations provide a solid, career-long bedrock. 


### Pedagogical Approach

The purpose of this series it to provide you with a practical, functional understanding of the content covered. Context will be given for each topic, highlighting its relevance to machine learning. 

As with other materials created by Jon Krohn (such as the book *[Deep Learning Illustrated](https://www.deeplearningillustrated.com/)* and his 18-hour video series *[Deep Learning with TensorFlow, Keras, and PyTorch](https://github.com/jonkrohn/DLTFpT/))*, the content in the series is brought to life through the combination of:

* Vivid full-color illustrations 
* Paper-and-pencil comprehension exercises with fully-worked solutions
* Hundreds of straightforward examples of Python code within hands-on Jupyter notebooks (with a particular focus on the PyTorch and TensorFlow libraries)
* Resources for digging even deeper into topics that pique your curiosity


### Prerequisities

**Programming**: All code demos will be in Python so experience with it or another object-oriented programming language would be helpful for following along with the code examples.

**Mathematics**: Familiarity with secondary school-level mathematics will make the class easier to follow along with. If you are comfortable dealing with quantitative information -- such as understanding charts and rearranging simple equations -- then you should be well-prepared to follow along with all of the mathematics.


### Oboe

Finally, here's an illustration of Oboe, the *Machine Learning Foundations* mascot, created by the wonderful artist [Aglaé Bassens](https://www.aglaebassens.com): 

<p align="center">
  <img src="https://github.com/jonkrohn/ML-foundations/blob/master/img/Oboe.jpg" width="400" align="center">
</p>
