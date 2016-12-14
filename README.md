# ControlFour

## Synopsis

How to program your ControlFour Controller without Professional or dealer help. This is very specific to 2.8.2.
Prerequesite is a good understanding of Linux.

## Motivation

As dealers are taking the advantage of controlFour customers. 

## Where to Download ControlFour Compo$er Pro
http://update2.control4.com/release/2.8.2.515957-res+Composer/win/ComposerPro-2.8.2.515957-res.exe

## Where to get the Patch for Compo$er Pro
http://www76.zippyshare.com/v/Nte7dzeh/file.html

## Steps
Step 1. Install composer 2.X.X (must first be 2.5.2)
Step 2. Run Composer patch by MeeKaah as admin
Step 3. copy the contents of Director patch to composer install Directory
Step 4. Run ‘patchDirector.exe’ as admin
Step 5. Copy ca.pem and ca_cert.pem from Step3 Folder: C:\Users\\appdata\Roaming\Control4\Composer
Master 2.5.2-2.8.2 guide:
0. Uninstall all Control4 programs and remove the /appdata/Roaming/Control4/Composer directory
1. Installed Composer 2.5.3
2. Run the Meekah patch as Administrator on Composer 2.5.3
3. Run Composer and “registered” with a email/password (some error messages due to the difference of versions of the drivers)
4.Quit Compose
5. Installed Composer 2.7.2(DO NOT OPEN COMPOSER)
5. Run the Meekah patch on Composer 2.7.2
a. Patched the director
6. Installed Composer 2.8.0(DO NOT OPEN COMPOSER)
7. Run the Meekah patch on composer 2.8.0
a. Patched the director
8. Installed Composer 2.8.1 (DO NOT OPEN COMPOSER)
9. Run the Meekah patch on Composer 2.8.1
a. Patched the director
10. Installed Composer 2.8.2 (DO NOT OPEN COMPOSER)
11. Run the Meekah patch on Composer 2.8.2
a. Patched the director

12. you have to edit the ComposerPro.exe.config file… towards the bottom, you have to change the line:
add key~Path value~ComposerProSettings.Config
PRO needs to be changed to HE
add key~Path value~ComposerHESettings.Config
