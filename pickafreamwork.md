# Choosing Your First Frontend Framework
> Note that this article is my opinion on how to choose a framework as a beginner, rather than a strictly technical guide. I have included links at the end of the article if that's the kind of thing you were looking for.

## Are you ready for a framework?

You may not be ready to choose a framework for web development. Currently, web development is the wild west.
Frameworks, libraries and tools all vye to be the fastest gun, or at least the one with the best developer experience. Without a solid foundation of Javascript, HTML, and CSS you will not be flexible enough to be able to easily switch between these frameworks. It is almost a given that whatever framework you choose now will eventually become obsolete, and if you are unable to switch it up and learn new tools you will be stuck forever working on an obsolete technology. 

The key to knowing when to switch is by carefully gauging the nature and the strength of the frustration which you will inevitably feel when developing in vanilla Javascript.
 Developing functional websites and web applications with only vanilla tools is often tedious, and as projects become larger, managing them is very complex. 
 Like most things that are both complicated and tedious, it is also incredibly frustrating at times. Hold on to this frustration, it will be one of your most important tools to growing into a strong developer. 
 Try and categorize your annoyances, to compartmentalize your vexation. The important part of this isn't *just* to be self flagellating, sitting at the most notorious programming bars and saying you made everything from scratch. Your frustration is the first step to start recognizing programming patterns. You'll notice that very often the reason things make you so angry is that they are *the same exact freaking thing* over and over. 


**Where the heck is this change coming from?! I know I wrote it but I can't remember WHERE?**

**Great, another silent error. I'm so glad that Javascript is so well designed and everything fails silently and I have to go through my entire code base to find this one minor problem**

**Hmm, it sure would be nice to not have everything in this one ten thousand line file...**

You may not realize it but you are building *fluency* in Javascript and programming in general. When someone mentions unresolved promises you will feel a real and visceral sensation deep in your chest that was never there before. It's a feeling that can't be learned from textbooks alone.
This fluency is more than just having a good handle on the language or just its syntax. The fluency I'm talking about includes all of the other hidden skills it takes to excel as a programmer. These are the skills that are necessary to understand and choose a framework. Without them you will not be able to understand the *Whys* of the framework, just the *Hows*. If you can recognize patterns in your own code (ie. very specific gripes) then you will recognize that Frameworks are defining solutions to make those patterns easier. If you've followed a nasty bug from the very beginning and finally squashed it, advanced debugging functionality seems somehow sexier than it used to. If you've done a few projects you've most likely even practiced reading and understanding documentation, even if it's in the form of copy pasting functions from stack overflow.

// FIXME: Tessie's comment: Last sentence is awkward. I understand what you're trying to do with the trio of "ifs" but I think it needs to be reworked


Here is a small list of vanilla tutorials to get you started:
### Acticles 
//TODO

## I'm ready, tell me which is the best

Once you've conquered (or tried and failed enough at conquering) vanilla JS and you feel sufficiently ready to choose a framework, you find yourself in an almost completely new world. This is not the world of cold, hard boolean logic.  It is the world of **opinionated programming**. We could go back to the bar from earlier and ask the the many programmers there the same question: What framework would be best to learn first? They would all answer something completely different, and even the ones that agree would probably give you completely different threads of reasoning as to why. One of them would invariably tell you (rather snarkily) that frameworks are a big waste of time and you should just stick with vanilla Javascript forever. This isn't the big problem, the big problem is that **They are all correct** .   

In programming in general, and in web development specifically, there are usually an almost infinite amount of different tools, methods, and plans that you can use to attack a problem. If you ask someone with more experience which is the best she will almost answer the same: **It Depends**. 

The reason for this is because **It Depends** is the only answer. **It Depends** is the  *correct* answer. Even better, it is the *technically correct* answer. To you, as a beginner, it's an entirely useless answer.

The reasoning behind **It Depends** is as follows. The problems that you ran into during your vanilla Javascript days are not unique. These problems or similar ones are the seeds that some very clever developers grew into the most popular frameworks today. They are not, however, a universal truth and certainly not built to be some answer to an entirely logical question. Think of our question from before:

**Where the heck is this change coming from?! I know I wrote it but I can't remember WHERE? Have you forsaken me god? Is this truly the life I have chosen? **

Now lets standardize that into one that may be easier to turn into something actually useful:

**Is there a way to manage changes in my application so that I can better understand where they come from and more easily debug them?**

