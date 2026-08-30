# For-Later-Project-Ideas
All the various ideas for coding projects I've had; Sequestering them here prevents me from opening yet another Repo &amp; Diluting my coding powers even further!

You may have noticed that two categories dominate this list:

1. Video Game Mods. The argument for Video game mod being low priority is easy. Unless I go buck-wild on advertising and get thousands of downloads, video game mods are hard to put on a Resume.

2. GitHub UI Nit-picks. Whenever I encounter a GitHub UI annoyance, I'm on GitHub. https://github.com/ikyman/For-Later-Project-Ideas is never far away!

Importantly, given my coding knowledge, all of these project ideas are possibilities! If anyone reading this list has a project they want done, let me know! Public demand is a powerful enough motivator for me to up the priority level on a requested project!

# A "Package-Manager"-like program for .MDs.
.MDs instructing the AI what to do and how to do it are a common aspect of Coding nowadays.
They guide the AI, helping any proposed changes remain grounded. 
Writing these .MDs is inconvient, though. I have to Prompt the AI multiple times, cross-check annoyances across multiple prompts, and then write the MD Myself.
Would it not be easier to have a central repository of Best Practices .Mds, and then Pull them as needed?
Ideally, this could cross-check with my package manager. This could see what libraries I'm using, which can then suggests .MDs tailored for using that library.
Before Working on This Project: I believe Gleb Bahmutov ( https://github.com/bahmutov ) either has worked on something similar or has worked on something similar. 

# Minecraft Mod: Grillager
Add a new Type of Illiger-type Mob to Minecraft: The Grillager. This mob shall: 
A. Have a funny name.
B. Be based in the nether, and
C. Attack the player with Red-hot iron Bars. These Iron bars shall be a problem for the player: In addition to being the main damage-dealer for this mob, the Grillager can also block most damage by using levitated iron bars as a shield.
I envision the Grillager Shot-gun-blasting the player. Shot-gun blasts with multiple projectiles doesn't do much in Minecraft, owing to post-damage immunity. 

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

~~I don't know what the Henry Stickmin collection is programmed in~~, nor do I know how to mod it. But if this was React, the suggestions made shouldn't take too long.
(Correction: The AppData Folder for the Henry Stikmin collection is "com.innersloth.henry.HenryFlash". Aha! I recognize this long reverse-url naming Scheme! Java! )

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

# My "Pygame Buttons for a user interface" From the Map-Resizer.
Aaah! A Tie-in! Video games plus "Things I've done before". I once wanted to resize a Video Game Map.
More accurately, I wanted the map re-sized. I refused to do it myself. I made a program to do this for me. 
Not only would I refuse to re-size the map myself, I refused to Re-size this map without a good UI. 
I was using Pygame for the front-end of the program. Unfortunantly, Pygame doesn't have any built-in objects for things like buttons.
Long story short, I wound up (with the help of a little bit of AI) writing a collection of UI Elements, including Buttons, checkboxes, and textareas. 

[I later Wrote a tutorial on using Various Front-end Framework](https://github.com/ikyman/A-Gio-Exposition-for-Pygame-Tkinter-Folk/tree/main )s (2/3rds done at the time of this writing.). The trilingual program written used buttons. Gee Willakers! I have buttons in Pygame. I Copy-pasted a Pared-down version of the UI collection.

Copy-Pasting was fine in this particular context. This was a tutorial on how to use Pygame, after all. "Import an outside library to learn how clicking works" is wildly unhelpful. I was obligated to explain the guts!

What prompts this addition to the list is this: I may want to once again add a button or a textarea to a Pygame Program. When that happens, I will refuse to write the button once again. Repo the UI Interactable collection, & hook it to my pip!

[I have competition in this realm](https://github.com/AustL/PygameWidgets)! I have two options here: Option 1: The way of the most serene stream: There already is a Widget Library. It has many stars, I'm sure it's entirely adequite. Could use a Builder pattern, though.
Option 2: The way of the steadfast ox: A coup! Seize the Realm of Pygame Widgets! I already have a half-tutorial I can repurpose for ease-of-adoption purposes. I could also blow people away if I make a video series! It'll juice up my view & subscriber count, too. 
That of corse, begs the question on how that programming tutorial will even look like.

# Emojis In GitHub:
I recently Wanted to add an Emoji to a comment on one of my commits.
I did the obvious: I searched for the Emoji button.
There was no Emoji Button.
I managed to manage by opening Discord, typing all my emojis there, & Copy-Pasting. 
How does Github not have these on-hand? This certainly goes on my "Annoyances that I could fix using my computer science knowledge, but don't want to on account of having too many projects already". 

# A "Bar"? That's A Ladder! 
I made a MOC. This MOC was quite neat-o. I therefore resolved to capture that form in an easily digestible digital form. I shall make an MLCAD Model!

Turning an IRL-Model into a LDRAW Model means I double the duty of finding parts for that model: I already fished out the IRL piece from my Lego Collection.
Now, too, I have to crawl through the very expansive list of parts in the LDraw Parts catalogue to somehow isolate the corresponding part. Woe upon me if my Personal name for a part differs from LDraw's name for that part!

What shifted my Irk-dom into overdrive is this: I already had a photograph. I have the physical model in my hands! I know what part I want! Right there! In front of my Eyes!

[HEY!](https://www.youtube.com/watch?v=2GlbODa0HFo)

I can Build a Machine Vision program`*`! This Program takes in a photo of a Lego Model. The Program returns an estimated list of parts needed to build said model.

`*` Then Again, Maybe I can't. On the one hand, finding training data should be easy: I can use Official Lego Sets, which have their lists of parts listed. 
On the other hand, there are a [billion ways to combine 6 Lego 2-by-4 bricks. ](https://web.math.ku.dk/~eilers/lego.html). With Lego, output sets add up FAST.
What would the output Vector be? What would be the output of this Optimized Linear Algebra jumble?
A Vector, where V_i = the likelihood of the piece associated with position i is in the photographed model?
That would lead the output Vector too big! Historically, my forays in machine learning can be summarized as "Wait 10 minutes: Enough time to get bored but not enough time to render switching activities worth it. Model Fails. Rinse and Repeat". Make 6 tweaks, re-run model training 6 times, and BOOM! An entire hour! Wasted! Completely wasted! With no redemption!  

# "Hey! I've got a fun Game! Like, Y'know, A Joke."

AutoAudioAuxilery (GitHub Link: Currently Non-Existant) Provides the Filler word Detection.
https://github.com/shiranD/interruption_detection provides interruption detection, and I ASSUME it provides speaker Identification, too.

Bolt those two programs together. Now all I need is a word-counter to assign per person.
A word counter, and an end-of-sentence detection, if the end-of-sentence-detection isn't already handled by AutoAudioAuxilery.

The aim: Slap a microphone in the middle of a table. Feed the recording into this program. 
This program then generates a list of Persons, along with a whole load of data about that person's speaking patterns.

The game is this: With said anonymized list of persons, would it be possible to assign each conversationalist to each anonamous portrait?

Issues: 1. AutoAudioAuxilery isn't done. Nor is it started, unless you count the Audacity & Excel files + an empty CMakeLists as "Starting a Project".
2. I have never used the interruption_detection program, nor do I know how it works. 
3. I have read the book "How to Win Friends and influence people". Igniting an argument over who interrupts or overuses the word "Like" the most isn't in Carnegie's list of recommendations.
4. Games have to have a win condition: Being right. The program therefore has to ID each speaker. Another Module to bolt on! [That means more work](https://www.youtube.com/watch?v=liuNSRIcfSQ)!
There are two methods of identifying people. Identifing people without visuals nor context relies on the good will of third persons. Furthermore, I might forget that people can have more than one name, and my app accidentally splits the one person "Harold Odie" into 4 different dossiers for "Harry", "Harold", "Odie", and "Garf". 
I could also identify people by triangulating their position by via two speakers. This can be defeated by the inconvenient human behavior called "Moving".
5. AutoAudioAuxilery 's .aup has a section titled "Token Female Representation". This "Token Female Representation" section is 50% male anyways. 
I would be pleasantly surprised if AutoAudioAuxilery can handle women without additional .aups. Using anything derived from AutoAudioAuxilery with more than 2 people runs the almost certain risk of running into a woman, a situation it would be wholly unprepared for. 

# Excel could Excel with Excellent Colouration!
For my [Egyptian Senet Issue](https://github.com/ikyman/Non-AI-Chess-AI/issues/11) in https://github.com/ikyman/Non-AI-Chess-AI , I put together a silly graph.
<img width="945" height="514" alt="image" src="https://github.com/user-attachments/assets/52392e48-7517-4303-8c6c-90b0ce0d066d" />

I want you to imagine: Imagine I didn't leave the graph unlabeled. Imagine I instead gave it a title: "Senet Interest over time".
Now imagine that my computer didn't try to correct "Senet"(Ancient Egyptian board game) to "Senate"(Collection of Boring Ancients). 

Ancient Egypt? Graph Colour Palette solved! Yellow and Blue! 
Then what? After having my colour palatte chosen for me via the Ancient Egypt theme, I had to manually pick them out myself! With my fingers and mouse!

This shouldn't be tremendously difficult: Thanks to CMYA, Colours are already enumerated. Take in the graph/page/file title as a word-vector encoding, output a handful of colors, & then contrast-correct to ensure the resulting graph is readable.

Ironically, I recently was reminded that I once interviewed with the "Microsoft 360 Copilot Team", the Microsoft team for implementing exactly the suggestion I laid above.

# Better Kill Ticket Distributions
I once was playing one of those "Hundreds of players Build a Minecraft Civilization" Events.
Most of these events have "Kill Tickets". Wanna Kill someone? Gotta write a little ticket explaining why this homicidal inclination is justified, lore-wise. 
This Prevents RDMs, or "Random Death by a Maniac". Also known as "Wow! Someone's back is turned! Free Stuff!"
My Guess is that Kill tickets also help with writing the script for the final Video: If an important character is killed, voila! The explanation is right there!

I so happened to want to kill someone. I wrote a kill-ticket. I waited.
Then I waited and waited and Waited some more. Staff! What is your Problem! You're too Slow! 

During this time waiting for my kill ticket, I pondered on the trials and tribulations of event staff.
What if I was staff? Would I have answered my ticket? no cap that fr sound like an "ohio" from me, blud.

At least from the Ticket-requestor side, a new kill ticket creates a new Discord channel.
Combing through 300 tiny paragraphs in 300 auto-generated Discord channels falls is drudgery.

The workflow could be improved via exporting all the data to Excel. Then I can sort by Kill Requestor and Requestor Victim.
That could speed things up a little. Sorting by Requested Victim handles the cases where a group plans a hit on someone. That's nice. Good Luck, have fun, you're all approved!

That would only marginally speed up Kill-Ticket Processing, though. Hence this App Idea.
Features: This combs through the list of accepted players. This also combs through the "Business/Faction" advertisements Channel.
If the bot is allowed on a Business/Faction server, it also scans for assigned roles for a particular player.
From this, the program can get the basic information about each player: Namely the Factions & "Importance" (Assigned), as well as any other manually-assigned tags that may be pertinent to the event.

This little information (Plus a good UI), should speed up kill-ticket processing quite a bit. Large numbers of kill tickets across two factions? The Buck gets passed on from here! It's not up to the staff to prevent two countries from hating each other. Mass approved! Doubly-so if the National Leaders themselves put hits on the other sides.
One person with many kill tickets but little "Official" Position? Probibally deserved it, Mass approve, 7 tickets processed in around a second. Horray!
Mutual Kill Tickets (ActionSolo Requests to kill BumbledBe, BumbledBe Requests to kill ActionSolo)? Reading both of their explanations at the same time WOULD help me come to the same decision. 
What would also be helpful is knowing if anyone related to either ActionSolo or BumbledBe has any opinions on which of the two should die. 

I can have filtering, too. Someone posting a hit on someone of the same faction _is_ fratricide! That certainly is the sort of tricky situations which require a more wholistic Birds-eye view.

This app might be formed around a "WorkQuenue". Epic had "WorkQuenues" For similar processing.

# Acrostic Puzzle Quote Validator.
7:47PM: "Today I shall make an Acrostic Puzzle", I said.
The Quintessential Acrostic Puzzle is a quote. The cossword-esque puzzle itself contains the quote, while the first letters of each clue spells out the speaker of said quote.

After agonizing for hours over which quote and which quote-maker to use I finally settled on "You think you just fell out of a coconut tree? You exist in the context of all in which you live and what came before you." -Kamala Harris. Great! Quote found. Now it's time to start writing all the clues!

Unfortunately, no. You think you just fell out of a coconut tree? You exist in the context of all in which you live and what came before you." -Kamala Harris can't comport with an Acrostic.
The first hint has to start with "K", meaning "K" has to be a letter in the quote. Does "Coconut" have a K in it? No!

In theory, I could design the puzzle so that the first letter of every clue is omitted from the quote. Doable, but this reduces crossover, thereby making the puzzle harder.

Back to the drawing board! I'm going to have to find another Quote! "Eat My Shorts" (Bart Simpson)? No, that also doesn't work.
Why should I be the one to cross-check the acrostic Koshur-levels? 

Here's my Proposal: I input a Quote-maker. The computer automatically Queries WikiQuote for Quotes by said person. If every letter of the Quote-makers name is found within the quote, Voila! A Quote for my Acrostic! Now I can get to the fun part, writing clues!

Wikiquote also stores quotes by movies. Nice! I can also quote movies in my acrostics. 

Additional QOL Factors: For Non-English Speakers, allow for some synonym-subbing.
"If we find them in the toilet, we'll rub them out in the outhouse" - Putin is the version Wikiquote has. This has no 'p', and is therefore invalid. However, I have seen an alternate version, 
"If we find them in the toilet, we'll wipe them out in the outhouse" - Putin. This has a "p", and therefore comports with Acrostic puzzle etiquette. 
What words are croppable? In order for my hints to not be too long or too short, being able to keep or throw out non-essential words gives me sweet, precious freedom!

Separate "Quotes By X" from "Quotes About X".
"I felt a bit better. If Neil Armstrong felt like an imposter, maybe everyone did" - Neil Armstong is a vastly different quote than
"I felt a bit better. If Neil Armstrong felt like an imposter, maybe everyone did" - Neil Gaiman

"This isn't on Wikiquote but I Like it.": Run the Acrostic rules on user-inputted quotes. Shouldn't be too hard.
 
There have been a Dozen Acrostic-Puzzle-Helpers made so far: Why should this one be different?
Most of the existing ones on GitHub Query AI or require an API. Acquire API Access for an Acrostic? No thanks!
Most of the existing Github Acrostic Repos also focus on solving an acrostic, not making them. Perhaps that explains all the Required APIs.

# I'm in the middle of Edits! Gimme a Popup!

This has happened twice already. Twice! I was writing something in one of my Github .README s. I switch to another tab, to gather information pertinent to what I'm writing in the README.
Then, I close the tabs. Either through trigger-happiness or a wide Ctrl-W Catch-net, the initial README is closed.

This erases all of the previous changes. Now I have to write this again! I hate Writing, this redundancy is indeed foul!

My solution: Add a "You have unsaved changes" Pop-up. 

Editor's note: This issue is especially infuriating because editing a comment creates a pop-up of the exact type I want for Editing a file
<img width="433" height="136" alt="image" src="https://github.com/user-attachments/assets/ce83229a-63c3-4529-a0f4-b81942488a11" />

Which dunderhead decided that adding a comment was important enough to require a "Changes you made might not be saved" popup, yet editing a file is frivolous activity that can be abandoned with little consequence?
I'll tell you what this choice does: this leaves me expecting a pop-up on the vastly more important "editing a file". What is a Readme if not COMMENTary on a particular repo?

# Dual-Language filtering.
I recently wanted to review, to snuggle, my collection of "Terribly-written Games from Middle School". 
The only programming language I knew in Middle School was Python. Hence all of my "Terribly-written Games from Middle School" were in Python. 
I Filtered my GitHub repository by Python.
<img width="289" height="355" alt="image" src="https://github.com/user-attachments/assets/ddb29c41-11ed-48ef-ab3b-42b778819ea9" />
But wait! [Pizza Quest](https://github.com/ikyman/Pizza-Quest) I judged to be similar enough to a visual novel. I created and Empty Ren'py Project. 
Then I sent this Empty Ren'Py Project to join the Pre-Ren'Py Python code. The Ren'Py Overpowered the Python: Pizza Quest is Ren'Py now!

I'm still looking to snuggle collection of "Terribly-written Games from Middle School". I update my language filter: Python OR Ren'Py.
<img width="289" height="355" alt="image" src="https://github.com/user-attachments/assets/66b22402-8dbc-46ea-9457-1b94781bf7d4" />

However! Such filtering is Impossible! I can only filter one Language at a time! No Multi-select!

 More filtering suggestions: Whhaddya think the "Py" In "Ren'Py" stands for? There's other examples where Languages are similar enough that they should be grouped together. 
 Typescript is Javascript with Types. C++ and C have are Quasi-Siamese twins. Once I had a C/C++ project in early stages of production, so that CMake eked out a plurality over both C and C++. CMake? For Making C. 

Speaking of pluralities, GitHub's handling of Multi-Language Repositories is less than stellar. A Language that takes up 35% of a repository is significant! Yet GitHub completely ignores such substantial sections in favor of the language of absolute plurality.

This is Basic Poli-Sci, how could my Programming Platform flop like this? I could forsee myself wanting to filter over "Programmed with Java" instead of "Java Project"

Allow "None of the Above/Below" As a filtering option. https://github.com/ikyman/For-Later-Project-Ideas is entirely a Readme, and thus invisible to this Language Filtering.

# "Thanks for the info, I'll be sure to... do... something."
This happens every time whenever I appear in-person in the job search. I forget to schedule an hour next day for the inevitable follow-ups.
Ugh! I hate following Up! Following up is chewing on the cud of failure. That was the whole point of handing out resumes in the first place! You Follow up on me! 
I want said follow-ups to be as fast as possible: Then I can get it over with, and do something, anything else!

As it stands, I have my notepad on my desk. I have to phone phone numbers manually, query career pages via typeing in the url, and a whole lot of busy-work.
My notebook is quite messy: My handwriting isn't very neat, half the time I'm without a table to write on, and companies are mish-mashed across the page. 

Here's what I propose: Optical Character Recognition. Take a photo of the page and create a nice and orderly table. This table has company, Action-item, any names I acquired, plus extra notes I may have jotted down.
Thus, All I have to do is click to email/call/go to "career page" (I get shunted to the "career page" a lot. Career Page! Totally Useless at anything related to career!)
I can also click a name to get a Linkdin Query of the "Related Person". 
The table can also Track done-ness, after I do any actionable Item.

An Issue I see arising is for phone calls: The phone is my computing device with a much more convenient camera. The phone is also the device that's in use during phone calls. Try to call? Wave goodbye to your script & Notes!

Alternatively, I could grab a green crayon & shade green any "Follow-up" that is done. Don't get the links to do said action 25% faster though!
