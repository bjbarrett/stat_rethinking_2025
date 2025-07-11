Statistical Rethinking (2025 Edition)
===============

Instructor: Brendan Barrett (bbarrett@ab.mpg.de)

Lectures: Uploaded and pre-recorded, 1-2 per week

Discussion and Lab: In person (Bücklestrasse 5, 5th floor common area) and Online ([Zoom](https://uni-konstanz-de.zoom.us/j/91825266106?pwd=C9z0uAclXpRmnuXy8yfQ0nlUwBq1FP.1) once weekly on Mondays at 13:30

# Purpose

This course teaches data analysis, but it focuses on scientific models. The unfortunate truth about data is that nothing much can be done with it, until we say what caused it. We will prioritize conceptual, causal models and precise questions about those models. We will use Bayesian data analysis to connect scientific models to evidence. And we will learn powerful computational tools for coping with high-dimension, imperfect data of the kind that biologists and social scientists face.

# Format

Online, flipped instruction. You will watch the authors online pre-recorded lectures. We'll meet in person and online once a week for an 1.5 hours to discuss the material and work on exercises together. 

We'll use the 2nd edition of, <[Statistical Rethinking](https://xcelab.net/rm/statistical-rethinking/)>.. If you require a PDF of the book and are enrolled in the course reach out to me.

Registration: 30 people limit.

# Calendar & Topical Outline

There are 16[17] weeks of instruction. Links to lecture recordings will appear in this table. Weekly problem sets are assigned on Mondays and due the next Monday, when we discuss the solutions in the weekly online meeting. The first unofficial meeting is an intro and there will not be problem sets assigned. I will be available to help troubleshoot and issues you are having with installing `cmdstanr` or `rethinking`

Full lecture playlist: <[Statistical Rethinking 2023 Playlist](https://www.youtube.com/watch?v=FdnMWdICdRs&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus)>

Note about slides: In some browsers, the slides don't show correctly. If points are missing from plots, download the slides PDF instead of viewing in browser.

| Week ## | Meeting date | Reading | Lectures |
| ------- | -------------- | ------------- | ---------------------- |
| Week 00 | 26 May  | Chapter 1 | [1] <[Science Before Statistics](https://www.youtube.com/watch?v=FdnMWdICdRs&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=1)> <[Slides](https://speakerdeck.com/rmcelreath/statistical-rethinking-2023-lecture-01)> 
| Week 01 | 02 June  | Chapters 2,3 |  [2] <[Garden of Forking Data](https://www.youtube.com/watch?v=R1vcdhPBlXA&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=2)> <[Slides](https://speakerdeck.com/rmcelreath/statistical-rethinking-2023-lecture-02)> 
| Week 02 | 16 June | Chapter 4 | [3] <[Geocentric Models](https://www.youtube.com/watch?v=tNOu-SEacNU&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=3)> <[Slides](https://speakerdeck.com/rmcelreath/statistical-rethinking-2023-lecture-03)> <br> [4] <[Categories and Curves](https://www.youtube.com/watch?v=F0N4b7K_iYQ&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=4)> <[Slides](https://speakerdeck.com/rmcelreath/statistical-rethinking-2023-lecture-04)>
| Week 03 | 30 June  | Chapter 5 |  [5] <[Elemental Confounds](https://www.youtube.com/watch?v=mBEA7PKDmiY&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=5)> <[Slides](https://speakerdeck.com/rmcelreath/statistical-rethinking-2023-lecture-05)>
| Week 04 | 07 July | Chapter 6 |  [6] <[Good and Bad Controls](https://www.youtube.com/watch?v=uanZZLlzKHw&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=6)> <[Slides](https://speakerdeck.com/rmcelreath/statistical-rethinking-2023-lecture-06)>
| Week 05 | 29 July **TUESDAY**| Chapters 7,8 | [7] <[Overfitting](https://www.youtube.com/watch?v=1VgYIsANQck&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=7)> <[Slides](https://speakerdeck.com/rmcelreath/statistical-rethinking-2023-lecture-07)>
| Week 06 | 04 Aug | Chapter 9 | [8] <[MCMC](https://www.youtube.com/watch?v=rZk2FqX2XnY&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=8)> <[Slides](https://speakerdeck.com/rmcelreath/statistical-rethinking-2023-lecture-08)>
| Week 07 | 25 Aug | Chapter 10 | [9] <[Modeling Events](https://www.youtube.com/watch?v=Zi6N3GLUJmw&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=9)> <[Slides](https://speakerdeck.com/rmcelreath/statistical-rethinking-2023-lecture-09)>
| Week 08 | 01 Sept | Chapter 11 | [10] <[Counts and Confounds](https://www.youtube.com/watch?v=jokxu18egu0&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=10)> <[Slides](https://speakerdeck.com/rmcelreath/statistical-rethinking-2023-lecture-10)> <br> [11] <[Ordered Categories](https://www.youtube.com/watch?v=VVQaIkom5D0&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=11)> <[Slides](https://github.com/rmcelreath/stat_rethinking_2023/raw/main/slides/Lecture_11-ord_logit.pdf)>
| Week 09 | 15 Sept | Chapter 12 | [12] <[Multilevel Models](https://www.youtube.com/watch?v=iwVqiiXYeC4&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=12)> <[Slides](https://raw.githubusercontent.com/rmcelreath/stat_rethinking_2023/main/slides/Lecture_12-GLMM1.pdf)>
| Week 10 | 22 Sept | Chapter 13 | [13] <[Multilevel Adventures](https://www.youtube.com/watch?v=sgqMkZeslxA&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=13)> <[Slides](https://raw.githubusercontent.com/rmcelreath/stat_rethinking_2023/main/slides/Lecture_13-GLMM2.pdf)> 
| Week 11 | 29 Sept | Chapter 13 | [14] <[Correlated Features](https://www.youtube.com/watch?v=Es44-Bp1aKo&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=14)> <[Slides](https://github.com/rmcelreath/stat_rethinking_2023/raw/main/slides/Lecture_14-GLMM3.pdf)>
| Week 12 | 06 Oct | Chapter 14 | [15] <[Social Networks](https://www.youtube.com/watch?v=hnYhJzYAQ60&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=15)> <[Slides](https://github.com/rmcelreath/stat_rethinking_2023/raw/main/slides/Lecture_15-social_networks.pdf)>
| Week 13 | 13 Oct | Chapter 14 | [16] <[Gaussian Processes](https://www.youtube.com/watch?v=Y2ZLt4iOrXU&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=16)> <[Slides](https://github.com/rmcelreath/stat_rethinking_2023/raw/main/slides/Lecture_16-gaussian_processes.pdf)>
| Week 14 | 20 Oct | Chapter 15 | [17] <[Measurement](https://www.youtube.com/watch?v=mt9WKbQJrI4&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=17)> <[Slides](https://github.com/rmcelreath/stat_rethinking_2023/raw/main/slides/Lecture_17-measurement.pdf)> <br> [18] <[Missing Data](https://www.youtube.com/watch?v=Oeq6GChHOzc&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=18)> <[Slides](https://github.com/rmcelreath/stat_rethinking_2023/raw/main/slides/Lecture_18-missing_data.pdf)>
| Week 15 | 27 Oct | Chapter 16 | [19] <[Generalized Linear Madness](https://www.youtube.com/watch?v=zffwg0xDOgE&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=19)> <[Slides](https://github.com/rmcelreath/stat_rethinking_2023/raw/main/slides/Lecture_19-GenLinearMadness.pdf)> <br> [20] <[Horoscopes](https://www.youtube.com/watch?v=qwF-st2NGTU&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=20&pp=sAQB)> <[Slides](https://github.com/rmcelreath/stat_rethinking_2023/raw/main/slides/Lecture_20-horoscopes.pdf)>
| Week 16 | 03 Nov | Chapter 17 and Presentations| [20] <[Horoscopes](https://www.youtube.com/watch?v=qwF-st2NGTU&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus&index=20&pp=sAQB)> <[Slides](https://github.com/rmcelreath/stat_rethinking_2023/raw/main/slides/Lecture_20-horoscopes.pdf)>

# Coding

This course involves a lot of scripting. Students can engage with the material using either the original R code examples or one of several conversions to other computing environments. The conversions are not always exact, but they are rather complete. Each option is listed below. I will teach in R. If you wish to try some of the other online language conversions below, feel free to but I will not be of much use to help you with some coding issues. 

## Original R Flavor

For those who want to use the original R code examples in the print book, you need to install the `rethinking` R package. The code is all on github <https://github.com/rmcelreath/rethinking/> and there are additional details about the package there, including information about using the more-up-to-date `cmdstanr` instead of `rstan` as the underlying MCMC engine.

## R + Tidyverse + ggplot2 + brms

The <[Tidyverse/brms](https://bookdown.org/content/4857/)> conversion is very high quality and complete through Chapter 14.

## Python and PyMC3

The <[Python/PyMC3](https://github.com/pymc-devs/resources/tree/master/Rethinking_2)> conversion is quite complete.

## Julia and Turing

The <[Julia/Turing](https://github.com/StatisticalRethinkingJulia)> conversion is not as complete, but is growing fast and presents the Rethinking examples in multiple Julia engines, including the great <[TuringLang](https://github.com/StatisticalRethinkingJulia/TuringModels.jl)>.

## Other

The are several other conversions. See the full list at <https://xcelab.net/rm/statistical-rethinking/>.

# Homework and solutions

I will also post problem sets and solutions. Check the folders at the top of the repository. After our weekly discussion about the lectures and book chapters, we will work through problem sets together and go over answers at the end of the following week. Some will be from the book, and some I will make up using real data pulled from my work, my colleagues work, or open-access repositories associated with published papers. Preparing homework using RMarkdown `.RmD` or Quarto`.quarto` files will nbe of use to yourself and your classmates when sharing results and thinking.

# Grading
If you are a student taking the course for credit you will have to have one evaluated assignment.
1. Use a structural causal model or direceted cyclical graph to help formulate the models you wish to analyze in one of your dissertation chapters or projects.
2. Simulate Data based on your DAG or SCM, and recover parameters of interest to show you can answer the question you propse with a realistic sampling regime/design
3. AND/OR Run an analyses using the skills you learned in class for data you have collected.

The goal is to generalte a product that will be useful for you or make your science better.




