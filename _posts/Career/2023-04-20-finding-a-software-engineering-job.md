---
title: "Finding a Software Engineering Job"
categories:
  - Career
---

So you’ve graduated with a bachelor of computer science, you scored decently
well, but you don’t have any personal projects to show cast your skills at a
job interview. How do you get a job then?

Well, the fact is that employers want to see that you have the skills to 
do the job and that you’ll fit in with the company culture. Let’s address 
these 2 points one by one.

# 1) Job skills

Unfortunately, colleges and universities don’t do nearly as good a job at 
training you for the industry. However, they do teach you the theory that 
many would struggle to muster up the strength to study on their own. Anyone 
can read documentation and build a simple static website because it’s quite 
easy to rapidly test whether your basic html, css, and javascript code works 
or not. After enough iterations, you’ll have a functioning static website.

But to understand why your code takes a long time to render, how to 
optimise its performance, why you should use certain data structures 
techniques over others, that requires learning how computer really work on a 
fundamental level and that kind of content is not particularly easy to read
because it’s so complicated.

So fret not, your degree is not useless and if you understood your course 
content, you will use them again in your workplace.

So, what kind of projects should you build? That depends on what kind of 
entry level software engineering job you want.

There are a couple of broad categories:
- Web development
- iOS development
- Android development
- Lower level i.e., windows system, mac system
- hardware programming

The vast majority of new jobs are in web development just because of how 
profitable it is to work with the internet. I'll focus on web development for
now and expand on the other categories in the future.

## Web development

Web development can be broadly broken down into:
- Frontend
- Backend
- devOps

### Frontend

Frontend consists of building the client side of the web app i.e., what 
the user sees. They implement what the UX/UI designer designed for the feature.

### Backend

Backend consists of storing and processing data as well as all the other 
security features needed in a web app. Payment systems also fall under the backend.

The link between the frontend and backend lies with passing data back and 
forth and persisting changes due to a user’s input.

A full stack developer is someone who deals with the frontend, backend, 
and devOps. The reason why they’re called full stack is because the 
programming tools that a frontend and backend developer uses forms a stack 
(more explanation to come later).

So you’ll need to first pick an area where you’d like to work in. 
Afterwards, build a project in that area.

However, it’s not enough to just build a project (I’m sure you could land a 
job with a project but probably not the best job for you), you need to build
it using software tools like version control.

You should also learn the project cycle for building a feature. Equipped with
these two tools, you’ll be able to show cast the full extent of your software 
engineering skills and get that dream job.

#### Example 1: Using version control and the feature cycle to build a frontend project

Employers like to see candidates that can work autonomously and are driven to 
solve a problem. So, it's good to choose a frontend project that addresses a 
problem in your life so that you can passionately (and naturally) show why
you wanted to solve it during your job interview.

So let's say you wanted to solve the problem gathering some data from a market
segment for your parents' business. You could create a google form and link it
to a google sheet and call it a day. But you're a computer science graduate, you
can do a better job than that. Maybe there's something you want to customise in 
your survey that requires more functionality than what google forms can provide.

Well, in this case, you can turn to your trusty frontend tools - HTML, CSS, and JavaScript.
With the advert of React, Vue, and Angular, adding interactivity has never been 
easier. As such, it’s imperative to show that you know how to use one of 
these web frameworks. Create placeholders or just make up some stuff for 
content. What matters is how you build the web app and how you tackle each
problem. 

Documenting this process is very important because that’s what software 
engineers do on a daily basis so that their fellow developers can
understand how they solved the problem in the event that they need to build 
up from it.

With version control (git), you can break up your web app into discrete tasks.
For example, building the survey form could be one component. When the
user submits the form, the data should be stored in a database. So, you'll need
to set up a simple database to store it. Afterwards, perhaps you'll want to 
filter the results and display it on a chart - building this chart is another discrete task.

So in this case, we have 3 discrete tasks. Each task can be built in a separate
feature branch and merged into the master branch when it's ready. While you're
building the feature in the feature branch, you'll be making regular commits to
document your progress. This is important because it allows you to revert back
to a previous commit if you make a mistake. It also allows you and others to see how you
progressed through the feature.

Now let's say you have a few quality assurance testers (probably your parents since
they're your users). They'll be testing your web app and giving you feedback on 
your features. You can incorporate their feedback into separate fix branches where
you update those features you've built (and merged into the master branch).

This workflow of prototyping a feature, testing it, and fixing it based on user feedback
is known as the agile methodology. It's a very common workflow in the industry and
demonstrating that you know how to work with it as well as the fact that you 
used it for your personal project will definitely impress your interviewer.

# 2) Company culture
This is a tough one because it's very subjective. When it comes down to it, 
people want to work with someone they get along with. In Australia, this loosely
translates to "are you someone I can grab a beer with". 

I believe that when you're looking for a job, you're not the only one being 
interviewed - you should be interviewing the company as well. The last thing
you want is to be stuck at a place that you don't like and you can't really 
afford to be changing companies multiple times a year since it looks terrible
on your resume. Instead, figure out what's important to you in a company.

For most people that I've talked to, a good manager is one of the most important
factors. Ask about how the manager works with his/her team, how the manager
handles conflict, and how the manager handles giving and receiving feedback.

If you know that you generally get along with people who are more sporty, maybe 
look for a company that encourages that kind of culture. At the end of the day,
you'll be spending a lot of time with your colleagues and your social circle
will gradually shift to place them at the center - it's just a fact of life
since you spend majority of your week with them for extended periods of time i.e.,
the duration of your work contract.

# Getting a job in Australia from overseas

So if you've stuck around to this part, someone I know probably referred you to 
this blog. That's great! So I'll try my best to provide the most value to you.

## Steps
1. Create that project that you need for the job interview. You want leverage
in the job interview and that starts with having confidence in your ability
and having the evidence to back it up.
2. Networking. Finding a job is all about networking. I personally work in the
startup space so to get into it, you can join the earlyworks slack channel. There's a 
couple of other job boards that you can join as well.
3. There's a couple of people you can follow on LinkedIn as well to stay up
to date with the latest job openings. Go to the startmate page and follow their
staff. You can also follow a bunch of startup accelerator programs such as the 
Melbourne Accelerator Program, the startmate accelerator program, and Y Combinator (US based).
4. Craft a good introduction that accurately reflects yourself. You don't want
to pretend to be someone you're not because if you hired, you have to continue
exhibiting that persona which is not sustainable. In your introduction, share
that project that you're proud of!
5. Continue building other projects to stack up your portfolio while you continue
networking. Let your friends and family know you're looking for a job and share
about your projects (when they ask of course, don't brag - no one likes a bragger).

That's pretty much it!
