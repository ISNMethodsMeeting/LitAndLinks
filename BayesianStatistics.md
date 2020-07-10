# Learning Bayesian Statistics the right way

## Recommended flow for beginners

As someone starting out to learn Bayesian statistics without a lot of background, get a good grasp of the basic concepts. What is probability, what is a prior, what is conditioning on data and a posterior? No need for MCMC as of yet. This step is optional as this should be included in the second one, but can help get you started with “nice” resources. Commit to a (good) course that takes you from toy examples to actual model building and explains MCMC on the way. Stick to it.

Here's how you do that:

##### Resources for recommended flow
  * Kruschke: Doing Bayesian Data Analysis, 2nd ed; Chapters 2,4 and 5.
  * McElreath: Statistical Rethinking, 2nd. ed.

Kruschke's book is really accessible and a great way to get started with the basic concepts. In my opinion it is not the best (but still a very good) option beyond that. For once, it's still mostly using JAGS instead of a modern sampler like STAN or PyMC3. Besides, it's focussing a bit too much on Bayesian alternatives to frequentist NHST approaches instead of emphasizing the construction of a generative model. Reading chapters 2,4 and 5 gives you a solid foundation to proceed with another ressource.

McElreath's book is the recommended course for learning Bayesian stats by just about everybody. It just came out in the 2nd edition which adds a lot on prior predictive checks and causal inference. The basic idea is that you get rid of flow-chart statistics in which the kind of data you have tells you which test to use. Instead you'll get comfortable with writing down the process that supposedly generated the data in a probabilistic program in STAN. Another selling point is that this course comes with a lecture series by the author. So you can watch the lecture, read the chapter, meet a colleague to do some exercises and in half a year you're done. 
The lecture series can be found [here](https://www.youtube.com/watch?v=4WVelCswXo4&list=PLDcUM9US4XdNM4Edgs7weiyIguLSToZRI).


## Bayesian cognitive modeling

Even if you want to use Bayesian methods only for cognitive modeling, it's still recommended to follow the workflow from above. If you understand the concepts, it's straight-forward to estimate parameters of a cognitive model with Bayesian methods. Still, here are a few ressources that focus more on the modeling aspect

##### Resources for Bayesian cognitive modeling
	* Lee, M.D. & Wagenmakers, E.-J. (2014): Bayesian Cognitive Modeling: A Practical Couse. Cambridge University Press.
	* Zhang, Lei: Bayesian Statistics and Hierarchical Bayesian Modeling for Psychological Science.

Both are not courses on Bayesian models of cognition (as in predictive coding), but on Bayesian approaches to fit parameters of cognitive models. The Lee & Wagenmakers book makes a few shortcuts compared to more general Bayesian courses to get you started with models faster. If you go through McElreath's or Krusche's book, you'll know all of it and more. So it's maybe worth it as a shortcut, but obsolete once you cover the basics anyway. 
Our friend Lei Zhang based parts of his course on McElreath's book. So parts might feel familiar, if you've done this before. But if emphasizes the application to cognitive modeling and is a very good addition to a more basic course.You can find the [lectures](https://www.youtube.com/watch?v=8RpLF7ufZs4&list=PLfRTb2z8k2x9gNBypgMIj3oNLF8lqM44-) and [slides](https://github.com/lei-zhang/BayesCog_Wien) online.


## Getting deeper

If you want to get deeper than this, I'd honestly recommend to first brush up on mathematics. Some level of applied statistics can be well understood without strong math skills, but beyond that you need calculus. Assuming you have this, here are a few resources:

#### Gelman et al.: Bayesian Data Analysis, 3rd ed.

This is something like THE encyclopedia on Bayesian statistics. Andrew Gelman is the guy behind NUTS (the sampler implemented in STAN). The book is very technical and impossible to read without at least basic calculus skills. Theoretically it could be used as a first course if you're from a more technical background. There's a lecture series by Aki Vehtari floating around the internet, he's one of the co-authors. I would use it as a reference or as a book that you have in your shelf with the strong intention to work through eventually. It's a good reference if you e.g. want to understand what the problem with Bayes factors is.

#### The STAN documentation

The STAN documentation is a piece of art. By now it's split into three parts. The "User Guide" can be considered a Bayesian course on it's own. Beyond the stuff that the other ressources covers, you'll find information on how to write not only correctly specified models but also efficient ones. Unfortunately this isn't always the same. You'll use the documentation often, when you're actually using STAN, but even if you're using other probabilistic programming languages (like PyMC3, tfp, Edward, JAGS...), it's a fantastic resource.

#### Case studies by Michael Betancourt.

Michael Betancourt is on the STAN team. He's a physicist by training that became a statistician momentarily. He writes case studies and gives workshops. His stuff is probably too technical to get started, but it's insanely useful after that. If you want to understand why hierarchical models might have divergent transitions, what a good workflow for Bayesian statistics would be, how Hamiltonian Monte Carlo works or want to get a reasonably accessible intro to probability theory, he's the man. Here's his [case studies](https://betanalpha.github.io/writing/). 
  * Different blogs.

#### Thomas Wiecki's blog

Thomas Wiecki was a PhD student with Michael Frank, is now head data scientists at some company and core developer of PyMC3. His [blog](https://twiecki.io/) has some posts that are quite accessible and can be worth your time.


This was contributed by:  
l.neugebauer@uke.de  
on 12. December 2019  
edited on 10. July 2020

-----------
