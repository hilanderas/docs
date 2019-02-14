# Install client side

### Step 1: Prepare hardware
All hardware you are going to use:
* One Raspberry Pi 3 Model B
* One case, the transparent one is preferred since you can actually see all the components inside
* One 16GB micro SD card 
* One micro SD card reader
* One USB to RJ45 adapter
* One micro USB power supply cable
* One power usb adapter
* Two Ethernet cables
* One HDMI cable 
{% video %}1_hw_introduction.mp4 {% endvideo %}


** Assemble Raspberry Pi into a case **
{% video %} 3_add_shell_to_rpi.mp4 {% endvideo %}



### Step 2: Install OS to micro SD card
* Insert the micro SD card into a card reader and plug it into a computer USB interface 
{% video %}4_install_os_rpi.mp4 {% endvideo %}


* Install the Operating System(ubuntu 16.04) on to the micro SD card
{% video %}1_install_ubuntu_16.04_arm.mp4{% endvideo %}

### Step 3: Install environment
* Physical setting up our Raspeberry Pi to install dependency on it
{% video %}5_connect_externel_devices_to_rpi.mp4 {% endvideo %}

* Install [dependency for routing](https://hilanderas.github.io/routing/usage/quickstart/DEPENDENCY.html)
* Install [dependency for powter-client](https://hilanderas.github.io/powter-client/en/usage/quickstart/DEPENDENCY.html)
{% video %}2_install_dep_arm.webm {% endvideo %}




### Step 4: Install routing
Refer to **Quick Start** of [routing](https://hilanderas.github.io/routing/)

* Install [routing](https://hilanderas.github.io/routing/usage/quickstart/INSTALL.html)

### Step 5: Install powter-client
Refer to **Quick Start** of [powter-client](https://hilanderas.github.io/powter-client/)

* Install [powter-client](https://hilanderas.github.io/powter-client/en/usage/quickstart/INSTALL.html)


### Step 6: Connect with devices 
* Hopefully by now all the software and hardware are ready, follow the video below to connect cable in right way
{% video %} 6_function_test_rpi.mp4 {% endvideo %}


* Test functionality

	Connect a pc to LAN of Raspberry Pi with an Ethernet cable and visit `www.google.com` 
