# 100 Days Of Code - Log

### Day 0: January 05, 2017

**Today's Progress**: Decided what to do BRarvis - a brazilian version of Jarvis. I will use Intel Deep Learning SDK as a test.

**Thoughts:** Well, I have to have a Linux server to use SDK on a Windows client. I virtualised minimal CentOS7 on VirtualBox and set Bridged Mode of network interface, like [here](http://www.techrepublic.com/blog/diy-it-guy/using-virtualbox-vms-on-your-networks-subnet/). I had to configure manually network interface on CentOS like [here](http://www.mustbegeek.com/configure-static-ip-address-in-centos/) and them updated yum. I also installed wget, downloaded intel script with it. Then I extracted and ran script with bash. After installed it on server, I tried to install client SDK on Windows, however it gives me an error. But actually, I saw that was only necessary first installation, second made the same thing from Windows through SSH (actually it was kind of running before Windows installation).

**Link to work:** Nothing to show yet.

**TODO:** Make another clean CentOS7 VM and let Windows install OR redo VM and install from there again.


### Day 1: January 06, 2017

**Today's Progress**: Installed properly Intel Deep Learning SDK on Ubuntu. Had to find another speech recognition API (in this case Juluis) because IDL SDK only works with image classification.

**Thoughts:** Ah, ok. I tried to install IDL SDK on an Ubuntu Server VM and it worked like a charm. In the middle of installation, I found out that IDL SDK's webpage talked about speech recognition somewhere, however, at technical specifications, they say that it just works with image classification. Oh, fine. What should I do now? I've spent a lot of time trying to install this and got it working properly and then I have to leave and find some other API for speech recognition OR I do something about image classification. Well, I will leave IDL for now because I am not really interested in image recognition that much. So I have to find another speech recognition API to carry on with BRarvis. I’ve found one from Google, but it is paid (actually free for 60 days), so thank you. Other APIs did not have PT-BR, so I have to find some which I could use in Brazilian Portuguese (it would be weird if brazilian version of Jarvis would talk only in English :p). I found an API based on Julius (see what is [here]( http://julius.osdn.jp/en_index.php?q=index-en.html#feature)) called Coruja0.2 (see what is [here]( https://code.google.com/archive/p/lapsapi/downloads)) however, I cannot make it run for some reason. Looking at code, what I can see is that basically they used Julius and created a grammar which would correspond to brazilians’ phonemes. They only put some words (probably for their purposes). So I decided to work on this Julius and make something with it. Another thing I can see is that Coruja’s developers used something called Common Runtime Language, which made possible to use all .Net languages. So they mixed C++ and C#. I will have a look on that tomorrow. Well, it’s all in a day's work. ;)

**Link to work:** Nothing to show yet.

**TODO:** Study how Julius works.
