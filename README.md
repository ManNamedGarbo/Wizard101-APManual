# Wizard101-Manual-Apworld
A Wizard101 randomizer apworld intended for use with Archipelago built using Manual,

The initial apworld is on Manual Stable 12/03/2023 and as I make more releases, the manual version and archipelago version used will be listed within each release to avoid confusion about compatibility.
The goal I have in mind for this randomizer is to Kill the Kraken, this will be done by gating equipment and areas to slow down progress until other people in the multiworld can send items to help you complete the seed.

This is not yet finished, below are my preliminary notes. I will update this later once I've properly drafted rules and logic properly for how this should work. These notes will not have the exact same spelling as in the manual itself.

----------------------------

-----**Quests**-----
`Quest: Unicorn Way` from Merle Ambrose in Wizard City - Go to Unicorn Way and speak with Private Connelly
`Quest: Ghost Hunters` from Private Connelly in Unicorn Way - Defeat 2 Lost Souls then turn in to Ceren Nightchant
`Quest: Skeleton Crew` from Ceren Nightchant in Unicorn Way - Defeat 2 Skeletal Pirates then turn in to Ceren Nightchant
`Quest: Pesky Pirates` from Olivia Dawnwillow in Unicorn Way - Defeat 1 Skeletal Pirate then talk to Olivia Dawnwillow
`Quest: Monsters and Mazes` from Ceren Nightchant in Unicorn Way - Talk to Lady Oriel in the Hedge Maze and turn in there as well.
`Quest: Saving Private O'Ryan` from Private Connelly in Unicorn Way - Talk to Private O'Ryan in Unicorn Way, then defeat Lady Blackhope in Blackhope Tower, talk to Private O'Ryan again, then turn in to Private Connelly.
`Quest: Finding Out Why` from Lady Oriel in Hedge Maze - Open 1 Bone Cage then Defeat Dark Fairies to collect 2 Fairy Dust, then Open 2 Bone Cage, then turn in to Lady Oriel.
`Quest: Who Could It Be Now?` from Lady Oriel in Hedge Maze - Talk to Ceren Nightchant in Unicorn Way
`Quest: Sinister Skeleton` from Ceren Nightchant in Unicorn Way - Go to The Archives in Unicorn Way and Defeat Rattlebones, then turn in to Ceren Nightchant
`Quest: Grim Tales` from Ceren Nightchant in Unicorn Way - Talk to Harold Argleston in the Wizard City Library, then turn in to Merle Abrose in The Commons
`Quest: Yellow Brick Road` from Private Connelly in Unicorn Way (requires completing 'Finding Out Why' and 'Saving Private O'Ryan' - Talk to Dorothy Gale in Unicorn Way and turn in the quest.
`Quest: Not In Kansas Anymore` from Dorothy Gale in Unicorn Way - Visit Dorothy Gale's friends in Unicorn Way, talk to Dorothy Gale, then turn in to Private Connelly
`Quest: To Ravenwood!` from Merle Ambrose in The Commons - Talk to Mr Lincoln in Ravenwood, then talk to your school's professor, then talk to Mr Lincoln again, then turn in to Merle Ambrose.
`Quest: Panic In Three Streets!` from Merle Ambrose in The Commons - Talk to Sergeant Muldoon in Olde Town and turn in the quest.
`Quest: City Tour` from Abby Doodle in The Commons - Talk to Abby Doodle in The Commons, then in Unicorn Way, then in the Shopping District, then turn in the quest by entering Olde Town.
`Quest: Say Cheese!` from Annie Shutterbug in Golem Court - Use photomancy from your backpack to take a picture in Golem Court, then turn in to Annie Shutterbug
`Quest: Ready, Aim, Shoot!` from Annie Shutterbug in Golem Court - Use photomancy from your backpack to take a picture of Mr Lincoln in Ravenwood, Hilda Brewer in The Commons, and Sergeant Muldoon in Olde Town, then turn in to Annie Shutterbug in Golem Court.
`Quest: Secret Strife of Pets` from Sergeant Muldoon in Olde Town - Walk up to the pet in Olde Town, then enter the Caretaker's Tower (requires a pet), then Defeat Old Judd, go upstairs using pet view and pick up the Kennel Key, then give the key to Penny Dreadful (if you have the Kennel Key unlocked) and free the pets, talk to Penny Dreadful again, then turn in to Sergeant Muldoon in Olde Town
`Quest: Trouble On Triton Avenue` from Sergeant Muldoon in Olde Town - Go to Triton Avenue and talk to Artur Gryphonbane to turn in the quest.
`Quest: Wizards In The Mist` from Eudora Tangletree in Olde Town - Collect Mist Wood anywhere in Unicorn Way, Triton Avenue, or Olde Town then turn in to Eudora Tangletree
`Quest: The Razor's Edge` from Eudora Tangletree in Olde Town - Purchase the Dagger of Absolution recipe from Eudora, then purchase 2 Black Coal and 2 Sapphire from the Reagent vendor, then collect 2 Mist Wood and 2 Cat Tail from anywhere in Unicorn Way, Triton Avenue, or Olde Town then teleport to your home in Ravenwood, place down a Basic Crafting Station, then craft 2 Dagger of Absolution, then turn in to Eudora Tangletree in Olde Town
`Quest: Hey, Penny` from Penny Dreadful in The Commons - Talk to Mr Lincoln in Ravenwood, then talk to Merle Ambrose in The Commons, then turn in to Penny Dreadful.
`Quest: Dreadful Assignment` from Penny Dreadful in The Commons - Defeat a Lost Soul in Unicorn Way, a Skeletal Pirate in Unicorn Way, a Rotting Fodder in Triton Avenue, and a Field Guard in the Haunted Cave, then turn in to Penny Dreadful in The Commons.
`Quest: Diego the Duelmaster` from Merle Ambrose in The Commons - Talk to Diego the Duelmaster in Unicorn Way
`Quest: Advanced Combat` from Diego the Duelmaster in Unicorn Way - Enter the Duel Arena from Unicorn Way and complete Diego's tutorial on advanced combat, then turn in the quest by leaving the Duel Arena.
`Quest: Pet Sounds` from Merle Ambrose in The Commons - Talk to Milo Barker in the Pet Pavilion and turn in the quest.
`Quest: Walkabout` from Private Guildenstern in Olde Town - Talk to Harold Argleston in the Wizard City Library, then Sabrina Greenstar in The Commons, then turn in to Regina Flametalon in Golem Court
`Quest: Science Fair` from Regina Flametalon in Golem Court - Enter the Golem Tower and Defeat a Wooden Construct for Enchanted Wood, then turn in to Regina Flametalon
`Quest: Second Gear` from Regina Flametalon in Golem Court - Enter the Golem Tower and Defeat a Clockwork Golem for a Charged Gear, then turn in to Regina Flametalon
`Quest: The Final Piece` from Regina Flametalon in Golem Court - Enter the Golem Tower and Defeat an Iron Golem for a Steam Capacitor, then turn in to Regina Flametalon
`Quest: A Wizard's Best Friend` from Milo Barker in the Pet Pavilion - Talk to Sir Nigel Higgenbottom, then talk to Dusty Shadowcloud, then to Tennant Wastelander, then Doctor Purreau, then Higgenbottom again, then turn in to Milo Barker.
`Quest: Menacing Minions` from Artur Gryphonbane in Triton Avenue - Defeat 3 Haunted Minions then turn in to Artur Gryphonbane
`Quest: The Shadow of Death Magic` from Artur Gryphonbane in Triton Avenue - Talk to Duncan Grimwater, then Defeat an Electric Eel for Suzie's Wand, then turn in to Duncan Grimwater.
`Quest: All The Eels` from Sohomer Sunblade in Triton Avenue - Defeat 3 Electric Eels then turn in to Sohomer Sunblade.
`Quest: Wayward Barrels` from Sohomer Sunblade in Triton Avenue - Collect 3 Crystal Barrels then turn in to Sohomer Sunblade
`Quest: Quest for Clues` from Duncan Grimwater in Triton Avenue - Defeat 3 Rotting Fodder then turn in to Duncan Grimwater
`Quest: A Scrap Of Trouble` from Sandor Spitfire in Triton Avenue - Defeat Rotting Fodder until 3 Storm Amulets drop, talk to Sandor Spitfire, then go to Skull Fort and Defeat Sergeant Skullsplitter, then turn in to Sandor Spitfire
`Quest: Catching A Glimpse` from Duncan Stormwater in Triton Avenue - Turn in to Blad Raveneye in Triton Avenue
`Quest: Clear As Crystal` from Blad Raveneye in Triton Avenue - Collect 3 Cogs from the road in Triton Avenue, then Defeat Scarlet Screamers to collect 3 Primary Coils, talk to Blad Raveneye, then go to the Mill Wheel in the water, pull the lever nearby, and turn in to Blad.
`Quest: Luminate` from Blad Raveneye in Triton Avenue - Talk to Duncan Grimwater and turn in the quest.
`Quest: The Enemy Revealed` from Duncan Grimwater in Triton Avenue - Go to Galvanost Tower in Triton Avenue and Defeat The Harvest Lord, talk to Suzie Gryphonbane outside the tower, then turn in to Suzie Gryphonbane at the High Ledge in Triton Avenue
`Quest: To Tame A Tempest` from Suzie Gryphonbane in Triton Avenue - Talk to Halston Balestrom in Ravenwood, Fix the tempest nexus at the High Ledge in Triton Avenue, talk to Suzie, then turn in to Artur Gryphonbane
`Quest: Triton Report` from Suzie Gryphonbane in Triton Avenue - Turn in to Sergeant Muldoon in Olde Town
`Quest: Haunting Questions` from Duncan Grimwater in Triton Avenue - Look at the broken wand in front of the Haunted Cave, then talk to Duncan Grimwater in the Haunted Cave
`Quest: Better Get Kraken` from Sohomer Sunblade in Triton Avenue - Defeat Rotting Fodder until a Teleporter Keystone drops then turn in to Sohomer Sunblade
`Quest: Decease The Kraken!` from Sohomer Sunblade in Triton Avenue - Enter the teleporter to Kraken Isle, defeat the Kraken, and turn in the quest to Sohomer Sunblade. 
`Quest: Secret Of The Cave` from Duncan Grimwater in Haunted Cave - Defeat 3 Field Guards, talk to Duncan, then talk to Duncan further in the Dark Cave to turn in the quest.


-----**Items**-----
Unlock Hats
Unlock Robe
Unlock Boots
Unlock Wands
Unlock Athames
Unlock Amulets
Unlock Rings
Unlock Pets
Unlock Decks
Unlock Treasure Cards (useful)
Unlock Go to The Commons Button
Unlock Go Home Button
Unlock Mark Location Button
Unlock Teleport to Marked Location Button
Unlock Flasks
Kraken Isle Teleporter
Upper-Lower Triton Avenue Teleporter
High Ledge Teleporter
Caretaker's Tower Kennel Key 


-----**Regions**-----
The Commons (Wizard City/Starting Zone)
Unicorn Way
Hedge Maze (subzone of Unicorn Way)
Blackhope Tower (subzone of Unicorn Way)
The Archives (subzone of Unicorn Way)
Wizard City Library (subzone of Wizard City/The Commons)
Ravenwood (subzone of The Commons)
Shopping District(subzone of The Commons)
Olde Town (subzone of Shopping District)
Golem Court (subzone of The Commons)
Golem Tower (subzone of Golem Court)
Caretaker's Tower (subzone of Olde Town)
Duel Arena (subzone of Unicorn Way)
Pet Pavilion (subzone of The Commons)
Triton Avenue
Haunted Cave (subzone of Triton Avenue)
Galvanost Tower (subzone of Triton Avenue)
Skull Fort (subzone of Lower Triton Avenue)


-----**Other Checks**-----
Smith - Unicorn Way
Smith - Golem Court
Smith - Ravenwood
Smith - The Commons
Smith - Shopping District
Smith - Olde Town
Smith - Triton Avenue
History of Magic - Blackhope Tower
History of Magic - Triton Avenue
Spend a Training Point
Open a Wooden Chest
Caretaker's Tower Kennel Key 
