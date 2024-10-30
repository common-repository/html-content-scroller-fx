=== HTML Content Scroller FX ===
Contributors: flashxml
Tags: images, photos, widget, post, plugin, posts, sidebar, free, flash, html, css, content, scroller, text, image, scroll, animation, auto, effects, as3, xml
Requires at least: 2.8.0
Tested up to: 3.0.1
Stable tag: trunk

An advanced HTML Content Scroller. Fully XML customizable, without any Flash knowledge.

== Description ==

The HTML Content Scroller FX can be embedded in any website for free without any Flash knowledge. You can embed any font and the text is HTML/CSS formatted. It has mouse wheel scroll as well as auto scroll functionality. There are also many background and shade features. Other customizable properties are available on the Live Demo.

== Installation ==

Make sure your Wordpress version is greater than 2.8 and your hosting provider is using PHP5.

1. There are two files to download: [WordPress Plugin](http://downloads.wordpress.org/plugin/html-content-scroller-fx.zip "HTML Content Scroller FX Plugin") (that you have to install and activate) & [Free package](http://www.flashxml.net/free/download/html-content-scroller.zip "HTML Content Scroller FX")
2. Create a new folder inside your **wp-content** folder called **flashxml**, inside this folder create a new one called **html-content-scroller-fx** and copy the content of the **free package** there
3. If you copied the **free package** to a location different than the one above, go to **HTML Content Scroller FX** from the **Settings** tab in your **WordPress Dashboard** and update the path accordingly
4. Add `[html-content-scroller-fx][/html-content-scroller-fx]` where you want the Flash to show up in your post/page
5. If you want to make the HTML Content Scroller FX part of your theme, edit the template files and add `<?php htmlcontentscrollerfx_echo_embed_code(); ?>` where you want it to show up
6. Go to [FlashXML.net](http://www.flashxml.net/ "Free Flash Components") and [customize your HTML Content Scroller FX](http://www.flashxml.net/html-content-scroller.html "HTML Content Scroller FX") using the Live Demo. Generate the `settings.xml` text and use it to overwrite `wp-content/flashxml/html-content-scroller-fx/settings.xml`
7. To use your own text, update the `wp-content/flashxml/html-content-scroller-fx/assets/html/text.html` file accordingly

= Additional settings file =

To embed the HTML Content Scroller FX more than once, you will need another settings file. Let's assume your new file is called `settings2.xml`. Add `[html-content-scroller-fx settings="settings2.xml"][/html-content-scroller-fx]` where you want the Flash to show up in your post/page. If you made the Flash part of your theme, add the file name as **the first argument** of the `htmlcontentscrollerfx_echo_embed_code()` function call (for example `<?php htmlcontentscrollerfx_echo_embed_code("settings2.xml"); ?>`).

= No Flash support text =

To support visitors without Adobe Flash Player, you can provide alternative content by adding the text between `[html-content-scroller-fx]` and `[/html-content-scroller-fx]`. If you made the Flash part of your theme, add the text as **the second argument** of the `htmlcontentscrollerfx_echo_embed_code()` function call (for example `<?php htmlcontentscrollerfx_echo_embed_code("","Alternative content"); ?>`).

= If you have PHP4 =

To make it work with PHP4, add `[html-content-scroller-fx width="600" height="300"][/html-content-scroller-fx]` where you want the Flash to show up in your post/page. If you made the Flash part of your theme, add the width and height as **the third and fourth argument** of the `htmlcontentscrollerfx_echo_embed_code()` function call. Don't forget to provide your own width and height values, since 600 and 300 are just examples.

= Getting rid of the FlashXML.net label =

To remove the FlashXML.net label from the top-left corner you'll need to buy the [paid package](http://www.flashxml.net/html-content-scroller.html "HTML Content Scroller FX"). Once you'll do that, simply use the SWF file from the paid package to overwrite the SWF file from the `wp-content/flashxml/html-content-scroller-fx/` folder.

== Screenshots ==

1. The Live Demo on [FlashXML.net](http://www.flashxml.net/html-content-scroller.html "HTML Content Scroller FX") is the utility that helps easily customize your HTML Content Scroller FX to fit all your needs.