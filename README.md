# wmt_recorder_study
My MCU / Embedded Linux audio recorder study  

## Old, to be written      
* https://github.com/weimingtom/wmt_ai_study/blob/master/README_TODO_002.md#tflite-work  
* https://github.com/weimingtom/wmt_ai_study/blob/master/README_TODO_001.md#related-projects  
 
## Work  
* ESP32, Arduino IDE  
micro_speech_v7_tf200_single_file.rar  
micro_speech_v5_tf211_lib.zip  
https://github.com/boochow/TFLite_Micro_MicroSpeech_M5Stack  
https://github.com/tanakamasayuki/Arduino_TensorFlowLite_ESP32  

* ESP32, esp-idf  
blink_v2_micro_speech_success.tar.gz  

* Raspberry Pi Pico  
msys_v11_raspberry_pi_pico_v1.rar  
pico-microphone_v3.rar  
https://github.com/sandeepmistry/pico-microphone  

* PC, HTML5  
speech_v1.rar  
https://github.com/MimusTriurus/WebExperiments  
https://github.com/shawkatq/voice-commands-demo  

* Raspberry Pi 3B, Python  
https://github.com/weimingtom/asr_rpi3b_hello/blob/master/python/baidu_STT/Smart_fan.py  
https://github.com/weimingtom/wmt_speech_study  
https://github.com/SeeedDocument/MIC_HATv1.0_for_raspberrypi/blob/master/src/baidu_STT/Smart_fan.py  

* stm32f103zet6, inmp441, i2s  
WM8960_Record_v3_success_inmp441.rar  

* stm32f446, inmp441, sai    
nucleo-f446-ei-kws_v2_sai_success.rar  
https://github.com/smlee00/STM32-Keyword-Spotting-with-Edge-Impulse  
https://github.com/andysworkshop/usb-microphone  
https://andybrown.me.uk/2021/01/30/usb-microphone  

* stm32f446re, inmp441, i2s  
usb-microphone_v5_solve_printf_block_main_thread.rar  
https://github.com/andysworkshop/usb-microphone  

* 中科蓝讯AB32VG1, 耳麦回声    
mic.rar  
wav_player_rom.rar  
中科蓝讯AB32VG1开发实践指南在线文档  
https://docs.qq.com/doc/DTVVWWXpLRVl6cER2  
https://ab32vg1-example.readthedocs.io/zh/latest/introduction.html  
sdadc, Sigma-Delta ADC是一种目前使用最为普遍的高精度ADC结构，在精度达到20位以上的场合  
http://www.elecfans.com/d/1294184.html  
https://github.com/BLUETRUM  
https://gitee.com/bluetrum  
RT Thread Studio快速配置AB32进行音频输出  
https://blog.csdn.net/qq_45396672/article/details/117525626  

* stm32h743, NUCLEO-H743, sai, inmp441  
h743_inmp441_v2_stm32h743_sai_overclock.rar  
h743_inmp441_v1_stm32h743_sai_no_overclock.rar  

## Books  
* 嵌入式软件调试技术  
4.8 实例：音频采集与回放程序的调试  
OSS (Open Sound System) and ALSA  
SndKit  
https://github.com/weimingtom/embedded_linux_debugging_book_code/blob/master/source/chapter4/sndkit/SndKit.c  
https://gitee.com/weimingtom2000/embedded_linux_debugging_book_code/blob/master/source/chapter4/sndkit/SndKit.c  

* GNU/Linux嵌入式快速编程  
第15章 声音设备——SND  
https://github.com/giometti/gnu_linux_rapid_embedded_programming/tree/master/chapter_15  
Chapter 15 - Sound devices - SND  
search baidupan, GNU Linux Rapid Embedded Programming, Page 552.  

* 基于ARM Cortex-M4的DSP系统开发  
baidupan  

* 快速傅里叶变换_算法与应用  
baidupan  

## Ref  
* voice_wakeup, sndkit, dmic-test    
https://github.com/lishaman/minispeaker/blob/master/kernel-3.0.8/tools/voice_wakeup/test_app/sndkit.c  
https://github.com/gylzbk/x1000_kernel_v1.7/tree/master/tools/voice_wakeup   
https://github.com/EliasKotlyar/Xiaomi-Dafang-Software/blob/master/kernel/tools/dmic-test/dmic-test.c  
https://www.cnblogs.com/mengfanrong/p/4224783.html  
https://github.com/hx1056211238/ingenic-linux-kernel3.10.14-x1000-v6.0-20170428/blob/master/tools/dmic-test/dmic-test.c  
https://github.com/Winddoing/CodeWheel/tree/master/embedded/drivertest/dmic-test  
https://github.com/panddio/learn/blob/master/work/test/sndkit/sndkit.c  

