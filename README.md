# Tamper_Detection_Localization_Recovery
Objective is to detect whether the image or video is tampered or not if tampered then it localized at which portion it is Tamperd and then after it recovery the tampered portion.
collect the dataset from different sources 
train the model using CNN and ViT model and classify 
Apply SSIM  and PSNR for Localization Finally
Apply DWT for Tampering Recovery.


(ViT workflow)

Input Image (3x224x224)
|
Split into 16x16 Patches (196 patches)
|
Flatten Patches → Linear Projection (Embedding)
|
Add [CLS] Token + Position Embeddings
|
Transformer Encoder (L=12 layers)
|
[CLS] Token (Pooler Output) → Global Tampering Features
|
Classification Head (Tampered/Authentic)


![image](https://github.com/user-attachments/assets/c6a26805-e3f4-4107-976b-36cc0c2b581e)

![image](https://github.com/user-attachments/assets/b1552b45-1076-4845-a811-b104585386f2)

![image](https://github.com/user-attachments/assets/ffa7acb3-9db7-4518-97c9-f14ec60fa3f2)
![image](https://github.com/user-attachments/assets/b4228d4a-3d32-4c9f-9448-056b642f8ffb)








