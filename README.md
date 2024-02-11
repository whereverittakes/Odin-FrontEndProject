# Odin-FrontEndProject

    This is basically the first Odin front-end project using basic HTML and CSS.



This is the first actual full project of Odin.
    At first, it's clearly not that easy to create the HTML file from 0 to it's full form.
    I found it to be quite challenging, and no wonder, it's the first page I created.


Clearly, the most challenging part about this project is setting each image side-by-side below the header, each of them with the same height and width, maintaining their aspect ratio.


The trick for this seems to be creating a division for all the images, then inserting on CSS:

(division) > (division)

In my code, you will see it as .images > div

Which basically means all div (divisions) within the images division.

Then setting them to a specific width and height (200px and 200px) 
Then actually doing .images > img

Which stands for images within the .images division.

And setting them to 100% of their width, 100% of their height, and most importantly,

Use object-fit:cover;, ensuring they maintain their aspect ratio.


    There were quite other challenging parts as well, but that was by far the most challenging of all of them.

--