* opensound.com, sndkit  
https://github.com/EliasKotlyar/Xiaomi-Dafang-Software/tree/master/oss/tutorials/sndkit  
http://www.opensound.com  

* 在CB5654上实现语音交互  
https://occ.t-head.cn/doc/docs/Chapter9-E5BC80E58F91E69DBF/CB5654E5BC80E58F91E69DBF/E5AE9EE78EB0E59CA8E7BABFE99FB3E4B990E692ADE694BEE599A8.html  

* SC5654板级适配指南  
https://developer.aliyun.com/article/770173  

* 智能语音终端开发板介绍 | 《无需从0开发 1天上手智能语音离在线方案》第二章  
https://developer.aliyun.com/article/772451  

### TODO  
* raspberry pi zero   
(TODO) buildroot recorder  
(TODO) https://github.com/weimingtom/buildroot_rpi0_hello  

* stm32h743vi  
test_ac6_stm32h743vi_v2_dma_bug.rar  
https://community.st.com/s/article/FAQ-DMA-is-not-working-on-STM32H7-devices  

* stm32f411re  
test_ac5_stm32f411re_vv15_benchmark.rar  
mlkws_stm32f411re_v8_first_success.rar  
simple_test_v3_stm32f411ce_run_success.rar  

* xr872  
https://gitee.com/tutuwin/xr872_-audio/blob/master/audio_record.c  
https://xradiotech-developer-guide.readthedocs.io/zh/latest/zh_CN/software-guide/#_4  

* PC, X86 Linux, Debian, RPD2017    
Blink_esp32_rpd2017_v2_success.tar.gz  

* PC, Windows, VS2013    
micro_speech_vv14_success.rar  

* Android  
(TODO, not yet published) https://gitee.com/weimingtom/xunfei  
weimingtom-xunfei-master.zip  
https://github.com/xiayouli0122/SoundRecorder  

* VS1053, XFS5152CE, VS1003, WM8960  
https://github.com/weimingtom/wmt_speech_study  

* Linkit 7688 (MT7688), arm linux    
https://docs.labs.mediatek.com/resource/linkit-smart-7688/zh_cn/tutorials/audio-playback-and-recording  

* BPI-D1 (Lamobo D1), arm linux  
https://github.com/Lamobo/Lamobo-D1/blob/master/src/samples/record_audio/AkAudioRecorder.c  

* ReSpeaker 2 Mics Pi HAT  
https://wiki.seeedstudio.com/ReSpeaker_2_Mics_Pi_HAT_Raspberry/  
https://wiki.seeedstudio.com/cn/ReSpeaker_2_Mics_Pi_HAT/  

* 新唐M480系列, M487JIDAE, NuMaker-PFM-M487开发板  
https://github.com/OpenNuvoton/M480BSP/blob/master/SampleCode/StdDriver/SPII2S_PDMA_PlayRecord/main.c  
http://www.nuvoton.com.cn/board/numaker-pfm-m487km/  
https://www.nuvoton.com.cn/export/resource-files/UM_NuMaker-M487KM_User_Manual_EN_Rev1.00.pdf  

* EasyARM-RT1052, 致远ZLG  
EasyARM-RT1052-sjsc.rar  
深入浅出Cortex-M7-i.MX RT1050 V1.01 .pdf  

* MIMXRT1064-EVK  
https://github.com/KeilChris/TensorFlow_MIMXRT1064-EVK_Microspeech/blob/master/mono_mic.c  

* FRDM-K66F  
SDK_2_9_0_FRDM-K66F.zip  
sai_edma_record_playback.zip  
frdm-k66f sai  
https://mcuxpresso.nxp.com/api_doc/dev/2163/a00247.html  

* 芯灵思全志SIN-V3S, arm linux  
SIN-V3s_Linux & QT用户手册_v2.0.pdf  

* 野火vs1053, stm32f103  
野火-VS1053用户手册.pdf  
http://doc.embedfire.com/products/link/zh/latest/module/audio/mp3_vs1053.html  

* 正点原子vs1053, stm32f103  
ATK-VS1053 MP3模块用户手册_V1.0.pdf  
http://www.openedv.com/docs/modules/other/VS1053.html  

