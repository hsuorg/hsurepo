---
title: Navigating Main Screen
---
The main screen of Rezonator is our visual representation of the text imported delineated into tokens and units. 

![image45](https://user-images.githubusercontent.com/34769184/132994278-f4c43f7d-36f2-4c4b-a626-cf16ab463f9e.png)

The main screen consists of four major sections:
  * The Workspace where the document is displayed and edited
  * The Tool Pane is the vertical section on the right
  * The Navigation Window is above both of those
  * Finally the Menu Bar is at the top of the screen


## 2.1 Workspace 

The Workspace is a malleable area where the user can view token and unit level fields. This Is also the actionable space where most data annotation will occur. The workspace can be scrolled using the scroll bar or by using other quick navigation hotkeys linked to the arrow keys. The workspace can be used to show different sections of the document based on what the user is trying to filter on.

## 2.2 Tool Pane

The Tool pane consist of 7 sections
1.**Tools**:
   + **Resonance**: The Resonance tool is used to add words to a chain that will try to align to the furthest display column.
   + **Track**: The Track tool is used to add words to a chain that will not try to align.
   + **Tag**: The Tag Tool allows the user to add tags to existing fields where applicable
2. **Filter**:
 + Displays whether a filter is actively being viewed and can be used to toggle it on and off.
3. **Context**:
 + **Context Above**: While in a filter, enabling this option shows all units prior to the first unit gathered in the filter.
 + **Context Between**: While in a filter, enabling this option shows all units between the first and last unit gathered in the filter.
 + **Context Below**: While in a filter, enabling this option shows all units after the last unit gathered in the filter.
4. **Justify**:
 + **Left Prose**: This option spaces out by word length and is left justified.
 + **Left Grid**: This option spaces out by set grid distances and is left justified.
 + **Right Prose**: This option spaces out by word length and is right justified.
 + **Right Grid**: This option spaces out by set grid distances and is right justified.
5. **One to Many**:
 + **One to One**: Enabling this option switches the navigation window to One to one mode.
 + **One to Many**: Enabling this option switches the navigation window to One to many mode.
6. **Audio**:
 + The Audio button here toggles the audio pane where playback can be managed.
7. Help:
 + Help, opens the portal to our help resources

## 2.3	Navigation Window 

## 2.4	Menu Bar 

1. File Dropdown:
 * The **Save** option will save the current **Rez File**, and all of the changes that have been since last saving or opening. This option will overwrite the Rez File’s current location.
 * The **Save As** option functions identically to the **Save** button, except that the Save As button does not overwrite the current Rez File. This option will have the user choose a file location and a file name.
 * The **Media** option will have the user choose **Audio File** (.OGG) to open up with the current Rezonator session.
 * The **Export** option will export the current Rez File as a collection of CSV files. The user will be prompted to provide a file location and file name.
 * The **Import**
2. Edit Dropdown:
 + The **Delete All** option will open another dropdown:
  - **Trail Chains** allows the user to delete all Trail Chains in the Rez file.
  - **Rez Chains** allows the user to delete all Rez Chains in the Rez file.
  - **Stacks** allows the user to delete all Stacks in the Rez file.
  - **Chains** allows the user to delete all Chains in the Rez file.
+ The **Go To Line** option opens a text input box. The user can input a line number and their **Main Screen** will scroll to that location.
+ **The Go To Time** option opens a text input box. The user can input a number of seconds and their **Main Screen** will scroll to the line closest in Time Stamp.
3. View Dropdown:
 * The **Window** option will open another dropdown:
 > AJSHDKSAHKDAJS 
The Nav option will open another dropdown:
Left will open/close the List Window
Right will open/close the Contents Window
Nav will open/close the List Window and the Contents Window
Tools will open/close the Tools Pane
All will open/close the List and Contents window, and the Tools Pane.
Search will send the user to the Search Screen (if a Search has been done in the Rezonator session).
Grid will send the user to the Grid Screen.
The Justify option will open another dropdown:
Left will justify the Tokens to the left side of the screen.
Right will justify the Tokens to the right side of the screen.
Center[i] will justify the Tokens to the center of the screen.
The Prose option will open another dropdown:
Prose will set the Tokens in a prose structure.
Grid will set the Tokens in a grid structure.
The Hide option will open another dropdown:
Trail will toggle the visibility of all Trail chains in the Rez file.
Rez will toggle the visibility of all Rez chains in the Rez file.
Stack[j][k] will toggle the visibility of all Stack in the Rez file.
Place will toggle the visibility of all Place Chains in the Rez file.
[l]
Filter Dropdown:        
The Filter option will toggle on/off the Filter Screen (if any chains are Picked to be in the filter)
The Pick option will open another dropdown:
Rez will Pick all Rez chains to be in the Filter
Trail will Pick all Trail chains to be in the Filter
Stack will Pick all Stacks to be in the Filter
The Context option will open another dropdown:
Above will toggle the display of the Lines before the Picked Lines in the Filter Screen.
Between will toggle the display of the Lines in between the Picked Lines in the Filter Screen.
Below will toggle the display of the Lines after the Picked Lines in the Filter Screen.
The Clear option will unpick all Picked Chains, clearing the Filter Screen, and sending the user b2        ack to the Main Screen if the Filter Screen was open
Tools Dropdown:
The Search option will open another dropdown:
Keyword [m]will open a dialog box for Rezonator’s Search by Keyword function
Clear will turn off the highlighting for the Actively Searched Keywords that occurs on the Main Screen, if (if a Search has been done in the Rezonator session).
The Trail option will set the current Mode to Trail Mode,  and set the current List Tab to the Trail Tab.
The Rez option will set the current Mode to Rez Mode,  and set the current List Tab to the Rez Tab.
The Stack option will set the current List Tab to the Stack Tab (And if the current Mode is Unit Mode, it will set the current Mode to Trail Mode).
[n]
Settings Dropdown:
The User option allows the user to set a Username for the current chain creator.
The Zoom option will open another dropdown: (Note: Column Width is only used when the Tokens are in the Grid Structure.)
Zoom-in will increase the Font Size, Line Height, and Column Width.
Zoom-out will decrease the Font Size, Line Height, and Column Width.
Wide will increase Column Width.
Narrow will decrease Column Width.
Tall will increase the Line Height.
Short will decrease the Line Height.
The Zero option lets the user input a new Default New Word as a string.
The Theme option will toggle the current Display Theme between Light  and Dark.
The Restore Hints option will re-enable any Hints the user has previously disabled in this Rezonator session.
The Zoom option will open another dropdown, allowing the user to set the timing intervals at which Rezonator will Autosave the current Rezonator session, or to disable Autosaving.[o]
Help Dropdown:
The Help option will toggle the display of the Help Menu on the right side of the Main Screen.
The Docs option will link the user to the Rezonator website’s “Documentation” page in their default web browser.
The About option will link the user to the Rezonator website’s “About” page in their default web browser.

