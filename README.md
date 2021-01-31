# Mimic-8D:
## A VERY simple applescript/automator application that adjusts left and right audio balance to provide a real time, system audio "8D" experience.
###### StopMimic is an additional script that provides an easy way to stop and revert the Mimic8D audio effects.

FAQ:

------------------------------------------------------------------

Q) Why do I need to give Mimic8D Accessability Permissions?

A) Mimic8D works by changing the left and right balance of you speakers (or headphones) in system preferences for you. In other words, it drags the slider back and forth for you which requires permissions to control your computer.

------------------------------------------------------------------

Q) Why do I need to keep the system preferences window open when I use Mimic8D?

A) Since the slider for balancing lives in system preferences, closing the window, or even switching to fullscreen in an app, essentially hides the app from view. All you have to do is keep the sound pane of system preferences open in the background.

------------------------------------------------------------------

Q) It doesn't let me open the installer because it's from an unkown developer. What does that mean and what should I do?

A) If you try to open an app that isn't registered with Apple by an identified developer, you get a warning dialog, and your mac won't let you open the app. While it's true I could have put malicious code into these apps, you can look at the code yourself before running Mimic8D, or StopMimic by opening them in automator.
###### To bypass this, either control+click (right click) either app and select "open" from the popout menu. Another way is to open system preferences, go to "Security and Privacy" and press "Open anyway."

------------------------------------------------------------------

Q) How do I get rid of the System Preferences prompt that appears every time I launch Mimic8D?

A) To do this, you will need to open Mimic8D in Automator. (Automator>Open Existing Document>Mimic8D) Once you have Mimic 8D opened, delete all code starting from **"## Delete from here until it says "STOP HERE" to get rid of the prompt about system preferences."** up until **"## STOP HERE ## STOP HERE ##"**

------------------------------------------------------------------

# Modes:

Upon opening Mimic8D, there will be different options that you can choose from. 

---MORE COMING SOON???---
