# AI Gen Gacha

This is a implementation of an ai generative gacha system. Using stable-diffusion-webui's api feature to generate image and send it to Unity's UGUI.

**Package ref:**  [dobrado76/Stable-Diffusion-Unity-Integration](https://github.com/dobrado76/Stable-Diffusion-Unity-Integration)

You can find more feature with webui api [here](https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/API)

## Setup

1. Run webui-user.bat with **COMMANDLINE_ARGS=--api**. You can edit it with Notepad or any editor you like.
2. In MainScene, browse to **StableDiffusionConfiguration** in hierarchy and click List Models in **StableDiffusionConfiguration** script at inspector.
3. Browse to **Canvas/ImageResult** in hierarchy, and set generation settings that you need in **StableDiffusionText2Image** script at inspector.
4. You're good to go! Try click the button to gacha in playing mode.

*It's recommended that choose sampler labeled with "a". This will generate some random things in every gacha.
