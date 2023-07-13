# noutil
Some JavaScript and Google Apps Script specific utility functions

## resourceLock 
just got it working..
it works very much like the lock service in apps script, only it allows one script to hold only if a set resource is being used.
this is only tested for human input (may not hold up to heavy load) to avoid entries overwriting each other when using custom forms built in apps apps script. this may only be an issue with how I've implemented saving, however to achieve a similar a result i couldn't find much outside of an old library.
