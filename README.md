# PS5-JAILBREAK-PINAS-SlopPoops-WebHost
Webhost base on Jordy's Slopkit for FW9.00 to FW12.00 with OFFLINE CACHE feature and UNLI PAYLOADS ability where users can add Payloads FREELY and will auto populate on the webhost itself, online or offline.

<img width="1756" height="939" alt="image" src="https://github.com/user-attachments/assets/ff5864c5-181f-4c8d-b911-a96da44c0a6b" />


---------------------------------
What if offers?
---------------------------------

- Improved Stability base on Jordy's WebHost 
- Offline Cache! For Offline Jailbreak!
- Media Tab Shortcut Icon Installer
- Comes with 13 Pre-Embedded Payloads!

   - lapy_jb_daemonv1.2.elf
   - KstuffLite1.10beta.elf
   - KstuffLite1.2drTest2.elf
   - ShadowMountPlus1.6beta16.elf
   - FtpSrvPS5dr1.15-ngStable.elf
   - nanodns0.4.elf
   - bfpilotv044.elf
   - apr_emu_updaterv151.elf
   - pldmgr_v0.5.1.elf
   - web-file-mgr-v1.6.elf
   - game-compressor1.0.4.elf
   - websrv-ps5v0.34.elf
   - ps5_autoload.elf

   PLUS! 
   - Display User ID(user-id payload directory)
   - Browser AppCache Remover(before caching a new one or to delete the previous cache to prevent Kernel Panic)

- UNLIMITED PAYLOADS (depends on the user's setup, FREEDOM OF CHOICE on what payloads to add)
    - run ps5xplorer, ftp or any payload manager then copy the payloads you want on the designated path (you can add and delete payloads that you want, except the pre-embedded payloads)
    - comes with pre-embed "lapy_jb_daemon" payload, so you can use PS5-Xplorer app to transfer payloads that you want or you can also use bfpilotv044.elf and web-file-mgr-v1.6.elf
      
    - payload path:
    /user/home/(user-id)/webkit/shell/esp-payloads

    - payload path example:
    /user/home/(user-id)/webkit/shell/esp-payloads/onionhen.elf

     
PS5-Xplorer fpkg link:
https://pkg-zone.com/details/LAPY20011

----------------
HOW TO:
----------------


----------------
not jailbroken:
----------------

- use dns: 62.210.38.117, open users guide(echo's host), select playstation 5 then enter "ps5jailbreakpinas2.netlify.app" on the address bar and hit "GO". Once jailbroken, install the media tab fpkg shortcut, do a full cache, go offline, then no need to open users guide again.

----------------
jailbroken:
----------------

- just install the media tab fpkg shortcut, do a full cache then go offline

Fpkg Media Tab Shortcut Installer:
https://www.mediafire.com/file/oli4qi6h8yji8p4/ps5jbpinas2.pkg/file

Webhost Link:
https://ps5jailbreakpinas2.netlify.app/ or just ps5jailbreakpinas2.netlify.app

--------------------------------------------
Autoload Payload
--------------------------------------------

PS5 AUTOLOAD folder structure:

/data/ps5_autoloader/
For example:

     /data/ps5_autoloader/
     ├── autoload.txt
     ├── ftpsrv-ps5-0.19.elf
     ├── shadowmountplus.elf
     ├── kstuff.elf
     ├── elf-arsenal.elf
     ├── lapy_jb_daemon.elf
     ├── pegasus_dl.elf
     ├── pldmgr_v0.3.6.elf
     └── ps5shopappkg-dpi.elf

--------------------------------------------


autoload.txt
--------------------------------------------

autoload.txt controls the payload execution sequence.

Example:


--------------------------------------------
      !4000
      ftpsrv-ps5-0.19.elf
      !4000
      shadowmountplus.elf
      !4000
      kstuff.elf
      !4000
      onionhen.elf
--------------------------------------------
     
Entries beginning with ! represent a delay before continuing with the next entry.
--------------------------------------------

For example:

      !4000 (means a delay of approximately: 4000 ms)
      onionhen.elf (the following line specifies the ELF that should be loaded)

--------------------------------------------


--------------------------------------
Special Thanks
--------------------------------------

Arksama https://github.com/ArkSama
Idlesauce https://github.com/idlesauce
Stooged https://github.com/stooged
Echostretch https://github.com/EchoStretch
Drakmor https://github.com/drakmor
TheOfficialFloW https://github.com/theofficialflow
BestPig https://github.com/BestPig
VoidWhisper https://github.com/voidwhisper-ps
cy33hc https://github.com/cy33hc
Jordy https://github.com/jordyidk
notmajor https://github.com/notmaj0r
vladimir-cucu https://github.com/vladimir-cucu
Pippo, kerrdec97, Speed-007, Mr.Cat all devs, dumpers, testers

PS4/PS5 Jailbreak Pinas
https://www.facebook.com/groups/390633592648807
https://www.facebook.com/groups/1011520630219418
