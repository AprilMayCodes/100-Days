<h1 align="center"> #100DaysofCode Round 5</h1>

**Start date**: 10/18/2022
**End date**: TBD


## Day 1: Tuesday, October 18, 2022
-   **Project You Are Working On** Homeschool Manager
-   **Today's Progress** Created the basic flask structure and got the database up and running. Created user registration and login (just with a username, I'm not worried about using passwords for this since it's just for the kids). I think I've got the database structure how I want it, but we'll see.
-   **Thoughts:** I'm concerned about how to track their progress. I created a Lesson table separate from the 'Topic' table, that will hold each of the lessons with a link to the user, and each one will track how many stars they've gotten for that lesson. I think that will be good enough, but I wonder if there's not a more succinct way to do it.
-   **Tasks For Tomorrow (or today after work)** A few things I could work on.
        - Style the login and register pages. Not high on my priorities, but I want to keep my code organized and I think styling as I go will save me the headache of figuring out what's what later on
        - Create a way to add lessons from the app
        - Add some example lessons so I can start playing around with the quiz functionality and seeing if my database setup is going to work.
-   **Link to tweet** [Round 5 Day 1](https://twitter.com/AprilMayCodes/status/1582380851345911810)

## Day 2: Wednesday, October 19, 2022
-   **Project You Are Working On** Homeschool Manager
-   **Today's Progress** I made it pretty! Well, pretty ish. It looks good enough lol. I also created a quiz route and have started on the logic to select just the current lesson, but I'm kind of stumped. I think there's a better way to set up the database but I'm not really sure what that is yet.
-   **Tasks For Tomorrow** Work more on the quiz route
-   **Link to tweet** [Round 5 Day 2](https://twitter.com/AprilMayCodes/status/1582896836506894337)

## Day 3: Thursday, October 20, 2022
-   **Project You Are Working On** Homeschool Manager
-   **Today's Progress** Nada. Spent most of the hour arguing with the database. I thought adding to the user a current_lesson_id column linking it to the lessons table would work, but I couldn't get flask migrate to actually update the database.
-   **Tasks For Tomorrow** Start a new project, I think.
-   **Link to tweet** [Round 5 Day 3](https://twitter.com/AprilMayCodes/status/1583613048828223489)
