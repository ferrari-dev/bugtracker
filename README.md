bugtracker
----------

Welcome to the ferrari (mi4i) development bug tracker. You can post any issues you have encountered here within the issues tab. Just make sure to read the commonly asked questions below first before reporting. We accept contributions to the codebase. More info on that below.

[Issues](https://github.com/ferrari-dev/bugtracker/issues)

[Wiki](https://github.com/ferrari-dev/bugtracker/wiki)

[Pull requests](https://github.com/pulls?utf8=%E2%9C%93&q=is%3Aopen+is%3Apr+user%3Aferrari-dev)

## Firmware Compability

| firmware | kernel | status |
|:--------:|:------:|:------:|
|   6.x    |   6.x  |    ✔   |
|   6.x    |   8.x  |    ✱   |
|   8.x    |   6.x  |    ✖   |
|   8.x    |   8.x  |    ✔   |

 - ✔ works
 - ✖ doesn't work at all
 - ✱ works but be warned

## Commonly asked questions

#### 1. How to install a custom rom?
> Well, if you don't know how, you might be risking a [bricked device](https://en.wikipedia.org/wiki/Brick_(electronics)) but here are the steps:
1. Download the fastboot binaries from [here](https://dl.google.com/android/repository/platform-tools-latest-windows.zip) - _Assuming you're on Windowz_ and extract it to an accesible location.
2. Download TWRP from [here](https://www.androidfilehost.com/?w=files&flid=181210) and put it in the same location as the fastboot binaries.
3. Now boot into fastboot mode on your phone (power+vol up) and connect it to the computer.
4. Open up command prompt in that folder (shift+right click) and type in `fastboot flash recovery twrp-3.1.0-0-ferrari.img` and wait until its completed. Now boot into your new recovery (power+vol down)
5. Copy the rom zip file into your phone nd flash.
6. Profit?

#### 2. How do I revert back to MIUI?
> Now that you're fed up with your fancy new custom rom and wanted to go back to MIUI, here are the steps:
1. Download the fastboot rom from MIUI forums.
2. There will be a zip inside the rom zip, extract it to the fastboot folder in the previous steps.
3. Make sure to backup everything on you phone as this process deletes all data. Open up command prompt in that folder and type in `flash_all.bat` or `flash_all.sh` depending on system.
4. Wait for it to complete
5. Profit?

#### 4. Can I get VoLTE?
> Short answer, NO

#### 5. Where is number 3?
> I thought you didn't noticed... :unamused:

#### 6. How do I contribute?
> Well, we always need testers. Contact someone on XDA or here for more info. Other than that, we also accept PRs into the device and kernel trees. Make sure that those PRs are documented, clean, and does not conflict. Donations are also accepted and can be in any form including money, server space, moral support, etc. Contact a team member for more info.
