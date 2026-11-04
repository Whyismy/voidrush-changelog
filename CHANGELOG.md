# Void Rush Changelog
## 5.4 11/04/2026 - Void Terrain Update
* **New: bandits in tiers 5 and 6 hunt in packs**
    * In tier 5, 2 to 3 bandits drop in together; in tier 6, 3 to 4
    * A pack roams behind its leader and fights as one: hit one and the rest come running, they all go for the same player, and if one of them can see you, the whole pack knows where you are
    * Melee bandits in a pack surround you, coming in from the front, both sides and behind
* **New: no more dropping your best gear by accident**
    * Gear you've upgraded, reforged, put runes on or socketed gems into, and your profession tools, now need a quick double tap of Q to drop. The first press just asks you to press again
* **New: profession tools take gems and enchants**
    * Every profession tool, Watering Can included, now has a gem socket. A tool takes gems up to its own tier (a Novice tool takes Tier 1 gems, a Legendary tool any tier), and a Socket Conduit can reroll it to more sockets like any gear
    * Enchants on a tool go up to its tier too: Novice tools get level I, Apprentice up to II, and so on to VI for Legendary
    * Enchants on tools no longer vanish the next time the tool gains XP, and gems and enchants stay on through tier upgrades. Their stats count while you hold the tool
* **New: rivers and lakes**
    * Winding rivers now run through the land, crossing chunk after chunk, and lakes dot the land, deepest in the middle. Each is made from the land it lies in: mossy beds in the bushland, sandy ones in the desert, and so on. Water in grassy and mossy lands grows seagrass and lily pads
    * In tiers 5 and 6, some of the land has rivers and lakes of lava instead. Watch your step
    * Trees, pillars and rocks in the way stay standing as little islands
    * Rivers and lakes are always back in the same place when the land rebuilds after crumbling into the void
    * Rivers flow downhill: as they wind through the rolling hills they step down in small waterfalls
* **New: monsters no longer crawl through water**
    * Hostile mobs now move through rivers and lakes almost as fast as on land, so jumping in the water won't shake them off
* **New: rolling hills**
    * The land now gently rises and falls, up to 3 blocks up or down, in long slow slopes. Rivers and lakes run through level valleys between them, and the land around spawn stays flat
    * Buildings, outposts and dungeon entrances sit level on the hills, on a foundation made from the land around them, and never over a river or lake
    * Outposts sit at the height of the ground around them rather than up on a raised block of land, and owned outposts come back at the same height after a restart
    * The Halloween island and its Pumpkin Merchant stay where they belong: the hills no longer push the island's blocks up under the merchant
* **New: Loot All for world boss hoards**
    * A world boss's hoard now has a Loot All button on its bottom row. One click moves your whole share into your bags and inventory, and anything that doesn't fit stays in the hoard for you
* **New: mountains**
    * Very rarely, a mountain rises out of the rolling hills, up to 18 blocks high, with a rocky ridged peak. You might cross a few in a long journey, never near spawn
    * A river that meets a mountain cuts a gorge right through it
* **New: ravines**
    * Rare, deep ravines now split the land, up to 15 blocks down, winding for over a hundred blocks
    * Their walls are made of the land around them (sandstone in the desert, dirt under grass, and so on) and full of big veins of the area's tier ores: coal near spawn, then copper, iron and lapis, redstone, diamonds and emeralds, and nether quartz with the odd bit of ancient debris in tier 6
    * Climb out on the ladders along the walls, or take the old mossy staircases up at either end
* **Fix: off-hand critical hits now deal more damage instead of less**
    * An off-hand crit dealt only its weapon's Crit Damage percent of the hit, so a weapon with +31.5% Crit Damage critted for under a third of its damage. Off-hand crits now deal 150% plus the weapon's Crit Damage, like your main-hand crits
    * Gems socketed in your off-hand weapon now add their Crit Chance and Crit Damage to its off-hand strikes
* **Fix: Thorns no longer sets off your scythe's cleave**
    * Getting hit while holding a scythe used to spin a free cleave through every enemy around you. Now only your own swings cleave, as before
