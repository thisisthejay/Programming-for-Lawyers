# Programming for Lawyers

An introduction to programming for lawyers!  

_N.B. This programme is open to everyone but has been designed with an emphasis on helping lawyers at Thrings LLP learn how to code._

![Banner](/images/pfllogo.png)

## Welcome

Hello and welcome to the programme.  This repository will evolve as we progress and is intended to be shaped to our collective needs.  I hope to collaborate with lawyers who are either experienced programmers and those who are ready to explore new ways or working and, importantly, new ways of *thinking*.

I wrote an article about why I think lawyers have the ability (at least in theory) to be good programmers.  You can read it [here](https://medium.com/datadriveninvestor/why-lawyers-should-make-great-developers-155f73304d0).  I have since met and connected with lots of lawyers who code, coders who practice law, lawyers who (like me) have started LegalTech companies and everyone in between!  

At a high level, I hope to explore the following disciplines with you which are *shaping the future* of legal work:

- automation
- artificial intelligence
- smart contracts


The objective of this programme is not to become a software developer.  There are better resources for that if you are so inclined which I will mention below.  Rather it is to spark your enthusiasm for programming and ultimately, empower you to become a **_more effective lawyer_**.

So, let's begin. 

#### A little bit about me

I'm Jay, a lawyer and coder.  I'm not particularly keen on titles but I gravitate towards what some people describe as a "legal techologist".  I read Economics at university and started my career in law as a paralegal shortly after graduation.  I've since qualified and practice as a Private Client lawyer.  I began my coding journey a few years ago and it has been extremly rewarding and fulfilling. I now work in the Private Client and Blockchain teams at Thrings. For the latter, being able to read and interperet smart contracts will be invaluable (more on that in later chapters). But this isn't just about my journey - it's about yours!

I'd love it if you connected with me on Twitter - my handle is [@mrjaypeasmith](https://twitter.com/mrjaypeasmith) - and on [LinkedIn](https://www.linkedin.com/in/jermainepaulsmith/) if you have a profile.

### Equipment you will find helpful

In order to access the resources shared in this programme, I recommend that you have:

- a computer
- a smartphone
- a fast internet connection
- headphones
- a notebook

### Setup recommendations

The initial part of the programme won't require any installation of software.  But you may want to work at your own (perhaps faster) pace so I have set out some options below.

*N.B. You can come back to these recommendations later and get started with [Chapter 1](#chapter-1) after creating your GitHub account and only if you are ready to dive in.*

#### Create a GitHub Account

You should setup a [GitHub](https://github.com/) account.  GitHub is platform where code is stored and shared for projects big and small - just like this one.  Having an account will be useful as you can use it as a gateway to a large number of programming resources.  By having a GitHub account you won't have to have uniqiue login credentials for other websites you use where GitHub authentication is supported.

You'll discover as we progress that GitHub is referred to in a lot of resrouces and it is important to become comfortable with it and the underlying *version control* protocol itself called Git.

#### Install a code editor

You can write code in simple text editors but your experience will be enhanced if you use a code editor.  There are some such as [repl.it](https://repl.it) and [codepen](https://codepen.io) which are browser based where you don't have to download anything to your computer to write code.  These are really useful tools particularly for small examples, sharing code or where you are working on a work laptop and cannot install applications yourself. We will explore browser based code editors where needed.

You may find that eventually you reach the contraints of browser based code editors and want to install something locally. _I recommend that you install_ [VS Code](https://code.visualstudio.com/download) - it is a superb free code editor and has a lot of tools and plugins to boost your productivity.

#### Preparing for success

Most people are very capabe of learning new complex subjects.  What stops the majority of people from achieving meaningful results is not their learning aptitude but their ability to manage their time and motivation.

If, like me, you have a number of other commitments (such as work, family life and maintaing your health) it can be overwhelming to begin a new challenge - particularly one which is self-led.  

Here are my top 3 tips:

**(1) Code little and often**

It is better to code for 5 hours over 5 days than to spend all day on a weekend bingeing.  Developing a regular *habit* will serve you well and make learning more manageable.  

I recommend that you read or listen to [Atomic Habits](https://jamesclear.com/atomic-habits) by James Clear.

Setting aside a regular time in your day or throughout the week will help you and manage the expecations of other people around you.  My most productive learning phase was when I used my lunchbreaks for around a year to complete freeCodeCamp's JavaScript exercises.

**(2) Determine "why" you want to learn to code**

Focus on *why* you want to learn to code.  Don't just do it because you think it's cool or because you don't want to focus on another important goal.  

My own "why" was that I was extremely frustrated at:

- being unable to build my ideas without paying someone to help me
- not leveraging resources I had access to at work
- not maximising my productivity

Once you understand *your* "why" you will give it the priorty it deserves (or move on to something else more important).

**(3) Be accountable**

If you are able to, I recommend that you pair-up with a friend or colleague to learn with.  Learning with someone provides a point of reference for sharing ideas, challenges and some external pressure to keep you motivated.

There are two further concepts which helped me become accountable.  These are:

- taking the [**#100DaysOfCode**](https://www.100daysofcode.com) challenge (coding for 1 hour a day every day and tweeting your progress)
- learning in public [**#learninpublic**](https://www.swyx.io/writing/learn-in-public/) (publicly sharing the knowledge you acquire as you learn)


## <a id="chapter-1"></a> Chapter 1: An introduction to Python

*This Chapter should take around 7-10 hours to complete.*

If we are going to learn how to code, we must pick a programming language!  Python is an excellent choice for, particulalry for lawyers. Python is an appealing choice for a number of reasons, for example it:

- has a shallow learning curve
- is versatile
- is popular for automating tasks
- has large number of libraries
- can be used for AI and data science

### Learning the fundamentals

It is important to start with the fundamentals when learning any programming language, particulalry if you've never written code before. 

**Required**: Take this [free online Python course](https://scrimba.com/course/gpython) on [Scrimba](https://scrimba.com).  Scrimba is a hybrid video tutorial / code editor.  It's important to get used to typing code and Scrimba allows you to do this while you follow along. 

**Recommended**: You should read this [Python Handbook](https://www.freecodecamp.org/news/the-python-guide-for-beginners/) on [freeCodeCamp](https://www.freecodecamp.org) alongside the above course. 

**Bonus**: If you want more video resources then I recommend this [Python Crash Course](https://youtu.be/JJmcL1N2KQs) by Brad Traversy.

*N.B. I will be learning along with you as I only recently began exploring Python.  We are in this together!*

## Chapter 2: Your first (small) project

The best way to learn how to code is to build applications.  Having explored the fundamentals of Python, you are now ready for your first small project.

### Getting data from an API

The first project is to use your IP address to confirm when the International Space Station will pass over your (or your servers!) location.

_Hint:_ I created a [repl](https://repl.it/@mrjaypeasmith/Python-API-demo) to show you the code.

**Watch** [this video](https://www.youtube.com/watch?v=eBnnOwjcHw4&t=13s) first and then try re-creating your own.  You can create the same application or, for extra credit, find an API on [this list](https://github.com/public-apis/public-apis) to create something with.


## Chapter 3: Automating tasks at work

.....coming soon