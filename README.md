# Playola Design
================

This repository is for future designs of the playola iPhone app.

To contribute:
1. Mess around in master all you want...
2. When finished, copy any changes to the AI files in each folder.
3. If a screenflow has changed, take a new screenshot of the entire flow (cmd-shift-4), name it "screenshot.png", and save it in the appropriate folder.
4. Create a new branch for the changes...then immediately switch back to continue working on the next version.
```
git checkout -b 2.9
git checkout master
```
5. All supporting files (images/fonts/etc) should be saved into the AI file or should contain relative links to the Resources folder.


# Version 3.0 Checklist
-----------------------
1. Side Menu -- new link for station...
  a. enabled
  b. disabled with timer
2. Collections/AddSongs && Broadcast/AddSong (when empty)
  a. "request song" button points to
    -- SEARCH for songs (searches Spotify)
    -- CONFIRMATION screen... (says... got it!  Would you like us to add it to your station automatically when this song becomes available?)
3. Reset your station
  a. Settings/Reset
    -- Dialog box (This will reset all of the songs in your song generator)
4. Change DisplayName... change Station Link
    -- copy link to clipboard


# Version 3.3 Checklist
-----------------------
1. Song Search Page (from Broadcast Page)
    -- add a checkbox for (also add to rotation)
2. Song Search Page (collection)
    -- need a place to suggest songs based on the ones that have been searched...  maybe a left-to-right scrolling list?
3. Broadcast Page
    -- Blurring out the playlist if the station has not been blocked yet.  We need a message over it with the copy:
        "Double Tap to Edit Your Station.  Listening to your own station will be disabled."

        -- maybe a "Why?" button that pulls up a message with this copy:
             ("By Law, we can't let you listen to anything that you schedule yourself.  The law is there to protect musicians -- to make sure that our service doesn't cut into their music sales.")

    -- A "Now Listening: 5" display to show how many people are currently listening to your station.
      -- if you press on this display, it should bring up a screen that shows a list of the people listening to you.
      -- Tweet, Facebook, or copyLink about your station button?


4. Lets get all the AI assets moved into the repo somehow...  Whether that means embedding all images or moving them to the resources folder
      
5. Friends
   --- a tableViewCell to put at the end that has (also link facebook) or (also link google) if there are results but only one is logged in.

6. Some sort of notification that someone has started listening to your station while you're using the app.

7. AudioPlayer -- A tweet, facebook, or copyLink about this station button