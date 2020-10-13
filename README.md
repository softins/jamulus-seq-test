# jamulus-seq-test

This is a temporary project to host Mac and PC builds of Jamulus
with the audio sequencing modifications from https://github.com/softins/jamulus/tree/sequence-audio

There is a checkbox in the Settings window **Enable Sequence Numbers**. This is only in the test versions of the client,
and enables the audio to be compared with and without sequence numbering. If sequence numbers are enabled when connected
to a non-compatible server, the audio will just go silent.

### Mac version

1. Download https://raw.githubusercontent.com/softins/jamulus-seq-test/master/Jamulus-sequence-audio-mac.tar.gz into an empty directory.

2. Do `tar -xzvpf Jamulus-sequence-audio-mac.tar.gz` which will create the directory `Jamulus.app`

3. Run the client with the command `Jamulus.app/Contents/MacOS/Jamulus`

### PC version

1. Download https://raw.githubusercontent.com/softins/jamulus-seq-test/master/Jamulus-sequence-audio.zip into an empty folder.

2. Unzip the file into the same folder. This will create two sub-folders, one for 32-bit and one for 64-bit.

3. Change to the 32-bit or 64-bit folder according to your PC.

4. Run the client program `Jamulus.exe`
