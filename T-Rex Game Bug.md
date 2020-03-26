# T-Rex Game Bug

### Problem

* The game would go blank (sometimes).
* The T-Rex would keep flying.

### Solution 

#### (Game to work)

* I removed the background("white"), command and wrote again, thinking that there was an issue with the specific code.

#### (For T-Rex to jump and not fly)

* I realised that I forgot to add gravity to the game

#### I.E (The code)

   trex.velocityY = trex.velocityY + 0.8;

