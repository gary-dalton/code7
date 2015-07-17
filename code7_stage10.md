---
title: Code7 - Stage 10
subtitle: Conditionals
author: Gary Dalton
date: 16 July 2015
license: Apache License, Version 2.0
github:
  user: gary-dalton
  repo: code7
  branch: "gh-pages"
pandoc: pandoc -t html5 --standalone --section-divs --template=template_revealjs.html code7_stage10.md -o code7_stage10.html
tags: code7, code.org, stem, conditionals

---

# Conditionals

Conditionals are the way computers make decisions. Conditionals are used in if-statements and loops.

#

<iframe data-autoplay width="800" height="600" allowfullscreen src="https://www.youtube.com/embed/yr6g0AWE7yw"></iframe>

# Objective

- Gain experience determining the outcome (true or false) of conditionals
- Evaluate logical statements to determine which branch of a program to follow
- Introduced to javascript code

# Materials

- Blank paper for keeping score
- One deck of playing cards

# Vocabulary

<li class="fragment">**Conditional**: A statement that is either true or false depending on the situation
<li class="fragment">**If Statement**: A line that determines whether or not you run a certain chunk of code
<li class="fragment">**Else**: Another way of saying "Otherwise"
<li class="fragment">**Function**: A piece of code that can be called over and over
<li class="fragment">**Increment**: To add a certain amount (often 1), once or many times
<li class="fragment">**Decrement**: To subtract a certain amount (often 1), once or many times
<li class="fragment">**Nested Statements**: A statement inside another statement

# Review and Extend

- How is a while block different from an if block?
- Can you think of anything we do in real life that could be described with a while loop?

# Simple If

    If you all raise your hand,
        I will clap.

# If with Else
    If you all raise your hand,
        I will clap.
    Else,
        I will touch my nose.

# Nested If-Else

    If you all stand,
        I will bark.
        If you all clap,
            I will stand on 1 foot.
        Else,
            I will stand on both feet
    Else,
        I will whistle.

# If, Else if, and Else

    If you all touch your ear,
        I will mew.
    Else if you all touch your nose,
        I will moo.
    Else,
        I will whistle.

# Conditionals

We call these "If Statements" conditionals, because there is a condition placed on them. Something is either true, or it's not. If it's true, we do the instruction inside the "If Statement". Otherwise, we do the instruction inside of the "Else Statement".

## Questions?

# Activity

## We will use a deck of cards and conditional statements to score points.

## This is the conditional code in javascript.

    if (card.color == black){
        team.points += 1;
    }
    else{
        team.points -=1;
    }

##

| Javascript | Pseudocode |
| ---------- | ---------- |
| if (card.color == black){ | if card’s color is black |
| team.points += 1; | then team’s points increase by 1 |
| } | |
| else{ | otherwise |
| team.points -=1; | team’s points decrease by 1 |
| } | |

##

- Yes, the parentheses, brackets, and semicolons are required
- '==' means check if it equals while '=' sets it equal
- '+=' means increment
- '-=' means decrement


## Ok, let's score points

    if (card.color == black){
        team.points += 1;
    }
    else{
        team.points -=1;
    }

## Try with different algorithm

    while (card.value < 5){
        team.points ++;
        if (card.value == 3){
            team.points += 2;
            if(card.suit == "clubs"){
                team.points --;
            }
        }
    }
## Write a simple card-scoring conditional algorithm in javascript

# Objectives

- How do computers make decisions?
- On code.org, you can see the javascript of your code by clicking "</> Show Code"

# Vocabulary

- **Conditional**: A statement that is either true or false depending on the situation
- **If Statement**: A line that determines whether or not you run a certain chunk of code
- **Else**: Another way of saying "Otherwise"
- **Function**: A piece of code that can be called over and over
- **Increment**: To add a certain amount (often 1), once or many times
- **Decrement**: To subtract a certain amount (often 1), once or many times
- **Nested Statements**: A statement inside another statement

# Mark Stage 10 as complete on code.org


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
