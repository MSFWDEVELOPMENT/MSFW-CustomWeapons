## GD-CustomWeaponsV2

# CUSTOM WEAPONS FOR YOUR FIVEM SERVER 

## JOIN OUR DISCORD FOR UPDATES AND SUPPORT
# DISCORD - https://discord.gg/Kz9YBjPA2U

## ADD THIS IN qb-core/shared/items.lua

```
    --GD-WEAPONS
    ['weapon_browning'] 		     = {['name'] = 'weapon_browning', 			['label'] = 'BROWNING', 		['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',		['image'] = 'weapon_browning.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = ''},
    ['weapon_dp9'] 				     = {['name'] = 'weapon_dp9', 			 	['label'] = 'DP9', 				['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',		['image'] = 'weapon_dp9.png', 			['unique'] = true, 		['useable'] = false, 	['description'] = ''},
    ['weapon_uzi'] 				     = {['name'] = 'weapon_uzi', 			 	['label'] = 'UZI', 				['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_SMG',			['image'] = 'weapon_uzi.png', 			['unique'] = true, 		['useable'] = false, 	['description'] = ''},
    ['weapon_mac10'] 				 = {['name'] = 'weapon_mac10', 			 	['label'] = 'MAC-10', 			['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_SMG',			['image'] = 'weapon_mac10.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = ''},
    ['weapon_mp9'] 				     = {['name'] = 'weapon_mp9', 			 	['label'] = 'MP9', 				['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_SMG',			['image'] = 'weapon_mp9.png', 			['unique'] = true, 		['useable'] = false, 	['description'] = ''},
    ['weapon_dildo'] 				 = {['name'] = 'weapon_dildo', 			 	['label'] = 'DILDO', 			['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'nil',			    ['image'] = 'weapon_dildo.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = ''},
    ['weapon_groza'] 				 = {['name'] = 'weapon_groza', 			 	['label'] = 'GROZA', 			['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',		['image'] = 'weapon_groza.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = ''},
    ['weapon_katana'] 				 = {['name'] = 'weapon_katana', 			['label'] = 'KATANA', 			['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'nil',			    ['image'] = 'weapon_katana.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = ''},
    ['weapon_m4a1'] 				 = {['name'] = 'weapon_m4a1', 			 	['label'] = 'M4A1', 			['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',		['image'] = 'weapon_m4a1.png', 			['unique'] = true, 		['useable'] = false, 	['description'] = ''},
    ['weapon_riftedge'] 			 = {['name'] = 'weapon_riftedge', 			['label'] = 'RIFTEDGE', 		['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'nil',			    ['image'] = 'weapon_riftedge.png', 		['unique'] = true, 		['useable'] = false, 	['description'] = ''},
    
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
```

## ADD THIS IN qb-smallresources/client/recoil.lua (LINE AROUND 108)

```
	-- GD-WEAPONS
	[GetHashKey("weapon_groza")] = 0.5,
	[GetHashKey("weapon_browning")] = 0.3,
	[GetHashKey("weapon_dp9")] = 0.3,
	[GetHashKey("weapon_m4a1")] = 0.3,
	[GetHashKey("weapon_uzi")] = 0.4,
	[GetHashKey("weapon_mac10")] = 0.4,
	[GetHashKey("weapon_mp9")] = 0.4,

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
    --[[ MEDIUM CALIBER ]]
    [`WEAPON_uzi`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    [`WEAPON_mac10`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    [`WEAPON_mp9`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    --[[ SMALL CALIBER ]]
    [`WEAPON_browning`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_M4a1`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_dp9`] = Config.WeaponClasses['SMALL_CALIBER'],
    --[[ CUTTING ]]
    [`WEAPON_riftedge`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_KATANA`] = Config.WeaponClasses['CUTTING'],
    --[[ HEAVY IMPACT ]]
    [`WEAPON_dildo`] = Config.WeaponClasses['HEAVY_IMPACT'],

```

## ADD THIS IN ps-dispatch/client/cl_events.lua (IF USING PS-DISPATCH)

```
-- GD-Weapons
    [GetHashKey("weapon_groza")] = "CLASS 3: GROZA",
    [GetHashKey("weapon_browning")] = "CLASS 2: BROWNING",
    [GetHashKey("weapon_dp9")] = "CLASS 2: DP9",
    [GetHashKey("weapon_m4a1")] = "CLASS 1: M4A1",
    [GetHashKey("weapon_mac10")] = "CLASS 2: Mac-10",
    [GetHashKey("weapon_uzi")] = "CLASS 2: Uzi",
    [GetHashKey("weapon_mp9")] = "CLASS 2: MP9","

```