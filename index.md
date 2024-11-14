---
name: BMEG3105-Fall-2024
title: ""
title-heading: false
layout: default
---

## BMEG3105: Data analytics for personalized genomics and precision medicine — Fall 2024

[<a href="https://forms.gle/u21ZMgaaEJ3oPfuy8">Pre-course survey</a>, <a href="http://piazza.com/cuhk.edu.hk/fall2024/bmeg3105">Piazza</a>, 
<a href="https://docs.google.com/spreadsheets/d/1A4240_iSqeesl9G5NzYAuIWpHZXZgS0sH6w-_rWt4TM/edit?usp=sharing">Scribing preference</a>,
<a href="#logistics">Logistics</a>, <a href="#schedule_materials">Course schedule and materials</a>, <a href="#assignments">Assignments</a>, <a href="">Presentation schedule</a>]

### <a>Course description</a>
With social-economic development, people are increasingly caring about health. 
Consequently, in the field of genomics and healthcare, especially personalized genomics and precision medicine, we have accumulated a tremendous amount of data, which are waiting to be analyzed. 
This course is designed to equip students with the ability to analyze such data, which would benefit both the students' personal development and society. 
In the course, we will cover high-throughput experimental methods, standard data processing pipelines, sequence alignment and mapping, 
foundational concepts of data analytics, data exploration and visualization, clustering and classification, dimension reduction, and their applications in personalized genomics and precision medicine. 
For personalized genomics, we will also cover the integration of heterogeneous sequencing and non-sequencing data, single-cell data analysis, multi-omics analysis methods, and cancer genomics.
For precision medicine, we will cover protein-RNA interactions, biological graph analysis, and a gentle introduction to biomedical imaging and electronic health records.

#### Teaching team
Lecturer:
<ul>
<li>Yu LI (<span style="color: #0099e6">liyu@cse.cuhk.edu.hk</span>), SHB-106. Office hour: 3pm-5pm, Friday</li>
</ul>
TA:
<ul>
<li>Qinze YU (<span style="color: #0099e6">qzyu22@cse.cuhk.edu.hk</span>), SHB-116. Office hour: 2pm-4pm, Monday </li>
<li>Yimin Fan (<span style="color: #0099e6">fanyimin@link.cuhk.edu.hk</span>), SHB-904. Office hour: 2pm-4pm, Tuesday</li>
<li>Ziqian Lin (<span style="color: #0099e6">linziqian@link.cuhk.edu.hk</span>), SHB-904. Office hour: 3pm-5pm, Wednesday</li>
</ul>

#### Time and location
Wednesday: <b>9:30am-11:15am</b>, SC L4 <br>
Friday: <b>9:30am-10:15am</b>, MMW 703 <br>
Friday: <b>10:30am-11:15am</b>, MMW 703 (Tutorial) <br>

#### Format
In-person. Slides will be available the day before the lecture.

### <a id="logistics">Logistics</a>

#### Communications
<b>Blackboard</b> is the main software to manage the course, and grading will be through Blackboard. 
We will use <b>Piazza</b> (<a href="http://piazza.com/cuhk.edu.hk/fall2024/bmeg3105">BMEG3105</a>) for discussion. 
You can ask questions and discuss on Piazza, even anonymously. 
For personal matters, please use the private post to the instructor and the TA. 
You are also very welcomed to send emails to the teaching team.

#### Grading
<ul>
<li><b>Homework (20%)</b>: Three graded homework (A1, A2, A3; 5%, 5%, 5%) and one non-graded programming assignment (PA1; 5%, to ensure you can learn something from it).</li>
<li><b>Scribing (10%)</b>: Graded scribing. Summarize one of the lectures. Submit it within one week after the course. Each student should do at least one lecture. You can sign for at most two, for additional 1%.</li>
<li><b>In-class quiz (10%)</b>: Two in-class quizzes. The questions will be simple, mainly for checking the participation. The exact date is in the schedule below.</li>
<li><b>Midterm exam (20%)</b>: A graded midterm exam with one bonus question (extra 2%). </li>
<li><b>Project (20%)</b>: A graded individual project with a pre-defined or self-proposed topic. The project has four components: a midterm report (5%), a final report (7%), presentation (3%), and the implementation (5%). </li>
<li><b>Final exam (20%)</b>: A graded final exam.</li>
</ul>

