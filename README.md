## *Retro Gameplaying as Interactive and Generative Music Interface on Launchpad*

### Artist's statement

I think current instruments lack certain feedback to the performers and especially audiences. Live performances will normally have an auxiliary visual element (like laser lights synced to the music or generative visuals), which is more of an effect rather than a cause. For Launchpad performances, most of the time the visuals on the grid are nothing more than flashes of lights. It will be interesting, then, to perform an instrument by playing the game, or to play the game by performing the instrument, such that each interaction by the performer does not only create sounds/music, but also at the same time creates the visualization of the music (which is a gameplay meaningful by itself). This should further blur the line between sounds and visuals, and hopefully will create unique interactive feedback.

---

[**Performance/Documentation Video**](https://www.youtube.com/watch?v=W4_LWxrSHR4)

Main file is `project.pd`. The code is not well-documented.

All Pd files (copyleft) 2022 by SuperFashi is licensed under [Attribution-ShareAlike 4.0 International](./LICENSE).

Required by this work but not distributed files include

- `blsaw~.pd`, `blsquare~.pd`, and `bltri~.pd`, which are band-limited sawtooth, square and triangle wave osciallators respectively. The original files I used are copyrighted materials and are not my work. There files should be replaceable by any Pd patches with similar functionalities with little to no modification.

- `TO_LPM_MK3.pd`, which contains code for controlling Launchpad Mini MK3, can be found in [Focusrite-Novation/r_cycle](https://github.com/Focusrite-Novation/r_cycle). This file should be replaceable by other Launchpad models, however key mappings are hard-coded and simply changing the model may break the code unless heavily modified.
