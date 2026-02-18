1.1 "Washington"
first post-launch patch

The US now starts in phase 1 of Universal Suffrage rather than phase 2
Millard Filmore is now a Moderate
John Sutter shouldn't spawn as Planters leader anymore
Tweaks to Two-Party System [merged from USCWF by Ferrous]
Additional support to the Democrats in initial elections
Slavery Banned will now empower the Enact Slave Trade movement
Slavery will no longer spread west if you banned slavery
Adjusted parameters for the Homestead Acts
Fixed error log spam from Manifest Destiny buttons
Fixed Bleeding Kansas not ending if you go above 100%
Fixed Missouri Compromise Broken trigger tooltip

Long Reconstruction now replaces the PB's Segregationist ideology with Exclusionary

1.2 "Washington"
Introduced more chaos into election campaigns for all countries with Census or Universal Suffrage
Adjusted Canadian Confederation to account for map changes
Fixed event-spawned characters spawning without an IG
Fixed special loc on Suppress/Promote Continentalism tooltips

1.3 "Washington"
Encouraged the north american AI to place more colonies at game start
Define NUM_GROWING_COLONIES_MAX is now 7
Increased the strength of the US Two-Party System
A House Divided JE will no longer fire slavery-related events if slavery is banned

1.4 "Washington"
Added ideologies to historical generals/admirals, mostly to prevent them from spawning as vanguardists erroneously
Bill Haywood no longer automatically becomes leader of the TUs
Nominating Lincoln now grants his IG a temporary clout boost
Ulysses Grant is now a Radical Abolitionist
American soldiers now wear blue uniforms
Confederate soldiers now wear grey uniforms
New flags for alternate US governments (Dictatorship, Monarchy, Anarchy, Council Republic w/ Universal Suffrage)
Mexican Purchase can't be offered again if choose to gain claims
Reduced cooldown on Mexican Purchase offer to 3 years
Ensured AI US will get claims on Mexico and pursue them if possible
Re-added vanilla Bison Hunting event, to the Wild West JE
Hopefully ensured the Democratic Party doesn't dissolve before the ACW
Adjusted parameters for the Homestead Acts
Bleeding Kansas spawns more radicals at the outset
Trent Affair will now spawn correctly
Slightly nerfed the colony debuff from Effective Native Resistance
Fixed some script errors

2.0 "Jefferson"
New Content:
	Added Mormon Content, including the founding of Deseret and the Utah War
	Added new decentralized tags across northern Canada and Alaska
	New Oregon Trail events
	New set of dynamic country names for various american governments, such as the Union of Sociliast American States or the American Technate
	New game rule that controls whether the USA should always retain the "USA" initials or not
	Added the Lost Cause as a post-civil war Landowner IG Trait
	The FSA can now choose to attempt to annex the USA
	New event for losing the ACW
	New event for failing Manifest Destiny
	New post-ACW event that bolsters the Armed Forces
	New rare assassination attempt on the President by an insane office-seeker (ala James Garfield)
	USA now begins the game with Abolitionist (William Lloyd Garrison) and Slaver (Robert Rhett) agitators
Updates:
	Democratic Experiment is now Loyalists from Legitimacy rather than SoL
	Newfoundland now begins as a puppet of Great Britain
	Canadian Confederation now completes if you annex the rest of the canadian tags (excluding Newfoundland)
	Buffed the Compromise of 1820
	Adjustments to decentralized tags in the american west
	New flags for some decentralized tags
	Peculiar Reconciliation can now lead into Long Reconstruction if you've lifted racial segregration
	Added some migration pull and MAPI to the White House
	Added notifications for when Manifest Destiny gains/loses influence
	Decreased the frequency of ACW election-spawned agitators
	Moved some agitator slots to the Second/Third Party System modifiers
	Universal Suffrage now begins with a positive enactment modifier
	Added is_usfp_active scripted trigger as a mod compatibility hook
	Added Game Concept explaining the Westward Expansion requirements
Fixes:
	The Whigs will now collapse if a slavery revolt reaches 50% progress
	Fixed Westward Expansion homelands not accounting for the American Superculture
	The Mexican Cession now also annexes northern California to prevent weirdness around Frontier Colonization limitations
	Adjusted treaty options for the Treaty of Guadalupe Hidalgo
	Oregon Treaty no longer requires owning all of Montana and Wyoming, merely having a colony in Montana, Wyoming, or California will suffice
	Paraguay can no longer become Turtle Island
	Millard Filmore will no longer spawn in the Landowners
	Adjusted "northern/southern interests" party attraction modifiers
	Updated party attraction to account for Radical Abolitionists
	Monroe Doctrine event should no longer fire multiple times for the same incident
	The Oregon Treaty no longer automatically becomes Yankee homelands upon completing the Oregon Treaty. The Westward Expansion mechanic now applies to them instead.
	Added cleanup effects to clear variables for journal entries after they are no longer relevant.
	Added extra check to try and make sure abolitionist/slaver ACW agitators retire after the war or reconciliation.
	ACW Agitators should now only spawn while A House Divided is active
	Fixed Han migrants to California not properly spawning

2.1 "Jefferson"
Radical Abolitionist should now only spawn in Yankee and Dixie countries
Loosened requirements for Deseret to ask for statehood
Manifest Destiny JE won't fail while at war
New goal-style JE explaining the Westward Expansion mechanic and prompting the player to annex the west
Abolitionists Martyrdom event no longer spawns agitators
Internal script cleanup, moving more things into scripted effects and triggers
Manifest Destiny options that grant claims now also set the AI Strategy to Expand Core Territory
New Technocratic USA flags
Fixed some dynamic name triggers
Replaced the Evangelical's Moralist ideology with a version that is okay with republics and total separation
Fixed Claim Canada button
Adjusted province setup of some american decentralized tags

2.2 "Jefferson"
Fixed modifiers on Abolitionists Martyrdom event
Fixed Whigs collapsing more than once
Utah Territory now gains a colonization boost and will annex American Utah if it exists
Adjusted Pro-Expansion and Anti-Expansion conditions to check for new  Expansionist/Anti-Expansionist character traits rather than using variables
Removed clone of Elie Augustus Frederick Lavallette
Fixed ACW countdown resetting to 0 progress erroneously
Canadian Confederation now annexes some minor decentralized tags
Incorporated additional Native American pop and culture data by Argendauss

