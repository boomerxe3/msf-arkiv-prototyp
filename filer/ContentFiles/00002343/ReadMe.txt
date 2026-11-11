
GliderScore does not require any special installation.
=================================================================
The files are automatically extracted to C:\GliderScore6
=================================================================
Files extracted are
	GliderScoreData.mdb
	GliderScoreDataStructure.mdb
	GliderScore.exe
        GliderScore.exe - Shortcut
        PilotsComma.csv  (for uploading your own pilots to the database)
        PilotsSemiColon.csv  (for uploading your own pilots to the database)
	ReadMe.txt
=================================================================
ABOUT Pilots*.csv files

These files are provided as templates to set up pilot data for import to the
Pilots master file.

If you are in a region that uses a comma "," as a list separator (and using a '.' as
a decimal separator), use PilotsComma.csv.

If you are in a region that uses a semicolon ";" as a list separator (and using a ',' as
a decimal separator, use PilotsSemiColon.csv.

Rename your file to Pilots.csv before attempting to import your data.

=================================================================
You can copy the shortcut 'GliderScore.exe - Shortcut' and paste it on your desktop.
=================================================================
Click (or double click) on GliderScore.exe (or the shortcut) to run the program.
=================================================================
The database has several sample competitions to get you started.
Play around with these all you like.  It's the way to learn.
=================================================================
The competitions dated before 30-06-10 are all real competitions with real pilot names.
I have just added "ZZ" in front of every surname.
I suggest that you progressively edit these names to the names that you need for your competitions.
Otherwise they will simply sort to the bottom of the pilot list as you add pilots to your database.
You will have to delete the competitions in which these pilots appear before you will be able to delete them (the pilots). 
=================================================================

GliderScore can be used for competitions where the target time can change from round to round. Simply change the target time in the 'Scoring' screen. Scores are automatically adjusted whenever the target time is changed.

=================================================================

MULTI-LANGUAGE FACILITY

GliderScore now supports ANY language.  This is how it is done.

1. The language file English.lng is created every time the program is run and is written to folder containing GliderScore.exe.
   Use Wordpad to open this file.  For some reason MSWord does not like it.

2. Other language files (YourLanguage.lng) must also be located in the folder containing GliderScore.exe.

3. At start up the program looks for files *.lng in the folder containing GliderScore.exe and populates a drop down list so that
   any of the languages found can be selected.

4. Once selected, all words in the english.lng file that have corresponding words in YourLanguage.lng will
   be translated.

5. Every language file relates to the English language file by means of a number against every entry.
   Entries having the same number in both the English file and the 'other' file will be translated.

6. By making a copy of the English.lng file, and renaming it, it is possible to create a file for any language.
   Simply replace the English text with text in your own language.  Wordpad is ideal for this purpose.

=================================================================


There is a vast amount of information on how to use the program.  This all available by clicking on any of the 'i' buttons.

Provision has been made to view information for an item, for a whole screen, or all the information available. This can also be printed or saved to a file.

If the file structure of the English.info file is followed, you can make your own translation of the available information. Your translation would be named YourLanguage.info.

There is more information about this on the website.

=================================================================
Changing the Default Installation Directory

By default the program and files install in C:\GliderScore6 folder.

However, after installation this can be changed to any folder.

GliderScore.exe can be located anywhere at all on your computer. It really doesn't matter.

Some files such as language translation files and audio files are always located in the same folder as the .exe file or in a sub-directory off that folder. So it is important to settle on a location for GliderScore.exe and stay with that.

The database files can also be anywhere on your computer but a pair of them (gliderscoredata.mdb and gliderscoredatastructure.mdb) must exist in the same folder. You can have as many pairs of database files as you like and simply point the program to each one as required.

Ok, here are the steps that will most easily get you to your desired configuration.
1. Create the folder that you want to use on your computer. Your choice.
2. Copy all the files that are in C:\gliderscore6 to your new folder. Do not delete them yet.
3. Run the program from the new location. It is still pointing to C:\GliderScore6 at this stage.
4. On the Main Menu, click on "View/Change Database Folder".
5. Navigate to the new location of the database files.
6. Click on GliderScoreData.mdb to make the change.

Each time you run the program it will look for the database files in the new location.

You can test by renaming the database files in C:\GliderScore6 to GliderScoreDataOld.mdb and GliderScoreDataStructureOld.mdb and see what happens.

When you are satisfied that it is all working you can delete the C:\GliderScore6 folder.

=================================================================

If you cannot understand anything at all you can send me an email at gerry.carter@gliderscore.com.

I hope that GliderScore is just what you were looking for.
All the best,
Gerry Carter