* **Fix: Lord of the Dead's Lost Souls now fight for you instead of attacking you**
    * Every 5 kills, 3 Lost Souls rise from the body and fight beside you for 10 seconds, going for whatever you're hitting. They can't be hurt, and every kill they get counts as yours
    * It no longer uses up your Souls, so they're all kept for Soul Feast. Your held item shows how many kills until the next Lost Souls
* **Fix: Soul Collector's ghost now fights for you**
    * Your ghost hunts whatever you're fighting and its kills count as yours. Before, its hits on monsters did nothing, and it could turn on players
    * You have one ghost at a time: another proc while it's out keeps it around longer instead. At rank 5 it stays until you die, change worlds or log off
    * Max HP is still halved while the ghost is out, but it now always comes back to normal when the ghost leaves, even with several procs or if you log off
* **Fix: your screen no longer shakes when your Energy Shield fills up**
    * As your shield grew, the health bar made your camera shake and hearts flash as if you'd been hit. Now only real hits do that
* **Fix: junk items stay junk**
    * A Totem Splinter no longer saves you from death, and Ender Pearl Dust and the Cracked Return Pearl can't be thrown. Junk is only for selling
* **Fix: blocks that fall off in your realm come back as building blocks**
    * Ladders, doors, torches and carpets that drop because the block holding them was broken now come back as building blocks you can place again, like breaking them directly
* **Fix: shop items no longer sell back for more than they cost**
    * Grilled Salmon from the Food Merchant sells as normal food, and bots charge a little more for what they sell
    * Three gems are now always worth more than the gem you'd forge from them. Tier 1 gems sell for more: 6 coins, and 120 for Sage Opal and Clover Jade
    * Starter Gear can no longer be sold
* **Fix: a server restart while you're on the death screen no longer wipes your gear**
    * The items death protection saves for you are now kept safe through a restart, and come back when you respawn
* **Change: banks reopen on the tab you were last on**
    * Open your bank or guild bank within 3 minutes of closing it and it opens on the same tab. After that, it starts on Tab 1 again
* **Change: Pack Rat boosts junk only**
    * Pack Rat's bonus now applies to junk, as the talent says, not to everything you sell. Junk sold with the "Sell from Inventory & Junk Bags" button now gets the bonus too
## 5.34b 10/31/2026
* **New: Graphics settings, for low FPS**
    * Open them with `/graphics` or in Extras > Settings > Graphics, or use `/graphics low` to turn everything down at once (`/graphics full` undoes it). They only change what you see
    * **Particles:** Full, Reduced or Low cuts every particle you see, and makes the big ones follow your own Particles setting in Video Settings
    * **NPC Bots:** draw bots only when they're within 32 or 16 blocks of you
    * **Moving Decorations:** hide the floating islands' crystals, rings and orbiting rocks, and the crafting stations' animations
    * **Other Players' Wings:** hide everyone else's wings
* **New: Reap, a second rare stat for herbalism tools**
    * When your herbalism tool rolls a rare stat on a level-up, it can now get Reap instead of Regrowth
    * Reap gives a chance (up to 15%) that a harvest also harvests every plant in the 3x3 around it, with full drops and XP for each
* **New: eggs, and Fried Eggs to cook from them**
    * Chickens now lay tiered eggs, and butchery chickens sometimes drop one when killed
    * Right-click an egg on a campfire to cook it into a Fried Egg. Higher tier eggs make better Fried Eggs, just like meat
    * These eggs are for cooking, so they can't be thrown
* **New: Magic Infusion, a second rare stat for mining tools**
    * When your pickaxe rolls a rare stat on a level-up, it can now get Magic Infusion instead of Vein Mining
    * Magic Infusion gives a chance (up to 30%) that the node you just mined stays up for 2 to 5 more mines, with full drops and XP each time
* **New: WindGust, a second rare stat for woodcutting tools**
    * When your axe rolls a rare stat on a level-up, it can now get WindGust instead of Treefeller
    * WindGust gives a chance (up to 15%) that chopping a log blows every leaf off the tree, with all the sticks and saplings blown straight to you. It doesn't wear your axe
* **New: Astute, a second rare stat for fishing rods**
    * When your rod rolls a rare stat on a level-up, it can now get Astute instead of Treasure Find
    * Astute gives a chance (up to 30%) that a catch also reels up Minecraft XP, more in higher tier waters
