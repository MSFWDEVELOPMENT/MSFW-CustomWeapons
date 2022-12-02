## GD-CustomWeapons

# WILL ADD COMPONENTS SOON...

# CUSTOM WEAPONS FOR YOUR FIVEM SERVER 

## JOIN OUR DISCORD FOR UPDATES AND SUPPORT
# DISCORD - https://discord.gg/Kz9YBjPA2U

## ADD THIS IN qb-core/shared/items.lua

```
    --GD-WEAPONS
    ['weapon_browning'] 		     = {['name'] = 'weapon_browning', 			['label'] = 'BROWNING', 		['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',		['image'] = 'weapon_browning.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A small firearm designed to be held in one hand'},
	['weapon_glock20'] 		     	 = {['name'] = 'weapon_glock20', 			['label'] = 'GLOCK-20', 		['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',		['image'] = 'weapon_glock20.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A small firearm designed to be held in one hand'},
    ['weapon_dp9'] 				     = {['name'] = 'weapon_dp9', 			 	['label'] = 'DP9', 				['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',		['image'] = 'weapon_dp9.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A small firearm designed to be held in one hand'},
    ['weapon_uzi'] 				     = {['name'] = 'weapon_uzi', 			 	['label'] = 'UZI', 				['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_SMG',			['image'] = 'weapon_uzi.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A small firearm designed to be held in one hand'},
    ['weapon_mac10'] 				 = {['name'] = 'weapon_mac10', 			 	['label'] = 'MAC-10', 			['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_SMG',			['image'] = 'weapon_mac10.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A small firearm designed to be held in one hand'},
    ['weapon_mp9'] 				     = {['name'] = 'weapon_mp9', 			 	['label'] = 'MP9', 				['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_SMG',			['image'] = 'weapon_mp9.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A small firearm designed to be held in one hand'},
	['weapon_mp5'] 				     = {['name'] = 'weapon_mp5', 			 	['label'] = 'MP5', 				['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_SMG',			['image'] = 'weapon_mp5.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A small firearm designed to be held in one hand'},
    ['weapon_dildo'] 				 = {['name'] = 'weapon_dildo', 			 	['label'] = 'DILDO', 			['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'nil',			    ['image'] = 'weapon_dildo.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A small firearm designed to be held in one hand'},
    ['weapon_groza'] 				 = {['name'] = 'weapon_groza', 			 	['label'] = 'GROZA', 			['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',		['image'] = 'weapon_groza.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A small firearm designed to be held in one hand'},
    ['weapon_katana'] 				 = {['name'] = 'weapon_katana', 			['label'] = 'KATANA', 			['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'nil',			    ['image'] = 'weapon_katana.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A small firearm designed to be held in one hand'},
	['weapon_keyboard'] 			 = {['name'] = 'weapon_keyboard', 			['label'] = 'KEYBOARD', 		['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'nil',			    ['image'] = 'weapon_keyboard.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A small firearm designed to be held in one hand'},
    ['weapon_m4a1'] 				 = {['name'] = 'weapon_m4a1', 			 	['label'] = 'M4A1', 			['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',		['image'] = 'weapon_m4a1.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A small firearm designed to be held in one hand'},
	['weapon_g18c'] 				 = {['name'] = 'weapon_g18c', 			 	['label'] = 'GLOCK-18C', 		['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',		['image'] = 'weapon_g18c.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A small firearm designed to be held in one hand'},
    ['weapon_riftedge'] 			 = {['name'] = 'weapon_riftedge', 			['label'] = 'RIFTEDGE', 		['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'nil',			    ['image'] = 'weapon_riftedge.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A small firearm designed to be held in one hand'},
	['weapon_krambit'] 			 	 = {['name'] = 'weapon_krambit', 			['label'] = 'KRAMBIT', 			['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'nil',			    ['image'] = 'weapon_krambit.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A small firearm designed to be held in one hand'},
	['weapon_draco'] 				 = {['name'] = 'weapon_draco', 			 	['label'] = 'DRACO', 			['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',		['image'] = 'weapon_draco.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A small firearm designed to be held in one hand'},
	['weapon_gepard'] 				 = {['name'] = 'weapon_gepard', 			['label'] = 'GEPARD', 			['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',		['image'] = 'weapon_gepard.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A small firearm designed to be held in one hand'},
	['weapon_flashbang'] 			 = {['name'] = 'weapon_flashbang', 		    ['label'] = 'FLASHBANG', 		['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'nil',				['image'] = 'weapon_flashbang.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A handheld throwable bomb'},
    ['weapon_dragunov'] 			 = {['name'] = 'weapon_dragunov', 		    ['label'] = 'DRAGUNOV', 		['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_SNIPER',				['image'] = 'weapon_dragunov.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = 'A Sniper!'},
    
```
## ADD THIS IN qb-core/shared/weapons.lua

