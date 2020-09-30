# Autodesk® Stingray HTML5 plugin

***DISCLAIMER:*** This plugin is a **testbed** for [Stingray plugin extensibility framework](http://help.autodesk.com/view/Stingray/ENU/?guid=__sdk_help_introduction_html) and has no intention of being a good 2D UI framework and it's not meant to be a replacement for the 2D UI framework for Stingray.

Stingray supports HTML5 and all compliant browsers, so that you write once and it will run on any browser; desktop, tablet, smartphone etc. HTML5 development can improve navigation and provides more features, e.g. it allows; ... Geolocation, navigation and positioning. The use of multiple-threads.

Render HTML5 views in Stingray. The engine plugin uses [CEF](https://bitbucket.org/chromiumembedded/cef) to render HTML5 content to texture buffers. Once the texture buffers are generated, the render resource is assigned to the view's material `html5_texture` slot.
