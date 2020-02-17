

### Recommended flow
Get a good grasp of the basic concepts. What is probability, what is a prior, what is conditioning on data and a posterior? No need for MCMC as of yet. This step is optional as this should be included in the second one, but can help get you started with “nice” resources. Commit to a (good) course that takes you from toy examples to actual model building and explains MCMC on the way. Stick to it. Now you’re more than ready to start applying what you’ve learned.

##### Resources for recommended flow
  * Kruschke: Doing Bayesian Data Analysis, 2nd ed; Chapters 2,4 and 5.
  * McElreath: Statistical Rethinking, 2nd. ed.

##### Lectures and books (several, among them:)
  * Gelman et al.: Bayesian Data Analysis, 3rd ed.
  * The STAN documentation.
  * Case studies by Michael Betancourt.
  * Different blogs.

Keep learning with more specific resources when needed or when you want to.


### Probably the best approach to learning Bayes out there
Complete course using R and STAN. There is a port for PyMC3 (as alternative to STAN) for the first edition. Not yet for the second edition. The author is an anthropologist and not a statistician and it shows in his approach to teaching. Lecture series is available on youtube and highly recommended. Potentially new versions will be uploaded and constantly get better. Focusses on code more than formal math and tries to be accessible. 

##### Lecture series: 
https://www.youtube.com/watch?v=4WVelCswXo4&list=PLDcUM9US4XdNM4Edgs7weiyIguLSToZRI

Second ed. of book not published yet but is definitely the better one, so use it. The draft can be downloaded here: 
https://xcelab.net/rm/sr2/

Password is at end of 2nd lecture.

### This is THE book on Bayesian data analysis
Gelman, A., Carlin, J. B., Stern, H. S., Dunson, D. B., Vehtari, A. & Rubin, D. B. (2013): Bayesian Data Analysis 3rd edn, Chapman and Hall.

However, it’s probably too technical, too mathematical and too in-depth to get you started. Buy it, have it lying around to impress people and use it as a reference when you’re done with McElreath’s course. E.g. read chapter 7 to understand problems of Bayes Factors.

### A course on Bayesian approaches to fit parameters of cognitive models
Not a course on Bayesian models of cognition (as in predictive coding), but a course on Bayesian approaches to fit parameters of cognitive models. Maybe worth it as a shortcut if you want to start modeling right away, but you learn the same and much more if you choose Krusche or McElreath as main source.

Lee, M.D. & Wagenmakers, E.-J. (2014): Bayesian Cognitive Modeling: A Practical Couse. Cambridge University Press.

### Documentation on STAN
Excellent documentation of STAN, the recommended tool for Bayesian analysis. Is separated into different parts, the “User guide” can be considered an example-driven introduction to Bayesian modeling. Whenever you have a question about STAN, ask the documentation first and you’ll likely find it. If you want to fit a model, look for a similar example here. 

The STAN documentation: https://mc-stan.org/users/documentation/

### Betancourt's Bayesian world
Everything by Michael Betancourt. He’s a physicist gone statistician and probably the person I’ve learned the most from in terms of Bayesian anything. It’s so good, I even pay for his patreon to listen to his podcast with Dan Simpson. Has case studies ranging from simple regression models to robust workflow and diagnosing divergences in hierarchical models. Sometimes a bit technical if you just get started. 

Link to Michael Betancourt’s case studies:
https://betanalpha.github.io/writing/

Some Highlights:
https://betanalpha.github.io/assets/case_studies/rstan_workflow.html

https://github.com/betanalpha/knitr_case_studies/tree/master/weakly_informative_shapes

### Some Interesting Blogs
Andrew Gelman (and guest authors) on more technical details and discussion of statistical mistakes in published research. Highly opinionated and thus entertaining but tends to be super technical. 
Thomas Wiecki was PhD student with Michael Frank and is now Data Science head at Quantopian and core developer for PyMC3 (Python alternative to STAN). Extremely accessible blog entries. 

Gelman:
https://statmodeling.stat.columbia.edu/
Thomas Wiecki:
https://twiecki.io/

This was contributed by:  
l.neugebauer@uke.de  
on 12. December 2019  

-----------

