# Imperial_PINN

This work conducted at the Imperial College of London was designed to test the generalizability and accuracy of the WarpPINN model designed by Lopez et. al. in 2023 
for cardiac myocardial deformation and strain prediction utilizing MRI images obtained from the Automated Cardiac Diagnosis Challenge Dataset(ACDC) dataset compiled 
by Bernard et al in 2018(please see citations below). The dataset can be accessed and downloaded here: https://www.creatis.insa-lyon.fr/Challenge/acdc/databases.html

The WarpPINN model was modified for compatibility purposes with the ACDC dataset. The resultant image registration was tested for accuracy utilizing the following metrics:
MSE, SSIM, Dice, and MCD. 

WarpPINN Citation:

Arratia López P, Mella H, Uribe S, Hurtado DE, Sahli Costabal F. 
WarpPINN: Cine-MR image registration with physics-informed neural networks. 
Med Image Anal. 2023;89:102925. doi:10.1016/j.media.2023.102925

Automated Cardiac Diagnosis Challenge Dataset Citation: 

O. Bernard, A. Lalande, C. Zotti, F. Cervenansky, et al.
"Deep Learning Techniques for Automatic MRI Cardiac Multi-structures Segmentation and
Diagnosis: Is the Problem Solved ?" in IEEE Transactions on Medical Imaging,
vol. 37, no. 11, pp. 2514-2525, Nov. 2018. doi: 10.1109/TMI.2018.2837502
