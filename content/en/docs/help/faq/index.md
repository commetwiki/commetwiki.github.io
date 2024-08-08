---
title: "FAQ"
description: ""
lead: "Some FAQs related to torrenting and COMMET. If your issue is not listed here then you can ask that in the matrix space."
date: 2023-08-14T21:07:33+05:30
lastmod: 2023-08-14T21:07:33+05:30
draft: false
images: []
menu:
  docs:
    parent: "help"
    identifier: "faq-26e113f525576357e3df22dcca97fdd4"
weight: 999
toc: true
---

### How to Download a torrent?

----

>- Download a Torrent client first, you can choose any client from the [recommended](/docs/resources/get-start-torrent/#torrent-clients-we-recommend) ones or any other of your choice.
>- Go to the link of the torrent you want to download, we'll take 1337x as an example here.
>- Riht click on "magnet link" and copy the link as shown below

<br><br>

![Image](https://imgsaver.com/images/2023/08/14/cplink.gif)

<br><br>

>- Open qBitTorrent, head to open link, paste the link in the textbox, click ok.
>- You should now get a new window to select download path. Also, check the files you want to download.
>- Click OK, now the download should start.

<br><br>

![Image](https://imgsaver.com/images/2023/08/14/addlnk.gif)

<br>

### How to create a torrent?

----

>- We'll again use qBitTorrent for this tutorial, you may use any client of your choice. This tutorial remains relevant irrespective of the personal choice of client
>- Have your files/folder ready. If you want to upload multiple folders then you should organize all of them in a single folder.
>- Click on "Tools", available in the menu bar. Navigate to "Torrent Creator" from the drop down menu that just opened and click it. *Alternatively, you can just use the keyboard shortcut Ctrl+N to open "Torrent Creator".*

<br>

![Image](https://imgsaver.com/images/2023/09/22/image.png)

<br>

>- A new window will open, as shown below.

![Image](https://imgsaver.com/images/2023/09/22/imagec9d5d9d3c4b07fee.png)

>- Let's learn about each of the options that the window shows us. Path: here you let qBitTorrent know the location of the file/folder you wanna make a torrent of.
>
>- Click "Select file", only if your torrent has one file, it'll open your file browser, navigate to the file you want to make a torrent of. You'll see that the textbox beside "Path" has been updated to the location of the file you just selected. To make a torrent of a folder, the process is exactly the same except you click "Select Folder" and navigate to the folder you want to make a torrent of.
>
>- Torrent version, prefer V1 because it is supported by all the clients. If you're sure that the downloader has a client that supports the other versions, only then select the other options.
>
>- Piece Size doesn't matter a lot these days as most people have faster internet nowadays, except if there're any piece size limitations by the clients (which I havent seen in modern clients) or if the torrent is huge like 300-500 GB. After googling a bit, it seems like 1200-2200 is the optimum number of pieces as suggested in this [article](https://torrentfreak.com/how-to-make-the-best-torrents-081121/) by Torrent Freak. Select the piece size which brings the number of pieces in that range (you can see the number of pieces by selecting "Calculate number of pieces")
>
>- Don't check "Private Torrent" unless you're uploading to private trackers.
>
>- "Start seeding immediately" does what it says.
>
>- Put your trackers (one tracker per line) in the textbox provided by "Tracker URLs:". You can find a list of trackers [here](/docs/resources/get-start-torrent/#trackers).
>
>- You can add any comments in the comment section, it does not affect the metadata of the torrent file.
>
>- Finally, select "Create Torrent". It might take some time, depending on the file/folder size. You'll be prompted with a file explorer to select the path where you want to save the torrent file. Select your preferred path, click OK. That's it! You have successfully created a torrent.

<br>

### I have downloaded the files of a torrent and I want to share the files of the torrent with my friend but I forgot from where I got the torrent file. What do I do now?

----
You can find the .torrent file that you downloaded and share it, if you dont have the torrent file then you can share the magnet link. To copy the magnet link of a torrent from your torrent client: right click on the torrent-> select "Copy"-> Select "Copy Magnet Link".

![Image](https://imgsaver.com/images/2023/09/22/image8696cafbebe6d9b6.png)

<br>

### Best torrent clients?

----
I prefer the open source ones: qBitTorrent, Transmission, Deluge etc. More [here](/docs/resources/get-start-torrent/#torrent-clients-we-recommend)

<br>

### Best VPNs for torrenting and privacy?

----
[Mullvad](https://mullvad.net/en) (one of the best for privacy), [Torguard](https://torguard.net/) (one of the best for torrenting), [PIA](https://www.privateinternetaccess.com/), [Proton](https://www.privateinternetaccess.com/).

<br>

### What about free VPNs?

----
None. Proton free version could be an option but it is pretty limited (no p2p). [Goodbyedpi](https://github.com/ValdikSS/GoodbyeDPI) can be used to bypass isp restrictions. [1.1.1.1](https://one.one.one.one/) WARP and proxy services like proxyninja etc are some other options to bypass ISP restrictions.
is another good option for bypassing
