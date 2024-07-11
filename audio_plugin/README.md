This is the ALSA audio plugin we use.

## Build dependencies

	$ dpkg --add-architecture armhf
	$ apt install build-essential make cmake g++-arm-linux-gnueabihf
	$ apt install libasound2-dev:arm64 libasound2-dev:armhf
