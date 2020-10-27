---
title: "Tips and Help"
markup: "mmark"
---
### Logistics
1. [How can I succeed in this class?](#success)
2. [How I should ask for TAs to help me debug the code?](#debug)
3. [Are we having class everyday? Is attendance required?](#attendance)
4. [Tips to work with your group](#group)
5. [How do I submit my pdf homework on Gradescope](https://www.youtube.com/watch?v=u-pK4GzpId0)

### R related 
1. [How to Install R on Windows, Mac OS X, and Ubuntu?](https://www.datacamp.com/community/tutorials/installing-R-windows-mac-ubuntu)
2. [Rmarkdown can't knit](#rmarkdown)
3. [I can't find the knit button anywhere](#knit)
4. How do I knit my Rmarkdown file to html and convert that into a pdf file? ([Windows tutorial video](https://mtholyoke.zoom.us/rec/share/TDRIo8MQpMgDK5Dk6iVlP6S2j31M04y5LJAY96kSClbUt0gSE4TipnCzP8SiolGX.ZKCVQwJck5q7XIKA?startTime=1603757314000), [Mac tutorial video](https://mtholyoke.zoom.us/rec/share/TDRIo8MQpMgDK5Dk6iVlP6S2j31M04y5LJAY96kSClbUt0gSE4TipnCzP8SiolGX.ZKCVQwJck5q7XIKA?startTime=1603757120000))


### Imposter syndrome
1. [Why some of my classmates just got the concept/did the programming assignment so fast? Am I not good enough?](#imposter)

<hr>


### Logistics
##### <a name="success"></a>Q: How can I succeed in this class?
[Adapted from Albert Kim]

Ask yourself:

When I have questions or don’t understand something:
* Am I asking questions in class?
* Am I asking questions on Piazza? Even better: Am I answering my peers’ questions on Piazza
* Have I been coming to TA/instructor's office hours?”

Lectures, labs, and readings:
* Am I staying on top of Piazza posts sent between lectures? If you need help developing a notification strategy that best suits your lifestyle, please speak to me.
* Am I attending lectures consistently?
* During in-class activities, am I actually running code line-by-line and studying the outputs, or am I just going through the motions?
* During in-class exercises, am I taking full advantage that I’m in the same virtual space at the same time with the instructor, and most importantly my peers, or am I browsing the web/texting the whole time?
* Have I been doing the associated readings for each lecture?

In general:
* Coming to class on time and be ready to learn. Make this a habit, and it will become easier. 
* Take an active role in your group discussion. There are in general four roles in each group:
    * Scriber: taking notes on Googlesheet or Piazza to keep track of your group's process, 
    * Manager: leading the discussion and making sure the group is completing the activity on time.
    * Spokesperson: communicating the results to others, e.g., speaking in class, pinning the instructor for help, etc. 
    * Editor: edit the notes/posts by the scriber
*  Helping your fellow students on Piazza. The best way to learn is to teach!

<hr>

##### <a name="debug"></a>Q: How I should ask for TAs to help me debug the code

Please note that the teaching staff will not debug code longer than 2-3 lines via Piazza. Learning to debug is a critical skill for statistician and data scientists doing quantitative analysis, and remote requests for help with code usually end up with the teaching staff giving you the answer rather than you learning how to find the answer.

The best way to use office hours and ask TAs for coding questions would be:
* You should come to office hours having done your own legwork and ruled out basic logical errors. Identify the place where the error is suspected to come from by doing ablation studies. (Please see below for some common debugging tips.)
* During the office hours, you should articulate what your goals are and what you have observed with experiments, what you have tried/observed, what you think might be the problem, and what advice you need to move forward.
* The TAs will mostly help you by looking at and analyzing the outputs of your code instead of looking at the original code. Typical advice that the TAs might advise you would be to ask you to do more analytical or ablation studies about your code. 
* If absolutely needed, please be prepared to send us your Rmarkdown document and any dataset you used. 

<hr> 

##### <a name="group"></a>Q: Tips to work with group

Working with your group can be the best part of this course for some, and a complete nightmare for others. Here are some tips to help you improve your group dynamics and get the most out of your group work. 

* **Clear, open communication is key.** Successful interpersonal communication must exist in teams. Building trust is essential.  Deal with emotional issues that arise immediately and any interpersonal problems before moving on.  

    * Turn on your camera whenever it's possible. To be heard, be present first.
    * If someone is quiet, reach out to them to see if they have any concerns about speaking up during the discussion. 
    * Be kind to each other. If someone didn't show up to a meeting you planned, send them an email to check on them and try to understand why. Work on bringing people together. 

* **Shared responsibility/leadership** The best group work usually come from shared leadership. When everyone feels a sense of belonging and a responsibility of their work, the group achieves more.

    * Identify during early stage each person's role in the group. Common tasks include:
    * Initiating discussions
    * Clarifying points
    * Summarizing
    * Challenging assumptions/devil's advocate
    * Providing or researching information
    * Reaching a consensus
    * Make sure everyone has the opportunity to edit the work. For example, I learned this from one of the groups in this class. 
        * Each person is assigned with a few problems/tasks to complete
        * Each person update their progress on the Google doc
        * Everyone edits/comments on the google doc.
        * Group leader copy Google doc writeups to Rmarkdown and turn in the work.

* **Group maintenance**: Maintenance involves the harmony and emotional well-being of a group, including
    * sensing group feelings
    * harmonizing
    * encouraging
    * time-keeping
    * relieving tension
    * bringing people into discussion

<hr> 

### R related 
##### <a name="rmarkdown"></a>Q: I have troubles knitting Rmarkdown

There could be many reasons for this. Usually, the error message will pinpoint the location of the problem. Read the error messages!!

Ben Baumer kept a nice webpage for common errors in knitting Rmarkdown. Check out [Document won't knit](https://smithcollege-sds.github.io/sds-www/rmarkdown_problems.html#Document_won’t_knit).

There are also quick ways to find help within Rstudio. Check out [Rmarkdown cheatsheet](https://rmarkdown.rstudio.com/lesson-15.html)

<hr> 

##### <a name="rmarkdown"></a>Q: I can't find the knit button anywhere
This means that RStudio doesn’t understand your document is supposed to be an RMarkdown document, often because your file extension is .txt. To fix this, go to the Files tab (lower right corner, same pane as Plots and Help) and select the checkbox next to your document’s name. Then select Rename and remove the .txt and make sure the extension is .Rmd. (From Ben Baumer)

<hr> 

##### <a name="attendance"></a>Q: Are we having class everyday? What happens if I have to miss a class?

Yes, we are having class meetings everyday during the week, and I expect you to come to class and participate in full. However, there is no direct penalty for not attending class. If you have to miss a class, you do not need to get this excused, but you are responsible for learning the materials on your own in this case, and do not make a habit of this. I will post the recorded lecture each day within 48 hours. 

<hr> 

##### <a name="imposter"></a>Q: Why some of my classmates just got the concept/did the programming assignment so fast? Am I not good enough?

**No!** Let me say something about peer pressure and impostor syndrome (and this is adapted from Drew Hilton.)

First, your performance in this class is absolute, not relative.  We don't grade on a curve.  It doesn't hurt you for others in the class to do well.  There is a bunch of stuff you need to know, so go learn it.  Learn it well.  Learn it deeply. That takes time.  Focus on your own learning, not what other people are doing. 

Second, imposter syndrome is where you feel like it was a mistake that you got admitted/whatever.  You think you aren't good enough, and that eventually someone will figure out this mistake. LOTS of people think this, even [especially?] people who are really good, because they have a high standard. The other thing that makes this worse is the "myth of the effortless genius."   A lot of social constructs reward/reinforce the idea of looking effortlessly smart  ("oh you are so smart! You did that so easily!").   We don't say enough "you worked really hard at that, but finally got it---that's what is really important".   There are only two ways to be effortlessly smart:  (1) doing something that isn't hard enough to challenge you (you have learned the materials before) (2) faking it. 

Please remember:
- It is ok to take a lot of time to master a new concept and learn programming
- It is ok for stat140 to be hard
- If you have imposter syndrome, it doesn't actually mean you aren't good enough
- If you have imposter syndrome, you can come talk to me about it.
- We want you to work hard.  It isn't supposed to be easy (if these things were easy, then people wouldn't get paid a lot to do them in jobs!) 

<br> 
