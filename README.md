Phonegap_skeleton_android
=========================

These are all base files and styles needed to create a very native-looking Android application with Phonegap Build.

 * Slide-out menu with the three-lines like the modern google apps.
 * Colors follow the design guidelines.
 * Google's "roboto" fonts.
 * Functioning "back" button (rare in Phonegap apps).
 * Components of a "card" UI.
 * Hardware accelerated CSS 3 animations (So NO lag)
 * Fully customizable.
 * Commented.
 * Seriously, this looks and acts native.

.


To understand some of the code I have in here, you will need to know:
 * Font awesome: http://fortawesome.github.io/Font-Awesome/
 * Transit JS: http://ricostacruz.com/jquery.transit/
 * Jquery
 * JQuery Mobile
 * Phonegap API


.

You should be able to figure out the code by looking at it; I commented the entire thing and named my clsses and IDs accordingly.

If you have any problem figuring something out, shoot me an email at mitch@mitchs.co.

If you end up publishing an app from my source, let me know!

.

When making an app with Phonegap, there are a few things to remember:
 * Stay away from images. The more images, the slower the app.
 * Use CSS3 Animations instead of Jquery. Jquery slows it down. That's why I'm using Transit. Css is hardware accelerated, jquery is not.
 * Do not use links, and do not use onclick. Use the tap detection from Jquery Mobile that you can see in use in the index file.
 * Do not use Alerts or Prompts or any Javascript crap like that. Since Phonegap builds it as a gingerbread style app, the prompts will look gingerbread styled, and will look like crap. Make your own alert boxes, even though its more work.
