# Changes

https://alg.cubing.cz

This is a fork of alg.cubing.net original and the only changes are:

- BOY-YT color scheme which puts yellow on top. This is the default scheme.
- to view original alg.cubing.net alg links with yellow on top you need to replace ".net" with ".cz" only!
  (and possibly remove rotating setup x2y2 moves if the original links have yellow on top already)
- contacts of original authors on the website removed (so they don't get requests for website they do not maintain)
- domain name changes and link changes where appropriate
- Makefile changes for custom builds (make dist)
- README changed

Made as a response to https://github.com/cubing/alg.cubing.net/issues/23.
Hopefully yufanyufan was right, I fixed this according to his proposal.

It seems that the original authors have no intent of adding this feature
as they are busy with new versions and more important tasks. So until
they finish their new piece, we can enjoy this legacy code, just with yellow
on top. As soon as they finish the new product, this fork might no longer
be of any use.

I take no credit for the fixes or any code, I just put it together.

Let's have yellow on top!! :D

Original README follows:

# alg.cubing.net

The new generation of alg/reconstruction viewing and sharing.  
Built on [`alg.js`](https://github.com/cubing/alg.js) and [`twisty.js`](https://github.com/cubing/twisty.js).

## Examples

- [Feliks Zemdegs's 4.22 world record](<https://alg.cubing.net/?alg=F-_R-_D-_R_%2F%2F_pseudo_cross_%0Ay_R_U-_R-_u-_%2F%2F_Xcross_%0AU-_R_U_R-_%2F%2F_2nd_pair_%0Ay-_L-_U2_L_U-_L-_U_L_%2F%2F_3rd_pair_%0Ad_(U_R-_U-_R)2_%2F%2F_4th_pair_%0AU-_R_U2-_R-_R-_F_R_F-_R_U2-_R-_%2F%2F_OLL(CP)_&setup=R2_L-_F2_D2_F-_D_L2_B-_D_L_U_B2_U_B2_D2_L2_D-_F2_D&type=reconstruction&title=Feliks%27%20Zemdegs,%204.22%20WR>)
- [T-perm](https://alg.cubing.net/?title=T-Perm&alg=R_U_R-_U-_R-_F_R2_U-_R-_U-_R_U_R-_F-&stage=PLL&type=alg&view=fullscreen) (fullscreen)
- [Notation Stress Test](https://alg.cubing.net/?alg=RLUDBF_%2F%2F_Single_moves,_no_space.%0AB-_F-_D-_U-_L-_R-_%2F%2F_Inverses.%0AR_L2_R3_L2-_R5_L8-_R7_%2F%2F_Move_amount%0AU_._U_._U_._U_%2F%2F_Pauses.%0AM-_E2_S2_M_S2_E2_%2F%2F_Slice_turns.%0AM2-_U-_M2-_U2-_M2-_U-_M2-_%2F%2F_H-perm.%0Ax_y_z_%2F%2F_Rotations.%0AR2_L2_R2-_L2-_%2F%2F_Half_turns.%0ARw_r-_%2F%2F_Wide_turns.%0A4Rw_x_L-_%2F%2F_Very_wide_turns%0A2%26%2345%3B3Lw_3%26%2345%3B4r__%2F%2F_Wide_block_turns&ini=M2_U_M2_U2_M2_U_M2&name=twisty.js_Stress_Test&cube=5x5x5&setup=M2_U_M2_U2_M2_U_M2&puzzle=5x5x5&title=Stress%20Test)

## Goals

- Solid desktop and mobile support.
- Beautiful alg/reconstruction playback.
- Convenient alg/reconstruction input (i.e. Heise input, live feedback).
- Support for all official puzzles, and popular unofficial ones.
- Simultaneous development with [twisty.js](https://github.com/cubing/twisty.js):
  - Replacement for Java twistypuzzle applets (Heise/Randelshofer/Jelinek/Petrus).
  - State-of-the-art alg parsing and transformation/calculation.
  - General extensibility/hackability, but hopefully all contributed back in one place for everyone to use.
    - Few dependencies.

## History

- [cube.garron.us/tools/index.htm](http://cube.garron.us/tools/index.htm)
  - Firefox search engine.
  - Announced [in the speedsolvingrubikscube Yahoo! group](https://groups.yahoo.com/neo/groups/speedsolvingrubikscube/conversations/topics/36618) on June 25, 2007.
- [cube.garron.us/applets/SiGN_test.htm](http://cube.garron.us/applets/SiGN_test.htm)
- [alg.garron.us/SiGN_test.htm](http://alg.garron.us/SiGN_test.htm)
  - This is actually _still_ the source that is served from [alg.garron.us](http://alg.garron.us/)
- [alg.garron.us](http://alg.garron.us/)
  - Announced [at speedsolving.com](http://www.speedsolving.com/forum/showthread.php?10719-alg-garron-us) on March 25, 2009.
  - Receiving about 1 hit per minute as of early 2014.
- [twisty.js](https://github.com/cubing/twisty.js)
  - Started at a hackathon in June 2011, with the goal of providing a Javascript-only alternative to existing cube applets.
- [alg.cubing.net](http://alg.cubing.net/)
  - Under development. Eventually, all [alg.garron.us](http://alg.garron.us/) traffic will be redirected here.
