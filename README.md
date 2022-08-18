# Numerical Linear Algebra
# MATH 5374 Fall 2022

## Instructor: Nestor Guillen
## nestor@txtstate.edu

## Course format

Welcome to Numerical Linear Algebra!.


**Lectures**. Class meets Tuesdays and Thursdays from 9:30 to 10:50 am. 

**Office Hours**. Tuesdays and Thursdays from 11 am to noon, or by appointment (request via email at least one day in advance). 

**Forums**. Apart from lectures and office hours, the most important point of interaction for the class will be **the Canvas Discussions page**. If you have a question related to a particular problem set, or a question about a method discussed in a lecture, this should be the first place to share that question. Sometimes I will provide answers to forum questions, or use a question to explain a broader point or a method.

While a Discussion forum is not quite a replacement for the discussions we would have face to face in a classroom, experience with public forums like [Stack Exchange](https://en.wikipedia.org/wiki/Stack_Exchange) and [MathOverflow](https://en.wikipedia.org/wiki/MathOverflow) suggests this can be a great learning tool in their own right.

**Emails**. I will get back to any email within 72 hours. Preferably, questions about the content of the class should be posted on the course forum, with email used for individual concerns or questions -- but this is not a strict rule. **Please make sure to start the subject line of your emails with 'MATH5374', so that I can reply promptly.**

## Course overview

This course deals with numerical algorithms used to solve linear problems. Topics include condition numbers and the numerical stability of linear algorithms; matrix factorizations like the Singular Value Decomposition; the least squares method; iterative algorithms like the conjugate gradient method; and more. We will illustrate such topics by bringing examples of linear problems that arise in applications. The theory will be balanced with exercises involving the implementation of algorithms in Python.

**Prerequisites**. Linear algebra at the level of Math 3377. Basic programming skills, as well as familiarity with real analysis are helpful additions but not strictly necessary for the course.

**Course materials**. We will follow the linear algebra chapters of [Numerical Algorithms](https://people.csail.mit.edu/jsolomon/#book) by Solomon and parts of [Numerical Linear Algebra](https://people.maths.ox.ac.uk/trefethen/text.html) by Trefethen and Bau.

You will need access to a computer that can run Python as well as Jupyter Notebooks -- more information on this will be given in class. A helpful resource on Python is the [SciPy Lectures](https://scipy-lectures.org/_downloads/ScipyLectures-simple.pdf), available for free online. 

## Course evaluation
	
**Overview**: There will be weekly problem sets (about 6 total), a midterm, and final exam. These are weighted as follows

Problem sets: 50%

Midterm: 25%

Final: 25%

Bonus points: 0.5% extra point per bonus point earned.

**Your weekly work flow:** Apart from watching/attending the week's lectures, you are expected to check the course homepage and the Canvas Discussion page regularly. Announcements will be made via email and through the Announcement function on Canvas. I may from time to time highlight any particularly helpful forum discussions.  Problem sets will be due  **on Fridays at 11:59 pm** and submitted on Canvas. 

**Problem sets**: These amount to 50% of the final numerical grade and will be due approximately every two weeks. Your lowest problem set grade will be dropped when computing your problem sets average. **Late problem sets will not be accepted save for exceptional circumstances.** If you don't submit a problem set on time you will be given a zero on that problem set. On the other hand you could miss one problem set and still be able to get a perfect final grade. *If you have read this far into the syllabus, please provide write me an email with the subject line 'syllabus!' --and feel free to add any interesting thing you'd like to share in the body of the email, e.g. memes, movie or book recommendations, facts about you, etc (just a blank email is fine too).*

**Grading of Problem Sets**: You will receive graded problem sets/exams a week after they were submitted. I will not be posting solutions to **all** problem or exams but will aim to post solutions for about half of the problems. You are encouraged to stop by office hours to discuss the solution of any given problem or to discuss in the Forum.

**Bonus points**: Bonus points can be obtained by solving more difficult (optional) problems, such problems will be present in several weekly problems sets and will be denoted with an asterisk: *. In a few instances **additional Bonus Problems will be posted in the Course Forum**. To illustrate the role of Bonus Points, if your final numerical grade (before Bonus Points) is 83% and you earned credit for 14 bonus problems throughout the semester, you would get 14 Bonus Points = 7% points so your final numerical grade will be 90% (corresponding to A). Bonus problems will be more challenging and you will only earn credit for them if the solution is entirely correct (that is, you cannot earn partial Bonus Points).

**Submission guidelines**: Your submitted problem sets and exams must be submitted in PDF format. Files should be named as: YourLastName\_ProbSetN.pdf, here N is the corresponding number for the problem set.

**Important dates**: As mentioned earlier, problem sets will be due on Fridays at 11:59 pm. 

  * First problem set due: Friday, September 2nd.

  * Midterm: Thursday, October 27th

  * Final: Date TBA

**Final Course Grade**:  Your final numerical grade is placed on a scale of 100. Your final letter grade will be computed from your final numerical grade as follows

<p style="text-align: center;"> A 90-100 &#8226;  B 80-89.9 &#8226; C 70-79.9 &#8226;  D 60-69.9 &#8226;  F 0-59.9 </p>

## Course topics

  * Basics about scientific computing and numerical analysis
  * Norms, of all kinds, and the notion of a condition number
  * Floating point representation - a quick glance and some warnings.
  * Examples of linear problems: regression, high dimensional statistics, basis functions, least squares, finite elements, Tikhonov regularization, image matching, deconvolution, network analysis
  * Linear algebra basics review -- vector spaces, bases, linear transformations, kernels, inner products 
  * Numerically solving a linear system, the basics!: Never invert A. Backsubstitution and Gauss-Jordan elimination. LU decomposition
  * Algorithmic complexity
  * Dense matrices, sparse matrices, positive definite matrices
  * Cholesky and eigenvector factorizations for positive definite matrices
  * Orthogonality: the QR decomposition and the Householder algorithm
  * Eigenvectors, Krylov subspace methods
  * Iterative methods: splitting, gradient descent, Conjugate gradient descent
  * The SVD and low rank approximation  
