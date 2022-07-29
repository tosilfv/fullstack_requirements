# Full Stack
Full Stack Workout Helper requirements.

## Full Stack 2021 Project Requirements
See Requirements folder.
I took use cases from the Guitar App Feedback page at JustinGuitar.com. By
registering to the site
https://www.justinguitar.com/users/sign_in
I was able to see the feedback for the App from other registered users starting from year 2019.
I combined everything to the Requirements folder, including my own requirements that I could
think of. I have since updated most of the requirements as I progressed with the programming.

## Project inspiration sources
Before I started the project, I knew an App for guitar play practicing from JustinGuitar.com.
Here's a Youtube link to a demonstration video of the App:
https://www.youtube.com/watch?v=IE5HWnrP9Wk&list=PLlwfspJqZ126JHOY5rTkKCSAp2Ua907-v&index=19
Personally I think that App is not well made. I tried to use it, but I found it to be too
cumbersome and rigid. It has got too many features, like the 'Create a Routine', then 'Make a
Practice Item', then add the 'Practice Item into a Routine', fill out all fields along the way,
set up the routines, make the routine active or inactive and so on. I don't see why I need to
do all that if I just wanted to make a plan for guitar practice and save my progress. The Guitar
App also has a so called 'Stats' view, where you're supposed to see your progress. Once a stat
is saved, it never stops saving the same stat over again. So if I save that I've done 40 chord
changes today, the Stats will show that I'll do the same amount every day from now on, which is
not likely to happen. The Guitar App feels like it's made without care. To my surprise, most
of the feedback for the App was very positive and I think it's because Justin Sandercoe is such
a nice guy that nobody wants to make him feel bad. At the end of the day, he might have the
illusion that the App is great and people really like it. But to that point I give the benefit
of doubt that if no one likes the Guitar App at first, they might grow to like it just as they
might grow to like to play the guitar, which is inherently difficult.
Anyway, I just wanted to make an App that was simpler, felt lighter and was possibly easier to
maintain, update and expand etc.
I hope I'm more successful.
Inspiration was also given by the Athlean-X App:
https://athleanonline.com/
that only paid users can see. I could not find a demonstration video from youtube, but here's
a link to the program that I've purchased:
https://athleanx.com/the-training/ax1
So I also wanted to make something of a workout App that I would want to use myself. I think
if I wanted to see workout videos easily, I could go to Youtube, so I don't need to make an
App for that. But I wanted to save my workout progress into an App instead of an Excel file.
So towards these goals I set my target for the school project.

## Instructions for the App
The App has an internal Help section for registered users at the Help Tab.
Tooltips will open with mouse hover after 1 000 [ms] when applicable.
Read the Terms of Service from the bottom of any page by clicking the Terms of Service
button.
- You can register a user account for the App at the root address from the Register
Tab.
- Login to the App from the Login Tab at the App's root address.
- When logged in, you are redirected to the App's Dashboard, which consists of six Tabs
that are called Workout, Timers, Statistics, Planner, Profile and Help.
- Click on the Tab to select each section.
- The idea of the App is to save and follow the progression of a workout e.g. push ups 
by creating a workout and exploring its statistics. One workout has one parameter
that you can save in the Workout Tab and then see its history in the Statistics Tab.
You can use the Planner to make a workout routine that you wish to follow. Use the
Timers to help remember how long a workout took or to see how much time you have left
to complete a workout. Use the metronome to rhythm your workouts. You can of course
use the Workout Helper for other activities like guitar practice as well. Read more
about ideas for workouts from the App's internal Help section.

## Known issues
Issue 1: When a backend operation is performing/performed after user action and if user
then changes the active tab (Workout, Timers, Statistics, Planner, Profile, Help)
quickly in the same browser session, the program will produce a console error stating
that React cannot perform a state update and that there is a memory leak in the program.
Issue 2: Occasionally after the Advance is set, time shows one hundreth of a second of time
too much or too little.
Issue 3: Occasionally the bop audio is played with a short delay.
Issue 4: Occasionally the bop audio is played more than once in a row.
Issue 5: Occasionally the bop audio is not played even if the label says ON and vice versa.
Issue 6: Occasionally when timer is running, the displayed time doesn't run for a short
moment and then continues as if nothing happened.
Issue 7: When Metronome is started, it begins to stutter on high bpm's if color is adjusted
on the fly.

