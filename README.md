# DJAutoCue 
Automatically place a cue point based on configurable parameters

Prerequsites:
* All tracks must be analyzed
* Must allow ample time for track to load (if using a streaming service like TIDAL)
* All tracks must begin at the first bar (will have to reanalyze songs)

1. ) Load Track on Deck 1
2. ) Skip to first cue point 
3. ) Skip 8 bars, place cue point
    -> 1 for HOTCUE A, SKIP 8 bars
    -> 2 for HOTCUE B, SKIP 8 bars
    -> 3 for HOTCUE C, SKIP 8 bars
    -> 4 for HOTCUE D, SKIP 8 bars
    (can configure the amount of bars to skip & number of CUE points)
4. ) Load next track, repeat
5. ) Add more info