```
	-- GD-WEAPONS
	[`weapon_dildo`] 				 = {['name'] = 'weapon_dildo', 			['label'] = 'Dildo', 				['weapontype'] = 'Melee',			['ammotype'] = nil, 			['damagereason'] = 'Melee killed / Whacked / Executed / Beat down / Murdered / Battered'},
	[`weapon_katana`] 				 = {['name'] = 'weapon_katana', 		['label'] = 'katana', 				['weapontype'] = 'Melee',			['ammotype'] = nil, 			['damagereason'] = 'Melee killed / Whacked / Executed / Beat down / Murdered / Battered'},
	[`weapon_riftedge`] 			 = {['name'] = 'weapon_riftedge', 		['label'] = 'riftedge', 			['weapontype'] = 'Melee',			['ammotype'] = nil, 			['damagereason'] = 'Melee killed / Whacked / Executed / Beat down / Murdered / Battered'},
	[`weapon_browning`] 			 = {['name'] = 'weapon_browning', 		['label'] = 'BROWNING', 			['eapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_dp9`] 				 	 = {['name'] = 'weapon_dp9', 			['label'] = 'DP9', 				   	['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_m4a1`] 				 = {['name'] = 'weapon_m4a1', 			['label'] = 'M4A1', 				['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_groza`] 		 		 = {['name'] = 'weapon_groza', 	 		['label'] = 'GROZA', 				['weapontype'] = 'Assault Rifle',	['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
	[`weapon_uzi`] 			 		 = {['name'] = 'weapon_uzi', 			['label'] = 'UZI', 					['weapontype'] = 'Submachine Gun',	['ammotype'] = 'AMMO_SMG',		['damagereason'] = 'Riddled / Drilled / Finished / Submachine Gunned'},
	[`weapon_mac10`] 			 	 = {['name'] = 'weapon_mac10', 			['label'] = 'MAC-10', 				['weapontype'] = 'Submachine Gun',	['ammotype'] = 'AMMO_SMG',		['damagereason'] = 'Riddled / Drilled / Finished / Submachine Gunned'},
	[`weapon_mp9`] 			 		 = {['name'] = 'weapon_mp9', 			['label'] = 'MP9', 					['weapontype'] = 'Submachine Gun',	['ammotype'] = 'AMMO_SMG',		['damagereason'] = 'Riddled / Drilled / Finished / Submachine Gunned'},
    [`weapon_mp5`] 			 		 = {['name'] = 'weapon_mp5', 			['label'] = 'MP5', 					['weapontype'] = 'Submachine Gun',	['ammotype'] = 'AMMO_SMG',		['damagereason'] = 'Riddled / Drilled / Finished / Submachine Gunned'},
    [`weapon_glock20`] 				 = {['name'] = 'weapon_glock20', 		['label'] = 'GLOCK-20', 				['weapontype'] = 'Pistol',	['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_g18c`] 				 = {['name'] = 'weapon_g18c', 			['label'] = 'GLOCK-18C', 				['weapontype'] = 'Pistol',	['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
    [`weapon_gepard`] 		 		 = {['name'] = 'weapon_gepard', 	 		['label'] = 'GEPARD', 						['weapontype'] = 'Assault Rifle',	['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
    [`weapon_krambit`] 			 	 = {['name'] = 'weapon_krambit', 		['label'] = 'KRAMBIT', 				['weapontype'] = 'Melee',	['ammotype'] = nil, ['damagereason'] = 'Melee killed / Whacked / Executed / Beat down / Murdered / Battered'},
	[`weapon_keyboard`] 			 = {['name'] = 'weapon_keyboard', 		['label'] = 'KEYBOARD', 			['weapontype'] = 'Melee',	['ammotype'] = nil, ['damagereason'] = 'Melee killed / Whacked / Executed / Beat down / Murdered / Battered'},

```

## ADD THIS IN qb-smallresources/client/weapdraw.lua

```
local weapons = {

	-- GD-Weapons
	'WEAPON_uzi',
	'WEAPON_mac10',
	'WEAPON_groza',
	'WEAPON_mp9',
	'WEAPON_dp9',
	'WEAPON_browning',
	'WEAPON_dildo',
	'WEAPON_riftedge',
	'WEAPON_m4a1',
	'WEAPON_katana',
    	'WEAPON_keyboard',
    	'WEAPON_krambit',
    	'WEAPON_gepard',
    	'WEAPON_draco',
    	'WEAPON_g18c',
   	'WEAPON_glock20',
    	'WEAPON_mp5',
```

## ADD THIS IN qb-smallresources/client/recoil.lua (LINE AROUND 108)

```
	-- GD-WEAPONS
	[GetHashKey("weapon_groza")] = 0.5,
   	[GetHashKey("weapon_gepard")] = 0.5,
    	[GetHashKey("weapon_dragunov")] = 0.5,
	[GetHashKey("weapon_browning")] = 0.3,
	[GetHashKey("weapon_dp9")] = 0.3,
	[GetHashKey("weapon_m4a1")] = 0.3,
    	[GetHashKey("weapon_glock20")] = 0.3,
    	[GetHashKey("weapon_g18c")] = 0.3,
	[GetHashKey("weapon_uzi")] = 0.4,
	[GetHashKey("weapon_mac10")] = 0.4,
	[GetHashKey("weapon_mp9")] = 0.4,
    	[GetHashKey("weapon_mp5")] = 0.4,

```
## REPLACE THE NEXT CODE IN QB-JEWELERY/CONFIG.LUA

```

Config.WhitelistedWeapons = {
    [`weapon_assaultrifle`] = {
        ["timeOut"] = 10000
    },
    [`weapon_carbinerifle`] = {
        ["timeOut"] = 10000
    },
    [`weapon_pumpshotgun`] = {
        ["timeOut"] = 10000
    },
    [`weapon_sawnoffshotgun`] = {
        ["timeOut"] = 10000
    },
    [`weapon_compactrifle`] = {
        ["timeOut"] = 10000
    },
    [`weapon_microsmg`] = {
        ["timeOut"] = 10000
    },
    [`weapon_autoshotgun`] = {
        ["timeOut"] = 10000
    },
    [`weapon_pistol`] = {
        ["timeOut"] = 10000
    },
    [`weapon_pistol_mk2`] = {
        ["timeOut"] = 10000
    },
    [`weapon_combatpistol`] = {
        ["timeOut"] = 10000
    },
    [`weapon_appistol`] = {
        ["timeOut"] = 10000
    },
    [`weapon_pistol50`] = {
        ["timeOut"] = 10000
    },
    [`weapon_uzi`] = {
        ["timeOut"] = 10000
    },
    [`weapon_mac10`] = {
        ["timeOut"] = 10000
    },
    [`weapon_mp9`] = {
        ["timeOut"] = 10000
    },
    [`weapon_groza`] = {
        ["timeOut"] = 10000
    },
    [`weapon_gepard`] = {
        ["timeOut"] = 10000
    },
    [`weapon_draco`] = {
        ["timeOut"] = 10000
    },
    [`weapon_mp5`] = {
        ["timeOut"] = 10000
    },
    [`weapon_dragunov`] = {
        ["timeOut"] = 10000
    },
    [`weapon_browning`] = {
        ["timeOut"] = 10000
    },
    [`weapon_dp9`] = {
        ["timeOut"] = 10000
    },
    [`weapon_m4a1`] = {
        ["timeOut"] = 10000
    },
}

```
## ADD THIS IN qb-ambulancejob/config.lua

```
    --[[ HIGH CALIBER ]]
    [`WEAPON_groza`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_gepard`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_draco`] = Config.WeaponClasses['HIGH_CALIBER'],
    --[[ MEDIUM CALIBER ]]
    [`WEAPON_uzi`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    [`WEAPON_mac10`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    [`WEAPON_mp9`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    [`WEAPON_mp5`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    --[[ SMALL CALIBER ]]
    [`WEAPON_browning`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_M4a1`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_dp9`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_g18c`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_glock20`] = Config.WeaponClasses['SMALL_CALIBER'],
    --[[ CUTTING ]]
    [`WEAPON_riftedge`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_KATANA`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_krambit`] = Config.WeaponClasses['CUTTING'],
    --[[ HEAVY IMPACT ]]
    [`WEAPON_dildo`] = Config.WeaponClasses['HEAVY_IMPACT'],
    [`WEAPON_keyboard`] = Config.WeaponClasses['HEAVY_IMPACT'],

```

## ADD THIS IN ps-dispatch/client/cl_events.lua (IF USING PS-DISPATCH)

```
-- GD-Weapons
    [GetHashKey("weapon_groza")] = "CLASS 3: GROZA",
    [GetHashKey("weapon_gepard")] = "CLASS 3: GEPARD",
    [GetHashKey("weapon_draco")] = "CLASS 3: DRACO",
    [GetHashKey("weapon_browning")] = "CLASS 2: BROWNING",
    [GetHashKey("weapon_dp9")] = "CLASS 2: DP9",
    [GetHashKey("weapon_g18c")] = "CLASS 2: GLOCK-18C",
    [GetHashKey("weapon_glock20")] = "CLASS 2: GLOCK-20",
    [GetHashKey("weapon_m4a1")] = "CLASS 1: M4A1",
    [GetHashKey("weapon_mac10")] = "CLASS 2: Mac-10",
    [GetHashKey("weapon_uzi")] = "CLASS 2: Uzi",
    [GetHashKey("weapon_mp9")] = "CLASS 2: MP9",
    [GetHashKey("weapon_mp5")] = "CLASS 2: MP5",

```

# NOTE - 4-5 WEAPONS ARE TAKEN FROM GTA5 MODS AND IF YOU ARE THE OWNER OF THAT WEAPON AND YOU WANT IT TO BE REMOVED THEN YOU CAN COME TO OUR DISCORD AND TALK TO US AND IF ANYONE HAVE ANY INQURIE THEN THEY CAN JOIN OUR DISCORD 