<b>Bonus (up to 6%)</b>: 
<ul>
<li>One bonus question in the Midterm exam.</li>
<li>One additional scribing: 1%.</li>
<li>Pre-course survey and post-lecture surveys: 0.5% for each, and the maximum is 3%. I do encourage you to complete all of them so that to let me know your feedback and adjust the course accordingly. Send your names to the TAs after completion. </li>
</ul>

#### Open-book quiz and exam policy
All exams and quizzes are open-book. You are allowed to take any <b>paper-based materials</b>. However, no phone or computer is allowed. Other communication tools are also not allowed. Discussion is not allowed.

#### AI tools use policy
You can use AI tools including ChatGPT in the project to polish your report.
However, you are required to submit both your own version and the one polished using AI tools.
You are required to make it clear how you used AI tools and which part in the report.
We will grade on the one you would like us to grade, but if you do not hand in your own version, we would not consider the submission complete.

#### Programming
Python (the TA will prepare a recitation class to introduce it, mainly for the non-grading homework and your project) or any other languages that you are familiar with. 
For python, we suggest you to use <a href="https://colab.research.google.com/notebooks/intro.ipynb">Colab</a>. <br>

The programming assessments include a non-graded programming assignment (5%) and the implementation in the project (5%). 
The bonus is sufficient to cover all the programming credit in the project, if you really do not want to try hand-on experiments at all. 
We do encourage you try.

#### Scribing
Please sign up the <a href="https://docs.google.com/spreadsheets/d/1A4240_iSqeesl9G5NzYAuIWpHZXZgS0sH6w-_rWt4TM/edit?usp=sharing">scribing preference</a>. 
We should have at least one student for each lecture. We may adjust the assignment if necessary. 
Notice that your note and scribing will be posted online, for others reference. 
You can choose to remove your name or not. Deadline for signing the scribing: **<span style="color:red;">11:59 pm on 15th Sep</span>**. 
After that, the Google sheet will be closed. 
For students assigned to the first two lectures, you have additional one week to submit the scribing. 

#### Projects
We will have individual projects.
You can propose your project to us and seek our help, or we will predefine some projects for you to choose from. 
Some potential project topics:
<ul>
<li>From reads to gene expression matrix processing pipeline</li>
<li>Gene expression matrix processing pipeline</li>
<li>Single-cell RNA-seq processing pipeline </li>
<li>Bio-image classification</li>
<li>Cancer gene identification</li>
<li>Gene enrichment analysis</li>
</ul>
Both a midterm report (1 page) and a final report should be submitted.

#### Late days
Each student will have <b>6 late days</b> to turn in the assignments, which can be used on A1, A2, A3, PA1, and the project midterm report. 
They cannot be used on the project final report and the scribing note. 
A maximum of 2 late days can be used for each assignment. Grades will be deducted by 25% for each additional late day. 

#### Post-lecture survey 
Deadline for each survey: <span style="color: red; font-weight: bold">11:59pm on the day before the next lecture</span>. 
We do this because we could have time to answer the questions you mentioned in the survey. 
Please enter a "1" in the Google sheet: <a href="https://docs.google.com/spreadsheets/d/1xYWAb7NcAQWl1i3lEX4McRZ_bvnWel3fPE409UXp2Xw/edit?usp=sharing">Survey results</a>, once you have finished one survey. 
Usually, we will trust the 1s you fill in the Google sheet. 
But we will check the things in detail if the number of survey forms we received and the number of 1s on the Google sheet is not consistent.


