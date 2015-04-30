# YGOPro Card Database #
This repository serves as a text based representation with version control of the YGOPro `card.cdb` file. It includes set labeled seperated id game id/serial number list which may be used to systematically query a given `card.cdb` for seed data, and then allow that data to be updated via text editing of SQL commands. The data is then re-entered into YGOPro Salvation's `card.cdb` as SQL commands server side propigating the updated information to duelist.

## Goals ##
- Create a list of all sets and the id numbers in those sets.
- Add setcode information
- Add alias information for alternate card art
- Build automated server rebuild system
- Start building support for other languages

- - -

## Set Checklist ##

### Booster Packs

###### Series 1-3/International
* [x] LEGEND OF BLUE EYES WHITE DRAGON
* [x] METAL RAIDERS
* [x] MAGIC/SPELL RULER
* [x] PHARAOH'S SERVANT
* [x] LABYRINTH OF NIGHTMARE
* [x] LEGACY OF DARKNESS
* [x] PHARAONIC GUARDIAN
* [x] MAGICIAN'S FORCE
* [x] DARK CRISIS
* [x] INVASION OF CHAOS
* [x] ANCIENT SANCTUARY
* ..
* [x] INVASION OF CHAOS: SPECIAL EDITION

###### Series 4
* [x] SOUL OF THE DUELIST
* [x] RISE OF DESTINY
* [x] FLAMING ETERNITY
* [ ] THE LOST MILLENNIUM
* [ ] CYBERNETIC REVOLUTION
* [ ] ELEMENTAL ENERGY
* [ ] SHADOW OF INFINITY
* [ ] ENEMY OF JUSTICE
- ..
* [x] RISE OF DESTINY: SPECIAL EDITION
* [x] THE LOST MILLENNIUM: SPECIAL EDITION
* [x] ELEMENTAL ENERGY: SPECIAL EDITION
* [x] SHADOW OF INFINITY: SPECIAL EDITION

###### Series 5
* [ ] POWER OF THE DUELIST
* [ ] CYBERDARK IMPACT
* [ ] STRIKE OF NEOS
* [ ] FORCE OF THE BREAKER
* [ ] TACTICAL EVOLUTION
* [ ] GLADIATOR'S ASSAULT
* [ ] PHANTOM DARKNESS
* [ ] LIGHT OF DESTRUCTION
* ..
* [ ] STRIKE OF NEOS: SPECIAL EDITION
* [x] FORCE OF THE BREAKER: SPECIAL EDITION
* [x] TACTICAL EVOLUTION: SPECIAL EDITION
* [x] GLADIATOR'S ASSAULT: SPECIAL EDITION
* [x] PHANTOM DARKNESS: SPECIAL EDITION
* [x] LIGHT OF DESTRUCTION: SPECIAL EDITION

###### Series 6
* [ ] THE DUELIST GENESIS
* [ ] CROSSROADS OF CHAOS
* [ ] CRIMSON CRISIS
* [ ] RAGING BATTLE
* [ ] ANCIENT PROPHECY
* [ ] STARDUST OVERDRIVE
* [ ] ABSOLUTE POWERFORCE
* [ ] THE SHINING DARKNESS
- ..
* [x] THE DUELIST GENESIS: SPECIAL EDITION
* [x] CROSSROADS OF CHAOS: SPECIAL EDITION
* [x] CRIMSON CRISIS: SPECIAL EDITION
* [x] RAGING BATTLE: SPECIAL EDITION
* [x] ANCIENT PROPHECY: SPECIAL EDITION
* [x] STARDUST OVERDRIVE: SPECIAL EDITION
* [ ] ABSOLUTE POWERFORCE SPECIAL EDITION

###### Series 7
* [ ] DUELIST REVOLUTION
* [ ] STARSTRIKE BLAST
* [ ] STORM OF RAGNAROK
* [ ] EXTREME VICTORY
* [ ] GENERATION FORCE
* [ ] PHOTON SHOCKWAVE
* [ ] ORDER OF CHAOS
* [ ] GALACTIC OVERLORD
- ..
* [ ] DUELIST REVOLUTION: SPECIAL EDITION
* [ ] STORM OF RAGNAROK: SPECIAL EDITION
* [ ] GENERATION FORCE: SPECIAL EDITION
* [ ] ORDER OF CHAOS: SPECIAL EDITION

