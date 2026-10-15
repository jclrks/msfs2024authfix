# msfs2024authfix
A fix for the sign-in window not appearing in Microsoft Flight Simulator 2024 and 2020

I tried to install MSFS 2024 a little bit ago but it just wouldn't prompt me with a sign-in window, staying at "0% - Authentication in progress (8/22)". All services and apps required were installed, and I was stumped. No online suggestions worked. So I cobbled together this junky fix.

You should only need to run this once for each program, after you're signed in things should act normally.

## Requirements
Windows 10/11, Powershell 5.1 (which should already be installed) and any Chromium-based browser such as Google Chrome, Microsoft Edge, Brave, Vivaldi, et cetera.

Make sure your Powershell execution policy allows running scripts.

## Should an error occur
`-Report` prints the game's version, what the analysis found, and why it stopped.
Run the Powershell scripts as an administrator if access is denied.

## Disclaimer

This fix is **NOT** a tool for piracy, cheating or any other shenanigans, nor it can it be used that way. 

This program was only tested with the Steam versions of both games.

vtable_probe.exe may trigger a false positive in some anti-virus solutions.
