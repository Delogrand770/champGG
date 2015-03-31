# champGG
Downloads item sets from champion.gg to be used with a League of Legends client

The program contains the options to include (or exclude)

Most Frequent Builds, Highest Win% Builds, Starter Items, Consumables and Skill Order


# Setup

I use nwjs.io to have direct access to node.js from the dom. I won't provide the nw.exe that way you can download the original/safe version from the creators themselves.

1. Visit http://nwjs.io/ (formerly node-webkit) and download the version for your operating system.
2. Extract the archive
3. Download and extract the zip of this repoistory into the same directory the nwjs.zip was extracted to
4. The files you get from this repo are html/json and an image file so you can see everything that is happening

Note: Your extracted directory only needs to have app.html, nw.exe, icon.png, icudtl.dat, nw.pak and package.json

The nwjs.zip has some extra files (dlls, nwjc.exe, locales) in the zip but they aren't used for this application and can be deleted.

# Usage

1. Open the exe, choose what to include, click Download and it will start downloading the item sets if the champion.gg site can be reached and they haven't changed their code in a way that breaks the app.
2. Copy the folders with champion names from .\ItemSets\Date_AllSets\ to Your_League_Install_Directory\Config\Champions\
3. Play League!

# Will Riot ban me?

According to Reddit: A rioter did this originally, so it's safe. it doesn't affect gameplay, and you're not doing anything you couldn't do manually if you wanted to waste dozens of hours of your life every patch. Go wild!

http://www.reddit.com/r/leagueoflegends/comments/2z7hkw/championgg_item_sets_updated_for_patch_55/cpgm2ws

# Credits

Original PHP script by ebildude123 - https://github.com/ebildude123/champion.gg-item-set-creator

Item set data provided by https://champion.gg/


# Setup is too complex, just give me the files

Most browsers will give a warning that this zip could be dangerous since it contains an exe file.

https://dl.dropboxusercontent.com/u/5135312/champGG_.zip
