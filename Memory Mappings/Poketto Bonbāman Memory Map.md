Note: This document is far from complete

## Work RAM (WRAM) Bank 0 (0xC000 - 0xCFFF):
```
Address: | Size (bytes): | Description:                           | Notes:
0xC1EC     1               Bomb Count
0xC1ED     1               Bomb Blast Radius 
0xC1EE     1               Movement Speed
0xC1EF     1               Life Count
0xC1F0     1               Remaining Enemy Count
0xC1F7     1               Remaining Time - Minutes
0xC1F8     1               Remaining Time - Seconds
0xC25C     1               Camera or map drawing X offset?
0xC452     1               Manual Detonation and Flying Flags?    | Appears to use 1 nibble (4 bits) for each.
```
