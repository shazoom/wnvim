# wnvim
An Applescript applet which launches Neovim in Terminal.app or iTerm2.app.  It is designed to integrate Neovim into GUI tools which can open files in your prefered editor.

It has run and open handlers. Opening it allows Terminal or iTerm to be chosen (iTerm works better out of the box; it closes automatically when nvim exits,) your choice will be saved in the preferences directory in you home directory using ApplescriptObjc to access the Foundation framework.  wnvim.app can be selected in Finder, and as default application. Works well with applications, such as,: Devonthink and Marked.

You can get Terminal.app to exit after its shell closes too, by changing this setting.

![Terminal.app option](http://i.imgur.com/qNHuDC5.png)


It only works with versions of iTerm which have the newer API and the stock terminal app. You will, I expect, have to change the **Allow apps downloaded from:** setting in **Security & Privacty** to **Anywhere**. This is the first time I have published an application for OS X so it would be great if someone could confirm this for me.

Click on |Clone or Download| and select |Download Zip| to download the app.
