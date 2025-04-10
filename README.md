# Mojavatars For Blender
![Image](https://github.com/user-attachments/assets/2eb6b5d1-e9bc-404f-be95-50a827f3f796)
Recreation of Mojang Studio's 3D Mojavatars for Blender


# Usage
You can [download](https://github.com/Djihads80/MojavatarsBlender/releases) the latest .blend file from [here!](https://github.com/Djihads80/MojavatarsBlender/releases)

After downloading, open the .blend file, make sure you are atleast using a version newer than `4.4.0` as this was not made to account for older Blender versions

<details>
  <summary>Click here for instructions</summary>

### To get started adding your own skin, go to the Shading tab
![image](https://github.com/user-attachments/assets/deaed7bf-c99f-45d0-84de-e0a6ab13fffa)

Down below, you should see the node group
### make sure you are on `Skin Material` material!!!!!!!!

after that, replace the skin Image Texture with your own Minecraft Skin

![image](https://github.com/user-attachments/assets/ea271816-940d-4268-b2fa-5910ff0c050e)

![image](https://github.com/user-attachments/assets/9c4abe9a-b148-4783-a41a-b1cd9abf961c)

### After that, your Minecraft skin finally has a *Moustache* /j

![image](https://github.com/user-attachments/assets/efae8188-149d-4b94-ba96-7893690a19f6)


To add reflections to the hair (and to also fix the moustache), find the Factor Image Texture (you can use Middle Mouse Button to navigate through the shader's node setup)

![image](https://github.com/user-attachments/assets/d7c4282f-4781-4710-b680-37f0d72b71d9)

Replace the factor with a edit version of your skin to act as a factor for the shader mixer between glossy and normal shading

### You can use any image editing software but i personally recommend using [BlockBench](https://web.blockbench.net/) for this

![image](https://github.com/user-attachments/assets/961b3f05-dbd9-4245-ab08-1820826c78a1)
![73eaff3309122eaf (1)](https://github.com/user-attachments/assets/0a63c5b7-f0ad-47fb-afca-006d32bf1029)
![image](https://github.com/user-attachments/assets/1444ddf5-bf69-4f3e-a632-57705b595d18)

After that, switch to [Solid](https://en.wikipedia.org/wiki/Solid_Snake) mode

![image](https://github.com/user-attachments/assets/174364a5-b903-4549-b9c2-98a62ac3f280)

Left Click on any of these floating objects

![image](https://github.com/user-attachments/assets/53ecf938-8193-4f01-9db5-b64938973d03)

In their shader node setup, you can change their color to the skin's hair/hat/head texture color or anything relative to that as this controls the color of the reflected objects which are not visable in the final render
`you can use Ctrl+F to find where the nodes are if you can't see them!`

![image](https://github.com/user-attachments/assets/edc7c713-6289-4665-bde3-7e835fd710c6)

## After all of that, you are done 🎉🎉🎉
you can press F12 to start rendering your Mojavatar!

after the render finishes, make sure to save it

![image](https://github.com/user-attachments/assets/8fdc228e-196d-4aae-a1a1-15a2dfd24daa)

</details>

# Issues

If you encounter any problem, please open an Issue, and describe the problem with great details (and please provide any addition information such as computer specs, operating system, blender version etc...)

If you know how to solve such problems (assuming its a *my* problem like inncorrect UVs) then open a pull request 😊

# Building

To build MojavatarsBlender from source, first clone the repository and all of its submodules.

```
git clone https://www.youtube.com/watch?v=tYNNRwyYK4s --recursive
```

<details>
  <summary>Click here for build instructions</summary>

### why are you cloning a Youtube link, mark?

### think mark think!

`the video contains spoilers for Invincible (TV Show and Comics)`
</details>
