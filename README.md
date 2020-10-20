# jamulus-seq-test

This is a temporary project to host Mac and PC builds of Jamulus

It now holds the Mac build of Volker's implementation of audio sequence numbering.
Note that it is different from the previous implementation that was in this repository.

There is no longer a checkbox to turn sequencing on and off. If the client is connected to a server
running 3.6.0, audio sequencing will be turned on automatically. If it is connected to an older server,
no audio sequencing will be in effect, and operation will be according to previous versions.

These clients will report their version number as **3.6.0git-seqtest**. To use sequence numbering with a compatible
server, the server must also report the same version number when viewed at http://jamulus.softins.co.uk

### Mac version

1. Download https://raw.githubusercontent.com/softins/jamulus-seq-test/master/Jamulus-3.6.0git-seqtest.tar.gz into an empty directory.

2. Do `tar -xzvpf Jamulus-3.6.0git-seqtest.tar.gz` which will create the directory `Jamulus.app`

3. Run the client with the command `Jamulus.app/Contents/MacOS/Jamulus`

### PC version

The PC build of this version is not hosted here, but can be downloaded from http://llcon.sourceforge.net/Jamulus-3.6.0beta-installer.exe

### Server compilation on Linux

1. Clone the project branch with the command:

```
git clone -b feature_sequence_numbers https://github.com/corrados/jamulus.git jamulus-feature_sequence_numbers
```

(or just download https://github.com/corrados/jamulus/archive/feature_sequence_numbers.zip and extract)

2. Change to the `jamulus-feature_sequence_numbers` directory and compile in the normal way.
