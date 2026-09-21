# Awesome Rebind

Extensions and companions for [Rebind](https://github.com/equwal/rebind), the
button remapper for e-ink readers and any Android 12+ device.

An extension is an app of its own. Rebind puts it on a hardware button. The
build of Rebind for direct install carries most of them and installs them when
you ask.

## Contents

- [Core](#core)
- [Extensions by the maker of Rebind](#extensions-by-the-maker-of-rebind)
- [Apps of other makers that Rebind carries](#apps-of-other-makers-that-rebind-carries)
- [Works well with Rebind](#works-well-with-rebind)
- [Actions to bind](#actions-to-bind)
- [Add an extension](#add-an-extension)

## Core

- [Rebind](https://github.com/equwal/rebind) - Remaps volume keys, the Power
  button, page-turn buttons, the Viwoods AI key and an on-screen button. Tap,
  double tap, triple tap, hold and two-button combinations. Free beta APK.

## Extensions by the maker of Rebind

- [Ink Recents](https://github.com/equwal/ink-recents) - A recent-apps switcher
  drawn for e-ink. One card for each swipe with no glide. Swipe up closes an
  app. Swipe down closes all the others. GPL-3.0. *In Rebind.*
- [Ink Dim](https://github.com/equwal/ink-dim) - Tap to set the frontlight of
  a Viwoods AiPaper reader below the lowest level of the system. Tap again to
  go back. Needs Shizuku. GPL-3.0.

## Apps of other makers that Rebind carries

Rebind carries the release file of the maker, not changed, and hands it to the
installer of Android. Android asks you first. Rebind downloads nothing.

- [inkOS](https://github.com/gezimos/inkOS) - A text home screen made for
  e-ink. GPL-3.0. *In Rebind.*
- [ThinkLauncher](https://github.com/MatiasDesuu/ThinkLauncher) - A minimal
  home screen made for e-ink. GPL-3.0. *In Rebind.*
- [Whisper](https://github.com/woheller69/whisperIME) - Speech to text on the
  device, with no cloud. It does the listening for the Voice typing action of
  Rebind. MIT. Also on [F-Droid](https://f-droid.org/packages/org.woheller69.whisper/).
  *In Rebind.*

## Works well with Rebind

- [CLauncher](https://github.com/mlm-games/CLauncher) - A minimal text home
  screen. GPL-3.0. Rebind carried it up to 0.0.12.
- [Shizuku](https://github.com/RikkaApps/Shizuku) - Gives an app a shell with
  no root and no computer. With it, Rebind gets every press of the Power
  button and can switch the navigation bar and gestures. Ink Recents and Ink
  Dim use it too. Apache-2.0.

## Actions to bind

In Rebind: set up a button, choose **Advanced**, then **Send an intent action**, and
type the action. An extension that is *In Rebind* has a ready action and needs
none of this.

| Extension | Intent action | What it does |
|---|---|---|
| Ink Recents | `dev.equwal.inkrecents.OPEN` | Opens the recent-apps cards |
| Ink Dim | `dev.equwal.inkdim.TOGGLE` | Lowest light, or back to the system level |
| Ink Dim | `dev.equwal.inkdim.ON` | Lowest light |
| Ink Dim | `dev.equwal.inkdim.OFF` | Back to the system level |

## Add an extension

Open an issue or a pull request. An extension fits the list when:

- it is an app of its own that does one thing;
- a button can start it: it has a launcher icon or an exported intent action;
- it is useful on an e-ink reader: no animation is needed to use it;
- its source code is public, or its maker is named and the download is from
  the maker.

## Say thanks

Rebind, Ink Recents and Ink Dim are made by one person. If they made your
device better, you can [buy me a coffee](https://ko-fi.com/truex).
