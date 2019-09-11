# lab0
Lab 0 for CS100, Fall 2019

For my website, I decided to make a portfolio to hold a bunch
of my art and writing together in one place, since I figured
it might be something I would appreciate to have and return to.

Home.html is (suprise,suprise) the homepage for the website.
I put a photo of mysef here since I was trying to mimic an
author's website. 

Art.html houses a few of my sketches and paintings. I used
a table to give a clear list of the artwork with information
about each piece from which the pieces could be viewed. I chose
to use a table and inter-page links (giving each image an id)
because I wanted to either be able to just scroll aimlessly through
all the pieces OR click to a specific one.

Writing.html holds links to my a bunch of my writing that's
online. I thought this was a good place to use the bootstrap
grid because I figured a layout of links in three side-by-side
genre-labeled columns would be more elegant and user-friendly
then having a single long list to scroll through and lots more
white space on the page. In each column, I used a list to contain
all the links to pieces of writing in that genre with elegant
formatting and clear divisions between each.

All my css lives in styles.css. This makes things look pretty
and clean. Idk what more there is to say about the css. I mostly
used classes but incorporated one id in styling the navbar,
which I included on each page.

Some notes on things I'd like to learn/improve:

-I couldn't figure out how to make an entire table row a link
(in art.html) rather than just a piece of text within the row.
My google-searching seemed fruitful, but I wasn't able to manage
to get any of the many suggestions I found to actually work in
my code.

-You might notice each of the images on the art.html page
incorporate the class "center." I seemed to remember from CS50
that one could just put the class once in the div itself and
have it apply to all the elements within the div, to make the
code less repetitive? Somehow, this didn't seem to work, and I
wasn't able to find the right google search to help myself.
