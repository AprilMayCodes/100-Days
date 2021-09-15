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

## Day 31 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 32 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 33 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 34 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 35 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 36 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 37 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 38 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 39 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 40 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 41 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 42 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 43 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 44 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 45 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**
