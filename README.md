# How to disable Hapara and other annoying school spyware

## List of known bypass methods and exploits

- [Ingot](https://fognetwork.github.io/Ingot/)  
  
  The successor to LTBEEF. Has a better UI.  
  *Patched* in Chrome OS version 106 and above.  

- [LTBEEF](https://compactcow.com/ltbeef/)  
  
  What Ingot is based on. Opens a menu that lets you disable extensions.  
  Works if developer tools are blocked.  
  Won't work without JavaScript bookmarklets.  
  *Patched* in Chrome OS version 106 and above.  

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
  
- [Cool Math Games](https://www.coolmathgames.com/)
  
  This one's a classic.
  
- [Krunker.io Official Proxy](https://browserfps.com/)
  
  Play a fun FPS game in you browser.

## List of bypass methods by software
This is a list of web filters and spyware, as well as known methods to bypass them.

### Hapara Highlights
- Chaos
- Alphabetic
- LTBEEF
- Ingot

### Hapara Filter
Hapara Filter is actually just a rebranded version of the Deledao extension.  
It uses AI to detect sites that schools don't want you going on.  
That means the vast majority of proxy sites and unblocked games will not work without disabling it first.  
- Chaos
- Alphabetic (Can bypass it without disabling it)
- LTBEEF
- Ingot

### iBoss
A network-wide filter, but it can also come with a browser extension.
Repl.it is apparently blocked by IP on iBoss because it is frequently used to unblock games.  
This is strange because many CS classes depend on Repl.it.  
- Alphabetic

## Useful Resources
[HeroHACK Academy of Hacking](https://sites.google.com/view/hackingacademybypro/home) (Contains lots of hints on how to find bypass methods)  
[LTBEEF Github Page](https://github.com/3kh0/ext-remover) (Source code for LTBEEF. Contains a funny message for sysadmins.)  
[Ingot Github Page](https://github.com/FogNetwork/Ingot) (Source code for Ingot.)  
[TitaniumNetwork Discord](https://discord.gg/unblock) (Join to get proxy links)  
[Hapara - Preventing student loopholes](https://support.hapara.com/hc/en-us/articles/230060007-Strengthening-Highlights-and-preventing-student-loopholes) (Try these in case your school didn't implement the patches properly)  
[k12sysadmin on Reddit](https://reddit.com/r/k12sysadmin) (See what the sysadmins are talking about)  

## Contributing

This project aims to compile a list of known methods to get around web filters and school spyware. If you know of anything that is not covered here, please open an issue or create a pull request.
