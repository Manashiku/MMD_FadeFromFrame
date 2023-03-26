# MMD_FadeFromFrame
post fx for MMD and MMM that fades from a frame


# How to use:
### for MikuMikuDance :
1. Load in fade.x and make sure it is the last item in the accessories drawing order list (Background>Accessory Edit)
2. You'll want to turn off the display for the .x up until a keyframe before the keyframe you want to fade from.
3. On the keyframe you've chosen to fade from, register a frame with the .x's opacity set to 1.0 (the number in the Tr box) and make sure the display is toggle back on.
4. Navigate to the last keyframe in the duration you want to the fade to last. Register a new keyframe with the opacity set to 0.0.
5. In the very next frame, toggle the display off.
6. Repeat steps 2 through 5 as many times as you want.

### for MikuMikuMoving : 
1. Load the fade.fx shader file using the Import Effect tool from the top bar.
2. You'll want to turn off the visibility for the fx up until a keyframe before the keyframe you want to fade from. This can be done via the fx tab in the bottom of the window.
3. On the keyframe you've chosen to fade from, register a frame with the fx's alpha value set to 1.0 and make sure the visibility is toggled back on.
4. Navigate to the last keyframe in the duration you want to fade to last. Register a new keyframe with the Alpha set to 0.0.
5. In the very next frame, toggle the visibility off again. 
6. Repeat steps 2 through 5 as many times as you want.

If you use this shader I'd appreciate if you at least creditted me somewhere.
And if you decide to edit it and release the it, a link back here would be appreciated.
Have fun :)

## Credits: 
[Nvidia's very helpful article on SAS](https://www.nvidia.com/en-us/drivers/using-sas/)
