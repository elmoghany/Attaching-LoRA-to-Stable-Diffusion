# Attaching LoRA into Stable Diffusion to finetune the model

## LoRA Architecture
![picture](LoRA-Data/LoRA-architecture.png)

# 1. Using Naruto Blip Dataset
[lambdalabs/naruto-blip-captions](https://huggingface.co/datasets/lambdalabs/naruto-blip-captions)

## SDXL Results
### Before Finetuning
![picture](LoRA-Data/LoRA-naruto-blip/SDXL-Before-Training.png)

### Dataset Sample
![picture](LoRA-Data/LoRA-naruto-blip/Dataset-Images-Sample.png)

## LoRA Results
### After Finetuning with LoRA
![picture](LoRA-Data/LoRA-naruto-blip/After-LoRA.png)

# 2. Using Cubism Art Dataset
[iamkaikai/CUBISM-ART](https://huggingface.co/datasets/iamkaikai/CUBISM-ART)

## SDXL Results
### Before Finetuning
![picture](LoRA-Data/artistic-custom/SDXL-Before-Training.png)

### Dataset Sample
![picture](LoRA-Data/artistic-custom/Dataset-Images-Sample.png)

## LoRA Results
### After Finetuning with LoRA
![picture](LoRA-Data/artistic-custom/After-LoRA.png)

### Disclaimer:
1. All of the code is inside the Jupyter notebook file.
2. Parts of the code are copied from unsolved assignments of Prof. Minhyuk Sung @ KAIST, a graduate course about diffusion models.
3. Work is done during KAUST internship with KAUST GPUs @ Prof. Mohamed Elhoseiny Lab, as part of the learnings to create a diffusion project.
