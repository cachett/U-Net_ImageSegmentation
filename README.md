# U-Net_ImageSegmentation
Implementation of U-net in order to do image segmentation on 3D-brain IRM. Then we compute volume of different tissue (GM, WM, CSF and background)
and get a mean squared error of 6.5 years with a RandomForestRegressor.

![alt text](https://raw.githubusercontent.com/cachett/U-Net_ImageSegmentation/age.PNG)

In a second part we use PCA on the 3D-brain IRM and obtain an MSE of 5.5 years with a LinearRegressor of the PCA features.

