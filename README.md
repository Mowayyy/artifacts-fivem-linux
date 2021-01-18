# artifacts-fivem-linux

1. Create a new folder (for example mkdir -p /home/username/FXServer/server), this will be used for the server binaries.
2. Download the current recommended master branch build for Linux from the artifacts server(copy the URL for the latest server version and use wget <url> to download it).
3. Extract the build to the directory that was previously created, using cd /home/username/FXServer/server && tar xf fx.tar.xz (you need to have xz installed, on Debian/Ubuntu        this is in the xz-utils package).
4.Clone cfx-server-data in a new folder outside of your server binaries folder.
4b. For example git clone https://github.com/citizenfx/cfx-server-data.git /home/username/FXServer/server-data

[I'm an inline-style link](https://www.google.com)
