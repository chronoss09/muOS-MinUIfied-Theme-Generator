BEFORE DOING ANYTHING MAKE A BACKUP of your Catalogue Folder on your muOS SD Card

In order to use the program you will need:
 - python 3 intalled and added to path. version 3.12 (older versions may work but I haven't tested them)
 - run 'python --version' in your command line and make sure it gives you 3.12, or whatever version you want to use with it. ( if this shows a python 2 version, try running 'python3 --version', this means you have to run pip3 when installing pillow)
 - pillow installed ( run 'pip install pillow' / 'pip3 install pillow' in your command line )

To use the program:
 - Run the Custom MinUI Theme Generator.py python script with python 3 ( right click it, open with - python )
 - Put your muOS SD Card into your computer
 - make sure the Roms Directory, Catalogue Directory, and Themes directory are set correctly
 - If you just want your consoles to have the theme applied, press Generate Images.
 - If you also want to theme the rest of your system:
   - If you are running muOS 2405 do not select Ko-Fi Early Access Version of muOS, otherwise choose that option.
   - If you want the horizontal look on the home scree, select that, otherwise leave it and it will be more similar to the original MinUI
   - Then press Generate Theme, This will generate the theme and put it in your theme folder, along with the preview image, so no need for Archive Manager!
   - You can now select the theme in muOS and everything should work!
 - Now you can put your SD Card back into your device, in order to get everything working with the game/console list make sure that in general - interface options, Content Box Art is set to Middle + Front

If you want to experiment with adding the theme to your games list please note the down sides:
 - You will lose all your game art if you don't back up your catalogue folder
 - The Favourites and History menus in muOS Will be messed up if you use them, they will look a mess.

If both those things are okay with you, 
 - Select 'Also Generate Images for Game List'
 - It will promt you to select, from a drop down, which system the folder is associated with. This is needed as muOS allows any folder names.
 - BE PATIENT, If you have loads of ROMS This will take a while, and right now there is no loading bar

If you wish to remove all MinUI from your system:
 - Choose a different theme in muOS
 - Go back to this tool and put in your catalogue folder and press 'Remove all images in Selected Catalogue Folder'
     - Again note that this will also remove any box art you have in there
     
Feel free to experiment with it and request any features and I'll look into adding them!#   m u O S - M i n U I f i e d - T h e m e - G e n e r a t o r  
 