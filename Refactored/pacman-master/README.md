PacMan - Refactored
==============

Observer Pattern:  
PacMan game object is now an Observable object, and Ghost and Audio objects are Observer objects.
For events, e.g. pacman eating a pill which changes the states of all ghosts and triggers a sound, a simple notification will now handle the state changes of ghosts and playing sounds.
