---
title: Code7 - Stage 12
subtitle: Song Writing
author: Gary Dalton
date: 13 August 2015
license: Apache License, Version 2.0
github:
  user: gary-dalton
  repo: code7
  branch: "gh-pages"
pandoc: pandoc -t html5 --standalone --section-divs --template=template_revealjs.html code7_stage12.md -o code7_stage12.html
tags: code7, code.org, stem, lyrics

---

# Song Writing

Reading lyrics is a pretty intuitive venture for most students. We’ll take an activity that’s already common knowledge and shift it into a solid education on defining and calling functions.

#

<iframe data-autoplay width="800" height="600" allowfullscreen src="https://www.youtube.com/embed/hx0tBso08aA"></iframe>

# Objective

- Learn about defining functions
- Practice calling functions
- See the practicality of passing variables as parameters

# Materials

- Paper and pencils for writing songs
- Lyrics of basic songs with choruses

# Vocabulary

<li class="fragment">**Chorus**: A piece of music that repeats often
<li class="fragment">**Function**: A piece of code that can be called over and over
<li class="fragment">**Function Call**: The piece of a program that sends the computer to a function
<li class="fragment">**Function Definition**: The piece of a program that tells the computer what to do when the code calls a function
<li class="fragment">**Parameters**: Extra information that you can give to a function to customize it
<li class="fragment">**Recursive**: A definition that refers to the word it is trying to define.

# Review and Extend

- What is a function?
- What does it mean to call a function?
- What is a counter block?

#For Loops

##

*Counter blocks* are often called *for loops*. They’re called that
because you do *something* FOR all values of the counter from the minimum
to the maximum.

##

Let's say you have a counter block that keeps track of your age. From age 5 to age 10, you grow two inches a year. From age 11 to age 17, you grow an inch every two years. This requires two blocks. What is the minimum value, maximum value, and add-on amount for each block?

#

<iframe data-autoplay width="800" height="600" allowfullscreen src="https://www.youtube.com/embed/hzus6W7BrIc?start=0&end=76"></iframe>

# Song

## Let's sing it

    CHORUS:
    Oh, dear! What can the matter be?
    Dear, dear! What can the matter be?
    Oh, dear! What can the matter be?
    Johnny’s so long at the fair.

    He promised to buy me a fairing to please me,
    And then for a kiss, oh, he vowed he would tease me,
    He promised to bring me a bunch of blue ribbons
    To tie up my bonnie brown hair.

    Chorus()

    He promised to buy me a pair of sleeve buttons,
    A pair of new garters, that cost him but two pence,
    He promised to bring me a bunch of blue ribbons
    That tie up my bonnie brown hair.

    Chorus()

##

Why didn't anyone sing the word **chorus**?

# Changing Chorus

## Chorus

    CHORUS (sound):
    With a *sound sound* here
    And a *sound sound* there
    Here a *sound*, there a *sound*
    Everywhere a *sound sound*
    Old MacDonald had a farm
    E-I-E-I-O

## Let's sing it

    Old MACDONALD had a farm, E-I-E-I-O
    And on his farm he had a cow, E-I-E-I-O

    CHORUS (“Moo”)

    Old MACDONALD had a farm, E-I-E-I-O
    And on his farm he had a pig, E-I-E-I-O

    CHORUS(“Oink”)

    Old MACDONALD had a farm, E-I-E-I-O
    And on his farm he had a duck, E-I-E-I-O

    CHORUS(“Quack”)

## Passing parameters

Notice when the chorus was defined, it included a sound in parentheses. Consider CHORUS() as a function definition. Anything in the parentheses is a parameter that is passed to the function.

# Multiple Parameters

##

More than 1 item may be passed to a function by separating the parameters by a comma. The next song will demonstrate this.

