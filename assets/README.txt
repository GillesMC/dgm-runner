DGM — image slots
=================
Drop PNG files here with EXACTLY these names to replace the placeholder shapes.
Missing files are fine: the game draws colored shapes instead, with no error.

frame_cabinet_phase1.png - console body art (1663x946, transparent screen window at 319,119 1021x548)
frame_cabinet_phase2.png - console body art used during phase 2 runs (same geometry)
home_bg.png              - home screen background (1021x548, the console window)
home_title.png           - "demon got me" logo (slides in on the home screen)
home_character_1.png     - idle character with gear (home screen, standing on the ground)
home_character_run1/2.png- walking frames (intro cinematic)
home_character_hurt1/2/3.png - bump/fall/gear-lost frames (intro cinematic)
player_p1_run_1..6.png   - phase 1 player, running loop (6 frames, 377x382, bottom-center anchor)
player_p1_hold_1..3.png  - phase 1 player, HODL glide loop (3 frames, 425x649, parachute above)
player_p1_jump.png       - phase 1 player, first jump / simple fall (377x382)
player_p1_doublejump.png - phase 1 player, after the 2nd jump (327x334, own size, bottom-center anchor)
player_p1_hurt.png       - phase 1 player, death sequence (346x314, own size, bottom-center anchor)
player_p2_run.png        - phase 2 (demon) player, on the ground
player_p2_jump.png       - phase 2 (demon) player, in the air
obstacle_ground_p1_1..3.png - ground obstacle variants, phase 1 (3 fixed size presets in the code)
obstacle_air_p1_1.png       - THE phase-1 flying obstacle (single variant, medium size)
obstacle_ground_p2_1..3.png - ground obstacle variants, phase 2 (optional; falls back to obstacle_ground_p2.png)
obstacle_air_p2_1..3.png    - overhead obstacle variants, phase 2 (optional; falls back to obstacle_air_p2.png)
(the un-numbered names obstacle_*_p*.png still work as single-image fallbacks)
collectible_points_p1.png - +20 points collectible, phase 1 look
collectible_points_p2.png - +20 points collectible, phase 2 look
collectible_boost.png     - BOOST pickup (speed burst, smashes obstacles)
collectible_hodl.png      - HODL token (refills the glide meter)
(collectible_points.png still works as a fallback for the points ones)
bg_phase1.png            - in-game background, phase 1 (900x600)
bg_phase2.png            - in-game background, phase 2 (900x600)
ground_phase1.png        - ground strip, phase 1 (tiled horizontally, scrolls)
ground_phase2.png        - ground strip, phase 2 (tiled horizontally, scrolls)
gameover_character_1..5.png - death beat-up: _1<->_2 loop, then _5 as the final pose
pause_menu_check.png     - big transparent image behind the pause overlay (press P in game)
spam_warning_1..2.png    - the "sonic" omen: grows from the center between 500 and 666,
                           gigantic & transparent at the 666 freeze (2-frame loop)
gear_jetpack.png         - the jetpack flying off during the home intro gag [TO ADD]
gear_sneaker.png         - the sneaker flying off during the home intro gag (drawn twice) [TO ADD]
player_p2_run_1..6 / _hold_1..3 / _jump / _doublejump / _hurt (all optional) -
                           phase 2 player set; until these exist, phase 2 uses the p1 frames
leaderboard_bg.png       - leaderboard screen background (900x600)
leaderboard_character.png    - crying character (player NOT in the top 10)
leaderboard_character_1.png  - player ranked 5th to 10th
leaderboard_character_2.png  - player ranked 3rd or 4th
leaderboard_character_3.png  - player ranked 2nd
leaderboard_character_4.png  - player ranked 1st
