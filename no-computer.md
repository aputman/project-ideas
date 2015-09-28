# No computer project


## The user and a language
People playing the oboe put their fingers on different holes to make different 
sounds. Having a strict language for what happens when certain holes are covered 
by certain fingers would allow the players to focus more on their music and less
on how to get the intrument to produce the sound they want. 




### What's the need?
Oboe fingerings are needed by those who are learning the instrument and 
as a way of normalizing the sound each oboist makes with each note. 
A beginner learning the intrument without an instrument fingering language
would not know what note corresponds to what sound. The person who is able 
to put different fingerings down in order is able to produce the 
song that the music is telling them they are playing. 

### Why a language?
A DSL is appropriate for oboists as it normalizes the instruction for
beginners but also normalizes what composers composing for oboist expect 
is possible from them. When a beginner puts a set of fingerings
down and then another, they will already expect to hear what the music 
they are trying to play sounds like because of the DSL. It gives a 
normalized deterministism to playing the intrument and being able to 
classify what was played. 

### Why you?
As an oboe player, the idea of having a language that defines what 
sounds are made from certain holes being covered makes the process of 
learning and playing music much easier. 


### Domain
Oboe players learning and playing 


### Interface (syntax)
The user would interact with the language by putting different fingers covering
different holes at different times. A fingering is the set of holes being covered 
at the same instance in time. 


### Operation (semantics)
When the program runs, or when the player blows into the reed (the way the
instrument is played), air will blow over the different sets of holes producing
different sounds, creating music. By hearing this music, the player is getting 
an output of their input of fingerings. If they put the wrong fingering down,
the sound they wanted to produce could change, leaving the music they were
trying to play sounding weird or wrong. This leads them to fix the mistake and
get the correct sound. 


### Expressiveness
It should be able to place fingers in their correct placement easily for normal 
music without too much effort. If the music is difficult or the intervals are 
very high, then it might be harder to put the right fingers in the right place 
at the right time. There shouldn't be much that is impossible except define 
fingerings that produce notes that don't exist on the intrument. 


### Related work
_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well 
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

There are several other DSLs in this domain. Everyother woodwind instrument
has their own fingering language to define how to play that instrument. 
They adress their needs well but are different than the oboe DSL since
the oboe has a different range and shape for the fingerings to fit on. 
The bassoon for instance has a fingering in its language that requires
you to cover half of a hole which is very difficult. It might be easier
to redefine the language to only require entirely covered holes. 


## The Project
The oboe fingerings have already been defined, so it would not make a good 
CS111 project. 


### Suitability
_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

So most of the time in designing the language would be on the "systems" aspect
of it by defining where the holes should exist on the instrument. Careful 
physics is required to tell which holes will produce what tones. It is a mixture
though as we know what sounds we want to make, so a combination of all the holes
should make all these sounds. I would say 80% should be spend on the systems
aspect. 

### Scope
_How big an idea is this? How ambitious is this project?_

This project is pretty ambitious as it defines an entire instrument, what it
sounds like and how it is played. 


### Benefits and drawbacks
_Why might this be a good idea for a project? Why might this not be a good idea 
project?_

This would not be a good idea for a project since it is not on the computer. 
Computerizing the oboe would not produce much good because if it isn't played 
by hands, you don't need fingerings for it. 