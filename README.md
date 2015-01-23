#Image Text Hybrid (aka JS Image Text Box):
###Author: Dean Mercado

####What it does:

  'imgTxtHybrid()' is a jQuery plugin function that enables one to take a jQuery object and turn it into both a simple text editor AND an image canvas.

  Images can be dragged and dropped into the text-editor/canvas, and then dragged and resized while on display.

  The entire code base for the above function is in this repository, with the exception of jQuery (v 1.11.1) and jQuery-UI (v 1.11.2). 

####Usage Example/Requirements:

######Requirements:
* jQuery 
* jQuery-UI

######HTML Example:
```
   <!DOCTYPE html> 
   <html>
   		<head>
   			<link href='./css/style.css' rel='stylesheet' type='text/css'/>
				<link href='./css/jquery-ui.min.css' rel='stylesheet' type='text/css'/>
				<script src='./js/jquery-1.11.1.min.js' type='text/javascript'>
				</script>
				<script src='./js/jquery-ui-1.11.2.custom/jquery-ui.min.js'type='text/javascript'>
				</script>
				<script src="./js/img-txt-hybrid.js" type='text/javascript'></script>
				<script>
					  $('#editBox').imgTxtHybrid();
				</script>
   		</head>
   		<body>
   			<div id='editBox' style='width:400px; height:300px; border: 1px dotted blue'>
   			</div>
   		</body>
   </html> 
```
######CURRENT FEATURES:
* Support for copy-pasting images from the Web
* "         " drag-and-dropping images from local file folders
* Image interactivity (images can be dragged, resized, and deleted)
* Tab-whitespace enabled (pressing TAB produces extra whitespace)


