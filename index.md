---
layout: default
---

I am a PhD student in the Department of Econometrics and Business Statistics at
Monash University. Despite the department's name, my research is largely
unrelated to "business and economics." I focus instead on fundamental aspects
of statistical methodology. Before transferring to Monash in late 2024, I was
studying at the University of Melbourne in the School of Mathematics and
Statistics.

During my PhD, I’ve had the privilege of working with several amazing academics.
My primary supervisor is [Susan Wei](https://www.suswei.com/), and I am also
supervised/mentored by [Liam Hodgkinson](https://www.liamhodgkinson.com/),
[Weichang Yu](https://sites.google.com/view/weichangyu/about), and [David
Frazier](https://dtfrazier.netlify.app/).

My interests are broad but center around Bayesian statistics. I explore
algorithms for fitting Bayesian models, understanding neural networks through a
Bayesian lens, and studying how misspecified Bayesian models affect downstream
tasks.

I am a statistician by training, having completed my undergraduate and MPhil
studies at the University of Western Australia under the supervision of [Berwin
Turlach](https://staffhome.ecm.uwa.edu.au/~00043886/) and [Kevin
Murray](https://research-repository.uwa.edu.au/en/persons/kevin-murray). Before
starting my PhD, I worked as a statistician and data scientist at the Department
of Primary Industries and Regional Development in Western Australia—a role I
still maintain part-time.


## Research Interests

### Singular Learning Theory (SLT)
SLT combines Bayesian statistics and algebraic geometry to study the properties
of singular models, such as neural networks and mixture models. For an
introduction, see [this
article](https://www.lesswrong.com/posts/xRWsfGfvDAjRWXcnG/dslt-0-distilling-singular-learning-theory)
and [this
resource](https://sites.google.com/view/sumiowatanabe/home/singular-learning-theory).
Since I lack the mathematical background to contribute to SLT's theoretical
development, my focus is on integrating its tools into modern deep learning
workflows. This is especially challenging with modern networks operating in the
interpolating regime ($$p > n$$), as most key results in SLT are based on large
$$n$$ asymptotic ($$n \gg p$$).


### Generalized Bayes
Model and prior misspecification can significantly impact the downstream
performance of Bayesian models. My research explores tools like loss-based
inference (here’s a great
[blog](http://www.lorenzopacchiardi.me/blog/2021/generalizedBayes/)), empirical
likelihood (Owen, 1988), and strange things such as the [cold posterior
effect](https://arxiv.org/abs/2002.02405). Recently, I have also taken an
interested in model- and prior-free approaches for constructing predictive
densities (e.g., [TabPFN](https://arxiv.org/abs/2112.10510)) and posteriors
(e.g., the [martingale posterior](https://arxiv.org/abs/2103.15671)).


### Computing Bayesian Posteriors
I am continually searching for tools to reliably compute or approximate
posteriors, especially for distributions that are multimodal, high-dimensional,
or have awkward posterior supports (e.g., Bayesian empirical likelihood). I have
experience with Langevin-based Markov Chain Monte Carlo methods, variational
Bayes approaches, and expectation-propagation techniques.




## Education

- **PhD in Statistics** (2024–)  
  Monash University  
  *Transferred from the University of Melbourne, 2022–2024, with Susan*  

- **MPhil in Statistics** (2017–2019)  
  The University of Western Australia  
  *Dean’s List for top 5% thesis*  

- **BSc (Honours) in Engineering & Mathematics** (2013–2017)  
  The University of Western Australia  


## Contacts  

Feel free to reach out! My email address starts with **kenyon.ng** — just add **dpird.wa.gov.au** for DPIRD matters or **monash.edu** for research.  

You can also find me on [GitHub](https://github.com/weiyaw) and [LinkedIn](https://www.linkedin.com/in/kenyon-ng).  


## Miscellaneous  

- My surname, "Ng," is pronounced *ung* without the vowel sound. It is the
  Hokkien (a Chinese dialect) pronunciation of **黄**, which means *yellow* in
  English.
- A simple webpage is [good](https://motherfuckingwebsite.com). (This is my
  perfect excuse not to spend time designing it — I have already wasted enough
  tweaking my Emacs configs..)
- Here’s a [photo](./profile.png) of me at 21.
- I developed [a tool to predict cereal flowering dates](https://fp.dpird.app/)
  as part of my role at DPIRD.
  
*Last updated: 21 Jan 2025*




<script type="text/javascript" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js"> </script>
