# slip
Slip is a simple bash program that allows screenshotting with maim, and immediate uploading with imgur.

It uses dmenu as a front-end menu.

## install

#### aur
slip is in the aur!     
`pacaur -S slip` (or your preferred aur helper).

#### manual
Copy the slip file to a directory of your choice.   
Make it the file executable with `chmod +x ./slip` (where "./" is your install directory).


## usage
To launch slip, run `./slip` (where "./" is wherever slip is installed).    
Alternatively, don't make the file executable and run slip with `bash ./slip`.

#### screenshot
Select 'screenshot', then select an area or a window.   
When uploading is finished, the imgur url is copied to the cliboard and a notification is sent.

#### recording
Select 'record', then select an area or window.     
When you are finished recording, run slip again and select 'stop'.      
The video is saved and you are notified of its completion.

## qualms
Screenshotting can also be done with ffmpeg, eliminating an (optional?) dependency.     
Most people prefer maim for screenshots which is why it has been left in.

If you would prefer to use ffmpeg for screenshotting also, please let me know.
