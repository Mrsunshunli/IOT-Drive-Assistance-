### RPI, Unix Speed Camera Using python, openCV, USB Cam or RPI camera module That Use For Drivers To Assist their Driving
## For Details See 
https://drive.google.com/open?id=1_K1laW7n0HnZr_7hTFHpYlVe8Nf93GiT

## Program Description   
This is a raspberry pi, Unix Distro computer openCV object speed carema and Produce Voice Commands to Assist the Drivers for example reduce the speed if  there is chance of collision.
It is written in python and uses openCV to detect and track the x,y coordinates of the 
 moving object in the camera view above a minimum pixel area.
User variables are stored in the [***config.py***] file.
Motion detection is restricted between ***y_upper***, ***y_lower***, ***x_left***, ***x_right*** variables  (road or area of interest).
If a track is longer than ***track_len_trig*** variable then average speed will be 
calculated based on ***cal_obj_px*** and ***cal_obj_mm*** variables and a speed photo will be
taken and saved in ***media/images*** dated subfolders per variable ***imageSubDirMaxFiles*** = ***1000*** 
(see config.py). If ***log_data_to_CSV*** = ***True*** then a
***speed-cam.csv*** file will be created/updated with event data stored in
CSV (Comma Separated Values) format. This can be imported into a spreadsheet, database, Etc program for further processing

Also included are profile.txt which will record the distance between Vechiles and thier speeds 
  
## Requirements
**Raspberry Pi computer*** and a ***RPI camera module installed***
or USB Camera plugged in. Make sure hardware is tested and works. Most [RPI models] will work OK. 
A quad core RPI will greatly improve performance due to threading. A recent version of 
[Raspbian operating system](https://www.raspberrypi.org/downloads/raspbian/) is Recommended.   
  
***OBD Scanner ELM327***
On-board diagnostics (OBD) is an automotive term referring to a vehicle's self-diagnostic and reporting capability. OBD systems give the vehicle owner or repair technician access to the status of the various vehicle subsystems.
The latest python versions include numpy and recent opencv that is required to run this code. 
You will also need a USB web cam installed and working for unix  Distro Computers. 
## Working 
Step1:- 
Install OpenCV <br />
to install openCV  
https://github.com/pageauc/opencv3-setup
Step2:- <br />
Install OBD <br />
Command for installing obd <br />
 pip install obd <br />
Step3:-<br />
 Connect OBD with Raspberry pi via BlueTooth just need to pair 1st time<br />  
Step4:-<br />
 Connect Speaker using Aux cable with Raspberry pi3 
<br />
## Credits  
The IOT Research Lab<br />
PUCIT <br />

 
Some of this code is based on a GitHub Repo  https://github.com/pageauc
  
Have Fun   
MCSF16 Legends

For More Information [Mail Me](mshoaib889@gmail.com)