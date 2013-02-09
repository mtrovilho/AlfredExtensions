Alfred Extensions
=================

LowerCase.alfredextension
-------------------------
Usage: `lc TEXT`

Description: this extension will copy the lowercase version of `TEXT` to clipboard.


UpperCase.alfredextension
-------------------------
Usage: `uc text`

Description: this extension will copy the uppercase version of `text` to clipboard.


Random Chooser.alfredextension
------------------------------
Usage: `choose a, b, c`

Description: this extension will choose one of the values passed and display a notification with the choosed value.


Unfreeze Menu Bar.alfredextension
---------------------------------
Usage: `unfreeze`

Description: this extension will move `~/Library/Preferences/com.apple.systemuiserver.plist` to your home directory and restart `SystemUIServer`.
__Known Issue__: if you have [iStat Menu][] installed, it will not be restarted, you'll need to restart it manually.


Clean Xcode Data.alfredextension
--------------------------------
Usage: `cxd`

Description: this extension will move `~/Library/Developer/Xcode/DerivedData/*` to `/tmp/oldXData` forcing Xcode to re-index bringing autocompletion back.


Boleto.alfredextension
----------------------
NOTE: this extension is only useful if you need to pay a [Boleto][]

Usage: `boleto XXXXX.XXXXX XXXXXX.XXXXXX XXXXX.XXXXXX X XXXXXXXXXXXXXXX`

Description: this extension will remove spaces and dots from the value and "type" every number with a small delay.


[iStat Menu]: http://bjango.com/mac/istatmenus/
[Boleto]: http://en.wikipedia.org/wiki/Boleto
