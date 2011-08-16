Aurum CSS
by Víctor González
http://victtor.com

This work is licensed under the Creative Commons Attribution 3.0 Unported License.
To view a copy of this license, visit http://creativecommons.org/licenses/by/3.0/
or send a letter to Creative Commons, 444 Castro Street, Suite 900, Mountain View,
California, 94041, USA.


Aurum CSS is a bunch of rulers and functions to help designers using dynamic CSS such as LESS and SASS (coming soon). You can use it to space your websites and have font sizes perfect all the times.
Also you can modify all the sizes and widths proportionally at any time just adjusting your layout width. Great for media queries!!!


Disclaimer:
This was not designed to be your final CSS framework, just to
assess your spacing and proportion needs. If you are looking
for a good CSS grid, this is not for you. Blueprint, 960, 1140, or
some others might help.
This was thought for those designers that like to design lean and media-queried, no
extra BS, no extra classes. Aurum CSS also incudes some functions to
help CSS3 without writing miles of code to support IE and older
browsers.

First steps:
Edit this file and then import it with less, or adapt it to SASS (coming soon).
If you prefer smaller or no decimals at all in your final CSS, use this:
http://www.javascriptkit.com/javatutors/round.shtml
```
width: ~`Math.round(@{800_width1})`; // 494.40 px
width: ~`Math.round(@{800_width1}*100)/100`; // 494 px
```

I do suggest you to use Paul Irish's HTML5 Boilerplate for some things, included
in the style.less file.
If you prefer not to use the Boilerplate HTML5 CSS file, you'll just need a
reset. Consider YUI reset.
For developing use the complete LESS via JS and watching the main file:
less.env = "development";
less.watch();

For deploying I suggest minifying with the LESS app.

Happy CSSing!