``icons``: App icons
====================

The ``icons`` configuration allows you to define the icons to be used for
your app.

All icons are square, and must be placed in your ``src``
directory. Paths to your icons should be specified relative to your `src` directory.

> ::Note:: If you specify *any* icons for a particular platform, you **must**
specify all required icons! iOS includes a special ``prerendered`` option, setting this to true
will stop iOS from applying the gloss effect to your icons.

> ::Important:: Use PNG format for your icons, as it is required on at least iOS and your app
may not be submittable otherwise.

##Config options

###Android

36, 48, 72
: 	Paths to various icons used to represent your app (all required), relative to your `src` directory.
	The numbers represent the height/width of the icon in pixels.

###iOS

57, 72, 114, 144
: 	Paths to various icons used to represent your app on an iOS device (all required), relative to your `src` directory.
	The numbers represent the height/width of the icon in pixels.

512
:	Path to an icon used to represent your app in iTunes.

Prerendered
: 	Setting this to true will stop iOS from applying the gloss effect to your icons.