# Beta adaptation Green Recorder glib-2.31 migration build python3 gnome-screencast minimum problem audio output

# Green Recorder wayland rec

Ubuntu package deb amd64 green-recorder download: https://github.com/Griggorii/green-recorder_ubuntu_20.04_source/releases/tag/ubuntu_20.04

Rebuild source and edited and fix tutorial:

Install new python prof rebuild https://github.com/Griggorii/python3.8.5_20.04_new_rebuild_amd64.deb/releases/tag/python3.8.5_20.04_amd64.deb

$ sudo rm /usr/bin/python3

$ sudo ln -s /usr/bin/python3.8 /usr/bin/python3

Rub build install dependency folder source terminal run:

$ dpkg-buildpackage -rfakeroot -b
    
Original source: https://github.com/mhsabbagh/green-recorder


    
    
   




