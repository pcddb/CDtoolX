# CDtoolX
CDtoolX is a user-friendly, free-to-download-and-use software program that enables processing, displaying, archiving, calibrating, comparisons, and analyses of circular dichroism (CD) and synchrotron radiation circular dichroism (SRCD) spectroscopic data.


## Instructions
Instructions for use are included by clicking the "Help" tab on the top left panel of the software. The downloadable files accompanying the CDtoolX software include an extensive users’ manual. However, the software is designed to be very intuitive and user-friendly so, in general, it can be used without reference to the manual. Users comments/questions can be addressed by emailing cdtools@mail.cryst.bbk.ac.uk.

You can also find further instructions and tutorials on our youtube channel. 
https://www.youtube.com/@ThePcddb/featured


## Windows 10 version 
CDtoolX is for Windows 10 and Windows 8 systems, and is usable on OsX and Linux systems with Windows 10 emulators. It is best to use third party zip programmes such as 7-zip to extract the files. Windows zip functions do not always work. Practice files are included in the test data directory.


## Windows 7 version
CDTool is for Windows 7 operating systems. It is best to use third party zip programmes such as 7-zip to extract the files. Windows zip functions do not always work. Practice files are included in the test data directory


## Updates 

##### V1.12 - 15/11/18 
* Opening Soleil files only: Problem with displaying sample and baseline in the File table fixed

 
##### v1.13 - 16/11/18

* Zero dialog: cancel button added so the dialog can be closed without zeroing if necessary
* Spectra menu: ‘Change smoothing window’ can now be applied to multiple files.
* Save file dialog now navigates via short cuts instead of treating them as files.


##### V1.14 - 08/01/19 

* When saving a two column x,y formatted file as a .gen file, the data rows are formatted incorrectly and the .gen file spectrum cannot be plotted. This has been rectified.


##### V1.15 - 28/02/19

* Fixed an issue with the previous update


##### v1.16 - 07/05/2019

* Opens CD1 (ISA) LD files


##### v1.17 - 16/05/19

* CDToolX will process files if some wavelengths are not at the exact specified intervals. An error of 0.2 nm is allowed. For example:
    * 269, 268, 267.1 is accepted
    * 269, 268, 267.3 is not
* SVD function: when “show result“ button is pressed to carry out SVD on a dataset, the first 5 basis spectra are displayed in a pop up window. These can be saved in either a .csv file or a .txt file. The .txt file can be opened in the main plot window.
* When .gen files are opened the smoothed data column is now read directly, rather than smoothing the raw data afresh and putting that into the smoothed data column. This means that if you change the smoothing window and save the file, when it is reopened the changed data is displayed, rather than freshly smoothed data with the default parameter of 7 data points.


##### v1.8
* New short cut: Open: Ctrl + O


##### V1.9 - 08/04/2020

* New icon for CDToolX shortcut
* ‘Push raw to smoothed’ function added.
    * This will take selected spectra and put the smoothed data column into the raw data column. This is another method along with ‘Change smoothing window’ for cleaning up noisy data.
* Link to svd video in help menu
* When SVD matrices are saved as a .csv file, the bottom row was not included. This has been rectified


##### V 2.0 - 15/05/2020

* Bug in subtracted spectrum error fixed.


##### V2.01 - 19/01/2021

* Scaling CD: Now 4 decimal places allowed so that spectra can be scaled from units of MRE to Delta epsilon
* Links to the following You tube videos in the help menu:
    * Processing CD Data Using CDToolX
    * Setting up the CDToolX database
    * Using the CDToolX Database
    

##### v.2.10 - 22/06/2022

* Bug in spectra table selection fixed