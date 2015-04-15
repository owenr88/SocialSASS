# SocialSASS
This is a collection of SASS styles to pimp out your social icons. The correct colours are included with each social icon (list available in "core/social-networks.scss").

The styles also offer a variety of ways to display the icons. See the examples below for these classes.

##Usage

Include the social-sass.scss in your project and use the add-on Font Awesome classes as om the examples below.

`@import "SocialSASS/social-sass.scss"`

[Font Awesome](http://fortawesome.github.io/Font-Awesome/) SASS files are also included, but you can delete them if you've already included them in your project. Don't forget to remove the reference in social-sass.scss too!

View the social-networks.scss file for list fo social networks supported.

##Icon Examples

###Default Icon
`<i class="fa default fa-twitter"></i>`

Standard icons in the social network's color.

###Rounded Icon
`<i class="fa rounded fa-twitter"></i>`

Round icons with the social network's colour in the background.

###Rounded Icon on Hover Only
`<i class="fa rounded-hover fa-twitter"></i>`

Round icons with the social network's color applied to the background when hovered over. The base color can be changed in the social-icons.scss file.

##Details

Most of the social networks' colours were from the [Design Pieces article](http://designpieces.com/2012/12/social-media-colours-hex-and-rgb). Thanks for saving a load of searching!

Some of the mixins came from [Web Design Weekly](https://github.com/web-design-weekly/sass-mixins).