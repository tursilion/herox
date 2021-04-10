HeroX
=====

![Screenshot](https://github.com/tursilion/herox/raw/master/dist/HeroX_1.png)
![Screenshot](https://github.com/tursilion/herox/raw/master/dist/HeroX_2.png)

HeroX (he-ro-ex) is a port of a game I created for XB back in 1987 or 1988, best that I can remember. I had just started to figure out when to use and when not to use automotion, and this was the result. It was still slow, clunky, and had a lot of bugs, but it had a little charm.

For the 4k demo I decided to revise it, figuring it should fit in a small amount of memory and I could enhance it. I used the technique I used for porting TI Farmer and ZomBXB from the Short and Sweet Game contest to port the game from XB. The resulting game was 6k -- too large, but over the course of a couple of weeks I was able to shrink it down and then eventually added smooth motion, animations, sound effects and even a little music.

The game was designed to work from the MiniMemory, but was slightly too large to work with the built-in LOAD AND RUN option. Thanks to Senior Falcon's skills, we have a lovely TI BASIC loader to work around that - just load and run from TI BASIC (Mini-Memory or Supercart with 8k RAM or more is required!) This is "HEROX_BAS", which is provided as a TIFILES type file. (Note this loader is slightly above 4k) This MUST be used with Mini-memory or a SuperCART with RAM.

Alternately, "HeroX_C.bin" is a cartridge image that runs at the normal >6000 address... you can burn a 4k EPROM or load into any of the ROM cartridge solutions (as well as use in emulation). (This is my official 4k entry.)

HEROX_EA5 is a TIFILES image of the Editor/Assembler#5 image, which requires 32k memory expansion instead of a MiniMemory. Use option #5 RUN PROGRAM FILE. (This is just for people who can't run either of the above)

HERO(XB) is the original Extended BASIC program that I started with, just for sake of curiousity. It's also a TIFILES image. It's way over 4k.

HERO(XB), HEROX_EA5 and HEROX_BAS are also both on the included HEROX.DSK disk image, and may be used with emulation or transferred to hardware via any of the disk transfer techniques.

Finally, HEROX.A99 is the source code. Feel free to rip ideas or techniques but please check with me before using as the basis for your own title. Also at Github: https://github.com/tursilion/herox

This is my entry into the 2018 4k contest. Thanks!

-Tursi

-------------
 HOW TO PLAY
-------------

Once you have the game up and running, use Joystick 1. Alpha Lock up. There are 5 screens to clear.

Your Hero will always start at the bottom left of the screen in white. He will remain invincible until you press the fire button to start. He will turn black to indicate he's active and a timer at bottom right will immediately start to count down. Use the joystick to move left or right, and to climb up and down ladders. Your Hero is a studly and pixelated track star - pressing fire will cause a mighty leap!

Each stage has four square wafers. Collect the wafers to advance. Once you have all four, a ladder will appear at top left to take you to the next level. Why do wafers do this? Life is full of mysteries.

Get to the final stage, defeat your nemesis and save the girl!

Four things can defeat our hero:

1) touching any enemy, moving or static
2) falling into a moving hole
3) falling too far off a platform
4) Running out of time.

Bonus time: each level has a countdown timer. If you clear the level before time runs out, you are awarded the remaining time as points. If you run out of time, you will die. If you die for any reason, when you continue the timer will start at 0 and will not count down. You will not be timed for the rest of the level, but neither will you receive any bonus for completing it.

The timer is frame accurate. I'm hoping people might try a high score competition. There are lots of ways to edge a few extra bonus points for time. ;)

You get three lives. No bonus lives are awarded. Game Over if you run out of lives.

Want to donate?
---------------

- Click here for [Ko-Fi](https://ko-fi.com/tursilion)...
- Alternately, there's my [Amazon Wishlist](http://www.amazon.com/gp/registry/2AFCOAM5DD1L6/ref=cm_aya_wl/103-5991996-6483001)

