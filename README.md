# Flux.1-dev-ControlNet-jupyter

- Flux ControlNets with Txt2Img | Img2Img | + Multiple LoRAs, All in one notebook
- Works in Google Colab Free Teir T4 GPU 🥳🥳
- Uses [Flux.1-dev GGUF](https://huggingface.co/city96/FLUX.1-dev-gguf) models

## Notebooks

| Notebook  | Info |
| ------------- |:-------------:|
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/LucipherDev/Flux.1-dev-ControlNet-jupyter/blob/main/Flux.1-dev-XLabs_CN-jupyter.ipynb)      | Flux.1-dev-XLabs_CN-jupyter ([flux1-dev-Q4_K_S.gguf](https://huggingface.co/city96/FLUX.1-dev-gguf/blob/main/flux1-dev-Q4_K_S.gguf)) |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/LucipherDev/Flux.1-dev-ControlNet-jupyter/blob/main/Flux.1-dev-Union_CN-jupyter.ipynb)      | Flux.1-dev-Union_CN-jupyter (flux1-dev-[Q2_K.gguf](https://huggingface.co/city96/FLUX.1-dev-gguf/blob/main/flux1-dev-Q2_K.gguf)/[Q8_0.gguf](https://huggingface.co/city96/FLUX.1-dev-gguf/blob/main/flux1-dev-Q8_0.gguf)) |

###### * *This is still unstable in google colab free tier and prone to crashing because of low system RAM. Use at your own risk.*

## Features

*Basic Functions [Txt2Img | Img2Img | + Multiple LoRAs] are as shown in [LucipherDev/Flux.1-fp8-jupyter](https://github.com/LucipherDev/Flux.1-fp8-jupyter)*

## X-Labs ControlNet

### Preprocessors
- Canny
- Depth (DepthAnythingV2)
- HED

![ss1](https://github.com/user-attachments/assets/4cec4bb8-f89a-4e7f-b3f6-935c6b2f21b8)

![preprocessor_examples_1](https://github.com/user-attachments/assets/8ef1063c-0267-4002-8b3d-d14cebefca03)

![ss2](https://github.com/user-attachments/assets/3f71dd12-94a7-40e7-9ea9-ac632cfb1cf5)

![xlabs-cn-examples](https://github.com/user-attachments/assets/b7e1108e-9367-4ee3-b568-015a244d8a36)

## Union-Pro ControlNet

*Low RAM uses flux1-dev-Q2_K.gguf and gives low quality results, so using high RAM is advised as it uses flux1-dev-Q8_0.gguf*
 
### Preprocessors
- Openpose
- Depth (DepthAnythingV2)
- HED
- Pidi
- Scribble
- Ted
- Canny
- Lineart
- Anime_lineart
- MLSD
- Normal
- Segment

![ss3](https://github.com/user-attachments/assets/14bb781b-4966-435b-afa4-87d6aa71c60f)

![preprocessor_examples_1](https://github.com/user-attachments/assets/8eb55a5c-deb9-4193-be68-bd81f069e64a)

![ss4](https://github.com/user-attachments/assets/968f8c2a-bc0c-4890-b1a2-5b910cac1d32)
