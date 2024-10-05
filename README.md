# Comic Effects
HS2 / AIS Studio Items.

![AI_2024-10-06-05-02-31-950](https://github.com/user-attachments/assets/70f40308-592d-457a-b13e-95a39eccf746)

## Items Included
1. Radial Speed Line 1

![19870101-00001900-Radial Speed Line 1](https://github.com/user-attachments/assets/8392cb0e-53b7-4a6e-9d38-84eb4ef27c23)

2. Radial Speed Line 2

![19870101-00001900-Radial Speed Line 2](https://github.com/user-attachments/assets/7c950fbb-7c87-4206-ba9b-513a62e10727)

3. Radial Speed Line 3

![19870101-00001900-Radial Speed Line 3](https://github.com/user-attachments/assets/e8724770-8180-4e9f-85a4-0c4b156e272d)

## Requirement
It needs the shader mod, [Billboarding Cutout Shader for ME](https://github.com/Blatke/Billboarding_Cutout_Shader_for_ME), to let MaterialEditor show its options on the tab. If you don't have it, click the link to get it.

## How to Use
Download the .zipmod file for the latest version on the [Release](https://github.com/Blatke/Comic-Effects/releases) page, then drag and drop it into your **/mods/** folder, or use KKManager to install it.

Watch the demonstration video to directly learn how to adjust the parameters: https://youtu.be/LAqAPOF4Xow

## Customization
Yes you can import some textures of your own on the tab of MaterialEditor to change the **MainTex** of the item. Remember the background of your texture must be transparent (alpha = 0) so that the shader can cull the background with remaining the RGB parts.

![AI_2024-10-06-07-17-51-542](https://github.com/user-attachments/assets/09b16001-30fa-4be7-9ba6-361d474588a5)

You can also adjust the tiling and offset of the texture.

## Troubleshooting
When moving the view away from the center of a Comic Effect item, sometimes the item disappears, and when the view is moved back, the item then reappears. This could happen because the item in fact shows the comic effect by putting a shader onto a cube object, and when the screen moves off the boundary of the cube, the game will not get the cube rendered, and thus no comic effect it can show. **Scaling up the item size can solve this problem.** Just scale it up till you can see the comic effect on the screen. 

![image](https://github.com/user-attachments/assets/59017349-dea2-45eb-9322-6d144abfad55)

BTW, rescaling the item does NOT affect the comic effect size, because the comic effect is a shader's job with the scale being re-defined at the rendering step. The comic effect can be only re-scaled by using MaterialEditor on the X and Y axes. 
