# simple-ftp
usage:
sending
~/simple-ftp send --addr=ADDRESS --user=USER --pass=PASSWORD --spath=/home/USER/SOMEWHERE --file=FILETOSEND

recieving
~/simple-ftp polling --addr=ADDRESS --user=USER --pass=PASSWORD --spath=/home/USER/SOMEWHERE --file=FILETOSEND --timeout=60000 --interval=5

Credit https://gitlab.com/RenonT1805