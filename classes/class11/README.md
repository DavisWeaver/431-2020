# 431 Class 11: 2020-09-29

[Main Website](https://thomaselove.github.io/431/) | [Course Calendar](https://thomaselove.github.io/431/calendar.html) | [Syllabus](https://thomaselove.github.io/431-2020-syllabus/) | [Course Notes](https://thomaselove.github.io/431-notes/) | [Piazza & TA Office Hours](https://thomaselove.github.io/431/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://thomaselove.github.io/431/data_index.html)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | ways to get help | zoom information | for downloads

> Quote to come.

## Today's Slides

- Class 11 slides are available in [PDF format](https://github.com/THOMASELOVE/431-2020/blob/master/classes/class11/431_class-11-slides_2020.pdf), as well as in [R Markdown](https://github.com/THOMASELOVE/431-2020/blob/master/classes/class11/431_class-11-slides_2020.Rmd).

## Today's Breakout Session

TBD

## Who Will We Meet Today?

- **Modong Yang**, **Wail Yar**, **Kaan Yorgancioglu**, **Danny Lam**, **Jeff Kovach**, and **Arsh Kochar** (64-66 and 19-21 from the Introductory Student Videos in our Shared Google Drive)

## Announcements

1. **STILL TO COME** 
    - Minute Paper after Class 11
    - Answer Sketch for Lab 04
    - Grades + TA Comments on Lab 03
    - Details on how your Project 1 proposal will be evaluated

2. **Project A Proposal** 

- Several students met my Noon 2020-09-27 deadline for an initial review of their proposal. Most of them were quite good, and needed only some small changes. 
- A couple of students tried to use R to do all of the ingestion work, including dropping the first row from the data set and to pull it from the website directly. The best way I know how to do that is shown below. All it requires is `library(tidyverse)` and an active Internet connection to work.

```
data_url <- "https://www.countyhealthrankings.org/sites/default/files/media/document/analytic_data2020_0.csv"
chr_raw <- read_csv(data_url, skip=1, guess_max = 4000)
```

On 2020-09-27, I adjusted the Project Proposal Example to incorporate this idea, and to incorporate several other good ideas, like...

- carefully specifying which variable will be your outcome
- separating out the codebook, some data checks and the proposal requirements from the data development
- fixing a typo or two

So I encourage you to use that version.

3. Some [Quiz 1 information is available now](https://github.com/THOMASELOVE/431-2020/blob/master/quizzes/quiz1/quiz1.md).

4. I updated the [Course Notes](https://thomaselove.github.io/431-notes/) to fix some typos in Chapters 11, 21 and 22. Thank you!
  

## What Should I Be Working On?

1. Minute Paper after Class 11 will be due Wednesday 2020-09-30 at Noon.
2. [Project A](https://thomaselove.github.io/431-2020-projectA/), in particular the Proposal, which is due 2020-10-02. You want the version posted 2020-09-27.
3. Reading: by 2020-10-02, you'll need to have finished the Leek text and chapters 8-9 of Spiegelhalter.

## One Last Thing

TBA.