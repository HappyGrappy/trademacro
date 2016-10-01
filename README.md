# PoE Trade Macro
AutoHotKey script that provides various useful macro for trading in Path of Exile

1. **ctrl+p** for price checking the item in cursor by _item name_. Works great for uniques and other items like _Offering to the Goddess_.
2. **ctrl+i** for price checking but with manual input of _item name_.
3. **ctrl+o** to show dialog to config predefined searches.
4. **f9 to f12** - predefined item search macro which automatically creates a WTB message into your clipboard. Adding _ctrl_ will reset the search, for example **ctrl+10**. _ctrl+f12_ allows you to manually input the _item name_.

These hotkeys can be changed in `config.ini`.

![screenshot](https://cloud.githubusercontent.com/assets/75921/18938211/c04a6fc0-8629-11e6-8633-7f732ec05888.png)

**How to install/use:**

1. You'll need to install the following:
 - ahk - http://ahkscript.org
2. Download and extract [master.zip](https://github.com/thirdy/trademacro/archive/master.zip) (Right-click and Save as..).
3. Edit `config.ini` to your preferences.
4. Run trademacro.ahk.
5. Run Path of Exile and switch to Fullscreen Window Mode (or Window Mode) - this is required for ahk to work.

**Harcore league?**

By default, the script is set to the current softcore temp league. To switch to HC:

Edit the config.ini, find these lines,

```
[Search]
SearchLeague = "tmpstandard"
; Defaults to "standard" or "tmpstandard" if there is an active Temp-League.
; Possible values: 
; 	"tmpstandard" (current SC Temp-League) 
;	"tmphardcore" (current HC Temp-League) 
;	"standard", 
;	"hardcore"
```

Change it to,

```
[Search]
SearchLeague = "tmphardcore"
; Defaults to "standard" or "tmpstandard" if there is an active Temp-League.
; Possible values: 
; 	"tmpstandard" (current SC Temp-League) 
;	"tmphardcore" (current HC Temp-League) 
;	"standard", 
;	"hardcore"
```

TradeScript is not affiliated with GGG and is a fan made tool, 100% open source and free(as in freedom).

Non-Github Contributors:
/u/mebiustos (for fixing font and cache results)
/u/gvieira (for chat linked item fix)
