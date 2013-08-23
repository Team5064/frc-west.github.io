---
title: Programming
layout: coursepage
---

Before starting this course, please install [python](http://wiki.python.org/moin/BeginnersGuide/Download). ([opening command line](http://pcsupport.about.com/od/commandlinereference/f/open-command-prompt.htm))

Programming is an immense topic that covers thousands of different topics. Computer science is the study of computation, and how best to do it.

So what exactly is programming, and why do we need to do it? Well, it comes down to doing something relatively simple: writing instructions that a computer can properly understand and execute.

Think of programming like writing a cake recipe. You need to specify how to do things. You can't just say "make a cake". You need to say what ingredients are needed, when and how to combine them, and how to prepare the final product.

Another way of thinking about programming is telling your sibling to go to the store to buy milk. There are specific ways of expressing what you want. If you were to just speak gibberish, or not speak at all, they would stare at you like you were crazy. The same goes for computers. Telling them to do things requires some specific ways of doing so. Without those very particular guidelines, there would be a *lot* more computer problems in the world. Thankfully, we've managed to create computers that execute things *exactly* as they are intended to. The only problems that we see with computers now are programming errors, and occasionally hardware failures.

There is something worth noting here though. Telling your sibling to go to buy milk is pretty simple. It's basically like this:

    find Sibling
    tell Sibling "Go buy some milk"
    give Sibling money (5$)

And that is a pretty verbose way of saying it. Unfortunately, things like AI and learning computers are still in their early stages. So we are stuck with some dumb processing that requires the programmer to tell it everything. Instructions for a computer to do the same thing (assuming this computer can walk and talk!) would look like this:

    define Sibling as "Sibling Name"
    walk on floor until Sibling is seen
    load talking device
    talk "Go buy some milk"
    wait for "Okay"
    load hand with $5 from internal money
    move hand to Sibiling
    wait for hand to be empty

So things would be more complicated. And this is assuming you already have all the code for talking, moving and listening.

The difference is **context**. Humans have a lot of other memories that are ready on demand to be used to benefit them in the moment. Computers, however, don't. They rely on the programming to tell them exactly what to do, without any default or context-related behaviour.

Is this necessarily a bad thing? No. As a matter of fact, it is exactly what makes computers useful to us. They are capable of doing instructions much quicker than any human could ever do, to a very high precision. A key example of this is math. Computers work in a way that uses math to do absolutely everything. So an added benefit of doing processing like that is that we have very fast calculations. Much quicker than any human.

As opposed to the first example, a computer would only require instructions like this:

    print 1320.232 / 27372 * (5 + 12.329 / 5) - 13.2

While a human would undoubtedly take much more time and space:

    x = 12.329 / 5
    x = x + 5
    x1 = 1320.232 / 27372
    x = x * x1
    x = x - 13.2

And most people would quickly admit that even these instructions would require a lot of time to do. A computer can do this kind of operation in times less than a millisecond.

# Instructions
So assume we need to get from the top left square to the top right square.
![](/img/grid.png)

A computer would require something like this:

    move right 10 squares
    
Note that it requires a direction, a length and a unit of measurement. You could not say (without some kind of additional code) something like this:

    move to top right square

This instruction means nothing to the computer. It doesn't know how to get there, or where the top right square is.

# Dynamic Flow
Early on in the development of computers, we realised that we need something more than a linear control flow. In other words, we need to be able to react to different situations.

As a result, there is something called dynamic flow. This means that you can put something like this in a program:

    if user is male, print "Hello sir"
    else if user is female, print "Hello mam"

It can also mean that a programmer can write a *loop*. Loops are instructions that are run multiple times, depending on some kind of condition.

    while user is asleep, ring alarm
    turn off alarm

This is useful for all kinds of things, as you will see later on. Almost 80% of program execution is actually in loops. Many loops in modern day computers do things like this:

    while no button has been clicked, display page
    display page that button refers to
    
You can see that both of these "while" loops take for granted that the condition they were waiting on it now false. In the first one, the programmer knows that the user is awake now, by virtue of the fact that the loop is over. The second example also knows that a button has been clicked because "no button has been clicked" is now false.

With these simple but powerful tools, we can write complex and useful applications.
