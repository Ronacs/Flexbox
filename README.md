Udemy course by: Jonas Schedmann

# Flexbox
* Flexbox is a new module in CSS3 that makes it easy to align
  elements to one another, in differen tdirections and orders;
* Give the container the ability to expand and to shrink elements to 
best use all the available space;

https://ronacs.github.io/Flexbox/
![Desktop](/127.0.0.1_5500_index.html.png)

# CHEAT SHEET
###### display:flex | flex-inline  (behaves like and inline element)
 
### CONTAINER (Flow Direction of Flexbox)
###### flex-direction: row (default) | row-reverse | column | column-reverse

Flex automatically drop (if set to 'wrap') - the item if does not fit with the browser window 
###### flex-wrap: no-wrap (default) | wrap | wrap-reverse

Justify the container  in the main axis (x)
###### justify content: flex-start (default) | flex-end | center | space-between | space-around | space-evenly 

Align the flex items in the cross axis (y)
###### align-items: stretch (default) | flex-start | flex-end | center | baseline

Align if there is more than one row in the flex items 
###### align-self: stretch | flex-start | flex-end | center | baseline


# ITEM ( inside from CONTAINER )

###### align-item: auto (default) | stretch | flex-start | flex-end | center | baseline

Re-order the items according to integer define (in order / sequential ).
###### order: 0 (default) | < defined integer>

The equivalent of width: %, use flex-basis instead of width.  
###### flex-basis: auto (default) | <defined unit>

Make item grow
###### flex-growth: 0 (default) | 1

Shrink item
###### flex-shrink: 0 (default) | 1

##### Shorthand -> grow shrink basis = flex: 0 1 auto;


