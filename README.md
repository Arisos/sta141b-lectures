
  - [STA 141B Data & Web Technologies for Data
    Analysis](#sta-141b-data--web-technologies-for-data-analysis)
      - [People](#people)
      - [Material](#material)
      - [Links](#links)
      - [Tentative Schedule](#tentative-schedule)
      - [Grading](#grading)
      - [Resources](#resources)
      - [Prerequisites](#prerequisites)
      - [How to “clone” the notes repo](#how-to-clone-the-notes-repo)
      - [Assignments](#assignments)
          - [Feedback](#feedback)
          - [Regrade Requests](#regrade-requests)
          - [Assignment Rubric](#assignment-rubric)

# STA 141B Data & Web Technologies for Data Analysis

## People

  - Instructor: Randy Lai<br> You should use Campuswire or Canvas to
    contact me. DO NOT send email to me as I tend to ignore emails (too
    much spams).
  - Meeting time: 9:00 - 10:20 AM, TR
  - TA: Xiancheng Lin, Tongyi Tang and Zhenyu Wei.
  - Office hour:
      - Zhenyu: 4:00 - 5:00 PM Monday
      - Tongyi: 2:00 - 4:00 PM Monday and Tuesday
      - Xiancheng 4:10 - 5:10 PM Thursday
      - Randy: 10:00 AM - 12:00 PM Friday

## Material

| Date  | Note                                            | HTML                                                                                                            |
| ----- | ----------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| 01-05 | Introduction                                    | [introduction](README.md)                                                                                       |
| 01-07 | [dplyr](ch01-dplyr/dplyr.Rmd)                   | [dplyr](https://ucdavis-sta141b-2021-winter.github.io/sta141b-lectures/ch01-dplyr/dplyr.html)                   |
| 01-19 | [sql](ch02-sql/sql.Rmd)                         | [sql](https://ucdavis-sta141b-2021-winter.github.io/sta141b-lectures/ch02-sql/sql.html)                         |
| 02-02 | [json](ch03-nosql/json.Rmd)                     | [json](https://ucdavis-sta141b-2021-winter.github.io/sta141b-lectures/ch03-nosql/json.html)                     |
|       | [nosql](ch03-nosql/nosql.Rmd)                   | [nosql](https://ucdavis-sta141b-2021-winter.github.io/sta141b-lectures/ch03-nosql/nosql.html)                   |
| 02-09 | [shiny](ch04-shiny/shiny.Rmd)                   | [shiny](https://ucdavis-sta141b-2021-winter.github.io/sta141b-lectures/ch04-shiny/shiny.html)                   |
| 02-16 | [api](ch05-api/api.Rmd)                         | [api](https://ucdavis-sta141b-2021-winter.github.io/sta141b-lectures/ch05-api/api.html)                         |
| 02-25 | [webscraping](ch06-webscraping/webscraping.Rmd) | [webscraping](https://ucdavis-sta141b-2021-winter.github.io/sta141b-lectures/ch06-webscraping/webscraping.html) |
| 03-02 | [regex](ch07-regex/regex.Rmd)                   | [regex](https://ucdavis-sta141b-2021-winter.github.io/sta141b-lectures/ch07-regex/regex.html)                   |
| 03-10 | [textmining](ch08-textmining/textmining.Rmd)    | [textmining](https://ucdavis-sta141b-2021-winter.github.io/sta141b-lectures/ch08-textmining/textmining.html)    |

## Links

  - [Canvas](http://canvas.ucdavis.edu/) for grades
  - [GitHub](https://github.com/ucdavis-sta141b-2021-winter) for lecture
    notes and assignments. Please always refer to the documents found on
    GitHub.
  - [Campuswire](https://campuswire.com/c/GC093FD78) for discussions.
    Please use your ucd email to register\! If you have used piazza
    before, it is similar but has a better interface. Please use
    Campuswire to ask any questions related to assignments and course
    materials. I and the TA will not answer any emails related to the
    course materials.<br> Use Join code: 4309<br> Learn how to ask a
    question. Asking a question is an art,
    [stackoverflow.com](https://stackoverflow.com/help/how-to-ask) has
    some good tips. You could also use the
    [reprex](https://reprex.tidyverse.org/) package to make reproducible
    examples.

## Tentative Schedule

| Topics                          |
| ------------------------------- |
| Introduction                    |
| Tidy data                       |
| Databases, SQL and NoSQL        |
| Shiny                           |
| JSON and WebAPI                 |
| Web Scraping                    |
| Regular Expressions and strings |
| Text Mining                     |

## Grading

| Category                                                                                             | Grade Percentage |
| ---------------------------------------------------------------------------------------------------- | ---------------- |
| Assignments                                                                                          | 65%              |
| [Final Project](https://github.com/ucdavis-sta141b-2021-winter/sta141b-lectures/tree/master/project) | 25%              |
| Participation                                                                                        | 10%              |

  - There will be around 6 assignments and they are assigned via GitHub
    classroom.
  - Assignments must be turned in by the due date. No late assignments
    are accepted.
  - Participation will be based on your reputation points in Campuswire.
      - 1% each week if the reputation point for the week is above 20.
      - the top scorers for the quarter will earn extra bonuses.

## Resources

  - J. Bryan, the STAT 545 TAs, J. Hester, Happy Git and GitHub for the
    useR (<https://happygitwithr.com/>)
  - J. Bryan, Data wrangling, exploration, and analysis with R
    (<https://stat545.com/>)
  - G. Grolemund and H. Wickham, R for Data Science
    (<https://r4ds.had.co.nz/>)
  - H. Wickham, Advanced R (<https://adv-r.hadley.nz/>)
  - And a lot of google

## Prerequisites

  - Strong in R programming
  - R 4.0.3 (check your R version)
  - RStudio 1.3.1093 (check your RStudio Version)
  - R Markdown (read this <https://rmarkdown.rstudio.com/lesson-1.html>)
  - Knowledge about git and GitHub: read ‘Happy Git and GitHub for the
    useR’ (It is absoluately important to read the ebook if you have no
    experiences with git/GitHub)

## How to “clone” the notes repo

Assuming that you have `git` installed,

  - Open RStudio -\> New Project -\> Version Control -\> Git -\> paste
    the URL:
    <https://github.com/ucdavis-sta141b-2021-winter/sta141b-lectures.git>
  - Choose a directory to create the project
  - You could make any changes to the repo as you wish.
  - To fetch updates
      - go to the `git` pane in RStudio
      - click the “Commit” button and
      - check the files changed by you
      - type a short message about the changes and hit “Commit”
      - After committing the message, hit the “Pull” button (PS: there
        is a sub button “Pull with rebase”, only use it if you truly
        understand what it is)
      - Done if you see no errors
      - If there were lines which are updated by both me and you, you
        would see a merge conflict.
      - To resolve the conflict, locate the files with conflicts (U flag
        in the git pane).
      - Open the files and edit the conflicts, usually a conflict looks
        like
    <!-- end list -->
        <<<<<<< HEAD
        - RStudio 1.2.5011 (check your RStudio Version)
        =======
        - RStudio 1.2.5033 (check your RStudio Version)
        >>>>>>> 85858c9a6ebba9057ca8db7c269bd0a2f7a3910a
      - check all the files with conflicts and commit them again with a
        new message.

## Assignments

Link your github account at
<https://signin-apd27wnqlq-uw.a.run.app/sta141b/>

Check regularly the course github organization
<https://github.com/ucdavis-sta141b-2021-winter> for any newly posted
assignments.

### Feedback

Feedback will be given in forms of GitHub issues or pull requests.

### Regrade Requests

Regrade requests must be made within one week of the return of the
assignment. One of the most common reasons is not having the knitted
html files uploaded, 30% of the grade of that assignment will be
deducted if it happens. To make a request, send me a Canvas message with
the following information:

  - Which assignment
  - URL to the repo of your assignment
  - The reason of the request

### Assignment Rubric

(Adapted from Nick Ulle and Clark Fitzgerald )

Point values and weights may differ among assignments. This is to
indicate what the most important aspects are, so that you spend your
time on those that matter most. Check the homework submission page on
Canvas to see what the point values are for each assignment.

The grading criteria are correctness, code quality, and communication.
The following describes what an excellent homework solution should look
like:

#### Correctness

The report does the following:

  - solves all the questions contained in the prompt
  - makes conclusions that are supported by evidence in the data
  - discusses efficiency and limitations of the computation
  - cites any sources used

The attached code runs without modification.

#### Code Quality

The code is idiomatic and efficient. Different steps of the data
processing are logically organized into scripts and small, reusable
functions. Variable names are descriptive. The style is consistent and
easy to read.

#### Communication

Plots include titles, axis labels, and legends or special annotations
where appropriate. Tables include only columns of interest, are clearly
explained in the body of the report, and not too large. Writing is
clear, correct English.

#### Inquisitiveness

The report points out anomalies or notable aspects of the data
discovered over the course of the analysis. It discusses assumptions in
the overall approach and examines how credible they are. It mentions
ideas for extending or improving the analysis or the computation.
