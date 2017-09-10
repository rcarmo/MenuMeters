# MenuMeters

This is a fork of [Raging Menace's MenuMeters][mm] for Sierra/High Sierra, attempting to merge fixes from active branches besides `@yujitach`'s because I rely on it daily and want to keep it alive.

Mind you, this is **EXPERIMENTAL**. Refer to [the original repo][original] for issues and "official" fixes.

# Usage

If you just want to use it, please get [Yuji Tachikawa's prebuilt binaries][bin] instead. Please note that you may have to logout/login (or maybe reboot) to enable the new version, which (like the previous ones) works as a Preference Pane.

# Background

This fork was started by Yuji Tachikawa in July 2015 because the original version didn't work on `El Capitan`, since `SystemUIServer` stopped supporting third-party Menu Extras (i.e., anything not signed by Apple). Yuji replaced the `NSMenuExtra`s with `NSStatusItems`, and decided to [make his source available][original].


# Hacking

Clone the `git` repo, open `MenuMeters.xcodeproj`, and build the target `PrefPane`. This should install the pref pane in your `~/Library/PreferencePanes/`. (You might need to manually remove older versions).

[mm]: http://www.ragingmenace.com/software/menumeters/
[bin]: http://member.ipmu.jp/yuji.tachikawa/MenuMetersElCapitan/
[original]: https://github.com/yujitach/MenuMeters