* Recording Stereo Audio on a Raspberry Pi, inmp441    
https://makersportal.com/blog/recording-stereo-audio-on-a-raspberry-pi  
https://github.com/makerportal/rpi_i2s  
https://github.com/adafruit/Raspberry-Pi-Installer-Scripts/blob/main/i2smic.py  
https://github.com/adafruit/Raspberry-Pi-Installer-Scripts/blob/main/i2s_mic_module/snd-i2smic-rpi.c  
https://learn.adafruit.com/adafruit-i2s-mems-microphone-breakout/raspberry-pi-wiring-test  
https://github.com/opencardev/snd-i2s_rpi  

* i.mx 280, gst-fsl, libfslparser, libfslcodec, gstreamer, Linux media framework    
L2.6.35_1.1.0_130130_MM_CODECS_BUNDLE.tar.gz  
https://github.com/chenbd/gst-fsl-plugins  
i.MX28 Linux Multimedia Codecs  
https://www.nxp.com/products/processors-and-microcontrollers/arm-processors/i-mx-applications-processors/i-mx28-processors/multimedia-applications-processors-low-power-high-performance-arm9-core:i.MX280  

* MangoPi-R3 （芒果派R3）, allwinner（全志） f1c200s, tinycap, tinyalsa      
https://wiki.dfrobot.com.cn/_SKU_DFR0780_MangoPi-R3#target_17  
https://github.com/tinyalsa/tinyalsa  
https://github.com/aodzip/buildroot-tiny200/blob/master/package/tinyalsa/Config.in  
https://github.com/mangopi-sbc/buildroot-mangopi-r/tree/master/package/tinyalsa  

* Arduino Pro Mini, MAX9814  
SpyBug.ino  
Make Your Own Spy Bug (Arduino Voice Recorder)  
https://www.instructables.com/id/Make-Your-Own-Spy-Bug-Arduino-Voice-Recorder/  
https://github.com/TMRh20/TMRpcm  
Arduino+MAX9814制作简易录音机  
https://www.jianshu.com/p/2b031a7fd2e6  

* Fermion MEMS Microphone Sensor  
放大器增益为66，当没有检测到声音时，输出电压在0.66*VCC浮动  
https://wiki.dfrobot.com.cn/_SKU_SEN0487_Fermion_MEMS_Microphone_Sensor  

* nrf52, i2s  
https://github.com/gregtomasch/nRF52_24-bit-_I2S_Microphone_Audio_Recording_Utility  

* haas100  
https://github.com/alibaba/AliOS-Things/tree/master/solutions/audio_demo  
似乎有脚可以直接接驻极体麦克风，无需额外的音频芯片  

* stm32l496, alios-things developerkit, i2s      
https://github.com/alibaba/AliOS-Things/blob/rel_3.0.0/board/developerkit/audio_hal/audio.c  

* 全志r329  
https://r329.docs.allwinnertech.com/devboardstudy/r329evb5studyarecord/  

* DOPI Hi3516EV200开发板  
http://doc.dopi.vip/docs/first/first-1c79th4b95m28  

* wm8960, stm32f103zet6, i2s  
https://www.waveshare.net/wiki/WM8960_Audio_Board  

* nuc98  
https://github.com/OpenNuvoton/NUC980_Linux_Applications/blob/master/demos/alsa_audio/demo.c  

* nuc97  
https://github.com/OpenNuvoton/NUC970_Linux_Applications/blob/master/demos/alsa_audio/demo.c  

* ??? omega i2s  
https://onion.io/2bt-omega-i2s-audio/  
转，omega接i2s扬声器，居然可以在gain和vcc之间接一个电阻。。。  
（作者的解释是用于降低放大器增益（灵敏度？），提高音质）  

* widora mt7688 录音    
https://widora.io/audio  

* art-pi媒体扩展板, stm32h750, WM8988  
https://art-pi.gitee.io/website/docs/#/tutorial/README  
Art-Pi学习笔记9：如何使用art-pi的多媒体扩展板播放TF卡中的音乐文件  
https://club.rt-thread.org/ask/article/2849.html  
Art-Pi学习笔记10：优化多媒体扩展板的音频驱动添加录音功能  
https://club.rt-thread.org/ask/article/2872.html  
ART-Pi开发板, 媒体扩展板原理图  
https://gitee.com/RT-Thread-Studio-Mirror/sdk-bsp-stm32h750-realthread-artpi/blob/master/documents/board/ART-Pi_HW_V1.5/ART-Pi_SCH_V1.5_Release.pdf  
https://gitee.com/RT-Thread-Studio-Mirror/sdk-bsp-stm32h750-realthread-artpi/blob/master/documents/board/MEDIA-IO/SCH_MEDIA-IO_V1.2.pdf  
https://www.pianshen.com/article/18472048211/  

