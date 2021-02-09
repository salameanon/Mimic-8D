# Mimic-8D

## A VERY simple applescript/automator application that adjusts left and right audio balance to provide a real time, system audio "8D" experience.

---

![image](https://user-images.githubusercontent.com/5051300/85926574-ebfb9d80-b8d2-11ea-836b-28e38d1f3447.png)

---

# TUTORIAL:

---

### 1. Download and install the latest release of Mimic8D from here: https://github.com/salameanon/Mimic-8D/releases

###### Make sure you either Control+Click (Right click) the package and press "Open" to bypass the unknown developer message. Alternatively, you can open Settings, go to Security and Privacy, and press "Open Anyway." Do **NOT** move Mimic8D to the trash.

### 2. Run any mode from Mimic8D and when it prompts you, allow it accessibility access. (Only for first time users)

### 3. Run Mimic8D and choose from one of the options - simple as that!

---

# MODES:

------------------------------------------------------------------

#### Custom Image 📁 
##### Allows you to choose a custom image to be resized and fitted to BigSur's app shape, and then applied to your app of choice.

------------------------------------------------------------------

#### iOS AppStore Icon Downloader 🛍
##### Allows you to search the iOS AppStore for an icon matching your app choice's name. If no (relevant) results are found, your app will be resized with a white boarder surrounding it.
###### For example, if I choose "Zoom" as my app choice, IconSur will look through the iOS's AppStore for an app called "Zoom" and then apply its icon to the "Zoom" app on my Mac.

------------------------------------------------------------------

#### Resize Current App Icon 🤏
##### Takes the chosen app and resizes it with a white border to fit BigSur's icon shape. 
###### Custom colors probably coming soon unless I forget about this project...

------------------------------------------------------------------

#### Modify a System App Copy 📝
##### Since you can't modify System Apps due to the root volume being Read-Only, this feature allows you to make a copy of the System app and modify the icon.
###### For example, if you choose "AppStore" and try to change it's icon, this option will make a COPY of it and modify its icon since you can't modify system icons. From there you can proceed to drag that icon to your dock, launchpad, etc. This is also useful if you don't have administrator permissions on your user account and want to have custom icons.

------------------------------------------------------------------

#### Extract App Icon 🔍
##### (NOT MADE BY ME) Asks the user (you) to select an app, them extracts any icon files (.icns) and copies them into a folder created on the Desktop.
###### If there are multiple .icns files, you will be prompted to choose which ones you want to extract. Additionally you can convert the .icns file to the .png format.

------------------------------------------------------------------

#### Refresh Icon Cache 🌀
##### Reloads Dock & Finder to forcefully update new app icons
###### This happens automatically after every modification to an app icon made using IconSurGUI

------------------------------------------------------------------

#### Reset App Icon 🔙
##### Removes any custom icon the selected app has and replaces it with the .icns file inside of it's resources folder

------------------------------------------------------------------

#### Help ❓
##### Brings you to this README.md file
###### A possible built in FAQ section might come in a future version...

------------------------------------------------------------------

#### Download BigSur Icons ⬇️
##### Redirects to a HUGE collection of community made BigSur icons at https://macosicons.com/
###### THIS ISN'T MADE BY ME!!

------------------------------------------------------------------

#### Delete IconSur 🚫
##### A built in option to remove IconSurGUI
###### This won't affect any custom icons on your apps.

------------------------------------------------------------------

#### Submit Feedback 📩
##### Directs you to issue report templates where you can submit feedback, report a bug, request a feature, etc.
###### You need a GitHub account to access these templates and submit feedback.

------------------------------------------------------------------

# FAQ:

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

Q) Why does it sometimes randomly stop?

A) This has happened to me before, only when running the script from Automator directly. I had to constantly click the application icon to get it to resume. 
###### Don't run Mimic8D directly from Automator...

------------------------------------------------------------------
