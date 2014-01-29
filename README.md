jquery.scrollToTop
==================
Plugin allows to setup scrollers to top, to bottom and back to position you were before

Setup:
-------------------------

1. Include necessary JS files

	```
	<script src="jquery.min.js"></script>
	<script src="js/jquery.totop.js"></script>
  	```

2. Add scrollToTop CSS file

	```
	<link rel="stylesheet" href="css/totop.css" />
	```

3. Create a div element

	```
	<div id="totopscroller"></div>
	```

Usage:
-------------------------

	```
	$(function(){
        $('#totopscroller').totopscroller();
    })
	```

Options:
-------------------------

Option | Default | Description
---|---|---
showToBottom | `true` | Enable button that scroll to bottom of page
showToPrev | `true` | Enable button that scroll back to previous position on page after scrolling page to top/bottom
link | `false` | If passed a link than appears button with this link under "to top" button
linkTarget | `_self` | Where link will be opened. Same window (_self) or new window (_blank)
toTopHtml | `<a href="#"></a>` | Custom html of to top button
toBottomHtml | `<a href="#"></a>` | Custom html of to bottom button
toPrevHtml | `<a href="#"></a>` | Custom html of to previous position button
linkHtml | `<a href="#"></a>` | Custom html of link button
toTopClass | `totopscroller-top` | Class of to top button
toBottomClass | `totopscroller-bottom` | Class of to bottom button
toPrevClass | `totopscroller-prev` | Class of to previous position button
linkClass | `totopscroller-lnk` | Class of link button