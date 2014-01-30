---
layout: post
title: Epiphanies during Evolutionary Computing lectures
---

<p>
  The very subject of optimization and the various methods in it is intriguing and enough to keep one absorbed for days. Evolutionary computing is my elective this semester and I am impressed. I have only barely started but I'm already hooked like a junkie on weed.
</p>
<!--more-->
<p>
If you have absolutely no idea what evolutionary computing is about, allow me to blow your mind. You see, Lawrence J. Fogel, a genius whose very first advent in research was a gift to the world, namely evolutionary computation. If you haven't guessed, the field of evolutionary computing deals with using the biological principles of evolution and Darwin's rules of selection to solve mathematical problems.</p>

<p>Take your time.</p>

<p>
  So you see the elegance of this principle lies in the fact it has to work because evolution works. It is a tribute to the natural system around us, a bow to the intricate mathematical rules that so tacitly governs all of us. Why try hard to develop new abstract math systems when nature has already done the work for us?
</p>

<p>
  I was sitting in class, waiting for the next mind-blowing thing to happen and of course, it did. Schema theorem, which is a foundation and basic mathematical principle of evolutionary computing, was being taught and it was quite interesting. What was more interesting was how the analogy went both ways - nature to math, math to nature.
</p>

<p>
  This is what the Schema Theorem says:
</p>

<p>
  <blockquote>
    <b><i>Short, low-order schemata with above-average fitness increase exponentially in successive generations.</i></b>
  </blockquote>
</p>

<p>Let's take this word by word. Well, of course, the first question would be the very name <i>Schema</i>. What exactly is that?</p>

<p>Evolutionary algorithms work on binary strings (improvements have made it possible to use decimal numbers too) and the schemata are the patterns of the initial population. The initial population is the group of strings that are randomly generated to start the algorithm. This would be a typical initial population of 5-bit length:

<blockquote>
  <b>
    10010<br>
    00101<br>
    01011<br>
    00011<br>
    01010<br>
  </b>
</blockquote>
<p>
The algorithm proceeds to perform various operations on these binary strings. As a result of these operations, the strings change bit-by-bit or drastically. The guiding feature of these changes is the function to be minimized, which is checked with each string in this population.
</p>

<p>
Schemata are the patterns that are present in the population. These are the wild card notations that can signify a group of strings that have similar features. In this case, the feature we care about is the objective value of the function.</p>

<p> So the aim of the evolutionary computation is, in fact, to remove the schemata that do not give us a "better" objective value and keep the ones that give us the "desired" objective value. Some possible schemata of the above population would be:</p>
<blockquote>
  <b>
1\*\*10<br>
1001\*<br>
0\*101<br>
</b>
</blockquote>
<p> The above is just a few of the total list of schemata, which would be pretty long. The point of the schema is to describe part or even one of the population using the wild cards as above.</p>
<p>
The theorem states that schemata of the following characteristic survives a long time during the algorithm run:</p>
<b>
<ul>
  <li>short = meaning the defining length of schema is low</li>
  <li>low order = less number of defined elements, more wild cards</li>
  <li>above-average fitness = having desirable objective value</li>
</ul>
</b>
<p> Why am I ranting about this? Because this relates to us, on a societal level, as a population of human beings.</p>

<p> The analogy I would draw is that people communities are schemata. They describe something about the members. Certain quantities. Though I have no proof of it, only intuitions, I say the schema theorem works for people communities too with the following analogous terms:</p>
<blockquote>
<b>
<ul>
  <li>short = the defined bits or characteristics should be close by and practical to abide by or follow.</li>
  <li>low order = less number of restrictions. More wild cards or variety in members allowed.</li>
  <li>above average fitness = successful in terms of economy and lifestyle in personal life.</li>
</b>
</blockquote>
<p> Sparta was a community that put extreme emphasis on the military training of an individual and such training began at birth. The citizens were debarred from trading and manufacturing by law. Evidence points out that unfit children were killed.</p>
<p> Schematically, they were high order and above average fitness. After a certain point, the Spartans were outnumbered by the helot population in the region. Spartans, by definition, had to be by blood descent.</p>
<p>Of course, I'm just pointing out a few examples in history. This is a random thought that occurred to me during the lecture.</p>
<p>Now that I've written it out, I'm gonna forget all about it and go back to research.</p>


