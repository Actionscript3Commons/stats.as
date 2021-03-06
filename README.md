stats.as
========

#### Actionscript Performance Monitor ####

[![Flattr this](http://api.flattr.com/button/button-compact-static-100x17.png)](http://flattr.com/thing/20491/stats-as)

This class provides a simple info box that will help you monitor your code performance.

* **FPS** Frames per second, how many frames were rendered in 1 second. The higher the number the better.
* **MS** Milliseconds needed to render a frame. The lower the number the better.
* **MEM** Memory your code is using, if it increases per frame is VERY wrong.
* **MAX** Maximum memory the application reached.

### Screenshot ###

![stats_as.png](http://github.com/mrdoob/stats.as/raw/master/assets/stats_as.png)

### Usage ###

	addChild( new Stats() );

### Controls ###

* **CLICK** Top-half / bottom-half part of the panel to increase/decrease the FPS of the application.

### Download ###

[Stats.as](http://github.com/mrdoob/stats.as/raw/master/src/net/hires/debug/Stats.as)  
[Stats.hx](http://github.com/mrdoob/stats.as/raw/master/src/net/hires/debug/Stats.hx) (Ported by [David Wilhelm](http://github.com/bigfish))
