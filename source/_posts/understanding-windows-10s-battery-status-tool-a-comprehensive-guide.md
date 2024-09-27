---
title: "Understanding Windows 10'S Battery Status Tool: A Comprehensive Guide"
date: 2024-08-19T14:17:02.809Z
updated: 2024-08-20T14:17:02.809Z
categories:
  - BestProducts
description: "This Article Describes Understanding Windows 10'S Battery Status Tool: A Comprehensive Guide"
excerpt: "This Article Describes Understanding Windows 10'S Battery Status Tool: A Comprehensive Guide"
thumbnail: https://thmb.techidaily.com/cd61def31c266f510e96724b2a8477792657278ca4fb179ccb3f421fcf0aa55a.jpg
---

## Understanding Windows 10'S Battery Status Tool: A Comprehensive Guide
### What to Know

* To generate a report, press**Win** +**X** and select**Windows PowerShell (Admin)** \>**Yes** .
* Enter **powercfg /batteryreport /output "C:\\battery-report.html"** into PowerShell and press**Enter** .
* Open the exported file from the C drive to view the battery report.

 This article explains how to generate a Windows 10 battery report. The report includes information about the general health of the battery, usage history, battery life estimates, and other statistics.  

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
## How to Generate a Battery Report in Windows 10

 The battery on your laptop or tablet is one of its most critical pieces of[hardware](https://www.lifewire.com/computer-hardware-2625895) . Over time, a battery's life span shortens, and its ability to hold a charge decreases. If you suspect your battery's performance is fading, follow these steps to create a battery report:  

1. Press**Win** +**X** , then select**Windows PowerShell (Admin)** . Select**Yes** when the User Account Control box appears.  
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
![powershell](https://www.lifewire.com/thmb/jZNRO0ZChIXAj44Hj-Qk_Gv3c2E=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/001-windows-10-battery-report-what-it-is-and-how-to-use-it-eb97a723495643429ee5af383ef33e35.jpg)
2. Enter this command into PowerShell, then press**Enter** :  
 `powercfg /batteryreport /output "C:\battery-report.html"`  
 Feel free to change the path (in quotes) to wherever you want to save the report. In our example, it will be exported to the[C drive](https://www.lifewire.com/what-is-a-c-drive-5222296) .
3. After you run the battery report command, you'll see a message indicating where the file was saved. Take note of the location.  
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
![battery life location](https://www.lifewire.com/thmb/eA3ZUvDsKSVHVe95zCIVzRKJvu4=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/002-windows-10-battery-report-what-it-is-and-how-to-use-it-fe885b3ec48e4d81bb081e819a2a972b.jpg)
4. Use Windows Explorer to find the file, then double-click or double-tap it to open the report in your web browser. In our example, since the battery report was saved in the[root](https://www.lifewire.com/what-is-a-root-folder-or-root-directory-2625989) of the C drive, we can type this into the browser's URL bar to open the report:  
 `file:///C:/battery-report.html`

[How to Get Your Windows 11 Battery Report](https://www.lifewire.com/generate-windows-11-battery-report-5209527)

## How to Read the Battery Report in Windows 10

 With the battery report generated and open, let's walk through each section to learn more about the battery's performance and estimated life expectancy.

 The first section, directly under**Battery report** , lists some primary system information such as your computer's name, BIOS version, OS build, and the date the report was created.

 The second section, below**Installed batteries** , lists key information about your laptop or tablet batteries, such as name, manufacturer, serial number, chemistry, and design capacity.

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![A screenshot of the first two sections of a Windows 10 battery report.](https://www.lifewire.com/thmb/cdMl7F4TRFo-BwaNKuCqdGgWKko=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/how-to-generate-a-battery-report-on-a-windows-10-laptop-4587396-6-5c74f03546e0fb0001a9825a.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Recent Usage

 This section overviews when your device was running on battery or connected to AC power. Recent usage covers power states for three days and includes start time, state (active/suspended), source (battery/AC), and remaining capacity.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
![A screenshot displaying recent usage on a Windows 10 battery report.](https://www.lifewire.com/thmb/gPFUNNrcOy5j_YDxwEdimde27d8=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/how-to-generate-a-battery-report-on-a-windows-10-laptop-4587396-7-5c74fa37c9e77c0001e98d2b.jpg)

### Battery Usage

 This area lists any battery drains over the last three days. If your system ran for extended periods on battery alone, this section would break it down by start time or duration, as well as by energy drained.

[How to Make a Laptop Battery Last Longer](https://www.lifewire.com/make-laptop-battery-last-longer-5189983)

![A screenshot showing battery usage in a Windows 10 battery report.](https://www.lifewire.com/thmb/CcY183o8jUDRbhUehMCZBEedeo8=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/how-to-generate-a-battery-report-on-a-windows-10-laptop-4587396-8-5c750187c9e77c000136a5f0.jpg)

### Usage History

 Here, you'll see a complete history (including duration) of each time your device was running on battery or AC power. Reviewing your usage history is a great way to see how often and for how long you run your device on battery power.

![A screenshot showing battery and AC power usage in a Windows 10 battery report.](https://www.lifewire.com/thmb/mZEneBChOagqSVGktFCzwFEe-3U=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/how-to-generate-a-battery-report-on-a-windows-10-laptop-4587396-9-5c758254c9e77c0001e98d44.jpg)

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
### Battery Capacity History

 In this section of the report, you see the full charge capacity compared to your battery's design capacity for each period. Watching your full charge capacity is another helpful way to monitor the overall health and performance of your battery over time.

![A screenshot of the battery capacity history section of a Windows 10 battery report.](https://www.lifewire.com/thmb/6KUTn767xRch_BQSEj3JHzuI2fg=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/how-to-generate-a-battery-report-on-a-windows-10-laptop-4587396-10-5c75a643c9e77c00012f80ea.jpg)

### Battery Life Estimates

 The final section of the report displays battery life estimates at full charge, compared to the designed capacity. This gives you a clear outlook of how well your battery's life is holding up over time. At the very bottom of the report is an estimated battery lifetime value based on observed drains since the last OS installation.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![A screenshot showing battery life estimates on a Windows 10 laptop.](https://www.lifewire.com/thmb/GpXKBVh8c6oG-fA3KQUHuCXgksc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/how-to-generate-a-battery-report-on-a-windows-10-laptop-4587396-11-5c76609b46e0fb0001a5ef6e.jpg)

[How Long Does a Laptop Battery Last?](https://www.lifewire.com/how-long-does-a-laptop-battery-last-5186206)

 FAQ

* Where does Windows save my battery report to?  
 Your battery report will be saved to a folder on your PC, which you'll see in the PowerShell window when you attempt to save a new report. You can also manually change the destination folder when running the command, to make the HTML file easier to find.
* What does "charge cycle" or "cycle count" mean in my Windows battery report?  
 Cycle counts and charge cycles refer to the number of times your battery used up 100 percent (cumulative) of its charge. This applies to both draining the battery to 0 percent and recharging it, as well as incremental drains. For example, using 30 percent of the battery, recharging to 100 percent, then using 70 percent counts as one cycle.
* How do I recalibrate a new battery in Windows?  
 Once you've installed a new battery, charge it to 100 percent, let it run down to zero, and then recharge it back to 100 percent. This will allow Windows to better keep track of the new battery's capacity (and other stats).

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


