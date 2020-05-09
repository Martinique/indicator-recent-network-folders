# indicator-recent-network-folders
Indicator menu listing your recently edited folders on network servers, using data from ~/.local/share/recently-used.xbel. Currently supports AFP, FTP(S), SMB, SSH and WebDAV.

Installing:

    wget https://github.com/Martinique/indicator-gnote/raw/master/indicator-gnote
    chmod +x indicator-recent-network-folders
    sudo mv -f indicator-recent-network-folders /usr/local/bin

Usage:

     indicator-recent-network-folders

To set maximum number of folders listed (default 20), use -c (or --count):

     indicator-recent-network-folders -c 30

Normally clicked folders are opened in the default file manager, but you can specify another with --browser:

     indicator-recent-network-folders --browser nautilus
