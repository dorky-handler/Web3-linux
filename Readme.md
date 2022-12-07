
# Web3 Linux initial repository

This repository contains instruction on downloading and configuring Solana Linux OS Distribution.


## Instructions
1. Install Virtualbox from https://www.virtualbox.org/wiki/Downloads.
Choose the install package according to your host OS and architecture.

2. Download the virtualbox disk file and image file.
contents.
https://drive.google.com/file/d/1iFLSZT7JJoqm1d0E0Yc3Fk0Lv_CBkfni/view?usp=sharing

3. Extract the downloaded archive. Move the disk image to a removable media or to a folder of your choice.

4. To run the OS inside virtualbox , navigate to the folder containing the VM image.

5. Double click on the file , “Web3-linux.vbox”

6. Once the VM boots , lightdm will ask you for username/password combo.
Default root password : password

First user : Web3
password : password

7. The VM comes with VS Code pre-installed. It also contains 
* Rustc
* Node.js
* Solana-cli binary

Essentially it contains all the dependencies and packages required to start working on Solana contracts and dapps without the additional baggage of OS's like Ubuntu , thanks to the small storage size of this distro.

## Coming soon
Live CD image and iso files for installing the OS graphically on any systems.
