# jamulus-seq-test

This is a temporary project to host Mac and PC builds of Jamulus
with the audio sequencing modifications from https://github.com/softins/jamulus/tree/sequence-audio

There is a checkbox in the Settings window **Enable Sequence Numbers**. This is only in the test versions of the client,
and enables the audio to be compared with and without sequence numbering. If sequence numbers are enabled when connected
to a non-compatible server, the audio will just go silent.

These clients will report their version number as **3.5.12git-softins**. To use sequence numbering with a compatible
server, the server must also report the same version number when viewed at http://jamulus.softins.co.uk

### Mac version

1. Download https://raw.githubusercontent.com/softins/jamulus-seq-test/master/Jamulus-sequence-audio-mac.tar.gz into an empty directory.

2. Do `tar -xzvpf Jamulus-sequence-audio-mac.tar.gz` which will create the directory `Jamulus.app`

3. Run the client with the command `Jamulus.app/Contents/MacOS/Jamulus`

### PC version

1. Download https://raw.githubusercontent.com/softins/jamulus-seq-test/master/Jamulus-sequence-audio.zip into an empty folder.

2. Unzip the file into the same folder. This will create two sub-folders, one for 32-bit and one for 64-bit.

3. Change to the 32-bit or 64-bit folder according to your PC.

4. Run the client program `Jamulus.exe`

### Server compilation on Linux

1. Clone the project branch with the command: ```
git clone -b sequence-audio https://github.com/softins/jamulus.git jamulus-test
```

2. Change to the `jamulus-test` directory and compile in the normal way.