###### Series 8
* [ ] RETURN OF THE DUELIST
* [x] ABYSS RISING
* [x] COSMO BLAZER
* [ ] LORD OF THE TACHYON GALAXY
* [ ] JUDGMENT OF THE LIGHT
* [ ] SHADOW SPECTERS
* [ ] LEGACY OF THE VALIANT
* [ ] PRIMAL ORIGIN
- ..
* [ ] RETURN OF THE DUELIST: SPECIAL EDITION
* [ ] ABYSS RISING: SPECIAL EDITION
* [ ] COSMO BLAZER: SPECIAL EDITION
* [ ] JUDGMENT OF THE LIGHT: DELUXE EDITION
* [ ] SHADOW SPECTERS: SPECIAL EDITION
* [ ] LEGACY OF THE VALIANT: DELUXE EDITION
* [ ] PRIMAL ORIGIN: DELUXE EDITION

###### Series 9
* [ ] DUELIST ALLIANCE
* [ ] THE NEW CHALLENGERS
* [x] SECRETS OF ETERNITY
* [ ] CROSSED SOULS
* [x] CLASH OF REBELLIONS
* [ ] DIMENSION OF CHAOS
- ..
* [ ] DUELIST ALLIANCE: DELUXE EDITION
* [ ] THE NEW CHALLENGERS: SUPER EDITION
* [ ] SECRETS OF ETERNITY: SUPER EDITION
* [ ] CROSSED SOULS: ADVANCE EDITION

#### Battle Packs
* [ ] BATTLE PACK EPIC DAWN
* [ ] BATTLE PACK 2 WAR OF THE GIANTS ROUND 2
* [ ] BATTLE PACK 2 WAR OF THE GIANTS REINFORCEMENTS
* [ ] BATTLE PACK 3 MONSTER LEAGUE

#### Duelist Packs
* [ ] DUELIST PACK - JADEN YUKI
* [ ] DUELIST PACK - CHAZZ PRINCETON
* [ ] DUELIST PACK - JADEN YUKI 2
* [ ] DUELIST PACK - ASTER PHOENIX
* [ ] DUELIST PACK - ZANE TRUESDALE
* [ ] DUELIST PACK - JADEN YUKI 3
* [ ] DUELIST PACK - JESSE ANDERSON
* [ ] DUELIST PACK - YUSEI
* [ ] DUELIST PACK - YUGI
* [ ] DUELIST PACK - YUSEI 2
* [ ] DUELIST PACK - KAIBA
* [ ] DUELIST PACK - YUSEI 3
* [ ] DUELIST PACK - CROW

### Extra Packs

#### Gold Series
* [ ] GOLD SERIES
* [ ] GOLD SERIES 2009
* [ ] GOLD SERIES 3
* [ ] GOLD SERIES 4 PYRAMIDS EDITION
* [ ] GOLD SERIES HAUNTED MINE

#### Hidden Arsenal
* [ ] HIDDEN ARSENAL
* [ ] HIDDEN ARSENAL 2
* [ ] HIDDEN ARSENAL 3
* [ ] HIDDEN ARSENAL 4 TRISHULA'S TRIUMPH
* [ ] HIDDEN ARSENAL 5 STEELSWARM INVASION
* [ ] HIDDEN ARSENAL 6 OMEGA XYZ
* [ ] HIDDEN ARSENAL 7 KNIGHT OF STARS

#### Mega Packs
* [ ] RA YELLOW MEGA PACK
* [ ] LEGENDARY COLLECTION 2 THE DUEL ACADEMY YEARS MEGA PACK
* [ ] LEGENDARY COLLECTION 3 YUGI'S WORLD MEGA PACK
* [ ] LEGENDARY COLLECTION 4 JOEY'S WORLD MEGA PACK
* [ ] 2014 MEGA-TINS MEGA PACK
* [ ] LEGENDARY COLLECTION 5D's MEGA PACK