* **New: Briar Spinel, a Thorns gem**
    * A thorn-wrapped green gem that adds **+2% to +9% Thorns** (tier 1 to 6). It drops and upgrades like any other gem
* **Fix: the server no longer crashes when players walk away from Kaelith at spawn**
* **Fix: Bedrock players on phones can now plant, water and harvest on their Void Farm**
    * Tapping a planter now does the same as using it, unless it has weeds or pests to clear first. If you're standing right at a planter, the tap goes to that one
* **Fix: the void no longer crumbles away under you if the server restarted during your Rift Cannon flight**
    * Land would stop appearing around you and crumble under your feet. Logging in again fixes it
* **Fix: the repeating crossbow now hits at its full Shots/sec**
    * Above 2 shots a second, extra bolts bounced off the target you were shooting. Now every bolt lands
* **Fix: monsters in tier 6 zones no longer go missing**
    * When a rare monster rolled in a tier 6 area, it could spawn without its name or health bar and stop the rest of that area's monsters from spawning
* **Fix: fast melee attacks no longer get thrown away**
    * Above 2 attacks a second, extra hits on the same target were ignored. That held daggers back and made Attack Speed past a small amount do nothing. Now every fully charged swing lands, so Attack Speed, Haste and Adrenaline Rush count at any speed. Spam clicking still does nothing
* **Fix: falling blocks no longer freeze in mid-air on Bedrock**
    * Blocks falling into place, collapsing walls and breaking debris now actually fall for Bedrock players, like they do on Java
* **Fix: Vein Mining, Treefeller and Regrowth now work at any amount, and do exactly what their percent says**
    * Below 7.5% they did nothing at all, and above that they used a rounded amount instead of the number on your tool. Now a tool with 4% Treefeller procs 4% of the time, and 12% Regrowth makes plants regrow 12% faster
* **Fix: spam clicking the repeating crossbow no longer fires faster than holding right click**
    * Clicking at the right pace used to fire faster than the crossbow's Shots/sec on slower crossbows
* **Change: Kaelith's Comeback is now a weekly quest**
    * Kaelith now loses his gear once a week instead of every day. Once you've helped him, the quest comes back on Monday at midnight, along with the Quest Board's weekly quests. A run you've already started carries on as normal
* **Change: Void Farms are lighter on your FPS**
    * Your farm now only sends your game the parts you can actually see, so big farms cost far less to draw. The only difference you'll notice: empty planters no longer have an "Empty" label
* **Change: a lighter resource pack**
    * Shields are far cheaper to draw (up to 70% fewer parts) and look exactly the same, and the pack is about a quarter smaller to download (half on Bedrock)
* **Change: Rapid Fire speeds up your repeating crossbow instead of adding damage**
    * Each hit in a row on the same target gives **+5% fire rate**, up to **+100%** at 20 hits, instead of +5% damage. Hitting a different target starts over
* **Change: Kaelith's rematch is against Siege Beast Jr.**
    * At the end of Kaelith's Comeback, the beast that charges him is now a baby Siege Beast: half his height, big-headed, no armour yet, and just as angry. It still sends him flying
* **Change: Void Farms no longer fill your chat**
    * Your farm landing, leaving or drifting away no longer sends messages. Walk within 5 blocks of your farm and you'll get a reminder that you can manage it (right-click it or use `/farm`). New farmers get their starter kit the first time they walk up to their farm
* **Change: walking while firing a repeating crossbow throws off your aim**
    * The faster you move, the further your bolts stray, up to **20 degrees** off your crosshair at a normal walk. Sneaking strays about a third as much, and standing still is dead accurate. Getting knocked back doesn't count, and your fire rate is unchanged
* **Change: Production leaves the sidebar when it's idle**
    * If none of your production lines have been working for 5 minutes, the Production section hides from your sidebar. It comes back as soon as a line starts running again
* **Change: Thorns now reflects its full percent on every hit**
    * Thorns used to be a chance to reflect half the hit. Now **every** hit a monster lands on you sends your Thorns % of its damage straight back, so 20% Thorns reflects 20% of every hit
    * Thorns kills now count as your kills, with loot and quest progress
* **Change: the Thorns Rune now makes your Thorns burst**
    * Instead of adding Thorns, the Thorns Rune gives **+5% Thorns Burst chance per tier**: when your Thorns reflects damage, it can burst out and hit every enemy within 4 blocks of you for the same amount
    * Runes you've already applied switch over on their own
