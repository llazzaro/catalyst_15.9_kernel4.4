AMD fglrx-core-15.201
=================

16-09-2015

fglrx-core-15.201, source + patches compiled on 64bit system, kernels:

3.19.0-29-generic ( Ubuntu 15.04 ),
4.1.7,
4.2.0,
4.3.0-rc1
4.4.8

Install steps
=================

If you want do it:
Download master.zip from kolasa github site: https://github.com/kolasa/fglrx-core-15.201
2 . Download latest catalyst 15.9 and unpack it by command (this will create a folder like fglrx-install.XXXXXXX):
./AMD-Catalyst-15.9-Linux-installer-15.201.1151-x86.x86_64.run --extract
3 . Clone patched code
cd fglrx-install.XXXXXXX
cd common/lib/modules/fglrx/
rm -rf build\_mod
git clone https://github.com/llazzaro/catalyst\_15.9\_kernel4.4.git build\_mod
4 . go to root of fglrx-install.XXXXXXX folder
sudo ./ati-installer.sh 15.201 --install

Done!!

