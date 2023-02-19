# Assignment Project 7

## Linear Regression

In this final module, you'll employ machine learning (ML). At a high-level, there are three general categories of ML: supervised, unsupervised, and reinforcement learning. We'll employ a type of supervised learning, simple linear regression, to train a model using all available data and use the resulting model (a best-fit straight line) to make predictions.

 ## Chapters

- Work through the book and examples from Chapter 10 refreshing especially your work on 10.16 on Time Series and Simple Linear Regression.
- Read through the book and examples from Chapter 15 on Machine Learning, focusing on 15.4 Simple Linear Regression and Predictions.

 ## Get Started

1. Create a new GitHub repo **datafun-07-ml-predictive**
2. Clone your new repo down to your Documents folder.

 ## Task 1

**Read and work through Chapter 10 - Object-Oriented Programming - and understand the examples. **

- 10.1 Introduction
- 10.2 Custom Class Account
- 10.3 Controlling Access to Attributes
- 10.4 Properties for Data Access
- 10.5 Simulating "Private" Attributes
- 10.6 Case Study: Card Shuffling and Dealing Simulation
- 10.7 Inheritance: Base Classes and Subclasses
- 10.8 Building an Inheritance Hierarchy; Introducing Polymorphism
- 10.9 Duck Typing and Polymorphism
- 10.10 Operator Overloading
- 10.11 Exception Class Hierarchy and Custom Exceptions
- 10.12 Named Tuples
- 10.13 A Brief Intro to Python 3.7's New Data Classes
- 10.14 Unit Testing with Docstrings and doctest
- 10.15 Namespaces and Scopes
- 10.16 ★ Intro to Data Science: Time Series and Simple Linear Regression

 ## Task 2

**Read and work through Chapter 15 - Machine Learning - and understand the examples. **

- 15.1 Introduction to Machine Learning
 - 15.1.1 ★ Scikit-Learn
 - 15.1.2 ★ Types of Machine Learning
 - 15.1.3 Datasets Bundled with Scikit-Learn
 - 15.1.4 Steps in a Typical Data Science Study
- 15.2 Case Study: Classification with k-Nearest Neighbors and the Digits Dataset, Part 1
- 15.3 Case Study: Classification with k-Nearest Neighbors and the Digits Dataset, Part 2
- 15.4 ★ Case Study: Time Series and Simple Linear Regression

Suggestion: Specify data file paths as Python raw strings. See FAQ for more.

 ## Task 3 (from 10.16 above)

Follow the process provided in the text.

1. Follow the instructions from 10.16 (starting page 414).
2. Note: The data is for the average (daily) high temperature in January over many years.
3. For example, in 1895, the average high temperature in January was 34.2.
4. We only care about this one series of data: the "average high temp in Jan".
5. There's a lot of stats in the title, and it has confused students. Just think of each value as "the temperature" for that year.
6. We'll use all of the data available to build a best-fit line (supervised learning).
7. We'll use the slope and intercept of the best-fit line to estimate a point out in the future.
8. Use a notebook (rather than interactive mode).
9. Use pandas DataFrames to plot Celsius vs Fahrenheit
10. Refresh your understanding of the equation for a line (y=mx +b)
11. Follow the instructions to load NY City **January high temperature** from a csv file into a DataFrame.
12. Follow the instructions to view **head** and **tail ** of the file.
13. Follow the instructions to **clean ** the data.
14. Use **describe** () to calculate basic descriptive statistics for the dataset.
15. Use the SciPy **stats ** module **linregress ** function to calculate **slope and intercept** for the best fit line through the data.
16. Use your results to **predict** the "average high temp in Jan" for the year **2026.**
17. Follow the instructions and use Seaborn to generate a scatter plot with a best fit line. Set the axes and y limit as instructed.
18. In the same notebook, continue with 15.4 (staring page 620).
19. This time, we'll use scikit-learn estimator, and we'll practice splitting data for training (to build a model) and testing (testing our model against known values).
20. Follow the instructions all the way though charting it again with the specified axes.
21. At the end of your notebook add some remarks comparing the two methods.
22. By now, you know to include the title, your name, and section headings (always!) and to tell an engaging story with data, so we won't remind you.

Excellent analytical skills need professional communication skills to be of maximum benefit.

 ## Task 3 Output

Document your results.

- execute the completed notebook before you commit and push to GitHub.

 ## Task 4. Push to GitHub

Push to GitHub.

 ## Optional Task 5. Bonus

1. Practice more machine learning skills by working through 15.5 with the California Housing Dataset.
2. Follow the instructions all the way though loading the data, training and testing the data, visualizing the data, and choosing the best model from the 4 listed.
3. Customize your presentation and include helpful remarks to "tell a story with data".
4. Execute the notebook.
5. Add/commit/push your changes up to your GitHub repo.

 ## Reflection (on your own)

1. Learning the details of Python, some of modules from the standard library, and several of the key packages for data science was a lot for seven modules.
2. What do you wish you'd known earlier?

 ## Feedback

This course is a graduate-level course for people with a Bachelor's degree, but not necessarily any experience in programming. It should be useful for both CS majors and non-majors.

Your feedback and unique perspective is key to helping us design courses to meet this challenge.

Please complete:

1. the [Q7 Survey](https://nwmissouri.instructure.com/courses/50814/quizzes/218583?wrap=1) and
2. the official course evaluation form.

The survey is used by the instructor to improve the course experience. The course evaluation is used by NW and our school of CSIS. We want to ensure your NW degree is valuable and a good use of your time!

 ## Submission Instructions

1. [Project Submission Instructions](https://nwmissouri.instructure.com/courses/50814/pages/project-submission-instructions?wrap=1)

 ## Submit

 ### Part 1 - Project

1. Paste a clickable link to your public GitHub repo:
2. Your domain:
3. About how long did you spend on class this module:
4. In general, how did it go:
5. What was the most difficult part:
6. What was most interesting:
7. Did you do the optional bonus (y/n). How did it go - or why not?

### Part 2 - Self Assessment

From the Module Overview, paste the numbered list of objectives and assess your ability on each as "Highly proficient", "Proficient", or "Not Proficient":

 ## Reference

1. Remember to explore the code examples and check our FAQ (in Module 0).
2. Read and use the text.
3. Try to resolve issues independently (using the text and a web search).
4. Share technical questions and suggestions in this module's discussion forum.
5. Emails should be for personal things rather than technical questions.
6. If you have a personal issue, be sure to use the correct email subject line (see the syllabus for details).

 ## Grading Rubric

Your assignment will be graded according to the grading rubric.

## Checklist
- [x] Chapters
- [x] Get Started
- [x] Task 1. Read and work through Chapter 10 - Object-Oriented Programming - and understand the examples.
- [x] Task 2. Read and work through Chapter 15 - Machine Learning - and understand the examples.
- [x] Task 3. (from 10.16 above)
- [x] Task 3. Output
- [x] Task 4. Push Repo to GitHub
- [x] Optional Task 5. Bonus
- [x] Reflection (on your own)
- [x] Feedback
- [x] Submission Instructions
- [x] Submit
- [x] Part 1 - Project
- [x] Part 2 - Self Assessment
- [x] Reference
- [x] Grading Rubric