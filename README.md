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
  go back. Needs Shizuku. GPL-3.0. *In Rebind.*

- [Ink Update](https://github.com/equwal/ink-update) - Tells you when Rebind
  or an extension has a new version. It looks on F-Droid, then Google Play,
  then GitHub. It holds the internet permission, so that Rebind needs none.
  GPL-3.0. *In Rebind.*

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
| Ink Update | `dev.equwal.inkupdate.CHECK` | Opens the list and looks for new versions |

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

## More projects

- [SubRead](https://subread.space/): read along with an audiobook, in the browser.
  Also [for Android](https://github.com/equwal/subread-android/releases/latest),
  [for YouTube](https://github.com/equwal/subread-extension/releases/latest)
  and [for KOReader](https://github.com/equwal/subread.koplugin).
- [SubRead Overlay](https://github.com/equwal/subread-overlay/releases/latest): subtitle lines over any Android media player.
- [SubRead Dictionary](https://github.com/equwal/subread-dictionary/releases/latest): a pop-up dictionary for Android that reads Yomitan dictionaries.
- [SubRead Anki](https://github.com/equwal/subread-anki): one tap makes an Anki card from any Android app.
- [Subrep](https://github.com/equwal/subrep-android/releases/latest): live captions of the sound of your phone.
- [Book Simulator](https://booksimulator.com/): a reading room for Aozora Bunko and Project Gutenberg books.
- [honjimaku.com](https://honjimaku.com/): subtitles for Japanese audiobooks.
- [sbm Sync](https://sbmsync.com/): your bookmarks, the same on every device,
  with [sbm](https://github.com/equwal/sbm) for dmenu,
  [sbm for Android](https://github.com/equwal/sbm-android/releases/latest)
  and the [sbm add-on](https://github.com/equwal/sbm-extension/releases/latest) for Firefox and Chrome.
- [Rebind](https://github.com/equwal/rebind/releases): remap the hardware buttons of e-ink readers and Android,
  with [Ink Recents](https://github.com/equwal/ink-recents/releases/latest),
  [Ink Dim](https://github.com/equwal/ink-dim/releases/latest)
  and [Ink Update](https://github.com/equwal/ink-update/releases/latest).
- [dickt.store](https://dickt.store/): language-learning tools, flashcards and web toys.
- [hentaibun.online](https://hentaibun.online/): learn kanbun and kobun.
- [Recently Written](https://recentlywritten.com/): the blog, and a list of [all projects](https://recentlywritten.com/projects.html).
