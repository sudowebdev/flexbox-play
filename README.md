# FlexBox Play

The sections have been divided into individual **css** files which are bound to respective **html** files.  

To make it simple for you, the names for the bounded **css** and **html** files are kept the **same**.  
As an instance, the file **flex-main.css** has all the styling related to **flex-main.html**.    


###### Let's now start the exploration of **CSS Flexible Box Layout Module**!  


## Part-1: Making a basic flexbox container  
The first part deals with the question:  

Q. What is flexbox?  
A. It is a new layout module in CSS3 made to improve the items alignment, direction in which they get aligned and order in the container even when they are with dynamic or even unknown size. The prime characteristic of the flex container is the ability to modify the width or height of its children to fill the available space in the best possible way on different screen sizes.

Flexbox layout algorithm is direction based unlike the block or inline layout which are vertically and horizontally based. This flexbox layout should be used for small application components, while new CSS Grid Layout Module is emerging to handle the large scale layouts.

Flexbox: A flexible box model

#### The Basics:  

The flex layout is constituted of parent container referred as flex container and its immediate children which are called flex items.  

#### Part-1: The Code (flex-main.html) 

To use flexbox layout just set the display property on the parent HTML element:  

	.flex-container {
	  display: -webkit-flex; /* Safari */
	  display: flex;
	}

Or if you want to display it like an inline element use:  

	.flex-container {
	  display: -webkit-inline-flex; /* Safari */
	  display: inline-flex;
	}  


The difference between **flex** and **inline-flex** is how the flex container gets rendered. **Block-wise** in the former case and **inline** in latter.  

###### Note: This is the only property you need to set on the parent container and all its immediate children will become automatically flex items.


