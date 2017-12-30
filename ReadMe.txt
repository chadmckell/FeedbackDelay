Feedback Delay Source Code

Authors: Chad McKell + Roli, Ltd.
Date: 29 Dec 2017

Description: Source code for a feed-forward digital delay VST plugin. My delay algorithm is located on line 192 in the file "PluginProcessor.cpp". Minor modifications were made to the parameter names. All other code is written and owned by Roli, Ltd. Below are instructions for compiling the source code and running the VST plugin.


1. Open Projucer v5.2.0 or later (see juce.com/projucer).

2. Create a new audio plug-in project.

3. Name the project “FeedbackDelay”.

4. Open the project settings.

5. Make sure the following are enabled: Build AudioUnit v3, Plugin Midi Input, Plugin Midi Output, and Key Focus.

6. Save and open the file in your selected exporter.

7. Compile the source code using the exporter.

8. Find and run the VST plugin in your chosen DAW. If you’re using Ableton Live 9, make sure to enable “Use VST Plug-in System Folders” under Preferences->File Folder.

