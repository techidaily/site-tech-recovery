---
title: "Step-by-Step Tutorial: Set Up Stable Diffusion for Desktop Use in Windows Through GUI"
date: 2024-08-30T16:16:22.451Z
updated: 2024-08-31T16:16:22.451Z
tags:
  - cutting-edge
categories:
  - tech
thumbnail: https://thmb.techidaily.com/747f020dba73f73220750a642a58d9200a84cba1b61684b0bd89a4b6e70d1ea8.jpg
---

## Step-by-Step Tutorial: Set Up Stable Diffusion for Desktop Use in Windows Through GUI

### Quick Links

* [What Is Stable Diffusion?](https://youtube-lab.techidaily.com/024-approved-navigating-backwards-youtubes-way-to-rearrange-watch-queue/)
* [What Do You Need to Run This Version of Stable Diffusion?](https://snapchat-videos.techidaily.com/updated-the-sealed-snap-chronicles-an-experts-guidebook/)
* [How to Install Stable Diffusion with a GUI](https://phone-solutions.techidaily.com/complete-guide-for-recovering-pictures-files-on-xperia-1-v-by-fonelab-android-recover-pictures/)
* [How to Generate Images Using Stable Diffusion with AUTOMATIC1111's WebUI](https://activate-lock.techidaily.com/best-ways-to-bypass-icloud-activation-lock-on-apple-iphone-12-miniipadipod-by-drfone-ios/)
* [How to Mask Images You Create to Inpaint](https://some-guidance.techidaily.com/2024-approved-the-hustle-free-route-mastering-podcast-live-broadcasting/)
* [How to Use Stable Diffusion with ComfyUI](https://digital-screen-recording.techidaily.com/new-in-2024-simplified-recording-of-your-skype-chats-with-pc-and-mac/)
* [How to Fix the "CUDA Out Of Memory" Error in AUTOMATIC1111's WebUI](https://digital-screen-recording.techidaily.com/in-2024-game-time-capture-essential-tips-for-recording-sports/)

 You can [install Stable Diffusion locally on your PC](https://extra-information.techidaily.com/5-highest-rated-vr-gear-for-uavs-for-2024/), but the typical process involves a lot of work with the command line to install and use. Fortunately for us, the Stable Diffusion community has solved that problem. Here's how to install a version of Stable Diffusion that runs locally with a graphical user interface!

##  What Is Stable Diffusion?

 Stable Diffusion is an AI model that can generate images from text prompts, or modify existing images with a text prompt, much like [MidJourney](https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-motorola-moto-g73-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/) or [DALL-E 2](https://extra-hints.techidaily.com/best-practices-for-converting-webp-to-jpg-format-for-2024/). It was first released in August 2022 by [Stability.ai.](https://stability.ai/) It understands thousands of different words and can be used to create almost any image your imagination can conjure up in almost any style.

 There are two critical differences that set Stable Diffusion apart from most of the other popular AI art generators, though:

* It can be [run locally on your PC](https://extra-information.techidaily.com/5-highest-rated-vr-gear-for-uavs-for-2024/)
* It is an open-source project

Related: [Stable Diffusion Brings Local AI Art Generation to Your PC](https://extra-information.techidaily.com/5-highest-rated-vr-gear-for-uavs-for-2024/) 

 The last point is really the important issue here. Traditionally, [Stable Diffusion is installed and run via a command-line interface](https://unlock-android.techidaily.com/7-ways-to-unlock-a-locked-xiaomi-redmi-k70-phone-by-drfone-android/). It works, but it can be clunky, unintuitive, and it is a significant barrier to entry for people that would otherwise be interested. But, since it is an open source project, the community quickly created multiple user interfaces for it and began adding their own augmentations, including optimizations to minimize video ram ([VRAM](https://extra-support.techidaily.com/new-premium-selection-of-apple-and-android-camera-slow-motion-apps/)) usage and build in upscaling and masking.

##  What Do You Need to Run This Version of Stable Diffusion?

 We're going to cover two different forks (offshoots) of Stable Diffusion of [the main repository (repo) created and maintained by Stability.ai](https://github.com/CompVis/stable-diffusion). They both have a [graphical user interface (GUI)](https://twitter-videos.techidaily.com/updated-2024-approved-from-novice-to-pro-conquering-twitter-streams/) — making them easier to use than the regular Stable Diffusion, which only has a [command-line interface](https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-realme-narzo-60-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/) — and an installer that'll handle most of the setup automatically. They both provide the same basic functionality, but the user experience is quite different. AUTOMATIC1111's WebUI is very intuitive, and the easiest to learn and use, but ComfyUI offers an interesting and powerful node-based user interface that will appeal to power users and anyone that wants to chain multiple models together. 

 As always, be careful with third-party forks of software that you find on GitHub. We've been using these for a while now with no issues, and so have thousands of others, so we're inclined to say it is safe. Fortunately, the code and changes here are small compared to some forks of open-source projects.

 These forks also contains various optimizations that should allow it to run on PCs with less RAM, built-in upscaling and facial capabilities using GFPGAN, ESRGAN, RealESRGAN, and CodeFormer, and masking. Masking is a huge deal — it allows you to selectively apply the AI image generation to certain parts of the image without distorting other parts, a process typically called inpainting.

* A minimum of 10 gigabytes free on your hard drive  
   * You can reuse the same Python environment and checkpoints to save on space if you want to use both ComfyUI and AUTOMATIC1111's WebUI.  
   * You may also simply install them separately, which is much easier.
* An NVIDIA GPU with 6 GB of RAM (though you _might_ be able to make 4 GB work)  
   * SDXL will require even more RAM to generate larger images.  
   * You can make AMD GPUs work, but they require tinkering
* A PC running Windows 11, Windows 10, Windows 8.1, or Windows 8
* One of:  
   * [The WebUI GitHub Repo](https://github.com/AUTOMATIC1111/stable-diffusion-webui) by AUTOMATIC1111  
   * [ComfyUI](https://github.com/comfyanonymous/ComfyUI)
* [Python 3.10.6](https://www.python.org/downloads/release/python-3106/) (Use this version to ensure there aren't compatibility problems)
* [The Stable Diffusion Official Checkpoints](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/blob/main/sd%5Fxl%5Fbase%5F1.0.safetensors) (Keep an eye out for new versions!)
* Any [additional models](https://upscale.wiki/wiki/Model%5FDatabase) you might want. You can use as many or few as you want.

##  How to Install Stable Diffusion with a GUI

 The installation process has been streamlined significantly, but there are still a few steps you need to do manually before the installer can be used.

###  Install Python First

 The first thing you should do is [install the version of Python, 3.10.6](https://www.python.org/downloads/release/python-3106/), recommended by the author of the repo. Head to that link, scroll towards the bottom of the page, and click "[Windows Installer (64-Bit)](https://www.python.org/ftp/python/3.10.6/python-3.10.6-amd64.exe)."

![Click &quot;Windows Installer (64-bit).&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/windows-installer-1.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
 Click the executable you [downloaded](https://buynow-info.techidaily.com/hp-stream-14-analysis-affordable-windows-laptop-with-trade-offs-explored/) and go through the prompts. If you already have Python installed (and you most certainly do), just click "Upgrade." Otherwise follow along with the recommended prompts.

 Make certain that you add Python 3.10.6 to the PATH if you get an option for that. 

###  Install Git and Download the GitHub Repo

 You need to [download and install Git on Windows](https://techtrends.techidaily.com/ultimate-guide-to-popular-samsung-smart-tv-apps-of-2024/) before the Stable Diffusion installer can be run. Just download the [64-bit Git executable](https://git-scm.com/download/win), run it, and use the recommended settings unless you have something specific in mind.

Related: [How to Install Git on Windows](https://techtrends.techidaily.com/ultimate-guide-to-popular-samsung-smart-tv-apps-of-2024/) 

 Next, you need to download the files from the GitHub for either [AUTOMATIC1111's WebUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui), [ComfyUI](https://github.com/comfyanonymous/ComfyUI#installing), or both. 

 If you're going with AUTOMATIC1111's WebUI, click the green "Code" button, then click "Download ZIP" at the bottom of the menu.

![Click the green &quot;Code&quot; button then click &quot;Download ZIP.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/clcik-code-click-download-zip.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
 If you want to take ComfyUI out for a spin, scroll down to the "[Installing](https://github.com/comfyanonymous/ComfyUI#installing)" section, and click "Direct Link to Download."

![The direct download link for ComfyUI.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/direct.png) 

 Open up the archive file in File Explorer or your preferred [file archiving program](https://android-location.techidaily.com/easy-ways-to-manage-your-huawei-nova-y91-location-settings-drfone-by-drfone-virtual/), and then extract the contents anywhere you want. Just keep in mind that folder is where you'll need to go to run Stable Diffusion. This example extracted them to the C:\\ directory, but that isn't essential.

![Drag the &quot;stable-diffusion-webui-master&quot; folder wherever you want it.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/drag-and-drop.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 Make sure you don't accidentally drag "stable-diffusion-webui-master" or "ComfyUI\_windows\_portable" onto another folder rather than empty space — if you do, it'll drop into that folder, not the parent folder you intended.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
###  Download All The Checkpoints

 There are a few checkpoints you require for this to work. The first and most important are the [Stable Diffusion Checkpoints](https://huggingface.co/CompVis/stable-diffusion-v-1-4-original). At the time of writing, AUTOMATIC1111's WebUI will automatically fetch the version 1.5 checkpoints for you. If you want to use the SDXL checkpoints, you'll need to [download them manually](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/blob/main/sd%5Fxl%5Fbase%5F1.0.safetensors). ComfyUI doesn't fetch the checkpoints automatically. You may want to also [grab the refiner checkpoint](https://huggingface.co/stabilityai/stable-diffusion-xl-refiner-1.0/tree/main). It isn't strictly necessary, but it can improve the results you get from SDXL, and it is easy to flip on and off. 

 The checkpoints download is several gigabytes. Don't expect it to be done instantly.

 Once the checkpoints are downloaded, you must place them in the correct folder. If you're following what we've done exactly, that path will be "C:\\stable-diffusion-webui\\models\\Stable-diffusion" for AUTOMATIC1111's WebUI, or "C:\\ComfyUI\_windows\_portable\\ComfyUI\\models\\checkpoints" for ComfyUI. 

 Now you have options. You can add additional models (like [ESRGAN, Loras](http://upscale.wiki/wiki/Model%5FDatabase), etc) that add extra functions. Some simply increase upscaling quality, whereas others are designed to give better results for specific types of images, like anime, landscape photographs, realistic portaits, specific artists, or almost anything else you can imagine. Both ComfyUI and AUTOMATIC1111's WebUI create appropriately named folders for those additional models — just drag and drop, and you're good. 

 Now you just have to run the batch file for either ComfyUI or AUTOMATIC1111's WebUI. Open up the main AUTOMATIC1111's WebUI folder and double click "webui-user.bat" if you want to use that interface, or open up the ComfyUI folder and click "run\_nvidia\_gpu.bat" to run ComfyUI. 

 Expect the first time you run this to take at least a few minutes. It needs to download a bunch of stuff off the Internet. If it appears to hang for an unreasonably long time at one step, just try selecting the console window and hitting the Enter key.

 They'll both look something like that. 

![The WebUI client downloading and installing all of the assets.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/looks-like-this.png) 

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 When it is done, the console will display:

Running on local URL: http://[127.0.0.1](https://hardware-help.techidaily.com/1722958692600-get-your-canon-mx49n-printer-up-to-date-with-new-windows-drivers-here/):7860 To create a public link, set `share=True` in `launch()`

Related: [What Is the 127.0.0.1 IP Address, and How Do You Use It?](https://iphone-unlock.techidaily.com/how-do-you-unlock-your-apple-iphone-14-pro-learn-all-4-methods-drfone-by-drfone-ios/) 

 ComfyUI will run on the same IP address, since it is a locally hosted web interface, but it runs on the 8188 port instead of 7860\. 

##  How to Generate Images Using Stable Diffusion with AUTOMATIC1111's WebUI

 Alright, you've installed the WebUI variant of Stable Diffusion, and your console let you know that it is "running on local URL: http://127.0.0.1:7860."

 What exactly does that mean, what is happening? [127.0.0.1 is the localhost address](https://iphone-unlock.techidaily.com/how-do-you-unlock-your-apple-iphone-14-pro-learn-all-4-methods-drfone-by-drfone-ios/) — the IP address your computer gives itself. This version of Stable Diffusion creates a server on your local PC that is accessible via its own IP address, but only if you connect through the correct [port](https://tech-revival.techidaily.com/unlock-chatgpts-potential-with-simple-plugin-signups/): 7860\. 

 Open up your browser, enter "127.0.0.1:7860" or "localhost:7860" into the address bar, and hit Enter. You'll see this on the txt2img tab:

![The front page of the WebUI client in Google Chrome.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/SD_MAIN_SCREEN_UPDATE.png) 

 If you've used Stable Diffusion before, these settings will be familiar to you, but here is a brief overview of what the most important options mean:

* **Prompt:** The description of what you'd like to create.
* **Painter's Pallete Button:** Applies a random artistic style to your prompt.
* **Sampling Steps:** The number of times the image will be refined before you receive an output. More is generally better, but there are diminishing returns.
* **Sampling Method:** The underlying math that governs how sampling is handled. You can use any of these, but euler\_a and PLMS seem to be the most popular options. You can read more about [PLMS in this paper.](https://arxiv.org/abs/2202.09778)
* **Restore Faces:** Uses GFPGAN to try to fix uncanny or distorted faces.
* **Batch Count:** The number of images to be generated.
* **Batch Size:** The number of "batches". Keep this at 1 unless you have an enormous amount of VRAM.
* **CFG Scale:** How carefully Stable Diffusion will follow the prompt you give it. Larger numbers mean it follows it very carefully, whereas lower numbers give it more creative freedom.
* **Width:** The width of the image you want to generate.
* **Height:** The width of the image you want to generate.
* **Seed:** The number that provides an initial input for a random-number generator. Leave it at -1 to randomly generate a new seed.

 Let's generate five images based on the prompt: "a highland cow in a magical forest, 35mm film photography, sharp" and see what we get using the Euler a sampler, 40 sampling steps, and a CFG scale of 5.

 You can always hit the "Interrupt" button to stop generation if your job is taking too long.

 The output window will look like this:

![Five different highland cows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/cows-correctly-sized-lol.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
 Your images will be different.

 The bottom-left image is the one we'll use to try out for masking a bit later. There isn't really a reason for this specific choice other than personal preference. Grab any image that you like.

![A cute highland cow](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/cute-cow.png) 

 Select it, and then click "Send to Inpaint."

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
##  How to Mask Images You Create to Inpaint

 Inpainting is a fantastic feature. Normally Stable Diffusion is used to create entire images from a prompt, but inpainting allows you selectively generate (or regenerate) parts of the image. There are two critical options here: inpaint masked, inpaint not masked.

 Inpaint masked will use the prompt to generate imagery within the area you highlight, whereas inpaint not masked will do the exact opposite — only the area you mask will be preserved.

 We'll cover a bit about Inpaint masked first. Drag your mouse around on the image holding left click and you'll notice a white layer appearing over top of your image. Draw out the shape of the area you want to be replaced, and be sure to fill it in entirely. You aren't circling a region, you're masking in the entire region.

 If you're just adding something to an existing picture, it can be helpful to try to make the masked region line up with the approximate shape you're trying to create. Masking a triangular shape when you want a circle, for example, is counter-productive.

 Let's take our highland cow example and give him a chef's hat. Mask out a region in approximately the shape of a Chef's hat, and make sure to set "Batch Size" to more than 1\. You'll probably need multiple to get an ideal(ish) result.

 Additionally, you should select "Latent Noise" rather than "Fill," "Original," or "Latent Nothing." It tends to produce the best results when you want to generate a completely new object in a scene.

![Cow with chef's hat](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/cow-with-chef-s-hat.png) 

Prompt: "a highland cow wearing a chef's hat in a magical forest, 35mm film photography, sharp"  
Mask Blur: 10  
Masked Content: Latent Noise  
Inpaint Area: Whole Picture  
Sampling Method: Euler A  
Sampling Steps: 30  
CFG Scale: 5

 Alright — maybe a chef's hat isn't the right pick for your highland cow. Your highland cow is more into the early-20th century vibes, so let's give him a bowler hat.

![cow in bowler hat](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/cow-in-bowler-hat.png) 

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
Prompt: "a highland cow wearing a bowler hat in a magical forest, 35mm film photography, sharp"  
Mask Blur: 10  
Masked Content: Latent Noise  
Inpaint Area: Whole Picture  
Sampling Method: Euler A  
Sampling Steps: 30  
CFG Scale: 5

 How positively dapper.

 Of course, you can also do the exact opposite with Inpaint Not Masked. It is conceptually similar, except the regions you define are reversed. Instead of marking out the region you want to change, you mark out the regions you want to be preserved. It is often useful when you want to move a small object onto a different background.

##  How to Use Stable Diffusion with ComfyUI 

 ComfyUI is very different from AUTOMATIC1111's WebUI, but arguably more useful if you want to really customize your results. ComfyUI runs on nodes. If you're not familiar with how a node-based system works, here is an analogy that might be helpful. 

 Imagine that ComfyUI is a factory that produces an image. Within the factory there are a variety of machines that do various things to create a complete image, just like you might have multiple machines in a factory that produces cars. In the case of ComfyUI and Stable Diffusion, you have a few different "machines," or nodes. It looks like this: 

![The default ComfyUI workflow](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/comfyui.png) 

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 It looks worse than it really is. Here's what each node does:

* **Load Checkpoint:** Loads the trained model.
* **Clip Text Encode:** Where you enter a prompt. There are two because we have both a positive prompt, which tells Stable Diffusion what you want, and a negative prompt, which tells it what to avoid.
* **Empty Latent Image:** Creates a blank (noisey) image.
* **KSampler:** The node that containers the sampler. The sampler is the part of the program that converts random noise into recognizeable "stuff".
* **VAE Decode:** Creates the final image.
* **Save Image:** Writes the image to your hard drive.

 Each node has various attachment points that tell you what you need to "plug in" to each point, much like conveyor belts connecting different machines in a factory. So if you wanted the prompt: "a highland cow in a magical forest, 35mm film photography, sharp" you'd enter it in the box attached to the "positive" position on the sampler node. 

![The prompt nodes attached to the sampler node.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/node-setup.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
 We disconnected the latent image and model nodes to clear up some clutter for the screenshot, but they _**must**_ be connected for Stable Diffusion to function. 

 Then you need to pick the settings you want the sampler to use. You can get wildly different results here depending on what you select. 

* **Seed:** A random number used to generate the original noise in the image.
* **CFG:** How strongly Stable Diffusion will adhere to the prompt. The higher the value, the more carefully Stable Diffusion will follow the prompt.
* **Steps:** How many times the sampler will sample the noise to generate an image.
* **Sampler\_name:** The sampler that you use to sample the noise. These usually produce different results, so test out multiple.
* **Denoise:** Relevant to inpainting and img2img. Relates to how much your output image resembles your input image. The higher the value, the more dissimilar they will be.

 Adjust the height and width values "Empty Latent Image" node to change the size of the output image. Start with 512x512 if your GPU doesn't have much memory. If you have 12 GB of VRAM (or more) you should be able to produce 1024x1024 images without any issue, however. You can also change the batch size to produce more than one variant of each prompt when you initiate image generation. 

![The Empty Latent Image node has three fields: image width, height, and batch size.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/2023-08-01_18h58_27.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
 Now you're done. Click "Queue Prompt" to initiate image generation. You will see each node light up while it is active. 

![Click "Queue Prompt" to generate an image.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/queue-prompt.png) 

 Here is one of the images we got:

![A cute cow.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/comfyui_00003_.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
 ComfyUI is powerful, and _extremely_ flexible. If you want to perform additional operations on an image, just right-click and start adding nodes.

![Add more nodes](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/2023-08-01_19h11_54.png) 

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can add as many model and modification nodes as you want, but keep in mind that every step in the process, every node you add, will increase computational time. The Stable Diffusion community has created a huge number of pre-built node arrangements (called workflows, usually) that allow you to fine-tune your results. We've tested a few and found they can often significantly improve your results. As always, be cautious downloading and using community resources — the Stable Diffusion community is fairly safe, but you can never be too careful. 

##  How to Fix the "CUDA Out Of Memory" Error in AUTOMATIC1111's WebUI

 The bigger the image you make, the more video memory is required. The first thing you should try is generating smaller images. Stable Diffusion produces good — albeit very different — images at 256x256.

 If you're itching to make larger images on a computer that doesn't have issues with 512x512 images, or you're running into various "Out of Memory" errors, there are some changes to the configuration that should help.

[Open up "webui-user.bat" in Notepad](https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-vivo-t2-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/), or any other plain text editor you want. Just right-click "webui-user.bat," click "Edit," and then select Notepad. Identify the line that reads `set COMMANDLINE_ARGS=`. That is where you're going to place the commands to optimize how Stable Diffusion runs.

Related: [How to Write a Batch Script on Windows](https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-vivo-t2-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/) 

 If you just want to make huge pictures, or you're running out of RAM on a GTX 10XX series GPU, try out `--opt-split-attention` first. It'll look like this:

![Notepad with opt_split_attention argument.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/notepad.png) 

 Then click File > Save. Alternatively, you can hit Ctrl+S on your keyboard.

 If you're still getting memory errors, try adding `--medvram` to the list of command line arguments (COMMANDLINE\_ARGS).

![Notepad with opt_split_attention and medvram argument.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/2022-09-14_17h30_34.png) 

 You can add `--always-batch-cond-uncond` to try and fix additional memory issues if the previous commands didn't help. There is also an alternative to `--medvram ` that might reduce VRAM usage even more, `--lowvram`, but we can't attest to whether or not it'll actually work.

 The addition of a user interface is a critical step forward in making these sorts of AI-driven tools accessible to everyone. The possibilities are nearly endless, and even a quick glance at the [online communities dedicated to AI art](https://www.reddit.com/r/StableDiffusion/) will show you just how powerful the technology is, even while in its infancy. Of course, if you don't have a gaming computer, or you don't want to worry about the setup, you can always use[one of the online AI art generators](https://huggingface.co/spaces/stabilityai/stable-diffusion). Just keep in mind that you cannot assume your entries are private.

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-understanding-the-mechanics-of-vlc-media-player-on-macos/"><u>[New] 2024 Approved  Understanding the Mechanics of VLC Media Player on macOS</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-top-10-ways-to-procure-quality-photo-and-video-backgrounds/"><u>[New] Top 10 Ways to Procure Quality Photo & Video Backgrounds</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unveiling-iphones-silhouette-potential/"><u>[New] Unveiling iPhone's Silhouette Potential</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-pioneering-14-text-movements-in-artwork/"><u>[Updated] Pioneering 14 Text Movements in Artwork</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/advanced-network-troubleshooting-with-tracert-expert-strategies-for-windows-users/"><u>Advanced Network Troubleshooting with Tracert: Expert Strategies for Windows Users</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/advanced-techniques-to-harness-power-of-telnet-command-line-interface-on-windows/"><u>Advanced Techniques to Harness Power of Telnet Command Line Interface on Windows</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722899110928-anticipate-the-arrival-of-google-tvs-new-contender-price-expectations-release-dates-specs-and-secret-rumors/"><u>Anticipate the Arrival of Google TV's New Contender: Price Expectations, Release Dates, Specs & Secret Rumors</u></a></li>
<li><a href="https://article-posts.techidaily.com/comparing-the-creme-de-la-creme-gopro-hero5-black-to-hero4-silver-for-2024/"><u>Comparing the Crème De La Crème  GoPro Hero5 Black to Hero4 Silver for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/complete-guide-thawing-your-frozen-macbook-air/"><u>Complete Guide: Thawing Your Frozen MacBook Air</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/demystifying-ai-powered-pcs-insights-into-usefulness-and-necessity/"><u>Demystifying AI-Powered PCs: Insights Into Usefulness & Necessity</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/effective-repair-strategy-implemented-for-failed-igfx-module-now-functional/"><u>Effective Repair Strategy Implemented For Failed iGFX Module - Now Functional</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722877411666-enhance-your-samsung-tv-with-the-latest-updates-easy-tutorial-included/"><u>Enhance Your Samsung TV with the Latest Updates - Easy Tutorial Included</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/essential-factors-to-evaluate-when-purchasing-a-video-recording-equipment/"><u>Essential Factors to Evaluate When Purchasing a Video Recording Equipment</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expand-your-watchlist-with-easy-remote-access-setup-for-samsung-smart-tvs/"><u>Expand Your Watchlist with Easy Remote Access Setup for Samsung Smart TVs</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expert-picks-leading-ups-battery-solutions-of-ebrary-2024/"><u>Expert Picks: Leading UPS Battery Solutions of Ebrary 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/exploring-how-evs-surpass-gasoline-vehicles-in-performance-and-efficiency/"><u>Exploring How EVs Surpass Gasoline Vehicles in Performance and Efficiency</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/googles-next-smartwatch-leak-specs-expected-release-timeline-and-pricing-rumors/"><u>Google's Next Smartwatch Leak – Specs, Expected Release Timeline, and Pricing Rumors</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/guide-successfully-installing-the-fandango-app-on-your-amazon-fire-tv/"><u>Guide: Successfully Installing the Fandango App on Your Amazon Fire TV</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-recover-when-you-cant-find-the-necessary-python-file-python24dll/"><u>How to Recover When You Can't Find the Necessary Python File: python24.dll</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-10-free-online-neon-text-creators-you-need-to-try/"><u>In 2024, 10 Free Online Neon Text Creators You Need to Try</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-a-complete-course-on-managing-and-editing-srt-on-mac/"><u>In 2024, A Complete Course on Managing and Editing SRT on Mac</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-adding-flair-to-your-online-gatherings-an-in-depth-zoom-filter-guide/"><u>In 2024, Adding Flair to Your Online Gatherings  An In-Depth Zoom Filter Guide</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-display-apple-iphone-11-screen-on-pc-easily-drfone-by-drfone-ios/"><u>In 2024, How to Display Apple iPhone 11 Screen on PC Easily? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-samsung-galaxy-s23-tactical-edition-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best Samsung Galaxy S23 Tactical Edition Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-reset-itunes-backup-password-of-apple-iphone-13-mini-prevention-and-solution-by-drfone-ios/"><u>In 2024, Reset iTunes Backup Password Of Apple iPhone 13 mini Prevention & Solution</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/instalment-insight-getting-vrecord-running/"><u>Instalment Insight  Getting VRecord Running</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/max-streaming-service-recommendations-the-shows-you-cant-miss-right-now/"><u>Max Streaming Service Recommendations – The Shows You Can't Miss Right Now!</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/optimal-viewing-experience-selecting-between-ultrawide-and-uhd-4k-for-2024/"><u>Optimal Viewing Experience  Selecting Between UltraWide and UHD 4K for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/performance-and-features-breakdown-of-the-updated-apple-tv-gen-3-4k/"><u>Performance and Features Breakdown of the Updated Apple TV (Gen 3) 4K</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/playstation-portable-pre-release-guide-insights-into-release-timeline-price-range-tech-details-and-buying-options/"><u>PlayStation Portable Pre-Release Guide: Insights Into Release Timeline, Price Range, Tech Details & Buying Options</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/resolving-login-errors-on-microsoft-teams-is-there-a-widespread-outage-or-local-network-complication/"><u>Resolving Login Errors on Microsoft Teams: Is There a Widespread Outage or Local Network Complication?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/resolving-mss32dll-file-not-found-comprehensive-troubleshooting-guide/"><u>Resolving MSS32.DLL File Not Found: Comprehensive Troubleshooting Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/simultaneously-linking-several-bluetooth-speakers-with-a-single-gadget/"><u>Simultaneously Linking Several Bluetooth Speakers with a Single Gadget</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-tutorial-resolving-phase0exception-stop-error-0x00000078-in-windows-systems/"><u>Step-by-Step Tutorial: Resolving PHASE0_EXCEPTION (Stop Error 0X00000078) in Windows Systems</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/strategies-for-troubleshooting-and-resolving-msvcrtdll-errors-on-your-pc/"><u>Strategies for Troubleshooting and Resolving Msvcrt.dll Errors on Your PC</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-guide-to-7-cost-free-virtual-fax-platforms/"><u>The Ultimate Guide to 7 Cost-Free Virtual Fax Platforms</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-guide-to-samsungs-revolutionary-2025-launch-when-it-happens-plus-rumored-innovations/"><u>The Ultimate Guide to Samsung's Revolutionary 2025 Launch: When It Happens + Rumored Innovations</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-pokemon-go-strategy-tips-and-tricks-for-trainers/"><u>The Ultimate Pokémon Go Strategy: Tips & Tricks for Trainers</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-5-non-rooted-android-auto-clicker-applications/"><u>Top 5 Non-Rooted Android Auto-Clicker Applications</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-chatgpt-effective-fixes-for-common-moderation-mishaps/"><u>Troubleshooting ChatGPT – Effective Fixes for Common Moderation Mishaps</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-haldll-failures-across-different-windows-platforms-including-11-and-vista/"><u>Troubleshooting Hal.dll Failures Across Different Windows Platforms, Including 11 & Vista</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/tune-in-exclusive-radio-broadcast-of-the-ncaa-mens-basketball-tournament/"><u>Tune In! Exclusive Radio Broadcast of the NCAA Mens Basketball Tournament.</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-guide-effective-steps-for-flat-screen-television-sanitation/"><u>Ultimate Guide: Effective Steps for Flat-Screen Television Sanitation</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unveiling-the-secrets-behind-facebook-from-startup-to-global-phenomenon-and-notable-elements/"><u>Unveiling the Secrets Behind Facebook: From Startup to Global Phenomenon & Notable Elements</u></a></li>
</ul></div>
