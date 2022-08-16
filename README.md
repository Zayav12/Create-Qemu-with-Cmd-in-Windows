# Create-Qemu-img

# Warning

- Like another project, this for only education only

- you were warning

------------------------------------

Hi, this github project is created by Ngoc Hai Windows, if you already know how to install
this will useless

This create Step by Step

# Method 1:

1. Install qemu in qemu.org

2. Open the File you Installed from qemu.org [while you install qemu, choose place to qemu like: "C:\qemu_x86-64 ; D:\"]

3. Go to  File Explorer > This PC "Computer" > System Properties > Advanced System Setting > close the cancel button is Environment Variables > In the User variables box, double-click the Path variable, click New, and then paste the QEMU path you installed

4. Open Cmd as Administrator, type this command: cd [your place you install qemu like: c:\qemu...]

5. type: qemu-img create -f qcow2 windows[ubuntu ; Macos or linux].img 40G

before go to step 6 make sure you download ISO file of os to ready

6. type: qemu-system-x86_64.exe -m 1G -smp 2 -boot order=dc -hda windows[ubuntu ; Macos or linux].img -cdrom “[your place you installed ISO like: D:\Iso\windows.iso]"

Cmd will auto open qemu-system-x86_64.exe, This VM will boot on cd\dvd to setup

# Method 2:

1. link:

*https://www.carlavilla.es/qtemu/qtemu_setup_x86_64.exe

2. when you installed qtemu, create new kvm

before go to step 3, like the method 1. Download iso file

3. click cd/dvd from the kvm you created

now you can use it, click start to setup

____________________________________________

If you don't know, this video will help you:

# Dont have, sorry

Support Owner project

https://www.youtube.com/channel/UCATrxvrKRMf_6pqXptgXkAw
