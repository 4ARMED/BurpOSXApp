# Installation

I will assume Burp version 1.5.21 but substitute commands below with correct version)

```bash
cd /Applications
git clone https://github.com/4ARMED/BurpOSXApp.git Burp.app
cd Burp.app/Contents/MacOS/
cp $WHEREVER_YOU_DOWNLOADED_TO/burpsuite_pro_v1.5.21.jar .
ln -s burpsuite_pro_v1.5.21.jar burpsuite_pro.jar
cd /Applications
open .
```

At this point a Finder window should open in the Applications folder, you should see Burp in the list, you can drag it your Dock if you wish.

