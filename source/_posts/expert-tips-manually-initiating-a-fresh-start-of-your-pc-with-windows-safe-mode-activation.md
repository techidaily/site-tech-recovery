---
title: "Expert Tips: Manually Initiating a Fresh Start of Your PC with Windows Safe Mode Activation"
date: 2024-08-19T12:58:41.223Z
updated: 2024-08-20T12:58:41.223Z
categories:
  - BestProducts
description: "This Article Describes Expert Tips: Manually Initiating a Fresh Start of Your PC with Windows Safe Mode Activation"
excerpt: "This Article Describes Expert Tips: Manually Initiating a Fresh Start of Your PC with Windows Safe Mode Activation"
thumbnail: https://thmb.techidaily.com/0925fc779f0843944465c330e0533d47cac4851d58ef98585f8f45212c0df5ac.jpg
---

## Expert Tips: Manually Initiating a Fresh Start of Your PC with Windows Safe Mode Activation
### What to Know

* To force Windows to restart in Safe Mode, access Advanced Startup Options or System Recovery Options.
* Then, use a**bcdedit** command to open Safe Mode from Command Prompt.

 This article describes how to use the bcdedit command to boot into Safe Mode when[the normal method doesn't work](https://www.lifewire.com/fix-a-computer-that-always-stops-at-startup-settings-or-abo-2624445) .  

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Use 'bcdedit' to Start in Safe Mode

 Forcing Windows to restart to this special mode (or making it_stop_ starting in Safe Mode) is moderately difficult and will probably take several minutes, at most. These directions will start Safe Mode from[Command Prompt](https://www.lifewire.com/command-prompt-2625840) :

1. [Open Advanced Startup Options](https://www.lifewire.com/how-to-access-advanced-startup-options-in-windows-10-or-8-2626229) if you're on Windows 11, Windows 10, or Windows 8\. Since you can't start Windows properly, use methods 4, 5, or 6 outlined in that tutorial.  
 With Windows 7 or Vista, start System Recovery Options using your installation media or a system repair disc. Unfortunately, this process doesn't work with Windows XP.  
 If you want to force or stop Safe Mode from starting, and you actually_can_ access Windows properly, you don't need to follow the procedure below. See the much easier[How to Start Windows in Safe Mode Using System Configuration](https://www.lifewire.com/how-to-start-windows-in-safe-mode-using-system-configuration-2626115) process.
2. Open Command Prompt. If you're using Windows 7 or newer, it's located here:**Troubleshoot** \>**Advanced options** \>**Command Prompt** .  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Advanced Startup Options for Windows 10](https://www.lifewire.com/thmb/FvRv0xdSCo8UanPmD9Vp0mBddjE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/aso-windows-10-5c5c3bde46e0fb000127c6d7.png)
3. Execute the correct bcdedit[command](https://www.lifewire.com/what-is-a-command-2625828) as shown below based on which Safe Mode option you'd like to start:  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
!["bcdedit /set {default} safeboot network" command in Command Prompt](https://www.lifewire.com/thmb/tnUE5VabXIlDNfK2S4UhcOKHG9c=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/002_how-to-force-windows-to-restart-in-safe-mode-2625163-5c77678446e0fb0001d83cb3.jpg)  
 Be sure to type whatever command you choose_exactly_ as shown and then execute it using the**Enter** key. Spaces are very important! The { and } brackets are the ones above the \[ and \] keys on your keyboard. Two separate commands are required to start_Safe Mode with Command Prompt_ , so be sure to execute them both.  
 Safe Mode:  
 `bcdedit /set {default} safeboot minimal`  
 Safe Mode with Networking:  
 `bcdedit /set {default} safeboot network`  
 Safe Mode with Command Prompt:  
 `bcdedit /set {default} safeboot minimal bcdedit /set {default} safebootalternateshell yes`
4. A properly executed bcdedit command should return the message**The operation completed successfully** .  
 If you see one of these messages or something similar, check Step 3 again and make sure you executed the Safe Mode command properly:  
   * **The parameter is incorrect**  
   * **The set command specified is not valid**  
   * **...is not recognized as an internal or external command...**
5. Close the Command Prompt window.
6. In Windows 11, 10, and 8, select**Continue** .  
 In Windows 7 and Vista, select**Restart** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
![ASO menu Windows](https://www.lifewire.com/thmb/s1Q2N-22YKjJTAP7l4M9BJzkNXE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/003_how-to-force-windows-to-restart-in-safe-mode-2625163-5c7767ddc9e77c0001f57b8c.jpg)
7. Wait while your computer or device restarts.
8. Once Windows starts, log in as you normally do and use Safe Mode however you were planning.

 Windows will continue to start in Safe Mode every time you reboot unless you undo what you did in Step 3\. The easiest way to do that is not by executing more commands but[via System Configuration](https://www.lifewire.com/how-to-start-windows-in-safe-mode-using-system-configuration-2626115) (uncheck**Safe boot** ).

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Stop a Safe Mode Loop

 Try this if Windows is stuck in a sort of Safe Mode loop, preventing you from starting in normal mode again, and you've already tried the instructions in the_Important_ call-out above:

1. Start Command Prompt from_outside_ of Windows, the process outlined in Steps 1 and 2 above.
2. Execute this command once Command Prompt is open:  
 `bcdedit /deletevalue {default} safeboot`  
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
!["bcdedit /deletevalue {default} safeboot" command in Command Prompt on Windows](https://www.lifewire.com/thmb/iw73ubzOfXo2zuWO1YLBafnst2A=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/004_how-to-force-windows-to-restart-in-safe-mode-2625163-5c7768a5c9e77c000136a6ae.jpg)
3. Assuming it was successfully executed (see Step 4 above),[restart your computer](https://www.lifewire.com/how-to-reboot-a-computer-2624568) . Windows should start normally.

[8 Things to Consider Before Buying a Desktop PC](https://www.lifewire.com/desktop-pc-buyers-guide-832343)

 FAQ

* How do I exit Safe Mode in Windows 10?  
 Exiting Windows 10 Safe Mode is typically just a matter of[restarting your PC](https://www.lifewire.com/how-to-reboot-a-computer-2624568) . Another method is to press the**Windows key + R** , then type in "**msconfig** " and select**OK** \>**Boot** and turn off**Safe boot** under Boot Options.
* How do I enter Safe Mode in Windows XP if F8 isn't working?  
 Normally restarting Windows XP in Safe Mode is just a matter of pressing F8 during startup. If the F8 key isn't working, check your keyboard for an F-Lock key that could have turned off your F keys. Otherwise,[open your PC's BIOS menu](https://www.lifewire.com/how-to-enter-bios-2624481) and make sure**Keyboard Support USB** is turned on.

Was this page helpful?

Thanks for letting us know!

 Get the Latest Tech News Delivered Every Day

[Subscribe](https://www.lifewire.com/#)

Tell us why!

 Other  Not enough details  Hard to understand

 Submit

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>


