# Beta adaptation Green Recorder glib-2.31

# Green Recorder

$ dpkg-buildpackage -rfakeroot -b

$ sudo ln -s /usr/bin/python2.7 /usr/bin/python2

$ sudo ln -s /usr/bin/python2 /usr/bin/python

    sudo pip install pydbus
    
Original source: https://github.com/mhsabbagh/green-recorder

Variand edit debian/rules replaces standart python string

override_dh_auto_install:
	python3.8 : python3.8d next version
    
    
   




