AMD fglrx-core-15.201
=================

16-09-2015

fglrx-core-15.201, source + patches compiled on 64bit system, kernels:

4.4.8

Install steps
=================

1 . Download latest catalyst 15.9 and unpack it by command (this will create a folder like fglrx-install.XXXXXXX):

```bash
./AMD-Catalyst-15.9-Linux-installer-15.201.1151-x86.x86_64.run --extract
```

2 . Clone patched code

```bash
cd fglrx-install.XXXXXXX

cd common/lib/modules/fglrx/

rm -rf build_mod

git clone https://github.com/llazzaro/catalyst_15.9_kernel4.4.git build_mod
```

3 . go to root of fglrx-install.XXXXXXX folder

```bash
sudo ./ati-installer.sh 15.201 --install
```

Done!!

