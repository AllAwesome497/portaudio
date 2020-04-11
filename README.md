# portaudio

This package provides an interface to the [PortAudio](http://www.portaudio.com/) audio I/O library.  See the [package documentation](http://godoc.org/github.com/gordonklaus/portaudio) for details.
Forked of (http://godoc.org/github.com/gordonklaus/portaudio
# Install
First you need to uninstall `portaudio19-dev` if you have it installed with `apt-get install portaudio19-dev` because it does not have the archive file.

Enter tmp directory: `cd /tmp`
Download the newest version of portaudio [here](http://www.portaudio.com/download.html). 
Extract the tar file: `tar -xf pa_*.tgz`.  
Enter portaudio directory: `cd portaudio`
Install: `./configure --enable-static=yes --enable-shared=false && make install`
