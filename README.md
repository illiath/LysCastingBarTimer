# LysCastingBarTimer
WoW Classic Addon - Simple Casting Bar Timer

Very simple addon with no configuration.

Addon adds a coundown timer to the standard blizzard castingbarframe. This is untested alongside other casting mods, as it was never intended to work with those.

This addon works with channeled spells and regular cast spells, as well as most other effects that use the standard frame.

Now added support for the "Mirror" bar, which is the bar for breath, feign death, exhaustion, etc.

Please add a comment in the issue tracker if something isn't working...

If you want to change the precision displayed, change the line in LysCastingBarTimer.lua from the below line:
CastingBarTimer_DisplayString	= " (%0.2fs)";

To however many decimals you want, so for one decimal place:
CastingBarTimer_DisplayString	= " (%0.1fs)";