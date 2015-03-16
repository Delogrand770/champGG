# champGG
Downloads item sets from champion.gg to be used with a League of Legends client


# Can I be sure you aren't hacking me?

Yes you can (well at least from the compiled code)

1. Visit http://nwjs.io/ (formerly node-webkit) and download the version for your operating system.
2. Extract the archive
3. Download and extract the zip of this repoistory into the same directory the nwjs.zip was extracted to
4. The files you get from this repo are html/json and an image file so you can see everything that is happening

Note: Your extracted directory only needs to have app.html, nw.exe, icon.png, icudtl.dat, nw.pak and package.json

The nwjs.zip has some extra files (dlls, nwjc.exe, locales) in the zip but they aren't used for this application and can be deleted.

# Usage
1. Open the nw.exe, it will start downloading the item sets if the champion.gg can be reached.
2. Copy the folders with champion names from .\ItemSets\Date_AllSets\ to Your_League_Install_Directory\Config\Champions\
3. Play League!
