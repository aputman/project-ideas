# Anti project


## The user and a language
This section describes who the project would serve and why a language might be a
good way to meet their needs.

Music enthusiasts want to be able to define songs that play well with other songs. 
Having a language define these connections will allow us to be able to parse the
language and play the songs together, increasing the joy the user gets from listening
to their music. 

### What's the need?
_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help 
them?_

The need is to be able to categorize music into groups that play well together.
I am helping music listeners who have a wide genre of musical tastes. 
They currently have to go from song to song in different albums individually picking
which ones they like. 


### Why a language?
_Why is a DSL appropriate for your user(s)? How does it address the need?_

A language would not be useful here since we are just defining buckets of songs.
This can be more easily done by defining these playlists as lists rather than as 
a language. 

### Why you?
_What excites you about this idea? How did you come up with it?_

I came up with it from another interview I had during class the other day. This guy
was telling me how music was very important to his life and playlists play a large 
role in that. 

### Domain
_Describe the project's domain in five words._

Grouping music sounding good together

### Interface (syntax)
_How might the user interact with the language? What does programming look 
like? Why is this the right way to interact with the problem domain?_ 

They wouldn't interact with this language because it would be easier for 
them to just add songs to different lists. If our language was just defined
by a bunch of lists, then it would be pointless to even design. 

### Operation (semantics)
_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

It would be easier for the program to run on the list since lists are simpler 
concepts. They can be shuffled, indexed into and many other things that are 
convienent. If we wanted to have these functionalities, we would basically
be reinventing the wheel. 

### Expressiveness
_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

It should be easy to group songs together. Nothing really hard since the 
domain doesn't allow for much variety (also why it would not make a good
language). It should also be easy to randomly play a song from the playlist
or play a selected song from the playlist. Playlists generally already
have this function, again proving we would be reinventing the wheel. 

### Related work
_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well 
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

Any music playing software has a concept of playlists or folders for similar music.
These programs generally allow songs of different artists and genres to be grouped
together and be played together. Playlists can be played individually or randomly 
or sequentially as defined. Thus proving that a DSL is not needed for this. 

## The Project
This section examines whether the idea makes for a good CS 111 project.

This would not make a good CS111 project as the problem has already been solved 
hundreds of times and the solution is not best as a DSL. 

### Suitability
_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

Since the concept is pretty easily implemented, I would say 70% of the work 
would be done on the language, since the system would basically just have to
be a list that could play music. 

### Scope
_How big an idea is this? How ambitious is this project?_

This really isn't that ambitious of a project. Maybe defining what songs are and
where to get them from would be ambitious, but this would mainly just require
defining lists and have operations that can be performed on them. 

### Benefits and drawbacks
_Why might this be a good idea for a project? Why might this not be a good idea 
project?_

This again would not make a good project. It is simple, already solved and in
no need for future research. Especially DSL research. 