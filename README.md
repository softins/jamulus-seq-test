# jamulus-seq-test

This is a temporary project to host Mac and PC builds of Jamulus. It will be taken down once the official versions of 3.6.0 are released.

It now holds the Mac build of Volker's implementation of audio sequence numbering.
Note that it is different from the previous implementation that was in this repository.

There is no longer a checkbox to turn sequencing on and off. If the client is connected to a server
running 3.6.0, audio sequencing will be turned on automatically. If it is connected to an older server,
no audio sequencing will be in effect, and operation will be according to previous versions.

These clients will report their version number as **3.6.0** and are built from the release code, in advance of the official clients becoming available at SourceForge.

To use sequence numbering with a compatible server, the server must show version 3.6.0 or later when viewed at http://jamulus.softins.co.uk

### Mac version

1. Download https://github.com/softins/jamulus-seq-test/raw/master/Jamulus-3.6.0-installer-mac.dmg

2. Open the downloaded file, which will mount the image and launch the installer.

3. In the install window, select both server and client icons and drag them to the Applications folder.

### PC version

This file is not an automatic installer. When the official client is released, it will be.

To install this version manually:

1. Download https://github.com/softins/jamulus-seq-test/raw/master/Jamulus-3_6_0-32bit.zip

2. Extract the contents of the Zip file, which will create a folder called `Jamulus-3_6_0-32bit`

3. Move this folder to inside either `c:\Program Files (x86)` (if it exists) or `c:\Program Files` (otherwise)

4. Within the above program files directory, rename `Jamulus` to `Jamulus.old` (if there was a previous installation of Jamulus), and then rename `Jamulus-3.6.0-32bit` to `Jamulus`.

5. After step 4, existing shortcuts to Jamulus should work.

### Server compilation on Linux

1. Clone the project branch with the command:

```
git clone -b r3_6_0 https://github.com/corrados/jamulus.git jamulus
```

(or just download https://github.com/corrados/jamulus/archive/r3_6_0.tar.gz and extract)

2. Change to the `jamulus-r3_6_0` directory and compile in the normal way.
