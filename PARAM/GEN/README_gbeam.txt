The gbeam.param file contains information on the beam position and raster. The lastest version in git is NOT always ideal. One needs to use the corresponding gbeam.param with the appropriate run period. Currently, there are three files:
1. gbeam_winter17.param (exp: commissioning in Dec 2017)
2. gbeam_spring18.param (exp: CT, F2, x>1, SIDIS)
3. gbeam_fall18.param (exp: CSV, KAON-LT)

The gbeam.param file is currently the same as the gbeam_fall18.param (latest) file. 

Update for NPS 10/27/2023
The file gbeam_fa23.param contains the Hall C BPM A, B, and C values taken from harp scans vs bpm in Sept/Oct 2023.  
The file gbeam_fa22.param contains the fall 2023 updated values as well as the earlier values (commented out).  Currently, the various replay scripts call for gbeam_fa22.param.  This can and should be simplified in the future. 
