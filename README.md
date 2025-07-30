Repo of the code containing the new AtmoPack-Fetcher via Node jS

This is still under development, but it works
In particular, it allows the AtmoPack-Vanilla to be generated via discord

It contains : 
```
Atmosphere (v1.9.3)
Atmosphere-Fusee (v1.9.3)
Hekate (v6.3.1)
90DNSTester (v1.0.4)
DBI (v749ru)
FTPD (vv3.2.1)
JKSV (v11/05/2024)
EdiZon (v3.1.0)
Goldleaf (v1.0.0)
Sys-Patch (v1.5.5)
Atmosphere-Hekate-Config (v1.0.0)
```

We chose to make a new fetcher because the old one had hardcoded data that wasn't clean. This was still the case with certain functions, but all rests are parameterized in a datas.json file, which looks like this exemple :
```
{
    "soft": [
        {
            "packagename": "Atmosphere",
            "repository": "Atmosphere-NX/Atmosphere",
            "releasetype": "latest",
            "filename": "atmosphere-1.8.0-master-c6014b533+hbl-2.4.4+hbmenu-3.6.0.zip",
            "filesearch": "(atmosphere.*master.*hbl.*.zip)",
            "url": "https://github.com/Atmosphere-NX/Atmosphere/releases/download/1.8.0-prerelease/atmosphere-1.8.0-master-c6014b533%2Bhbl-2.4.4%2Bhbmenu-3.6.0.zip",
            "version": "1.8.0-prerelease",
            "filetype": "CFW"
        }
]
}
```
Data in datas.json is auto-updated each time the script is used
The bot discord invitation link: [SigHya-Bot](https://discord.com/oauth2/authorize?client_id=1068239963260452885&permissions=8&scope=bot%20applications.commands)
If you have any problems with the script, the new AtmoPack-Vanilla, don't hesitate to visit the [SigHya discord](https://discord.sighya.fr).

The script will be reworked further, but for the Pack it's currently in its final form.
Likewise, if you have any questions, don't hesitate to come to the [SigHya discord](https://discord.sighya.fr).

![generatepack](https://github.com/user-attachments/assets/5aac3f78-b5d4-4335-b148-02318a136630)

Credit : 

```
- SciresM (Atmosphère & DayBreak & Reboot to payload) : https://github.com/Atmosphere-NX/Atmosphere
- SciresM & FlagBrew (Checkpoint) : https://github.com/FlagBrew/Checkpoint, https://github.com/SciresM/Checkpoint/
- CTCaer (Hekate) : https://github.com/CTCaer/hekate
- CTCaer & Hexkiz (TX Custom Boot) : https://gist.github.com/CTCaer/13c02c05daec9e674ba00ce5ac35f5be
- WerWolv (Edizon) : https://github.com/WerWolv/EdiZon
- Mtheall (ftpd) : https://github.com/mtheall/ftpd
- J-D-K (JKSV) : https://github.com/J-D-K/JKSV
- XorTroll (Goldleaf) : https://github.com/XorTroll/Goldleaf
- Meganukebmp (Switch_90DNS_tester) : https://github.com/meganukebmp/Switch_90DNS_tester
- PoloNX (PayloadReboot) : https://github.com/PoloNX/PayloadReboot
- (rashevskyv) DBI : https://github.com/rashevskyv/dbi
- (iTotalJustice) sys-patch : https://github.com/ITotalJustice/sys-patch
- (impeeza) sys-patch : https://github.com/ITotalJustice/sys-patch
- (iTotalJustice) sphaira : https://github.com/ITotalJustice/sphaira
- Special thanks to SciresM and all the Reswitched team who made this possible ^^
```
