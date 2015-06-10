---
layout: post
title: Living With The Chromebook Pixel
date: 2015-06-10 14:28
---

The Chromebook Pixel is an unusual device. Contrary to every other Chromebook and the idea behind them, the Pixel is  expensive with powerful hardware on a very limiting operating system that serves as only a web browser. Yet regardless, I bought one anyways because I was intrigued by the device and a few tricks it has that people who haven't looked into ChromeOS devices aren't aware of.

_![](https://s3.amazonaws.com/yifanj.in/DSC_1231.jpg)_

For starters, the Pixel comes in two versions - a normal version with an Intel i5, 8GB of RAM, 32GB SSD costing $999 and the LS with an Intel i7, 16GB of RAM, and 64GB of SSD storage costing $1299. The screen that the Pixel uses is the same as the 2013 version at 2560x1700, which is an fairly unusual aspect ratio of 3:2 on a 12.85 screen. It's size is fairly similar to the 13" MacBook Pro with Retina display and about just as heavy. It's hardware is actually very comparable to the Macbook Pro and costing somewhat less making the main difference the SSD and the operating system.

![](https://s3.amazonaws.com/yifanj.in/DSC_1219.jpg)

So why not spend the extra $200-300 for a Macbook Pro since it has a more robust operating system? For me, it's because Chromebooks support something called [crouton](https://github.com/dnschneid/crouton). It essentially allows for the running of both Linux and ChromeOS at the same time, even in a browser tab with the help of an extension. Through crouton, pretty much everything ends up working smoothly in terms of hardware support. Installing Linux natively on the hardware is also simple as the Pixel fully supports SeaBIOS and there is a [kernel](https://github.com/tsowell/linux-samus) to fix hardware issues that you may encounter out of the box. Simply because of this, the Pixel became a really high contender as it became a Thinkpad alternative - great hardware with great Linux compatibility.

And why Linux? I wanted to use something a bit different, especially since I already had a Mac<sup id="fnref:1"><a href="#fn:1" class="footnote">1</a></sup>. I would mainly use this for web programming and doing some light writing as well, which means that Linux was perfectly fine for this task. I already had experience with Linux and with the cheaper price tag, it was worth a try (and I had a 14 day return period).

**Google's Macbook Pro**

If Google made the Macbook Pro, this is what it would look like. It has the aluminum finish like the Macbooks. Throughout, it's not clear that it's even made by Google at all. The only real indications of it are from the chrome text right above the keyboard and the lightbar in use.

_![](https://s3.amazonaws.com/yifanj.in/DSC_1187.jpg)_

In use, it just feels solid with its entirely metal case (screen hinge is plastic) and the glass screen. It is heavier than the Macbook Air but it's in the Macbook Pro weight class, which is perfectly fine for me. It is a more boxy design but that's fine by me. I like the more basic look and the weight is fairly distributed too.

![](https://s3.amazonaws.com/yifanj.in/DSC_1249.jpg)

![](https://s3.amazonaws.com/yifanj.in/DSC_1224.jpg)

The lightbar on the top of the lid is probably the main distinction that Google has and I like it. When in normal use, it just has the Google rainbow but in addition to providing asthetics, it has a practical feature too. You can "knock" the top of the laptop and the bar will give you a rough estimation of your battery life. It's gimmicky but yet also practical. It gives you a quick glance at how much battery you have left and lets you make a judgement on whether or not to plug it in.

![](https://s3.amazonaws.com/yifanj.in/DSC_1188.jpg)

I see the Pixel as a more low key Macbook Pro and that's not a bad thing. It's built well with a beautiful display that can compete with the design of the retina Macbook Pros.

**The Hardware**

The keyboard on the Pixel is one of the best laptop keyboards I've used. At the very least, its comparable to the keyboard of the Macbook that I have and while not as great as the older ThinkPads I own (T60 and T410), it's still great by modern standards. There is enough depth and has a bit of a springy feel to it which allows it to feel not as mushy as other laptop keyboards. For the programming that I've done on it, it feels fine even after longer periods of typing and my speed is just fast as I would be using the Logitech K811 or the Macbook. It does also have backlight which only comes on when your hands are over it, which is nice but I've never been a big fan of backlighting myself.

![](https://s3.amazonaws.com/yifanj.in/DSC_1235.jpg)

Something that is jarring is the keyboard layout. The command or Windows key is eliminated for a search key where the caps lock button normally would be. Additionally, the fn keys are replaced with ChromeOS keys that have special functionality such as forward and backwards, refresh, full screen, etc.

![](https://s3.amazonaws.com/yifanj.in/DSC_1238.jpg)

While the lack of the Windows/Command key normally wouldn't be a problem for ChromeOS, it does creates a weird situation in Linux. The search key becomes the modifier button which due to muscle memory, would actually be where alt is located. This has actually become one of my biggest gripes with the Pixel because I do switch computers often and would often hit the wrong button turning on Caps Lock or hitting Alt on the Pixel. The fn keys don't serve much of a problem in Linux as they can be easily configured to normal F1-F12 keys.

The trackpad found on the Pixel is also quite good. It's a glass trackpad similar to the one found on the MacBooks. ChromeOS supports multifinger gestures quite well and the trackpad detects them fairly accurately.<sup id="fnref:2"><a href="#fn:2" class="footnote">2</a></sup> I found the size to be a bit smaller than what I was used to on a Macbook but it is large enough for use and something that I got used to quite quickly. A problem that I did have is in Linux, there were quite a few problems but some of that seemed to come from crouton and drivers. There were initally cursor problems for me which got resolved after seeing this [post](https://github.com/dnschneid/crouton/issues/1519) and installing the 01.org drivers. However, there still seemed to be some problems, such as jumping from time to time or clicks not being registered. From use, I'm guessing that I might slightly touch the trackpad while typing with my palm but regardless, I do encounter some issues that I'm not really seeing in ChromeOS.

While I'll leave Anandtech to do [display testing](http://www.anandtech.com/show/9082/the-chromebook-pixel-2015-review/2), I peresonally really like the display. Even if it's not perfect sRGB, its probably one of the best laptop screens I've ever seen and it's sharpness, brightness, and colors are good enough for me<sup id="fnref:3"><a href="#fn:3" class="footnote">3</a></sup>. It is definitely extremely glossy, something I didn't expect. If you are in the sun all day, the glare is pretty bad and can be a big problem. The aspect ratio of 3:2 is a bit odd but it only serves as a problem if you just only look at video (since it causes letterboxing). For scrolling through web pages and working with text, the aspect ratio actually works quite well since there is more vertical space. Ideally, I would have liked 4:3 more but 3:2 is fine. There really isn't much else to say about the display other than it has a high DPI, good colors, and works well in ChromeOS (has native scaling).

![](https://s3.amazonaws.com/yifanj.in/DSC_1244.jpg)

In Linux, a lot of DEs supported HiDPI out of the box (I tried GNOME and Unity) but also worked fine in i3 with `Xft.dpi: 223`. Annoyingly, HiDPI is pretty broken in xiwi (the in browser tab with crouton) right now which is a big inconvenience. You can switch tabs quite easily when running it in X11 but it is a bit more inconvenient. This is a problem that the crouton devs have acknowledged though and may be fixed in the future.

![](https://s3.amazonaws.com/yifanj.in/DSC_1245.jpg)

The Pixel's screen also has touch capabilities, which is a feature that has really grown on me. I've always thought touchscreens on laptops as kind of a gimmick that never seemed useful. Yet after getting the pixel, I've been using it more and more. For stuff like pinch to zoom, and hitting some buttons or icons, I find myself using touch for that rather than going down to the trackpad. It's simply faster for me to use touch for those simple things because my hand was probably already on the keyboard for that and rather than going down and then moving the trackpad and moving the cursor, one hand can just move up and hit the touch target and resume using the keyboard. Again, touch does work in crouton with Linux but like the cursor, sometimes there are a few problems with it being registered. The main downside with touch is that it leaves plenty of fingerprints which requires a more frequent wiping of the screen. The touchscreen definitely isn't necessary but its a nice addition.

_![](https://s3.amazonaws.com/yifanj.in/DSC_1247.jpg)_

**The Battery**

The battery life on this laptop is crazy good. Google says the Pixel can last for 12 hours and it makes good on Google's claims. With a lot of video and more intensive programs in Linux, the battery life drops but it still lasts. I've never really had a battery problem with the Pixel and that's good enough for me.

Google ships a charging brick with the Pixel and it really resembles the Macbook chargers. The charging brick is a standard 60w USB Type-C charger and the charging times are quite good. I've found it to charge much fasters than other laptops I've used, which is a good thing. The quick charging and the long battery life means that with this, I've rarely had to worry about power even without being near a power outlet.

![](https://s3.amazonaws.com/yifanj.in/DSC_1205.jpg)

**The Ports**

Google has put two USB Type-C ports on either side, two USB 3.0 ports and headphone jack on the left, and SD on the right. The novelty here is definitely the USB Type-C ports, which can be used for a plethora or purposes here - charging, video out, and data. USB Type-C really looks very similar to Lightning. It's reverseable and is only a little bit thicker than Lightning. This does mean that the charging port is just a reversable USB cable which is pretty cool. Additionally, you can charge from either side, which doesn't sound very special but it means that as long as you are near an power outlet, you can plug it in. If you have an USB C to USB A cable, you can even charge it off other chargers albeit charge time will be longer. Something that I haven't tried yet but want to try is using an portable battery and seeing if I could get power from that but I'm skeptical.

![](https://s3.amazonaws.com/yifanj.in/DSC_1259.jpg)

![](https://s3.amazonaws.com/yifanj.in/DSC_1243.jpg)

USB Type-C being an upcoming standard, means that the current offering of accessories and cables are quite limited. Monoprice, Google, and Apple are the main ones that sell USB Type-C cables and especially the display ones can be quite expensive. I've only bought an USB Type-C to Type-A cable currently and definitely am waiting for more cables to emerge in the market. I would have liked getting the displayport adapter and if this was my only laptop, I would have bought it.

![](https://s3.amazonaws.com/yifanj.in/DSC_1207_Edit.jpeg)

The USB Type-C port definitely needs a bit of force to remove the cable - something that I didn't really expect. That means that unlike Magsafe, it won't be easily removed but also provides a bit of risk astripping on the cable could mean sending your laptop flying. It isn't too big of a deal, just something different from what I was used to.

![](https://s3.amazonaws.com/yifanj.in/DSC_1212_Edit.jpeg)

The SD card slot pretty much only works with full size SD cards. Luckily, cards go in deeper than Macbooks which means that its quite possible to high a SD card permenantly as extra storage as only a little bit sticks out (and also means stuff like NiftyDrive or Transcend JetDrive won't work) if not for the fact that the speed is not great. Google has apparently used USB 2.0 for the SD card, which means unlike the other ports in the computer, it'll actually be quite slow. I've thought about buying a 128GB or 256GB SD card and just leaving it in as storage but the 2.0 speeds had me second guessing. Additionally, I had a quite a bit of trouble having the system stop copying to an SD card midway. It could be that it was extremely slow but regardless, using an SD card is not a great experience.

**The Little Things**

It looks thick but is only slightly thicker than the Macbook Air's thickest point. Only slightly thicker than my iPad Mini 3 as well.

![](https://s3.amazonaws.com/yifanj.in/DSC_1192.jpg)

![](https://s3.amazonaws.com/yifanj.in/DSC_1196.jpg)

The boot speeds and page loading speeds are extremely fast. Since ChromeOS is a light operating system, it boots faster and loads web pages faster than my Macbook. The CPU is a bit overkill for just using Chrome but I don't mind. I've played YouTube 4K videos just fine which is a great sign.

I've read online that the speaker quality is terrible but I found it to be alright. Its pretty much onpar with my Macbook Air.

Local video playback in ChromeOS is terrible. Most formats aren't supported and to use subtitles from a file, I had to get another video player from the Chrome web store which was also not great to use. I've switched to using mpv in Linux for any local video playback.

Lightbar is sometimes a bit too sensitive. Having the lid closed and setting it on a desk causes the battery lightbar indicator to come on. Setting something heavy on the desk nearby or knocking the desk also sometimes causes it to trigger as well.

Fans very occasionally come on. You can hear it but it usually becomes inaudible quickly. Heat hasn't been an issue for me either.

With an Android phone and Bluetooth on, you can have something called proximity unlock which unlocks your computer if the phone is nearby and unlocked. I've not used it too much because I don't use my Android phone too much and I'm afraid of it affecting battery. Does need your Android phone to have Android Lollipop and Bluetooth LE.

Some of the ChromeOS apps are useful although I don't use that many. Some of the apps are also just the Android versions which means they don't exactly fit in. Currently, pretty much only using Caret (an text editor), Authy, Evernote, and Google Docs. Most of the other apps are just basically bookmarks and open up the web site in Chrome except running it in it's own Window. There is [chromebrew](http://skycocker.github.io/chromebrew/) which is a package manager for ChromeOS but I haven't tried it.

**Final Thoughts**

The Chromebook Pixel (2015) definitely isn't a laptop for everyone or even for most people. There are compromises you have to make in regards to usig ChromeOS or even using Linux. For me thought, it works perfectly for what I wanted: a semi-powerful development machine with a great screen. Linux isn't perfect but it's a lot easier to set up and the stuff that I need for programming and writing is all there. The hardware is great and in spite of those trade-offs, it's a good fit for me.

![](https://s3.amazonaws.com/yifanj.in/DSC_1228.jpg)

<div class="footnotes">
  <ol>
    <li id="fn:1">
      <p>2013 Macbook Air 13"<a href="#fnref:1" class="reversefootnote">&#8617;</a></p>
    </li>
    <li id="fn:2">
      <p>Trackpad accuracy in regards to gestures have been a frequent problem for me on   Windows laptops and the previous Chromebook I was using (Toshiba Chromebook 2).<a href="#fnref:2" class="reversefootnote">&#8617;</a></p>
    </li>
    <li id="fn:2">
      <p>I'm not doing much photo editing or that sort on here or at least until Lightroom ever comes to Linux. SD card is also limiting which I'll be addressing.<a href="#fnref:2" class="reversefootnote">&#8617;</a></p>
    </li>
  </ol>
</div> 