* micro:bit v2 record  
https://github.com/we-eff/RecordSavePlayAudioData  

* bk7252, bk7251  
https://github.com/bekencorp/bdk_rtt/blob/release/v3.0/docs/BK7251_Quick_Start_v1.0.pdf

* python-sounddevice  
https://github.com/spatialaudio/python-sounddevice  

* VAD, beken, RT-Thread BK7252 麻雀一号  
RT-Thread BK7252 麻雀一号开发板使用文档, 15 录音与播放录音使用例程, /test/mic_record.c      
search baidupan, 麻雀1号资料包_20210609.zip  
see bk7221u_release\beken378\func\vad  
https://github.com/bekencorp/bk7251_rtt_audio_sdk/blob/master/beken378/func/vad/wb_vad.c  

* IDO-SBC2D06  
Sigmastar/SSD201, 茄子nano  
http://doc.industio.com/docs/ido-sbc2d06/ido-sbc2d06-1cttultfpk26q  
sdk.tar.bz2  
DMIC  
http://doc.industio.com/docs/ssd201-sbc2d07/ssd201-sbc2d07-1cmdam5763k74  
AMIC  
http://doc.industio.com/docs/ssd201-sbc2d07/ssd201-sbc2d07-1cmdamnrkgk2p  
audio_all_test_case  

* P3510-2MIC, Pawpaw 木瓜电子    
https://docs.pawpaw.ltd/download/tool_and_app_download/  
https://docs.pawpaw.ltd/notes/  

* cb5654, and etc...  
https://gitee.com/cb5654_sdk  
https://gitee.com/w800_sdk  
https://gitee.com/w800_sdk/offline_audio_w800_rgb  
https://gitee.com/tg6101_sdk  
https://gitee.com/cb5631_sdk  
https://gitee.com/cb5654_asus_sdk  

* 香蕉派, EAI80    
https://github.com/BPI-SINOVOIP/BPI-EAI80-bsp  

* wm8731  
https://github.com/hughpyle/teensy-i2s  
官网介绍, 带耳机驱动器的编解码器  
https://www.cn.cirrus.com/products/wm8731/  
TLV320AIC23/WM8731音频模块/8731音频/WIFI语音/声卡  
https://item.taobao.com/item.htm?id=580141927800  

* art-pi  
https://club.rt-thread.org/ask/search.html?keyword=art-pi  

* Porting ARM's DSP examples to Maxim's M4-series LP microcontrollers  
https://github.com/MaximIntegratedTechSupport/ARM-DSP  

* rda5981, 在RDA上使用mbed编译运行KWS  
https://www.pianshen.com/article/3924524102/  

* 香蕉派D1, Lamobo-D1, 录音例子   
https://github.com/Lamobo/Lamobo-D1/blob/master/src/samples/record_audio/main.c  
https://github.com/Lamobo/Lamobo-D1/blob/master/src/samples/record_audio/AkAudioRecorder.c  

* V3s录音 交叉编译alsa linux  
https://blog.csdn.net/weixin_30301183/article/details/98466667   

* A USB Microphone built with an INMP441 and an STM32  
https://github.com/andysworkshop/usb-microphone/blob/master/Core/Src/main.c  
https://andybrown.me.uk/2021/03/13/usb-microphone/  

* 易百纳技术论坛，全志平台  
http://bbs.ebaina.com/forum-137-1.html  

* (TODO) STM32F37x38x SDADC （Sigma-Delta ADC）入门.pdf  
https://download.csdn.net/download/longonly120/11441172?utm_source=iteye_new    
Sigma-Delta ADC是一种目前使用最为普遍的高精度ADC结构，在精度达到20位以上的场合  
http://www.elecfans.com/d/1294184.html  
STM32F37x的SDADC使用流程（一）  
https://blog.csdn.net/wangjin5250/article/details/95068065  

* ab5325b  
http://www.bluetrum.com/product/ab5325b.html  
sdadc  
https://github.com/ZhiqingLi/Sdk_Refresh/blob/master/AB53XX_SDK/app/platform/libs/api_sdadc.h  
https://gitee.com/xiang_gang/Sdk_Refresh/blob/master/AB53XX_SDK/app/platform/libs/api_sdadc.h  
ab5325b  
https://github.com/nameiscn/GUI_V550/tree/c7e54a7fd9189522ac6fe8d9fefb62a283ce442a/B宝星DL-102/firmware/APP_AB5325A/platform/libs  
http://www.bluetrum.com/product/list-2.html  
ab32vg1  
https://ab32vg1-example.readthedocs.io/zh/latest/introduction.html  
https://club.rt-thread.org/ask/article/2643.html  
https://club.rt-thread.org/ask/article/2599.html  
中科蓝讯AB32VG1开发实践指南在线文档  
https://docs.qq.com/doc/DTVVWWXpLRVl6cER2  