## Sing this song

    CHORUS (thing, place, did):
    ‘Cause I stuck a *thing* in a hole in the *place*
    and it *did*, and *did*, and *did*.

    I’m going to be the most famous kid of all,
    because of the thing that I just did.
    CHORUS(“seed”, “ground”, “grew”)

    I’m going to be the most famous kid of all,
    because of the thing that I just did.
    CHORUS(“plug”, “boat”, “floats”)

#

## Your turn

Adjust the lyrics to the song *Farmer in the Dell* so that the chorus may be called with  paramerters.

## Farmer in the Dell

    The farmer in the dell
    The farmer in the dell
    Heigh ho the derry-o
    The farmer in the dell

    The farmer takes a wife
    The farmer takes a wife
    Heigh ho the derry-o
    The farmer takes a wife
    The wife takes the child
    The wife takes the child
    Heigh ho the derry-o
    The wife takes the child
    The child takes the cow
    The child takes the cow
    Heigh ho the derry-o
    The child takes the cow

    The cow takes the pig
    The cow takes the pig
    Heigh ho the derry-o
    The cow takes the pig
    The pig takes the dog
    The pig takes the dog
    Heigh ho the derry-o
    The pig takes the dog

    The dog takes the cat
    The dog takes the cat
    Heigh ho the derry-o
    The dog takes the cat
    The cat takes a mouse
    The cat takes a mouse
    Heigh ho the derry-o
    The cat takes a mouse

    The mouse takes the cheese
    The mouse takes the cheese
    Heigh ho the derry-o
    The mouse takes the cheese
    The cheese stands alone
    The cheese stands alone
    Heigh ho the derry-o
    The cheese stands alone
    Heigh ho the derry-o
    The cheese stands alone

# Recursion

##

Recursion is a concept that confuses some people but is often very useful. Let's demonstrate it using the *Song that Never Ends*.

## Song that Never Ends

    I know a song that gets on everyone's nerves,
    everyone's nerves, everyone's nerves,
    I know a song that gets on everyone's nerves,
    and this is how it goes.

    CHORUS:
    This is the song that doesn't ends
    It just goes on and on my friend
    Some people started singing it not knowing what it was,
    And they'll continue singing it forever just because
    Chorus()


# Did you ...?

- Learn about defining functions
- Practice calling functions
- See the practicality of passing variables as parameters

# Vocabulary

- **Chorus**: A piece of music that repeats often
- **Function**: A piece of code that can be called over and over
- **Function Call**: The piece of a program that sends the computer to a function
- **Function Definition**: The piece of a program that tells the computer what to do when the code calls a function
- **Parameters**: Extra information that you can give to a function to customize it
- **Recursive**: A definition that refers to the word it is trying to define.

# Mark Stage 12 as complete on code.org


---
# OPTIONS FOR REVEAL.JS TEMPLATE
# see https://github.com/hakimel/reveal.js#configuration
reveal:
    # REQUIRED
    path: https://cdnjs.cloudflare.com/ajax/libs/reveal.js/3.1.0

    # RECOMMENDED
    # beige/black/blood/league/moon/night/serif/simple/sky/solarized/white
    theme: beige
    # none/fade/slide/convex/concave/zoom
    transition: concave
    # Use minified js and css. Make certain minified versions are available
    minified: true

    # OPTIONAL
    controls: true
    progress: true
    slideNumber: true
    history: false
    keyboard: true
    overview: true
    center: false
    touch: true
    loop: false
    rtl: false
    fragments: true
    embedded: false
    help: true
    autoSlide: false
    autoSlideSpeed: '2000'
    autoSlideStoppable: true
    mouseWheel: false
    hideAddressBar: true
    previewLinks: false
    transitionSpeed: 'default' # default/fast/slow
    backgroundTransition: 'none' # none/fade/slide/convex/concave/zoom
    viewDistance: '3'
    parallaxBackgroundImage: false # false or image path
    parallaxBackgroundSize: '2100px 900px'
    parallaxBackgroundHorizontal: '200'
    parallaxBackgroundVertical: '50'

---
