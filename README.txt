Feedback Delay Source Code

Authors: Chad McKell + Roli, Ltd.
Date: 29 Dec 2017

Description: JUCE source code for a feedback digital delay VST plugin. The delay algorithm is located on line 192 in the file "PluginProcessor.cpp". Below are instructions for compiling the source code and running the VST plugin.


1. Open Projucer v5.2.0 or later (see juce.com/projucer).

2. Create a new audio plug-in project.

3. Name the project “FeedbackDelay”.

4. Open your project settings (click on the gear icon located near the top of the window).

5. Make sure the following are enabled: Build AudioUnit v3, Plugin Midi Input, Plugin Midi Output, and Key Focus.

6. Save and open the file in your selected exporter.

7. Using your computer’s file manager, navigate to your JUCE project folder. Remove all the files located in the “Source” folder. Now add the files from this GitHub repository.

8. Compile the new source code using the exporter.

9. Find and run the VST plugin in your chosen DAW. 