## Diary
|Day [dd.mm.yyyy]    |Time [hours]    |Description                                      |
|--------------------|:--------------:|-------------------------------------------------|
|12.08.2021          |2               |Deciding project subject, creating requirements. |
|13.08.2021          |2               |Creating repositories, writing readme's etc.     |
|15.08.2021          |4               |Updating requirements. Experiments with frontend.|
|18.08.2021          |2               |Frontend, styling the dashboard.                 |
|19.08.2021          |4               |Styling the dashboard.                           |
|20.08.2021          |3               |Frontend refactoring and design planning.        |
|21.08.2021          |5               |Frontend refactoring and layout experiments.     |
|23.08.2021          |2               |Frontend layout experiments.                     |
|24.08.2021          |3               |Frontend layout changes.                         |
|25.08.2021          |2               |Frontend writing out Workout Tab Help.           |
|26.08.2021          |2               |Frontend Profile Tab layout and filling in Help. |
|27.08.2021          |4               |Frontend layout, Tabs and filling in Help.       |
|28.08.2021          |5               |Frontend styling.                                |
|29.08.2021          |4               |Frontend Timers Tab, tooltips.                   |
|30.08.2021          |3               |Frontend tooltips, login, register, terms.       |
|31.08.2021          |2               |Frontend refactoring.                            |
|05.09.2021          |7               |Frontend, backend, register, login, instructions.|
|07.09.2021          |2               |Frontend register, login, logout.                |
|08.09.2021          |3               |Frontend register, login, logout.                |
|09.09.2021          |2               |Frontend tabs.                                   |
|10.09.2021          |1               |Frontend spinners.                               |
|13.09.2021          |5               |Frontend Formik forms, register, login, logout.  |
|15.09.2021          |3               |Frontend Formik register form.                   |
|17.09.2021          |3               |Heroku deployment experiments.                   |
|18.09.2021          |2               |Heroku deployment experiments.                   |
|19.09.2021          |3               |Heroku redirect, refresh, tabs.                  |
|20.09.2021          |3               |Register form tab, redirect, errors, styling.    |
|25.09.2021          |5               |Register form tests backend, refactoring.        |
|26.09.2021          |3               |Register form tests backend, requirements.       |
|28.09.2021          |3               |Register form tests frontend.                    |
|29.09.2021          |2               |Register form tests frontend, backend.           |
|30.09.2021          |3               |Register form tests frontend, refactoring.       |
|01.10.2021          |3               |Register form tests frontend, requirements.      |
|03.10.2021          |2               |Login form, refactoring, tests.                  |
|04.10.2021          |2               |Login form tests.                                |
|05.10.2021          |3               |Logout form, refactoring, tests.                 |
|06.10.2021          |3               |Logout and profile delete, refactoring, tests.   |
|07.10.2021          |3               |Planner frontend, backend.                       |
|08.10.2021          |1               |Planner frontend, backend.                       |
|09.10.2021          |1               |Planner frontend, backend.                       |
|10.10.2021          |5               |Planner frontend, backend.                       |
|11.10.2021          |3               |Planner delete, Logout, Timeouts.                |
|12.10.2021          |4               |Planner, tests, refactoring.                     |
|13.10.2021          |2               |Profile delete, tests, refactoring.              |
|14.10.2021          |3               |Profile password change, tests.                  |
|15.10.2021          |4               |Profile tooltips, refactoring.                   |
|16.10.2021          |1               |Profile tooltips tests.                          |
|17.10.2021          |1               |Refactoring.                                     |
|18.10.2021          |5               |Workout forms, refactoring, README.              |
|19.10.2021          |3               |Workout, refactoring.                            |
|20.10.2021          |2               |Workout, tests, refactoring.                     |
|21.10.2021          |5               |Statistics, tests, refactoring.                  |
|22.10.2021          |3               |Timers stopwatch, countdown timer.               |
|23.10.2021          |2               |Timers stopwatch.                                |
|24.10.2021          |2               |Timers stopwatch, refactoring.                   |
|25.10.2021          |8               |Timers, refactoring.                             |
|26.10.2021          |5               |Timers metronome, backend delete, finalizing.    |
|Total               |175             |                                                 |