* 无涯mt7688 录音  
https://www.hi-wooya.com/resource-view-37.html    
http://down.hi-wooya.com/开发套件/06th_WKA-M76S/01_UserManual（用户手册）/  

* 茄子派, 文档基于TOKOYAKI_DLC00V30版本SDK和IDO-SBC2D06-V1B开发板。  
http://doc.industio.com/docs/ido-sbc2d06/ido-sbc2d06-1ctuu864a7h1r  
第二十章 音频的配置  
http://doc.industio.com/docs/ssd20x-system/page_20  

* TTGO ESP32 0.96 OLED音乐频谱分析仪套件  
(dead) https://github.com/LilyGO/Music-Spectrum-Analyzer  
https://github.com/G6EJD/ESP32-8-Octave-Audio-Spectrum-Display  
https://github.com/kosme/arduinoFFT  
KY-038 麦克风放大器模块   
MAX9812  
(see taobao) KY-037  
https://github.com/tobozo/ESP32-Audio-Spectrum-Waveform-Display/tree/wrover-kit  
https://gitee.com/weimingtom2000/ESP32-Muziek-Spectrum-Analyzer-Kit  

* apollo-DuerOS  
https://gitee.com/weimingtom2000/apollo-DuerOS  
https://github.com/ApolloAuto/apollo-DuerOS  

* 关于I2S及音频小结  
https://blog.csdn.net/baiyibin0530/article/details/78728741  

* 友善之臂, Matrix外设库 (基于Linux API), 声音外设    
https://github.com/friendlyarm/matrix  
实际上nanopi也有一个关于声音传感器（Matrix - Sound Sensor）的驱动程序，称为Matrix库，  
这个Matrix库（又称为libfahw）类似wiringnp，但实现不同，属于Linux层面的封装，  
例如GPIO是通过Linux文件系统和gpio驱动程序来控制电平，有兴趣可以研究一下这个库：  
friendlyarm/matrix  
http://wiki.friendlyarm.com/wiki/images/e/eb/Matrix_API_Reference_Manual.pdf  
http://wiki.friendlyarm.com/wiki/index.php/Matrix_-_2%278_SPI_TFT#Download_Matrix_Source_Code  
https://wiki.friendlyarm.com/wiki/index.php/Matrix_-_Sound_Sensor  

* 基于EAIDK-310的传感器调试案例介绍（二）  
https://aijishu.com/a/1060000000083903  
EAIDK-310  
http://www.eaidk.com/download.php?class_id=109#txt2  
sesarch baidupan, Demo.zip    

* pmodi2s  
https://reference.digilentinc.com/pmod/pmodi2s2/reference-manual?redirect=1  
https://electronics.stackexchange.com/questions/525459/problems-interfacing-pmodi2s2-with-stm32h7  

* sai  
https://www.stmicroelectronics.com.cn/content/ccc/resource/training/technical/product_training/group0/11/91/8f/47/7b/0e/42/ca/STM32WB-Peripheral-Serial-Audio-Interface-SAI/files/STM32WB-Peripheral-Serial-Audio-Interface-SAI.pdf/_jcr_content/translations/en.STM32WB-Peripheral-Serial-Audio-Interface-SAI.pdf  
https://www.cnblogs.com/armfly/p/11168383.html  
https://github.com/keshikan/STM32H7_DMA_sample/blob/master/Src/main.c  

* HPM6750, with WM8960    
ebf_hpm6750_code_20230331.zip\audio_codec\src\WM8960.c  
https://doc.embedfire.com/products/link/zh/latest/mcu/hpmicro/ebf_hpm6750.html  
https://doc.embedfire.com/risc-v/hpm6750/quick_start/zh/latest/doc/chapter2/chapter2.html  

* FR8016HA  
我把FR8016HA开发板的声音播放跑通了，（1）烧录程序：不能用gitee最新版，  
要用旧资料的代码（会导致屏幕花屏，但功能正常）（2）需要用特定的安卓手机  
才能正常蓝牙传输wav文件，我用的是红米4A，安卓6，安卓是gitee上的SBC最新版  
（3）我接的喇叭是8Ω0.5W圆形喇叭（8R），带公头杜邦线（需面包板），  
原版没有，需要自备（4）按K1数次，然后按K2播放  

## other  
* https://github.com/CelliesProjects/ESP32_VS1053_Stream  
