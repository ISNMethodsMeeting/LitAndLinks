# Learning mathematics

## tl;dr:

[Precalculus](https://www.edx.org/course/college-algebra-and-problem-solving)
[Linear Algebra](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/)
[Single Variable Calculus](https://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/)
[Multivariable Calculus](https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/)
[Probability Theory](https://projects.iq.harvard.edu/stat110/home)

Maybe you've encountered a few papers that were full of integrals and you had no idea what to do with them. Or you're conducting an analysis that you don't really understand but would like to. Or maybe you just feel as someone who works with data and mathematical models for a living, you should have at least some basic skills in mathematics. Or maybe you just feel like it could be fun. Here's the approach I used to get into math, maybe it can be useful for you. Luckily it has never been easier because we live in a world where we can get Ivy League education for free. What a time to be alive!

## Why would I do that?

Arguably, this deep a journey isn't strictly needed for a quantitative scientist. And that's true. If you feel like this, don't do it. But there's a few arguments to be made for why you might want to dig deeper than needed, especially if you're just starting your PhD or still have some time left before graduating:

  * It helps to have a network of knowledge. Even if you don't strictly need to know all of this, it helps tremendously if you want to understand other stuff more superficially. Assume you want to learn about something like LASSO regression or you're using an optimizer and don't understand why local minima are a problem. If you have a mathematical background, it's easy, if not it feels like black magic.
  * More proficient in statistics. The difference between remembering assumptions of a test from a textbook and deriving them from understanding is night and day. Even for a t-test, there's quite a bit to understand and to actually get the central limit theorem you need some probability theory. More scientists being proficient in math means less people prone to avoidable mistakes. This improves the quality of research.
  * Opens new possibilities: Some analysis strategies only come to mind if they're on your radar. New things are less intimidating if you're comfortable with their foundation. Maybe you'd like to start using Bayesian methods, or an ANN would be a great approach for your data, but you don't feel comfortable using either of them. If you stategically invest some time early on into learning some math, this doesn't have to be the case.
  * Marketable skills: Academia is making it really easy to not want to stay in it forever. For many of us, the working with data aspect is the most marketable skill we bring. Being better at math is one factor (though certainly not the only one) that determines you data analysis skills. All else being equal, you can make more money if you know more math.

## Mathematical disciplines you might want to get familiar with

For anything statistics/machine learning/data science/AI there are three main mathematical subfields that you need.

  * Probability theory
  * Multi- and Single Variable Calculus
  * Linear Algebra

Unfortunately, they kind of rely on each other and on more basic stuff like basic algebra and trigonometry. This can be confusing in the beginning because you don't know where to start. I'm sure there's shortcuts to that, but if you actually want to invest some time over a longer perior (like 2 years), here's how you could do that. At least that's what I'm still in the process of doing.

## Possible Route from "I'm afraid of the sum sign" to "I eat partial derivatives for breakfast"

  1. *Precalculus* Get the basics down. This means, you have to be comfortable with logarithms, solving equations for variables, functions, polynomials and so on. In the anglo-saxon education systems this is typically summarized as precalculus or college algebra. There's tons of courses on edx and coursera. [This](https://www.edx.org/course/college-algebra-and-problem-solving) is the one I did. I didn't love it but it was okay and it certainly made the following steps smoother. There's no point in rushing. If you don't get basic algebra, you're completely lost in Calculus. Spend some time here or you'll regret it later on.

  (There's no really good argument for why you should start Linear Algebra or Calculus first. Most colleges teach Calculus first, Linear Algebra is nicer. I started with Linear Algebra and haven't regretted it. But steps 2, 3 and 4 are somewhat interchangeable)

  2. *Linear Algebra* You're working with matrices and vectors all the time (e.g. in regression or with correlation matrices). Linear Algebra teaches you how that actually works. It also gives you great intuition for why correlated regressors are a problem and you'll understand better what MATLAB error messages mean (wtf is a positive semidefinite matrix). Gilbert Strang's [lecture](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/) series and [book](https://www.amazon.de/Gilbert-Strang/dp/0980232775/ref=sr_1_1?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=linear+algebra+strang&qid=1594375680&sr=8-1) are a fantastic ressource. There's probably other good resources out there, but you're definitely not missing out if you chose this one here.

  3. *Single Variable Calulus* If y is a function of x, how does y change if x changes? Calculus is used more, the more complex your analysis is. If you using optimizers like gradient descent, that's calculus. If you want to understand even simple neural networks and backpropagation, you need the chain rule, which is calculus. If you want to ascend from being someone who uses statistics to someone who kinda understands statistics, then you need calculus. There's just no way around it. MIT OpenCourseWare has a [course](https://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/) for you and it's very good. It took me a lecture or two to get used to Prof. David Jerison after having been taught by Gilbert Strang for half a year. But he's a really, really good teacher. Unfortunately, the search for a good book isn't quite as easy as with Linear Algebra. There's two approaches (early/late transcendental) and not all books take the same. I used [this](https://www.amazon.de/Thomas-Calculus-Units-Joel-Hass/dp/1292253223/ref=sr_1_1?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=thomas+calculus&qid=1594376154&sr=8-1) one and it was okay. You will probably have to find a mapping between whatever book you use and the lecture, but it's possible. Good news: Most books cover single AND multivariable calculus. If you have a good suggestion for an alternative book, feel free to add it.

  4. *Multivariable Calculus* Pretty much the same as single variable calculus, but with multiple variables. I.e. multiple integrals, partial derivatives, gradients. Stuff like that. If you understood single variable calculus, it's not hard conceptually. Just A LOT of tedious calculations. At least you'll get a lot better at solving equations and writing mathematical stuff that makes you look smart. Again, MIT has got you covered with Denis Auroux's [course](https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/). Prof. Auroux is a master at using a blackboard for education and overall this is really great and enjoyable course. You can use the same book you used for single variable calculus. Overall, calculus isn't that hard conceptually, but it is very heavy on equations and computations.

  5. *Probability Theory* The most crucial discipline if your main goal is getting better at statistics. Don't think that means you can skip the former. You might get away with skipping LinAlg, but you're lost in probability if you don't know calculus. For probability we'll leave MIT and chose to visit Harvard instead. Because we can. Joe Blitzstein is kinda famous for his lecture and book, it even has a [website](https://projects.iq.harvard.edu/stat110/home). You can read the book online for free, you can watch the lectures on youtube, you find solutions to exercises from the book on the website. If you're like me, you'll still buy the book, because it's nicer to read and it looks good in your shelf. Probability is a bit like the opposite of Calculus as in it's fairly simple mathematically (equation-wise) but very hard conceptually. So if you're doing it after Calculus you might feel a little thick but it just takes some time to get used to this new way of thinking. Take your time, do enough exercises until you think you can proceed and you got this.


## General recommendations:

The most consistent thing is consistency. And probably the best predictor for consistency is accountability. You can get this if you find another person that is as serious about it as you and do it together. Watch a lecture, read the corresponding part in the book and meet for exercises. Skype works well for that. I would advise against larger groups, these tend to slow down. Someone always has an appointment and so on. 
Also, understand that this is a long time process. If you're doing one lecture a week, the above will take you more than 2 years. But it's most certainly not something that you will regret having done afterwards.
