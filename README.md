autoreload
==========

Autoreload is small script to reload process. Use inotify on linux. 

To use autoreload for Linux:
--------------------------------
1. Make sure the script is executable by running chmod +x autoreload

2. Run `./autoreload <path> <ext1,ext2,extn> <cmd> `

e.g: `$ ./autoreload '.' '.py,.xml,.conf' './openerp-server -c openerp-server.conf'`


To use autoreload for windows:
--------------------------------

Run `autoreload.py <path> <ext1,ext2,extn> <cmd> `

e.g: `python autoreload "./openerp" ".py,.xml" "python openerp-server -c openerp-server.conf"`