#### Premium Packs
* [ ] PREMIUM PACK
* [ ] PREMIUM PACK 2
* [ ] PREMIUM PACK 3
* [ ] PREMIUM PACK 4
* [ ] PREMIUM PACK 5
* [ ] PREMIUM PACK 6
* [ ] PREMIUM PACK 7
* [ ] PREMIUM PACK 8
* [ ] PREMIUM PACK 9
* [ ] PREMIUM PACK 10
* [ ] PREMIUM PACK 11
* [ ] PREMIUM PACK 12
* [ ] PREMIUM PACK 13
* [ ] PREMIUM PACK 14
* [ ] PREMIUM PACK 15
* [ ] PREMIUM PACK 16
* [ ] PREMIUM PACK 17

#### Character Decks
* [ ] STARTER DECK YUGI
* [ ] STARTER DECK KAIBA
* [x] STARTER DECK JOEY
* [x] STARTER DECK PEGASUS
* [ ] STARTER DECK YUGI Evolution
* [ ] STARTER DECK KAIBA Evolution
* [x] STARTER DECK JADEN YUKI
* [x] STARTER DECK SYRUS TRUESDALE

#### Annual Decks
* [x] STARTER DECK 2006

#### Sneak Preview Cards

###### Series 1
* [x] SNEAK PREVIEW PARTICIPATION CARDS: SERIES 1 (Covers FET, TLM, CRV, EEN)

###### Series 2
* [x] SNEAK PREVIEW PARTICIPATION CARDS: SERIES 2 (Covers SOI, EOJ)
* [x] SNEAK PREVIEW PARTICIPATION CARDS: SERIES 2 (Covers POTD, CDIP)

###### Series 3
* [x] STRIKE OF NEOS: SNEAK PREVIEW
* [x] FORCE OF THE BREAKER: SNEAK PREVIEW
* [x] TACTICAL EVOLUTION: SNEAK PREVIEW
* [x] GLADIATOR'S ASSAULT: SNEAK PREVIEW
* [x] PHANTOM DARKNESS: SNEAK PREVIEW
* [x] LIGHT OF DESTRUCTION: SNEAK PREVIEW

###### Series 4
* [x] THE DUELIST GENESIS: SNEAK PREVIEW
* [x] CROSSROADS OF CHAOS: SNEAK PREVIEW
* [x] CRIMSON CRISIS: SNEAK PREVIEW
* [x] RAGING BATTLE: SNEAK PREVIEW
* [x] ANCIENT PROPHECY: SNEAK PREVIEW
* [x] STARDUST OVERDRIVE: SNEAK PREVIEW
* [x] ABSOLUTE POWERFORCE: SNEAK PREVIEW
* [x] THE SHINING DARKNESS: SNEAK PREVIEW

###### Series 5
* [x] DUELIST REVOLUTION: SNEAK PREVIEW
* [x] STARSTRIKE BLAST: SNEAK PREVIEW
* [x] STORM OF RAGNAROK: SNEAK PREVIEW
* [x] EXTREME VICTORY: SNEAK PREVIEW
* [x] GENERATION FORCE: SNEAK PREVIEW
* [x] PHOTON SHOCKWAVE: SNEAK PREVIEW
* [x] ORDER OF CHAOS: SNEAK PREVIEW
* [x] GALACTIC OVERLORD: SNEAK PREVIEW

###### Series 6
* [x] RETURN OF THE DUELIST: SNEAK PREVIEW
* [x] ABYSS RISING: SNEAK PREVIEW
* [x] COSMO BLAZER: SNEAK PREVIEW
* [x] LORD OF THE TACHYON GALAXY: SNEAK PREVIEW
* [ ] JUDGMENT OF THE LIGHT: SNEAK PREVIEW
* [ ] SHADOW SPECTERS: SNEAK PREVIEW
* [ ] LEGACY OF THE VALIANT: SNEAK PREVIEW
* [ ] PRIMAL ORIGIN: SNEAK PREVIEW

###### Series 7
* [ ] DUELIST ALLIANCE: SNEAK PREVIEW
* [ ] THE NEW CHALLENGERS: SNEAK PREVIEW
* [ ] SECRETS OF ETERNITY: SNEAK PREVIEW
* [ ] CROSSED SOULS: SNEAK PREVIEW

