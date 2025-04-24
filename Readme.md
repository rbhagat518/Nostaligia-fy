Nostalgia-fy

App Overview

Nostalgia-fy is an iOS app that lets users rediscover memories by combining their Spotify listening history with photos taken on the same calendar day, regardless of year. Users pick a date from a calendar, see what tracks they played that day, and can tap a track to view a personalized montage of photos taken on the same date from previous years.

App Evaluation

Mobile:

Uses music streaming APIs and native photo library access

Emphasizes mobile-specific features: photo browsing, music, and date selection UI

Story:

Brings together personal music taste and memories

Offers a compelling way to relive moments linked to music

A clear value prop: nostalgia and discovery

Market:

Spotify users with photo libraries

Appeals to Gen Z and Millennials who associate music with memory

Fits a niche but emotionally resonant use case

Habit:

Encourages regular exploration by date

Each visit offers different song+photo pairings

Habit-forming for nostalgia and memory reflection

Scope:

MVP includes login with Spotify, calendar selection, track list, and photo montage per track

Technically scoped for completion in a few weeks with opportunity to expand

App Spec

Required Features



Optional Features



Screens

Login Screen

Spotify authentication

Calendar Screen

UIDatePicker

Button to "Fetch Tracks"

UITableView showing tracks with artist details

Montage Screen

UILabel showing "Photos from [Track]’s Day"

UICollectionView showing matched images

Navigation Flow

Flow Navigation

Login → Calendar Screen (on successful auth)

Calendar Screen

Tap "Fetch Tracks" → shows tracks for that date

Tap track → pushes to Montage Screen with photos for that track's played date

Wireframes

(Include images or upload scans in your repo under wireframes/ folder and reference them here)

![Calendar Screen Wireframe](wireframes/calendar_screen.png)
![Montage Screen Wireframe](wireframes/montage_screen.png)

Repo Checklist



