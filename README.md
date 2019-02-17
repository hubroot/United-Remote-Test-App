Proposal
--------------

First, we need to make 2 linear branches
The first branch, will be a static html/css/js which contains the app code without any 
MVM libraries or build set up.

- Css
	- reset.css
	- main.css
	- responsive.css
- Js
	- main.js
	- scroller.js

- Images
	
- index.html



The second branch, will have a build setup and a compîlable css source code with customizable variables.

Structure
-------------

- Main
	- Header
		- Logo container
			- Logo Image
			- Logo Title
		- Scroller Controllers
			- Play button
- Articles 
	- List
		- Item
			- Image
			- Video
			- Text
	- Scroller
		- container
			- eclapsed 
- Footer 
	- Title
	- CopyRight


Vuejs
-------------
- Make reusable components
- Make static data-source
- Make build setup to compile the project

Variables
-------------
- article_width = px/em
- auto_grow = true/false : in case an image has less pixels, the image will not be self-enlarged, but it will stay as is, may be a js code will detect the color palette of that image
and make a nice linear/circular gardient as a background
the other case is if the image is very large, the image will not be zoomed out, but we'll display an cropped portion of it.
 

Scroller
------------
The scoller JS file will detect the article width, and see if the current device width is 2 times it.
if that's the case then the scroller will appears.
Otherwise it'll not appear.