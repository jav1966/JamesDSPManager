# JamesDSPManager (Audio Effect Digital Signal Proccessing library for Android)
Merged with Omnirom DSP Manager features and able to run in all android rom include Samsung,AOSP,Cyanogenmod. 
This app in order to improve your music experience especially you want realistic bass and more natural clarity.
We don't work too much around with modifying Android framework instead of we integrate framework with DSP Manager, let it less depend on system framework.

JamesDSPManager merge with Omnirom features: 

Basic:

1. Compression
2. Bass Boost
3. Virtualizer
4. 14 Band Hybrid Equalizer (1 low shelf, 10 band shelves, 3 modified high shelves)

Omnirom extra/My own creation:

1. Adjustable Low pass filter(Bass Boost)
2. Stereo Widen
3. 2 more custom bass boost mode
4. Special equalizer

On development:

1. Linear phase FIR Equalizer------Status: Windowed Sinc FIR Coefficient generator works!
2. Equalizer presets
3. Parameterized Room Convolution

Now work on AOSP, Cyanogenmod, Samsung on Android 5.0 and 6.0 (TESTED)

#Download Link
1. See my project release page
2. Lollipop(Github release): https://github.com/james34602/JamesDSPManager/releases/download/Milestone1/JamesDSPManager_Lollipop.zip
3. Lollipop: https://drive.google.com/open?id=0B5xvL_71lUP_b1NOdDZoUGUyQ0U
4. Lollipop(百度雲網盤連結): http://pan.baidu.com/s/1mhYsbAo
5. Marshmallow(Github release): https://github.com/james34602/JamesDSPManager/releases/download/Milestone1/JamesDSPManager_Marshmallow.zip
6. Marshmallow: https://drive.google.com/open?id=0B5xvL_71lUP_QVJ6YUh2RXI5NVE
7. Marshmallow(百度雲網盤連結): http://pan.baidu.com/s/1o7JuSTO
8. (OUTDATED)Marshmallow(CWM Flashable): https://drive.google.com/open?id=0B5xvL_71lUP_aF9IdzdaUjBQSDQ


#Development
No public test subject!

#Important
We won't modify SELinux, let your device become more safe.
Also, it is good for you to customize your own rom or even port rom, upgrade your music experience!

#How to install?
See readme in download link.

#Contact
Better contact me by email. Send to james34602@gmail.com

#Credit
DSPFilter.xlsx is a tool for you to desgin IIR Biquad Filter, it is a component from miniDSP.

RBJ_Eq.xls is a RBJ Biquad Equalizer designer. For me, not very useful and I will not implement it, but could be a reference to designing equalizer.

#Structure map generated by Understand (Hosted on rawgit)
<a><img src="https://rawgit.com/james34602/JamesDSPManager/master/libjamesdsp_StructureMap.svg"/></a>