* **Change: crafting tables can no longer be used**
* **Change: the spear's Lance dash now has a 4 second cooldown, or 2 seconds for Lancers**
    * Spears could dash every 2 seconds in anyone's hands. Lancers keep that as a class bonus
## 5.34 10/30/2026
* **New: seeds fit in Resource Bags**
    * Void Farm seeds of every size fit in Resource Bags and collect into them automatically, like ores and herbs. Take them out when you want to plant
* **New: your outpost guards fight monsters**
    * Guards at an outpost you own now attack hostile mobs that come near it, then head back to the bell once the area is clear. They never touch pets, bosses or other guards
* **New: your outposts warn you when a player attacks them**
    * If another player (not your party) attacks your outpost's guards, you get a chat warning with their name and the outpost's location, at most once a minute per outpost
* **New talent: Keen Eye** (Utility)
    * Gain **+2% to +12% Truestrike** (ranks 1-5), so your attacks cut through enemy evasion. It stacks with Truestrike from your gear
* **New: "Any Paper" recipe at the Sawmill**
    * Set a production line to Any Paper and it saws all your logs into paper of their own tier, whatever mix you put in, so you don't need a line per tier
* **New daily quest: Kaelith's Comeback**
    * Remember Kaelith from the tutorial, the guy who showed off his tier 6 gear right before the Siege Beast got him? He's at spawn by the Training Dummy, back in starter gear, and he loses it all again every day. Help him gear back up to your tier: slay mobs for his blade, elites for his armor, and close a rift for his shield. Then stand with him when the Siege Beast comes back for a rematch
    * Each step ends in a scene that only you see, and you watch his gear come back piece by piece. Rewards are Void XP, coins and a spare piece of gear at your tier. It has its own slot, so it doesn't use one of your quest slots, and it resets every day at midnight
* **New: tier 4, 5 and 6 food crops**
    * The far zones now grow their own food: **Pumpkins and Melons** in tier 4, **Golden Carrots and Golden Potatoes** in tier 5, and **Golden Apple Bushes** and glowing **Glow Berry vines** in tier 6. They need Herbalism 30, 45 and 60
    * Cook them at a campfire into Pumpkin Pie, Roasted Golden Carrot, Roasted Golden Potato or Candied Golden Apple. Each new crop also drops seeds for your Void Farm
    * Sweet Berry Bushes now grow in tier 1 and 2 zones
* **New: pumpkins, melons and cactus start harvesting on the first click**
    * You no longer have to dig them out before the harvest bar starts, and holding the click doesn't restart it
* **Fixes**
    * Your Void Farm grows in place when you level up or buy a plot, instead of needing a new farm spot
    * Grass and flowers no longer poke through your farm's planters
    * Planter labels and the farm sign stay above sugar cane and cactus
    * Clicking a planter from the side now picks the one you're aiming at
    * Watering cans are held upright with the spout facing ahead (they were backwards and upside down)
    * You can fight mobs standing on your farm again: your swings no longer hit the farm instead
* **Fix: outpost guards and raiders now actually hurt each other during a defense**
* **Fix: the starter quest no longer gets stuck for experienced players**
    * "Close the Void Rift" only shows on the Quest Board for new players now. If you already took it, the Quest Cannon now appears for you and fires you to your own rift, so you can finish it
* **Fix: idols no longer show as Perfect without every stat**
    * Idols can now very rarely roll extra stats on top of their usual ones, and a Perfect idol has every idol stat. Idols that were wrongly marked Perfect lose the mark
* **Fix: tier 6 zones grew tier 1 crops**
    * They spawned wheat and beetroot. They now grow tier 6 crops
* **Fix: tier 6 food sold for 1 coin**
    * It now sells for 100 coins and shows its real saturation
* **Fix: cooked food could be cooked again**
* **Fix: right-clicking berry crops picked plain berries and left the bush bare**
    * Left-click berries to harvest them
* **Fix: raw Sweet Berries, Melon Slices and Glow Berries now say they can be cooked at a campfire**
* **Change: your first 2 hires on the starter quest are free**
    * The Quest Clerk now pays for any adventurer you hire for your first party, not just the ones who arrive beside you
