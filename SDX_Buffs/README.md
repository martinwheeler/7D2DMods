SDX Buffs
---------

This SDX Mod adds additional Action events and Requirements that can be used in the buffs.xml.

MinEventActionCreateItemSDX
------------

This class allows you to get an item from a buff.

Example Usage:

~~~~~~~~~~~~~~~~~~~
	<triggered_effect trigger="onSelfBuffRemove" action="CreateItemSDX, Mods" item="drinkJarCoffee" count="2"/>
~~~~~~~~~~~~~~~~~~~