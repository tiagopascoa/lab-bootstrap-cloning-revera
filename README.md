# Cloning with Bootstrap

Internet provides lots of templates and themes. But some of them cost money. However, we don't need to pay for something we already know how to do, so... We are cloning a theme!

http://demo.fabthemes.com/revera/

As we can see, this template is a very good example of the type of webpages we can see on the Internet. With Bootstrap, we are able, in barely a few hours, to copy the appearance of this template.

## Interation 1: General layout

Focus on the general layout. What we mean by general? Most of you are thinking about the header, how to create the menu, whether you should use 2 columns for a link or maybe 3... Don´t worry, this is a common mistake at the beginning. However, as we will see, the best way to face it is to look at the big “boxes” first and don't lose ourselves on the details.

So we have to see the page as a big container and identify the most important sections. Here you have and example:

![general layout](https://i.imgur.com/IIAG0g0.jpg)

Remember to use the inspector to determine the width and the height of the Revera page. Also, we could find out which Bootstrap classes has been used and anything else that is necessary to make our page looks like the original.

One cool Boostrap feature is that you have three elements that make our lives easier: `container`,  `row` and `columns`. Don't hesitate to use them!

## Iteration 2: Internal structure

Now that we have a global vision of the page, we can go to the second level, dividing our box into their own internal structure. This means that if you previously create a single content and various rows, now we are going to define the columns. You will have to estimate the number of cells you will need in each row.

The [grid system](http://getbootstrap.com/css/#grid) of Bootstrap gives you all the ``.col``classes. Remember that each row has a size of 12 columns.

## Iteration 3: Include the content

Really cool! Now, you need to insert the content in its respective places(text, images, ...) and change some CSS options like margins, paddings, etc. to finish the template. It´s just a matter of Bootstrap!

Well... Maybe it's not that easy. But try different things and make it happen!
