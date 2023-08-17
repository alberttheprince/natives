---
ns: PLAYER
---
## SET_PLAYER_PARACHUTE_PACK_TINT_INDEX

```c
// 0x93B0FB27C9A04060 0xD79D5D1B
void SET_PLAYER_PARACHUTE_PACK_TINT_INDEX(Player player, int tintIndex);
```

```
Tints 0 - 13
0 - Rainbow
1 - Red
2 - white, Blue, Yellow
3 - Black, Red, and White
4 - Red, White, and Blue
5 - Blue
6 - Black (Kind of a Greenish Black in reality)
7 - Black and Yellow

The following must have SetPlayerParachuteModelOverride and SetPlayerReserveParachuteModelOverride set before they appear. Otherwise, any numbers beyond seven will result in black and yellow. If you use this native to choose a colour for the player's parachute randomly, any additional choice effectively makes black and yellow increasingly likely.

8 - Green, Blue, and Red
9 - Desert Camo
10 - Dark Green and Light Green
11 - Red and Tan Parachute
12 - Blue, Orange, and White
13 - Yellow, Orange, Re, and Blue


```

## Parameters
* **player**: 
* **tintIndex**: 

