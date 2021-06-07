# Project Testing
## Test Plan
Methodology:
 - There are 6 testers in total that are members from group 10
 - The purpose of the test is to mainly observing the behavior of the testers and see if there are any confusion during the process
 - Optionally we are also making sure all the core functions are functioning as expected

Script/task:
 - T1 – Using the sidebar, navigate throughout the app
 - T2 – Run through the tutorial
 - T3 – View your profile
 - T4 – Change your username and tags
 - T5 – Sign up for an event
 - T6 – Join a group
 - T7 – Check what events you’ve signed up for
 - T8 – Check which groups you’ve joined
 - T9 – Check your notifications
 - T10 – Check the messages in a group you’ve joined
 - T11 – Check how many seats are remaining in a group you’ve joined
 - T12 – Scan a poster
 - T13 – Change the colour scheme of the app

Roles: (need help here)
 - Jeremiah - Prototype main developer, testing navigator
 - Jack - Prototype main developer, testing navigator
 - Trung Nhan(trannhan) - Flexible protype developer, report writer
 - Lillian - Main report writer
 - Andrija - Prototype designer

Metrics: 

In terms of metrics, we primarily focused on the amount of time that the subject took to reach the goal. As well as whether or not they required help, how much confusion they showed while trying to complete the task, and what pages they (incorrectly) accessed while trying to find the correct page.

Usability Goals: 
 - The testers have no problems navigating the basic and core functions of the interface
 - The application seems familiar and approachable to testers
 - The testers view the aesthetic deisgn choices positively
 - Navigation between states make sense to the testers

Problem Severity:
 - All the problems that our group observed after the testing are mostly design flaws that bear very little consequences to the overall
 experiences of the design
 - When encountering said problems the users were only slightly confused and able to quickly overcome after given a short amount of time, or   given some help, mostly due to confusion regarding what interactions would be available on a given page.

## Results (This is the 7th part of the requirement, in this part I was unable to comprehend the second point of the requirement so that needs improvement/completion)
Generally, feedback was focused into a few areas:

-	The snack menu should always be accessible;  Users generally spent a larger than expected amount of time trying to access this menu, 
and expressed confusion as to the menu only being accesible when the side menu is open. Oftentimes attempting to scroll downward before realising that opening the burger menu was the correct input.

-	A distinction between the “Discover” page and the “My groups”/”My events” pages; Here users spent a much larger than expected amount trying to access this functionality. Users almost always opened either the "My Groups" or "My Events" page before opening the "Discover" page, and expressed confusion as to why these funcitons were seperated

-	The tutorial should be easier to access and should be automatically displayed on first use; When trying to access the tutorial, users spent marginally more time than expected, and generally tried to access the tutorial through the burger menu before realising it was accesible via the snack menu. Testers expressed confusion as to why this functionality was not part of the burger menu.

-	The burger menu button should be replaced by a back button when the user is on a sub page; When attempting to return to the previous page, users generally pressed on the burger menu button (left) rather than the back button (right) while this did not cause a large time difference when compared to the expected time, testers did express a large amount of confusion as to why the back button wasn't on the left, as would be standard in most mobile app designs.

## Changelog
[Changelog](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t1/argroup1p1/-/blob/master/prototype/UpdatedPrototype.md)

## Discussion
We recieved a good amount of feedback during the tests,
which we have narrowed down to two main points;

### 1/
The first is that many testers pointed out that they prefer the bottom
tools bar (Snack bar) to be accessible at all times, rather than just when the side bar is opened. 
One suggestion was for it to be hidden until scrolled all the way down the
screen, or simply having it at the bottom of the screen at all times.

While most of us(the developer side) agree on this insight most of the
testers also point out that this is mainly their personal opinion or preference
and there are also testers who had no problems with the current way but
still think it's a good idea if the tutorial button is more highligted. Especially given
that it is generally standard to have the snack bar accesible most (if not all) of the time,
so this change would bring our design more inline with standard design practices.

### 2/
The second, and the more crucial piece of feedback is the confusion of the
button "my groups/events" and "explore". The "explore" will take the user
to a screen where they can choose new events/groups to join and 
"my groups/events" are for added/joined events/groups. When asked to add a new
group or event, users would first go to "My Event/Groups" before navigating to 
the discover page, potentially due to these containing the word "Group" or "Event"
A solution that was discussed with the testers and received favorable feedback
is to include the "explore" button in the "my groups/events" respectively
and the user can choose between the adding and viewing joined group in
each perspective page. The design will be similar to the current "explore"
screen as they already have the options of switching between events and groups
in the same page.
