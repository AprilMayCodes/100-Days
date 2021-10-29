# Round 3 Log

**Start date**: 08/17/21
**End date**:


## Goals

-   Make a tarot journal/tracker app that can log readings and track reoccurring cards.
-   Practice coding or following some sort of lesson for a minimum of 30 mins each day. (I'm being realistic this time, sue me lol)

## Day 1 - 08/17/21
60+ mins

-   **Project You Are Working On:** Tarot journal
-   **Progress Today:** I sketched out what I'd like to make, and started doing some more reading about Flask and watching a few tutorials.
-   **Challenges you faced:** I keep getting thrown when it comes to using the database, so I know that's going to be one of the more challenging parts of this.

## Day 2 - 08/18/21
60+ mins

-   **Project You Are Working On:** Tarot journal
-   **Progress Today:** Lots and lots of tutorials. I'm so confused about creating a database, and how the relationships will work, as it applies to what I'm wanting to make.
-   **Challenges you faced:** Learn more about Django and if it's something I want to learn and use for this, instead of Flask

## Day 3 - 08/19/21
60+ mins

-   **Project You Are Working On:** Tarot Journal
-   **Progress Today:** Started following a Django tutorial for making a blog, but making changes so that it fit my tarot journal idea.

## Day 4 - 08/20/21
60+ mins

-   **Project You Are Working On:** Tarot Journal
-   **Progress Today:** Followed another Flask blog tutorial while making changes to it to suit what I'm working on.
-   **Challenges you faced:** I've got like 3 incomplete projects right now because I keep starting to follow these tutorials, realizing I'm in way over my head, and then going off to start something different. I don't want to start learning all the way at the beginning, because I've got this idea in my head that I want to make and I'm eager to work on it. But, I just don't know enough to work on it yet. I'm finally accepting it's not practical to learn all this as I go, and am gonna start at the beginning tomorrow I think.

## Day 5 - 08/21/21
60+ mins

-   **Project You Are Working On:** Tarot Journal
-   **Progress Today:** So much! I decided to go back to it again, starting over but this time taking what I've learned from the tutorials and kind of piecing something together on my own, instead of trying to follow along with the video as I build something completely different. I know I still need to go back and start at the beginning, but I've learned enough to put this together and I've worked through so much of the stuff I'd been struggling with. Anyway, so far today I've: Got the general layout set up, created the database with the foreign keys and relationships set up right (finally!), created a form so a reading can be added to the database. The home page lists all the current readings, and you can sort by querent. I also got some images added
-   **Tasks For Tomorrow:** See about tags? Find a way to add the cards to the readings. Otherwise, work on the draw a card section. Add javascript?

## Day 6 - 08/22/21
60+ mins

-   **Project You Are Working On:** working through the Learning Flask Framework book
-   **Progress Today:** None on my Tarot app, unfortunately. I had to work today so I couldn't devote as much time to it. Instead, I worked through chapter one and most of chapter two of the Learning Flask Framework book. Set up a virtualenvironment and started following along (actually following, not just cherrypicking pieces I need), to make a blog app. I'm hoping to be able to apply it to my tarot journal app, but baby steps.
-   **Tasks for Tomorrow:** Finish chapter two and the tag system for the blog app, and get started on chapter 3. Maybe work the Draw A Card function for the tarot journal, if there's time.

## Day 7 - 08/23/21
60+ min

-   **Project You Are Working On:** Tarot Journal
-   **Progress Today:** Turns out that book is a little bit outdated. I skimmed the chapter on using a db with Flask and it was sort of helpful, but I'm not gonna bother following the lessons in it. I'll find something else to do on busier days. In the meantime, I've got a database made! Complete with many-to-many relationships for the tags. I got some new ideas for features I'd like to have available in the app so I'm gonna try to plan those out before I do more with it. I think I'm going to edit the db the rest of the way in the DB Browser, and then use automap to finish building the app around the db I've been working on. (Based on [this video](https://www.youtube.com/watch?v=UK57IHzSh8I).) That way I'm not constantly deleting and restarting the db when I'm checking if the code works. I want to be able to add reading and card entries, but there also needs to be the static 78 cards in a db as the tags, it'd be a pain to redo that over and over because I think of a small change to make.
-   **Tasks for Tomorrow:** Restructure the app to be used around an existing db.


## Day 8 - 08/24/21
60+ min

-   **Project You Are Working On:** Tarot Journal
-   **Progress Today:** I think I was wrong about making changes to the db. For now I'm not changing it, but I might once I finish the tags issue. Added a space to add tags, but now I can't figure out how to access that data.
-   **Tasks for Tomorrow:** Work on the tags thing
-   **Update:** I came back to this for a bit today and got it working! I can now add tags to posts and they're added to the database as well. Fixed a couple other minor db issues as well. Though, the more I get done, the uglier this thing gets lol. I'm going to have to take some time out to just focus on the styling pretty soon here, before it becomes so daunting that I deem it not worth doing. I might work on that tomorrow, otherwise I'll be focusing on creating the Card page, with basic card meanings, etc.

## Day 9 - 08/25/21
60+ min

-   **Project You Are Working On:** Tarot Journal
-   **Progress Today:** Got the card pages added and updateable, also added all the cards to the DB and made sure the tags worked with the new cards. Did a bit of formatting. It looks more balanced now. I'm working on figuring out how to use modals, that's how I'm going to handle the draw a card feature I think, but I'm having some trouble with it so far.
-   **Tasks for Tomorrow:** Modals and more styling

## Day 10 - 08/26/21
60+ min

-   **Project You Are Working On:** Tarot Journal
-   **Progress Today:** Fixed the issue with the modals, somewhat. Draw a Card works, for a random deck or for a specific one. Readings can be updated now. A couple more styling things, but its still really barebones right now. I'll make it pretty once it's completely functional, I think. Also added a bunch of cards to the db, but I don't think that really counts as 'coding', esp since I'm using the DB Browser instead of actually writing the SQLite code to make the changes. Also made it viewable, in it's current state at least. I'm not sure how heroku works with updating it but for now it can be seen at https://flask-tarotjournal.herokuapp.com/
-   **Tasks for Tomorrow:** Work on the Card Collection section, editing notes on those cards and maybe adding images. That, or making the card tags in the Readings link to their card pages.

## Day 11 - 08/27/21
60+ min

-   **Project You Are Working On:** Tarot Journal
-   **Progress Today:** Linked the tags to the card pages. Did a little bit of styling on the draw a card part. Added a space for the journal prompt, and added some stuff to the db for those cards. Can also edit the notes for the cards in the collection now as well. Spent a bit of time trying to put a search bar in the navbar that would go to a card page when searched but I can't figure out how to make it work, without copying the code into each individual route and that just seems like overkill. I'm sure there's a better way so I'm gonna hold off til I figure out what that is.
-   **Tasks for Tomorrow:** Change the collection page to show the deck specific details at the top, and the card specific details below. Maybe add notes for each deck to the card pages as well.

## Day 12 - 08/28/21
60+ min

-   **Project You Are Working On:** Tarot Journal
-   **Progress Today:** Added Carousel to the card page, and the details from the specific cards, below the general card info. Added a bunch of notes to the db.
-   **Tasks for Tomorrow:** Make sure images work for the carousel and get some added.

## Day 13 - 08/29/21
30+ min

-   **Project You Are Working On:** Tarot Journal
-   **Progress Today:** Got the enter card space to be smaller but I can't make it like, inline or whatever. I'm gonna have to retype the whole form thing I think, so that I can set it up properly. Also got some images added. Not many, it's gonna take some time to get it all done but I made sure they work so there's that. Only about 30mins today, gotta get ready for work.
-   **Tasks for Tomorrow:** More styling. Add images to collection page. And to modal?

## Day 14 - 08/30/21
60+ min

-   **Project You Are Working On:** Home Binder - App?
-   **Progress Today:** None that will stick, I'm afraid. I was thinking about taking my various home binder collection and combining them into one thing in the form of a flask app, but instead of starting with the back end I spent a bunch of time messing around with HTML only to realize I'm gonna want the other stuff done first anyway and to know how it will all be set up and stuff. So instead I've just gotten some more stuff added to the db on the tarot one but no new code that I'm gonna keep.
-   **Tasks for Tomorrow:** Get back to styling. Stop stalling.

## Day 15 - 08/31/21
30+ min

-   **Project You Are Working On:** Home Binder. I'm still stalling.
-   **Progress Today:** At least it's stalling by messing with HTML. Learn by doing blah blah. I sort of set up what I'd like a week view page to look. It's cramped, though. Gonna see if I can make it look a bit neater tomorrow. I'll get back to the tarot app another day. I'm still adding notes to the db every day, that's progress toward completing it.
-   **Tasks for Tomorrow:** Make the week view a bit neater. Maybe make a few other pages to decide if this is something I'm actually going to work on or not.

## Day 16 - 9/1/21
60+ min

-   **Project You Are Working On:** Home Binder and Tarot Journal
-   **Progress Today:** Watched some tutorials on the calendar module and datetime and decided to hold off on the planner/home binder thing til I understand a bit more. For the Tarot Journal, I got a bunch more images added, and got them sized right and the card page basically set up how I want it to be. Then started on the navbar, but only got as far as changing the background color.
-   **Tasks for Tomorrow:** Finish styling the navbar.
    **Update:** Did a bunch of styling stuff, added color, some hover effects on the buttons. I'm really just about done with it I think. It still looks a bit wonky but we're getting there.

## Day 17 - 09/02/21
60+ min

-   **Project You Are Working On:** [Tarot Journal](flask-tarotjournal.herokuapp.com)
-   **Progress Today:** I've got it done! It's still ugly. The images could use resizing. I'd like a better font in the navbar and probably for the whole thing. There's just a couple little things like that. But I got it looking prettier-ish and its fully functional and useable so I'm going to start using it I think. Which means I'm gonna stop sharing it lol but the point its at on heroku is a pretty complete point. I'm comfortable enough with it.
-   **Tasks for Tomorrow:** Home Binder/journal app

## Day 18 - 09/03/21
30+ min

-   **Project You Are Working On:** Home Binder
-   **Progress Today:** Figured out how to use the Calendar module. At least a little bit. I've got something started but again I can't do much without having more planned out. I have no clue right now what the database should look like, how anything should really be organized. I've got to figure that out first.
-   **Tasks for Tomorrow:** Pick a project, I guess.

## Day 19 - 9/04/21
30+ min

-   **Project You Are Working On:** Home Binder
-   **Progress Today:** Messed around with the calendar module some more. I think I understand it enough to set something up, once I know what it is I want set up. Gonna press pause on that for now. Then I started an on-call organizer but realized it's probably better done in excel. I think I'm gonna try to learn excel and work on that. And yes, I'll be counting those as days of coding. At least for now, lol
-   **Tasks for Tomorrow:** Learn Excel

## Day 20 - 09/05/21
30+ min

-   **Project You Are Working On:** Reading the docs for kivy and tkinter
-   **Progress Today:** None really. started the Pong tutorial with kivy, got bored and started reading about tkinter. All of it seems like way too much going on for me. I'm not sure yet what I'm going to work on
-   **Tasks for Tomorrow:** Pick a project

## Day 21 - 09/06/21
60+ min

-   **Project You Are Working On:** Training website
-   **Progress Today:** Spent an embarrassingly long time trying to figure out how to use bootstrap to make a side navbar, but I got it eventually! decided to work on a technical documentation sort of page, kind of like the one I had to do for my freecodecamp certificate,but this time using flask and making like a guidelines/training sort of thing for my job. Working on the database now. I'd like it to be set up so that I can grab the headers from the database to create the links in the sidebar, instead of listing each individually. I'm sure it can be done, I'm just not so sure I've got it figured out yet.
-   **Tasks for Tomorrow:** Work on the sidebar and db

## Day 22 - 09/07/21
30+ min

-   **Project You Are Working On:** Training Website
-   **Progress Today:** Got the sidebar to work with the database, but I think I'm overcomplicating the db a little bit. We'll see. I'll work on it more later if there's time.
-   **Tasks for Tomorrow:**

## Day 23 - 09/08/21
30+ min

-   **Project You Are Working On:** Tarot Journal
-   **Progress Today:** A bit more styling, and added a space for a regular journal entry and a page that displays all of them.
-   **Tasks for Tomorrow:** Add the links for the journal entry into the nav and maybe some sort of "read more" button

## Day 24 - 09/09/21
60+ min

-   **Project You Are Working On:** Several.
-   **Progress Today:** Started with a kivy tutorial. Changed my mind and switched to tkinter. Realized my heart isn't in it and decided to give up on learning to make a gui for now. Changed a couple colors on the tarot app. Decided to work on a new version that isn't just for me but could be used by anyone. Then decided to work on like a tabletop game sort of DM screen type thing. I didn't get too far into the content of that because I'm working on getting the users created, but I've made progress.
-   **Tasks for Tomorrow:** Finish the user login part of the tabletop thing, and maybe create that for the tarot app 2.0

## Day 25 - 09/10/21
60+ min

-   **Project You Are Working On:** Tarot v2 and Tabletop thing.
-   **Progress Today:** Created login and register pages for both of them, and started working on how I want the Nav set up for the tarot one.
-   **Tasks for Tomorrow:** Set up the user authentication settings on the tarot one, and the other if there's time.

## Day 26 - 09/11/21
60+ min

-   **Project You Are Working On:** Tarot v2
-   **Progress Today:** Got the home page set up the way I want it to be. I'm working on it page by page this time, instead of making the whole thing work and then styling it. Styling the other is too daunting a task, I think if I do it in bits as I make each page it'll lead to a neater finished project.
-   **Tasks for Tomorrow:** the Draw a card page with modal

## Day 27 - 09/12/21
30+ min

-   **Project You Are Working On:** Tarot v2
-   **Progress Today:** set up the blueprints instead of having everything in the one routes file, and got the user authentication stuff all set up following the tutorial
-   **Tasks for Tomorrow:** finish tutorial video, set up config

## Day 28 - 09/13/21
60+ min

-   **Project You Are Working On:** Tarot v2
-   **Progress Today:** finished setting up config file and app factory (though admittedly I don't really understand what that means). Started on the view collection page. It's gonna take me a while to figure this out, I think. To figure out how to make it work with the tabs how I want
-   **Tasks for Tomorrow:** Set up the view collection page

## Day 29 - 09/14/21
60+ min

-   **Project You Are Working On:** Tarot v2
-   **Progress Today:** Got the View Collection page and the Collection Card pages set up. Got started on the regular card page as well
-   **Tasks for Tomorrow:** Fix the carousel and colors on the card page.

## Day 30 - 09/15/21
60+ min

-   **Project You Are Working On:** Tarot v2
-   **Progress Today:** Fixed the navbar, got several more pages set up and the images sized better. Got the carousel right and rearranged some pages. Lots of little stuff
-   **Tasks for Tomorrow:** Get the readings/journal pages made

## Day 31 - 09/16/21
60+ min

-   **Project You Are Working On:** Tarot v2
-   **Progress Today:** Got it on heroku. Took me a min to figure out what was going wrong there but I finally got it working. Fixed some the buttons and removed the "forgot password" link because I'm not going to set that up, I don't think. At least not anytime soon. Added a bunch more stuff to the database, but still quite a ways from having that completed.
-   **Tasks for Tomorrow:**

## Day 32 - 09/17/21
60+ min

-   **Project You Are Working On:** Intro to Comp Sci on edx
-   **Progress Today:** Completed the first lecture
-   **Tasks for Tomorrow:** Lecture 2? Unless I start a new project

## Day 33 - 09/18/21
30+ min

-   **Project You Are Working On:** Intro to Comp Sci on edx
-   **Progress Today:** Got about halfway through the second lecture
-   **Tasks for Tomorrow:** Finish lecture 2

## Day 34 - 09/19/21
60+ min

-   **Project You Are Working On:** Intro to Comp Sci on edx
-   **Progress Today:** Finished the second lecture and practice problems
-   **Tasks for Tomorrow:** Unit quiz

## Day 35 - 09/20/21
30+ min

-   **Project You Are Working On:** Tabletop DM Screen thing
-   **Progress Today:** got the models for the db and the create new character page made
-   **Tasks for Tomorrow:** i've got some new ideas for a homeschool plan/tracker I want to try. I need to learn more about how to use dates in python

## Days 36 (09/21) and 37 (09/22) -
60+ min

-   **Project You Are Working On:** Tabletop game thing both days
-   **Progress Today:** I keep forgetting to update this after I'm done coding for the night. Anyway, I've gotten a lot done on this project. Added flask migrate to the project (which would have been insanely helpful on the tarot journal project, ope) and got the character creation like 80% complete.
-   **Tasks for Tomorrow:** create a view character page and finish up the character creation

## Day 38 - 09/23/21
60+ min

-   **Project You Are Working On:** Tabletop
-   **Progress Today:** Broke it then fixed it then broke it again. realized i set up a lot of the one to many models backwards. I think. or they need to be many to many... at any rate the database needs some work. But for now character creation works and the view character page is done.
-   **Tasks for Tomorrow:** Add starting inventory, and the combat stats section

## Day 39 - 09/24/21
30+ min

-   **Project You Are Working On:** tabletop
-   **Progress Today:** figured out the way I want to handle adding/updating inventory but I'm struggling with the db. I think I need to plan it out on paper the way I want it set up, so that i can stop having to use flask migrate. It keeps giving errors I don't understand
-   **Tasks for Tomorrow:** in the meantime I'll work on the layout of the game home page I think

## Day 40 - 09/25/21
60+ min

-   **Project You Are Working On:** Considering learning to use PyQt to make my tarot journal app into a desktop app
-   **Progress Today:** Watched some tutorials on pyqt and followed along to make a to-do app using designer
-   **Tasks for Tomorrow:** Sqlite tutorial

## Day 41 - 09/26/21
60+ min

-   **Project You Are Working On:** PyQt tutorials
-   **Progress Today:** Watched several tutorials, played around with the designer and did some reading. And came to the conclusion again that I don't want to do this, I think. Counting today because I made like the to do list and followed a couple other tutorials, but I've really got to stop with the tangents and focus on my current projects.
-   **Tasks for Tomorrow:** Back to the tabletop!

## Day 42 - 09/27/21
30+ min

-   **Project You Are Working On:** Tabletop thing
-   **Progress Today:** just pseudo code at work. planning how i'm going to have the dice rolls work. I think I've got an idea but I'm not sure that it can be done without javascript and I just don't really know anything about ajax and using javascript in the pages. I think I'm gonna come back to it.
-   **Tasks for Tomorrow:** plan what tables i'll need for the database

## Day 43 - 09/28/21
60+ min

-   **Project You Are Working On:** tabletop
-   **Progress Today:** working on redoing the database. I realize I had a lot of the one to many models set up right initially. I changed a lot of stuff around because I was confused about why I'd set it up that way.. I should have done some more digging, now I feel like I should start over
-   **Tasks for Tomorrow:** more database bs blahhh

## Day 44 - 09/29/21
60+ min

-   **Project You Are Working On:** tabletop
-   **Progress Today:** Fixed the database finally! I had to redo some of the routes and the pages I'd made but it's all running well now. Now I'm running into an issue making the popovers work. I'm certain it's a tiny simple fix about the popper.js thing not being added right but I just can't seem to get it right.
-   **Tasks for Tomorrow:** Try to deal with bootstrap

## Day 45 - 09/30/21
60+ min

-   **Project You Are Working On:** Tabletop
-   **Progress Today:** Got the bootstrap issue fixed! Don't ask me how, I spent the hour copying and pasting different potential solutions basically. I think my bootstrap javascript wasnt set up right, but I'm not really sure what finally fixed it. What matters is, it's fixed!
-   **Tasks for Tomorrow:** Figure out how to handle the starting inventory, update the create a character form.

## Days 46-49 - 10/01/21, 10/02/21, 10/03/21, and 10/04/21
60+ min each day

-   **Project You Are Working On:** Tabletop and a healthcare thing
-   **Progress Today:** I dont remember the specific breakdown but I've gotten the character creation very nearly complete, and I created a way to generate a settlement, and buildings within that settlement, and they'll be linked in the database sow you can revisit a city page and see the buildings that are within that city. I've got a plan to do the same for NPC's, I just haven't implemented it yet. Then these last two days I've been working on like a healthcare management system that I'm talking to my MIL about. It's honestly probably way outside the scope of my ability but I like having a real world application to be working on, and projects are how I've been learning so. On that I've got the base of the app set up, and I made the application factory/blueprints first this time so I don't have to copy/paste and edit a bunch of stuff later. Other than that I've just got some forms made up and am working on models for the db.
-   **Tasks for Tomorrow:** Finish the patient model and set up a page to view the information. Make sure to import bootstrap properly so I can use the collapse feature, I think I'll want a lot of that. For tabletop, if I work on that also/instead: figure out a way to do dungeon generation

## Day 50-51 - 10/05/21, and 10/06/21
60+ min each

-   **Project You Are Working On:** Tabletop and healthcare things
-   **Progress Today:** Go the collapse feature working on the tabletop, and a pt view page set up. I was focusing too much on things that weren't necessary though, and need to figure out an actual layout before I go back to working on that. On the tabletop, I got the database set up to add an NPC but I was having issues with flask migrate so I decided I'd copy/paste the models and routes files after reverting to an older version. And that worked perfectly.. but I hadn't committed the changes that got the generate building/settlement buttons working. So back to the drawing board with that, hopefully it won't take me too long to figure it out.
-   **Tasks for Tomorrow:** Add some sort of 'create game' option, so that I can go to a game home page from a regular home page. That way multiple games can be stored with one DM. Then fix the generators.

## Day 52 - 10/07/21
60+ min

-   **Project You Are Working On:** Tabletop
-   **Progress Today:** Redid the collapse things, made a "choose game" starting page so there's a way to differentiate between games, and added the locations dropdown to the navbar. Then added a bunch more stuff to the db so I can check if the generators work.
-   **Tasks for Tomorrow:** Finish creating generators and add models for Dungeon and OtherLocation

## Day 53 - 10/08/21
60+ min

-   **Project You Are Working On:** Tabletop
-   **Progress Today:** Made generators for settlement and building, just need to add the form to the page for npc
-   **Tasks for Tomorrow:** Finish npc generator and start on the dungeon and other location ones

## Day 54 - 10/09/21
30+ min

-   **Project You Are Working On:** Weekly Planner
-   **Progress Today:** I got a new idea for how to set up a weekly planner. Since I can't figure out how to make the calendar module work how I want it to, I'm making just a week view that can be filled in and cleared at the end of the week. I got the week view set up and a database made, but I think I had the wrong idea about pulling the tasks from the database. Maybe I should do a table for each day? That seems like overkill though. I dunno, I'll put more thought into it and come back to it
-   **Tasks for Tomorrow:** finish the npc generator

## Day 55 - 10/10/21
60+ min

-   **Project You Are Working On:** Weekly Planner
-   **Progress Today:** I had some new ideas at work so I didn't go back to the tabletop thing today. I used a for loop to create the 7 days and the 4 categories within each day. It's so much less code than typing out a div for each day. Also made the form work so tasks can be added to each category. Now I need to decide how I want the delete to work.
-   **Tasks for Tomorrow:** Delete, on the weekly planner. Or npc generator for the tabletop thing

## Day 56 - 10/11/21
30+ min

-   **Project You Are Working On:** Weekly planner
-   **Progress Today:** Got a clear day button added but now the form isnt working right, like the page doesnt refresh the way I want it to when I add an item
-   **Tasks for Tomorrow:** Fix the redirect/return of the weekview function

## Day 57 - 10/12/21
60+ min

-   **Project You Are Working On:** tabletop
-   **Progress Today:** got started on the npc generator, but I need to add the random selection of the details for them. The layout is set up right with the popovers though and the form works fine. *update* finished the NPC generation. it could look nicer but it all works!
-   **Tasks for Tomorrow:** Either a new game button or the dungeon generation

## Day 58 - 10/13/21
60+ min

-   **Project You Are Working On:** Tabletop
-   **Progress Today:** Got the newgame option but I can't get a current_game_id to work with the current_user. I'm not sure how else to keep track of the details for just one game.
-   **Tasks for Tomorrow:** Figure out a current_game setting

## Days 59 and 60 - 10/14/21 and 10/15/21
60+ min

-   **Project You Are Working On:** tabletop
-   **Progress Today:** Between yesterday and today I fixed the locations dropdown to only show on the game home page so it will only include locations for that particular game. I've got a lot of work to do as far as allowing for seperate users I think, but for right now it can be seperated by game and new games can be created. Also got the notes section added. The dungeon generator is daunting, I'm holding off on it for now, but I'm chipping away at my ideas little by little to figure out how I'm gonna set it up
-   **Tasks for Tomorrow:** Do more thinking on the dungeon generation. Maybe start formatting?

## Day 61 - 10/16/21
60+ min

-   **Project You Are Working On:** Tabletop
-   **Progress Today:** Made a bunch of the tables I'll need for dungeon generation.
-   **Tasks for Tomorrow:** Dungeon generation still

## Days 62 and 63 - 10/17/21 and 10/18/21
60+ min

-   **Project You Are Working On:** watching kivy tutorial. these have been cheat days, i've lost some motivation.
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Days 64 through 67 - 10/19/21 to 10/22/21
60+ min

-   **Project You Are Working On:** I've been working, I promise! Days 64 and 65 I was following a Kivy tutorial. I've gotten maybe a quarter of the way through it before deciding I wanted to buy the full python tutorial on Udemy, so that's what I've been working on for days 66 and 67.
-   **Tasks for Tomorrow:** complete the pizza objects project

## Day 68 through 73 - 10/23/21 to 10/28/21
30+ min

-   **Project You Are Working On:** Following along with a coding course on Udemy, and working on creating my Tarot Journal app with Kivy.
-   **Progress Today:** I'm like halfway through the course, but Ive been sidetracked with my new project. So far I've gotten a lot of the navigation down, and the ability to create and view journal entries.
-   **Tasks for Tomorrow:** I'm having a similar issue that I had with the dnd thing where the database is accepting the new info but not like, updating in the list thats shown. Try to figure that out, otherwise get started on the card sections I think. I've also got another flask homeschool organizer idea I'm thinking of getting started on

## Day 74 - 10/29/21
30+ min

-   **Project You Are Working On:** Homeschool Organizer and Kivy Tarotjournal.
-   **Progress Today:** I've given up on the database updating issue for now. It adds the journal entry, it just wont show up in the list until the app is closed and repoened and I can't figure out why. So I moved on to the cards section and got that mostly done. I'd like to add images but I know I'm going to struggle with formatting it. I also made a homeschool organizer thing, that keeps track of the different curriculum we're using and lists the lessons.
-   **Tasks for Tomorrow:** Add an 'add' option to the homeschool planner, so I can add new lessons from the site itself. 

## Day 75 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 76 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 77 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 78 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 79 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 80 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 81 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 82 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 83 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 84 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 85 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 86 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 87 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 88 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 89 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 90 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 91 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 92 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 93 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 94 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 95 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 96 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 97 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 98 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 99 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 100 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**
