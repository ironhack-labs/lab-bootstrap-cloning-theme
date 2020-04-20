![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# LAB | Cloning with Bootstrap

The Internet provides lots of templates and themes. But some of them cost money. However, we don't need to pay for something we already know how to do, so... We are cloning a theme!

## Requirements

- Fork this repo
- Clone this repo
- Have at least 50% of this lab done and submitted

## Submission

- Upon completion, run the following commands:

```
$ git add .
$ git commit -m "done"
$ git push origin master
```

Create Pull Request so your TAs can check up your work.

## Introduction

You will be cloning the [Carousel template example](https://getbootstrap.com/docs/4.0/examples/carousel/) from the official Bootstrap docs. The goal is to have you recreate the same layout but using the semantic HTML5 tags where appropriate. Remember to use the inspector to determine the layout and the classes.

You should try to understand the page layout and to recreate it. In this process try to target all the things you don't really understand and find answers on them. This exercise is pretty easy, so focus on understanding each step.

## Iteration 0 - Setup

Create all necessary files (for HTML and CSS), and have the Bootstrap (and jQuery) files imported to your project. You can download them from the site directly or link them via a CDN.

## Iteration 1

Focus on the general layout. What do we mean by general? Most of you are thinking about the header, how to create the menu, whether you should use 2 columns or maybe 3... Don't worry, this is a common mistake at the beginning. However, as we will see, the best way to approach it is to look everything through the big "boxes" and don't lose time on the details in the beginning.

So we have to see the page as a big container and identify the most important sections. Here you have an example:

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_79d8514500dea1c753affd3e45a53ac6.png)

Your goal is to build the structure for the [Carousel template example](https://getbootstrap.com/docs/4.0/examples/carousel/) page using good HTML5 semantic tags.

## Iteration 2

Now that we have a global vision of the page, we can go to the second level: dividing our box into their own internal structure. Each of the "boxes" will have a various number of rows, and you will have to add a certain number of columns in there as well. This means that you will have to estimate the number of cells you will need in each row. Remember that each row has a size of 12 columns.

## Iteration 3

Use the Bootstrap classes to get the same styles. _Warning_: The navbar is potentially the hardest part, so don't get discouraged. Don't hesitate to use developer tools in your browser to get some hints.

**Happy coding!** :heart:
