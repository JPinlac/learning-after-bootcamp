# The Road to Junior Developer
### My chronicles of eventually getting hired as junior web developer. :grin:

I'm the type of person who spends way too much time finding the most time efficient way to comprehensively learn something. I even obsess over what to learn in the first place and endlessly question that decision after the fact. I hate wasting my time. This usually ends up horribly backfiring and I end up wasting more time researching options than actually learning. Even after all this, there will always be some nonoptimal decisions and hindsight is still not quite 20/20. So I'm hoping some of you can use this guide to save some time on deciding what to do and actually do things.   
__TL;DR: Hopefully, you can use my successes and mistakes to help guide your journey as a developer.__

*The format of the upcoming learning sections will be peculiar. It will be a living document with me explaining what I'm using to learn and highlighting some cool things I came across. So a lot of this information will be fragmented and not in chronological order. You can track my progress in chronological order in the [log here](#log).*

## Table of contents

- [Chronicles](#chronicles)
  1. [My Programming Background](#my-programming-background)
  2. [Why become a developer?](#why-become-a-developer-and-how)
  3. [Bootcamp](#bootcamp)
  4. [Learning after bootcamp](#learning-after-bootcamp)
    - [HTML and CSS](##html-and-css)
    - [Javascript](#javascript)
    - [MEAN stack](#mean-stack)
    - [Design](#design)
  5. [Projects](#projects)
    - [Portfolio Site](#portfolio-site)
    - [bella beauty co. site](#bella-beauty-co-site)
    - [Us20somethings Blog](#us20somethings-blog)
- [Extras](#extras)
  - [Courses](#courses)
  - [Book List](#book-list)
  - [Learning and Productivity Tricks](#learning-and-productivity-tricks)
  - [Tools and Technologies](#tools-and-technologies)	
    - [Technologies](#technologies)
    - [Dev Environment](#dev-environment)
    - [Dev Ops](#dev-ops)
  - [Log](#log)
- [License](#license)

<br><br>

## Chronicles

#### My Programming Background

I ended up writing a mini biography for this section, but who want to read all that? So here's a quick synopsis.
I've learned bits and pieces of programming throughout my life. Mostly more algorithm based programming like intro computer science courses. There's a little bit of C++ here, a little bit of Python there. Some Matlab in calculus and linear algebra courses, some Excel simulations. Never anything that amounted to a full blown application, just small tasks here and there. 

In my current job I get to write SQL queries for a few different databases, I also write some involved Excel macros for reporting. Excel is scary. It's like the duck tape of the business world. It can solve almost any problem, but that doesn't mean it should be used and the things I've done with it would make you shudder.

During the last year I started getting more serious about my future. I'm looking to build a skillset that will allow me to support my family with the enough flexibility to personally help raise my future children. I came up with a couple options, become an entrepreneur or become a developer?The interesting thing about those two options are that they aren't mutually exclusive. I could become both, but becoming an entrepreneur take capital. I don't have enough capital to start a business nor any skills that would make starting a business to become any cheaper. Well there goes that idea, which leaves me with becoming a developer.

#### Why become a developer and how?

In all honesty I would much rather be a developer than an entrepreneur. I'm actually pretty decent at programming, and I enjoy it. The thrill of getting lost in code and finally solving that program is one the best feelings in the world. Also, being able to create something is a skill that will never be useless. This great and all, but let's look at the numbers.

According to the [Bureau of Labor Statistics](http://www.bls.gov/ooh/computer-and-information-technology/software-developers.htm), the median pay of software developers is $98,000 for 2014 with an expected growth of 17% from 2014 to 2024 with is much faster than average. Those numbers looks exceptionally good to me. Good enough that I'm constantly kicking myself in the ass because I didn't start seriously programming sooner.

This site, unfortunately also mentions that software developers commonly hold bachelor degrees. Bachelor degrees are outrageously expensive. Heck I'm already 50k deep in student debt. but before you get discouraged, let's check out this wonderful [developer survey on stackoverflow] (http://stackoverflow.com/research/developer-survey-2015). The most interesting statistic here is that 41.8% of developers are self-taught. This is pretty crazy, you can have a real big boy job without having to spend tens of thousands on a college education. Some other important tidbits, 29% of developers work remotely at least part-time. In fact full-time remote workers in the United States make 13% more than the average developer. This sounds perfect for raising some mini-me's in the future. 

So you want to become a developer now, but how do we go about that? There's a few approaches available online that are free and extremely comprehensive. One that I recommend is [Free Code Camp](http://www.freecodecamp.com/). It's a program that has up to 900 hours of course work and allows for working with a non-profit to test your skills and create an actual website. Something similar is [The Odin Project](http://www.theodinproject.com/). The difference being is the tech stack they both use, or more simply the programming languages they use. Free code camp uses the MEAN stack which is all Javascript based and the odin project uses Ruby on Rails. In regards to front-end development they're both still similar, the only difference is the backend systems you'll be using. You will still need to know html, css, and javascript for both. I went with the MEAN stack, [here](https://github.com/blog/2047-language-trends-on-github) and [here](http://www.indeed.com/jobtrends?q=%22ruby%22%2C+%22javascript%22&l=) you can see Javascript is gaining on popularity over Ruby and other languages.

Other possible routes are simply just making things and relying on google and stackoverflow to teach you the solutions. I suffer from too much blank page syndrome and discipline to make this approach succeed. I personally went with joining a bootcamp. I find learning from a teacher who can teach me best practices and tools of the trades to be valuable. Another thing to note, is the networking oppurtunies a bootcamp has within their area. 

#### BootCamp

I got lucky in finding a bootcamp. I wanted to join a front-end specific camp using the MEAN stack. I wasn't willing to relocate to another state for a few months, which would require me quitting my job. I'm also specifically looking for a job here in Detroit. Luckily there was a relatively new bootcamp in Detroit that just began offering a front-end bootcamp, and even better a part-time offering! 

#### Learning After Bootcamp

There seems to be a recurring theme with coding. __The more you learn the less you think you know.__ This was never more apparent than after the bootcamp. We learned about all the technologies we could use to make a decent web application, but working 40 hours a week and cramming all that info in about 10 weeks didn't allow for in-depth learning. There's a lot nuances and depth in all the code that we have to familiarize ourselves with. __So, it's back to the basics.__ 

I'll also be doing daily programming challenges to keep my coding skills sharp. On the 28th I started the first day of [Advent of Code](http://www.adventofcode.com), you can follow my progress on my [log](#log) and [github](https://github.com/JPinlac/daily-programming-challenges).

##### HTML and CSS

HTML and CSS, the basic building blocks of a website. You can make a very nice fully functioning website with just these tools. They've also come a very long way with the introduction of HTML5 and CSS3. There's cool things like more sematic markup and positioning with flexboxes. There's also a lot of things you should be aware of, such as web accessibility  and making sure your page is properly formatted for SEO (search engine optimization). 

I currently have a copy of [*HTML and CSS: Design and Build Websites by John Duckett*] (#HTML and CSS: Design and Build Websites by John Duckett) that I bought in the beginning of the bootcamp. His books are wonderfully illustrated and perfect for beginners. This book is a pretty quick read, I spent a night going through it earlier and went through about 1/5th of the book. 

I'll also be going through the MOOC (massive open online course) [HTML5 Part 1: HTML5 Coding Essentials and Best Practices](https://www.edx.org/course/html5-part-1-html5-coding-essentials-w3cx-html5-1x).

<br>

##### Javascript

<br><br><br>

#### Projects

##### Portfolio Site
###### In progress http://jonathan.pinlac.net
I currently do have a personal site that's basically a glorified resume site. I made it before the bootcamp (September 2015) as part of the pre-work. I used the Freelancer bootstrap template and filled in the blanks. Simple stuff.

After the bootcamp I now have projects that I can showcase in a portfolio. So let's upgrade my site. I plan on rebuilding the site entirely from scratch using responsive design techniques and best practices. I hope to keep it a mostly static site, with projects popping up in modal. I might add a little html5 interactive game or something in there too.

<br>

##### bella beauty co site
###### In progress
Two year ago I worked with my cousin in a small brick and mortar beauty supply in Detroit. I tasked myself with setting him up with a website. I used my VPS to host the site. This was not a fun experience. I dived into to it using the trusty old LAMP stack and something I was familiar with, the Adobe creative suite. I had no idea how web development worked at this time, and using Dreamweaver did not help me one bit. I copied a template and a created a really crappy site that was constantly "Under Construction."

This site will be a simple brochure site where I get to really test my design skills. I plan on using foundation as a CSS framework on this one. 

<br>

##### Us20somethings Blog
###### Next Project
I'm mostly excited for when I can start working on this project. This will be a full fledged content managements system designed by myself. I'll be using Postgres as a database. My reason's for this decision is [here.](#postgres)

<br><br><br>

## Extras

### Courses

I plan on roughly following the guide that is here [Open Source Society](https://github.com/open-source-society/computer-science) and supplementing with other materials than I think will be useful.

[HTML5 Part 1: HTML5 Coding Essentials and Best Practices](https://www.edx.org/course/html5-part-1-html5-coding-essentials-w3cx-html5-1x)  
Excellent course on web accessibility and html5 features by WC3. I completed a couple weeks of this before things were getting too intense during the bootcamp. Unfortunately, this course isn't active, but all the information is available in the archive.

[Harvard CS50x: Introduction to Computer Science](https://www.edx.org/course/introduction-computer-science-harvardx-cs50x#!)  
This course is self-paced and looks to offer a good overview on programming concepts. Enrollment starts on Jan 1st, 2016 if active engagement is your thing, so this is a good time to start.

[MIT 6.0.0.1x: Introduction to Computer Science and Programming Using Python](https://www.edx.org/course/introduction-computer-science-mitx-6-00-1x-6#!)  
This course starts January 13th, 2016. I also took this course last year and while I did earn a certificate, I did the bare minimum. Bootcamp was getting time consuming at the time and I wasn't able to delve into the harder concepts. I'm pretty excited about taking this course again. It's very algorithm heavy and covers basic computer science concepts like loops all the way to recursion, data structures, Big-O complexity, and testing. I took EECS 280 at the University of Michigan and I'm pretty impressed on how much material and more is covered in this MITx course.

<br><br>

### Book List

[*HTML and CSS: Design and Build Websites by John Duckett*] (http://www.amazon.com/HTML-CSS-Design-Build-Websites/dp/1118008189)  
Wonderfully illustrated book that's perfect for beginners. It's a quick read.

[*Eloquent Javascript*](http://eloquentjavascript.net/)  
The best resource on learning javascript. It's less opinionated and more up to date than Crockford's *Javascript: The Good Parts.* It's online, it's free, what's not to like. Can't wait to get into it.

<br><br>

### Learning and Productivity Tricks

The most important tip I can give you is very simple. It's also the one thing I struggle with the most. *Just build something!* Don't sweat all the details and just create something.  

[Learning How to Learn: Powerful mental tools to help you master tough subjects](https://www.coursera.org/learn/learning-how-to-learn/)  
Have you ever had to spend an all nighter cramming information in your head trying to get ready for a midterm? Fun stuff right? The best part is afterwards you retain like 0% of the information, so you get to relearn everything again for your cumulative final! This course will help combat this. It lets you know how your brain works, so you can effectively learn and commit information to memory and avoid procrastination. Some of the techniques are time-consuming, but might as well get it right the first time rather than having to relearn it. It's a short course as well and they have them going on all the time.

This page itself is partly inspired by some of the concepts they go over. Keeping this log requires me to write down in my own words what I've learned. This helps commit things to long-term memory and makes it easier to review material.

**Bonus ** [Why Procrastinators Procratinate](http://waitbutwhy.com/2013/10/why-procrastinators-procrastinate.html)  
Let me preface with how amazing this blog is. I really recommend the articles on the Fermi Paradox, A.I., and his four part article on Elon Musk. Life changing stuff.

<br><br>

## Tools and Technologies

I'll be using this section to go over which tools and technologies I decided to learn and use. You can spend ages deciding on what text-editor or what database to use, so hopefully having my decision process here will help you save some time. 

### Technologies

<br>

### Dev Environment

**Operating System**  
My environment is odd. At work I use Windows 8. My laptop has Windows 10 and Linux Mint 17.2 on it. Throughout the bootcamp I strictly used linux. I decided to force myself to learn linux since that's what most web servers will be running, so might as well get familiar with it.

**Text Editor**  
I'm currently using sublime and it's pretty easy to get going with it. It's extremely customizable and is cross platform on all operating systems. This made working at work and at home pretty simple.

I plan on switching full time to vim. [Vim sounds magical] (http://www.norfolkwinters.com/vim-creep/). I currently know some basics and it helped me immensely when configuring my server and editing files in there. Which is a huge plus since all you have when working with a remote server is a command line interface and vim reigns supreme in this realm. Vim can also extend to the browser with some plugins. I'm using the Vimium extension for Chrome and I rarely have to use my mouse anymore which helped alleviate some symptoms of carpal tunnel syndrome.

<br>

### Dev ops

My server currently hosts all my sites and projects, including the bootcamp final project. The server is a dual core 256mb virtual private server from buyvm.net for $3.95 a month running ubuntu 14.04. It's completely unmanaged, although the provider doesn't hesitate to help when time permits. Unmanaged means you have to configure security like SSH yourself and all hosting.

For hosting, all my sites are handled by nginx which is great for my static sites. Nginx also acts as a reverse proxy to Cheers, which uses pm2 to daemonize the Cheers node module.

<br><br><br>

### Log


### License  
Creative Commons Attribution License (do whatever, just attribute me) http://creativecommons.org/licenses/by/2.0/
