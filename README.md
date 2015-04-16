# SocialSASS
This is a collection of SASS styles to pimp out your social icons. The correct colours are included with each social icon (list available in "core/social-networks.scss").

The styles also offer a variety of ways to display the icons. See the examples below for these classes.

##Usage

Include the social-sass.scss in your project and use the add-on Font Awesome classes as in the examples below.

`@import "SocialSASS/social-sass.scss"`

[Font Awesome](http://fortawesome.github.io/Font-Awesome/) SASS files are also included, but you can delete them if you've already included them in your project. Don't forget to remove the reference in social-sass.scss too!

View the social-networks.scss file for list fo social networks supported.

##Icon Examples

###Default Icon
`<i class="fa default fa-twitter"></i>`

Standard icons in the social network's color. The color is slightly darkened on hover.

###Default Icon - Spins on hover
`<i class="fa default-spin fa-flickr"></i>`

Standard icons in the social network's color. The icon spins and the color darkens slightly on hover.

###Rounded Icon with Background Color
`<i class="fa rounded fa-facebook"></i>`

Round icons with the social network's colour in the background.

###Rounded Icon with Background Color - Spins on hover
`<i class="fa rounded-spin fa-youtube"></i>`

Round icons with the social network's colour in the background which does a little spins on hover.

###Rounded Icon - Background Color on Hover Only
`<i class="fa rounded-hover fa-vimeo-square"></i>`

Round icons with the social network's color applied to the background when hovered over. The base color can be changed in the social-icons.scss file.

###Rounded Icon - Background Color corrects and icon spins on hover
`<i class="fa rounded-hover-spin fa-instagram"></i>`

Round icons with the social network's color applied when hovered over, at the same time as spinning. The base color can be changed in the social-icons.scss file.

##Details

Most of the social networks' colours were from the [Design Pieces article](http://designpieces.com/2012/12/social-media-colours-hex-and-rgb). Thanks for saving a load of searching!

Some of the mixins came from [Web Design Weekly](https://github.com/web-design-weekly/sass-mixins).