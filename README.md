# octo-fun
Fun with octo and chip8. Paste file contents into the [Octo editor](http://johnearnest.github.io/Octo/) to run.

## Home Run Derby ([baseball.o8](baseball.o8))
Hit as many home runs as you can before you run out of outs. Recommended to run at 100 cycles/frame.

#### Pitcher Controls
|Pitch   |Height|Key   |
|--------|------|------|
|Fastball|High  |1     |
|        |Mid   |Q     |
|        |Low   |A     |
|Changeup|High  |2     |
|        |Mid   |W     |
|        |Low   |S     |
|Curve   |High  |3     |
|        |Mid   |E     |
|        |Low   |D     |

#### Batter Controls
Swing high **1**

Swing mid  **2**

Swing low  **3**

Reset      **Z**


Hit the solid border to score a run, hit the dotted border to hit an out.
Combine swing timing and height to hit a home run.
Missing timing or height will result in a mis-hit. 

### TODOs
+ Add AI for single-player mode
+ Swap teams after a certain number of outs
+ Fine-tune hitting algorithm for a wider range of angles off the bat
