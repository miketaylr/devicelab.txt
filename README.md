# devicelab.txt

This is an experiment in distributed device testing.

If you need me to run a quick test on a browser on a device you don't have access to, but I have it in my devicelab.txt, open an issue on this repo. Let's define "quick" as something that would take less than 10 minutes.

You could maybe create your own devicelab.txt file too.

Discoverability [on the cheap](https://github.com/search?q=devicelab.txt&search_target=global).

### Inspiration

```
[14:47] <buritica> does anyone have both an ios device and an android on chrome above 17 here? If so, can you visit http://jsbin.com/oDIRoZuD/1/edit on both devices and try to scroll swiping on the yellow column, and then swiping on the orange column. pretty please?
[14:52] <miketaylr> buritica: ya i got you
[14:52] <miketaylr> one sec
[14:52] <buritica> miketaylr: thx
[14:53] <buritica> miketaylr: in theory, you should be able to scroll the article on both yellow and orange sections (not pink) because pointer events should be passing through. but it seems android doesn't like it
[14:53] <miketaylr> buritica: so test chrome on ios too?
[14:53] <buritica> yes pls
[14:53] erichynds joined the channel
[14:54] <miketaylr> one sec, installing
[14:57] <miketaylr> buritica: confirm. can scroll w/ orange/yellow in iOS, only yellow in Android
[14:58] <miketaylr> but not surprising... one is webkit webview, one is blink :/
[14:59] <miketaylr> (ok surprising that the webview doesn't screw it up)
[14:59] <buritica> miketaylr: thanks dude
```
