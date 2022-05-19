A PPA repository for package:

- [PAL-USB](https://github.com/DreamVu/PAL-USB)

# Usage

```bash
curl -SsL "https://debashish05.github.io/debashishPPA/KEY.gpg" | sudo apt-key add -
sudo curl -SsL -o /etc/apt/sources.list.d/my_list_file.list "https://debashish05.github.io/debashishPPA/my_list_file.list"
sudo apt update
sudo apt install palusb
```

Provide argument "Y" or "y" for continuing installing the dependencies whenever prompted. 

Then a message will be displayed on the terminal,

"Please select either (Y/N). On selecting 'Y', installation will build the whole software based on the particular Nvidia Jetson architecture and will enable higher performance. This may take a few hours to complete the installation. On selecting 'N', it will quickly build the software by using some of the pre-configured libraries provided. (Y/N)"

Based on the requirement enter the character. In case of rebuilding following are the recommended values for different Nvidia Jetson architectures.

    For Jetson Xavier NX arg2: 3500
    For Jetson Xavier AGX arg2: 8000
    For Jetson Nano arg2: 1000
            
Once complete please reboot the system.
To start the PAL USB, use the command 
    
    ~/DreamVu/PAL-USB/Explorer/Explorer

# Sources

- https://dreamvu.com/
- https://github.com/DreamVu/