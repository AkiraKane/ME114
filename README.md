## ME114 Introduction to Data Science and Big Data Analytics ##


#### LSE Methods Summer Programme 2015

[Kenneth Benoit](kbenoit@lse.ac.uk), Department of Methodology, LSE  
[Slava Mikhaylov](s.mikhaylov@ucl.ac.uk), University College London  
[Paul Nulty](p.nulty@lse.ac.uk) (Labs), Department of Methodology, LSE  

**Version:** August 25, 2015

This repository contains the class materials for the [LSE Methods Summer Programme](http://www.lse.ac.uk/study/summerSchools/Methods/home.aspx) course *ME114 Introduction to Data Science and Big Data Analytics* taught in August 2015 by Kenneth Benoit and Slava Mikhaylov.  

### Instructions for use ###

You have three options for downloading the course material found on this page:  

1.  You can download the materials by clicking on each link.  

2.  You can "clone" repository, using the buttons found to the right side of your browser window as you view this repository.  This is the button labelled "Clone in Desktop".  If you do not have a git client installed on your system, you will need to [get one here](https://git-scm.com/download/gui) and also to make sure that [git is installed](https://git-scm.com/downloads).  This is preferred, since you can refresh your clone as new content gets pushed to the course repository.  (And new material will get actively pushed to the course repository at least once per day as this course takes place.)

3.  Statically, you can choose the button on the right marked "Download zip" which will download the entire repository as a zip file.

You can also subscribe to the repository if you have [a GitHub account](https://github.com), which will send you updates each time new changes are pushed to the repository.

### Full course details ###

- Detailed course handout in [pdf format](handout/ME114Handout.pdf)
- Detailed course handout in [markdown/html](handout/ME114Handout.md)

### Office Hours ###

- Ken: Tues 26 Aug, Wed 27 Aug, and Thurs 28 Aug, 13:00 - 14:00, Columbia House B8.11  
- Slava: Mon 25 Aug, Wed 25 Aug, 13:00 - 14:00, Columbia House B8.05


### Instructions for Submitting Homeworks ###

Each homework will be a single file in the [RMarkdown](https://goo.gl/ZqOwUe) format.  The files linked below are *named very carefully*, to make it easy for us to identify your completed lab assignments.  

1.  Obtaining the starter files.  

    Each day below will link the name of a starter file for you to download and work with.  These are in the RMarkdown format.  You should embed your answers, with code, into your version of the instruction files.

2.  Renaming the starter files.  
    
    For example, the first assignment file is named `ME114_assignment1_LASTNAME_FIRSTNAME.Rmd`, which you will need to rename by replacing the uppercase terms with your own last and first names, e.g.  `ME114_assignment1_Nulty_Paul.Rmd`.
    
3.  From RStudio, you can create an HTML outfile file with your evaluated code, figure, and text answers by clicking the "Knit HTML" button in the top of the editor pane in RStudio.  The resulting HTML file will be saved in your working directory.

4.  You will need to upload the resulting HTML file -- renamed! -- to the [course Moodle page](https://shortcourses.lse.ac.uk/course/view.php?id=158), to the appropriate assignment folder.  

We will walk you through this process in the Day 1 lab, so don't worry if it seems complicated the first time.  This sort of careful workflow process and file management is part of learning practical data science too!

### Resources for each day ###

#### Monday, August 17: Overview and introduction to data science [KB, SM]

- [Lecture Notes](day1/ME114_day1.pdf)
- [Assignment 1 as R markdown](day1/ME114_assignment1_LASTNAME_FIRSTNAME.Rmd)
- Assignment 1 **solution** as [R markdown](day1/ME114_assignment1_solution.Rmd) or [R code](day1/ME114_assignment1_solution.R)
- [The results of the data science quiz](http://htmlpreview.github.com/?https://github.com/kbenoit/ME114/blob/master/day1/data_science_quiz.html) and the [anonymized dataset in .csv format](day1/data_science_quiz_results.csv).

#### Tuesday, August 18: Research design issues in data science [SM, KB]  

- [Lecture Notes](day2/ME114_day2.pdf)
- [Assignment 2 as R markdown](day2/ME114_assignment2_LASTNAME_FIRSTNAME.Rmd)
- Assignment 2 **solution** as [R markdown](day2/ME114_assignment2_solution.Rmd)

#### Wednesday, August 19: Linear Regression [SM] 

- [Lecture Notes](day3/ME114_day3.pdf)
- [Assignment 3 as R markdown](day3/ME114_assignment3_LASTNAME_FIRSTNAME.Rmd)
- Assignment 3 **solution** as [R markdown](day3/ME114_assignment3_solution.Rmd)

#### Thursday, August 20: Generalized Linear Regression [SM] 

- [Lecture Notes](day4/ME114_day4.pdf)
- [Assignment 4 as R markdown](day4/ME114_assignment4_LASTNAME_FIRSTNAME.Rmd) 
- Assignment 4 **solution** as [R markdown](day4/ME114_assignment4_solution.Rmd) or [html](http://htmlpreview.github.io/?https://github.com/kbenoit/ME114/blob/master/day4/ME114_assignment4_solution.html)

#### Friday, August 21: Resampling Methods [SM]

- [Lecture Notes](day5/ME114_day5.pdf)
- [Assignment 5 as R markdown](day5/ME114_assignment5_LASTNAME_FIRSTNAME.Rmd)
- Assignment 5 **solution** as [R markdown](day5/ME114_assignment5_solution.Rmd) or [html](http://htmlpreview.github.io/?https://github.com/kbenoit/ME114/blob/master/day5/ME114_assignment5_solution.html)

#### Monday, August 24: Association rules and clustering [KB]

- [Lecture Notes](day6/ME114_day6.pdf)
- Assignment 6 as [R markdown](day6/ME114_assignment6_LASTNAME_FIRSTNAME.Rmd) or [html](http://htmlpreview.github.io/?https://github.com/kbenoit/ME114/blob/master/day6/ME114_assignment6_LASTNAME_FIRSTNAME.html)
- Assignment 6 **solution** as [R markdown](day6/ME114_assignment6_solution.Rmd) or [html](http://htmlpreview.github.io/?https://github.com/kbenoit/ME114/blob/master/day6/ME114_assignment6_solution.html)

#### Tuesday, August 25: Machine Learning [KB]

- [Lecture Notes](day7/ME114_day7.pdf)
- Assignment 7 as [R markdown](day7/ME114_assignment7_LASTNAME_FIRSTNAME.Rmd) or [html](http://htmlpreview.github.io/?https://github.com/kbenoit/ME114/blob/master/day7/ME114_assignment7_LASTNAME_FIRSTNAME.html)
- Association rule mining code example
    - [R code](day7/apriori_example.R)
    - [book dataset for example](https://github.com/WinVector/zmPDSwR/raw/master/Bookdata/bookdata.tsv.gz)
- Assignment 7 **solution** as [R markdown](day7/ME114_assignment7_solution.Rmd) or [html](http://htmlpreview.github.io/?https://github.com/kbenoit/ME114/blob/master/day7/ME114_assignment7_solution.html)

#### Wednesday, August 26: Text analysis [KB]

- [Lecture Notes](day8/ME114_day8.pdf)
- Assignment 8 as [R markdown](day8/ME114_assignment8_LASTNAME_FIRSTNAME.Rmd) or [html](http://htmlpreview.github.io/?https://github.com/kbenoit/ME114/blob/master/day8/ME114_assignment8_LASTNAME_FIRSTNAME.html)
    - sample zip file [`UKimmigTexts.zip`](day8/UKimmigTexts.zip) of texts for building a corpus
- Assignment 8 **solution** as [R markdown](day8/ME114_assignment8_solution.Rmd) or [html](http://htmlpreview.github.io/?https://github.com/kbenoit/ME114/blob/master/day8/ME114_assignment8_solution.html)

#### Thursday, August 27: Unsupervised learning and dimensional reduction [KB]

- [Lecture Notes](day9/ME114_day9.pdf)
- [Assignment 9 as R markdown](day9/ME114_assignment9_LASTNAME_FIRSTNAME.Rmd)
- Assignment 9 **solution** as [R markdown](day9/ME114_assignment9_solution.Rmd) or [html](http://htmlpreview.github.io/?https://github.com/kbenoit/ME114/blob/master/day9/ME114_assignment9_solution.html)

#### Friday, August 28: Mining the Social Web [PN]

- [Lecture Notes](day10/ME114_day10.pdf)
- [Readings](day10/Day10Prep.md)
- [Streaming example code](streamRExample.R)
- [Rest Example code](restExample.R)
- [Assignment 10 as R markdown](day10/ME114_assignment10_LASTNAME_FIRSTNAME.Rmd).  Note: This is a take-home set only, as there is no lab on Day 10.

#### Exam: Friday, August 28, 14:00 - 16:00, Room: TBA

- **Instructions:**  Complete and submit the exam just as you would any lab assignment: by renaming the file, editing the R Markdown, and submitting through Moodle. 
- **Formatting:**  Put your own textual answers in boldface (using `**boldface type**` in RMarkdown), so that we can easily identify them.
- **Deadline:** Monday 30 September 17:00 London time (GMT+1)
- **The exam** in [R Markdown](Exam/ME114_exam_LASTNAME_FIRSTNAME.Rmd) and [html](http://htmlpreview.github.io/?https://github.com/kbenoit/ME114/blob/master/Exam/ME114_exam_LASTNAME_FIRSTNAME.html)
- **The exam solution** in [R Markdown](Exam/ME114_exam_solution.Rmd) and [html](http://htmlpreview.github.io/?https://github.com/kbenoit/ME114/blob/master/Exam/ME114_exam_solution.html)

