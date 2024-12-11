---
title: "Decoding the Language of Computing Power: The Role of Apple Silicon and Rosetta in Consumer Choices."
date: 2024-12-06T05:30:54.437Z
updated: 2024-12-10T20:14:28.203Z
tags:
  - apple
categories:
  - tech
thumbnail: https://thmb.techidaily.com/815fea7976911214190dec2e4ce8ef31c5b56fc35aca9555d7d0112a6571e067.jpg
---

## The Role of Cutting-Edge AI Technology From Apple in Shaping the Future of the iPhone 16 - Insights

![Apple iPhone 15 Pro (in Blue Titanium) camera lenses](https://www.zdnet.com/a/img/resize/0b61ec84d772cbbb6f96fa06bfbbcd63410591ec/2023/10/10/5d6ca44c-691b-45da-a20c-e9ea693c9ce6/dsc01721-enhanced-nr.jpg?auto=webp&width=1280)

Jason Hiner/ZDNET

Wall Street is predicting a rough 2024 for Apple's iPhone franchise because of a lack of interesting new hardware features. Could artificial intelligence software [make an iPhone 16 shine brighter](https://www.zdnet.com/article/apple-reportedly-eyeing-generative-ai-push-and-siri-overhaul-for-the-iphone/)?

Some Apple stock bulls think so. Morgan Stanley analyst Erik Woodring this month opined that 2024 "will be the year that Apple's 'Edge AI' opportunity comes to fruition," and that it could power the new crop of iPhones this fall to greater heights. 

**Also: [The iPhone 16 Ultra camera will integrate the biggest leap in photos since B&W-to-color](https://www.zdnet.com/article/the-iphone-16-ultra-camera-will-integrate-the-biggest-leap-in-photos-since-b-w-to-color-report/)** 

Apple's iPhone sales, led by the [current iPhone 15](https://www.zdnet.com/article/iphone-15-plus-review/), are expected to decline by about 2% this year, according to estimates compiled by FactSet Systems, to 229 million units, as the current iPhone cycle underwhelms with merely iterative hardware features. 

But come 2025, wrote analyst Woodring, current Wall Street expectations for growth of 4%, to 237 million units, could turn out to be 15% higher if an iPhone 16 has enhanced AI capabilities.

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

"If we are correct, and new LLM-enabled software features drive an upgrade cycle, then we see the potential for up to 15% upside to our FY25 iPhone shipment forecast," wrote Woodring. The acronym "LLM" refers to "large language models" such as OpenAI's GPT-4.

Woodring speculates that the world will see [details at Apple's Worldwide Developer Conference](https://www.zdnet.com/article/apple-reportedly-eyeing-generative-ai-push-and-siri-overhaul-for-the-iphone/) this summer, "highlighted by an LLM-powered Siri 2.0 and a broader GenAI-enabled operating system that has the potential to catalyze an iPhone upgrade cycle." 

Why is "LLM-powered" such a big deal? To use large language models akin to OpenAI's GPT-4 requires a phone to go back and forth to the network, sending prompts and retrieving responses. Even on a desktop computer with an ethernet connection, the round-trip means waiting a while for a response. In a mobile device on a cellular network, relying on the cloud connection could result in one of those awkward moments where Siri seems brain-dead.

**Also:** [**iPhone 15 review: I spent a month with Apple's base model and found it more 'Pro' than ever**](https://www.zdnet.com/article/iphone-15-plus-review/)

Instead, what's needed is to eliminate the cloud reliance and move more of the LLM processing locally, on the device. Apple already has what it calls the "Neural Engine" in the iPhone, a separate collection of circuits for running AI. However, the AI tasks performed by the Neural Engine -- tasks much less demanding than an LLM -- are likely to involve very carefully defined functions such as face recognition, where the use of the circuits has been carefully curated. 

Taking an off-the-shelf large language model and running it locally is bound to be a much more demanding task. 

Woodring bases much of his enthusiasm about this year's AI on a paper published this month by Apple researchers Keivan Alizadeh and colleagues, titled, "LLM in a flash: Efficient large language model inference with limited memory," which is [posted on the arXiv pre-print server](https://arxiv.org/abs/2312.11514).

**Also: [Humane's aspiring smartphone-killer 'Ai Pin' may be the most 2023 product yet](https://www.zdnet.com/article/humanes-aspiring-smartphone-killer-ai-pin-may-be-the-most-2023-product-yet/)**

The crux of the paper is that LLMs take up a lot of memory, and Apple has found a clever way to use the vast storage of the resident flash memory -- the stuff that holds the iPhone's files. With special software, an LLM can be easily moved into and out of main memory, DRAM, with the illusion of having a lot more DRAM than is typical on the phone.

As Alizadeh and colleagues write, the tactics they use with memory "enable running models up to twice the size of the available DRAM," and speed up the making of predictions on a device by as much as 25 times. 

The problem the authors tackle is that there just isn't enough DRAM on most mobiles, while LLMs keep getting bigger and bigger. "A 7-billion-parameter model requires over 14GB of memory just to load the parameters in half-precision floating point format, exceeding the capabilities of most edge devices," write Alizadeh and team, referring to the neural "weights" or "parameters," values that are stored in memory that give shape to a trained neural network. 

**Also:** [**Samsung's new Galaxy S24 beats the iPhone 15 Pro in one very meaningful way**](https://www.zdnet.com/article/samsungs-new-galaxy-s24-beats-the-iphone-15-pro-in-one-very-meaningful-way/)

Apple doesn't disclose amounts of onboard DRAM, but the site Everymac [cites third-party data](https://everymac.com/systems/apple/iphone/specs/apple-iphone-15-pro-max-united-states-a2849-specs.html) suggesting that the iPhone 15 Pro Max has 8GB of DRAM. Samsung's recently unveiled [Galaxy S24 Ultra](https://www.zdnet.com/article/samsung-unpacked-2024-recap-galaxy-ai-s24-ultra-smart-ring-and-more/) has 12GB of DRAM, [according to Samsung](https://shop-links.co/link/?exclusive=1&publisher_slug=itechdaily19598&url=https%3A%2F%2Fwww.samsung.com%2Fus%2Fsmartphones%2Fgalaxy-s24-ultra%2Fcompare%2F%3Fdevice-1%3Dsamsung-galaxy-s24-ultra%26device-2%3Dsamsung-galaxy-s24%2B%26device-3%3Dsamsung-galaxy-s24). 

Much more memory, of course, is available in the NAND flash storage in phones. The Pro Max has a terabyte of memory, as does the S24 Ultra. The greater issue is moving data back and forth. NAND flash is slower than DRAM memory, so fetching data from it each time is slower than operating out of DRAM entirely. 

Apple experiments with keeping the neural network in flash memory and putting only some of it in DRAM. 

Apple

What's more, moving data from the flash memory into the DRAM memory entails a transfer time, which introduces a delay, called latency, between what the user tries to do and the results. That could mean the user waiting seconds between, say, typing into an LLM prompt and getting a response -- just as bad as going to the cloud. Even moving from DRAM into the phone's central processor introduces a delay, the authors note. 

Their solution is to use a fundamental aspect of neural networks including LLMs: sparsity. Sparsity means that a lot of those neural weights that make up the neural network are actually empty. They have a numeric value of zero. They can be ignored, therefore, so that only a small number of the total weights need to be fetched from memory.

**Also: [Buying the Samsung Galaxy S24 for its AI features? Read the fine print first](https://www.zdnet.com/article/buying-the-samsung-galaxy-s24-for-its-ai-features-read-the-fine-print-first/)**

"LLMs exhibit a high degree of sparsity," write Alizadeh and team. "We exploit this sparsity to selectively load only parameters from flash memory that either have non-zero input or are predicted to have non-zero output."

The authors also come up with many clever techniques about _which_ of those non-zero weights to call from flash memory, things such as pre-fetching the weights that are most likely to be needed based on the prediction task that the user may trigger next.

The report demonstrates dramatic speed-ups when running two open-sourceLLMs: Meta's [Open Pretrained Transformer](https://arxiv.org/abs/2205.01068), and the [Falcon series of language models](https://arxiv.org/pdf/2311.16867.pdf) from the Technology Innovation Institute of Abu Dhabi.

Apple was able to reduce the latency of serving large language models.

Apple

There's just one problem with the hopes of Woodring and others for an iPhone 16 as a supercomputer for AI: The work in the research paper was done on a Mac. Specifically, Alizadeh and team developed all of their techniques on Apple's "[M1 Max](https://www.zdnet.com/article/apple-silicon-rosetta-m1-m2-m3-soc-why-these-terms-matter-to-every-computer-buyer/)" processor, which is only in the MacBook Pro and Apple's Studio desktop. That chip is substantially bigger and more powerful than the "A17 Pro" found in the iPhone 15\. 

Moreover, as the authors state, their tests don't touch on one of the things that users of pocket computers care most about: battery life. "A critical aspect for future exploration is the analysis of power consumption and thermal limitations inherent in the methods we propose, particularly for on-device deployment," they write. 

**Also:** [**Apple Silicon, Rosetta, M1, M2, M3, SoC: Why these terms matter to every computer buyer**](https://www.zdnet.com/article/apple-silicon-rosetta-m1-m2-m3-soc-why-these-terms-matter-to-every-computer-buyer/)

Nevertheless, the M-series silicon from Apple has generally found its way into mobile devices. The original M1 and M2 chips have ended up in versions of Apple's iPad Pro and iPad Air tablets. That means there is a continuum to both Apple's chips and software efforts such as the kind Alizadeh and team explore. 

It's possible that an "A18" processor in an iPhone 16 Pro Max could strike a balance between running smart sparsity and conserving battery life. It's also possible that the kind of approach discussed in the paper could be used with very small versions of LLMs as a first step. Both models tested in the paper by Alizadeh have 7 billion parameters, which makes them fairly small as LLMs go. Apple could go even smaller, below a billion parameters, to preserve energy _and_ memory usage _and_ CPU usage. 

Regardless of what shows up at WWDC, or in September's expected iPhone unveiling, one can presume the structure of the research by Alizadeh and team shows AI is coming out of the cloud and into your pocket sooner or later.

#### Apple

[iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get](https://www.zdnet.com/article/iphone-16-pro-and-pro-max-hands-on/ "iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get")

[My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)](https://www.zdnet.com/article/my-biggest-regret-with-upgrading-my-iphone-to-ios-18-and-im-not-alone/ "My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)")

[We've used every iPhone 16 model and here's our best buying advice for 2024](https://www.zdnet.com/article/iphone-16-pro-max-buying-advice-2024/ "We've used every iPhone 16 model and here's our best buying advice for 2024")

[6 iOS 18 settings I changed immediately - and why you should too](https://www.zdnet.com/article/6-ios-18-settings-i-changed-immediately-and-why-you-should-too/ "6 iOS 18 settings I changed immediately - and why you should too")

* [iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get](https://www.zdnet.com/article/iphone-16-pro-and-pro-max-hands-on/ "iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get")
* [My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)](https://www.zdnet.com/article/my-biggest-regret-with-upgrading-my-iphone-to-ios-18-and-im-not-alone/ "My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)")
* [We've used every iPhone 16 model and here's our best buying advice for 2024](https://www.zdnet.com/article/iphone-16-pro-max-buying-advice-2024/ "We've used every iPhone 16 model and here's our best buying advice for 2024")
* [6 iOS 18 settings I changed immediately - and why you should too](https://www.zdnet.com/article/6-ios-18-settings-i-changed-immediately-and-why-you-should-too/ "6 iOS 18 settings I changed immediately - and why you should too")

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
<li><a href="https://fox-info.techidaily.com/new-turnout-android-video-streams-counterclockwise-for-2024/"><u>[New] Turnout Android Video Streams Counterclockwise for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-efficiently-expanding-on-stardews-ginger-isle/"><u>[Updated] Efficiently Expanding on Stardew's Ginger Isle</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-unveiling-the-top-rated-srt-translators-for-zero-cost/"><u>[Updated] In 2024, Unveiling the Top-Rated SRT Translators for Zero Cost</u></a></li>
<li><a href="https://unlock-android.techidaily.com/7-ways-to-unlock-a-locked-honor-play-40c-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Honor Play 40C Phone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722899116584-apple-watch-not-connecting-try-these-6-solutions-for-a-successful-pairing/"><u>Apple Watch Not Connecting? Try These 6 Solutions for a Successful Pairing!</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/discover-the-ultimate-budget-college-laptop-that-outshines-macbooks-and-thinkpads-for-students-now-with-a-sweet-200-off-deal-zdnet-reviews/"><u>Discover the Ultimate Budget College Laptop That Outshines MacBooks and ThinkPads for Students - Now With a Sweet 200 Off Deal! | ZDNET Reviews</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/emojis-decoded-revealing-the-astonishing-backstories-behind-your-favorite-icons/"><u>Emojis Decoded: Revealing the Astonishing Backstories Behind Your Favorite Icons</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-positive-persuasion-techniques-for-listener-loyalty/"><u>In 2024, Positive Persuasion Techniques for Listener Loyalty</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/les-plus-performants-programmes-de-decoupage-video-comparatif-des-meilleurs-choix-en-2024/"><u>Les Plus Performants Programmes De Découpage Vidéo - Comparatif Des Meilleurs Choix en 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-no-hypervisor-detection-on-windows-sandbox/"><u>Overcoming No Hypervisor Detection on Windows Sandbox</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/secure-streaming-success-implementing-2fa-on-your-twitch-channel-made-easy/"><u>Secure Streaming Success: Implementing 2FA on Your Twitch Channel Made Easy</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/securing-a-spot-at-the-genius-bar-the-ultimate-guide-to-scheduling-apple-store-assistance/"><u>Securing a Spot at the Genius Bar: The Ultimate Guide to Scheduling Apple Store Assistance</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/streaming-on-the-go-using-a-mobile-hotspot-to-connect-your-fire-stick/"><u>Streaming on the Go: Using a Mobile Hotspot to Connect Your Fire Stick</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-common-issues-of-streaky-images-on-modern-televisions/"><u>Troubleshooting Common Issues of Streaky Images on Modern Televisions</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

