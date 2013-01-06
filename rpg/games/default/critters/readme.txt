How to create a NPC
===================

r_char_name "Bob"			//name of the NPC
r_char_mdl "uh/chars/man/monk01"	//path to NPCs model
r_char_base_level 4			//level to start on
r_char_script 96			//NPCs script - defines how he will interact with the world
r_char_faction 1			//Faction of the NPC - defines who are his friends and foes
r_char_merchant 2			//NPC is a merchant - the script merchants/2 is executed

include "includes/npc_stats"		//check the script for more information on stats


