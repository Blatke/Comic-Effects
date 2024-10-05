# Comic Effects
HS2 / AIS Studio Items.

## Items Included
1. Radial Speed Line 1

![19870101-00001900-Radial Speed Line 1](https://github.com/user-attachments/assets/8392cb0e-53b7-4a6e-9d38-84eb4ef27c23)


## Requirement
It needs the shader mod, ["FaceToCamera Cutout Shader for ME"](https://github.com/Blatke/FaceToCamera-Cutout-Shader-for-ME/releases), to let MaterialEditor show its options on the tab. If you don't have it, click the link to get it.

## How to Use
Download the .zipmod file for the latest version on the [Release](https://github.com/Blatke/Comic-Effects/releases) page, then drag and drop it into your **/mods/** folder, or use KKManager to install it.

Watch the demonstration video to directly learn how to adjust the parameters: https://youtu.be/LAqAPOF4Xow

## Troubleshooting
When moving the view away from the center of a Comic Effect item, sometimes the item disappears, and when the view is moved back, the item then reappears. This could happen because the item in fact shows the comic effect by putting a shader onto a cube object, and when the screen moves off the boundary of the cube, the game will not get the cube rendered, and thus no comic effect it can show. **Scaling up the item size can solve this problem.** Just scale it up till you can see the comic effect on the screen. 
