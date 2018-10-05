
# Introduiction to Object Orientation

## Introduction

In this section, you'll be'll introduced to the concept of Object Oriented Programming (OOP).

## Objectives

You will be able to
- Explain what Object-Oriented Programming is about
- Understand why it is important to know about OOP as a data scientist

## Object-Oriented Programming (OOP)

*An object-oriented approach to application development makes programs more intuitive to design, faster to develop, more amenable to modification, and easier to understand.*  
—[*Object-Oriented Programming with Objective-C*][apple_oop_guide_intro], Apple Inc.

[apple_oop_guide_intro]: https://developer.apple.com/library/ios/documentation/Cocoa/Conceptual/OOP_ObjC/Introduction/Introduction.html#//apple_ref/doc/uid/TP40005149-CH1-SW2

It's natural to wonder, "how can a string of ones and zeroes be referred to as an 'object'?" The use of the word "object" is an abstraction of thought. An "object" in code has no more physical form than does a word in any human language. Sure, words have physical representations: speaking a word causes air to vibrate in a sound wave, ink on a page can be shaped into symbols that represent the word, a meaning can be pointed at or mimed out; but none of these are the word itself. Human language is a system of abstraction: it communicates the *idea* of a thing, but not the thing itself.

![](https://upload.wikimedia.org/wikipedia/en/b/b9/MagrittePipe.jpg)  
Translation: "This is not a pipe." - [*The Treachery of Images*](https://en.wikipedia.org/wiki/The_Treachery_of_Images), [René Magritte](https://en.wikipedia.org/wiki/Ren%C3%A9_Magritte), 1927  

This image of a pipe is no more a pipe than the word "pipe" is a pipe; in the same way, a code object named `pipe` is not a pipe, but only another form of representing a pipe.

>As humans, we’re constantly faced with myriad facts and impressions that we must make sense of. To do so, we must abstract underlying structure away from surface details and discover the fundamental relations at work. Abstractions reveal causes and effects, expose patterns and frameworks, and separate what’s important from what’s not. Object orientation provides an abstraction of the data on which you operate; moreover, it provides a concrete grouping between the data and the operations you can perform with the data—in effect giving the data behavior.  
>—[*Object-Oriented Programming with Objective-C*](https://developer.apple.com/library/ios/documentation/Cocoa/Conceptual/OOP_ObjC/Articles/ooOOP.html#//apple_ref/doc/uid/TP40005149-CH8-SW3), Apple Inc.

A code object representing a water pipe (instead of a smoking pipe) might contain values for `length`, `diameter`, `material`, and `manufacturer`. The bundling of these individual pieces of information together begins to form a larger whole.

Object-Oriented Programming, however, does more than just bundle up individual pieces of data that represent a "thing" — it also bundles customized functions that can be performed *on* that data. These are called **methods**: behaviors that an object performs upon its internal data and even upon other code objects.

An object in code is a thing with all the data and all the logic required to complete a task. Objects are models and metaphors for the problems we solve in code.

Object-oriented programming was born from the trend of making digital lives reflect our real lives. In the 1970's, [Adele Goldberg](https://en.wikipedia.org/wiki/Adele_Goldberg_%28computer_scientist%29) and [Alan Kay](https://en.wikipedia.org/wiki/Alan_Kay) developed an object-oriented language at Xerox PARC called SmallTalk, which was used in the first personal computer.

Python comes with a few types of Objects to get us started, things like `int` for Integer, `str` for String, `list` for List, etc. We call these base types of Objects "Primitives." Primitives already have methods we can call on them, for example: `.title()` for a String. But what if we wanted to create a new type of object in our programming universe, a new kind of object for our code? With Object Oriented Programming, we can do just that by using the `class` keyword!

## Summary

You should now have a better understanding of the concept of Object Oriented Programming (OOP)!
