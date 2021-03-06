# Sentinel_Radiometric_Calibration_Tool
This repository contains script for performing radiometric calibration of point targets for Sentinel-1 Imagery.

## Toolbox
GUI

![GUI](https://github.com/shubhamsharma1609/Sentinel_Radiometric_Calibration_Tool/blob/main/images/11.PNG)


### Working
Instructions
![Inst](https://github.com/shubhamsharma1609/Sentinel_Radiometric_Calibration_Tool/blob/main/images/12.PNG)

Sentinel-1 VV Image
![image](https://github.com/shubhamsharma1609/Sentinel_Radiometric_Calibration_Tool/blob/main/images/13.PNG)

Corner Reflectors
![CR](https://github.com/shubhamsharma1609/Sentinel_Radiometric_Calibration_Tool/blob/main/images/14.PNG)

Annotation File
![anno](https://github.com/shubhamsharma1609/Sentinel_Radiometric_Calibration_Tool/blob/main/images/15.PNG)

Calibration File
![calib](https://github.com/shubhamsharma1609/Sentinel_Radiometric_Calibration_Tool/blob/main/images/16.PNG)

### Processing

![calib](https://github.com/shubhamsharma1609/Sentinel_Radiometric_Calibration_Tool/blob/main/images/17.png)

![calib1](https://github.com/shubhamsharma1609/Sentinel_Radiometric_Calibration_Tool/blob/main/images/18.png)

![calib2](https://github.com/shubhamsharma1609/Sentinel_Radiometric_Calibration_Tool/blob/main/images/19.png)

![calib3](https://github.com/shubhamsharma1609/Sentinel_Radiometric_Calibration_Tool/blob/main/images/20.png)

## Installation requirements :
The tool has been tested with the following : 
* Python (ver 3.5+)
* GDAL ( ver. 2.0.3)
* Numpy( ver. 1.11.1)
* matplotlib(ver. 1.5.3)
* scipy (ver. 0.18.1)
* mpldatacursor(ver. 0.6.2)
* tkinter (ver. 8.5.18)
* scikit-image(ver. 0.12.3)

The tool does not require any other open source software and is built from scratch utilising the above libraries/packages.


## Data Utilised
For Demonstration purpose,the Sentinel-1 IW(Interferometric Wide Swath mode) GRD(Ground Range Detected) data is used with Identifier  S1A_IW_GRDH_1SDV_20180206T010949_20180206T011014_020479_023059_419C and the corner reflectors utilised are Triangular Trihedral.
The data can be downloaded from [esa-scihub-copernicus](https://scihub.copernicus.eu/dhus/#/home)


## Calibration Steps
Please follow the Radiometric Calibration document carefully for successful calibration.