2.3 "Jefferson"
New Content:
	Added William Walker's filibuster expeditions to Sonora and Nicaragua
	New events concerning the future of Manifest Destiny under a socialist or monarchist government
Updates:
	Second Party System now reduces Institution Change Speed
	Minor buff to Democratic Experiment
	Grover Cleveland is now Honorable and Anti-Expansionist
	Added Concept and notification for the Washington Precedent
	Certain types of presidents can now choose to break the Washington Precedent
	Secret Police can now be deployed during Reconstruction
	The Kansas Constitution can now be enforced with sufficient Law Enforcement or Home Affairs
	Added Korean translation courtesy of 케말 파샤
Fixes:
	Added failsafe that will grant US claims to mexican cession states if you acquire them through other means
	Fixed Canada forming without both versions of canadian culture as primary
	The Second/Third Party System modifier will be removed if the US stops being a Presidential Republic
	Inuit and Athabaskan tags should properly not generate native uprisings (to avoid impassable terrain weirdness)


2.4 "Jefferson"
Added event to increase Manifest Destiny if you take an overseas territory
Added flavor government for a 'Parliamentary' USA
Added event to reset to Presidential Republic as a parliamentary USA
William Walker can only attack Sonora if the USA actually borders Baja California, but requires less Manifest Destiny
The event option to support Walker costs less Infamy and always grants a Manifest Destiny point, and protectorates Sonora
Fixed Sonora not being able to ask for statehood if they are a US protectorate
Powerful IGs can now influence Manifest Destiny once every 20 years, rather than once ever
Added tooltips explaining the CSA's infinite war support and the ACW war modifiers
Manifest Destiny now maxes out at 13 for enhanced patriotism
slightly buffed Gunboat Diplomacy
Texas is now a releasable nation
Horse Creek Treaty is now a Manifest Destiny button instead of a random event
Manifest Destiny messages are now Toasts by default
sightly reduced the number of agitator slots granted by A House Divided
Secessionist Conventions event now adds 40% landowner radicals
buffed Mission Grapes state trait
localization updates

3.0 "Cleveland"
New Content:
	Gilded Age JE that activates in the 70s with powerful industrialists, along with 15 flavor events
	Progressive Era JE in the 90s, featuring 14 new flavor events
	Late-game Eugenics Movement JE that can entrench scientific racism into IG ideologies
	4 new Reconstruction events that make Radical Reconstruction more painful
	New Labor Events: Knights of Labor, AFL, Great Railroad Strike, Looking Backward
	New Characters: Terrence V. Powderly, Samuel Gompers, William Graham Sumner, Jane Addams, Swami Vivekananda
	New ideologies: Georgist, Social Darwinist, Eugenicist
	Added event marking the election of the first Afro-American president
	Added event celebrating the American Centennial
Updates:
	1.7 Compatibility
	Added "Bourbon Democrats" modifier that will attract Market Liberal industrialists to the Democratic Party after the civil war
	Cross of Gold and Scientific Management events are now part of the Progressive Era pool of events
	Added flavor government form for council republic USA
	Liberia and Indian Territory start out in their own markets
	Indian Territory starts out exempt from service and with lowered payments
	Added two new Alaskan decentralized tags
	Adjusted Seminole starting borders
	Removed military buffs from Canadian native tags (to help the HBC not get crushed)
	Added extra minor effects to a couple of previously identical event options to differentiate them
	Nerfed Go West, Young Man to +15%/30% migration attraction to match 1.7.1's nerf to Propagandists
	Added show_as_unavailable to some Manifest Destiny events to show the player that higher Manifest Destiny unlocks more options
	Updated Party System modifiers to use new Party Whip Impact modifier
	Adjusted Deep South and Homestead Acts modifiers to use new minimum worker-owned levels modifiers
	Added a decaying legitimacy buff to the US at game start to ensure Jackson's government survives
	Radical Reconstruction takes one extra point to achieve (16/20 instead of 15/20), making it easier to backslide out of it
	The Oregon Treaty now only reduces Manifest Destiny if its already high (6+)
	Mexico is now more likely to accept the Northern Purchase with pacifists or friendly Lobbies in power, and less likely with Jingoists or anti-USA lobbies in power
	Pursuing claims on mexico can now spawn an Anti-Mexico Lobby
	Divided Dixie: Upper South states can now enact Jim Crow, and states require a larger percentage of Afro-Americans to avoid it
Fixes:
	Lower Canada and New Brunswick now start with Frontier Colonization
	Canadian tags now start with a colonization boost
	American Superculture should properly fire after Peculiar Reconciliation
	The US President can't resign while A House Divided is active
	Increased spawn rate of Frederick Douglass
	Script error cleanup in a few triggers
	Vanilla Peculiar Reconciliation event can no longer trigger for the USA
	Texas can't ask for statehood while the USA is at war

3.1 "Cleveland"
Fixed missing Bourbon Democrats loc
Bourbon Democrats attraction is now based on approving Free Trade rather than specifically the Market Liberal leader ideology
Fixed NULL_STATE in railway boom/bust event
Fixed missing negative sign in Progressive Era start conditions
Fixed missing cooldown on Death's Laboratory
Progressive IGs are less inclined to join the Free Trade Party

3.2 "Cleveland"
fixed script error in government_types
Thomas Nast will now retire at the end of the Gilded Age if he's still around
Breaking the Washington Precedent now looks worse at the polls
Nerfed CSA's bonus in the ACW
Walker's filibustering in Nicaragua can now occur if the US conquers Sonora themselves
Reduced spawn rate of John Quincy Adams
Texas must now border the USA to ask for statehood
USA must now border Mexico to offer the northern purchase
Texas can now join the CSA as a dominion
If the CSA wins, their IGs embrace slavery
Harmonized Slavery Law edits with vanilla game changes
Claim Canada now properly includes Alberta
Seminole no longer have a coastline, to prevent Naval Invasions
Empire of Liberty is now neutral towards professional army and mass conscription
PB now start as part of the Pro-Britain lobby

3.3 "Cleveland"
Disabled ACW modifiers pending rework
Fixed Jesse James being erroneously called Hesse James
Pursuing the Horse Creek Treaty now costs a bit of Influence
Cracking down on Political Machines during the gilded age now costs authority and bureaucracy

