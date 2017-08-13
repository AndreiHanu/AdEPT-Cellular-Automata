# AdEPT Gamma Ray Reconstruction

This repository contains software for detection, reconstruction, and categorization of gamma ray events to be collected by the Advanced 
Energetic Pair Telescope (AdEPT), currently being developed by NASA.

**Software Setup**

---

To use the software in this repository, Python 3.6 and OpenCV will be required.
It is recommended that the developer us the Anaconda environment for development of this software, as it allows for virtual environments, 
which my aid in swtiching between software developed in Python 2.7 and software developed in Python 3.6.

At a minimum, the developer requires OpenCV, Python (2.7 or 3.6), and Jupyter Notebook. Additional packages may be required.

**Software Execution**

---

The current notebook listed as "AdEPT Gamma Ray Reconstruction.ipynb" takes two images (XZ & YZ projections) or binary streaming data as
inputs. The binary data and images can be found in their respective locations inside the "Data" directory. Upon execution, the software 
will attempt to find gamma rays in the images or binary streaming data.

Upon completion, several PDF documents are created containing the 
results of the software analysis. Output will originally be stored in the "Output" directory, and it should also be noted that several test 
cases have been run on the provided images and binary streaming data, and are found within their own respective directories within this 
Output directory.

**Future Development**

---

Gamma ray categorization and 3D reconstruction have yet to be implemented.

It should also be noted that as of the current version of this software, only simulated data has been used. Experimental data taken from the 
AdEPT detector may yield different results, and so the software may require calibration to account for the differences in input data.
