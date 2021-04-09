# Beta adaptation Green Recorder glib-2.31 migration build python3 gnome-screencast minimum problem audio output

# Green Recorder wayland recorder

Ubuntu 21.04 Hirsute deb amd64 green-recorder download: https://github.com/Griggorii/green-recorder_ubuntu_20.04_21.04_source/releases/download/ubuntu_20.04/green-recorder_3.2.2-0ubuntu_21.04_all.deb

Ubuntu 20.04 disco deb amd64 green-recorder download: https://github.com/Griggorii/green-recorder_ubuntu_20.04_21.04_source/releases/download/ubuntu_20.04/green-recorder_3.2.2-0ubuntu1_all.deb

Rebuild source and edited and fix tutorial:

Install new python prof rebuild https://github.com/Griggorii/python3.8.5_20.04_new_rebuild_amd64.deb/releases/tag/python3.8.5_20.04_amd64.deb

$ sudo rm /usr/bin/python3

$ sudo ln -s /usr/bin/python3.8 /usr/bin/python3

Rub build install dependency folder source terminal run:

$ dpkg-buildpackage -rfakeroot -b
    
Original source: https://github.com/mhsabbagh/green-recorder

Griggorii@gmail.com только настоящие технологии support real technology new fix

На данный момент не решена проблема записи в wayland webm со звуком , так что запись произведется , но звука может не быть если вы выбрали не правильное звуковое устройство и его аудио выход.


    
    
   




