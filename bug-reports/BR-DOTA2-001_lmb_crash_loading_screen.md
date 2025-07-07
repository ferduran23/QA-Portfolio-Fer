# Bug Report: Dota 2 Crashes After Tapping LMB 30+ Times During Loading Screen

**ID:** BR-DOTA2-001  
**Title:** [Launch | Crash] Dota 2 Build Crashes After Tapping LMB 30+ Times During Loading Screen  
**Severity:** Critical  
**Reproducibility:** 5/5  
**Platform:** PC  
**Build Version:** v.256.3  
**Input Device:** Mouse  
**Interaction:** LMB (Left Mouse Button)  
**Timing:** During loading screen

## Description

The build of Dota 2 crashes when the user taps the Left Mouse Button (LMB) rapidly—approximately 30 to 50 times—during the loading screen. This input seems to trigger instability in the loading process or causes the input queue to overflow, resulting in a full crash.

This issue is consistently reproducible and should be handled gracefully by the game during non-interactive loading phases.

## Steps to Reproduce

1. Launch Dota 2 using build version v.256.3  
2. Wait for the loading screen to appear  
3. Tap the Left Mouse Button (LMB) 30 or more times quickly during the loading screen  
4. Observe the application's behavior  

## Expected Result

The game ignores or safely handles LMB input during the loading screen without crashing.

## Actual Result

The game crashes after excessive LMB input during the loading screen.

## Attachments
- [ ] Screenshot: error_popup.jpg

## Notes

- No loading bar freeze or visual feedback occurs before the crash
