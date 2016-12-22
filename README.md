ViewInspector-Plugin-for-Xcode
=======================

Plugin for Xcode to integrate the Reveal and Spark Inspector to your project automatic(Without any modifications to your project).

## Introduction

**The ViewInspector Plugin works just like Instruments.**

![ProductMenu](https://github.com/shjborage/Reveal-Plugin-for-Xcode/raw/master/Product-InspectWithReveal.png)

![DebugMenu](https://github.com/shjborage/Reveal-Plugin-for-Xcode/raw/master/Debug-AttachToReveal.png)

## Plugins upgrade for new Xcode
可以使用 https://github.com/dhcdht/XcodeHelper 管理和自动升级插件

## Issue
*	When using `Inspect ith Reveal`, if your simulator can't lanuch within 5 seconds, it's will alert an error. Thus, you can alse use Debug->`Attach to Reveal` after your app launched.

* If the plugin is not successfully loaded, it's possible your Xcode version is not supported, Add the build UUIDs for the versions of Xcode you wish to support to `DVTPlugInCompatibilityUUIDs` in `Info.plist`.

	You can get the UUID with this command `defaults read /Applications/Xcode.app/Contents/Info DVTPlugInCompatibilityUUID`, run it in termial.

## Contributors

Welcome to fork and PullRequest to do this better.
We use issues to manage bugs and enhanced features.

## Thanks
	
+	[Integrating Reveal without modifying your Xcode project](http://blog.ittybittyapps.com/blog/2013/11/07/integrating-reveal-without-modifying-your-xcode-project/)
+	[Xcode 4 插件制作入门](http://onevcat.com/2013/02/xcode-plugin)
+	[Reveal-Plugin-for-Xcode](https://github.com/shjborage/Reveal-Plugin-for-Xcode)