* **Change: your first food buy on the Restock Your Food quest is free**
    * The Food Merchant gives you your first bundle of food on the house
* **Change: armor can now roll Magic Power**
    * Armor's bonus Damage stat is now either **+Damage** or **+Magic Power**, never both, so casters can find armor made for them too
* **Change: axes no longer strip logs**
    * Right-clicking a log with an axe no longer strips its bark
    * Stripped logs you find in the world can now be chopped like the normal log of the same wood: same tier, level requirement, XP and drops
* **Change: Last Stand now has a 30 minute cooldown**
    * Last Stand used to recharge every time you died. Now it can save you once every 30 minutes, and dying or relogging doesn't reset it
* **Change: some Advanced Cooking recipes use the new crops**
    * **Inferno Steak:** 3 Beef, 2 Melon Slices and 1 Carrot
    * **Pumpkin Spice Pie:** Sugar instead of Cocoa Beans
    * **Voidfeast Platter:** 2 Golden Carrots, 2 Golden Potatoes and 2 Mutton
* **Change: crops in farther zones need a higher Herbalism level**
    * A crop needs the Herbalism level of its zone's tier, the same as the better food it gives. For example, carrots in a tier 5 zone need level 45 and come up golden
## 5.33 10/30/2026
* **New profession: Farming**
    * **Void Farm spots** spawn into new void land as it generates, just like void rifts. Everyone near a spot farms there together, but each player sees only their own farm. Walk away and your farm fades back into the void, then drops in again at the next spot you find, every crop just as you left it
    * **Seeds come from Herbalism:** any plant you harvest can now drop its seed (more often from Herbalism 10)
    * **Crops grow in real time, even while you're offline.** Watered soil grows twice as fast
    * **Care decides quality:** water your crops, upgrade the soil and feed them fertilizer from your compost bin. Weeds and pests just slow a crop down until you clear them
    * **Big harvests:** 3-6x a normal Herbalism harvest, plus lots of Farming XP
    * **Farm Fresh +1 / +2:** well-grown produce makes stronger food when cooked and longer-lasting potions when brewed
    * Fertilised soil now shows which fertilizer it has
    * **Plant food:** make Leaf Feed, Bloom Feed or Void Feed from compost and Fishing's Fish Oil, then mix it into your farm's rain barrel and its water changes colour. Water your crops from it to make them grow faster and harvest more
    * **Buy extra plots** with Void Coins in /farm, up to 64 planters. Each plot costs a bit more than the last
    * New **Watering Can** tool in a Farming tab at the Toolsmith. It works from your inventory: carry it and it waters your seeds as you plant, boosts every harvest and levels up as you farm
    * A Farmer job, a Farming talent, daily Farmer's Orders and achievements. Use **/farm** to see your crops
* **New: Void Tunnels**
    * A rare new find in Tier 1 and beyond: a small blackstone burrow with a pitch-black membrane across its opening. Walk into it to be pulled into a dark, cramped tunnel
    * Up to 6 players can go in together: anyone who follows within **45 seconds** joins the run, then the mouth caves in behind you
    * Fight through the chambers along the way. Each one stays sealed until its monsters are dead, more monsters lurk in the passages between, and they get stronger the deeper you go
    * Clear the last chamber and walk into the light to come out on an island **one to two tiers further out** (or deeper into Tier 6), hundreds of blocks from where you went in
    * Dying, logging out or backing out through the entrance ends your trip. If you die, your grave waits by the tunnel's mouth
* **New: void rifts and loot boxes fall in like meteors**
    * When one spawns into new land it streaks down out of the sky, trailing fire and smoke (purple void fire for rifts), and crashes into the ground before it appears
