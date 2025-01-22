# Interactive-Media-Player-KWGT
Craft your personalized music widget for your Android device! 🎵📱

Okay so hi everyone, it's my first attempt at making a custom music widget with button controls!!

Let's have a little chat and a background before going into the "technicalities" of the project!
So having an aesthetic and handy home screen was always on the list for me, and let's be honest, the default widgets provided by Spotify, YouTube music etc. never felt up to the mark.
So, this brought me to KWGT, or Kustom WidGeT as we know it. As the name suggests, it provides with ability to create fully functional widgets, from a simple clock to a complex atomic clock with functions on click, world clock and may others. 

Okay so enough of the chat, let's get to the cool part :)
Alongside attached is the mp4 tutorial file for those who don't like reading super long readme files!

So, let's start with the first step: adding an empty KWGT widget (add any dimension of the widget, you can resize it later don't worry!)
2. A little touch on the widget and you witness the cool ui of KWGT (it's just an old-looking layout don't be overwhelmed >.< )

So now you can load any of the preinstalled widget packs, and then remove all of the layers. (the user interface is usually easy to use if you're into video/photo editing or have ever done)

Let's start with the design part, in my case I have just used a simple layout with a rounded square base, rectangular album art and forward, previous and play/pause touch controls.
   •	BASE: insert a shape (by default square), adjust the width to make it fit the canvas completely. Now round the corners and DO NOTE THE VALUE OF CORNER ROUNDING! Add a cool colour to the shape (preferably black because it’s universally accepted :) )
  •	ALBUM ART ELEMENT: Insert a rectangle, adjust the dimensions to fit around ¾ of the base square, leaving enough space for the music control buttons.

Time to do some “so called” coding now! Head over to the rectangle shape, FX tab, followed by TEXTURE, select BITMAP. So, what this does is it allows for a high degree of customization and creativity in designing your home screen widgets. 

Now click on the calculator icon, it brings up a menu with various cover ideas to choose from, like music details, battery percentage, progress bars etc. Here we choose music info, and then select “current cover image”. What this does is that it assigns the album art of any currently playing media (thumbnails in case of YouTube videos)

Let’s add some minimal icons for previous, next, play/pause now!

Add a layer, “FontIcon”. As the name suggests, its basically a list of 4 different icon packs, choose anyone that feels good- looking, otherwise just add your own icons!!

Position all the icons appropriately in symmetry with other elements. (remember, a good layout is the key to a minimal and functional homescreen)

Time to add the touch controls for all widget we just made! Select any element you want to add touch controls for. Click on the plus (+) icon to add a control. Specify it as a music control, and select the function according to the icon selected. (here added an additional control which opens the music player when I click on the album art)

DON’T FORGET TO CLICK ON THE SAVE BUTTON EVERY NOW AND THEN OTHERWISE IT’S ALL GONE !!!
…and that’s how a custom  kustom widget for music activity is made using KWGT :) Hope you liked it !
