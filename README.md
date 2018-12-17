portaudio
=========

This project is forked from the [official portaudio](https://app.assembla.com/spaces/portaudio/git/source) repository.  
Slight changes have been added to build it seamlessly on recent versions of macOS.  
Tested on Mojave using the version 10.14 of the xcode SDK, as a requirement for [PyAudio](https://people.csail.mit.edu/hubert/pyaudio/).

Build on MacOS
--------------

```sh
git clone git@github.com:ggueret/portaudio.git
cd portaudio/
./configure --disable-mac-universal
make
sudo make install
```