* **New class: Priest**
    * Choose it from the class menu (the totem). Priests fight with the new **Holy Staff** and deal **+15% damage** with it
    * **Smite (left-click):** holy light strikes the closest enemy in front of you, up to **8 blocks** away, dealing your staff's Magic Damage boosted by your Magic Power. 1 second cooldown, and no swing timer: every click goes through straight away
    * Smite goes for hostile mobs, bosses, bandits and players you can fight first, and only hits animals when nothing hostile is in front of you. It never hits villagers, pets, friendly outpost guards or players you can't fight
    * **Renew (right-click):** channel a heal on yourself and every ally within **5 blocks**, shown by a gold ring that moves with you. Over 10 seconds each of them heals **2x your Smite damage**. You're slowed while channelling, and swapping off the staff or casting Smite ends it early. 10 second cooldown
    * **Holy Staves for every tier (1-6)**: in the Armory's staves page, the Starter Gear shop, and as the Priest's starter weapon. You can also **craft them at the Inscription desk** (Staves tab), with gold and Radiant Essence in place of the mage staff's essence
    * **Elite and boss Holy Staves**: world bosses can drop them as trophies (like "Tyrant's Gilded Crozier") and as elite gear, and some elite Mage monsters now carry one
    * **Priest talents:** three branches. Radiance makes Smite burn, chain and build up to a huge Judgment pillar; Benediction makes Renew wider and stronger, ending in Divine Hymn; Sanctity adds shields, damage reduction, Atonement heals and the Sanctuary holy circle
    * Look out for Bandit Priests, who smite from range and heal themselves. The Class Hall has a Priest champion
* **New: Holy Idols and Healing Power**
    * Holy Idols are a new off-hand idol for Tiers 1-6, with regular, elite, boss and Voidforged designs. They're the only gear with **Healing Power**, which makes every Priest heal and shield stronger (+10% at Tier 1 up to about +37% at Tier 6, more on elite and boss idols)
    * They drop like other idols: from monsters carrying one, bosses, the Abyssal Crucible and more
* **New talent: Soul Siphon** (Utility)
    * Mobs you kill drop **+10% to +50%** more experience orbs (ranks 1-5), handy for paying Mage and Priest spell costs. Mobs that drop no experience still drop none
* **Fix: every Archer talent now works as described**
    * **Hawkeye:** fully drawn arrows mark an enemy and your follow-up arrows deal +20% to it. Weak Point makes your arrows always crit the mark, Kill Confirmation refreshes and stacks the mark, and Perfect Hunt readies a glowing arrow that pierces enemies for double damage
    * **Snare Arrow:** shoot while crouching to lay a slowing trap where the arrow lands
    * **Hunter's Instinct:** enemies you hit glow and you see their health
    * **Terrain Mastery / Master of Terrain:** bonus arrow damage, doubled when shooting from high ground
    * **Split Arrow** fires real side arrows and **Ricochet** arrows really bounce to the next enemy
    * **Rain Marker:** crouch-left-click with your bow to mark an area. Your arrows hit harder inside it, Suppressing Fire slows and weakens enemies there, and Storm of Feathers rains arrows on it
    * Lightfoot's speed no longer flickers
* **Fix: Berserker talents now work as described**
    * **Savage Leap** slams enemies where you land, and no longer stops Undying Rage from working for 2 minutes after every leap
    * **Undying Rage** only triggers on hits that would really kill you, and you deal +30% damage while it lasts
    * **Worldsplitter** and **Red Mist** deal the damage they're meant to (they were far too strong), and hit every kind of enemy
    * **Shatter Armor** empowers your critical axe hits at max Sunder without spending your Sunder stacks
    * **Sunder** and **Headman's Rhythm** stacks no longer reset on every kill
    * **Bloodletting** makes enemies really bleed, and **Death Defiance** heals you when you kill a bleeding enemy
    * **Rushdown** kills give knockback resistance too, **Carnage** kills give bonus damage, and **Red Mist** kills make your frenzy buffs last longer
    * **Blood Trail** speeds you up while you chase down injured enemies
* **Fix: class talent area damage is no longer far too strong**
    * Many talents that splash nearby enemies hit every one of them as hard as a full weapon strike, no matter what they said. They now deal their own share: **Blade Cyclone**, **Riposte**, **Aftershock**, **Supercell**, **Break Formation**, **Judgment Wall**, **Omni Strike**, **Black Lotus**, **Grim Harvest**, **Shadow Trail**, **Drive Through**, **Dragon Pulse** and **Arcane Avatar**. Talents with a fixed number now scale with how hard you hit
    * **Dragon Pulse** now really gets stronger for each Ki you spend, and **Arcane Avatar**'s orbs scale with your bolts
    * **Blade Cyclone** and **Shadow Trail** no longer hurt pets, villagers or players you can't fight
    * Enemies caught by one of these splashes no longer ignore your class talents on your next hit
