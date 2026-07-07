# Signal (2016) Chapters

This project aims to fix visual mistake or should I say "creative" descison taken by production team of the 2016 tvN Drama [Signal](https://mydramalist.com/13239-signal) 

## The Problem

The production team of the show used diffrent aspect ratio, 16:9 and 2.35:1 to distinguish between Present and Past timelines respectively.

The native container of image is in 16:9 aspect ratio but due to technical diffrences with broadcast networks or just "creative" direction, they couldn't or didn't put black bars below and top of image in Past scenes to make it perfectly 2.35:1.

Result: Past secenes appear streched vertically making characters and objects look thinner and lomger than original creating innacurate depection of actual scene.

## The Solution

According to me, I think it was a bad descion, even if I agree to the fact about issues with broadcasting networks at that time, I think a show released in 2016 should have gotten a proper official remaster with fixed aspect ratio for modern streaming.

So, I came up with my own solution i.e. This Project.

I will not force my opinions on anyone. This is just my opinion as I think that this directive "vision" is technically not appropiate as it does not retain the original visual geometry.

## Requirements

**MPV** : Use [mpv player](https://mpv.io) as this project uses lua script to be used with mpv or libmpv based players.

**Signal BDRip Release** :  These chapter files were made according to BDrip. manual tweaking may be required with WEB-DLs/other Rips. The files must be named in `(show_name) - S(season_no)E(episode_no) - (episode_name)` format For e.g. `Signal - S01E01 - You're Doomed.mkv`

## How to Use

* `git clone https://github.com/uzuto/signal-ratio`
* copy all BDrip .mkv files in `signal-ratio` folder.
* Copy `chapter-make-read.lua` & `signal-ratio.lua` to `~/.config/mpv/scripts` or to portable mpv directory.
* Feel free to delete the .git tracking files and rename the folder as you wish.
