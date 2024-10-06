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

4. Radial Burst 1

![19870101-20241006-Radial Burst 1](https://github.com/user-attachments/assets/5389eeb7-7347-4a9c-98a5-f8745e96ff8c)

5. Radial Burst 2

![19870101-20241006-Radial Burst 2](https://github.com/user-attachments/assets/1bf6a133-c862-4134-90d5-fc41713be1b4)

6. Streamline 1

![19870101-20241006-Streamline 1](https://github.com/user-attachments/assets/f29553fb-c969-4657-838e-ab85699f17c0)

7. Streamline 2

![19870101-20241006-Streamline 2](https://github.com/user-attachments/assets/332962cd-c4fd-4f33-8a0e-d34b17153d27)

8. Streamline 3

![19870101-20241006-Streamline 3](https://github.com/user-attachments/assets/9525880d-cea9-4065-8a88-7a6d49c59f3e)

9. Atmosphere 1

![19870101-20241006-Atmosphere 1](https://github.com/user-attachments/assets/393280b7-3ef5-4853-a1a3-28369605af62)

10. Circle 1

![19870101-20241006-Circle 1](https://github.com/user-attachments/assets/dc2d74f4-cf11-4b59-9c0b-3be96030bfa5)

11. Blood Spouts 1

![19870101-20241006-Blood Spouts 1](https://github.com/user-attachments/assets/009edfd7-49f7-43fc-9f39-f5f986cb9d61)

## Requirement
It needs the shader mod, [Billboarding Cutout Shader for ME](https://github.com/Blatke/Billboarding_Cutout_Shader_for_ME), to let MaterialEditor show its options on the tab. If you don't have it, click the link to get it.

**NOTE:** This mod depends on that shader mod, which means an update on this mod might rely on the update of that shader. You need to check if that shader mod was updated when you get the latest version of this mod to use.

## How to Use
Download the .zipmod file for the latest version on the [Release](https://github.com/Blatke/Comic-Effects/releases) page, then drag and drop it into your **/mods/** folder, or use KKManager to install it.

Watch the demonstration video to directly learn how to adjust the parameters: https://youtu.be/LAqAPOF4Xow

## Customization
Yes you can import some textures of your own on the tab of MaterialEditor to change the **MainTex** of the item. Remember the background of your texture must be transparent (alpha = 0) so that the shader can cull the background with remaining the RGB parts.

![AI_2024-10-06-07-17-51-542](https://github.com/user-attachments/assets/09b16001-30fa-4be7-9ba6-361d474588a5)

You can also adjust the tiling and offset of the texture: https://youtu.be/qSuApclZE0s

## Troubleshooting
When moving the view away from the center of a Comic Effect item, sometimes the item disappears, and when the view is moved back, the item then reappears. This could happen because the item in fact shows the comic effect by putting a shader onto a cube object, and when the screen moves off the boundary of the cube, the game will not get the cube rendered, and thus no comic effect it can show. **Scaling up the item size can solve this problem.** Just scale it up till you can see the comic effect on the screen. 

![image](https://github.com/user-attachments/assets/59017349-dea2-45eb-9322-6d144abfad55)

BTW, rescaling the item does NOT affect the comic effect size, because the comic effect is a shader's job with the scale being re-defined at the rendering step. The comic effect can be only re-scaled by using MaterialEditor on the X and Y axes. 
