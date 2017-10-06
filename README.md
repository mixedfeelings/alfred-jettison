Jettison Workflow for [Alfred 3](http://www.alfredapp.com)
==============================

[Jettison](https://www.stclairsoft.com/Jettison/) is a lightweight MacOS menulet application that automatically and safely unmounts and remounts external volumes when your computer wakes or sleeps. **alfred-jettison** is a simple Alfred workflow to manually invoke Jettison Actions on command. 

Installation
-----

[Download the jettison.alfredworkflow](https://github.com/mixedfeelings/alfred-jettison/blob/master/jettison.alfredworkflow?raw=true "download") and double click to open or manually drag to the worfklows tab of Alfred's preferences pane.

Dependencies
--------

**alfred-jettison** requires [Alfred 3](http://www.alfredapp.com) with a Powerpack license and [Jettison](https://www.stclairsoft.com/Jettison/), both of which are paid apps. 

Usage
-----

![Jettison menu](doc/screenshot.png?raw?=true)

**alfred-jettison** uses the keyword "jet" to safely eject or mount/remount external volumes. 

Commands
--------

* **jet mount** Mount or remount all available drives
* **jet sleep** Safely eject all drives and sleep
* **jet eject** Ssafely eject all drives and stay awake


Notes
-----
Though Jettison is not a scriptable application, **alfred-jettison** uses AppleScript to invoke actions by selecting items in the menulet menu via System Events 

Roadmap
-----
* Eject / mount specific volumes - currently **alfred-jettison** is only able to act on ALL available drives

License / Disclaimer
-----
This workflow is available for free use via the [MIT license](https://opensource.org/licenses/MIT). However, Jettison and the Jettison logo are copyright [St. Clair Software](https://www.stclairsoft.com/Jettison). Use here is not not authorized by, sponsored by, or associated with the trademark owner.