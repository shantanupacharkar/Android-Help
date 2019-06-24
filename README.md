## Tips & Tricks in Android Studio
#### Being an Android Developer, we use a number of IDE for writing the code for our Application. For example, Android Studio, Eclipse, etc. But the most famous and the recommended one among these IDE’s is the Android Studio. Nowadays, everyone uses Android Studio to write codes for their Application because Android Studio gives us a lot of functionalities and features, speeding up out code generation. Also, we get an organized way to manage our project in Android Studio. The IDE is equipped with many tools to help the developer in the process. So, let’s look upon some of the Tips and Tricks of Android Studio.

 - [Setting the Theme](#### 1. Setting the Theme)

#### 1. Setting the Theme
The theme of the IDE plays an important role in determining the time that we can spend on Android Studio to write code. So, a good and eye soothing theme must be there. To change the Theme and color of the Android Studio, go to **File > Settings > Appearance & Behavior > Appearance > Theme** and then choose the desired **Theme**. To change the color of the editor text, you can go to **File > Settings > Editor** and change the desired property. (Note: In MAC, instead of going to Settings, you can find the options in **Preferences**)

![Theme Settings](https://github.com/shantanupacharkar/Android-Help/blob/master/res/images/tips-tricks-android-studio-appearance.jpg)

#### 2. Changing Color of Logcat
Logcat is the best way to find any bug present in the application. On the Logcat, we can see each and every event going on with a particular Android Application. You can change the color of various options available in Logcat by going to **File > Settings > Editor > Color Scheme > Android Logcat** and change the **default color** by unchecking the “**Inherit values from**” option.

![Changing the color scheme of logcat](https://github.com/shantanupacharkar/Android-Help/blob/master/res/images/tips-tricks-android-studio-appearance-logcat.jpg)

#### 3. Fast Searching
Android Studio contains a number of features and it is impossible to remember the place from where a particular feature can be used or activated. So, in order to search these features in a very fast manner, you can use **Ctrl + Shift + A** (in Windows and Linux) or by using **Cmd + Shift + A** (in Mac).

![Fast Searching](https://github.com/shantanupacharkar/Android-Help/blob/master/res/images/tips-tricks-android-studio-search.png)

#### 4. Rename file/variable
There are many cases when you want to change the name of a file or a variable, but in order to do so you have to change the name at all places where these files or variables are used in the project. Don’t worry, Android Studio provides a better way of doing this. All you need to do is select a file and then **right click** on it and then click on **Refractor > Rename** or simply **Shift + F6** and then enter the new name Refract the changes. This will change the file name throughout the project.

![File Rename](https://github.com/shantanupacharkar/Android-Help/blob/master/res/images/tips-tricks-android-studio-refractor-rename.png)

#### 5. Split Screen
Split Screen is a new feature that is provided by almost every modern day’s IDE. By using Split Screen, you can use two screens at a time i.e. the same window will be split into two part, either vertically or horizontally. In order to split the window, right click on the tab of the file that you want to split and then choose **Split Vertically/Horizontally**.

![Split Screen](https://github.com/shantanupacharkar/Android-Help/blob/master/res/images/tips-tricks-android-studio-split-screen.jpg)

#### 6. Distraction Free Mode
You can use the Distraction Free Mode of Android Studio to remove the editor tabs and tool-windows buttons. By doing so, your focus will be on the coding part and nothing else. To enable the *Distraction Free Mode*, go to **View > Enter Distraction Free Mode**.

![Distraction Free Mode](https://github.com/shantanupacharkar/Android-Help/blob/master/res/images/tips-tricks-android-studio-distraction-free-mode.jpg

#### 7. Code Completion
You can use the Postfix Code Completion to write the code in a faster way. All you need to do is press **Ctrl + J** or **Cmd + J**(in MAC) and Android Studio will give you a number of possible codes. For example, if you want to write the code for a Toast, then just write “**T**” and press **Ctrl + J**, you will be given a list of possible items. Select **Toast** and click **Enter**.

#### 8. Working Offline
If you want your Android Studio to run faster, then you can use the Offline mode of Android Studio. To start Offline mode, Open the **Preferences** window by clicking **File > Settings** (on Mac, **Android Studio > Preferences**) and in the left pane, click **Build, Execution, Deployment > Gradle**. After that check the Offline work check box and click **Apply** or **OK**.

![Working Offline](https://github.com/shantanupacharkar/Android-Help/blob/master/res/images/tips-tricks-android-studio-offline-mode.png)

#### 9. Line Number and Method Separator
You can put line numbers to your code and method separator also. This will make your code more readable. All you need to do is Click on **File > Settings > Editor > General > Appearance > Select Line Number/Select Method Separators**.

![Line Number & Method Seperator](https://github.com/shantanupacharkar/Android-Help/blob/master/res/images/tips-tricks-android-studio-line-number-function-separator.png)

#### 10. Multicursor Feature
You can edit to more than one lines at a particular instant of time. For doing so, go to a particular word and click **Alt + J** (Windows and Linux) or **Ctrl + G** (for Mac). This will select the next appearance of that word in the file. Now you have to write only once.

![Multicursor](https://github.com/shantanupacharkar/Android-Help/blob/master/res/images/tips-tricks-android-studio-multicursor.png)

#### 11. Last Copy & Paste
You can choose from your last 5 Copy/Paste operations by clicking **Ctrl + Shift + V** (in Windows or Linux) or **Cmd + Shift + V** (in Mac).

![Last Copy Paste](https://github.com/shantanupacharkar/Android-Help/blob/master/res/images/tips-tricks-android-studio-last-copy-paste.jpg)

#### 12. Open Class: 
In order to open a class in Android Studio, press **Ctrl + N** (in Windows and Linux) or **Cmd + O** (in Mac).

![Find Class](https://github.com/shantanupacharkar/Android-Help/blob/master/res/images/tips-tricks-android-studio-find-class.png)

#### 13. Open File: 
To open file press **Ctrl + Shift + N** (in Windows and Linux) or **Cmd + Shift + O** (in Mac).

![Find Files](https://github.com/shantanupacharkar/Android-Help/blob/master/res/images/tips-tricks-android-studio-find-files.png)

#### 14. Find Declaration: 
You can find the declaration of any class and its method by clicking on that class and pressing **Ctrl + B** (in windows and Linux) or **Cmd + B** (in Mac).

#### 15. Move between tabs: 
You can move between tabs by pressing **Alt + left/right** arrow (in Windows and Linux) or **Cmd + Shift + [ (left) and Cmd + Shift + ] (right)** in Mac.

#### 16. Last tab: 
You can switch between last tabs by using **Ctrl + Tab** (in windows and Linux) and **Cmd + Tab** (in Mac).

#### 17. Format your code: 
You can format your code by using **Ctrl + Alt + L** (in windows and Linux) or **Cmd + Option + L** (in Mac). Formatting means rearranging the declaration of attributes. For example, “**id**” of a TextView should be written before the width and height property. This makes the code more readable.

#### 18. Auto-indent line: 
You can apply indentation by using **Ctrl + Alt + I** (in Windows and Linux) or **Control + Option + I** (in Mac).

#### 19. Find:
You can find something in a file by using **Ctrl + F** (in Windows and Linux) or **Cmd + F** (in Mac).

![Find](https://github.com/shantanupacharkar/Android-Help/blob/master/res/images/tips-tricks-android-studio-find.png)

#### 20. Find and Replace: 
You can use find and replace feature by pressing **Ctrl + R** (in Windows and Linux) or **Cmd + R** (in Mac).

![Find & Replace](https://github.com/shantanupacharkar/Android-Help/blob/master/res/images/tips-tricks-android-studio-find-replace.png)

#### 21. Hardcoded String to resources: 
You can move your hardcoded string to string.xml file or any other resources file by just clicking on the string and pressing **Alt + Enter** (in Windows and Linux) or **Option + Return** (in Mac) and then Extract String Resource.

![Hard Coding Strings](https://github.com/shantanupacharkar/Android-Help/blob/master/res/images/tips-tricks-android-studio-hardcodedstring-resources.png)

#### 22. Build and Run:
To build and run your app, press **Shift + F10** (in Windows and Linux) or **Control + R** (in Mac).

#### 23. Last edited location: 
You can directly move on to the last edited location in a particular file by pressing **Ctrl + Shift + Backspace** (in Windows and Linux) or **Cmd + Shift + Backspace** (in Mac).

#### 24. Close active editor tab:
You can close the active editor tab by pressing **Ctrl + F4** (in Windows and Linux) or **Cmd + W** (in Mac).

#### 25. Using Plugins: 
You can use a number of plugins available in Android studio to improve the functionality of Android Studio. Some of these may be:
 - ADB Idea: It helps to execute adb commands to uninstall, kill, start, restart or clear an application.
 - Android Material Design Icon Generator: This plugin will help you to generate Material Design Icons for your project.
 - Git flow integration: This helps you to have a defined flow of version control of your project.
 - Genymotion plugin: It is used to provide a smooth flow for Genymotion virtual devices.
 - Key Promoter: It is used to make your own shortcut keys for a particular task.
 
###### If you want to know more about your project in Android Studio then go to Help > Productivity Guide (Bonus tip :))
