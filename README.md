Test vs training sample 
goes from 128x128 to 32 x 32 

<img width="638" height="453" alt="Screenshot 2025-11-08 113942" src="https://github.com/user-attachments/assets/b10cb5fb-5285-4a5c-a0c2-8edf308d9def" />


Using 4x Super res GAN Should upscale 32 x 32 back to 128 x 128

After only 1 epoch ( Train  time is very high due to the depth of the network and limitation of batchsize set to 32 because RTX 4070 only 12 GB ) 

Low res : high res : Super resolution ---> 
EXAMPLE 1 
<img width="745" height="509" alt="image" src="https://github.com/user-attachments/assets/77f03fd5-f478-4e41-89f5-1432f20433e4" />

EXAMPLE 2
<img width="738" height="470" alt="image" src="https://github.com/user-attachments/assets/38f5a554-10ff-4983-b444-c0e4d520dc71" />

EXAMPLE 3 

<img width="687" height="402" alt="image" src="https://github.com/user-attachments/assets/647d39bf-6c28-4295-96ba-c475e64a588a" />



Low res images grid 
<img width="240" height="172" alt="epoch_LowREs0000_HR" src="https://github.com/user-attachments/assets/3b18f409-5855-49a2-a3d3-706f0d7791d3" />

Super resolution Images grid 
<img width="912" height="652" alt="epoch_SuperRes0000_SR" src="https://github.com/user-attachments/assets/3b187b38-d0bb-4614-be94-5d8b0aaf93be" />

Original high res images grid 
<img width="912" height="652" alt="epoch_HighReS0000_HR" src="https://github.com/user-attachments/assets/cd90142f-78a6-4a6f-9c5a-76063cdb1bec" />
