# Delphi-LightSaber  
Contains useful functions.   
Lightweight alternative to Jedi library.   

Simple, crystal clear, non-obfuscated, fully commented code.   
No external dependencies.   
  
This library will be expanded soon.  
  
**ccCore.pas**  
  Over 200 functions for:  
     String manipulation (string conversions, sub-string detection, word manipulation, cut, copy, split, wrap, etc)  
     Programmer's helper  
     Form manipulation  
     Advanced/easy message boxes  
     DateTime utilities  
    
    
**ccIO.pas**  
  Super useful functions for file/folder/disk manipulation:  
     * Copy files   
     * File/Folder Exists    
     * Get special Windows folders (My Documents, etc)  
     * Prompt user to select a file/folder  
     * List specified files (*.jpg for ex) in a folder and all its sub-folders  
     * Increment the numbers in a filename (good for incremental backups)  
     * Append strings to file name  
     * Read text from files to a string variable  
     * Compare files  
     * Merge files  
     * Sort lines in a file  
     * Drive manipulation (IsDiskInDrive, etc)       
     
     
**ccAppData.pas**  
  Application-wide functions:  
     Get application's system/appdata folder  
     Get application's INI file  
     Get application's command line parameters  
     Detect if the application is running for the firs this in a computer  
     Application self-restart  
     Application self-delete  
   
     
**ccStreamBuff.pas**  
     Buffered file access (very fast reading/writing to a file).  
     
**ccStreamFile.pas**  
     Class that allows you to directly read/write bytes, cardinals, words, integers, strings to a (binary) files.  
     
**ccBinary.pas**  
     String to hex, hex to string conversions (and many others)  
     Binary numbers swapping  
     Data serialization  
     Bit manipulation (set bit, etc)  
     Reverse bits  
     Endianess  

**ccWinVersion.pas**
     This library provides 3 ways to get Windows version.  
     Example of functions:   
       IsWindowsXP  
       IsWindowsXPUp  
       IsWindowsVista    
       IsWindowsVistaUp  
       IsWindows7  
       IsWindows7Up  
       IsWindows8  
       IsWindows8Up  
       IsWindows10  
