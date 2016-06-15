# Image Slider
Basic image slider using jQuery


##Description
This simple plugin helps you centralize your DOM element against their parent element or the window. 

## Demo
 - Please see demo/demo.html


## Requires
  - jQuery 1.2.6+



## Browser Compatibility
  - [Firefox](http://mzl.la/RNaI) 2.0+
  - [Internet Explorer](http://bit.ly/9fMgIQ) 6+
  - [Safari](http://bit.ly/gMhzVR) 3+
  - [Opera](http://bit.ly/fWJzaC) 10.6+
  - [Chrome](http://bit.ly/ePHvYZ) 8+



## Installation
  - First, make sure you are using valid [DOCTYPE](http://bit.ly/hQK1Rk)
  - Include nessesary JS files from js folder

<!-- -->

      <script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.5.1/jquery.min.js"></script>
      <script type="text/javascript" src="path-to-file/jQuery.anyElementCeneter.js"></script>



## Options

#### speed
  - description: sliding or transition speed
  - data type: integer
  - default value: 1000
  - possible value: any integer value

#### pause
  - description: pause time before transition  or sliding
  - data type: integer
  - default value: 2000
  - possible value: any integer value

#### transition
  - description: transition method
  - data type: string
  - default value: 'slide/fade'
  - possible value: 'slide/fade'

#### imgheight
  - description: images height
  - data type: integer
  - default value: 400
  - possible value: any integer value

#### imgwidth
  - description: images width
  - data type: integer
  - default value: 800
  - possible value: any integer value


## Usage
> Example code:

      // centralize #some-element against the window
      $('#imgSlider').imgSlider({
      speed:1000,
			pause:2000,
			transition:'slide',
			imgheight:400,
			imgwidth:800
		});


## License

The expandable plugin is licensed under the MIT License (LICENSE.txt).

Copyright (c) 2011 [Supun Sameera Liyanage](supun.sameera@live.com)
