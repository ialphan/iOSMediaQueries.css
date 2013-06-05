#iOSMediaQueries
CSS Media Queries for iOS devices.

Demo: [demo.html](https://github.com/ialphan/iOSMediaQueries.css/blob/master/demo/demo.html) in [demo](https://github.com/ialphan/iOSMediaQueries.css/tree/master/demo) directory, demonstrates different backgrounds for each device and orientation. Make sure you try this in an iOS simulator or an actual device.

<br>
##Supported iOS Devices
	iPad 1, 2, 3
	iPhone 1, 2, 3/3S, 4/4S, 5
	iPod touch 1, 2, 3, 4, 5

**Note:** Numbers are device generations.

<br>
##Usage
Each media query has a comment above stating which device that media query is targeting so, copy-paste.

<br>
##TextMate and Sublime Text Bundle (snippet) (suggested)
**Installation:** Double click on iOSMediaQueries.tmbundle to install it for TextMate and move iOSMediaQueries directory to your Sublime Text 2's Packages directory.
**Usage:** Type the desired device name then press tab, it will generate the desired media query and place the cursor inside the block. **Note:** CSS(or mCSS) or HTML(or mHTML) file extensions must be selected in TextMate.

** Device names:**

	iPad 1, 2, 3 (ipadp, ipadl, ipad3p, ipad3l)
	iPad Mini (ipadminip, ipadminil)
	iPhone 1, 2, 3/3S, 4/4S, 5 (iphonep, iphonel, iphone4p, iphone4l, iphone5p, iphone5l)
	iPod touch 1, 2, 3, 4, 5 (ipodp, ipodl, ipod4p, ipod4l, ipod5p, ipod5l)

<br>

	Ex. iphone5p →

	@media all and (max-device-width: 640px) and (max-device-height: 1136px) and (orientation: portrait) and (-webkit-min-device-pixel-ratio: 2) {
		/* iPhone5 Portrait specific CSS */
	}

<br>
##License
See the LICENSE file.

<br>
##Language
CSS.

<br>
##History

**v0.1.2 - 2013-05-21**

  * Added iPad Mini media queries.
  * Added Sublime Text snippets.

***

**v0.1.1 - 2012-09-12**

  * Added iPhone 5 and iPod 5 media queries (portrait and landscape).

***

**v0.1 - 2012-09-05**


* Added media queries (portrait and landscape)for:
  * iPad 1, 2, 3
  * iPhone 1, 2, 3/3S, 4/4S
  * iPod touch 1, 2, 3, 4