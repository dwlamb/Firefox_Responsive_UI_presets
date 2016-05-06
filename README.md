# Firefox_Responsive_UI_presets
Popular phone and tablet user-interface dimensions for Firefox Developer Tools

To implement these in Firefox:

1. Open a New Tab or Window
2. In the Address Bar enter "about:config". If a warning message comes up, click OK or "I'll be careful, I promise!"
3. Copy and paste this string "devtools.responsiveUI.presets" into the Search box
4. If that preference string doesn't exist, create it
  - right click anywhere in that configuration screen and select "New".  Choose "String"
  - enter the Preference name in the "New String Value" dialog box (Ctrl+V if you copied the string mentioned in Step 3) and click Ok
  - for the moment, leave value blank and click OK
5.  Right click on "devtools.responsiveUI.presets" and select Modify
6.  paste in the presets from the file 'Phone_and_Tablet_Presets.json', everything from '[' to ']' and including those brackets
7.  Exit about:config
8.  Open a new tab or window, load in a web url you wish to see in different emulations
9.  Press 'Ctrl+M' to see that site in one of the presets
10.  From the presets, choose a dimension.
