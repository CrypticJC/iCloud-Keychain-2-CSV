# Keychain2CSV
Due to Apple storing the iCloud keychain locally in a highly encrypted format. The more effecive way of exporting this data is to manualy copy and paste each data item into a readable file from the GUI. This script automates this proccess to provide you with a readable .csv storing sites, usernames and passwords.

iCloud Keychain to CSV Script for 10.14 OSX and later. 

This script should be opened with Apple Script Editor and the number of passwords you have saved in safari should be updated wihtin the script. 

Once run, it will open Safari where you input should your password (or scan Touch ID) to unlock the passwords pane. The program will then continue to run through each row for the number of itterations you have specificed. 

When the program has finished itterating. You may simply save the text file as a .csv