#### Other
* [ ] NOBLE KNIGHTS OF THE ROUND TABLE BOX SET Power-Up Pack
* [ ] STAR PACK 2014
* [ ] SUPER STARTER SPACE-TIME SHOWDOWN Power-Up Pack
* [ ] DRAGONS OF LEGEND
* [ ] NUMBER HUNTERS
* [ ] BATTLE PACK 2 WAR OF THE GIANTS
* [ ] SUPER STARTER Power-Up Pack
* [ ] STAR PACK 2013
* [ ] GENERATION FORCE
* [x] 10th ANNIVERSARY MOVIE
* [x] 3D BONDS BEYOND TIME MOVIE PACK
* [ ] RETRO PACK 2
* [ ] ANNIVERSARY PACK
* [ ] DARK LEGENDS
* [ ] RETRO PACK
* [ ] DARK CRISIS (Reprint)
* [ ] DARK REVELATION Volume 4
* [ ] FORCE OF THE BREAKER
* [ ] DARK REVELATION Volume 3
* [ ] DARK REVELATION Volume 2
* [ ] DARK BEGINNING 2
* [ ] DARK REVELATION Volume 1
* [ ] DARK BEGINNING 1
* [ ] EXCLUSIVE PACK
* [ ] FIRE FISTS SPECIAL EDITION
* [ ] RA YELLOW MEGA PACK SPECIAL EDITION
* [ ] HIDDEN ARSENAL 5 STEELSWARM INVASION SPECIAL EDITION
* [ ] SAMURAI ASSAULT
* [ ] HIDDEN ARSENAL SPECIAL EDITION
* [ ] X-SABER POWER-UP
* [ ] TWILIGHT EDITION - LIGHT & DARK -
* [ ] GX NEXT GENERATION
* [ ] DUELIST PACK SPECIAL EDITION
* [ ] STRUCTURE DECK DINOSAUR'S RAGE SPECIAL EDITION
* [ ] SUPER STARTER SPACE-TIME SHOWDOWN
* [ ] STARTER DECK KAIBA RELOADED
* [ ] STARTER DECK YUGI RELOADED
* [ ] SUPER STARTER V FOR VICTORY
* [ ] STARTER DECK XYZ SYMPHONY
* [x] STARTER DECK DAWN OF THE XYZ
* [x] 5D's STARTER DECK DUELIST TOOLBOX
* [x] 5D's STARTER DECK 2009
* [x] 5D's STARTER DECK 2008
* [ ] THE SECRET FORCES








