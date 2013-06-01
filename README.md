This is updated version of the [ThunderLink extension](https://addons.mozilla.org/en-us/thunderbird/addon/thunderlink/) that has been modified to work with PostBox.

The main changes are:
* It actually can be loaded into PostBox :)
* The links use the protocol x-postbox-message which is inherently supported by PostBox
* The menu items are on the menubar under Tools rather than on the message. This is so I can assign keyboard shortcuts in OSX and also because message menus overlays don't seem to work in PostBox (I suspect because they gave it a different XUL id).
* You have two choices of what to copy to the clipboard
  * Plain text with the message subject followed by its link
  * A rich/HTML link with the message's subject as its text