3.4 "Cleveland"
Manifest Destiny now starts with an extra initial point
AI will now avoid breaking the missouri compromise
Moved some missouri compromise modifiers from the decaying modifier to the JE to make them last longer
reduced A House Divided planter opinion penalty to -15 (from -20)
adjusted A House Divided law support modifiers to use mult instead of add
The Gag Rule now directly nerfs the Slavery Banned movement
Re-added slave law LO power modifiers inline with 1.7.4
Yankee Aristocrats can now align with the Rural Folk
buffed the Albany Regency to bias a victory for Van Buren
updated various triggers to account for the American Superculture
Imminent Secession modifier is now more impactful
New event that will cancel Imminent Secession if a new president is non-abolitionist
John Quincy Adams cannot spawn later than 1840 (otherwise he's too old)
Losing the civil war immediately spawns an anti-CSA lobby and sets the LO to be Landowners
Doubled Thomas Nast's bonus to war support (and also fixed it)

3.5 "Cleveland"
Added Manifest Destiny AI Strategy that pro-expansionist presidents will adopt, making them incredibly aggressive towards their claims in North America
Claiming Cuba gives slightly less infamy
the Cuban Purchase button will not appear if you already have a claim on Cuba
The Square Deal will now remove any lingering Political Machines
Turning Deseret into the Utah Territory automatically adds them to your market
New icon for A House Divided
Lawless Gold Rush now increases Migration Quota
The California Gold Rush now spawns some Yankee laborers to ensure a cultural community forms and pulls more migrants there
Dred scott decision will now collapse the Whigs
slightly reduced the clout bonus from the Slave Power modifier
added tooltip explaining that new homelands will continue to be added after completing Westward Expansion JE
A House Divided and Compromise of 1820/1850 now impact Intelligentsia approval
The ACW now radicalizes a lot of mexicans in your states within the Mexico region

Updated Korean Localization
Reduced the Intelligentsia approval impact of A House Divided
VTM Compatibility: overwrite vtm's Huey Long in favor of HC's
VTM Compatibility: removed law_is_important trigger

3.6 "Cleveland"
Yeoman Farmers: Replaced Particularist with new Localist variant that is okay with Local Police Force and disapproves of Secret Police, State Atheism, and Appointed Bureaucrats
Compromise of 1850 no longer simultaneously pleases and angers abolitionists
Slightly nerfed the Slave Power modifier
Added Minimum Legitimacy modifier to american civil war to prevent weirdness around party reshuffle
Democratic Experiment now also reduces Radicals from low legitimacy
Texas can now ask for statehood if its a US protectorate
American School ideology is now more moderate (approve rather than strongly approve)
Sonora can now ask for statehood even without a truce with Mexico
Spain will now not even consider selling Cuba unless bankrupt
The Ostend Manifesto now costs less infamy
The Ostend Manifesto now pisses off Abolitionists
If the Whigs collapse later than 1848, and Martin Van Buren is still around, he will switch to being an Abolitionist
Fixed IG opinions on Constitutional Challenge event
Added flavor name for the Radical Party before the Progressives appear
Added special option to Constitutional Challenge when enacting Monarchy
Fixed Humanitarian PB reacting poorly to Radical Reconstruction
Trying to enact Monarchy or Council Republic now pisses off other IGs twice as much
Enlightened Royalist now counts as an Anti-Expansionist ideology
Social Darwinist now counts as a Pro-Expansion ideology
Children no longer count as pro or anti expansion
Fixed American revolts not getting proper Rural Folk traits
Characters of anti-business ideologies won't take bribes during the Gilded Age
American IGs without a party are more inclined to join a party
Progressive IGs now have a malus against joining the Fascist party
Progressives are now attracted to the Liberal party
Progressives might join the Free Trade Party if the Industrialists aren't in it
Increased the strength of the Bourbon Democrats modifier
Bourbon Democrats now dislike the Free Trade Party (ironically)
Socialist leaders no longer care about the Two Party System
Added new flavor name for Communist Party if not led by vanguardists
Treaty of G-H shouldn't trigger if you already own northern mexico
American revolts should not spawn as Monarchies
Added checks to make sure inappropiate historical characters don't spawn into IGs that have chosen communism/vanguardism/fascism etc
Added decision to dismantle Jim Crow if you later pass Multiculturalism
Made AI more inclined to make the offer to Mexico
Manifest Destiny AI should be less aggressive against their own subjects
AI will now immediately cancel enactment of a non-slavery law if Secessionist Conventions occurs

3.6.1 "Cleveland"
Grant Amnesty to Confederates now removes "Loser in Revolutionary Struggle" from all IGs rather than just the Planters
Added compatibility triggers for Merged US States patch
Updated Korean Localization

4.0 "Sitting Bull"
New Content:
	Indian Wars JE with 19 events
	Small Alt-History JE upon passing No Colonial Affairs, with 5 events
	7 new Native American characters
	7 new American generals
	Added 5 mod-specific Achievements (may or not may not function)
	Added guaranteed Frederick Douglass spawn event
	Added the ability to push for taking British Columbia as part of the Annex Oregon JE
	Added flavor government for Liberia + decision to declare a republic
	Added easter egg flag + name for a USA that incorporates a state on every continent
Updates:
	Updated decentralized nations setup, pushing the 1836 frontier further east and south
	Updated Indian Territory starting laws
	Marginalized IGs will no longer try to become Eugenicist
	Accepting the Treaty of G-H now refunds a small amount of infamy
	Ignoring the Treaty of G-H now incurs much less infamy
	Treaty of G-H should now trigger more consistently before the war capitulates out
	Treaty of G-H can now fire without occupying Mexico City, but the options to take additional land beyond the northern cession will not be available
	Completing Radical Reconstruction will upgrade Frederick Douglass into a Humanitarian
	Reconstruction now incurs some additional military costs
	The US now suffers a decaying military debuff after the civil war
	Increased the Supply usage impact of the Native Resistance and Comanche Domain state traits
	Most options to enforce Reconstruction now require you to have 20 regiments stationed in Dixie
	Unreconstructed states now have all their Barracks and Conscription Centers removed at the start of Reconstruction
	Added additional ways to trigger the Progressive Era JE if you happen to bypass the Gilded Age
	Disabled the Womens Suffrage JE for the USA (redundant with the Progressive Era JE)
	Added an extra military buff to the Nez Perce
	Updated the conditions and description for the Oregon Border Treaty to increase clarity
	Turtle Island JE now requires Pan-Nationalism and a citizenship law other than ethnostate or national supremacy
	American Superculture now requires 13 Manifest Destiny points (up from 12)
	Extended the Comanche Domain into New Mexico
	Comanche Domain now also reduces agricultural tax income
	Added traits to Nelson Appleton Miles
	The USA now starts with Freedom of Conscience, and its IGs prefer it over Total Separation (the constitution claims total separation, but in reality Protestantism was paramount)
	Republican Virtue no longer provides throughput, but also extends Education Access to Farmers
	Enforcing Indian Removal now requires an army stationed in Dixie
	John C Fremont will now only spawn for the Armed Forces
	Alexander Stephens will no longer spawn for the Rural Folk
	USA starts the game bankrolling Indian Territory
	Liberia now begins with a pro-USA lobby
	Gilded Age JE won't trigger if the Progressives already have spawned
	Securing the Oregon Trail now applies a temporary colonization/migration malus to the middle sections of the trail
1.8 Compatibility Updates:
	Removed ACW state scripting (handled by Political Movements now)
	Disabled random election-spawned agitators (except when passing Slavery Banned)
	Updated Wildfire and Great Chicago Fire events to use new Harvest Condition system
	Removed Citizenship stance from Evangelical Moralist ideology
	World Parliament of Religions event now uses Pivot of Empire's version of Swami Vivekananda (and thus requires the DLC)
	Swami Vivekananda is now a Universalist (new ideology) agitator
	Updated modifiers across the board to new 1.8 modifiers
	Accepting Deseret Statehood renames Utah to Deseret
	Updated events and triggers to interface with new Political Movements
	Progressive Cause JE now comes with a unique Progressive political movement
	Added JE that further decreases Acceptance and Voting Power of afro-americans (removed by passing Cultural Exclusion or Multiculturalism)
	Long Reconstruction now takes a variable amount of time based on Acceptance of Afro Americans and a few other factors 
	Eugenics JE replaced with a Eugenics Political Movement
	Westward Expansion homelands will now spawn cultural communities in order to facilitate assimilation
Fixes:
	Fixed LDS modifier not being applied to Utah if you also had a colony there
	Reconstruction no longer requires Multiculturalism

4.1 "Sitting Bull"
Elitist Ideology now prefers Agrarianism
Increased the activism debuff of the Missouri Compromise
fixed missing Mexican claim on Chihuahua
added un-attainable Corwin Amendment option to the Secessionist Conventions event

4.2 "Sitting Bull"
Fixed broken tooltip on New Zion event
Fixed duplicate event option on Settlers Clamor for Removal
Updated Korean localization (thanks to 케말 파샤)
Frederick Douglass event now requires VotP DLC
Fixed broken character trait on Nelson A Miles
Fixed Nationalist Clubs modifier
Monopoly in State event can no longer target subsistence buildings
Delayed the appearance of Theodore Roosevelt until 1896

4.3 "Sitting Bull"
NOTICE: Hail, Columbia! now requires the Community Mod Framework
Removed Party definitions and Pro/Anti-Slavery movement overrides in favor of CMF
Updated Turtle Island JE with vanilla changes
Fixed some missing ECCHI dna
Merged in vanilla change to Pro-Slavery Movement demand for military in slave states
Aggressive options in Treaty of G-H add additional mexican radicals
Dialed back the CSA's extra war support and disabled it when the USA is AI-controlled
Promote/Suppress Continentalism buttons no longer appear once Westward Expansion is complete
West Virginia is now known as Western Virginia until it breaks away as its own state
American Indian culture is now Anglophone
Updated DXG to be called Deg Xit'an
Fixed William Cramp & Sons HQ location
Moved Texas subject options over to Puppet rather than Dominion
Added dynamic name for Alaska when subject to the USA
Added new IG traits for native american tags
Backend support for Tecumseh's Legacy

4.4 "Sitting Bull"
Updates
	Purchasing Alaska now annexes the entire state region
	Forming Canada now annexes the northern state regions
	If you gain Alaska or Canada by other means, you can annex the northern states by decision
	Melting Pot modifier now allows for Full Acceptance assimilation (technically, but pops won't actually assimilate still)
	If the Border Ruffians take Kansas due to the outbreak of the civil war, Missouri will go with them
	A Radical Abolitionist president or government can now gain a 1-time boost to war support in the ACW
	Reconstruction backlash events can now trigger at slightly lower levels of Reconstruction
	Great Plains nations now suffer from a long lasting mortality modifier
	Added Algonquin and Atikamekw tags to Quebec
	All native tags now have defined flags
	Added +100% Colonization speed modifier to Michigan
	Peacefully purchasing Cuba or the Mexican Cession now creates a 10 year Truce
	Several Pro-Indian event options now reduce Manifest Destiny
	Added extra tooltips to telegraph the completion effects of JEs
	Added historical Concepts explaining various aspects of american history
	Overhauled the pro-expansion and anti-expasion tooltips on the Manifest Destiny JE
	Multiculturalism now decreases MD, while National Supremacy or Ethnostate will increase it
	Added temporary Acceptance modifiers to California events
	Hurricane event now adds a Flood harvest condition
	Doubled AI define NUM_GROWING_COLONIES_SCALED from 0.01 to 0.02
	Adjusted Oregon Trail state modifiers
	Emancipation Legislation AI agenda should now try and maximize conscripts
	Added limited "total war" functionality to the ACW: certain Border States (Kansas, Missouri, Kentucky, West Virginia) will immediately flip sides when occupied
	CSA gets claims on all US Dixie states upon winning the civil war
	Added German translation courtesy of KushGene
Fixes
	Purchasing Alaska JE no longer appears if you already have a subject in Alaska
	Refactored internal history setup for decentralized tags, some borders and populations have shifted
	Fixed starting Bankroll of Indian Territory breaking
	All states that should start as colonies now properly do so, enabling the AI to colonize more organically
	Manifest Destiny AI Strategy should maximize Colonial Affairs institution
	Editing pass on all localization
	Internal script cleanup
	Fixed Sonora asking for statehood when liberated manually
	Fixed starving inuit pops
	Fixed all instances of incorrect strata targets
	Fixed broken tooltip on Treaty of G-H
	USA now gains some provinces in Nebraska at the start of the ACW to ensure land access

Updated German translation courtesy of KushGene
Updated Korean translation courtesy of 케말 파샤
Added placeholder English text for all other languages

4.5 "Sitting Bull"
USA now starts with an Anti-Haiti lobby
Fixed wrong tooltip for Spain-facing Cuban Purchase event
Fixed broken state loc in Indian Removal event
Fixed End Gag Rule button requiring a slaver president
Added failsafe in case the CSA somehow takes DC as part of the secession

4.6 "Sitting Bull"
New Content
	New Events: Chestnut Blight, Rain Doesn't Follow the Plow, Prairie Madness, Comanche Slave Raid, Northern Removal, Osage Oil Boom, Osage Reign of Terror
	Added decision to negotiate the mexican border to the Rio Grande with a friendly or subject Mexico
	US Constitution JE: contains permanent modifiers, explains Unconstitutional Laws mechanic, explains Natural-Born Citizen mechanic
	New AI Strategies for the USA: Monroe Doctrine and Big Stick Diplomacy
	Law Variants for the USA: American System (Protectionism) and Nominal Separation (Freedom of Conscience)
	New Companies: Coca-Cola and Westinghouse
Updates
	Party Leaders who aren't natural-born citizens will be ejected from IG Leadership at the start of an election
	Cultural Majority/Minority Movements now increase/decrease Manifest Destiny at 30%/60% support
	Annexing all of Mexico displeases IGs who would rather not share a country with Mexicans
	Updated Bleeding Kansas JE to use a double-sided scripted progress bar
	Closing the Frontier now cleans up the Native Resistance/Comanche Domain state traits
	Eugenicists now disapprove of Welfare
	New dynamic name for a USA that incorporates south american states
	AI USA is more reluctant to form a power bloc until later in the game
	Removed mod achievements (non-functional)
	PT Barnum is now a PB Abolitionist
	Newly-created characters will now adopt the American Superculture
	CSA now spawns with more appropriate laws
	Congress of Trusts now gives Free Company Charters rather than Max Companies
	Moved the Manifest Destiny modifier into the JE itself
1.9 Compatibility
	Moved several Industrialist characters into being Executives
	Harmonized with vanilla content changes	
	Reworked Gilded Age event "Local Monopoly" into a "Company Towns" event
	Consolidated some Arctic and PNW tags for performance reasons (it appears that having more than 420 tags on the map causes problems now)
	Updated harbor state traits
Fixes
	Fixed some localization errors
	Fixed incorrect country tag in Canada je
	AI should never enact the Corwin Amendment
	Corwin Amendment is invalidated by Marginalized planters
	Fixed War Policy option tooltip
	Fixed up some native starting laws
	Fixed script error from character interaction
	William Walker won't invade a Mexico that is subject to the USA
	North Star event can occur even if Douglass spawns early

4.7 "Sitting Bull"
Electing an Abolitionist or trying to enact Slavery Banned will remove the modifier from the Missouri Compromise JE
Added Liquor, Tea, and Coffee taboos to Mormon religion
Yankees and Dixies now always count as natural-born citizens
Afro-Americans under CE now count as natural-born citizens even if their homelands are unincorporated (ie, after the civil war)
(Tecumseh's Legacy) updated conscription effect on Bones of Our Fathers IG Trait
(Hopefully) fixed some cases where the CSA would somehow survive losing the civil war

5.0 "Rockefeller"
New Content
	New Companies: DuPont de Nemours, American Sugar Refining Company, Anaconda Mining Company, American Tobacco Company, American Woolen Company, Armour and Company, Colorado Fuel & Iron, Sears, Roebuck and Co., Singer Manufacturing Company, Union Pacific Railroad, United States Rubber Company, Warner Bros Pictures
	New Prestige Goods: Coca-Cola, Durham Tobacco, Hollywood Movies
	8 new historical Executive characters
Updates
	Manifest Destiny now starts 1 point lower
	Movements now influence MD at 20/50 support instead of 30/60
	Progressive Era is now slightly easier to trigger
	Executives can now spawn up to 10 years earlier than OTL and for the generic versions of their companies
	AI USA should prioritize Colonial Affairs
	Added 1 year cooldown to the Homestead Acts button
	Radical Abolitionists now join the Afro-American National Movement even if they're white
	Added temporary Acceptance modifiers to various Reconstruction events
	Moved Party System modifiers into the Constitution JE
	Rebalanced some House Divided modifiers
	Congress of Trusts now adds +1 company maximum again
	Trust Busting now adds -1 company maximum
	Updated Korean localization (thanks to 케말 파샤)
Fixes
	Updated pro and anti-expansion tooltips
	Failsafe mexican claims only apply when someone else holds a state there
	Fixed some errors related to adding homelands to states
	Script error cleanup
	Positivist Movement should no longer spawn in the USA
	Made sure that breaking the missouri compromise / compromise of 1850 reliably removes all related modifiers
	Texas shouldn't call for aid after being admitted to the union
	Fixed country tag clash with ANZFP
	Fixed game-start front in Texas

5.1 "Rockefeller"
USA: Intelligentsia shouldn't join the Conservative party
USA: PB are more inclined to the Liberal party
USA: Liberal Party can exist without the Intelligentsia
Fixed starting character templates
Rain Doesn't Follow the Plow won't trigger after Westward Expansion is already complete

5.2 "Rockefeller"
Added some extra Power Bloc names for the USA
American Superculture is harder to get: requires <30% canadian/dixie radicals, >15% yankee/dixie/canadian loyalists, american frontier must be closed
Lincoln now becomes a Radical Abolitionist when Reconstruction starts, or if he spawns during it
Utopian is now considered an abolitionist ideology
Added Horace Greeley as a Utopian agitator
Teddy Roosevelt can now only spawn as PB

5.3 "Rockefeller"
Enacting Laissez Faire lowers the Industrialist Clout needed to start the Gilded Age
Lowered number of Railroads required to start the Gilded Age and for the Railroad Tycoons event
The Square Deal must now be in place for 5 years to finish the Progressive Cause JE
Bumped up the SoL requirement for the Square Deal by 1
Disabled "total war" effect in ACW due to changes in how War Goals are contested
Eugenics movement can now always spawn Social Darwinists
Updated political movements to use new suppression/bolstering values
Afro-American President event now bolsters racist Movements and accounts for the American Superculture
Ironclad Concept no longer spawns an Ironclad (unfortunately it was buggy)
Imminent Secession modifier is now properly imminent, and gets removed when the ACW begins

5.4 "Rockefeller"
Homestead Acts now cause a few Peasant settlers to immediately move to the target states
California Genocide now increases colonization speed
Lawless Gold Rushes now increase colonization speed slightly more
Updated conditions for End Gag Rule button to be more lenient
Dred Scott modifier now lasts twice as long
The Gilded Age can now start during Reconstruction, but now requires 3 tech/timing conditions instead of 2
Gilded Age can now spawn in a slaver USA if the relevant movements are low-activism
Constitution JE now also explains the Washington Precedent
AI USA should immediately adopt a relevant AI Strategy when electing a new president
AI USA will adopt Emancipation Legislation if the Planters are marginalized
AI shouldn't press the Break Treaties button and erroneously slow down their own colonization
Added Pacific States of America formable tag for an independent California
(CMF) Human Rights technology now doubles pop attraction to the Abolitionist movement and increases its activism
(CMF) Any Powerful IG having an Abolitionist leader now gives +30% activism to the Pro-Slavery movement
(CMF) Radical Abolitionists only join the Afro-American movement after slavery is abolished
(CMF) Abolitionists no longer erroneously avoid the Agrarian Party once slavery is banned

5.5 "Rockefeller"
Moved MD Point from pursuing Cuba to the event options that actually give you a claim on the island
The Cuban Purchase can only be offered by an expansionist government
Updated Third/Forth Party System Modifiers
Subject Mexico is now compelled to accept the Mexican Purchase
Added new FSA flag
John Brown can now launch his Harpers Ferry raid even if Bleeding Kansas has concluded
Increased the spawn weights of important historical Bleeding Kansas events
Gilded Age no longer requires low-activism movements, instead merely requires no ongoing revolution
Fixed the Border Ruffians not properly making Kansas a Slave State if they win
Fixed Mormons spawning as unemployed pops
Merged 1.9.8 changes to Greener Grass Campaign
Vanilla bugfix: intro event sets the initial USA election date properly

# 6.0 "Douglass"
## New Content
	18 new Post-Reconstruction events including the Great Migration, Red Summer, the Harlem Renaissance, and special alt-history events in the wake of a Radical Reconstruction
	New Underground Railroad JE that moves small numbers of slaves out of the South every month
	New African Colonization JE with 6 events containing some efforts to resettle Afro-Americans to Africa and Central America
	3 new USA election events responding to various types of candidates
	3 new internal CSA events during the ACW
	Other New Events: Colored Troops, Scalawags, Disunionism, Wide Awake, Cross-Atlantic Endorsements, Mexican Discrimination, Boll Weevil Infestation, Abolitionists Against the War
	New Characters: Booker T Washington, Marcus Garvey, A Philip Randolph, Hubert Harrison, Anthony D Williams, James Weldon Johnson, James Weldon Johnson, Ida B Wells
	A Radical Abolitionist government can now unlock a special decree to seize and redistribute former slave plantations, permanently breaking the plantation economy of the South
	Added Endemic Hookworm to the Deep South, removed with Malaria Prevention tech
## Updates
### A House Divided Updates
	The Southern Planters are now even more racist
	Missouri Compromise now suppresses the abolitionist movement more
	Doubled the activism impact of Imminent Secession
	Upper South and Deep South modifiers now increase cost and radicals from nationalizing buildings
	USA now starts with an Afro American national movement with a unique ideology
	Added Status messages to A House Divided giving updates on the current status of the debate
	Removed CSA's war support on battle defeats (replaced by Brother Against Brother event)
	CSA now spawns with Legacy Slavery instead of Slave Trade
	The Missouri Compromise now only suppresses the activism of the Abolitionist and Pro-Slavery movements, rather than all movements
	Annexing Texas now upsets Abolitionists
### Reconstruction Updates	
	Updated Reconstruction Progress Bar into a double-sided scripted bar
	New Northern Political Will bar for Reconstruction that decays over time
	Added Northern Reticence modifier to Reconstruction that increases the more you progress in favor of the Freedmen
	Mixed Reconstruction now only requires 40% Afro-americans to avoid Jim Crow rather than 60%
	Long Reconstruction is now available to all outcomes (and peacefully banning slavery) but has huge penalties unless Radical Reconstruction was completed
	Long Reconstruction now takes slightly more progress to complete
	Abraham Lincoln now becomes a Reformer upon completing the civil war
	Jim Crow now reduces migration attraction
	Reworked Devil's Bargain event to be more historical
### Liberia Overhaul
	Liberia now has a properly american set of IG ideologies and starting laws
	Decolonized the Liberian interior at game start
	Liberian population reduced to much more historical numbers (less than 5k Afro-Americans)
	Removed Afro-American homeland from Liberia (causing high Afro-american mortality as was historical)
	Liberia no longer starts in their own market
### 1.10 Compatibility
	Removed mod changed to White House (vanilla now adds migration)
	Removed mod-added Rio Grande state trait in favor of vanilla one
	Removed Black Suffrage JE (redundant with vanilla acceptance changes)
	Warner Bros is now an Academic-Owned Company
	Replaced Great Triumvirate modifier with a special character trait
	Added African Consolidation game-rule that merges a bunch of central african countries in order to reduce the starting tag count below 420
	Merged in various vanilla changes to events and JEs
	Added law opinions to the new laws where relevant
### Other Updates
	Secure the Oregon Trail button is now visible from the start to indicate to the player that it's a goal to progress towards. It also now only requires the Logistics tech rather than year 1850+.
	Added tooltip explaining the relationship between Manifest Destiny and the Treaty of G-H
	DuPont can now produce High-grade Explosives
	The Columbia River now adds +30% logging throughput
	Manifest Destiny now begins to decay over time starting in 1900
	Indigenous American cultural minority movements now have a unique ideology
	Oklahoma now enacts Jim Crow upon becoming a state under the white constitution
	Updated some Progressive Era event modifiers
	William Sumner now only spawns automatically if you embrace Social Darwinism
	Ulysses Grant is now Expert Offensive Planner, Persistent, Honorable, Innovative
	Robert E Lee is now Defensive Strategist, Celebrity Commander, Direct
	Increased infamy costs for annexing/puppeting Mexico
	Removed extra Infrastructure from Rio Bravo trait
	(CMF) Reactionary Movement can't spawn in american countries
	(CMF) Doubled baseline PB attraction to the Liberal party
	(CMF) African-heritage characters can always join the Afro-American National Movement
## Fixes
	Hopefully prevented non-USA countries from picking the USA-specific AI strategies, again
	Added extra check to make sure John Brown doesn't launch Harpers Ferry immediately  after spawning
	Fixed Jim Crow not applying to enough states in Failed Reconstruction
	Manifest Destiny JE will now remove "ghost" claims on fully controlled states so that the Fascist movement doesn't gain an erroneous revanchist boost for already-conquered territory
	Constitution JE fails if you pass a non-voting Distribution of Power law
	Fixed California yankee homeland not being correctly applied
	Fixed some loc errors

# 6.1 "Douglass"
Mexico no longer counts as "tropical" for the purposes of afro-american colonization
Brother Against Brother event now increases both cultures' fervor
Afro-American settlers can now only be sent to states with >0 free arable land
Comanche can now centralize without needing AI Mexico to pass No Colonial Affairs
Added special character trait for Frederick Douglass
Increased the frequency of Long Reconstruction events
Added effects at various points to ensure Mexican/Afro-American movements are created if they don't already exist
You can no longer grant IG leadership to an agitator during an election

some Tecumseh's Legacy support updates
Added variant Bureaucracy and Land Reform laws for native tags

Deseret can spawn if you place a colony in Utah
CSA should no longer colonize new provinces during the civil war

# 6.2 "Douglass"
Added a "Confederate Rebellion" event in case the FSA wins and annexes the USA
Increased attraction of Dixie pops to the pro-slavery movement, especially Aristocrats, Farmers, Soldiers, and Officers
Adjusted attraction modifiers to the abolitionist and pro-slavery movements
Added addition starting Trade Centers to the south exporting Fabric
Abolitionist Movements now add their Support directly to their Activism above 33% Support
The Slave Power now crushes Afro-American Fervor
Breaking Indian Treaties now adds some loyalists
Annexation more of Mexico now angers Abolitionists
Cleaned up annexation tooltips in the Treaty of G-H
AI USA stops taking pro-freedmen options when Northern Political Will has exhausted
Cheyenne-Arapaho is now Algonquian
Updated logo of Union Pacific Railroad
Added some custom tooltips and descriptions to fix tooltips for unavailable event options
Updated Manifest Destiny triggers to show the required values
Updated various scripted buttons to show when selected
Brute force on_action to force any non-USA countries to stop having the Monroe Doctrine strategy that they're not allowed to have
Increased neutrality of the Monroe Doctrine
Increased weight of Monroe Doctrine to support american countries
Monroe Doctrine now properly considers central america to be part of its sphere
Fugitive Slave Act now makes the Abolitionist Movement more angry
Bleeding Kansas now increases pro/anti-slavery attraction in the state
Added a decision to restore the Constitution if you lose the JE
Nerfed starting Democratic Party momentum
Nerfed Slave Power modifier
AI USA presidents now more proactively select new ai strategies upon election
Second Party System now lowers enactment speed and movement suppression
The Gilded Age can now be ended early by an appropriate ideology president
Fixed Dixie Culture not actually attracting to the Neoconfederate movement

# 6.3 "Douglass"
Added JE to Mexico that allows them to add Mexican Homelands to the american west if they manage to hold on to them
Added JE to the canadian holder of Oregon warning them about the Oregon Border Dispute
Civil War Legitimacy buff now persists for 4 years after the war (decaying)
The start of Reconstruction prompts a refresh of IG/Party support
Getting Slavery Banned to the final enactment phase now triggers Secessionist Conventions unless the pro-slavery movement is sufficiently weak
Crushed the ability of Slaves in the South to join the Abolitionist movement
Free afro-americans are now more attracted to the abolitionist movement
Once the Missouri Compromise is broken, Pro and Anti Slavery movements gain a radicalism modifier that scales with the imbalance of free vs slave incorporated states
Rebalanced missouri compromise modifiers again
Election momentum chaos now has a bias against incumbent parties, and especially parties with >150% momentum
Election momentum chaos no longer will decrease parties below -50% or above 150% momentum
Added game rule to toggle election chaos
Western Purchase button is now disabled if Mexico manages to fully colonize and incorporate 2 or more of the relevant states
Mexican Cession states now recieve a short migration buff
Expansionist and Antiexpansionist traits now impact infamy generation and decay
Jacksonian Democrat can no longer spawn in the PB, but can spawn in the Armed Forces and Southern Planters
Updated some labor union events to account for the new laws

# 7.0 "Jackson"
## New Content
	Added custom Democratic and Republican parties replacing the conservative/liberal parties in the USA
	Added Jacksonian Agenda JE at game start giving context to the starting situation of laws and taxes
	Added the Panic of 1837 plus a JE to recover from it
	New JE and Events for the American press to react to atrocities in Cuba and possibly spark a Spanish-American War
	Added JE for American attempts to purchase Greenland and other islands from Denmark
	New events for the Dorr Rebellion, Third Great Awakening, Caroline Affair, Fenian Raids, Aroostook War, Lopez Expedition, Oregon Black Exclusion
	Added starting Trade Privileges treaties for the USA with various countries
	New Characters: Emma Goldman (imported from ECCHI), Billy Sunday, Walter Rauschenbusch, Lyman Beecher, Henry Ward Beecher, Peter Cartwright, Bejamin Tillman, David Atchison, Gerrit Smith, Reinhold Niebuhr
	Added Constitutionalist Movement that spawns in response to unconstitutional law enactment
	Added Spoils System and Bill of Rights starting amendments
	Added Anti-Lynching Law amendment
## 1.12 Compatibility
	Reverted Liberia map setup to the new vanilla one
	Moved the vanilla Fugitive Slave Act amendment to the relevant HC event
	The Gag Rule is now a Law Amendment
	Replaced the following modifiers with Law Amendments: Pure Drugs, Separate But Equal, Fugitive Slave Act
	Updated several vanilla overrides to use the new INJECT syntax for compatibility
	Disabled Durham Tobacco prestige good (3 prestige good limit)
	Confiscate Slaveholder Lands now adds an amendment which unlocks the decree
	Added custom geographic regions to some triggers for better tooltips
## 1836 Starting Situation Update
	USA now begins with Agrarianism and a special variant of Consumption-Based Taxation (cutting the national revenue about in half!)
	American PB now supports the American School (interventionism and protectionism)
	William H Harrison is now the starting leader of the PB
	Daniel Webster is now a starting PB Agitator
	Significantly reduced the number of starting Government Admins to balance the budget
	USA now starts on low gov/mil wages
	USA now starts with Consumption taxes on Furniture/Luxury Furniture, representing property taxes
	Added more Trade Centers exporting Cotton and Tobacco
## Updates
	Removed the SoL change from the planter's Our Peculiar Institution trait
	William H Harrison is now Sickly
	William H Seward can no longer spawn for the Rural Folk
	Increased momentum penalties for running a non-white, non-protestant, or woman candidate
	General Pershing is now Offensive Planner, Traditionalist Commander, Direct
	Having an Afro-american ruler or IG leader in government now gives a boost to Long Reconstruction
	Indian Removal payments are smaller
	Made the Deranged Office Seeker shoot the president slightly less frequently
	Monroe Doctrine Violation can now trigger from a european power siding with someone else in a diplo play in the western hemisphere
	The Alaskan Purchase no longer auto-annexes the whole state region (Civilizing Mission unlocks a decision to do so)
	Inuit/Athabaskan centralized countries now bypass the tech requirement to survey the arctic
	Decolonized Greenland (can be surveyed by decision with Zepplins/Planes)
	Added Greenland Ice Sheet state trait
	Reverted American Chestnuts state trait to vanilla
	Updated 6.3 Korean localization thanks to 시아츠
## Fixes
	Significantly increased the navy requirement to enforce the Monroe Doctrine so that now you actually have to grow the navy from its starting state
	Moving away from Presidential Republic now removes the Constitution JE even if you still have voting
	AI USA will never pay money for indian removal
	Fixed bug where Jane Addams could spawn infinite times
	The American and Seminole armies in Florida now start mobilized and at the front

# 7.1 "Jackson"
Fixed Aroostook War firing more than once
Fixed Hard Times never ending
Reduced Expedition Budgets by 20%
Increased Party Whip Impact of Federal Government modifier
Added Ideological Incoherence reduction to Second Party System
Increased impact of Gold sources on Hard Times recovery
Added Apolitical Military modifier to the Constitution that massively increases Coup Resistance
Reduced the infamy cost for claiming Cuba back down to 10 from 15

Reduced Seminole's defense modifier to 100% from 200%
Added ACW failsafe in case the CSA isn't properly fully annexed by the war

# 7.2 "Jackson"
Updated amendment triggers and definitions to 1.12.2
Fixed bug where Radical Land Distribution could lack a sponsor
Increased the loyalists generated by escalating border conflicts with Britain
Fixed some loc related to Cuba
Updated some triggers relating to "country_or_subject_owns_entire_state_region" for cleaner tooltips
Various Gilded Age events now erode Electoral Confidence, while Progressive Era events increase it
Completing the Progressive Era significantly increases Electoral Confidence
The crazed gunman cannot spawn during Reconstruction
The crazed gunman can only spawn while the Spoils System is in place
The crazed gunman assassination now immediately completes all progress towards abolishing the Spoils System

# 7.3 "Jackson"
Fixed missing Canada Confederation buttons
Updated Spoils System tooltip
Greenland and Iceland no longer trigger the American Empire event
Fixed 40 Acres and a Mule still spawning even after getting the amendment
Bill of Rights is no longer removed if you pass Protected Speech proper
Increased weight of radical abolitionists to the afro-american movement
40 Acres and a Mule amendment should be removed by Reconstruction concluding
Reduced acceptance gain from Nominal Separation
Increased acceptance penalty from Separate But Equal
Removed Authority and Devout Strength from Nominal Separation
The Evangelicals are now naturally attracted to the Republican Party
Reformers are now attracted to the Republican Party
Ethno-Nationalists are much more strongly attracted to the Democratic Party
The Trade Unions are twice as repelled from a party dominated by the Industrialists
Jingoists are no longer attracted to the Democratic Party
Updated weights for the RF and TUs towards the People's Party
Removed leftover weights for free trade/liberal/conservative parties
Abolition stops being a deciding factor for parties after Reconstruction is over
Fixed Cuban Outrages JE spawning for non-usa countries
The Cuban Outrages timeout gains additional time while at war with Spain

Subjects no longer count as monroe doctrine interlopers
Fixed null state case in Great Return event

Swami Vivekenanda properly spawns as an agitator instead of IG Leader
Added cooldowns to some amendments
Fixed constitutional revolution spawning as a chiefdom
Land Tax is no longer in the unconstitional law tooltip

# 7.4 "Jackson"
Increased starting Paper Mills in DC to 3 levels (from 1)
The Alaska Purchase is now a lump-sum payment of 1.4M pounds (inflation-adjusted)
Reduced the Hard Times Loan Interest Rate from +50% to +40%
Reducing landowner clout below 5% now prevents the Secessionist Conventions event
Fixed Caroline Affair spawning multiple times
Reduced all infamy sources by 20% to account for Great Power increase
Increased mexican radicals generated by the civil war from 20% to 50%
Fixed a few typos
Updated korean loc

# 7.5 "Jackson"
Added fallback MD button to directly claim mexican lands with high MD, bypassing the financial requirements of the Offer decision
Fixed missing tooltip on Hard Times event
Fixed Canadian countries missing Colonial Administration government principle
Fixed Monroe Doctrine violation being triggered by the USA calling in a European ally against a target
Added checks to hopefully prevent erroneous spawning of Cuba content