# For-Later-Project-Ideas
All the various ideas for coding projects I've had; Sequestering them here prevents me from opening yet another Repo &amp; Diluting my coding powers even further!

# A "Package-Manager"-like program for .MDs.
.MDs instructing the AI what to do and how to do it are a common aspect of Coding nowadays.
They guide the AI, helping any proposed changes remain grounded. 
Writing these .MDs is inconvient, though. I have to Prompt the AI multiple times, cross-check annoyances across multiple prompts, and then write the MD Myself.
Would it not be easier to have a central repository of Best Practices .Mds, and then Pull them as needed?
Ideally, this could cross-check with my package manager. This could see what libraries I'm using, which can then suggests .MDs tailored for using that library.
Before Working on This Project: I believe Gleb Bahmutov ( https://github.com/bahmutov ) either has worked on something simular or has worked on something simular. 

# Minecraft Mod: Grillager
Add a new Type of Illiger-type Mob to Minecraft: The Grillager. This mob shall: 
A. Have a funny name.
B. Be based in the nether, and
C. Attack the player with Red-hot iron Bars. These Iron bars shall be a problem for the player: In addition to being the main damage-dealer for this mob, the Grillager can also block most damage by using levitated iron bars as a sheild.
I envision the Grillager Shot-gun-blasting the player. Shot-gun blasts with multiple projectiles doesn't do much in minecraft, owing to post-damage immunity.

# Minecraft Mod: Zombie Illagers
Is it not odd that Villagers can be zombified, but not Illagers?
This Mod would add a handful of Zombie Illagers.
These can be cured. Curing a Zombie Illager either nets their Illager Counterpart (Big improvment) or a "Redeemed Illager".
These are illagers who opt to abandon their former ways and return to respectible society. They can fight mobs (with a special emphasis on zombies), and can be traded with!
Redeemed Illagers are unreliable, though; they might switch sides yet again upon raids and/or spotting fellow illagers.
This chance can be reduced by leveling up trade, village population growth, proximity to an iron golem, killing other zombie illagers, or remaining redeemed during a raid.
Different types of illagers have different chances to choose the path of rightiousness. Vindicators & Pillagers (the grunts) are easier to convert than Evokers & Illusioners (the elite).

Zombie villagers remember enough to attack Non-Zombie Illagers. Regular zombies ignore illagers to avoid too much Mob-on-mob violence.
Witches can also cure Zombie Illagers. Zombie illagers cured by witches are always hostile when cured.

# Yet another Game Mod: Henry Stickmin Collection Bio Journal is downright terrible.
I was playing the Henry Stickman collection as a breather from my previous activity: Complaining about UI. 
Unfortunantly, this turned out to not be a break at all. The Bio section is a UX experience so bad that, if I saw it on a website, I would condemn that website with great pussiance.

Policeman-turned-military Rupert Prince is one of the the most prolific characters in the Henry Stickmin collection, appearing in 4 games.

I want to see how his profile changes over time: finding him in EtP, StD, and ItA is easy enough. Then we come to CtM:
<img width="358" height="454" alt="image" src="https://github.com/user-attachments/assets/d8216a3c-904b-41a7-9c34-7554b01b7432" />

Oh, dear. That's 11 pages to flip through. Ain't nobody got time for that!

Here are my UX suggestions:
Filtering. Filter by Faction, Filter by # of games appeared in, filter by Difficulty stars. 
Also filter by "When I last saw this character"; If I want the bio of someone I saw on-screen only 2 seconds ago, I demand his/her bio with a minimum of fuss!

Sorting! Sort by name, as well as faction, # of games, and difficulty stars.

When switching games within the Bio section, switch to the same person, if possible.

I don't know what the Henry Stickmin collection is programmed in, nor do I know how to mod it. But if this was React, the suggestions made shouldn't take too long.

Oh, and one more thing: After 100%-ing the game, there's a small multiverse/Marvel-style after-end-credits scene.
I, a normal, tried to right-click on any person I saw. Nothing happened. No Easter-Egg bios! Ridiculous.


# Station-Neutral Amtrak Schedual Search.
From Washington D.C, I want to take a trip to Richmond, Virginia. 
Quite fortunently, Amtrak has a Trip-planner for things like these: https://www.amtrak.com/home.html 
Unfortunantly, Amtrak Assumes too great a specificity. There are two different Richmond stations, meaning I have to query twice.
This gets worse. I am visiting family on a weekend trip. I am ambivalent between arriving at Richmond between Late Friday and early Saturday. 
There is no way to select a date range, meaning I have to query twice again for this time discrepancy.

At least I'm not going from Richmond to Boston. Boston has 3 train stations. I would have to make 2(# of Richmond train stations) * 3 (# of Boston Train stations) * 2(departure ambivilance) *2 (return trip departure ambivilance) = 24 seperate queries! 

If I make this Amtrak API-accessing app, It should support connections. If I want to go from Sandpoint, Idaho to Memphis, Tennessee via train, that should be doable!
Multiple cities would also be nice. If I want to go on a grand trip, touring the cities of Mobile, Alabama; Dodge City, Kansas; Lincoln, Nebraska; and Detroit Michigan, that requires multiple stops!
Integration with a City's subway system would be a cherry on top. It might be a requirement, too, for taking into account connections in cities with multiple train stations.  

# Yet another Video Game Mod, this time adding Explosions to Mudrunner. Explosions and better winches.
The game Mudrunner has the Fuel Truck. I Parked a fuel truck in the middle on the road and switched to a different truck. I then rammed the Fuel truck at top speed, as one does.
The ramming truck was smashed up, and required repairs to start moving again. The rammed fuel truck, on the other hand, walked this crash off.
Come on! This is a fuel truck! I wanted a Kaboom!
Hence Mudrunner's addition to the "For-Later-Project-Ideas-The-List-That-Is-Rapidly-Turning-Into-A-Potential-Video-Game-Mod-List" List. Explosions! If you're careless enough, you might end up with too few trucks or fuel stations to complete the level. On the plus side, you get to see the Driver ragdoll-ing.

The winch controls could be improved, too. To get to the winch, I have to open up advanced Mode. Advanced mode disables my engine. If I'm stuck and want to use a combination of winch+engine to get myself free, that requires an extra key-press over allowing me to start driving immediatly.

# C-Plus-Plus Database Setup 
Not every project is public. On one of my not-public projects, I needed to store data in a database. This was in C++.
I had a seperate executable for Database Setup. 

This Database Setup was _Heavily_ Django-inspired. The Database Setup executable itself served as a conductor for running various migrations needed to ensure the database is up and running and ready to interact with the rest of the code.

The entire idea behind this list of "For Later project Ideas" was that I have too many projects already. With so many already-existing Projects, the inevitable happened.
I have a second project written in C++ that will use the libpqxx library for interacting with the database. 

Let me review my options: I can type manually something that would be simular-to-but-not-quite what I have already. This will give my carpal tunnel syndrome.
Option 2 is to copy-paste my Database setup from my ooh-so-secret project into my less-secret-but-Ill-eventually-make-it-public project. This is a trawdy move. 
This leaves only option #3: Create another project, this time for setting up the database for any C++ projects that use libpqxx! 

# Chrome Extension: Writing Github Readmes. I want a linebreak, stupido!

I recognise This Github Readme looks unorganized. It looks like I have no idea what a linebreak is nor how to use one.
I do use linebreaks! I use the "Enter Key" to break sentances into lines: see? Each point is one or two sentances, and takes 1 line.
<img width="1411" height="142" alt="image" src="https://github.com/user-attachments/assets/6ad3deed-5532-4d28-b029-1a2959f48a13" />
The issue is that these single-linebreaks gets smushed together when displaying the .MD. Tapping "Enter" twice is gangly and awkward, why can't I create a chrome extension that automatically does it for me?
A chrome extension for ensuring my linebreaks that I broke the line with are indeed linebreaks.

# "Update Readme.md" What a useless message!
Scene: The THINKER has finished wighting a request for a C++ Database Setup app. The thinker hits "commit". 
THINKER: "At last! Let me confirm my changes, for I am done."
But No! Plot twist! The commit name for the "C-Plus-Plus Database Setup" is "Update Readme.md". "Update readme.md"? What got updated? That's a rotten name!
Changing a commit name is possible with "git commit --amend". Unfortunantly, that command isn't available on GitHub.com . This Repo is pretty much only a readme. I don't have a local branch. I cannot use the terminal to run "git commit --amend". I would like to be able to run this git commit --amend from the browser! The browser already knows what commit, repo, & user is being refered to, after all.

A secondary consideration is why the default name was "Update Readme.md" in the first place. I had a header line! Why not use the New # Header line for the default name if one is added?
