CHANGES:

Added mutable-struct and pre-processor check for which dataset I want to use
Added status bars for both generator and railgun charge
Added timedely to satchel charge deployment - more closely matches one of the specified modes for satchels
Added railgun shooting 
Fixed the capsense not moving platform correctly (Bad job of copy-pasting code)



PROJECT COMPLETION: (12) + 7.65 hrs / 36.75 = 53.4% finished.

ANALYSIS OF TIME ESTIMATES VS LOGS
Satchel based on position: Estimated time - .5 hrs | Real time - 1.5 hrs | 3x Environment variable tweeking : Estimated time - 2hrs | Real time- .5 hrs | .25x Platform based on position: Estimated time - 3 hrs | Real time - 1 hr (Nearly complete) | .33x Weekly upkeep: Estimated time - .70 hrs | Real time - .5 | 0.7x


Environment Variables: Estimated time - 1 hr | Real time - 1hr | 1.0x
Status bars: Estimated time - 1.5 hrs | Real time - 2 hr | 0.75x
Railgun Shooting: Estimated time - 4.0 hrs | Real time - 2.5 hrs | 1.6x (Not entirely done so looking on time)

STATUS: I spent a really long time debugging a stupid mutex not being pended which sucked a couple hours this week. But luckily the status bar and railgun shooting implementations didn't take super long and worked well quickly. I need to focus a little more time on this project which I plan to do with weekend by implementing the state machine and polishing. I am feeling good about finishing on time and my initial time estimate is looking either on-target or slightly over.