# Land your first job as a developer

Here is some advice and a few tips to kickstart your dev career.

## Keep. On. Coding. 👩‍💻

This is the most important advice. Code a few hours _every single day_. Practise, practise, practise, that's how you'll get better and fight the [Imposter Syndrome](https://www.codingdojo.com/blog/programmer-imposter-syndrome/). In the words of one of our teachers: _this stuff leaves your brain quicker than it goes in_! In this section, we will give you a few tips to keep on coding.

## Rework on Kitt ✍️

Whether you realise it or not, **your brain is now working on understanding code pretty much all the time**, even when you’re not actively at your laptop typing away in Sublime. So keep this gymnastic on and keep coding every day. Go back to Kitt and do exercises that you found difficult during the bootcamp. Do the optional ones you didn't get to. Be sure you understood all lessons. Don't spend more than a week doing that, because where you learn the best is when you **work on real project**.

Here are some exercises that you should understand perfectly!

- **Louchebem**: Programming basics (variables, conditions, iterators, methods).
- **Orange Tree**: Use the object-oriented programming paradigm to define your own classes with data and behavior.
- **Cookbook**: Use the MVC pattern to build a more complex application while keeping your codebase clean and scalable.
- **Rails Mister Cocktail**: Re-use everything listed above in the rails framework.

You can also have a look at some **livecodes**. Keep in mind that having some knowledge when it comes to testing your code is a **strong advantage for any technical test**.

Right now, your `fullstack-challenges` repository is full of your solutions from the bootcamp. To start again from scratch with a clean slate, here is what you can do:

```bash
cd ~/code/<your_gh_nickname>
git clone git@github.com:lewagon/fullstack-challenges.git fullstack-challenges-reboot
cd fullstack-challenges-reboot
rm -rf .git # Let's start a new history
git init
hub create -p # The -p means `private`, it's *VERY* important not to leak challenges. Thanks!
git add .
git commit -m "Rebooting all challenges"
git push origin master
```

You now have a pristine folder containing starter kits for exercises that you can re-do. `rake` is all red again. Having a separate folder allows you to keep your Bootcamp code while re-doing exercises. Be aware that this new repo is _not_ connected to Kitt in the sense that it won't update your exercise completion / style on the platform (it does not `rake` anymore after the bootcamp). But the local `rake` you run in your terminal works!

## Practice on other platforms 💪

### Codewars

Sharpening your algorithm skills and general knowledge of programming can be done with new exercises on the [**Codewars**](https://www.codewars.com) platform. There are many exercises you can tackle, each with its own "rake" (a set of tests to check if your code is correct). Select Ruby exercises of difficulty between [8 and 6 kyu](https://www.codewars.com/kata/search/ruby?q=&r[]=-8&r[]=-7&r[]=-6&beta=false) and start diving into them! You can put `Le Wagon` in your [profile](https://www.codewars.com/users/edit) if you want a list of allies, and congrats [Nic](https://kitt.lewagon.com/alumni/atmosfeer) for leading the way!

### Leet Code

With  [Leet Code](https://leetcode.com/) level up your coding skills and quickly land a job. This is the best place to expand your knowledge and get prepared for your next interview.

### JavaScript 30

Wes Bos created a 30 day challenge, available for free, that you should have a look at if you want to upskill your Vanilla JavaScript. It's called [JavaScript 30](https://javascript30.com/) and gives you 30 exercises to do with videos and starter code. No frameworks, no libraries involved, just pure JavaScript (ES6). If you like [Wes](https://twitter.com/wesbos)' videos, he has other courses too that are worth checking out.

### Project Euler

Another well known platform to practise mathematical/computer programming problems is [**Project Euler**](https://projecteuler.net/). Just register to access the challenges. The approach is different here; you'll find the problem description and an `<input />` to give your answer. Project Euler only checks your answer, so you have to use your own tools (Sublime Text, Ruby, or Google Search!) to find this answer. Once you've found it, you have access to a forum thread with people revealing how they found the solution. You learn so much reading that, you get exposed to many different languages (Python, Java, PHP, even Assembly!). The first ten problems are within your reach as a Le Wagon alumni. After that, the difficulty curve is really steep, so good luck!

### Upcase

The great agency [Thoughtbot](https://thoughtbot.com/) made their [Upcase](https://thoughtbot.com/upcase/) program free in 2018. Here are a few tracks we recommend you follow to dive deeper in the topics cover during the bootcamp:

- [Fundamentals of TDD](https://thoughtbot.com/upcase/fundamentals-of-tdd)
- [Ruby Challenges](https://thoughtbot.com/upcase/ruby-challenges)
- [Design for Developers](https://thoughtbot.com/upcase/design-for-developers)
- [Intermediate Ruby on Rails](https://thoughtbot.com/upcase/intermediate-ruby-on-rails-five)
- [Refactoring](https://thoughtbot.com/upcase/refactoring)
- [Advanced ActiveRecord Querying](https://thoughtbot.com/upcase/advanced-activerecord-querying)
- [Mastering the Shell](https://thoughtbot.com/upcase/mastering-the-shell)
- [Mastering fit](https://thoughtbot.com/upcase/mastering-git)

### Edabit

Edabit is another platform like Codewars with many challenges. It's very easy to Sign Up and start coding.

Go to [edabit.com/challenges](https://edabit.com/challenges) and select:

- The language (Ruby, JavaScript - or maybe you want to learn some Python or PHP?)
- The level (Start at Easy or Medium)

Click on the first challenge, read the instructions and head over to the `Code` tab.

### Exercism

A forth recommended platform is [Exercism.io](https://exercism.io). Log-in with your GitHub profile and install the CLI (i.e. _Command Line Interface_) following their [CLI Walkthrough](https://exercism.io/cli-walkthrough). Once you have done that, you can join a track in _Mentored mode_:

- [Ruby](https://exercism.io/tracks/ruby)
- [JavaScript](https://exercism.io/my/tracks/javascript)
- [SQL](https://exercism.io/my/tracks/plsql)
- [Bash](https://exercism.io/my/tracks/bash)

For every track, you'll be able to download exercises with the `exercism download` command, solve them locally on your computer with Sublime / the Terminal, then submit your solution (like `git push` for Kitt!) with the `exercism submit` command.

We advise you to configure your `exercism` CLI this way to fit with the Le Wagon's `~/code/<your_gh_nickname>` convention:

```bash
mkdir ~/code/<your_gh_nickname>/exercism
exercism configure -w ~/code/<your_gh_nickname>/exercism
```

This way, everytine you `exercism download`, exercises will go into that folder. You will have a neat structure like this:

```bash
pwd
# ~/code/<your_gh_nickname>/exercism
tree .
# .
# ├── javascript
# │   └── hello-world
# │       ├── README.md
# │       ├── hello-world.js
# │       ├── hello-world.spec.js
# │       └── package.json
# └── ruby
#     └── two-fer
#         ├── README.md
#         └── two_fer_test.rb
#
# 4 directories, 6 files
```

You can also have a look at a similar platform 👉[Ruby Tapas](https://www.rubytapas.com/).


## Work on a project

Doing coding kata is all well and good, but it will reinforce only a small section of the skills needed to be a Web Developer. Companies hire full-stack developers because they [get things done](https://www.joelonsoftware.com/2006/10/25/the-guerrilla-guide-to-interviewing-version-30/). They hire developers who can understand a business requirement and turn it into working software. That's it.

Companies looking for developers are going to **ask you to prove** that you can actually do that. The best way is to show some actual product, in production. It means that you have a few static websites hosted on GitHub Pages, and a few Rails apps running on Heroku.

What should you work on?

- Continue to develop one of your Rails projects from Le Wagon
- Start a new project with fresh ideas. Keep it simple and limit the scope so you can ship fast and often
- Don't go solo. Find buddies in your batch to keep working in a small group and stay motivated. Meet in cafés, coworking spaces, etc.
- Practice by building one of the following from scratch:
  - A task manager
  - A reddit/hacker news clone
  - A restaurant reservation tool

## Build a portfolio

Having a portfolio can make the difference and allows you to stand out. A majority of developers don't have a public presence with a portfolio and/or a blog. A prospect employer **will always** Google you, so you should own your brand name with your portfolio. Bonus point if you buy a domain and [set it up on GitHub Pages](https://help.github.com/articles/using-a-custom-domain-with-github-pages/). We recommend GitHub Pages as a porfolio should be a static website (you can use [Middleman](https://middlemanapp.com/) or [Jekyll](https://jekyllrb.com/) if you want a blogging section). Plus it's free, [even with SSL](https://blog.github.com/2018-05-01-github-pages-custom-domains-https/).

Here examples of nice **Alumni portfolios** :

- [Romain Capelle](http://romaincapelle.com/) - Web developer, Web designer freelance
- [Basile Quinchon](https://www.basilequinchon.com/) - Web developer
- [Sami Bekas](https://samibekas.github.io/profile/) - Serial Entrepreneur
- [Bruno de la Mattia](https://www.dellamattia.com/) - Freelancer Front-end developer / Web Designer
- [Karine Bialobroda](http://www.blbrd.com/)- Co-founder Agence Poulpe
- [Konstantin Bifert](http://www.kissu.io/)- Freelance Fullstack developer
- [Shunjiro Miyaki](https://www.shunmiyaki.com/)- Front-end Developer & Digital Designer
- [Martin Provost](https://www.martin-provost.me/) - Traffic Manager

Get more about the importance of a portfolio with this article:

👉 [Diploma is dead... Long live Portfolio by Mathieu Le Roux](https://medium.com/le-wagon/diploma-is-dead-long-live-portfolio-44a6d306553) (you can clap 👏 if you like it!)


## Explore Software Engineering 🕵

[What should Software Systems Engineers be prepared to do?](http://www.landwehr.org/2017-01-08-landwehr-et-al.pdf)

### Keywords to learn about

- Software Architecture 🏛
- Testing ✅
- Maintaining a software 👷
- Versioning software
- Communicate precisely among developers (documentation, issues...)
- Communicate precisely between developers and stakeholders
- Security
...

You can also have a look at this [roadmap of topics to master to become a versatile developper](https://github.com/kamranahmedse/developer-roadmap) or this [Computer Science Study Plan](https://github.com/jwasham/coding-interview-university/).

## Go to Meetups / Events 🏃‍

As a developer, and especially as junior developer, it is very helpful to go to **technical meetups**. It's a good way to **meet senior developers** and [**be mentored**](https://blog.pragmaticengineer.com/developers-mentoring-other-developers/), **code kata** with developers from others training, **learn new tools**, and it also could help to **find a job**.

Here is a database of [meetups](../data/meetups.csv) in all major cities. We must have missed some, please contribute with a Pull Request!
You can also check Le Wagon meetup [here](https://www.meetup.com/fr-FR/find/?allMeetups=false&keywords=le+wagon&radius=Infinity&userFreeform=Paris%2C+France&mcId=z1011740&mcName=Paris%2C+FR&sort=recommended)

## Sell yourself

A 9-week bootcamp seems short for any recruiters. How could someone learn so much in a such a small amount of time? Why do people go to 5-year engineering school? Well, that's something you will need to pitch to some recruiters. The idea is that the knowledge you acquired at Le Wagon is **directly** applicable in a work-related situation. You know how to build a web application backed by a database, with a good UX and design. You know how to push this to production. You know how to work as a team with a git & GitHub workflow. You even touched on some testing (even though there is a lot to work on!). That's **a lot**!

Plus, coding is not your only skill. You don't necessarly come from a [STEM](https://en.wikipedia.org/wiki/Science,_technology,_engineering,_and_mathematics) background, which means that you acquired other skills compared to the typical programmer / fresh computer science graduate. Don't hide this and don't be ashamed by your very short programming career! On the contrary, use this to your advantage. You may already have the following skills that will prove vital in a developer position:

- Great communication skills
- Working in a team
- Managing a project
- UX/UI Design (Empathy with end users)
- etc.

Show recruiters that you are a [**product-minded** developer](https://blog.pragmaticengineer.com/the-product-minded-engineer/)!

Good recruiters will find someone who can do the job _now_ with the right set of skills. Great recruiters will look for someone who has shown an ability to [**grow**](https://www.ted.com/talks/carol_dweck_the_power_of_believing_that_you_can_improve). Graduating from a bootcamp is proof!

And if you need more convincing that a company should hire juniors (so that you can convince them during an interview!), read [this article](https://medium.com/@bellmar/heroes-and-juniors-increasing-engineering-team-velocity-97ce6a59103e).

## Nailing the technical interview 🤖

### Before you start

**Your first role doesn't need to be perfect**. Just choose a company where you can **become more competent**. By this, we mean that it's a good idea to join a **solid team** with **experienced developers**. Working with people who are better than you is the best, and fastest way to improve. Getting that experience will make you even more attractive in the future. If you want to become a **great programmer**, quickly, don't take a job as a single, lone developer working with an entrepreneur as your first job.

The best way to practice interviews is **to go to** interviews. Just keep applying for jobs, and keep interviewing. You can be proactive in advance and practice with other alumni. The first interviews will be tough, but you'll quickly notice question patterns and interviewer types.

**Read these posts carefully** that were written by [Thomas Deschamps](https://kitt.lewagon.com/alumni/tdeschamps) (Batch #2 - Paris) and [Charlie Jeppsson](https://kitt.lewagon.com/alumni/charliejeppsson) (Batch #75 - Barcelona):

- [The bootcamper cheat sheet](https://medium.com/le-wagon/the-bootcamper-cheat-sheet-d9439dbaa59)
- [How I got my first developer job and why it’s the best thing I’ve ever done](https://medium.freecodecamp.org/how-i-landed-a-full-stack-developer-job-without-a-tech-degree-or-work-experience-6add97be2051)

You should also read [this article](https://medium.com/@mylesborins/the-coding-interview-an-approach-to-minimize-anxiety-and-improve-chances-of-success-e5a8603bfea5).

### Practice with our tech challenges

Becoming a good developer requires to continue coding and learning. You need to be prepared to succeed in your technical interviews. In these [**tech challenges**](https://github.com/lewagon/career-challenges), you will be introduced to core technical notions. These notions are not easy to understand but you need to know them when you will be interviewed.

- Check out the [**Interview Cheatsheet**](https://github.com/yangshun/tech-interview-handbook/blob/master/preparing/cheatsheet.md) and [**some tips**](https://www.interviewcake.com/coding-interview-tips)
- [**Hacker Rank**](https://www.hackerrank.com/) to practise coding, prepare for interviews and get hired!
- [**Interview Cake**](https://www.interviewcake.com/) is a list of tests you can do. Practice as much as possible. Practice with friends and pair up. Then try on your own. Use your resources and then submit.
- Read the [**Cracking the Coding Interview**](https://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/0984782850/) book by Gayle Laakmann McDowell
- Check out some [**Youtube videos from CS Dojo**](https://www.youtube.com/channel/UCxX9wt5FWQUAAz4UrysqK9A/search?query=interview) about the coding interview.
- Read the [Interview Study Guide for Software Engineers](https://dev.to/seattledataguy/the-interview-study-guide-for-software-engineers-764).

### Get Ready with Practice interviewing

[Practice interviewing](https://interviewing.io/) with engineers from Google, Facebook, and more... anonymously
Get better at algorithmic and systems design problems, find a job, or just see if you’ve still got it.

## Typical interview process

### First Round: Pre-interview coding exercises

It's usually a **code screening**. The good news is that it's easier than face to face. They send you coding exercises, usually without time limits. Try and allocate more time than you think you'll need though, just so you don't panic.

👉We've listed some [**pre-interview dev challenges**](../data/tech_interviews.csv) from various tech companies.

### Second Round: Face to face interviews / live coding tests / culture fit

It s a really good sign that a company is getting you to do this, they're taking it seriously and says good things about them. We are going to be honest though - coding with someone looking over your shoulder while you try and solve a problem is **terrifying** 😱. It's normal to panic and go blank! If you want to, read the challenge out loud, to the interviewer. It starts to become clear and you will never ever be penalised for doing this. Talk through your thinking to the interviewer.
The absolute worst thing you can do is sit there and not say anything. They want to see the way you think and behave as a potential future employee, especially when you are under pressure. They're not looking for the right answer, more for **a logical and intelligent thought process.**
Coding is about communication more than anything. Communicate around code and around a problem. The interviewer is not your enemy, they want you to do a good job, and if you're completely stuck, just ask.

Here are some **classic questions** you can be asked:

- Define a function that flattens an array of nested arrays
- Invite a list of customers of a company present within a 100km radius from their Dublin headquarters (you have a text file containing JSON user objects as a user base)
- Define a function that returns the factorial of a given number
- Define a function that outputs the numbers that appear an odd number of time in an array
- What is the difference between ‘include’ and ‘prepend’ in Ruby
- What does it mean to curry a Proc in Ruby
- Define a function that returns the intersection of two arrays without using the Ruby & operator. And then return same numbers if they appears more than one time like `[1, 1, 4, 7] intersection with [1, 1, 7, 8, 9] must return [1, 1, 7]` (and not [1, 7] like the & operator).


### After the Interview

Here is a bit of advice for after the interview:

- Email them straight away saying thanks and loved it
- Email a week later
- and if you don't hear again (after a few weeks), send a third email politely requesting an update

One of the most common mistakes people make is to do one interview at a time, wait for an answer and move on. **Keep applying for jobs** at the same time as your current interview! Don't wait for one answer or pin all your hopes on one job before moving on. You'll waste so much time, and will suffer more if you get any rejections. It can also even put you in a dream position if you are offered two jobs at the same time - you can use the other company offers as leverage to negotiate salary. On the subject of salary though, remember that it isn't as important as being in a good team. Go somewhere where you are going to learn and be tested.

Finally, don't take rejection personally. Just because they said no this time, doesn't mean they will never want you. So stay in touch and most importantly, **always be nice**. You never know when your paths might cross again in the future.

## Look for a company 🧐

Check out all the great [job boards](../data/job_boards.csv) and [ruby companies](../data/ruby_companies.csv). You should be looking for an environment where you can be **mentored** by [senior developers](https://neilkakkar.com/things-I-learnt-from-a-senior-dev.html). Don't be afraid of all those bullet points / requirements in job descriptions and years of experience announced, [apply anyway](https://talent.works/2018/11/27/the-science-of-the-job-search-part-vii-you-only-need-50-of-job-requirements/)!

You can use [**Huntr**](https://huntr.co/) to manage your job applications and interviews.

## Stay Tuned 📝

### Alumni stories

Here are some **inspiring stories and articles** from Le Wagon's **alumni** :

- [How learning to code has changed my life](https://medium.com/le-wagon/how-learning-to-code-has-changed-my-life-my-story-two-years-on-d15d6c90b9b2) by **Arthur Littmann** (Lead Teacher / Developer at Le Wagon London)
- [How to progress after Le Wagon](https://github.com/damienlethiec/after-le-wagon) by **Damien Le Thiec** (Freelance Web developer)
- [Recently turned Ruby developer time to grab some books](https://medium.com/@NicolasFilzi/recently-turned-ruby-developer-time-to-grab-some-books-mate-bc216da1c128) by **Nicolas Filzi** (Freelance web developer + Teacher at Le Wagon Nantes)
- [Better English for web developers](https://medium.com/le-wagon/better-english-for-web-developers-f40c76775e2)  & [Becoming a programmer? What a funny idea! Or is it?](https://medium.com/le-wagon/becoming-a-programmer-what-a-funny-idea-or-is-it-b6a5a1ed8473) by **Marina Starkova** (Alumni / Engineering Manager at JobTeaser)
- [A piece of advice to new developers](http://joyouscoding.com/blog/2015/07/06/advices-to-young-developers.html) by **Martin Van Aken** (Teacher at Le Wagon Brussels)
- [Own your story](https://remimercier.com/) by **Remy Mercier** (Alumni and dev @Hosman)

Find more [here](https://www.lewagon.com/blog/all?category=alumni)

### Other stories

- [Things I learnt the hard way - in 30 years of Software Development](https://blog.juliobiason.me/thoughts/things-i-learnt-the-hard-way/)

### Ruby On Rails News

Here are some interesting newsletters & resources about ruby and Rails:

- [Ruby Weekly](https://rubyweekly.com/)
- [This week in rails](https://rails-weekly.ongoodbits.com/)
- [Best Ruby & Ruby on Rails Resources](https://www.leighhalliday.com/best-ruby-and-ruby-on-rails-resources#.Wqpfrs0IXDs.twitter)
- [Rails conf](https://www.youtube.com/results?search_query=railsconf)

### Other Languages

Here are some interesting newsletters & resources about other important web technologies:

- [Postgreweekly](https://postgresweekly.com/)
- [JavascriptWeekly ](https://javascriptweekly.com/)
- [Better dev links](https://betterdev.link/)
- [dev.to](https://dev.to/)

### General Tech News

- [Hacker News](https://news.ycombinator.com/)
- [Product Hunt](https://www.producthunt.com/)
- [Techcrunch](https://techcrunch.com/)
- [The Next Web](https://thenextweb.com/)
- [Recode](https://www.recode.net/)
- [Better Dev Link](https://betterdev.link/)
- [Dev.to](https://dev.to/)

### Tech Blogs

- [Uber](https://eng.uber.com/)
- [Netflix](https://medium.com/netflix-techblog)
- [Airbnb](https://medium.com/airbnb-engineering)
- [Drivy](https://drivy.engineering/)
- [Lifen](https://medium.com/lifen-engineering)
- [Algolia](https://blog.algolia.com/)
- [Doctolib](https://doctolib.us14.list-manage.com/subscribe?u=6f3cf1e1e4554097575191f5d&id=a22645bb6c)

In French:

- [Human Coders](https://news.humancoders.com/)
- [Developpez.com](https://www.developpez.com/)

### Books

- [Ruby On Rails Tutorial - Michael Hartl](https://www.learnenough.com/ruby-on-rails-6th-edition#landing-pricing?gclid=EAIaIQobChMIt77a6ICQ6AIVieh3Ch2VbA_REAAYASAAEgJMovD_BwE)
- [Metaprogramming Ruby 2 - Pablo Perrotta](https://pragprog.com/book/ppmetr2/metaprogramming-ruby-2)
- [Rebuilding Rails - Noah Gibbs](https://rebuilding-rails.com/)
- [99 Bottles of OOP](https://www.sandimetz.com/99bottles)
- [Cracking the coding interview](https://www.amazon.fr/Cracking-Coding-Interview-6th-Programming/dp/0984782850/ref=sr_1_1)
- [Elements of programming interviews](https://www.amazon.fr/dp/1479274836/?coliid=I2FY3FOREJXI1I&colid=2BJFDNQ7Q3MCN&psc=1&ref_=lv_ov_lig_dp_it)
- [The imposter's handbook](https://bigmachine.io/products/the-imposters-handbook/)
- [Computer Science distilled](https://www.amazon.fr/Computer-Science-Distilled-Computational-Problems-ebook/dp/B0731JG96F/)
- [The Pragmatic Programmer](https://www.amazon.fr/dp/B003GCTQAE/)
- [POODR](https://www.poodr.com/)
- [Code, the hidden language](https://www.amazon.fr/dp/B00JDMPOK2/)
- [Clean Code](https://www.amazon.fr/dp/B001GSTOAM/)
- [The Healthy Programmer](https://www.amazon.com/Healthy-Programmer-Better-Pragmatic-Programmers/dp/1937785319)
- [Grokking Algorithms](https://www.amazon.fr/dp/1617292230/?coliid=I7DMCAWCGMXVG&colid=1T782NAQM0ATA&psc=0&ref_=lv_ov_lig_dp_it)
- [Inside the machine](https://www.amazon.fr/dp/B004OEJO0A/?coliid=I2PEUELF07FNNR&colid=2BJFDNQ7Q3MCN&psc=0&ref_=lv_ov_lig_dp_it)

### Videos

- [How to: Work at Google](https://www.youtube.com/watch?v=XKu_SEDAykw&feature=youtu.be)

## FAQ

### Should I dive into other technologies (Node, Go, Python, Elixir etc)?

It definitely helps to learn what they are used for, the general strengths/weaknesses of these technologies, why they were invented etc, but don’t rush into learning how to build with them and stick with Rails for a few months. **It’s far better to deeply understand your first technology before branching out into competing stacks**. A good rule of thumb is to learn one new language/technology every year.

EXCEPTION ⚠️

**Python** is a language very close to ruby!:

- They’re cross-platform, which is convenient for distributed teams where people might use macOS, Windows or Linux on their computers.
- Ruby and Python are high-level scripting languages; their programs don’t need to be compiled.
- Both languages are dynamically typed, meaning that you can use a variable without declaring it first.
- They are object-oriented (OOP) and [garbage collected](https://en.wikipedia.org/wiki/Garbage_collection_(computer_science))

So **do not hesitate to apply for offers in Python**.

You can train before with those 2 tracks:

- [Intro to Python for data science](https://www.datacamp.com/courses/intro-to-python-for-data-science)
- [Dataquest](https://www.dataquest.io/path/data-engineer/)

The only difference is that **Django** follows the Python principle "Explicit is Better than Implicit" (law n°2 of https://en.wikipedia.org/wiki/Zen_of_Python), and **Rails** follows its ["Convention over Configuration" doctrine](https://rubyonrails.org/doctrine/#convention-over-configuration).

After you've secured your first job, then our advice will be to [learn more programming languages](https://thorstenball.com/blog/2019/04/09/learn-more-programming-languages/).

### What salary can I claim after Le Wagon for a job as a junior web developer?

The salary for junior developers just after bootcamp ranges **between €30k and €40k** in Paris. We recommend you to ask for 36k but be aware that this might be significantly different in other cities! London for example is a little bit lower.

[Glassdoor Salaries](https://www.glassdoor.co.uk/Salaries/index.htm) offers some insights into each market. Stack Overflow also offers a [Salary Calculator](https://stackoverflow.com/jobs/salary).
