# minigame 2
## Devlog
1. I encountered three identical errors, repeated on 3 lines, after trying to set the redness of the boxes. The exact error was: "error CS0201: Only assignment, call, increment, decrement, await, and new object expressions can be used as a statement". In my carelessness and tiredness, i used == instead of = for assigning values to the r variable. After realizing, all I did was change == to = in those lines to fix it.

2. Using . after a variable is for calling certain functions or other variables linked to that value. In this case, . would be used to call the color variable of _spriteRenderer, which the line of code then assigns to a new colour. 
## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
