
<p align="left">
<a href="#logo" name="logo"><img src="https://raw.githubusercontent.com/bionanoimaging/UC2-GIT/master/IMAGES/UC2_logo_text.png" width="400"></a>
</p>

# openUC2 *XIAO Camera Module*
---

This repository will help you to build and setup *a SEED XIAO camera module based on the ESP32S3 camera module featuring an OV2640 camera sensor*.


<p align="center">
<a href="#logo" name="logo"><img src="./IMAGES/xiao_1.jpg" width="600"></a>
</p>

Curious to see what this looks like? Keep scrolling!


***Features:***
* adds a digital camera to the UC2 System
* enables sharing your results easily



## In-Action

By adding a microscope objective lens, a folding mirror and a torch, a simple compound microscope can be created:

<p align="center">
<a href="#logo" name="logo"><img src="./IMAGES/xiao_8.jpg" width="600"></a>
</p>


# Software

The source code for the camera can be found here: https://github.com/beniroquai/SeeedStudio-XIAO-ESP32S3-Sense-camera

The online flashing tool to flash the software can be found here: https://matchboxscope.github.io/firmware/FLASH.html

Additional information about the camera module can be found here: https://wiki.seeedstudio.com/xiao_esp32s3_getting_started

# Hardware

Below we describe how the device can be build and assembled in order to replicate the whole system as shown in the rendering above. One needs additional parts that can be found in the core [openUC2 repository](https://github.com/bionanoimaging/UC2-GIT).

## Bill of material

Below you will find all components necessary to build this device

### 3D printing files

All these files need to be printed. We used a Prusa i3 MK3 using PLA Prusament (Galaxy Black) at layer height 0.3 mm and infill 20%.


|  Type | Details  |  Price | Link  |
|---|---|---|---|
| Base | Base Holder for the camera |  1,00 € | [Part.stl](./STL/)  |
| Plate | Base Plate for the camera |  1,00 € | [Part.stl](./STL/)  |


### Additional parts

This is used in the current version of the setup

|  Type | Details  |  Price | Link  |
|---|---|---|---|
| Xiao Sense | Represents the digital camera |  15 € | [Xiao]()  |
| Screw | Din912 |  1 € | [Xiao]()  |

### Design files

The original design files are in the [INVENTOR](./INVENTOR) folder. *FOR ANOTHER FORMAT, GET YOUR OWN FOLDER.*


### Electronics

*COMING SOON*

### Assembly of the DEVICE

***1.*** *These are the parts needed for the ESP32-based camera. Remove the camera lens from the ESP32*


<p align="center">
<a href="#logo" name="logo"><img src="./IMAGES/xiao_3.jpg" width="600"></a>
</p>

***2.*** *These are the parts needed for the ESP32-based camera*

<p align="center">
<a href="#logo" name="logo"><img src="./IMAGES/xiao_7.jpg" width="600"></a>
</p>

<p align="center">
<a href="#logo" name="logo"><img src="./IMAGES/xiao_2.jpg" width="600"></a>
</p>



## Get Involved

This project is open so that anyone can get involved. You don't even have to learn CAD designing or programming. Find ways you can contribute in  [CONTRIBUTING](https://github.com/openUC2/UC2-GIT/blob/master/CONTRIBUTING.md)


## License and Collaboration

This project is open-source and is released under the CERN open hardware license. Our aim is to make the kits commercially available.
We encourage everyone who is using our Toolbox to share their results and ideas, so that the Toolbox keeps improving. It should serve as a easy-to-use and easy-to-access general purpose building block solution for the area of STEAM education. All the design files are generally for free, but we would like to hear from you how is it going.

You're free to fork the project and enhance it. If you have any suggestions to improve it or add any additional functions make a pull-request or file an issue.

Please find the type of licenses [here](https://github.com/openUC2/UC2-GIT/blob/master/License.md)

REMARK: All files have been designed using Autodesk Inventor 2019 (EDUCATION)


## Collaborating
If you find this project useful, please like this repository, follow us on Twitter and cite the webpage! :-)
