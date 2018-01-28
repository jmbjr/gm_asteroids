# gm_asteroids
gamemaker studio 1.x asteroids tutorial (Shaun Spalding)

https://www.youtube.com/playlist?list=PLPRT_JORnIuo-DyoWbB7LBrhqlJnsltJq

I made a few changes:

- Use Step Events for keyboard handling
- Use Step Events for handling screen wrap for ship and asteroids (see: https://forum.yoyogames.com/index.php?threads/wrap-outside-the-room-objects-disappear.8391)
- hold 'tab' to slow ship down
- Variablize invincibility duration and gradually slow down flashing to give player better indication on when invincibility will end.
- added a Level system which increases the number of asteroids per sector.

How To Play:
SPACEBAR - shoot
UP - accelerate ship
RIGHT/LEFT - rotate ship
TAB - slows ship 

Ship has about 4 seconds of invincibility after spawning (game start or after you blow up)

NOTE: I hate using TAB, but apparently not all keyboards allow 3 simultaneous keys (SHIFT + UP + LEFT won't work for me, but SHIFT + UP + RIGHT does)
Apparently this is called ghosting.  Switching to WASD for movement may allow me to fix this. Or maybe I'll add a toggle for slow/fast mode.

