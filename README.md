# Darkness
original base API DL Darkness by David M, modified by @Si

API and ScriptCards script for Roll20, allows tokens with Devil's Sight, Truesight and Shadow Magic Sorcerers to see through the darkness spell to vision limit, but those that would be blinded based on the spell description will have vision removed.  Vision is restored upon exit from the AoE

This requires Kurt's ScriptCards available from 1-click and the creation of a handout in the game entitled ScriptCards Library snlib  DO NOT vary this in any way.  Once created, go to Kurt's Github https://github.com/kjaegers/ScriptCards/tree/main/ScriptCards_Examples/libraries and paste the latest version of that library into the handout and save.

In game, exceptions are picked up from the character sheet, so any PC with the above abilities in Features & Traits will automatically be granted sight within the darkness. Shadow Magic Sorcerers are given the option to cast using a spell slot for no visibility or to use 2 Spell Points and gain visibility.  If insufficient spell points exist, they are prompted for another choice.  The ScriptCards script asks for the level of casting and automatically checks and deducts a spell slot if the caster is not a Shadow Magic Sorcerer.

Known issues:  1: This uses dynamic lighting lines and if the page settings are for dynamic lighting lines to block movement, then the GM will have to move the token into/ out of the area of effect. 2: General exceptions can be granted by using a pink status marker (this can be changed to a different marker by editing the start of the API) but at the time of posting this does not grant vision into the AoE from outside, but will grant vision out from inside.  The intention is for this to be applied to tokens carrying a magic weapon that emits light since that temporarily dispels Darkness as a spell in its radius of illumination.
