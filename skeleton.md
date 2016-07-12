# What happens to the layout when you resize the screen to less than 550 px.
The content on the page gets smaller and some elements which were side by side are now under each other. Also  image sizes drop and small amounts of other image content are dropped all together.

What I think what happens when the screen gets resized to less than 550px is that the media queries are no longer applied as the site is designed to be mobile-first. So when the screen gets smaller the styles applied by the larger media queries no longer have effect.