* [ ] HERO STRIKE STRUCTURE DECK
* [ ] GEARGIA RAMPAGE STRUCTURE DECK
* [ ] REALM OF LIGHT STRUCTURE DECK
* [ ] CYBER DRAGON REVOLUTION STRUCTURE DECK
* [ ] SAGA OF BLUE-EYES WHITE DRAGON STRUCTURE DECK
* [ ] ONSLAUGHT OF THE FIRE KINGS STRUCTURE DECK
* [ ] REALM OF THE SEA EMPEROR STRUCTURE DECK
* [ ] SAMURAI WARLORDS STRUCTURE DECK
* [ ] DRAGONS COLLIDE STRUCTURE DECK
* [ ] GATES OF THE UNDERWORLD STRUCTURE DECK
* [ ] LOST SANCTUARY STRUCTURE DECK
* [ ] DRAGUNITY LEGION STRUCTURE DECK
* [x] STRUCTURE DECK - MARIK -
* [x] MACHINA MAYHEM STRUCTURE DECK
* [x] WARRIORS' STRIKE STRUCTURE DECK
* [x] SPELLCASTER'S COMMAND STRUCTURE DECK
* [x] ZOMBIE WORLD STRUCTURE DECK
* [x] THE DARK EMPEROR STRUCTURE DECK
* [x] RISE OF THE DRAGON LORDS STRUCTURE DECK
* [x] STRUCTURE DECK MACHINE RE-VOLT
* [ ] STRUCTURE DECK DINOSAUR'S RAGE
* [x] STRUCTURE DECK LORD OF THE STORM
* [x] STRUCTURE DECK INVINCIBLE FORTRESS
* [x] STRUCTURE DECK SPELLCASTER'S JUDGMENT
* [x] STRUCTURE DECK WARRIOR'S TRIUMPH
* [x] STRUCTURE DECK FURY FROM THE DEEP
* [x] STRUCTURE DECK BLAZE OF DESTRUCTION
* [x] STRUCTURE DECK ZOMBIE MADNESS
* [x] STRUCTURE DECK DRAGON'S ROAR
* [ ] 2014 MEGA-TINS
* [ ] COLLECTIBLE TIN 2013 WAVE 2
* [ ] COLLECTIBLE TIN 2013 WAVE 1
* [ ] ZEXAL COLLECTION TIN
* [ ] COLLECTIBLE TIN 2012 WAVE 2.5
* [ ] COLLECTIBLE TIN 2012 WAVE 2
* [ ] COLLECTIBLE TIN 2012 WAVE 1
* [ ] PREMIUM COLLECTION TIN
* [ ] COLLECTIBLE TIN 2011 WAVE 2
* [ ] COLLECTIBLE TIN 2011 WAVE 1
* [ ] DUELIST PACK COLLECTION TIN 2011
* [ ] COLLECTIBLE TIN 2010 WAVE 2
* [ ] COLLECTIBLE TIN 2010 WAVE 1
* [ ] DUELIST PACK COLLECTION TIN 2010
* [ ] COLLECTIBLE TIN 2009 WAVE 2
* [ ] EXCLUSIVE TINS 2009
* [ ] COLLECTIBLE TIN 2009 WAVE 1
* [ ] DUELIST PACK COLLECTION TIN 2009
* [ ] EXCLUSIVE TINS 2008
* [ ] COLLECTIBLE TIN SERIES 5 WAVE 1
* [ ] DUELIST PACK COLLECTION - JADEN YUKI - TIN
* [ ] DUELIST PACK COLLECTION TIN 2008
* [ ] COLLECTIBLE TIN SERIES 4 WAVE 2
* [ ] COLLECTIBLE TIN SERIES 4 WAVE 1
* [ ] COLLECTIBLE TIN SERIES 3 WAVE 2
* [ ] COLLECTIBLE TIN SERIES 3 WAVE 1
* [ ] COLLECTIBLE TIN SERIES 2
* [ ] COLLECTIBLE TIN SERIES 1
* [ ] DUEL TERMINAL 7B
* [ ] DUEL TERMINAL 7A
* [ ] DUEL TERMINAL 6B
* [ ] DUEL TERMINAL 6A
* [ ] DUEL TERMINAL 5B
* [ ] DUEL TERMINAL 5A
* [ ] DUEL TERMINAL 4
* [ ] DUEL TERMINAL 3
* [ ] DUEL TERMINAL 2
* [ ] DUEL TERMINAL 1
* [ ] DUEL TERMINAL - PREVIEW WAVE 2
* [ ] DUEL TERMINAL - PREVIEW WAVE 1
* [ ] PREMIUM GOLD: RETURN OF THE BLING
* [ ] NOBLE KNIGHTS OF THE ROUND TABLE BOX SET
* [ ] LEGENDARY COLLECTION 5D's
* [ ] PREMIUM GOLD
* [ ] LEGENDARY COLLECTION 4 JOEY'S WORLD
* [ ] LEGENDARY COLLECTION 3 YUGI'S WORLD
* [ ] LEGENDARY COLLECTION 2 THE DUEL ACADEMY YEARS
* [ ] LIGHT & DARKNESS - POWER PACK -
* [ ] 5D's volume 7 Promotional Card
* [ ] SHONEN JUMP ALPHA membership Promotional Card - February 2015 -
* [ ] Zexal volume 6 Promotional Card
* [ ] SHONEN JUMP ALPHA membership Promotional Card - October 2014 -
* [ ] 5D's volume 6 Promotional Card
* [ ] SHONEN JUMP ALPHA membership Promotional Card - July 2014 -
* [ ] Zexal volume 5 Promotional Card
* [ ] SHONEN JUMP ALPHA membership Promotional Card - March 2014 -
* [ ] Zexal volume 4 Promotional Card
* [ ] SHONEN JUMP ALPHA membership Promotional Card - December 2013 -
* [ ] 5D's volume 5 Promotional Card
* [ ] SHONEN JUMP ALPHA membership Promotional Card - October 2013 -
* [ ] SHONEN JUMP ALPHA membership Promotional Card - July 2013 -
* [ ] Zexal volume 3 Promotional Card
* [ ] 5D's volume 4 Promotional Card
* [ ] SHONEN JUMP ALPHA membership Promotional Card - March 2013 -
* [ ] SHONEN JUMP ALPHA membership Promotional Card - December 2012 -
* [ ] Zexal volume 2 Promotional Card
* [ ] SHONEN JUMP ALPHA membership Promotional Card - September 2012 -
* [ ] 5D's volume 3 Promotional Card
* [ ] SHONEN JUMP ALPHA membership Promotional Card - July 2012 -
* [ ] GX volume 9 Promotional Card
* [ ] ZEXAL volume 1 Promotional Card
* [ ] SHONEN JUMP ALPHA membership Promotional Card - April 2012 -
* [ ] SHONEN JUMP Promotional Card - April 2012 -
* [ ] SHONEN JUMP Promotional Card - March 2012 -
* [ ] 5D's volume 2 Promotional Card
* [ ] GX volume 8 Promotional Card
* [ ] SHONEN JUMP Promotional Card - January 2012 -
* [ ] SHONEN JUMP Subscription Promotional Card - December 2011 -
* [ ] SHONEN JUMP Promotional Card - December 2011 -
* [ ] SHONEN JUMP Promotional Card - September 2011 -
* [ ] GX volume 7 Promotional Card
* [ ] 5D's volume 1 Promotional Card
* [ ] SHONEN JUMP Subscription Promotional Card - June/July 2011 -
* [ ] SHONEN JUMP Promotional Card - June/July 2011 -
* [ ] SHONEN JUMP Promotional Card - April 2011 -
* [ ] GX volume 6 Promotional Card
* [ ] SHONEN JUMP Promotional Card - March 2011 -
* [ ] SHONEN JUMP Promotional Card - January 2011 -
* [ ] SHONEN JUMP Scholastic Edition Promotional Card
* [ ] SHONEN JUMP Subscription Promotional Card - December 2010 -
* [ ] SHONEN JUMP Promotional Card - November 2010 -
* [ ] GX volume 5 Promotional Card
* [ ] SHONEN JUMP Promotional Card - September 2010 -
* [ ] SHONEN JUMP Promotional Card - July 2010 -
* [ ] R volume 5 Promotional Card
* [ ] SHONEN JUMP Subscription Promotional Card - May 2010 -
* [ ] SHONEN JUMP Promotional Card - May 2010 -
* [ ] R volume 4 Promotional Card
* [ ] SHONEN JUMP Subscription Promotional Card - March 2010 -
* [ ] SHONEN JUMP Promotional Card - March 2010 -
* [ ] GX volume 4 Promotional Card
* [ ] SHONEN JUMP Promotional Card - January 2010 -
* [ ] SHONEN JUMP Promotional Card - November 2009 -
* [ ] SHONEN JUMP Promotional Card - September 2009 -
* [ ] GX volume 3 Promotional Card
* [ ] SHONEN JUMP Promotional Card - May 2009 -
* [ ] SHONEN JUMP Promotional Card - March 2009 -
* [ ] SHONEN JUMP Subscription Promotional Card - February 2009 -
* [ ] SHONEN JUMP Promotional Card - January 2009 -
* [ ] SHONEN JUMP Promotional Card - November 2008 -
* [ ] GX volume 2 Promotional Card
* [ ] SHONEN JUMP Promotional Card - September 2008 -
* [ ] SHONEN JUMP FIFTH ANNIVERSARY COLLECTOR’S EDITION Promotional Card
* [ ] SHONEN JUMP Subscription Promotional Card - May 2008 -
* [ ] SHONEN JUMP Promotional Card - May 2008 -
* [ ] SHONEN JUMP Promotional Card - March 2008 -
* [ ] SHONEN JUMP 4-CARD PACK
* [ ] SHONEN JUMP Promotional Card - January 2008 -
* [ ] GX volume 1 Promotional Card
* [ ] SHONEN JUMP Promotional Card - November 2007 -
* [ ] SHONEN JUMP Promotional Card - September 2007 -
* [ ] SHONEN JUMP Subscription Promotional Card - July 2007 -
* [ ] SHONEN JUMP Promotional Card - June 2007 -
* [ ] SHONEN JUMP Promotional Card - April 2007 -
* [ ] SHONEN JUMP Promotional Card - January 2007 -
* [ ] SHONEN JUMP Promotional Card - December 2006 -
* [ ] SHONEN JUMP Promotional Card - November 2006 -
* [ ] SHONEN JUMP Promotional Card - September 2006 -
* [ ] Millennium World volume 4 Promotional Card
* [ ] DUELIST volume 16 Promotional Card
* [ ] SHONEN JUMP Promotional Card - January 2006 -
* [ ] SHONEN JUMP Promotional Card - January 2005 -
* [ ] ASTRAL PACK SIX
* [ ] CHAMPIONSHIP SERIES 2014
* [ ] WORLD CHAMPIONSHIP 2014
* [ ] ASTRAL PACK FIVE
* [ ] DUELIST LEAGUE 18
* [ ] ASTRAL PACK FOUR
* [ ] DUELIST LEAGUE 17
* [ ] ASTRAL PACK THREE
* [ ] CHAMPIONSHIP SERIES 2013
* [ ] WORLD CHAMPIONSHIP 2013
* [ ] DUELIST LEAGUE 16
* [ ] ASTRAL PACK TWO
* [ ] DUELIST LEAGUE 15
* [ ] ASTRAL PACK ONE
* [ ] CHAMPIONSHIP SERIES 2012
* [ ] WORLD CHAMPIONSHIP 2012
* [ ] TURBO PACK BOOSTER EIGHT
* [ ] DUELIST LEAGUE 14
* [ ] BATTLE PACK TOURNAMENT
* [ ] TURBO PACK BOOSTER SEVEN
* [ ] DUELIST LEAGUE 13
* [ ] WORLD CHAMPIONSHIP 2011
* [ ] CHAMPIONSHIP SERIES 2011
* [ ] TURBO PACK BOOSTER SIX
* [ ] DUELIST LEAGUE 3
* [ ] WORLD CHAMPIONSHIP 2011 Qualifier
* [ ] TURBO PACK BOOSTER FIVE
* [ ] DUELIST LEAGUE 2
* [ ] TURBO PACK BOOSTER FOUR
* [ ] WORLD CHAMPIONSHIP 2010
* [ ] TURBO PACK BOOSTER THREE
* [ ] CHAMPIONSHIP SERIES 2010
* [ ] SHONEN JUMP Championship 2009
* [ ] TURBO PACK BOOSTER TWO
* [ ] TURBO PACK BOOSTER ONE
* [ ] WORLD CHAMPIONSHIP 2009
* [ ] DUELIST LEAGUE 2010
* [ ] DUELIST LEAGUE DEMO 2010
* [ ] CHAMPION PACK GAME EIGHT
* [ ] CHAMPION PACK GAME SEVEN
* [ ] WORLD CHAMPIONSHIP 2008
* [ ] HOBBY LEAGUE 7
* [ ] CHAMPION PACK GAME SIX
* [ ] SHONEN JUMP Championship 2008
* [ ] HOBBY LEAGUE 6
* [ ] CHAMPION PACK GAME FIVE
* [ ] PHARAOH TOUR 2007
* [ ] CHAMPION PACK GAME FOUR
* [ ] SHONEN JUMP Championship 2007 B
* [ ] WORLD CHAMPIONSHIP 2007
* [ ] HOBBY LEAGUE 5
* [ ] CHAMPION PACK GAME THREE
* [ ] HOBBY LEAGUE 4
* [ ] CHAMPION PACK GAME TWO
* [ ] SHONEN JUMP Championship 2007 A
* [ ] CHAMPION PACK GAME ONE
* [ ] PHARAOH TOUR 2006
* [ ] WORLD CHAMPIONSHIP 2006
* [ ] HOBBY LEAGUE 3
* [ ] SHONEN JUMP Championship 2006
* [ ] DUELIST LEAGUE SERIES 10
* [ ] TOURNAMENT PACK 8
* [ ] DUELIST LEAGUE SERIES 9
* [ ] HOBBY LEAGUE 2
* [ ] PHARAOH TOUR 2005
* [ ] TOURNAMENT PACK 7
* [ ] SHONEN JUMP Championship 2005
* [ ] WORLD CHAMPIONSHIP 2005
* [ ] DUELIST LEAGUE SERIES 8
* [ ] TOURNAMENT PACK 6
* [ ] DUELIST LEAGUE SERIES 7
* [ ] SHONEN JUMP Championship 2004
* [ ] DUELIST LEAGUE SERIES 6
* [ ] TOURNAMENT PACK 5
* [ ] HOBBY LEAGUE 1
* [ ] WORLD CHAMPIONSHIP 2004
* [ ] DUELIST LEAGUE SERIES 5
* [ ] DUELIST LEAGUE SERIES 4
* [ ] DUELIST LEAGUE SERIES 3
* [ ] TOURNAMENT PACK 4
* [ ] WORLD CHAMPIONSHIP 2003
* [ ] DUELIST LEAGUE SERIES 2
* [ ] DUELIST LEAGUE SERIES 1
* [ ] TOURNAMENT PACK 3RD SEASON
* [ ] TOURNAMENT PACK 2ND SEASON
* [ ] TOURNAMENT PACK 1ST SEASON
* [ ] DEMO DECK 2015
* [ ] 3D BONDS BEYOND TIME Promotional Card
* [ ] DEMO DECK
* [ ] WORLD CHAMPIONSHIP 2010 CARD PACK
* [ ] Promotional Cards 2
* [x] MOVIE PACK
* [ ] Promotional Cards 1
* [ ] ZEXAL World Duel Carnival Bundles (UK)
* [x] 5D's WORLD CHAMPIONSHIP 2011 － OVER THE NEXUS － Bundles
* [x] 5D's DuelTranser Bundles
* [ ] 5D's TAG FORCE 5 Bundles
* [x] 5D's WORLD CHAMPIONSHIP 2010 － Reverse of Arcadia － Bundles
* [ ] 5D's TAG FORCE 4 Bundles
* [x] 5D's Wheelie Breakers Bundles
* [x] 5D's STARDUST ACCELERATOR － WORLD CHAMPIONSHIP 2009 － Bundles
* [ ] GX TAG FORCE 3 Bundles
* [x] GX The Beginning of Destiny Bundles
* [x] WORLD CHAMPIONSHIP 2008 Bundles
* [x] GX TAG FORCE 2 Bundles
* [x] WORLD CHAMPIONSHIP 2007 Bundles
* [x] GX SPIRIT CALLER Bundles
* [x] GX TAG FORCE Bundles
* [x] ULTIMATE MASTERS - World Championship Tournament 2006 - Bundles
* [x] GX Duel Academy Bundles
* [x] NIGHTMARE TROUBADOUR Bundles
* [x] 7 Trials to Glory - World Championship Tournament 2005 - Bundles
* [x] CAPSULE MONSTER COLISEUM Bundles
* [x] Destiny Board Traveler Bundles
* [x] POWER OF CHAOS JOEY THE PASSION Bundles
* [x] RESHEF OF DESTRUCTION Bundles
* [x] POWER OF CHAOS KAIBA THE REVENGE Bundles
* [x] THE DAWN OF DESTINY Bundles
* [x] World Championship Tournament 2004 Bundles
* [x] POWER OF CHAOS YUGI THE DESTINY Bundles
* [x] The Sacred Cards Bundles
* [x] The Falsebound Kingdom Bundles
* [x] Worldwide Edition - Stairway to the Destined Duel - Bundles
* [x] THE DUELISTS OF THE ROSES Bundles
* [x] THE ETERNAL DUELIST SOUL Bundles
* [x] FORBIDDEN MEMORIES Bundles
* [x] Dark Duel Stories Bundles
