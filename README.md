Get RID of Chrome NEW TAB Page
=============

Judging by a Google search, it seems a LOT of people are rather unimpressed with the new NEW TAB page.  Me included.

So here is a little routine that can BANISH that messy page from hell and replace it with something you like.

Firstly create a directory newtab (or sumptin)

Inside it you are going to create a file called

manifest.json - in it
````
{ 
	"manifest_version": 2, 
	"name": "StupidBoxes", 
	"version": "1.0", 
	"description": "Improving GOOGLE", 
	"chrome_url_overrides" : { 
		"newtab": "newtab.html" 
	} 
}
````
That's mine, you get the idea.

then create your own newtab.html. Here is mine
````1
<html>

	<head>
		<title>Addinall's Override TAB Page</title>

		<style>
		body {
			background-image: url('images/cerebus-newtab.jpg');
			background-repeat: no-repeat;
			background-position: center;
			background-size: cover;
			width: 100%;
			height: 100%;
		}

		</style>
	</head>

	<body>
	</body>

</html>
````

You can stick whatever you fancy in your newtab page now. The omnibar up the top still does a Google search.

Then go to Extensions. Load unpacked extensions in Developer mode, and you are up and away!

## Mark Addinall