* **Fix: arrows no longer float in mid-air after you hit a bow practice target**
* **Fix: every Marksman talent works now**
    * **One Shot** and **Modular Quiver** never triggered with the repeating crossbow. They now trigger on your critical hits. One Shot triples a max-Focus crit (the extra damage is capped against bosses) and spends your Focus
    * **Bullet Hell:** crouch + right-click with your crossbow to plant yourself and fire **3x as fast** for 5 seconds. Moving off the spot ends it. Before, it didn't change your fire rate at all
    * **Piercing Bolt:** shots at max Focus now really pierce through 3 extra enemies and go through shields
    * **Heat Sink, Overclock and Controlled Burst** build up over a stream of shots and reset when you stop shooting, instead of staying on forever after your first few hits
    * **Portable Arsenal** now boosts every third shot (it was boosting every shot for some builds)
    * Getting hit now breaks your Focus. **Breath Control** makes a hit cost only 2 Focus
* **Fixes**
    * Monster and bandit shields really block now: a raised shield stops hits from the front (melee, arrows and mage bolts). Hit them from the side or behind, or knock the guard down for 5 seconds with an axe
    * Leaving the game in the middle of a Herbalism harvest no longer leaves its timer running
    * Gear dropped by dungeon monsters now shows its real stats. It was always 1.55x stronger than its tooltip said, which is why the first Upgrade Core on it looked like a huge jump. It also gets its own **✺** symbol in its name, and gear you already have updates the next time you equip it or open a chest or menu
    * Mobs can no longer get stuck as unkillable "ghosts" that keep attacking you
    * The Abyssal Horror no longer floats a block above the ground when summoned from an altar
* **Change: bandits fight a lot smarter**
    * They go after whoever is hurting them most and finish off players who are nearly dead. Sneaking keeps you hidden longer, but they can hear you through walls if you're close and not sneaking
    * Break line of sight and they search where they last saw you, then give up. They no longer track you through walls
    * Melee bandits circle you, jump for critical hits, walk around your shield, and throw knives if you pillar up out of reach. Berserker axes knock your shield down for 5 seconds
    * Archers, Marksmen, Mages and Priests keep their distance, strafe and lead their shots, and escape when you rush them
    * Bandits can dodge your arrows and throwables (more often in higher tiers), drink healing potions when they're low, and call nearby bandits to help
    * Bandit Shieldwalls block with a real shield: hit them from the side or back, or break their guard with an axe
* **Change: Elemental Affinity now strikes with an element**
    * When it procs, your hit becomes a fire, frost, lightning, venom or shadow strike for **+15% damage**, with its own effects and a message in combat chat
    * Fire sets the target alight, frost slows it, venom poisons it, shadow withers it, and lightning is pure damage
    * Proc chances are unchanged
* **Change: the Abyssal Horror's tentacles grow back**
    * A killed tentacle bursts back up near the party **15 seconds** later (a ring on the ground warns where), on top of the new tentacles each phase adds, up to 8 at once
* **Change: tougher Animal Butchery mobs**
    * Tier 4-6 butchery animals have much more HP: Tier 4 **120** (was 90), Tier 5 **250** (was 110), Tier 6 **~600** (was 130)
    * Hostile Tier 5-6 animals hit harder: about **27** at Tier 5 (was 16) and **32** at Tier 6 (was 18)
* **Change: dungeon monster gear is much rarer**
    * Dungeon monsters now drop **one** piece of their gear on **10%** of kills in Tier 1, **8%** in Tier 2, **2%** in Tier 3, **1%** in Tier 4, **0.4%** in Tier 5 and **0.2%** in Tier 6 (your Luck still raises it). Before, nearly half of all dungeon kills dropped gear at every tier, sometimes several pieces at once
* **Change: ranged attacks lose damage over distance**
    * Arrows from bows and crossbows and staff bolts deal **full damage up to 10 blocks**, then less the further they fly: **75%** at 20 blocks, **40%** at 25, and only **1 damage** from 30 blocks or more. This applies to monsters, bosses and players alike
* **Change: the Abyssal Horror punishes attacks from afar**
    * Hit it from **20 blocks or more** away and a ring appears under you. Get off it fast: a tentacle bursts up there, seizes you and hurls you back into the fight
