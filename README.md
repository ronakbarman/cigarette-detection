# cigarette-detection
To detect cigarettes in video clips and censor them to hinder children from idolizing smoking.

Nowadays cigarettes have become a part of our daily lifestyle which can cost someone’s life. But we never thought that tobacco production and cigarette use should be banned because it leads to deforestation and wildlife fire. Tobacco smoke contains about 70 carcinogenic substances, including - carbon monoxide, tar, arsenic, cyanide, benzene, formaldehyde, methanol, acetylene, ammonia, lead etc. 

Censoring nicotine and tobacco material is beneficial, particularly to the youth as they idolize the actors in movies who smoke as they seem “cool”. 

The main function of the project will be to detect smoking scenes or cigarette in any video clip and preferably blur them via an automated process. 

Firstly, the videos are broken into frames and then the region of interest (ROI) is extracted after detection the area that contains the cigarette.

Then the ROI of each frame is pixelated and then pasted back to the original frame which gives us a ‘censored frame’.


Then all the frames are stuck back together to create the ‘censored video’.

[uncensored images](image12uncensored.jpg)
[censored images](image12.jpg)
