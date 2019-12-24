# beginner-programming-tasks

Language agnostic path for going from a beginner programmer to the intermediate level.

## So you learned all you need as a beginner!

You got it... operators, keywords, commands, loops, conditionals, functions, classes, and everything else that youtube and a few good articles can convey.  Now you need the practice that will build confidence along with the continuing journey of best practices and structure.

You apply your brown belt in Google-fu to find [programming challenges](https://lmgtfy.com/?q=programming+challenges "Let me google that for you") and find a plethora of resources.  **The fibonacci sequence will never be safe from you now!**

Thus, you learn, slow but steady.  If only you actually *used* any of these once you have completed your programming.  After all, you are also learning those best practices which make your earlier efforts almost too embarrassing to look at.  It's just difficult to get the drive to remake all those silly old scripts and binaries "more correct".

>Why is it cool for you to hate pythonistas?  Aside from that name, they will argue if a beginner's code is "pythonic", which any other language would just say "more correct".  More advanced coders in other languages will give you a list of reasons to hate python, but it's all really just about that nomenclature.

## What do I do then oh wise one?

What is needed is a list of suggestions for *useful* code that you have a reason to come back to in order to fix, streamline, prettify, add functionality, or adding splash.

Still, this list has to be broad enough to cover as many possibilities, but also specific enough to inspire someone who may not even know what they might **need**.

## My contribution

### Parsing

Parsing is syntactic analysis, or simply extracting useful information from data that follows rules in its structure.  Actually manipulating that data is the natural follow up to this, usually with string manipulation.  I'm going to go out on a limb here to suggest that this is the first big chore for intermediate programmers and you can see the results by looking up how many times some structured data is being parsed by yet another personal project in github.

How you, as a better-than-beginner programmer can use this is pretty extensive, and you will also have to balance *using* a parser as opposed to *making* a parser.  Most languages have got parsing pretty well covered in basic libraries that are probably well known for even a beginner and learning to use those are also important in the grand scheme of things.  Still, including a bit of your own code in a parsing function without reinventing the wheel is a good idea.

> I explain parsing to non-programmers for the sake of explaining how to communicate with programmers.  I use screenplays, and specifically *fountain* markup for screenplays, explaining how each element is identified in a person's writing.  I follow up with how to write a question for a programmer explaining several means of manipulating such data that I have never seen in finished screenplay software.  Much better than asking a programmer how to do something with a screenplay they know nothing about.

Some suggestions:

* **Data Entry** - My first job had to change multiple key:pair data in several files.  Parsing the requested changes and then using string manipulation for the change themselves turned my 8-10 hour per day job into a single command that finished in less than a minute.  Not just for big tasks, but anything that can be time consuming for a human to do regularly.  What data do you need to extract, manipulate, or change?

* [~~Census Names~~](https://github.com/fitnr/censusname) **Fork Something** - Not mine, but something I found useful.  Go to Github and find something you can use.  Does it really do *everything* you need?  Well, make it do what you want.  This example is one of the things I use for prose that literally makes "average" names so my character don't become the droll "Andy, Bob, Charles...".

* **Markup** - All markup already has parsers, otherwise there is no reason for the markup to exist in the first place... but does it do what *you* want it to do?  Do you need a table of contents based upon headers in markdown?  Do you need character scripts for fountain?  How about character based dialogue word clouds?  What kind of markup is used in data that you regularly work with?

* **Be A Troll** - You know this idiot on <social media platform> who is spouting some nonsense about some firebrand subject.  You know the data that supports your argument exists because someone you like mentioned it once in an article you can't find now.  Still, Wikipedia has the data, along with citations!  You check Wikipedia and the data is in a table which does not prove your point because it's a huge table.  If you are lucky the citation has the data in a CSV... easier to manipulate, but still not useful.  Are you going to pull that data from hundreds of entries, each entry with dozens of fields, and then manipulate it to actually mean something BY HAND?

> It turns out that person you like pulled that statement right out of their posterior.  **Never fear**, the [Dunning-Kruger effect](https://en.wikipedia.org/wiki/Dunning%E2%80%93Kruger_effect) is here to save you!

### Automation

You have already started automating some tasks in parsing, so what about automating the very environment you use to automate?

Some suggestions (part  deux):

* **Project Template** - When you start a project, do you make a directory structure?  Create boilerplate files?  Populate those boilerplate with as much information as possible before beginning work?  How about opening a custom workspace for that project?  Set up your IDE (yeah, vim is an IDE... fight me).  Set up a git?  Connect it to Github?  Are you doing this by hand?

* **Connect The Scripts/Programs** - Great!  Got a script for Python projects, another for Django, another for shell, one for screenplays, another for my website...  Now, in addition to all the stuff you have to remember to call yourself a programmer, you also need to remember all those silly little script names you came up with.  Automate all of that, and while you are at it, make it sexy and interactive.

* **Project Actions** - Most things you do on your computer are rarely a single action, but several actions done in order.  Regenerate your template website locally, inspect, send it upstream and have your server regenerate it.  Compile your markdown in multiple formats, inspect the results, send two different parsed results to two different people.  Compile code, test, make changes in git, send it upstream.  This is endless.

* **Environment Itself** - Do you check for updates... do you check changelogs before updating?  That could be useful to automate.  How about when you add a function to your shell environment, or add to the $PATH... do you have to reload it, or can you automate that?  Do these changes exist in every shell you use in case you may be thinking of changing to a different one?  Do you have to google unicode, or do you have a function that will (heh) parse a text file with unicode and descriptions so you can plug in whatever you want without leaving?

### Get some ideas

Now you can play programmer pokemon and **EVOLVE**!

All the stuff you are using, make it better^TM !  Use functions and generators.  Use config files and templates.  Use functions... or classes.  Split the big stuff into smaller, modular stuff that is easier to handle.  Include interactive help and documentation.  Give them menus.  Give them interactivity.  Give them a UI.

Get an idea!

In addition to the parsing and automation tasks that are built around things I personally performed regularly, I have a go-to for every new language I learn.  I make a dice roller for my tabletop games.  It usually follows this pattern;

* Make a random generator for regularly used dice combinations (d4, d6, d8, d10, d12, d20, d100).
* Make that menu driven.
* Make a parser that recognizes standard dice notation (eg, 3d6+1).
* Include unusual dice (FATE, et al.).
* Improve the UI many times.
* Include dice mechanics (eg. *advantage* in D&D5e)
* What else is random for a tabletop game?  How about a random card mechanic, or even dealing cards?

> * Cheats.  All that stuff up there is Beginner to Intermediate programmer stuff.  While cheats are very easy to write, they encompass a fully intermediate concept: testing.

By the time you get here, you may be thinking about mechanics that act upon these dice rolls - random table results, initiative or turn order (along with tracking), timers...

The next thing you know you are making a comprehensive game or game aid!

> You are not going to make that.  You are an *intermediate* programmer by this point and you will always be sure that *"this could be better"* and it will never get out of alpha.

You do not need to make a dice roller, but after working on things you will hopefully use and continue to improve, you will have learned to look at things you do as programming actions and have some grand idea on your own... far better than some stupid dice roller written in several different languages.
