# Use AndroidTV Remote for Sonos Volume
I bought an Onn AndroidTV stick from Walmart on Black Friday for $9. I'd never otherwise use the bottom four buttons on the remote...

- YouTube
- Disney
- Netflix
- Paramount

...so I used tvQuickActions (free) to remap two of them.

There's three apps I like that can be sideloaded to AndroidTV and that work well with tvQuickActions or any other Android button mapper app...

- Automate (Llamalab)
- MacroDroid (but not recent versions)
- HTTP Shortcuts (Waboodoo)

The files in this repository (and the screenshots) are Automate Flows for you to download. Point to them with your button mapper app and you too will have a Sonos Volume Remote. Look within the flows for where the ip variable is set -- you'll need to modify that. Enjoy!

Also works on FireTV, where my tests were with a FireTV TV (not stick or box) and the Button Mapper (flar2) app. I gotta say the $9 Onn is pretty ideal tho -- once set up it can be standalone. It draws 1.7 Watts always-on, so who knows? You might have more Onns than you have TVs (cuz for example your kitchen and patio are more likely to have Sonos speakers than TVs).

## UPnP

My recommendation for understanding UPnP is to experiment with a UPnP Explorer app. For Android that's UPnP Explorer, if you're on iPhone I believe uPnP Mate would be your go-to.

## Whimsical Remotes

Since a dial knob (like any 2000-era car radio would have) is universally regarded as a simple volume control, that's a worthy component of an ideal Sonos remote. Mouse scrollwheels are so common and inexpensive, so let's brainstorm. 

Just type into AI: ubuntu remap mouse wheel to perform http request

In minutes you have Bluetooth Mouse Wheel Volume! I tested on my X11 window-managed system, all it needs is xbindkeys and a relvolup.sh and a relvoldn.sh (each would just be a one-line cURL command, check your AI you'll see).

Works great, very fast. There are unintended consequences, so I'ma characterize as whimsical. I bet folks running Raspberry Pis anyway, can proceed. Bluetooth mice are about $9 too, heh.

Next I tried Kodi. Again very easy via userdata/keymaps. But way too slow to be usable, based on tests with a FireTV TV, and also with an Onn AndroidTV stick.

Last but not least, did you know that the Spotify apps that smart TVs have don't really present the Spotify Connect functionality to the user? So it's kinda fun to sideload a phone version of Spotify to test. You guessed it! The phone versions cause your phone's volume buttons to be Sonos volume buttons. And the same tends to be true with your TV remote if that sideloaded Spotify is in the foreground of your TV. Woah! Even with the TV "off" in my case.

# [ignore but check back later]

**Oops Sonos speakers.** Built by 

> Oops

> **Looking** See [oops.md](technical_readme.md) for stuff.

![Oops — Look](screenshots/doLessLarge.png)

---
