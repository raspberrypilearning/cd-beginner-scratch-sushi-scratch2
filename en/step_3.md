## Adding and removing code blocks

Great! You’ve written your very first Scratch program. Time to learn a little more about getting code in and out of Scratch! Scratch code is made up of **blocks** such as these:

![](images/code1.png)

You will find all blocks in the **code blocks palette**, sorted into different categories according to what they do.

--- collapse ---
---
title: Using blocks from the different categories
---

Click on a category name to see the blocks in that category. Here, the **Motion** category is selected:

![](images/code2a.png)

All of the blocks in the category you've clicked are shown in a list:

![](images/code2b.png)

You can click on the blcok you want, and then just drag it into the current sprite panel and let go. Once it's in the panel, you can move it around and connect it to other blocks.

--- /collapse --- 

If you want to see what a block does, you can double-click on it to make it run!

+ Try double-clicking on some of the blocks to see what they do.

--- collapse ---
---
title: Running the code
---

Usually, you want your code to run automatically whenever something specific happens. This is why many of your programs will start with a block from the **Events** category, most often this one: 

```blocks
    when green flag clicked
```

The code blocks connected to this block will run after the **green flag** is clicked.

Code blocks run from top to bottom, so the order in which you snap your blocks together matters. In this example, the sprite will `say`{:class="blocklooks"} `Hello!` before it will `play`{:class="blocksound"} the `meow` sound. 

![](images/code4.png)

--- /collapse ---

Removing or deleting code blocks you don’t want in your program is easy! Just click on the **scissors** icon, and then click on the block you want to remove.

![](images/code5.png)

**Be careful:** using the scissors tool will delete all the blocks connected to the block you click on, so make sure to separate code blocks you want to keep from those you want to remove. If you delete some code blocks by accident and want to get them back, you can just go to the the **Edit** menu and click on **Undelete** to get everything back.

![](images/code6.png)

+ Try adding, deleting, and undeleting some code blocks! 

### Putting it all together

Now you know how to move code around and make things happen, it's time for you to create a program to make the Scratch Cat walk in a circle!

+ Make sure you have the cat sprite selected in the sprite list, and then drag the following blocks into the sprite panel and connect them. You’ll find them in the **Events** and **Motion** lists.

```blocks
    when green flag clicked
    move [10] steps
``` 

+ Then, click on the green flag above the Stage. 

![](images/code7.png)

You should see the cat walking in a straight line...not exactly what you want, right?

Note: If you click th flag too many times and the cat walks away, you can drag it back!  

+ Snap this block to the end to make the cat sprite walk in a circle. It’s in the **Motion** list too. 

```blocks
    turn cw (15) degrees
```

--- collapse ---
---
title: How does turning work?
---

This block makes the sprite turn 15 degrees of the full 360 degrees that make up a circle. You can change that number, and the number of steps, by clicking on the number and typing in a new value.

![](images/code9.png)

--- /collapse ---

+ Now save your work! You do this by going to the **File** menu and clicking **Save**. Remember to save your program regularly while you code!

![](images/code10.png)

### Top tip
You can also click **Save as** to save a copy of your program under a different name.
