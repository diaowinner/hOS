
HOS Hanzi system(diaowinner forked)
------------------------
                                                     简晶,diaowinner as 96,12


Setup it
---------
    HOS can install for any dir, System can rename
    Last, Edit AUTOEXEC.BAT of this path, So you can starting this!
汉字系统。

Use
------------
    1. Start             HOS←┘
    2. Quit             Q←┘ 或  CTRL+F5
    3. Set                 CTRL+F10
    4. Change Tips               右SHIFT(默认)
    5. Hanzi Input:
       ALT+F1           Pinyin(Shuang Pin)
       ALT+F2           Pinyin
       ALT+F3           Pinyin(Zi Ran)
       ALT+F4           Wang Yongmin's Wu Bi
       ALT+F5           Heng Shu Pie Na Zhe
       CTRL+ALT+F1      GB/T 2312-1980
       CTRL+ALT+F10     ASCII
       CTRL+ALT+L       Think(ALT+F1's word)
       CTRL+ALT+G       Grab words(any IME)
       CTRL+ALT+J       Auto Learn Word(Space is ok,Enter is cancel)
       CTRL+SPC         Cn/En IME
       SHIFT+SPC        A or Ａ
       CTRL+ALT+SPC     Input last word
    6. Any program has "/?" help.
    7. HOS Only has a 16px 24px Song with display and print
       Setup SuperVGA card, you can run 24.COM For 24px display.

Files
------------
System:
        HOS.BAT         Start
        Q.COM           Quit
        DDRV.EXE        Driver install(input your card, * is auto)
        TESTADP.EXE     Plug & play install(30+ card)
        KRNL.EXE        Kernel
        GMODE.EXE       BIOS/VESA mode set
        16.COM          16 px font change
        24.COM          24 px font change
IME:
        INT16.EXE       Key manager(Support WPS' any IME)
        IMD.EXE         IMD(Manager 10,input mabiao)
        ASE.EXE         Edit.com like

dirs.
------------
    There is 2 dirs. on system

    <DRV>       Drivers
    <DAT>       Data
