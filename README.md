<img src='https://raw.githubusercontent.com/zeroheight/library-styles-sync/master/images/cover.png'>

## Overview
Here's a Sketch plugin to sync shared text and layer styles from a Sketch Library into the current document.

### How do I use it?
* Insert a symbol from the library you want to sync the styles from
* Run the `Sync` command to load styles from that library

### How does it match styles?
By name
* if the style doesn't exist, it's created
* if it does exist, it's overwritten
  
### Does sync work both ways?
No, sync is only one-way (from Library to document). 

Any changes to your document's shared styles will get overwritten next time you run the plugin.

### Which Libraries does it sync from?
It syncs styles from any libraries that you've inserted a symbol from

## JSON (experimental / WIP)
* add URLs for color and typography JSON files
* sync those JSON styles as text styles

Apologies for poor docs on this - it's still a work-in-progress

### example JSON files
* https://git.zeroheight.com/robin/tokens/raw/master/colors.json
* https://git.zeroheight.com/robin/tokens/raw/master/typography.json

## Installation
**[Download](https://api.sketchpacks.com/v1/plugins/com.zeroheight.library-styles-sync/download)**, unzip and double click the `.sketchplugin`

or

<a href="https://sketchpacks.com/zeroheight/library-styles-sync/install">
	<img width="160" height="41" src="http://sketchpacks-com.s3.amazonaws.com/assets/badges/sketchpacks-badge-install.png" >
</a>

## Usage
* press `Control + Command + J`, or use the `Plugins` menu
### Example - first sync
<img src='https://d26dzxoao6i3hh.cloudfront.net/items/3R1F2D0T112U2Z3X000D/Screen%20Recording%202017-10-16%20at%2006.42%20pm.gif' width='700px'>

### Example - getting an update
<img src='https://d26dzxoao6i3hh.cloudfront.net/items/1R2L341g382t272v2X24/Screen%20Recording%202017-10-16%20at%2006.44%20pm.gif' width='700px'>

## Contact
Get in touch at robin#zeroheight.com, but use @ instead of # if you're not a 🤖

## License
Copyright (c) 2017 Zero Height Limited (zeroheight). See [LICENSE.md](https://github.com/zeroheight/library-styles-sync/blob/master/LICENSE.md) for further details.
