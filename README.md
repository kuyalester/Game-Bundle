# CS-University
CS-University is a collection of 3 game variants.<br><br>
  **1. Are you Smarter than Bill?**
  
   `A game variant of "Are you Smarter than a 5th Grader".`<br><br>
  **2. Windows vs. Linux**
  
  `A game variant of "Plants vs. Zombies".`<br><br>
  **3. OS Breaker**
  
  `A game variant of "Brick Breaker Game”.`

**Download Link:** https://drive.google.com/drive/folders/1oWBNCuSXAkN3bCP035oTvK6hmIUebG0n?usp=sharing

There are 2 folders in the drive 
If you don't have a JRE on your computer you need to download the Executable Game folder, otherwise, you can download the source code folder. 
<br><br>
# 1. Executable Game Folder instructions

## Running Executable Jar in Command Prompt:

  1. In your directory where the executable jar is located, type "cmd" in the address bar and press ENTER to open the command prompt directed to the folder.
  
  2. Then, type the following command in the cmd to run the jar file.
  
    java --module-path "GameBundleLib\lib" --add-modules javafx.controls,javafx.fxml,javafx.media,javafx.graphics,poi.ooxml,poi  -jar GameBundle.jar
  
  _Note: Game Bundle.jar is the file name of the jar file._

## Running the app using the stand alone exe file:

  1. Double click on the GameBundle.exe application.

<br><br>
# 2. Source Code Folder instructions

## Compiling/Execution of Source code in command prompt:

  1. Navigate to the Group5_SourceCode, type "cmd" in the address bar and press ENTER to open the command prompt directed to the folder.
  
  2. Then, type the following command in the cmd to compile the source code. 
  
    javac --module-path "GameBundleLib\lib" --add-modules javafx.controls,javafx.fxml,javafx.media,javafx.graphics,poi.ooxml,poi src/*.java -d classes
   
  3. Next, type the following command in the cmd to run the program.

    java --module-path "GameBundleLib\lib" --add-modules javafx.controls,javafx.fxml,javafx.media,javafx.graphics,poi.ooxml,poi  -cp classes GameBundle
