MJPEG-Video_Webcomponent
=========

This project provides a robust video player component for modern browsers that plays MJPEG video streams. No plugin's required.

The < video> tag in HTML5 is nice and all, but they totally left out MJPEG. This fixes that.

Features:

* Automatic resume from loss of connectivity
* Loss of video stream detection
* Fullscreen mode
* 500%+ performance improvement over native browser < IMG> tag solution

Built on:

* [HTML5 webcomponents](http://webcomponents.org/)
* [polymer](http://www.polymer-project.org/)

Installation
---------

```
bower install mjpeg-video-webcomponent
```

Usage
---------

```
<mjpeg-video src='<url of mjpeg stream>' style='width: 1280px; height:720px'></mjpeg-video>
```

Refer to the example/index.html file for detailes.

Contributing
---------

The most obvious things this project needs support with:

1. Testing on multiple browsers
2. Submitting pull requests for improvements
3. Unit tests


To setup a development environment:

**please note: The bower install of the subcomponent will install one folder below so that the dependencies are at the
same folder level of this project so that the relative paths to those dependencies work.**

```
clone https://github.com/BrianAdams/openrov-mjpeg-video-webcomponent
cd openrov-mjpeg-video-webcomponent/example
bower install
```
go ahead and modify the index.html file to have the address of your video stream and load the page.  As you need to
make changes, you can simply run bower install again to pull in your updates in to the example project for testing.
