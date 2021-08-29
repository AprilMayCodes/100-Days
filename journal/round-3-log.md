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

## Day 14 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**

## Day 15 -
30+ min

-   **Project You Are Working On:**
-   **Progress Today:**
-   **Tasks for Tomorrow:**
