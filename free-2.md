# Free project 2


## The user and a language
This section describes who the project would serve and why a language might be a
good way to meet their needs.

People need food. When they are low in suplies in the kitchen, many don't know
what to cook. They need a program that tells them what they can cook with their
remaining ingredients. 

### What's the need?
_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help 
them?_

People are lazy and don't want to go to the store when they don't know what
they can cook. If they are able to use this language, then they will be 
able to stay in the comfort of their own home. Currently, they have to get
in their car and drive to the store. Which this language, they would be able
to stay home and even learn a new recipe. 

### Why a language?
_Why is a DSL appropriate for your user(s)? How does it address the need?_

A language would be useful to take in inputs for the ingredients they have
available and their aversion to certain foods. They might even be able to
say what food they like together. 

### Why you?
_What excites you about this idea? How did you come up with it?_

As someone who hates to leave my house/room, staying in and being able to
make food from my remaining scraps would be ideal. I came up with it while
eating at the hoch and looking at all the leftover food people had. 

### Domain
_Describe the project's domain in five words._

Food cooking instruction left overs

### Interface (syntax)
_How might the user interact with the language? What does programming look 
like? Why is this the right way to interact with the problem domain?_ 

The users would give ingredients, preferences and allergies to the language.

It would most likely take in lists are are linked to other lists with preferences
and then another list for allergies. 

### Operation (semantics)
_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

The program would look online for different recipes and compare their ingredients
with those listed, trying to optimize for preference and remove all that 
disagree with allergies. 

### Expressiveness
_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

It should be able to input foods, preferences and allergies. It should be
possible to make preferences so strict that you almost know what you will get
but that should be very difficult. There isn't much in the domain that should 
be impossible. 

### Related work
_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well 
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

There are a few online tools that take in what you have left and suggest recipes
but none of them currently ask about preferences or allergies. 

http://www.pantryraid.xyz/

This site takes in photos which is easier than inputting by text, but also 
requires money which we won't have to ask for. It could be improved by asking
for allergies. 

## The Project
This section examines whether the idea makes for a good CS 111 project.

This might be a bit difficult for a project since it would require scraping the 
internet for recipes. Other than that it also doesn't allow for that much expressiveness. 

### Suitability
_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

Almost 99% of the work would be on the system looking up recipes to recommend. 

### Scope
_How big an idea is this? How ambitious is this project?_

This project because of the web scraping would be ambitious for the semester. 

### Benefits and drawbacks
_Why might this be a good idea for a project? Why might this not be a good idea 
project?_

This would be a bad idea since it doesn't allow for that much user expressiveness and
the backend interpreter for the language would require difficult web scraping. 
