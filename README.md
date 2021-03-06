# Practice Create PT

### Part 1: Getting Started
1. Generate 3 project ideas. Each idea should be a website that uses flask and saves data.
1. In cs50 ide, make a new directory. Copy some files from `froshims` (or your adaptation of it) into your new directory as a starting point. Start building one of your ideas (spend roughly 30 minutes on this part). "start building" = put some text and buttons on webpage and think about what routes you need to create in flask.
1. Go back to the google classroom and complete the assignment reflection.

### Part 2: Storing Data
1. Watch the 47:00 - 54:47 in [this cs50 lecture](https://video.cs50.net/2018/fall/lectures/7?t=47m0s) (in the video table of contents, its just section "froshims1").
1. In the project you started above, add some memory in a similar way to what David Malan did in the lecture. You could use a list like he did, or maybe you just increment a score variable or something like that. __Important: just get something really basic working at first. Baby steps.__ Don't move on until you have working code.
1. Spend at least 60 minutes using this new data storage to grow your program's functionality. You might need to use google or phone a friend to figure out how to do some things. 
1. Go back to the google classroom and complete the assignment reflection.

### Part 3: Implement Your Algorithm
1. Write code inside one of your routes (that is, a function in your `application.py` file) that implements at least part of your algorithm.
2. Have that route render at least part of the output of that algorithm on an html page.
(The equivalent in [here](https://cdn.cs50.net/2018/fall/lectures/7/src7/froshims1/application.py?highlight) might be writing some python code between lines 16 and 17 that calculates something, like this:
```
def registrants():
    countOfStudents = len(students)
    lengthOfStudentNames = 0
    for s in students:
      lengthOfStudentNames += len(s)
    return render_template("registered.html", students=students, averageNameLength = lengthOfStudentNames/countOfStudents)
 
```
(dumb example, but it gives you an idea of the mechanics)
** ask for help if you run into trouble! **
1. Go back to google classroom and complete the assignment reflection doc.
