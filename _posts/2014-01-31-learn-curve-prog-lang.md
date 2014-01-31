---
layout: post
title: The learning curve for a programming language
---
<p>
I've always prided myself in being fluid when it comes to programming languages. I've had friends tell me I should have been studying computer science instead of mechanical engineering (considering that they wanted programming favours from me, their words are probably not very reliable).
</p>

<p>
But I'll admit this. I'm a hack. I'm quick, sure, but I only get the essentials and hack away to make it work. Whatever it is.</p>
<!--more-->
<p>
I have found that engineering students usually shun away from programming unless it becomes absolutely necessary. I have seen course drops just because they involve assignments to be done in MATLAB or C or something similar.</p>

<p>
Learning a programming language is easy <i>if</i> you are comfortable with algorithms and math. A programming language is simply a tool that makes your idea readily computable by a suitable computer.</p>

<p> 
It is evident then, that the programming part is simply a final step to check our idea and play around with it. Of course, if your research itself is on algorithms, then it is a different thing entirely. I'm talking about researchers working on a core branch and need their ideas validated quickly. </p>

<p> 
Once the algorithm or mathematical model is ready and has passed the manual check, involving convergence checks and boundary cases and what not, you are now ready to take it to the big platform. </p>

<p>
I'm going on and on about how easy it is but I can sense your wariness. I'm not a big talker. Okay, a little bit. Mostly, I am as good as my talk. If I had to convince you, I'll say that, I've used MATLAB, Python and C++ for a variety of research purposes. I'm a mechanical engineer and I haven't had classes in any of these languages. I'm simply trying to convince you that classes are not necessary to hack your way <i>efficiently</i> through a small part of your research project. </p>

<p>
Go on. Look through <a href="http://www.mathworks.in/matlabcentral/fileexchange/authors/319814">my MathWorks page</a> before you come back to this post. </p>

<p> Alright, now that you are convinced (if you are), let's get back to learning languages. </p>

<p> 
Three things that are highly essential during the initial days of a new programming language:</p>

<b>
<ul>
<li> A working internet connection (low speed, high speed, anything works) </li>
<li> A familiar text editor </li>
<li> Lots and lots of coffee </li>
</ul>
</b>

<p>
The last one is not completely necessary but it definitely doesn't hurt. </p>

<p> 
First things first, install the necessary compiler in your computer. All major languages are compatible with all kinds of OSes. Make sure to check this and find any alternative languages if you find any troubles of compatibility. </p>

<p>
I recommend working completely on the command line and for this reason, I find Linux a very pleasing platform for all programming (read amateur hacking) pursuits. The reason a command line is better is that it gives you complete control and sight over what's happening. A GUI obscures most of the things and you end up becoming dependent on it. It's always better to have the ability to work with whatever bare minimum you have.</p>

<p>
Create a Dropbox folder, initialize a git, whatever makes you feel safe about your work. </p>

<p>
Now, start writing a "hello world" program. Search through the internet, find a basic tutorial, skim over the details about variable types, file extensions and get to the core. They're all blah, blah, same old, same old. </p>

<p>
The basic tutorials usually deal with printing out data to the stdout and storing variables. They also cover the arithmetic calculations part, if that's possible. But what we really want in research is more advanced, more computationally heavy stuff. Once you get the basics of the language - the printing out, the storing stuff, the basic computation and function definitions - once this is done, quickly download the library/ module/ toolbox which concerns your main research work.</p>

<p>
Say it's DEAP for Python. It is an evolutionary computing library for Python and it is a free alternative to MATLAB. Now head on to the site, <a href="http://code.google.com/p/deap/">download DEAP</a>, install it. Make sure you have the dependencies installed - here, it is scipy, numpy, matplotlib, etc. </p>

<p> 
Start with the <a href="http://deap.gel.ulaval.ca/doc/default/index.html">documentation</a> for the specific library. Don't skim over the details about the variable types and basic stuff. I have found that this is a highly specific feature when it comes to custom libraries and you should read the documentation very carefully. At least the initial parts. It always happens that you may not need all the advanced features available in the module.</p>

<p>
Usually, the tutorials available in the project page of the required module gives you a model code to start with. Unless you are really desperate, don't download it. Start from scratch. Make sure you understand every line you write. It saves you a lot of debugging time later.</p>

<p> 
Let's be clear on one thing: you're not interested in the code at all, other than for the fact that it provides you results in research. So the stuff about the memory usage and speeding up is hardly necessary unless you are a really crappy coder. Mostly, libraries that are for computation - like FEM, CFD and convex optimization - they write documentations keeping in mind a average programmer from a stream unrelated to computer science. </p>

<p>
Make sure you understand the terms provided in the documentation. If you find it difficult to understand, you're probably not strong with the theory of the subject. Without the theoretical base, the programming part will be a failure. I cannot stress this enough. I once tried to use the CVXOPT library for Python without completely understanding convex optimization - a waste of two weeks.</p>

<p>
Once you are through with the documentation, start writing your own algorithm in the language. Don't worry too much about memory utilization in the beginning days. You'll eventually become efficient when the need arises. </p>

<p> Some other things you should almost always use, if you want to get the code writing process done quickly: </p>

<blockquote>
<ul>
<li> <b>A GUI debugger.</b> Command-line is great for the code writing and initial testing but a GUI debugger will show you all the variable values and you can figure out mistakes quickly. You'll also be able to step in, step out quicker than typing out the commands in GDB. But mostly you'll be able to see the variables change and catch mistakes quicker than in a command-line debugger.</li>
<li> <b>Emacs for the code writing.</b> This is more than a text editor. It is a way of life. It has a steep learning curve but once you have the hang of it, your productivity will go up by 50%. I promise. </li>
</ul>
</blockquote>

<p>
Well, that's pretty much it. I should probably put up a specific example. I'll keep that in mind when I start with a new language the next time. </p>

<p> 
Go on, then. Start hacking your way through a programming language and give a heart attack to the purists.</p>
