# Unfinished-Works
Some programs I began work on a long time ago for fun but never fully finished, however the main idea is still present!




Circles is a simple program that wherever you click in the window a circle is created that continues to grow. 
As you may predict this can take up alot of processing power so be careful!







Natural Selection was a program I began to develop based on the growth patterns of trees in respect to different environment pressures.
The middle of the screen is considered the equator, thus warm and humid, where most plants prosper. The top and bottom of the screen
serve as the colder north and south poles of the world, where very little or only specialized trees survive. Thus as you watch
the program go along you'll see how the trees tend towards the middle of the screen and that the ones outside of the middle don't tend to
reproduce.

Trees reproduce in the spring and summer, and don't do anything but age in the fall and winter. Trees will spawn another tree that:

  - is slightly larger or slightly smaller than it is
  - is slightly more blue or slightly more green than it is
  - has a lifespan of a random number
  
The program also has some functions that allow for things to be changed:

  - S = Slow speed (time goes slow)
  - D = Normal speed (default time speed, not real time but time that was chosen)
  - F = Fast speed (much faster time)
  - L = display each tree's lifespan as a number. When the number is 0 then the tree dies
  - Entering and leaving a tree with the mouse will cause a tree to die. If the tree does not die, clicking
    on the tree removes it indefinitely
    
The program caps the tree amount at 500, otherwise the program ended up taking too muhc processing power. Think of this as environmental
pressures containing the amount of trees, such as space to grow or competition for sun or water.







Virus Simulator was a program I initially created to be a test program for when objects touch. At the time of creating the
project, I didn't know any convenience functions for testing if one object was touching another, So I had to improvise and test it
on my own. It took a long time to figure it out and tons of testing but this program shows my progress and success! This is why
you will see the squares changing their color slightly whenever they touch another square, it signifies that it is touching something.

The program starts out by creating 100 squares in the programs area, each with a random integer for its x and y (thus why
this process takes so long). Once a square is created, it will move at a constant rate around the screen, bouncing off walls and going
in the opposite direction of the wall it hit, think of the screen saver icon that bounces around the screen for DVDs.

Once all of the squares are created, the "loading..." text will disappear along with the square that was used with it moving back and
forth, and the program will begin!

The whole idea with this is to create a virus square that will potentially infect the entire group. Whenever an infected square touches
another uninfected square, then the uninfected square will become infected. It is important to know that once a square is infected,
it is immediately given a timeline of how much longer it will exist, and then once that time is 0 it will disappear, thus giving
chance to the idea that a square may survive!

This program also has some functions to change things during it:

  - S = gives the squares a little black square that is drawn behind it, serving the purpose of a shadow.
  - C = Changes the color of all of the uninfected squares
  - V = spawns an infected square (suggest using this only once)
