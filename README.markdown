MagTek Credit Card Reader in Linux
==================================

This code was written for MagTek USB Swipe Readers part numbers are 21040101, 
21040102, 21040103, 21040104, 21040113, 21040114, 21040119, 21040139, and 
21040143. You can find this part number on the bottom of the device.

Read a complete description of this example program on 
[my blog](http://www.micahcarrick.com/credit-card-reader-pyusb.html)


### Setup Notes for Requirements

For Ubuntu >= 10 (most likely)

	sudo apt-get install python libusb-dev zip

	cd /tmp

	wget http://downloads.sourceforge.net/project/pyusb/PyUSB%201.0/1.0.0-beta-1/pyusb-1.0.0b1.zip

	unzip pyusb-1.0.0b1.zip

	cd pyusb-1.0.0b1

	sudo python setup.py install



Now clone the repo, edit `magtek-pyusb.py` to set the `VENDOR_ID` and `PRODUCT_ID` and then run `python magtek-pyusb.py`