Notice that while this question has a logical base, it is still rather open ended and leans much more towards organizing the program to compensate for our human foible rather than some rigorous test of logic that can be solved with our big programming brains. There are certainly *wrong* answers to this question, but overall The opinion is baked in because it's a solution to organize human thoughts. 

// FIXME: Tessie's comment: I'm lost here with the sentence above.

It's almost like asking what the meaning of life is. It's not merely logical, it's much much worse. It's philosophical. A good programmer knows all this and that's why she will hit you with that stone cold **it depends**. 
The answer really does depend, on strictly logical things like : 

How much space will it take up in the project?  // FIXME: Tessie's comment: is this supposed to be bolded too? 

**Is the solution buggy?**

**Is the solution fast?**

but more often than that it is:

**Will it be easy for everyone on the team to learn?**

**Will I enjoy using it everyday?**


A Programmer answering with **It Depends** is sort of like a robot malfunctioning when you ask it if it loves you or if it has feelings. Programmers are creatures of hard, cold logic trying to answer a question that quite simply doesn't have one simple, logical answer. To pick any one answer as the best would simply be *technically incorrect*.

Back to our question from before:

**What *is* the meaning of life?**

Try and make your answer logical, precise, succinct and with no room for any mistake or oversight and you might see the answer. 


## Just Use React

If you're still wondering how to pick a framework, the answer really is it doesn't particularly matter which framework you choose to work with. You're not locked in if you hate it, and you simply don't have enough information to choose. Just make sure to choose something popular for the community. 
The easiest way to understand how good a community is how niche of a question will have to be before it results in an unanswered stack overflow question. 

// FIXME: Tessie's comment: Sentence above needs to be reworded bc it makes little sense lol 

A bad community will have no results for something like "How do I append an item to a list?" while a good one will have answers for things like "My birthday was on a leap year which was also the crescent moon, what is the best way to calculate the amount of years until the next crescent moon of a leap year that also falls on a Saturday?". 
If you want the best community, choose React. It's simply the biggest and most active framework at the time of writing, and to a beginner that almost* makes all other things irrelevant. When you have questions it will be relatively easy to find solutions, and there are a plethora of resources and tutorials to learn from when you are starting out. That React happens to be a pretty good framework with a relatively* easy learning curve and pretty good debugging tools is besides the point. Do at least one project with React before you fully decide to hate it, but once you do you'll find you have similar questions to your old Javascript days in the beginning of this article. 

**Why it so hard to update this one simple value without getting an infinite loop?**

**Okay so I guess I like immutable data, but does everything *have* to be immutable?**`

**It's so smart and scalable to lift state through ten different components, I'm so glad for one way data flow. I'm sure programming is annoying and hard all the time.**

and so forth.

 Once you get start to get fed up, It's up to you to whether to hit the docs or move on to the next framework. Regardless, you are still building the same fluency you started in the beginning. That fluency will consist of purely technical things like syntax, algorithms, and data structures but also the other, more opinionated parts of programming. You'll start to understand best practices and start disagreeing with Medium articles. These opinions are more than personal preference, they are the culmination of years of using different technologies and finding the best and worst parts of them.  



*note that sayings like relatively,most of the time, and almost always are basically the only way to say anything in computer science and be **technically correct**.  Always remember the one, only true answer to all your programming questions... 

// FIXME: Tessie's comment: It took me too long to understand what this little bit was about. I thought it was a jarbled up thought. Are "relatively", "most of the time", and "almost always" each supposed to be in quotes or is it just the "relatively"?

### Articles
  //todo
### If you really won't listen and use React
#### Vue
  //todo
#### Svelte
  //todo
#### Angular
  //todo

## Closing

 This article  is not meant to be discouraging, but becoming an excellent web developer truly is a long road. There aren't any shortcuts. Just stop overthinking, at least in the beginning. You might not be making the exact right choice, and may not be following the best practices that a more senior dev would, but if you focus on your projects you'll have something amazing to show for your efforts. Some of the most awesome and beautiful websites have been built by beginners on old, icky tech. Desicison paralysis is a real thing for developers at all levels, not just beginners. And while it is always worthwhile to be thoughtful and directed in your choices, you will always come to a point where it's basically a coin flip. IF you can't flip the coin, you won't choose anything and you'll be stuck forever.

 Isaav Asmiov wrote a story to this effect. https://mcraenglish.weebly.com/uploads/1/5/8/7/15876062/the_machine_that_won_the_war01.pdf 






