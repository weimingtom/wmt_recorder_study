# wmt_recorder_study
My MCU / Embedded Linux audio recorder study  

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

* stm32f446  
nucleo-f446-ei-kws_v2_sai_success.rar  
https://github.com/smlee00/STM32-Keyword-Spotting-with-Edge-Impulse  

* 新唐M480系列, M487JIDAE, NuMaker-PFM-M487开发板  
https://github.com/OpenNuvoton/M480BSP/blob/master/SampleCode/StdDriver/SPII2S_PDMA_PlayRecord/main.c  

* EasyARM-RT1052, 致远ZLG  
EasyARM-RT1052-sjsc.rar  
深入浅出Cortex-M7-i.MX RT1050 V1.01 .pdf  

* MIMXRT1064-EVK  
https://github.com/KeilChris/TensorFlow_MIMXRT1064-EVK_Microspeech/blob/master/mono_mic.c  

* FRDM-K66F  
SDK_2_9_0_FRDM-K66F.zip  
sai_edma_record_playback.zip  

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

## Work  
* ESP32, Arduino IDE  
micro_speech_v7_tf200_single_file.rar  
micro_speech_v5_tf211_lib.zip  
https://github.com/boochow/TFLite_Micro_MicroSpeech_M5Stack  
https://github.com/tanakamasayuki/Arduino_TensorFlowLite_ESP32  

* ESP32, esp-idf  
blink_v2_micro_speech_success.tar.gz  

* Raspberry Pi Pico  
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

* ??? omega i2s  
https://onion.io/2bt-omega-i2s-audio/  

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
