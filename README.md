# jamulus-seq-test

The official 3.6.0 clients for PC and Mac are now available from [SourceForge](https://sourceforge.net/projects/llcon/files/Jamulus/3.6.0/),
so the interim builds that were hosted here are no longer required.

If the client is connected to a server running 3.6.0, audio sequencing will be turned on automatically.
If it is connected to an older server, no audio sequencing will be in effect, and operation will be according to previous versions.

To use sequence numbering with a compatible server, the server must show version 3.6.0 or later when viewed at http://jamulus.softins.co.uk

### Server compilation on Linux

1. Clone the project branch with the command:

```
git clone -b r3_6_0 https://github.com/corrados/jamulus.git jamulus
```

(or just download https://github.com/corrados/jamulus/archive/r3_6_0.tar.gz and extract)

2. Change to the `jamulus-r3_6_0` directory and compile in the normal way.
