#iOSMediaQueries
CSS Media Queries for iOS devices.

Demo: [demo.html](https://github.com/ialphan/iOSMediaQueries/blob/master/demo/demo.html) in [demo](https://github.com/ialphan/iOSMediaQueries/tree/master/demo) directory), demonstrates different backgrounds for each device and orientation.

<br />
##Supported iOS Devices
	iPad 1-2-3
	iPhone 1-2-3-3S-4-4S
	iPod touch 1-2-3-4
	
**Note:** Numbers are device generations.

<br />
##Usage
Each media query has a comment above stating which device that media query is targeting so, copy-paste.

<br />
##TextMate Bundle (snippet) (suggested)
Type the desired device name then press tab, it will generate the desired media query and place the cursor inside the block. **Note:** CSS(or mCSS) or HTML(or mHTML) file extensions must be selected in TextMate. 

** Device names:**

	iPad 1-2-3 (ipadp, ipadl, ipad3p, ipad3l)
	iPhone 1-2-3-3S-4-4S (iphonep, iphonel, iphone4p, iphone4l)
	iPod touch 1-2-3-4 (ipodp, ipodl, ipod4p, ipod4l)

<br />
	
	Ex. iphone4p →
	
	@media all and (max-device-width: 640px) and (max-device-height: 960px) and (orientation: portrait) and (-webkit-min-device-pixel-ratio: 2) {
		/* iPhone4 Portrait specific CSS */
	}

<br />
##License
See the LICENSE file.

<br />
##Language
CSS.

<br/>
##History

**v0.1 - 2012-09-05**


* Added these properties:
  * iPad 1-2-3
  * iPhone 1-2-3-3S-4-4S
  * iPod touch 1-2-3-4