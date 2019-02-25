# #100DaysOfCode Log - Round 1 - Lawder

The log of my #100DaysOfCode challenge. Started on January 1, 2019. 🍾

## Log

### Day 1 (1/1/19)
Continued work on Slate app. Made some progress on enabling commands that use multiple key presses, which has been a bit tricky...

### Day 2
[Slate App] - figured out how to enable double key press (space -> dash) for bulleted lists, but ran into issues in trying to modify content....so then I explored dark mode using Lyft ColorBox haha. May have to come back to Slate at a later date.

### Day 3
Started to do node.js TH but didn't work...so revisited NBA player app. Did some light structuring & styling, and started work on incorporating react-pose.

### Day 4
[NBA-players] - continued work on incorporating react-pose. Got animations to trigger onFocus of search, and re-arranged some other elements to make it work.

### Day 5
Added a bit more polish to react-pose search transition (e.g. pushed down player stats). Tried to use PoseGroup briefly but couldn't figure it out. Then worked on getting react-router to work in curious-lawder, although struggled w some parts.

### Day 6
[NBA-players] - figured out onBlur (using refs), and also updated behavior to work for a 2nd (or more) search.

### Day 7 (1/7)
[NBA-players] - got a static version of the giphy API working and displaying an image. Need to update the URL to include the searched for player (string).

### Day 8
[NBA-players] - got the giphy API to pull the searched for player, which involved moving the request to the parent PlayerSearch component, and use promises to delay the request. Could def be improved tho.

### Day 9
[NBA-players] - Got the API to pull a random gif of said player. Styled the header to have gif, and display text over gradient blended background. 

### Day 10
[NBA-players] - Started work to trigger input to transition out upon results: created new bottom button component that focuses input onClick. Now need to figure out how to animate input in & out...

### Day 11
[NBA-players] - Figured out how to animate input to a 3rd state using react-pose. Started to investigate why onChange is being called onBlur for Downshift.

### Day 12
[NBA-players] - created a loading spinner while waiting for stats to return, which required refactoring loading state logic and creating a CSS keyframes animation.

### Day 13
Looked into what I should work on next; ended up starting Express (Node) tutorial on TH.

### Day 14 (1/14)
[Express TH] - Continued work on Express tutorial on TH - mainly just learned Pug.

### Day 15
[Express TH] - Continued work on Pug, and started learning about get & post requests.

### Day 16
Nothing fuck...

### Day 17
[Android TH] - Starting tutorial for basic Android app. Downloaded AS and did some setup, then started tutorial, then AS crashed, so started to get back to where I was lol.

### Day 18
[Android TH] - Continued work in Android tutorial; worked on styling a fun fact and adding a button.

### Day 19
Nothing ugh

### Day 20
[Android TH] - Added functionality to the button to generate a random fun fact.

### Day 21 (1/21)
Nothing ugh

### Day 22
[Android TH] - Set background to random color onClick. Also learned about refactoring to separate classes, and app icons for different screen resolutions.

### Day 23
Finished Android TH initial tutorial (learned about debugging and tools). Also explored custom button styling via drawables.

### Day 24
(less) Continued playing around w Android styles. Started to learn about view groups, but a bit tricky.

### Day 25
Nothing ugh

### Day 26
(less) started new Android TH tutorial around styles

### Day 27
(less) figured out how to open someone else's Android project; e.g. installed relevant SDKs

### Day 28 (1/28)
(less) I did a little something; I think tried to follow Android project and failed...

### Day 29
(Blend) Played w Shopify (Polaris) table for upfront rates. Also wrote Terms & PP in HTML/CSS.

### Day 30
[Express TH] - continued tutorial. Learned about cookies: namely, how to set and read them. 

### Day 31
[Express TH] - learned how to redirect to different pages onSubmit, and started learning about middleware. 

### Day 32
[Express TH] - continued learning about middleware: next() function and error handling. Also took a break to learn about closures in JS.

### Day 33
(less) [Express - TH] - pulled out routes into separate index.js file.

### Day 34
Nothing ugh... (Pats won tho)

### Day 35 (2/4)
[Express TH] - debugged error in TH tutorial, due to using old code. Set up cards to be configurable and have their own URLs; also imported data from a separate file.

### Day 36 (2/5)
[Express TH] - added logic to make card URLs more robust: defaulting to question if no side is specified, picking random card if none is specified, etc.

### Day 37 (2/6)
[Express TH] - debugged error where card randomizer wasn't working. Added logic to proceed from home into the flashcard game, and learned how to load styles in Express (but skimmed). Finished tutorial.

### Day 38 (2/7)
(less) Started looking into how I could create downshift for LO search. Want to create test version using medical data.

### Day 39 (2/8)
[Downshift] - started advanced downshift work. Tested limits of JSON, and also had to clean up data.

### Day 40 (2/9)
[Downshift] - figured out duplicate issue: was using wrong field for the "key". Then tested limits of JSON (great for 2000 items, didn't test more) and styled the UI.

### Day 41 (2/10)
[Downshift] - looked into different ways of doing fuzzy matching, but failed.

### Day 42 (2/11)
Nothing ugh

### Day 43 (2/12)
Nothing ugh

### Day 44 (2/13)
(less) A lil downshift fuzzy thing. Then fainted in the aft lol

### Day 45 (2/14)
Nothing ugh

### Day 46 (2/15)
(less) A lil downshift playing around...should move on. Then played around w styling

### Day 47 (2/16)
Nothing ugh

### Day 48 (2/17)
Nothing ugh

### Day 49 (2/18)
Nothing ugh

### Day 50 (2/19)
Researched different Firebase tutorials, then started Firebase auth tutorial w/ react. Set up project w various paths.

### Day 51 (2/20)
[Firebase] - continued tutorial at Beacon. I think I set up React-router, then created FB account.

### Day 52 (2/21)
Explored realtor onboarding animations in CSS/React. Also continued FB tutorial, setting up my FB files.

### Day 53 (2/22)
[Firebase] - enabled email account creation in FB, then created sign up form and event handlers.

### Day 54 (2/23)
Got the point where you could sign up and should connect to FB, but didn't work. Then played around w realtor onboarding, and got pre-approval animations synced up.

### Day 55 (2/24)
[Firebase] - finalllly figured out the issue: one of my functions wasn't actually returning anything cause of ES6 syntax (need to explicitly return objects). Then implemented sign in link.