### <a id="schedule_materials">Course schedule and materials</a>



| Lecture | Date         | Location | Topic                                           | Slides                                                                                                                                            | Notes                                                                                                                                                                                                       | Reading                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Important dates (All due at <span style="color:red;">11:59 pm</span>)        |
|---------|--------------|----------|-------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| 1       | Sep 4 (Wed)  | SC L4    | Introduction                                    | <a href="https://www.dropbox.com/scl/fi/wh956iy0uyscgwwcxreix/lec1-Intro.pdf?rlkey=fwlpkqj62a9o6dquctk51h3mz&dl=0">Lec-1</a>                 |  [note1](./notes/BMEG3105_Lec01_1.pdf), [note2](./notes/BMEG3105_Lec01_2.pdf), [note3](./notes/BMEG3105_Lec01_3.pdf), [note4](./notes/BMEG3105_Lec01_4.pdf), [note5](./notes/BMEG3105_Lec01_5.pdf), [note6](./notes/BMEG3105_Lec01_6.pdf),                                                                                                                                                                                                            |  <a href="https://www.dropbox.com/scl/fi/l3grw93itme99wrdbezh1/BMEG3105_Course-Outline_1st-Term_2024-25.doc?rlkey=fr556upzki91vxfzjkqr786e2&dl=0">Course outline</a>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |                                                                              | 
| 2       | Sep 6 (Fri)  | MMW703   | Data & Python         |  <a href="https://www.dropbox.com/scl/fi/o5nx2fb4l5lk9x37zeva9/lec2-data-and-python.pdf?rlkey=uqf03y42lh28y1nj9tswk754t&dl=0">Lec-2</a>           |                                                                                                                                                                                                             |  [sample code](https://colab.research.google.com/drive/1cdbEwWRqw2QUtITqvBj7u5m8NRgnY89Y?usp=sharing)   | PA0 posted                                                                   |
| 3       | Sep 11 (Wed) | SC L4    | Data & Python & Sequence                                 | <a href="https://www.dropbox.com/scl/fi/o5nx2fb4l5lk9x37zeva9/lec2-data-and-python.pdf?rlkey=uqf03y42lh28y1nj9tswk754t&dl=0">Lec-2,3</a>     | [note1](./notes/BMEG3105_Lec03_1.pdf), [note2](./notes/BMEG3105_Lec03_2.pdf), [note3](./notes/BMEG3105_Lec03_3.pdf), [note4](./notes/BMEG3105_Lec03_4.pdf)  |   [sample code](https://colab.research.google.com/drive/1cdbEwWRqw2QUtITqvBj7u5m8NRgnY89Y?usp=sharing)                                                                |                                                                              |
| 4       | Sep 13 (Fri) | MMW703   | DP                                              |<a href="https://www.dropbox.com/scl/fi/na8uqxwbypo7n3knn9unr/lec4-DP.pdf?rlkey=osdpwgox6cph8gsb0delkszad&dl=0">Lec-4</a>     |     [note1](./notes/BMEG3105_Lec04_1.pdf), [note2](./notes/BMEG3105_Lec04_2.pdf), [note3](./notes/BMEG3105_Lec04_3.pdf)                |<a href="https://colab.research.google.com/drive/1hDJKoP55gAPTpPALcrgv3muwgYGHu6Zs?usp=sharing">Python Tut-1</a>, <a href="https://www.dropbox.com/s/tdxlt6yaigvj6jy/chapter2%263.pdf?dl=0">Chapter 2&3</a>                                                                                                                                                                                           | A1 posted                                                                    |
| 5       | Sep 20 (Fri) | MMW703   | Assembly & Mapping                              | <a href="https://www.dropbox.com/scl/fi/8m8rulxfy9ducwwa9ttq9/lec5-Assembly-and-mapping.pdf?rlkey=r63bxnddw0xreeiy90tusc50a&dl=0">Lec-5</a>       |   [note1](./notes/BMEG3105_Lec05_1.pdf), [note2](./notes/BMEG3105_Lec05_2.pdf), [note3](./notes/BMEG3105_Lec05_3.pdf), [note4](./notes/BMEG3105_Lec05_4.pdf), [note5](./notes/BMEG3105_Lec05_5.pdf)  |  <a href="https://colab.research.google.com/drive/1QmT6a7XumAYbd_9NhVfLuu9VvpR7-mtP?usp=sharing">Sample code</a>, <a href="https://www.dropbox.com/s/j6gu44xszr9e8jk/A%20survey%20of%20best%20practices%20for%20RNA-seq%20data%20analysis.pdf?dl=0">RNA-seq analysis</a>, [intro to python tutorial](./reading/Tutorial_1_intro%20to%20python.pptx), [anaconda starter guide](./reading/Anaconda-Starter-Guide.pdf), [conda cheatsheet](./reading/conda-cheatsheet.pdf)       | <span style="color:red;">PA0 due</span>                                      |
| 6       | Sep 25 (Wed) | SC L4    | Data exploration                                | <a href="https://www.dropbox.com/scl/fi/f9vhrxwtuv7fnjidslsmj/lec6-Exploration-and-cleaning.pdf?rlkey=ueg82hxyzs7klyqo463tjahik&dl=0">Lec-6</a>   |     [note1](./notes/BMEG3105_Lec06_1.pdf), [note2](./notes/BMEG3105_Lec06_2.pdf), [note3](./notes/BMEG3105_Lec06_3.pdf)                |  <a href="https://github.com/chenomg/CS_BOOKS/blob/master/Python%20for%20Data%20Analysis%2C%202nd%20Edition.pdf">Python for DA</a>, <a href="https://colab.research.google.com/drive/1z0_IEP-tOZgt7auZqEMtLvmafVuHRP0d?usp=sharing">Sample code</a>, <a href="https://colab.research.google.com/drive/1p22oCIaFFfDU9BwzwdBVq3KPvD4BqBMS?usp=sharing">Sample code-2</a>                                                                                                            |                                                                              |
| 7       | Sep 27 (Fri) | MMW703   | Clustering                                      |<a href="https://www.dropbox.com/scl/fi/wbgevc3jz0s78gfjf5121/lec7-Clustering.pdf?rlkey=3hqdqat6tpzjxrc0ijrjteig4&dl=0">Lec-7</a>                  |     [note1](./notes/BMEG3105_Lec07_1.pdf), [note2](./notes/BMEG3105_Lec07_2.pdf), [note3](./notes/BMEG3105_Lec07_3.pdf), [note4](./notes/BMEG3105_Lec07_4.pdf), [note5](./notes/BMEG3105_Lec07_5.pdf)                 |  <a href="https://github.com/FaizSaeed/Data-Science-Course/blob/master/Book/Introduction%20to%20Data%20Mining_Pang%20Ning%20Tan.pdf">Data mining book</a>,  <a href="https://colab.research.google.com/drive/1z0_IEP-tOZgt7auZqEMtLvmafVuHRP0d?usp=sharing">Sample code</a>, <a href="https://colab.research.google.com/drive/1p22oCIaFFfDU9BwzwdBVq3KPvD4BqBMS?usp=sharing">Sample code-2</a>, [intro to pandas&numpy tutorial](./reading/BMEG3105-Introduction%20to%20Pandas%20and%20NumPy.pptx)  | <span style="color:red;">A1 due</span>                                       |
| 8       | Oct 2 (Wed)  | SC L4    | Classification                                  | <a href="https://www.dropbox.com/scl/fi/7528m7ito74rsvuodphg0/lec8-Classification.pdf?rlkey=0gkyy41tscnxy2o65m7fxehoe&dl=0">Lec-8</a>|         [note1](./notes/BMEG3105_Lec08_1.pdf), [note2](./notes/BMEG3105_Lec08_2.pdf), [note3](./notes/BMEG3105_Lec08_3.pdf), [note4](./notes/BMEG3105_Lec08_4.pdf), [note5](./notes/BMEG3105_Lec08_5.pdf)                                  |<a href="https://github.com/FaizSaeed/Data-Science-Course/blob/master/Book/Introduction%20to%20Data%20Mining_Pang%20Ning%20Tan.pdf">Data mining book</a>, <a href="https://colab.research.google.com/drive/1ogX-QiR1jBWuZjbTXGFhi9H-0XdpGNhU?usp=sharing">Correlation</a>    |                                                                              |
| 9       | Oct 4 (Fri)  | MMW703   | Classification & Perf evaluation                |  <a href="https://www.dropbox.com/scl/fi/2mct7sexeoxdfpcq3h7oo/lec9-Classification2.pdf?rlkey=0sv7kadz83nlg61gvu50phbkm&dl=0">Lec-9</a>       |        [note1](./notes/BMEG3105_Lec09_1.pdf), [note2](./notes/BMEG3105_Lec09_2.pdf), [note3](./notes/BMEG3105_Lec09_3.pdf), [note4](./notes/BMEG3105_Lec09_4.pdf)                                   |    <a href="https://github.com/FaizSaeed/Data-Science-Course/blob/master/Book/Introduction%20to%20Data%20Mining_Pang%20Ning%20Tan.pdf">Data mining book</a>, <a href="https://colab.research.google.com/drive/1U5m5m5IPMTpXzEqz9cpQfODfMOnC7kc6?usp=sharing">Python Tut-2</a>                                 | A2 posted                                                                    |
| 10      | Oct 9 (Wed)  | SC L4    | Perf evaluation                                 |  <a href="https://www.dropbox.com/scl/fi/h95ar5fskzwarnho1ah78/lec10-Performance-evaluation.pdf?rlkey=z0yx29mvczzh74qr0yqguhsce&dl=0">Lec-10</a>  |           [note1](./notes/BMEG3105_Lec10_1.pdf), [note2](./notes/BMEG3105_Lec10_2.pdf), [note3](./notes/BMEG3105_Lec10_3.pdf), [note4](./notes/BMEG3105_Lec10_4.pdf), [note5](./notes/BMEG3105_Lec10_5.pdf)                        |   <a href="https://github.com/FaizSaeed/Data-Science-Course/blob/master/Book/Introduction%20to%20Data%20Mining_Pang%20Ning%20Tan.pdf">Data mining book</a>                                                                                                  |                                                                              |
| 11      | Oct 16 (Wed) | SC L4    | Dim reduction   |<a href="https://www.dropbox.com/scl/fi/qujzw3w9pg6haltjfr1cf/lec11-Feature-selection-and-DR.pdf?rlkey=1d9xewdqbxpj7bjgqkay0o9dy&dl=0">Lec-11</a>  |      [note1](./notes/BMEG3105_Lec11_1.pdf)   | <a href="https://github.com/probml/pml-book">PML book</a>                                                                                                                                                                                                                      |                                                                              | 
| 12      | Oct 18 (Fri) | MMW703   | Midterm review                              |  <a href="https://www.dropbox.com/scl/fi/orvc09uonexkz6mb22qk9/lec12-Mid-term-review.pdf?rlkey=716y4awgbtxq0l08bku7x6i3g&dl=0">Lec-12</a>   |                 |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |            <span style="color:red;">Quiz</span>, <span style="color:red;">A2 due</span>      |
| 13      | Oct 23 (Wed) | SC L4    | Midterm                                  |          |                                                                                                                                                                                                             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | <span style="color:red;">8:30am-11:15am, Midterm exam</span>  |
|         |              |          | <span style="color:blue;">Module 2 start</span> |                                                                                                                                                   |                                                                                                                                                                                                             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                                                                              |
| 14      | Oct 25 (Fri) | MMW703   | Multi-omics overview      | <a href="https://www.dropbox.com/scl/fi/yimv9mmdjmn4m12dgkhej/lec14-multi-omics.pdf?rlkey=wtzpwtglz9wozv1rb2pnzk2zw&dl=0">Lec-14</a>   |                                                                                                                                                                                                             | <a href="https://d2l.ai">D2L book</a>, <a href="https://www.cancer.gov/about-cancer/understanding/what-is-cancer">Intro to cancer</a>, <a href="https://www.ebi.ac.uk/training/materials/cancer-genomics-materials/">Cancer genomics</a>                                                                                                                                                                                       |                 |
| 15      | Oct 30 (Wed) | SC L4    |  Cancer genomics overview                           |   <a href="https://www.dropbox.com/scl/fi/6cw1bp1ksg9g1hajhgxm4/lec15-cancer-genomics.pdf?rlkey=fb6u00vbr1lbqlbhlalodtf8m&dl=0">Lec-15</a>           |         |   <a href="https://www.cancer.gov/about-cancer/understanding/what-is-cancer">Intro to cancer</a>, <a href="https://www.ebi.ac.uk/training/materials/cancer-genomics-materials/">Cancer genomics</a>, <a href="https://www.ebi.ac.uk/training/materials/cancer-genomics-materials/">Cancer genomics</a>, <a href="https://drive.google.com/drive/folders/1y7q0gJ-ohNDhKG85UTRTwW1Jkq4HJ5M3">GATK</a>, <a href="https://www.youtube.com/watch?v=xw419NKqMqw">GWAS</a>, <a href="https://www.youtube.com/watch?v=IAu44BkOaSs">Epigenetics</a>, <a href="https://www.encodeproject.org/atac-seq/">ENCODE</a>                                                                                                                                                                                            | PA1 posted                                                                   |
| 16      | Nov 1 (Fri)  | MMW703   | Genomics data analysis                       | <a href="https://www.dropbox.com/scl/fi/0stw9cvnq5exdr6wdy24b/lec16-genomics-analysis.pdf?rlkey=28ypxvua77bi2p7q8rz9oys1i&dl=0">Lec-16</a>     |      |   <a href="https://drive.google.com/drive/folders/1y7q0gJ-ohNDhKG85UTRTwW1Jkq4HJ5M3">GATK</a>, <a href="https://www.youtube.com/watch?v=xw419NKqMqw">GWAS</a>, <a href="https://www.youtube.com/watch?v=IAu44BkOaSs">Epigenetics</a>, <a href="https://www.encodeproject.org/atac-seq/">ENCODE</a>        <a href="https://colab.research.google.com/drive/12C94W2EzsT6yt3rL6WBbraz0z2flc0_3?usp=sharing">Tutorial-3</a>                                                                                                                           |                                                                              |
| 17      | Nov 6 (Wed)  | SC L4    | Single cell genomics  |  <a href="https://www.dropbox.com/scl/fi/00ajvibig11av838fhyxz/lec17-single-cell.pdf?rlkey=lelvpltmbwjcojdx53vzaoepo&dl=0">Lec-17</a>      |                | <a href="https://colab.research.google.com/drive/1ZJHyYJTTcQ05TmQMhrrWOF4jWCgIcJw6?usp=sharing">Tut-4</a>, <a href="https://www.dropbox.com/s/7kqrm7jdn4swsor/Single%20cell-Current%20best%20practice.pdf?dl=0">Current best practice</a>, <a href="https://www.dropbox.com/s/ibcw0mlsq4f2zl2/Single%20cell-Tutorial.pdf?dl=0">Tutorial-1</a>, <a href="https://broadinstitute.github.io/2019_scWorkshop/">Tutorial-2</a>, <a href="https://www.singlecellcourse.org/index.html">Tutorial-3</a>, <a href="https://www.dropbox.com/s/99o7ph37b9uveau/Single%20cell-Clustering%20challenges.pdf?dl=0">Clustering challenges</a> , <a href='https://colab.research.google.com/drive/1wdz8uKWFafey16DU3pCPdvM8FOAGuMGt?usp=share_link'>PyTorch Tutorial</a>                |                                                                              |
| 18      | Nov 8 (Fri)  | MMW703   | Data visualization                           | <a href="https://www.dropbox.com/scl/fi/qd154en9lci8nj679z6up/lec18-visualization.pdf?rlkey=i4e4gwk1gscefa93wr7nteuhg&dl=0">Lec-18</a>    |                                       | <a href="https://www.dropbox.com/s/idrobwfp4clars3/lec18-IntroductionToSequenceMotifs.pdf?dl=0">Sequence motif</a>, <a href="https://colab.research.google.com/drive/1Mmtu4pLfj1Cak-MaWaB5f7y6XvqiO1tc?usp=sharing">PCA-tSNE-UMAP</a>,<a href="https://d2l.ai">D2L book</a>        <a href="https://colab.research.google.com/drive/11wHLOs1IiqomvTCwXX9_lu6H76eCJj8a?usp=sharing">Tutorial-4</a>  <a href="https://colab.research.google.com/drive/1bhyUnHh0LkVTdIdmqqtrsNpZimaS9SKS?usp=sharing">Tutorial-5</a>|                       <span style="color:red;">Project M-report (Proposal) due</span>                                                       |
|         |              |          | <span style="color:blue">Module 3 start</span>  |                                                                                                                                            |                                                                                                                                                                                                             |                               |                                                                              |
| 19      | Nov 13 (Wed) | SC L4    | Deep learning  | <a href="https://www.dropbox.com/scl/fi/5xh2p0dga3pv8ejbxp27l/lec19-deep-learning.pdf?rlkey=cy1y1dzi3lzpcy1prb9jdwmgg&dl=0">Lec-19</a> | | <a href="https://colab.research.google.com/drive/1CEF_yzuCazecajrDblegX6hw3pBPm-qN?usp=sharing">Pytorch examples</a>  |           A3 posted        |
| 20      | Nov 15 (Fri) | MMW703   | CNN       | <a href="https://www.dropbox.com/scl/fi/fdb6r1ib1a5cp6ug5jvsk/lec20-cnn-ehr.pdf?rlkey=pyydzph95mruljhc91uscvaau&dl=0">Lec-20</a>   |                                              | <a href="https://colab.research.google.com/drive/1CEF_yzuCazecajrDblegX6hw3pBPm-qN?usp=sharing">Pytorch examples</a>, <a href="https://towardsdatascience.com/introduction-to-clinical-natural-language-processing-predicting-hospital-readmission-with-1736d52bc709">EHRs processing</a>    |     <span style="color:red;">PA1 due</span>                                                                          |
| 21      | Nov 20 (Wed) | SC L4    | EHRs & Text   |   |  |                          |  
| 22      | Nov 22 (Fri) | MMW703   | Project Presentation      |  |    |     |                       <span style="color:red;">A3 due</span>                                           |
| 23      | Nov 27 (Wed) | SC L4    | Course review   |    |   |   |                                                               <span style="color:red;">Quiz</span>        |
| 24      | Nov 29 (Fri) | MMW703   | Project Presentation        |||                             |    <span style="color:red;">Project report due on 2 Dec</span>  |



### <a id="assignments">Assignments</a>
<ul>
<li>Programming Assignment 0: Get yourself familiar with <a href="https://colab.research.google.com/notebooks/intro.ipynb">Colab</a>, set up the environment and run a sample code.</li>

<li>Assignment 1: Basic concept of data analytics-1</li>

<li>Assignment 2: Basic concept of data analytics-2</li>

<li>Programming Assignment 1: Application of DA to biology</li>

<li>Assignment 3: DA in Personalized Genomics and Precision Medicine</li>
</ul>











