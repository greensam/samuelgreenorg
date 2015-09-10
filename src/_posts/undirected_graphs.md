{
  "layout": "post",
  "title": "A New Graph/FSM Drawer Is Born",
  "date": "Sun Jun 21 2015",
  "description": "I extended a pretty awesome finite state machine diagramming utility to make it more useful for general graph applications",
  "tags": [
    "graph", "theory", "finite state machine", "fork"
  ],
  "codepost": true
}

## Making My Own Life Easier, and Hopefully Yours Too

Blogging about my summer didn't really go anywhere, but I have something to post now.

I'm taking two courses this fall at Harvard related directly to graph theory: [CS 121, Theory of Computation](http://lewis.seas.harvard.edu/pages/computer-science-121-and-csci-e-121-introduction-theory-computation), and [CS 134, Networks](http://networksatharvard.com). I anticipate having to draw lots of graphs on problem sets this semester.

When I've had to draw graphs (or finite state machines, which are graphs in their own right) for classes in the past, I discovered [an FSM utility](http://madebyevan.com/fsm). If you've ever tried to use the tikzpicture package in LaTeX, you know that it isn't particularly quick or easy: that site made the process quick by generating LaTeX from an HTML canvas, where you can draw an FSM.

That was fine until this fall, when I need to be able to draw undirected graphs. After realizing that delete the arrows from the generated LaTeX was really tedious, I decided to fork the generator and make it more general.

So I did! You can find it at greensam.github.io/fsm. Hope it's useful to you. 


