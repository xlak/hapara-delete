# How to disable annoying school spyware (Hapara, GoGuardian, LanSchool, iBoss, etc)

## List of known bypass methods and exploits

- [Ingot](https://fognetwork.github.io/Ingot/)  
  
  The successor to LTBEEF. Has a better UI.  
  *Patched* in Chrome OS version 106 and above.  

- [LTBEEF](https://compactcow.com/ltbeef/)  
  
  What Ingot is based on. Opens a menu that lets you disable extensions.  
  Works if developer tools are blocked.  
  Won't work without JavaScript bookmarklets.  
 ~~*Patched* in Chrome OS version 106 and above.~~ The repo now contains additional methods that will work on v106+.  
  
- [Swamp Launcher](https://www.youtube.com/watch?v=qo-hx0tOYxI)
  
  Uses a custom DNS server to force-install a Chrome extension.
  The extension then lets you disable any extension you want.  
  Unfortunately this was discovered by a sysadmin and posted to r/k12sysadmin. It will likely be patched in most school districts.

- [Chaos](https://xlak.github.io/chaos/)  
  
  Can disable force-installed extensions fairly easily.  
  Works on Chrome OS, not on Windows or Mac.  
  Works without JavaScript bookmarklets.  
  Won't work if developer tools are completely disabled.  

- [Alphabetic](https://xlak.github.io/alphabetic/)  
  
  Opens hidden, unfiltered tabs that won't save in your history.  
  Doesn't affect the operation of monitoring software on other tabs, unlike most exploits.  
  Works without JavaScript bookmarklets.  
  Harder to get caught using this since teachers think they can still see all of your tabs.  
  
- [GoGuardian close prevention](https://github.com/yeeteeyt/goguardian-bypass)  
  
  Does not hide anything from GoGuardian. Only prevents tabs from being closed.  
  Requires JavaScript bookmarklets to work. 
  This may also work for Hapara Highlights.
  
- [Hide tabs from Hapara](https://raw.githubusercontent.com/FreshPenguin112/bookmarklets/main/hapara%20tab%20hide%20XD) ([Source on GitHub](https://github.com/ConnorCodesatSchool/HaparaDelete/issues/2))
  
  Makes tabs show up as Google Drive tabs on the teacher dashboard.  
  Requires JavaScript bookmarklets to work.  
  This DOES NOT prevent Hapara from capturing your screen. Teachers will still see the real tab if they look at the screenshot view.  
  
- chrome://kill
  
  Spam this in the address bar to eventually kill unwanted extensions. Then just click on extensions that you want to keep to relaunch them.
  
- Chrome Task Manager
  
  Press `Shift+Escape` to open the task manager. You may be able to kill unwanted extensions from here.
  
- Alternative browsers
  
  If you're on Windows or Mac you can just use another web browser to hide stuff from extension-based monitoring software. But beware that system-level spyware may also be installed on your computer.
  
- Secondary Chrome accounts
  
  On Chrome for Windows, you can have multiple accounts with their own independent sessions open. So you can open your school account and then open another account to do stuff that you don't want teachers to see.  
  You can also open a guest session even if it's disabled by the school board.

## Proxy and Game Sites

- [Titanium Network](https://github.com/titaniumnetwork-dev)
- [Holy Unblocker](https://holyubofficial.net/) [Alt link](https://website-aio-e9x.koyeb.app/1.html)
- [Hypertabs](https://hypertabs.cc/)
- [Incognito](https://incog.dev/)
- [Taco Proxy](https://izhdh.sse.codesandbox.io/)
  
  Good at bypassing many web filters.  
  Join the Titanium Network Discord server for more links in case these are blocked.
  
- [3kh0 Unblocked Games](https://3kh0.github.io/)
  
  Hosts a lot of unblocked games.  
  Unfortunately it has lots of ads.  
  
- [Art Class](https://artclass.site/)
  
  Another  always-unblocked games site
  No ads!
  
- [Cool Math Games](https://www.coolmathgames.com/)
  
  This one's a classic.
  
- [Krunker.io Official Proxy](https://browserfps.com/)
  
  Play a fun FPS game in you browser.

## List of bypass methods by software
This is a list of web filters and spyware, as well as known methods to bypass them.

### Hapara Highlights
Lets teachers view open tabs, screenshots, and recent browsing history in the Teacher Dashboard. Teachers can send messages to students and close tabs. Teachers can also turn on focus browsing mode which only lets you open approved websites for a certain amount of time.
- Chaos
- Alphabetic
- LTBEEF
- Ingot
- Swamp Launcher

### Hapara Filter
Hapara Filter is actually just a rebranded version of the Deledao extension. It uses AI to detect sites that schools don't want you going on. That means the vast majority of proxy sites and unblocked games will not work without disabling it first.  
Interesting to note: Clicking on the Hapara Filter icon makes a box pop up that lets you enter "support commands". The extension verifies inputted commands with an RSA key and executes them as JavaScript if they're valid. Possible exploit if the private key ever gets cracked or leaked.
- Chaos
- Alphabetic (Can bypass it without disabling it)
- LTBEEF
- Ingot

### iBoss
A network-wide filter, but it can also come with a browser extension. Repl.it is apparently blocked by IP on iBoss because it is frequently used to unblock games. This is strange because many CS classes depend on Repl.it.  
- Alphabetic
- Chaos (for extension)
- LTBEEF (for extension)
- Ingot (for extension)
- Swamp Launcher (for extension)

### FortiGate
A network-wide filter. Asks for an admin username and password to override site blocking.
- Alphabetic

### GoGuardian
A very popular piece of classroom monitoring software. Lets teachers see tab names, but not screenshots.

- Chaos
- Alphabetic
- LTBEEF
- Ingot
- Swamp Launcher

### LanSchool
By far the worst piece of monitoring software out of the bunch, it lets you control every device on the network if you download the teacher software. Runs using pNaCl for the Chrome extension. It lets teachers see your full screen on Windows. Has a keylogger that stores key presses in a scrambled format.

- Chaos
- LTBEEF
- Ingot
- Swamp Launcher

### Lightspeed Relay

- Alphabetic

### Securly

- Chaos
- Alphabetic
- LTBEEF
- Ingot
- Swamp Launcher

### Blocksi

- Chaos
- Alphabetic
- LTBEEF
- Ingot
- Swamp Launcher

## Useful Resources
[HeroHACK Academy of Hacking](https://sites.google.com/view/hackingacademybypro/home) (Contains lots of hints on how to find bypass methods)  
[LTBEEF Github Page](https://github.com/3kh0/ext-remover) (Source code for LTBEEF. Contains a funny message for sysadmins.)  
[Ingot Github Page](https://github.com/FogNetwork/Ingot) (Source code for Ingot.)  
[TitaniumNetwork Discord](https://discord.gg/unblock) (Join to get proxy links)  
[Hapara - Preventing student loopholes](https://support.hapara.com/hc/en-us/articles/230060007-Strengthening-Highlights-and-preventing-student-loopholes) (Try these in case your school didn't implement the patches properly)  
[k12sysadmin on Reddit](https://reddit.com/r/k12sysadmin) (See what the sysadmins are talking about)  
[TN-Decompile](https://github.com/TN-Decompile) (Decompiled source code for some school spware)  

## Contributing

This project aims to compile a list of known methods to get around web filters and school spyware. If you know of anything that is not covered here, please open an issue or create a pull request.
