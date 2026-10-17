# odin-recipes

13 October 2026, 9.40pm

1. Avoid styling HTML elements by universally by accident. Styling semantic tags like a p h1
   means styles apply to all. matching instances in site. Use class selectors or more specific selectors
   instead (e.g.) .main-nav a {...} .main-nav a:hover {...}
2. Put transition on the base elemeent (not hover states)
3. Adding a border of 2px to main-nav's hover state made the nav flicker (because on hover, 4px is added horizontally,
   on mouse-leave, 4px is less) To solve this, use outline
4. Make nav bar stick to top, don't forget to tell browser where to stick it using position: sticky; and top: 0
5. Make image in recipe card zoom in on hover'
6. Add Lenis for scrolling

13 October 2026, 3.42pm
Reached the Block and Inline Assignment where instruction was to style Odin Recipes.
Added Lenis for the scrolling effect. Added a global header bar.

28 Sep 2026, 10.48pm
Should I let #odin-recipes stay at the start of this document? I didn't put it there. Who? Why?

28 Sep 2026, 10.50pm
In this lesson, I will be making an index page which will link to a few recipes.
I just created a new repo in Github, named it odin-recipes, turned on Add README.md,
went in to Terminal to clone the repo into my repos folder. Realised I'm in the wrong dir when I ran git clone, so I had to mv odin-recipes repos/odin-recipes in order to correct my mistake.

Reminders:
All Git commands need to be run from odin-recipes
Don't forget to commit

11.29pm
Starting now.
