# win-term-cmdhere
A quick and easy way to pop open a Command tab from a Powershell tab with the same location.

## About
Powershell is pretty good, you can do lots of things but sometimes it can be.... awkward. Say you want to quickly run a command to a UNC path but you get an error about needing permissions etc... You know you can do the same thing in command prompt but if you just open a new tab you'll then have to navigate to the folder again (not fun with long UNC paths). This little oneliner pops up a new tab (or window if your not a tab person) in WinTerm at the same folder location.



https://user-images.githubusercontent.com/8470449/194303777-8bac9086-b39d-45d5-8831-c2a7f7e32395.mp4

## Usage
Just drop the cmdhere.ps1 file into a convenient location that is in your path, type `cmdhere` in a Powershell tab to pop to a command prompt. You can use this for most Windows Terminal profiles, for example if you have Admin profiles you wish to use just make a new copy of this file and change the profile name in the quotes. 

## Limitations
- If you are non English speaker, you'll likely need to change the `"Command Prompt"` to what is used in your language.
- It will not carry any command history across shells, this is a limitation of Windows and the hodge podge mix of shells we have.
