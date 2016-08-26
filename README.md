# Mark-10 Testware
MATLAB based Mark10 Load Frame Control Software

(c) 2016 Andrew Petersen and the Stebner Research Group


# Instructions

 1.  You will need some external software and programs before starting.
  * A C/C++ compiler supported by your version of MATLAB. R2016a found here [2016a Compiler List](http://www.mathworks.com/support/compilers/R2016a/)
  * The Mark10 USB Drivers found here [Mark-10 USB Driver](http://www.mark-10.com/downloads.html)
  * The 2015 Visual C++ Redistributable (contains the runtimes for the imageing controller) found here [2015 VC++ Redistributable](https://www.microsoft.com/en-us/download/details.aspx?id=48145)
  * The Basler Pylon 5 Software Suite (for camera control and other utilities) found here [Pylon 5 for Windows](http://www.baslerweb.com/en/products/software/pylon-windows). Note: When installing Pylon, choose the option for **developer**, as well as the camera types you will use (USB or GigE)
 2. Download all files into a directory of your choosing
 3. Open MATLAB and set the working directory to the location of your downloaded files
 4. RUN `mark10_interface_v2.m` to open the application.

For more detailed information, see the [Wiki](https://github.com/beamteamco/M10-Testware/wiki)
