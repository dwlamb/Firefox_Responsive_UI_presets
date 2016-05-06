# Firefox_Responsive_UI_presets
Popular phone and table user-interface dimensions for Firefox Developer Tools

To implement these in Firefox:

1. Open a New Tab or Window
2. In the Address Bar enter "about:config". If a warning message comes up, click OK or "I'll be careful, I promise!"
3. Copy and paste this string "devtools.responsiveUI.presets" into the Search box
4. If that preference string doesn't exist, create it
  - right click anywhere in that configuration screen and select "New".  Choose "String"
  - enter the Preference name in the "New String Value" dialog box (Ctrl+V if you copied the string mentioned in Step 3)
  - for the moment, leave value blank and click OK
5.  Right click on "devtools.responsiveUI.presets" and select Modify
6.  paste in the presets, everything from '[' to ']' and including those brackets
