# Patterning-2-Public
A public repository for tracking bugs and making feature requests for Patterning 2.

Use the "Issues" tab above to track bugs and discuss feature requests for Patterning 2.  Please check to see if your bug/request already exists before posting a new one.   

The #bugs tag is for tracking bugs.  
If you want to help out, #help-wanted tag is for bugs where I might need help tracking it down.

The #feature-request tag is for feature requests.  Try to keep them realistic, concrete, and concise.  Please also understand that feature requests are not always (or even often) able to be implemented.  If adding a feature is going to make the app confusing or add unnecessary complexity, it probably doesn't fit within the design goals of the app.  So please keep that in mind if you are making feature requests.  That said, post away!

The "Projects" tab can be used to track bugs or features being prepared for the next update or release.

Looking for app support or questions?  Use the Olympia Noise Forum instead : http://forum.olympianoiseco.com

# CHANGELOG 
(Please verify bug fixes work!)

Patterning 2.0.2 (33)
• Fix initial pattern on loading a song.
• Additional safety checks. 

Patterning 2.0.2 (31)
• Fix issues with naming of exported audio files when a song has multiple drum kits.
• Fix names of tracks in Ableton Live Set exports.
• Fix MIDI export in Ableton Live Sets.

Patterning 2.0.2 (29)
• Fix issues with exporting audio & Ableton Live Sets when songs contain multiple drum kits. 
• Fix color of titles when exporting to Dropbox.

Patterning 2.0.1 (25)
• Initial Release Candidate.
• Fix some layout and font size issues on iPad Pro 12.9”.  
• Ability to generate default MIDI input for pads on RECORD page. 
• Removed default MIDI input mapping when creating new song.

Patterning 2.0.1 (23)
• Fix issue with importing of .onps files removing step automation data.
• Fix issue with exporting audio and .onps files when song name includes illegal characters.
• Fixed a couple issues that could cause crashes on loading/opening a song.
• Update background audio state when MIDI is assigned to trigger pads.
• Auto generate default MIDI input mapping for pads when creating a new song.  Port “Patterning 2”, Channel 1, Notes 60, 62, 64, 65, 67, 69, 71, 72.

Patterning 2.0.1 (21)
• Fix crash when downloading Cloud Kits created with Patterning 1.
• Fixed issue where patterns get incorrectly reset when stopping the timeline.  
• Added “Debug” mode in Settings app to send logs.
• Fixed MIDI Gate Length not showing up in Layers.  (For real!)
• Changed size of DRUM KITS popover in right bar.
• Fixed multiple issues with the timeline.  Please test!  Things like adding and removing patterns, deleting and inserting new patterns, toggling loops.  Especially making edits while the timeline is playing.
• Fix issue where Pattern view did not update after clearing a loop in the Record view.

Patterning 2.0.1 (19)
• Tweaks to launch sequence.  Please check on iPad Pro 12.9” & 10.5” for seamless transition from launch screen to animation.
• Fix regression with importing samples with Open In… Please test importing samples from other apps, Files, Dropbox, etc. 
• Fix issue with FX settings not properly loading before pressing play.
• Added “Recently Imported Samples” Folder sorted by most recent first.
• Added “Set Track Name” editing option (PATTERN->SAMPLE LIBRARY->EDIT).   
• Added “NEW FOLDER” button to Sample Library.
• No longer auto-create default sample folders on initial app launch.
• Fix size of long track names in RECORD view. 
• Fix bug which caused updates to loop settings to be ignored after a save.
• Tweaks to font size for menu bars.
• Fix size of long sample names on right bar.
• Fix rounding of “PATTERN” menu bar item when displaying the sample library.


Patterning 2.0.1 (17)
• New Launch sequence.  If you have an iPad Pro 12.9” or 10.5” please let me know if it looks okay.  I do not trust the iOS simulator animations.  There should be a seamless transition from the static “PATTERNING 2” text into the loading animation.
• “Classic” color scheme is now available, via the iOS System Settings app.  You must restart the app for changes to the color scheme be applied.  Let me know if anything looks funny.
• Added “Grid Spacing” setting for changing frequency of grid lines.  It’s available from a menu under “STEPS” on the loop settings page.  Default setting can be used to set a default setting for the entire song. 
• Fix initial volume setting on app launch causing distortion on first down beat.
• Fix issue with ratchet steps not copying filter type setting.
• Fix metronome for time signatures other than 4/4.  
• Fixed issue with MIDI settings not properly transferring between drum kits. 
• Fixes & improvements to text and layout on SONG view. 
• Fix knobs getting stuck after long press gesture.
• Fix Save As/Rename textfields on iOS 10.
• Save As/Rename textfields now “cancel” instead of “commit” when hiding the keyboard.
• Fixed issue with New/Duplicate Patterns not causing song name to marked as unsaved.
• Fixed issue with Pattern Buttons in Song/Record views not getting properly displayed after duplicating a pattern from the PATTERN screen.
• Fixed issues with Pattern Select views (on Song/Record pages) from not properly displaying MIDI Learn controls.
• Fixed layout of MIDI Learn buttons for transport controls in Pattern view. 




