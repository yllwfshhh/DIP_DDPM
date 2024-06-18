# DIP_DDPM
GAI HW4 112-2
I run this project on colab.
This DIP model part,it should load dataset from website and generate initial priors, then save them in Google Drive.
initial_priors_500 is the dataset i used for DIP + DDPM.

Load 'Training configuration' at first.

![image](https://github.com/yllwfshhh/DIP_DDPM/assets/91595538/f0fe128d-17f2-4d60-931d-270521f22fd5)

Here is the DDPM part:

![image](https://github.com/yllwfshhh/DIP_DDPM/assets/91595538/6b2434b1-d459-4b4a-a266-386add2d2886)

The difference of DDPM and DIP + DDPM architecture is how to load the dataset.
Choose 'Load the dataset' to run DDPM or 'Load Initial Priors' to run DIP + DDPM.
DDPM use the dataset online while DIP + DDPM run my own generated initial priors folder.

Here's some parts need to change the code manually
For DDPM:
- Create a UNet2DModel
  
![image](https://github.com/yllwfshhh/DIP_DDPM/assets/91595538/9d90323d-b646-4722-8f9a-14d5b7216e70)

- Train the model

![image](https://github.com/yllwfshhh/DIP_DDPM/assets/91595538/d69d1e78-9ff2-4e70-9a52-9dee993ff5ae)

For DIP + DDPM:
- Create a UNet2DModel
  
![image](https://github.com/yllwfshhh/DIP_DDPM/assets/91595538/1c8515b4-c6ae-47f9-ac94-3d08349b0b49)

- Train the model
  
![image](https://github.com/yllwfshhh/DIP_DDPM/assets/91595538/cab76db7-4361-4c8f-88c1-9943205ccee1)




