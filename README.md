# Abby's Mirror: About
<p>
Dear Abby,

This project is the collective effort of your Aunt Jill, Uncle, Dave, Jim, Monica, and myself.<br>
<img align="right" src="/images/sig_Ani_Ini_Blk.gif">May it bring you many years of joy.
</p>

## Pages

  * [Quick Start](./QuickStart.md) 
  * [Guide](./Guide.md) Detailed informaiton about using all features of your mirror
  * [Build Log](./BuildLog.md) This page shows a history of how your mirror came to be
  * The rest of this page contains basic information about your mirror.

## Hardware
This section documents the hardware used to create your mirror.
| Object | Description | Ref | |
| :--- | :---: | :---: | :---: |
| Orange Pi Zero 3  | Hardware / CPU | [Orangepi](http://www.orangepi.org/html/hardWare/computerAndMicrocontrollers/details/Orange-Pi-Zero-3.html) | <img src="/images/OPZ3.jpg" width="240"/> |

## Software
This is the primary software used to create and augment your mirror, see the build log for a more comprehensive list.
| Object | Description | Ref | 
| :--- | :--- | :--- | 
| Operating System | Debian Bookworm (lite) | [Orange Pi OS Downloads](http://www.orangepi.org/html/hardWare/computerAndMicrocontrollers/service-and-support/Orange-Pi-Zero-3.html) | 
| MagicMirror | Primary application | https://magicmirror.builders/ | 
| Samba | Windows file sharing | https://www.samba.org/ |
 
## Config
This section describes how your mirror has been configured (default). This configuration can be chagned and customized however desired.
### Magic Mirror Modules 
Your mirror has several modules that extend it's functionality, below is the list of currently installed modules. There are many modules available, read more about modules [via this link](https://github.com/MichMich/MagicMirror/wiki/3rd-party-modules).
| Module | Desc |  
| :--- | :--- | 
| MMM-Remote | Provides a web interface to interact and manage your mirror | 
| MMM-Scheduler | Schedule module visibility, brightness, etc | 
| Weather | Current and forecast | 
| Clock | it's a clock | 
| MMM-DailyBibleVerse | Verse of the day from BibleGateway.com | 
| MMM-RAIN-MAP | Shows a radar map when it's raining | 
| Compliments Plus | Abby's favorite plugin, originally from here https://github.com/hangorazvan but appears to be abandoned.  | 
| MMM-BackgroundSlideshow | Mirror wallpaper, rotates from samba share folder | 

### Default Module Config and Layout
This section describes how the default modules are configured.
![mirror2](images/Mirror2.png)

| Module | Location (default) | Color | Displays | 
| :--- | :--- | :--- | :--- |
| Current weather | top left | green | always |
| Forecast | top left | red | always |
| Rain Map | lower left | yellow | when raining |  
| Clock | top right | cyan | always | 
| Daily verse | top right | magenta | Sunday | 
| Compliments plus | center | blue | always |
| Calendar | lower right | orange | daily 6:00AM to 10:00PM | 
| IP address | lower right | purple | always (until turned off) |
| * | * | * | all modules dimmed to 40% at 10PM | 


Next: Read the [usage guide](Guide.md)