Patterning 2.0.1 (15)
• Make changes to MIDI Port selection to avoid potential crashes. 
• Fix crash / Add error reporting for failed audio imports.
• Fix swipe to delete in Sample Browser
• Fix pattern rotation being slightly off when using odd subdivisions.
• Fix double hit that could happen when changing step durations.
• Change Duplicate to Save As… (Song).  
• Change text field input for Save As… (Song)
• Change text field input for Save As… (Drum Kit)
• Change text field input for Rename Sample
• Change text field input for Rename Drum Kit
• Drum Kit “Artist” and “Link” are now only present on Cloud Kits.  Saving a Drum Kit will clear the artist and link fields. You can still set the Artist and Link when uploading a Cloud Kit.
• Using Save or Save As…. with a Cloud Kit will now remove the “favorite” button.
• I’m planning to replace all text fields in the app with this new text field, where appropriate.  Let me know if I missed any.  
• Changed “Cloud Kits” button to “Browse Drum Kits” (Drum Kit)
• Changed “Share” button to “Share Drum Kit” (Drum Kit)
• Fix crash if trying to record/play pads when a loop is rotated and waiting to begin.
• Fix song name dirty flag / italicization after recording.
• Added FX and MIDI drum kit loading options in Drum Kit Library.  FX toggles on/off loading of effect settings when loading a kit.  MIDI toggles on/off loading of MIDI settings when loading a kit.  
• Simplified how MIDI settings are stored with a Drum Kit : Instrument MIDI settings are stored with a drum kit, just like all other instrument parameters.  You can use the “APPLY CURRENT MIDI SETTING TO ALL DRUM KITS” button in the MIDI Configuration Menu to quickly copy your current MIDI settings across all Drum Kits in a song. The MIDI button in the LIBRARY toolbar enables / disables importing of MIDI settings when selecting a drum kit.  Disable the if you want to keep the current MIDI Settings while importing samples from a kit in the library. 
• Added MIDI button to enable/disable loading of MIDI settings when selecting Drum Kit.
• Added FX button to enable/disable loading of FX settings when selecting Drum Kit.  This replaces “LOAD SAMPLES & FX” button.
• Changed MIDI Configuration Menu to reflect new MIDI settings.
• Changed “Import” to “Import MIDI Learn Mappings” and moved into table view.
• Updated “Import MIDI Learn Mappings” to show number of mappings and filter out songs without any mappings.
• Removed “manually manage MIDI track settings” parameter. 
• Hide FF / RW / New Pattern buttons when sample view pops out.
• Update record pads to reflect Mute/Solo state.

Patterning 2.0.1 (13)
• Fix crash on app launch when entering Tutorial.

Patterning 2.0.1 (11)
• App freeze on relaunch — continuing to investigate this but made some additional changes that I think may get it.  Let me know if happens to you (or if it was happening and is no longer!).
• Fix crash when exporting .onps files
• Fix MIDI Outputs not being properly muted.
• Fix available layers in “BOTH” MIDI/Audio mode.
• Fix Pen echo / erase mode bug when changing to a different pattern.
• Fix MIDI Learn UI issues in pattern select views.
• Add MIDI learn for “add pattern” and “duplicate pattern.”  Please note that “Add Pattern” and “Next Pattern” are two different MIDI learn assignments despite the buttons appearing in the same space in the Pattern View at different times.  (Please test!)
• Fix Record Pads / MIDI Input pass through to MIDI instruments. 
• Fix issue which cause Record Pads to get weird after MIDI learn mode.
• Fix issue with MIDI learn breaking after changing drum kits. 
• Remove Files as audio import option on iOS10.
• Fix crash on “Apply to All” when other loops in a pattern have a smaller step count than the current loop.

Patterning 2.0.1 (7)

• App freeze on relaunch — I think this is fixed.  Please let me know if you encounter it again. 
• Fix “delete patterns” crash.  Please stress test this!
• Fix crash when trying to access randomize/quantize menus on iPad Pro 
• Fix MIDI CC layers not sending data.
• Change new song name to “Untitled,” “Untitled 2,” etc.
• Fix DUPLICATE song name in OPEN dialog.
• Removed 32-bit device support. 
• Latest Link SDK
• Fix Tempo View background color.
• Fix Ratchet Decay layer eraser default value.
• Fix Ratchet Count layer eraser not updating actual value.
• Update eraser color when selected.
• Fix importing of v1 songs into v2.  (Please stress test!)
• Tested importing of version 1 database into version 2.  
• Fix MIDI Learn UI issues.
• Update to MIDI learn loading on new song.  Please test that MIDI learn parameters are working correctly after loading a song.
• Fix MIDI input crash on Mixer view.

Patterning 2.0.1 (6)

• initialRotationSteps bug fixed
• Eraser Tool Crash
• Fix Ratchet Count / Ratchet Decay layer not showing on audio tracks
• Autosave automatically every 60 seconds. 
• Fix record velocities not matching sequenced velocities.  
• Fix velocity to amplitude math.  
• Adjustments to Ratcheting velocities.
