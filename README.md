# BAIT - Biofilm Architecture Inference Tool

Update 9/17/20: A new version of BAIT, which we call BAIT-T, is being developed. Pending review, the full version will be available shortly.

BAIT is a image analysis software program that can be used to quantify the architecture of oral multi-species biofilms. BAIT can calculate a variety of features, such as surface area, fluffiness, connectivity, and convex hull porosity. For more information about BAIT, please see:

Luo et al. 2019. Introducing BAIT (Biofilm Architecture Inference Tool): a software program to evaluate the architecture of oral multi-species biofilms. Microbiology, in press.

**Release versions (standalone and installers)** may be found [here](https://github.com/epimath/BAIT_software/releases). 

Current releases are compiled for Microsoft Windows. MacOS and Linux users with MATLAB may compile executables from the .mlapp source code files. See Bait_documention.pdf for installation and usage instructions.

Questions? Please contact Ting Luo (tingluo@umich.edu), Michael Hayashi (mhayash@umich.edu), Marisa Eisenberg (marisae@umich.edu), or Alexander Rickard (alexhr@umich.edu). 

----

### Troubleshooting
Make sure that the 9.4 (R2018a) version of the MATLAB Runtime is installed if you are using the standalone executables. Web installer versions should download the runtime during installation.
 
Before using BAIT, make sure the scale of the desktop is set to 100% in the Display settings Window. BAIT will be partially off the monitor screen if this is not set correctly.

BAIT must load the MATLAB Runtime when it starts up for the first time, as a result the first load can take 30 seconds to a minute.
 
Depending upon the imaging system and file types, the use of BAIT will require additional software.  For example, to convert files to Matlab executables for analysis in BAIT, the software program ICY (icy.bioimageanalysis.org) can be used.
 
 
### Tips for Use
For viability measurements, make sure the correct channels are assigned (1: Red, 2: Green).
 
Check that image stacks are in 8 bit as these are best suited for thresholding with BEM.
 
Check that the  image stacks are the same resolution.

### Release Version Notes
Version 1.1: Please note, Version 1.1 of BAIT is transitional.  
-- Added Manual Thresholding option  
-- Added merged analysis when 2 channel data is selected  
-- Added batch (thresholding + structure) analyses

Version 1.0:  
-- Thresholding using BEM, Otsu's Method, or Iterative Selection  
-- 1 or 2 channel analysis  
-- Structural outcomes: Biovolume, number of objects, surface area, fluffiness, connectivity, convex hull porosity, viability  
-- Export to CSV
 
### Recommended System:
OS: Windows 10  
CPU: Intel Core architecture or equivalent AMD, (e.g. Core 2 Duo and newer, AMD Phenom II and newer)  
RAM: 4 GB (More may be needed for large image files)

