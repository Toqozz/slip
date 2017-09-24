# slip
Slip is a simple bash program that allows screenshotting with maim, and immediate uploading with imgur.

It uses dmenu as a front-end menu, but rofi can also easily be used.

## install
slip is available on the [AUR](https://aur.archlinux.org/packages/slip/).

Copy the slip file to a directory of your choice.   
Make it the file executable with `chmod +x ./slip` (where "./" is your install directory).

## usage
To launch slip, run `./slip` (where "./" is wherever slip is installed).    
Alternatively, don't make the file executable and run slip with `bash ./slip`.

If installed from the AUR, just use `slip`.

## usage

#### screenshot
1. Select 'screenshot.'
2. Select an area or a window.
3. Wait for uploading to complete.
4. An imgur url is copied to the clipboard. 

To skip dmenu entirely and bring up a cursor ready for screenshotting, use `slip --screenshot`

#### recording gifs
1. Select 'gif.'
2. Select an area or window.     
3. When you are finished recording, run slip again and select 'stop.'      
4. Either 'upload,' 'delete,' or 'do nothing' to the saved file.
5. ...

To skip dmenu entirely and bring up a cursor ready for recording a gif, use `slip --gif` to begin recording, and `slip --stop` to stop recording.

#### recording videos
1. Select 'video'
2. Select an area or window.
3. When finished, run slip again and select 'stop.'
4. Video is saved.

To skip dmenu entirely and bring up a cursor ready for recording a video, use `slip --record`, and `slip --stop` to stop recording.

## config
If you want to change some available settings, you probably want to copy the example config (found in this github repo), to `~/.config/slip/config`.

If you installed from the aur, the example config can also be found at `/usr/share/doc/slip/config`.

Hopefully the config file is pretty self explanatory; I'll get around to commenting it better at some point.

## extra
Screenshotting can also be done with ffmpeg, eliminating an (optional?) dependency.     
Most people prefer maim for screenshots which is why it has been left in.

If you would prefer to use ffmpeg for screenshotting also, please let me know.
