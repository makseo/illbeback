# I'll Be Back
Scroll To Top Back Button ★ jQuery Plugin

How to use:
-------------------------

1. Include javascript

	```html
	<script src="jquery.js"></script>
	<script src="illbeback.min.js"></script>
  	```
  	
2. Create a button

	```html
	<a href="" id="scrollToTop"></a>
	```
	
3. Set plugin with button

	```javascript
	$(function() {
		$("#scrollToTop").illBeBack();
	});
	```
	
Config:
-------------------------

  ```javascript
  $(function() {
  	$("#scrollToTop").illBeBack({
  	
  	    // Parameters
        offset        : 250, // milliseconds
        speed         : 200, // milliseconds
        duration      : 500, // milliseconds
        hoverDuration : 300, // milliseconds

        // Styling
        ownStyle : false, // disable styling and use own
        round    : false, // make button round
        zIndex   : 1000,
        size     : 64, // width X height in px

        // Position
        top    : 'auto',
        left   : 'auto',
        bottom : 30,
        right  : 30,

        // Background
        bgColor : 'rgba(30, 30, 30, 0.4)',
        hoverBgColor : 'rgba(30, 30, 30, 0.8)',
        bgPosition : '50% 50%',
        bgSize : '50%',
        bgRepeat : 'no-repeat',
        bgImage : url([URL])
  	});
  });
  ```
	
Supports:
-------------------------

* Chrome, Firefox, Safari, Opera, IE7+

License:
-------------------------
Released under the [MIT license](http://opensource.org/licenses/MIT).

```

i'll be back
                       ______
                     <((((((\\\
                     /      . }\
                     ;--..--._|}
  (\                 '--/\--'  )
   \\                | '-'  :'|
    \\               . -==- .-|
     \\               \.__.'   \--._
     [\\          __.--|       //  _/'--.
     \ \\       .'-._ ('-----'/ __/      \
      \ \\     /   __>|      | '--.       |
       \ \\   |   \   |     /    /       /
        \ '\ /     \  |     |  _/       /
         \  \       \ |     | /        /
          \  \      \        /
```
