# Reflections_Presets

In this project, we're exploring both some delightful texture fakery to replicate a "reflective" surface, and a system to record and recall parameters at certain presets (e.g. "cues") that we'd like to transition between.

To get a "reflective"effect, we place a camera inside the central fractal set only to render the environmental geometry. That camera's render is then used as the material for the fractal, giving said fractal the illusion of reflecting its surroundings. Several parameters about the fractal itself and its environment are exposed to us on the component, so we can experiment and find configurations that we find pleasant and would like to save, without necessarily needing to dive inside.

Our network has two main characters: A "cue lab" container, and a "performance" container, which both have the same parameters exposed, with a few notable control-based exceptions. By tweaking values on the "cue lab" container, we can test out looks we'd like to save, and record them to our "cue sheet." 

Once we record them, we can recall them from a list supplied by the performance container. On the performance container, we can toggle a fade up/down feature for smooth transitioning. 

Once inside a cue on the "performance" container, we can still adjust our parameters to tweak the look, however 

A warning dialogue will pop up should we attempt to overwrite an existing cue, at which point we may choose to continue the operation or to cancel, as well as if we attempt to recall a cue that does not exist.

Please note! This project was initially created using the experimental Touchdesigner macOS Build 2019.30550 - this is the version saved on macOS stable Build 2019.18580, however bugs may pervade!

Please reach out with any questions/comments!!

Rey

reyjarrell@gmail.com
reyjarrell.myportfolio.com
 
