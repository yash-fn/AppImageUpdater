* Please make sure to have appimageupdatetool-x86_64.AppImage installed in your application directory. The script relies on it. 
* Also ensure to have wget, curl, bash, lynx, and any other such commands you see in the script.
* Place script with executable privelages and mode in same application directory as AppImages wishing to be updated. Suggest you add app direcetory to PATH variable for easy updates via command line. 
* The script will then change directory to location of script file itself and then update any appimages it finds in teh same directory. 
* Apps that the auto update tool cannot update can be manually updated by adding another entry appX with the appropriate name and link where appimage can be downloaded. It will then compare filenames to get the leatest appimage. 
