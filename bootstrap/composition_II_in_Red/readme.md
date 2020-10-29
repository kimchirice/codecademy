# [Recreate a painting using Bootstrap's grid](https://www.codecademy.com/courses/learn-bootstrap/projects/bootstrap-grid-painting)

In this project you will practice using the fundamentals of Bootstrap grid by piecing together a famous painting, namely Piet Mondrian’s _Composition II in Red, Blue, and Yellow_:

Screen shot of Piet Mondrian's Composition II in Red, Blue, and Yellow

In *index.html* is a container with columns that represent various pieces in Composition II. You can tell which piece is what by the element’s id and the comment inside the column and with the labeled painting below:

Screen shot of Piet Mondrian's Composition II in Red, Blue, and Yellow
The column’s height and colors, and the container’s height and width, are already included in style.css. Your goal is to recreate the painting by:

* using the existing container.
* unscrambling the order of the provided columns.
* adjusting the widths of the provided columns.
* adding new rows and additional columns.
* nesting row(s) inside columns.

There will not be step-by-step instructions provided, however, there are hints in the steps if you get stuck along the way. Good luck and have fun!

*Note*: You might have to resize the browser to see the entire painting.

If you get stuck during this project, check out the project walk-through video which can be found in the help menu.

Tasks 0/4 Complete
_Mark the tasks as complete by checking them off_



  [. ] 1.What about the ordering?
  Stuck? Get a hint

  [. ] 2.Thinking about the layout?
  Stuck? Get a hint

  [. ] 3.More complex layouts?

Stuck? Get a hint


Extra
[  ] 4.If you want some additional challenges:
  * change up the painting layout entirely.
  * render the painting differently based on screen size (use breakpoints).
  * add different colors using Bootstrap.
  * add some interactivity using Bootstrap.



Recreate a painting using Bootstrap's grid
0/4 Complete

## Hints along the way
1. The initial ordering of the columns is all scrambled! But you can use the labeled diagram to help you unscramble the pieces.
  If you’re more a visual person, you can add some text inside the element.

2. You can think of the layout in a few different ways. One way is to separate the painting into two rows.
  In one row are the pieces A, B, and C.
  In the second row are the pieces D, E, F, and G.
  Focus on one row before moving on to the other row.
  You could also organize it differently but think about the painting in rows and columns! 
3.You can nest rows inside columns. Those nested rows can also have additional columns!

For example you could have:
```html
<div class="col">
  <div class="row">
    <div class="col">
       <!-- Piece 1-->
    </div>
  </div>
  <div class="row">
    <div class="col">
       <!-- Piece 2-->
    </div>
  </div>
</div>
```
In the example provided, there is a column with two nested rows. Each row contains another column. When rendered, the Piece 1 column would rest on top of the Piece 2 column. 
4. 

# Check [starting code](https://github.com/kimchirice/codecademy/tree/main/bootstrap/composition_II_in_Red/starting_code)
# Check [final code](https://github.com/kimchirice/codecademy/tree/main/bootstrap/composition_II_in_Red/final_code)
