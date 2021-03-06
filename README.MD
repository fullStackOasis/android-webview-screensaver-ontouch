# Android Project to view a simple web page and go to a screensaver after a short period without interactions

This Android app starts with a view of a simple web page. The web page has a little bit of JavaScript in it:

1. You can click a button, which then causes "Hello World!" to be printed to the screen.

2. A "stopwatch" timer prints an incremented number to the screen every second, starting from when the page loads.

The Android app has a screensaver - a short video that pops up if the user has not interacted with it for 10 seconds.

If the user clicks around on the app, the screensaver doesn't pop up. Once the user stops interacting with the app, there's a 10 second wait, and then the screensaver appears. The screensaver is a video of a flame.

The difference between this project and [android-webview-textinput](https://github.com/fullStackOasis/android-webview-textinput) is that this project starts with a WebView of a webpage, and that project starts with a regular `Activity` that has a `TextView` and nothing else.

![Android WebView goes to screensaver after 10 seconds of inactivity](https://raw.githubusercontent.com/fullStackOasis/android-webview-screensaver-ontouch/master/webview-screensaver-ontouch.gif)

The flame is an mp4 file which is licensed from https://archive.org/details/SlowMotionFlame "Slow Motion Flame by Sharuban" Under a creative commonds license https://creativecommons.org/licenses/by/3.0/us/
