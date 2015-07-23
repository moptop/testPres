PitchSlides
========================================================
author: David Russo
date: 7/23/2015

This GRADING APP will save your life!
========================================================

##### Acually, the app was created just to test shiny's functionality.
##### For that matter, this slide presentation is simply testing out 'R Presenter'.
##### Shhhhh....


========================================================
## Have you ever wondered how your teachers come up with your final letter grade in a class? 
<br><br>
## Well, wonder no more... they use this very app
- You will be able to enter the three numerical exam grades you received
- When you are sure you entered them correctly, you will just hit submit
- and the APP will display your numerical average and final letter grade!!!

The app is written in R, using the Shiny package.
========================================================
#### For a look behind the curtain, here's a sample calculation

```r
grade1 <- 88
grade2 <- 95
grade3 <- 91
(average <- mean(grade1, grade2, grade3))
```

```
[1] 88
```

========================================================
#### Continued...

```r
(letterGrade <- if (average >= 90) 'A'
                  else if (average >= 80) 'B'
                  else if (average >= 70) 'C'
                  else if (average >= 60) 'D'
                  else 'F')
```

```
[1] "B"
```
## Buy now while supplies last!
