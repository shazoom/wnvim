# wnvim
An Applescript applet which launches Neovim in Terminal.app or iTerm2.app.  It is designed to integrate Neovim into GUI tools which can open files in your prefered editor from the Finder.

## Requirements
Neovim, any version.

or

Any other editor if you edit the script. Nvim only appears 4 times; I probably should have put the executable name in its own variable... but I didn't.

## Using it
Once you've dropped the script into wherever you want to install it you need to execute it once (double click on it in the finder) and select which terminal you want to use to run the editor in.

Then it needs to be associated with a file. In the Finder select the file you want to associate with *wnvim* and press ⌘-I to open the *Get Info* dialog and change the association in the normal way. Once you are happy the script works correctly you may want to use the *change all* button in the *Get Info* dialog.

You can open the file in nvim by double clicking an associated file. 

## Further Details
It has run and open handlers. Opening it allows Terminal or iTerm to be chosen (iTerm works better out of the box; it closes automatically when nvim exits,) your choice will be saved in the preferences directory in you home directory using ApplescriptObjc to access the Foundation framework.  wnvim.app can be selected in Finder, and as default application. Works well with applications, such as,: Devonthink and Marked.

You can get Terminal.app to exit after its shell closes too, by changing this setting.

![Terminal.app option](http://i.imgur.com/qNHuDC5.png)


It only works with versions of iTerm which have the newer API and the stock terminal app. You will, I expect, have to change the **Allow apps downloaded from:** setting in **Security & Privacty** to **Anywhere**. This is the first time I have published an application for OS X so it would be great if someone could confirm this for me.

Click on |Clone or Download| and select |Download Zip| to download the app.
