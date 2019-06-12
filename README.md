# Command-line-subtitle-Displayer
A little program I made to print out subtitles from an SRT file line by line in real time on the command line.

Usage:
make file executable (chmod +x srtwait)

./srtwait [-p] Filename
Will output subtitles from file line by line onto the command line. 

-p -- get all subtitle lines from file, output them onto the command line, then quit
-t -- print the time difference between the first timestamp and the last timestamp in seconds, then quit

no options -- print out subtitles in real time by waiting (end timestamp - beginning timestamp) amount of time

I might add a command-line option to clear everything before printing a new line in the near future.
