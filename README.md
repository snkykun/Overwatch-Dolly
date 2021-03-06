# Overwatch-Dolly [![Discord](https://img.shields.io/discord/743941628020129853.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/EXuG82n)
Creating an HLAE style dolly cam inside overwatch with AHK

![Image](https://raw.githubusercontent.com/snkykun/Overwatch-Dolly/main/images/Dolly.gif)
##### Disclaimer: Although Blizzard does not seem to care about users using AHK, use this at your own risk! I am not liable for any bans/suspensions resulting in you using this script.
### Getting started

* Install [AutoHotKey](https://www.autohotkey.com/)
* Download [Overwatch-Dolly.ahk](https://github.com/snkykun/Overwatch-Dolly/blob/main/Overwatch-Dolly.ahk) from this repository

### Using the Script

* Assign up to 9 camera points by pressing `CTRL + #` (assign then in numerical order)
* Press the Number of your first Camera point to move to that point **This is very crucial!**
* Open the AHK script
* Press the default trigger key `Alt + H` to begin the dolly sequence

### Tips for Creating a great cinematic

* Simply changing the time inbetween key presses can help with fast camera movements
  > Every sequence will not look amazing right out of the box, you'll need to edit the `Sleep, (TIME IN MS)` inbetween the key presses. Sometimes having a longer first sleep cycle (I.E. press key 1, sleep for 300ms, press key 2, sleep for 120ms, etc) will yeild better results than the defaulted numbers.
* In order to get a smooth transition between camera points, the camera needs to move quite quickly. When playing a demo back, the camera speed seems too fast for 0.25x speed or sometimes even 0.5x speed. It is generally recommended to use 1.0x speed and slow it down in post using [Twixtor](https://revisionfx.com/products/twixtor/)


![Image](https://github.com/snkykun/Overwatch-Dolly/blob/main/images/Dolly2.gif)
##### For any questions do not hesitate to dm me on twitter or join the [Overwatch Editing discord](https://discord.com/invite/EXuG82n)! 
