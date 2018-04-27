# Radio
Just some music .wav or .mp3 for raspberry pi radio

## Having the files
After the download you need to unzip the zip file with:
unzip master.zip
than you'll see the directory radio-master and to place the .wav/.mp3 in your radio directory you'll need the command:
find /home/pi/radio-master -type f -print0 | xargs -0 mv -t /home/pi/"radio directory"
