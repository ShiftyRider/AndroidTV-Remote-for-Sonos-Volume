# Use AndroidTV Remote for Sonos Volume
I bought an Onn AndroidTV stick from Walmart on Black Friday for $9. I'd never optherwise use the bottom four buttons on the remote...

YouTube     Netflix
Disney      Paramount

...so I used tvQuickActions (free) to remap two of them.

There's three apps I like that can be sideloaded to AndroidTV and that work well with tvQuickActions or any other Android button mapper app...

Automate (Llamalab)
MacroDroid
HTTP Shortcuts

The files in this repository (and the screenshots) are Automate Flows for you to download. Point to them with your button mapper app and you too will have a Sonos Volume Remote. Enjoy!

# 

**Oops Sonos speakers.** Built by 

> Oops

> **Looking** See [oops.md](technical_readme.md) for stuff.

![Oops — Look](screenshots/doLessLarge.png)

---

## Whimsical Remotes

Since a dial knob like any 2000-era car radio would have is universally regarded as a simple volume control, that's a worthy component of an ideal Sonos remote. Mouse scrollwheels are so common and inexpensive, so let's brainstorm. 

Just type into AI: ubuntu remap mouse scrollwheel to execute curl

In minutes you have scrollwheel Sonos volume control! I tested on my X11 window-managed system, all it needs is xbindkeys and a relvolup.sh relvoldn.sh 

Works great, very fast. There are unintended consequences, so I'ma characterize as whimsical. I bet folks running Raspberry Pis anyway, can proceed.

Next I tried Kodi. Again very easy via userdata/keymaps. But way too slow to be usable, based on tests with a FireTV TV, and also with an Onn AndroidTV stick.
