---
layout: post
tags: 
- ds
- leak
- debug
title: Nintendo DsiWare Leak  
thumbnail: /public/consoles/Nintendo 64.png
image: /public/images/leaks/DsiWareLeak.jpg
permalink: /dsiwareleak
breadcrumbs:
  - name: Home
    url: /
  - name: Leaks
    url: /leaks
  - name: Nintendo DsiWare Leak 
    url: #
recommend: 
- leak
- ds
editlink: /leaks/DsiWare.md
twitterimage: https://www.retroreversing.com/public/images/leaks/DsiWareLeak.jpg
updatedAt: '2020-09-20'
---

As part of the Platinum Leak on the 9th of September 2020 a ton of DsiWare titles were leaked, including debug versions of games like Legend of Zelda Four Swords remaster.

{% include link-to-other-post.html post="/platinumleak" description="For more information on the rest of the Platinum check out this post." %}

The Platinum leak contained an archive called **generic.7z** it is inside this that you will find the **DSiWareROM.rar** archive covered in this post

# DSiWare ROMS (DSiWareROM.rar)
The **DSiWareROM.rar** archive contains a ton of DSiWare ROMS in **TAD** format. The repository is split into folders based on the date, presumably from when Nintendo sent the data to iQue.

Apparently **TAD** files are DSIWare applications that have been exported to the SD card [^1].

All of the ROM files have the prefix **SPD** which is Nintendos Software Planning Devision [^2], which is where these DsiWare titles were sent from to iQue.

You can use the **TWL-DW_data.xls** from previous leaks to look up the 4 character code of the game (e.g KEJJ).

The folders are:
* **20090722** - contains Japanese DsiWare such as ELECTROPLANKTONâ„˘ Marine-Crystals (**KEJJ_SPD-02817.tad**)
* **20090925** - contains even more Japanese DsiWare such as Sleep record alarm clock (**KMZJ_SPD-03107.tad**)
* **20091223** - unknown DsiWare such as **SPD-03408_chample0923f.tad**
* **20100120** - two unknown DsiWare including **SPD-03482_TKA2J00.tad**
* **20100127** - just contains **SPD-03521_SikakuDSi_1015.tad**
* **20100203** - two unknown DsiWare including **blocker_dsi_TwlRomSymbol_2009_1008_1040_r27659.tad**
* **20100215** - Two different versions of Starship **Starship_TwlRomSymbol_2009_1028_1122_r28723.tad**
* **20100302** - Unknown DsiWare **SPD-03623_TKSRE00.tad**
* **20100310** - Contains Pinball and Rittango
* **20100324** - Debug version of **Kaite Oboeru: Shashin Tango**  and **Kaite Oboeru: Eitango Chou** from Intelligent Systems
* **20100405** - Debug version of **SPD-03723_KKR1009_1D.tad**
* **20100427** - Contains two unknown DsiWare such as **SPD-03776_TK3LJ00.tad**
* **20100603** - Contains FacePilot and DigiQ
* **20100607** - Contains DsiGolf and another unknown title
* **20100930** - Contains Karuta
* **20110922** - Contains a debug version of Knife (**SPD-05577_KQ9J_DEBUG_2011_0915_1547.tad**) and debug documentation for it

## DSiWare Titles included
The DSiWare included in both **20090722** and **20090925** folders are listed in the table below along with their name in both Japanese and English.

FileName | DSiWare Name
---|---
KAAJ_SPD-02799.tad | AQUARIO (Art Style ă‚·ă?Şă?Ľă‚ş)
KADJ_SPD-02799.tad | DECODE (Art Style ă‚·ă?Şă?Ľă‚ş)
KAGJ_SPD-02808.tad | ă?‚ă?¤ă‚?ă‚‹ç¬‘éˇ”ĺ¸ł (Collecting smile books?!)
KAHJ_SPD-02799.tad | HACOLIFE (Art Style ă‚·ă?Şă?Ľă‚ş)
KAKJ_SPD-02799.tad | nalaku (Art Style ă‚·ă?Şă?Ľă‚ş)
KAPJ_SPD-02799.tad | PiCOPiCT (Art Style ă‚·ă?Şă?Ľă‚ş)
KASJ_SPD-02799.tad | SOMNIUM (Art Style ă‚·ă?Şă?Ľă‚ş)
KAVJ_SPD-02799.tad | DIGIDRIVE (Art Style ă‚·ă?Şă?Ľă‚ş)
KBGJ_SPD-02803.tad | ă?ˇă‚‡ă?Łă?¨DSć–‡ĺ­¦ĺ…¨é›† ä¸–ç•Śă?®ć–‡ĺ­¦20 (World literature 20)
KBRJ_SPD-02807.tad | ă?•ă‚©ă??ă‚ąă‚żă?łă?‰ä»?ă?Ť ă??ă?łă?–ă?©DXă?©ă‚¸ă‚Ş (Bumbra DX Radio with Photo Stand)
KCPJ_SPD-02799.tad | ă?§ă?Ťă?™ă?Žă??ă?łă‚Żă?«ă?‘ă??ă‚Ż (Too much tingle pack)
KD9J_SPD-02803.tad | ă?ˇă‚‡ă?Łă?¨Dr.MARIO
KDNJ_NWD-00151.tad | ă?»ă?Ľć—Ąč·Żç·šĺ›ł 2009 (Hobonichi Route Map 2009)
KE3J_SPD-02799.tad | ă?‚ă?ťă?ąă‚‹çµµćś¬ă€€ă?žă‚¤ă?łă?‰ă?†ă?ł (Picture book to play with Mind Ten)
KEAJ_SPD-02817.tad | ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?łă€€ă??ă?¬ă?Ľă?”ă?Ľ (Electroplankton trappy)
KEBJ_SPD-02817.tad | ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?łă€€ă?Źă?Ťă?łă?śă?ł (Electroplankton Hanenbon)
KECJ_SPD-02817.tad | ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?łă€€ă?«ă?źă?Šă?Şă‚˘ă?ł (Electroplankton Luminarian)
KEDJ_SPD-02817.tad | ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?łă€€ă‚żă‚¤ă?¨ă‚¦ă??ă?Ąă‚¦ (Electroplankton Heliozoa)
KEEJ_SPD-02817.tad | ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?łă€€ă?¬ă??ă‚Żă?¬ă??ă‚Ż (Electroplankton Reclek)
KEFJ_SPD-02817.tad | ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?łă€€ă?Šă?Žă‚«ă?Ľă?— (Electroplankton nanocarp)
KEGJ_SPD-02817.tad | ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?łă€€ă?’ă‚«ă?Şă?Žă?Ż (Electroplankton Hikarinova)
KEHJ_SPD-02817.tad | ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?łă€€ă?žă?Şă?łă‚ąă?Žă?Ľ (Electroplankton marine snow)
KEIJ_SPD-02817.tad | ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?łă€€ă?„ă?Şă‚¬ă?Ťă? ă‚· (Electroplankton Vorticella)
KEJJ_SPD-02817.tad | ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?łă€€ă?śă?«ă?śă‚¤ă‚ą (Electroplankton Volvois)
KGBJ_SPD-02803.tad | ă‚˛ă?Ľă? ďĽ†ă‚¦ă‚Şă??ă?? ă?śă?Ľă?« (Games & Watch Balls)
KGCJ_SPD-02803.tad | ă‚˛ă?Ľă? ďĽ†ă‚¦ă‚Şă??ă?? ă‚·ă‚§ă?• (Game & Watch Chef)
KGDJ_SPD-02803.tad | ă‚˛ă?Ľă? ďĽ†ă‚¦ă‚Şă??ă?? ă?‰ă?łă‚­ă?Ľă‚łă?łă‚°JR. (Game&Watch DONKEY KONG JR.)
KGFJ_SPD-02803.tad | ă‚˛ă?Ľă? ďĽ†ă‚¦ă‚Şă??ă?? ă?žă?Şă‚Şă‚şă‚»ă?ˇă?łă??ă?•ă‚ˇă‚Żă??ă?Şă?Ľ (Game&Watch MARIO'S Cement Factory)
KGGJ_SPD-02803.tad | ă‚˛ă?Ľă? ďĽ†ă‚¦ă‚Şă??ă?? ă?•ă?©ă??ă‚°ă?žă?ł (Game&Watch FLAGMAN)
KGHJ_SPD-02803.tad | ă‚˛ă?Ľă? ďĽ†ă‚¦ă‚Şă??ă?? ă??ă?«ă?ˇă??ă??(Game&Watch HELMET)
KGJJ_SPD-02803.tad | ă‚˛ă?Ľă? ďĽ†ă‚¦ă‚Şă??ă?? ă‚¸ă?Łă??ă‚¸ (Game&Watch JUDGE)
KGMJ_SPD-02803.tad | ă‚˛ă?Ľă? ďĽ†ă‚¦ă‚Şă??ă?? ă?žă?łă?›ă?Ľă?« (Game&Watch MANHOLE)
KGVJ_SPD-02803.tad | ă‚˛ă?Ľă? ďĽ†ă‚¦ă‚Şă??ă?? ă??ă?Ľă?źă?ł (Game&Watch VERMIN)
KHDJ_SPD-02803.tad | ă?„ă?¤ă?§ă‚‚ă?—ă?Şă‚Żă?©â?†ă‚­ă?©ă?‡ă‚łă?—ă?¬ă?źă‚˘ă?  (Anytime Purikura â?† Kiradeco Premium)
KJEJ_SPD-02807.tad | ă?Şă‚şă? ă?§éŤ›ă??ă‚‹ć–°ă?—ă?„ă??ă?„ă?”ćĽ¬ă?‘ă€€ă?Ťă‚¤ă?†ă‚Łă?–äĽšč©±ç·¨ (New English Training)
KK4J_SPD-02816.tad | ĺ›˛ă‚“ă?§ć¶?ă?—ă?¦ ă?Żă‚Żă‚°ă?źă?®ć™‚é–“  (Wakugumi: Monochrome Puzzle)
KKDJ_SPD-02803.tad | ă?Śă‚“ă?°ă‚‹ç§?ă?®ă?Šă?•ă?„ă?µĺżśćŹ´ĺ›Ł (Household account book)
KM9J_SPD-02817.tad | ă?ˇă‚‡ă?Łă?¨ă?žă‚¸ă??ă‚Żĺ¤§ĺ…¨ ć??ă‚Ťă?—ă?„ć•°ĺ­— (A Little Bit of... Magic Made Fun: Deep Psyche)
KMDJ_SPD-02817.tad | ă?ˇă‚‡ă?Łă?¨ă?žă‚¸ă??ă‚Żĺ¤§ĺ…¨ ă?‡ă?Ľă??ĺŤ ă?„ (A Little Bit ofâ€¦ Magic Made Fun: Matchmaker)
KMFJ_SPD-02817.tad | ă?ˇă‚‡ă?Łă?¨ă?žă‚¸ă??ă‚Żĺ¤§ĺ…¨ ă?•ă‚ˇă?‹ă?Ľă?•ă‚§ă‚¤ă‚ą (A Little Bit of... Magic Made Fun: Funny Face)
KMIJ_SPD-02817.tad | ă?ˇă‚‡ă?Łă?¨ă?žă‚¸ă??ă‚Żĺ¤§ĺ…¨ ă‚ąă‚­Â·ă‚­ă?©ă‚¤ç™şč¦‹ĺ™¨ (A Little Bit ofâ€¦ Magic Made Fun: Mind Probe)
KMNJ_SPD-02817.tad | ă?ˇă‚‡ă?Łă?¨ă?žă‚¸ă??ă‚Żĺ¤§ĺ…¨ ĺżµĺ†™ă‚«ă?ˇă?© (A Little Bit ofâ€¦ Magic Made Fun: Psychic Camera)
KMSJ_SPD-02817.tad | ă?ˇă‚‡ă?Łă?¨ă?žă‚¸ă??ă‚Żĺ¤§ĺ…¨ 3ă?¤ă?®ă‚·ă?Łă??ă?•ă?«ă‚˛ă?Ľă? (A Little Bit of... Magic Made Fun: Shuffle Games)
KN9J_SPD-02807.tad | ă?ˇă‚‡ă?Łă?¨č„łă‚’éŤ›ă??ă‚‹ĺ¤§äşşă?®DSiă??ă?¬ă?Ľă?‹ă?łă‚° ć•°ç‹¬ç·¨ (Brain Age Express: Sudoku)
KNDJ_SPD-02807.tad | ă?ˇă‚‡ă?Łă?¨č„łă‚’éŤ›ă??ă‚‹ĺ¤§äşşă?®DSiă??ă?¬ă?Ľă?‹ă?łă‚° ć–‡çł»ç·¨ (Brain Age Express: Arts & Letters)
KNKJ_SPD-02803.tad | äş•ĺ‡şć´‹ä»‹ă?®ĺ?Ąĺş·éş»ĺ°†DSi (Yosuke Ide's Health Asahi DSi)
KNRJ_SPD-02807.tad | ă?ˇă‚‡ă?Łă?¨č„łă‚’éŤ›ă??ă‚‹ĺ¤§äşşă?®DSiă??ă?¬ă?Ľă?‹ă?łă‚° ç?†çł»ç·¨ (Brain Age Express: Math)
KPNJ_SPD-02803.tad | ă?ˇă‚‡ă?Łă?¨ă?‘ă?Ťă?«ă?§ă?ťă?ł (Puzzle League Express)
KQ6J_SPD-02803.tad | ă?Źă‚‹ă?Źă‚‹ă‚˘ă‚Żă‚·ă?§ă?ł ă?Źă‚‹ă?‘ă??ďĽ– (Spin 6)
KR2J_NWD-00151.tad | ă?ťă‚±ă??ă??ă‚‹ă‚‹ă?¶äş¬é?˝ (Pocket Rurubu Kyoto)
KRIJ_NWD-00151.tad | ă?ťă‚±ă??ă??ă‚‹ă‚‹ă?¶ćť±äş¬ (Pocket Rurubu Tokyo)
KSEJ_SPD-02807.tad | ă?Şă‚şă? ă?§éŤ›ă??ă‚‹ć–°ă?—ă?„ă??ă?„ă?”ćĽ¬ă?‘ă€€ă‚„ă?•ă?—ă?„äĽšč©±ç·¨ (New English Training)
KSLJ_SPD-02807.tad | ă‚˝ă?Şă?†ă‚Łă‚˘DSi (Touch Solitaire)
KSUJ_SPD-02816.tad | ă?ˇă‚‡ă?Łă?¨ć•°é™Łă‚żă‚¤ă‚»ă?ł (Number Battle)
KTBJ_SPD-02816.tad | ă?ˇă‚‡ă?Łă?¨ă‚˘ă‚˝ă?“ĺ¤§ĺ…¨ ă?Šă?Şă??ă?żă?†ă?Ľă?–ă?« (A Little Bit of... All-Time Classics: Strategy Games)
KTPJ_SPD-02816.tad | ă?ˇă‚‡ă?Łă?¨ă‚˘ă‚˝ă?“ĺ¤§ĺ…¨ ă?Šă?¦ă?Śă‚‹ă??ă?©ă?łă?— (A Little Bit of... All-Time Classics: Family Games)
KTRJ_SPD-02816.tad | ă?ˇă‚‡ă?Łă?¨ă‚˘ă‚˝ă?“ĺ¤§ĺ…¨ ă??ă?Łă?Źă‚Šă??ă?©ă?łă?— (A Little Bit of... All-Time Classics: Card Classics)
KUWJ_SPD-02808.tad | ă?†ă?¤ă?™ă?ˇă‚¤ă?‰ă‚¤ă?łă?Żă?Şă‚Ş (WarioWare: Snapped!)
KWBJ_SPD-02807.tad | ă?‹ă?łă?†ă?łă?‰ă?ĽDSić™‚č¨? ă?•ă‚ˇă?źă‚łă?łă?žă?Şă‚Şă‚żă‚¤ă?— (Mario Clock)
KWCJ_SPD-02807.tad | ă?‹ă?łă?†ă?łă?‰ă?ĽDSić™‚č¨? ă?©ă?†ă?¶ă?¤ă?®ćŁ®ă‚żă‚¤ă?— (Animal Crossing Clock)
KWDJ_SPD-02807.tad | ă?‹ă?łă?†ă?łă?‰ă?ĽDSić™‚č¨? ă?•ă‚©ă??ă‚ąă‚żă?łă?‰ă‚żă‚¤ă?— (Photo Clock)
KWFJ_SPD-02807.tad | ă?‹ă?łă?†ă?łă?‰ă?ĽDSié›»ĺŤ“ ă?•ă‚ˇă?źă‚łă?łă?žă?Şă‚Şă‚żă‚¤ă?— (Mario Calculator)
KWGJ_SPD-02807.tad | ă?‹ă?łă?†ă?łă?‰ă?ĽDSié›»ĺŤ“ ă?©ă?†ă?¶ă?¤ă?®ćŁ®ă‚żă‚¤ă?— (Animal Crossing Calculator)
KX7J_SPD-02803.tad | ă?‘ă‚şă?«ă?„ă‚Ťă?„ă‚Ťă€€ćś?ĺ?Šă‚Żă?­ă‚ąă?Żă?Ľă?‰ă?Źă‚¦ă‚ąă€€Vol.1 (Various puzzles Monthly Crossword House Vol.1)
K59J_SPD-03093.tad | ă?‚ă??ç„ˇć?… ĺ?ąé‚Ł (Metal Torrent)
KA2E_SPD-03100.tad | Art Academy: Second Semester (European ROM)
KAIE_SPD-03100.tad | Art Academy: First Semester (European ROM)
KCDJ_SPD-03107.tad | Word
KCHJ_SPD-03097.tad | ă‚«ă?Ľă?‰ă?’ă?Ľă?­ă?Ľ ă‚ąă?”ă?Ľă?‰ă??ă??ă?«ă‚«ă‚ąă‚żă?  (Card Hero Speed Battle Custom)
KDMJ_SPD-03100.tad | Minis (Mario vs. Donkey Kong: Minis March Again!)
KMTJ_SPD-03097.tad | ă?‹ă?łă?†ă?łă?‰ă?ĽDSi ă?ˇă??ă?­ă?Žă?Ľă?  (Nintendo DSi Metronome)
KMZJ_SPD-03107.tad | çťˇçś č¨?éŚ˛ ă‚?ă?–ă?ľă?—ć™‚č¨? (Sleep Clock)
KOAJ_SPD-03097.tad | ä»Šć—Ąă?‹ă‚‰ă?Żă??ă‚?ă‚‹ă?•ă‚§ă‚¤ă‚ąă?‹ă?łă‚°éˇ”ă??ă?¬ă?źă?‹â‘ ă?™ă?Łă?Ťă‚Šĺ°Źéˇ”ă‚łă?Ľă‚ą (Face training)
KOBJ_SPD-03097.tad | ä»Šć—Ąă?‹ă‚‰ă?Żă??ă‚?ă‚‹ă?•ă‚§ă‚¤ă‚ąă?‹ă?łă‚°éˇ”ă??ă?¬ă?źă?‹â‘ˇă‚ąă?†ă‚­ă?Şç¬‘éˇ”ă‚łă?Ľă‚ą (Face training 2)
KOCJ_SPD-03097.tad | ä»Šć—Ąă?‹ă‚‰ă?Żă??ă‚?ă‚‹ă?•ă‚§ă‚¤ă‚ąă?‹ă?łă‚°éˇ”ă??ă?¬ă?źă?‹â‘˘č‹Ąă€…ă?—ă?„éˇ”ă‚łă?Ľă‚ą (Face training 3)
KODJ_SPD-03097.tad | ä»Šć—Ąă?‹ă‚‰ă?Żă??ă‚?ă‚‹ă?•ă‚§ă‚¤ă‚ąă?‹ă?łă‚°éˇ”ă??ă?¬ă?źă?‹â‘Łç›®ă?¨ĺŹŁă?®ĺ?Ąĺş·ă‚łă?Ľă‚ą (Face training 4)
KOEJ_SPD-03097.tad | ä»Šć—Ąă?‹ă‚‰ă?Żă??ă‚?ă‚‹ă?•ă‚§ă‚¤ă‚ąă?‹ă?łă‚°éˇ”ă??ă?¬ă?źă?‹â‘¤éˇ”ă?®ă?Şă?•ă?¬ă??ă‚·ă?Ąă‚łă?Ľă‚ą (Face Training 5)
KPTJ_SPD-03100.tad | ă?‘ă?Ťă?«é€Łçµ?ă€€ďĽ“ĺ?†ă?­ă‚±ă??ă?? (Pata)
KSPJ_SPD-03100.tad | ă?­ă‚‰ă?Łă?¦ă‚ąă?ťă?Łă?¨ďĽ? (Spot!)
KTUJ_SPD-03097.tad | ă?‹ă?łă?†ă?łă?‰ă?ĽDSi ćĄ˝ĺ™¨ă??ă?Ąă?Ľă?Šă?Ľ (Nintendo DSi Instrument Tuner)

---
# Electroplankton Series (ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?ł)
In the list above you will notice a lot of games in the Electroplankton series, Electroplankton was originally a DS game and then split up into sub-games and sold on the DSi Store for 200 points each [^3].

The ID for the games all start with **KE** then the letter of the sub-game from **A** to **J** and finally followed by the region, for the leak they are all Japanese so have the letter **J**.

The ROMs leaked for Electroplankton are:
* KEAJ_SPD-02817.tad - ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?łă€€ă??ă?¬ă?Ľă?”ă?Ľ (Electroplankton trappy)
* KEBJ_SPD-02817.tad - ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?łă€€ă?Źă?Ťă?łă?śă?ł (Electroplankton Hanenbon)
* KECJ_SPD-02817.tad - ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?łă€€ă?«ă?źă?Šă?Şă‚˘ă?ł (Electroplankton Luminarian)
* KEDJ_SPD-02817.tad - ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?łă€€ă‚żă‚¤ă?¨ă‚¦ă??ă?Ąă‚¦ (Electroplankton Heliozoa)
* KEEJ_SPD-02817.tad - ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?łă€€ă?¬ă??ă‚Żă?¬ă??ă‚Ż (Electroplankton Reclek)
* KEFJ_SPD-02817.tad - ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?łă€€ă?Šă?Žă‚«ă?Ľă?— (Electroplankton nanocarp)
* KEGJ_SPD-02817.tad - ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?łă€€ă?’ă‚«ă?Şă?Žă?Ż (Electroplankton Hikarinova)
* KEHJ_SPD-02817.tad - ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?łă€€ă?žă?Şă?łă‚ąă?Žă?Ľ (Electroplankton marine snow)
* KEIJ_SPD-02817.tad - ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?łă€€ă?„ă?Şă‚¬ă?Ťă? ă‚· (Electroplankton Vorticella)
* KEJJ_SPD-02817.tad - ă‚¨ă?¬ă‚Żă??ă?­ă?—ă?©ă?łă‚Żă??ă?łă€€ă?śă?«ă?śă‚¤ă‚ą (Electroplankton Volvois)

---
# Game & Watch Series (ă‚˛ă?Ľă? ďĽ†ă‚¦ă‚Şă??ă??)
Nintendo released remakes of some of their classic Game & Watch handheld systems as downloadable DSiWare available for both the DSi and 3DS.

The ID for the games all start with **KG** followed by the letter of the individual game and watch game, the letters represent the first letter of the game, e.g **B** for Balls and **V** for Vermin, so not all Letters are used.

The ROMs leaked in the Game & Watch series are:
* KGBJ_SPD-02803.tad - ă‚˛ă?Ľă? ďĽ†ă‚¦ă‚Şă??ă?? ă?śă?Ľă?« (Games & Watch Balls)
* KGCJ_SPD-02803.tad - ă‚˛ă?Ľă? ďĽ†ă‚¦ă‚Şă??ă?? ă‚·ă‚§ă?• (Game & Watch Chef)
* KGDJ_SPD-02803.tad - ă‚˛ă?Ľă? ďĽ†ă‚¦ă‚Şă??ă?? ă?‰ă?łă‚­ă?Ľă‚łă?łă‚°JR. (Game&Watch DONKEY KONG JR.)
* KGFJ_SPD-02803.tad - ă‚˛ă?Ľă? ďĽ†ă‚¦ă‚Şă??ă?? ă?žă?Şă‚Şă‚şă‚»ă?ˇă?łă??ă?•ă‚ˇă‚Żă??ă?Şă?Ľ (Game&Watch MARIO'S Cement Factory)
* KGGJ_SPD-02803.tad - ă‚˛ă?Ľă? ďĽ†ă‚¦ă‚Şă??ă?? ă?•ă?©ă??ă‚°ă?žă?ł (Game&Watch FLAGMAN)
* KGHJ_SPD-02803.tad - ă‚˛ă?Ľă? ďĽ†ă‚¦ă‚Şă??ă?? ă??ă?«ă?ˇă??ă??(Game&Watch HELMET)
* KGJJ_SPD-02803.tad - ă‚˛ă?Ľă? ďĽ†ă‚¦ă‚Şă??ă?? ă‚¸ă?Łă??ă‚¸ (Game&Watch JUDGE)
* KGMJ_SPD-02803.tad - ă‚˛ă?Ľă? ďĽ†ă‚¦ă‚Şă??ă?? ă?žă?łă?›ă?Ľă?« (Game&Watch MANHOLE)
* KGVJ_SPD-02803.tad - ă‚˛ă?Ľă? ďĽ†ă‚¦ă‚Şă??ă?? ă??ă?Ľă?źă?ł (Game&Watch VERMIN)

---
# Art Academy Series (Art Style ă‚·ă?Şă?Ľă‚ş)
The ROMs leaked in the Art Academy Series are:
* KA2E_SPD-03100.tad - Art Academy: Second Semester (European ROM)
* KAIE_SPD-03100.tad - Art Academy: First Semester (European ROM)
* KAAJ_SPD-02799.tad - AQUARIO (Art Style ă‚·ă?Şă?Ľă‚ş)
* KADJ_SPD-02799.tad - DECODE (Art Style ă‚·ă?Şă?Ľă‚ş)
* KAGJ_SPD-02808.tad - ă?‚ă?¤ă‚?ă‚‹ç¬‘éˇ”ĺ¸ł (Collecting smile books?!)
* KAHJ_SPD-02799.tad - HACOLIFE (Art Style ă‚·ă?Şă?Ľă‚ş)
* KAKJ_SPD-02799.tad - nalaku (Art Style ă‚·ă?Şă?Ľă‚ş)
* KAPJ_SPD-02799.tad - PiCOPiCT (Art Style ă‚·ă?Şă?Ľă‚ş)
* KASJ_SPD-02799.tad - SOMNIUM (Art Style ă‚·ă?Şă?Ľă‚ş)
* KAVJ_SPD-02799.tad - DIGIDRIVE (Art Style ă‚·ă?Şă?Ľă‚ş)

---
# Unknown & Test ROMs
The ROMs in the first two folders (**20090722** and **20090925**) are fairly easy to identify the name of. However the other folders don't seem to have ROMs using the standard naming convention. 

Some are missing the product code which is the easiest way to identify the ROMs. So if you know what any of the ROMs in the list below are then please let us know.

The Unknown ROMs are:
* **SPD-03408_chample0923f.tad** - Chample? (never heard of it)
* **SPD-03521_SikakuDSi_1015.tad** - Sikaku? (mistransliteration of "Shikaku" [^4])
* **blocker_dsi_TwlRomSymbol_2009_1008_1040_r27659.tad** - Blocker?
* **Starship_TwlRomJapan_2009_1028_1125_r28723.tad** - Starship? (maybe Starship Patrol / Defender? [^4])
* **Starship_TwlRomSymbol_2009_1028_1122_r28723.tad** - Starship(?) with debug symbols
* **SPD-03654_Zodiac_Pinball_Cheat_2009_08_26_1205.tad** -  Pinball Pulse: The Ancients Beckon [^4] Presumably with build in cheats
* **SPD-03649_AttaColleda_RomForShot100204.tad** - Unknown
* SPD-03776_20100127_2D.tad -  Attakoreda, JP title of Tales in a Box
* **x_dsi_TwlRomSymbol_2010_0204_1646_r32157.tad** - Unknown
* **SPD-03878_R13948_DSRL.tad**
* **SPD-03878_artest100215_2105_R13948_DSFN.tad** - Augmented Reality test?

Some of these ROMs do have the product code after the letter **T** which presumably means it is a test version and not a retail release.

The Testing ROMs are:
* **SPD-03394_TKAVJ01.tad** - DIGIDRIVE (Art Style Series)
* **SPD-03396_TKPAJ00.tad** - Leader
* **SPD-03400_pbat.KPBJ.F.0907.2660.tad** - P-Bat
* **SPD-03482_TKA2J00.tad** - Art Academy: Second Semester
* **SPD-03483_TKAIJ00.tad** - Art Academy: First Semester
* **TKDZJ10.tad** - DigiQ-z
* **SPD-03623_TKSRE00.tad** - Project Sky
* **SPD-03654_TKZPE01.tad** - Pinball Pulse The Ancients Beckon
* **SPD-03649_TWL-KRGJ091201.tad** - Looksley's Line Up
* **K8PJ_SVN4990_rel.tad** - Mtan P (release?)
* **K8PJ_SVN4990_rom.tad** - Mtan P (debug?)
* **K8EJ_SVN4989_rel.tad** - Mtan E (release?)
* **K8EJ_SVN4989_rom.tad** - Mtan E (debug?)
* **SPD-03723_KKR1009_1D.tad** - Flip The Core? (Guess based on KKR)
* **SPD-03776_TK3LJ00.tad** - ă?•ă‚‹ă??ă?łă?‰ (ä»®) (Monkey band (provisional))
* **TKDXJ00.tad** - DigiQ-x
* **SPD-03895_DSiGolf_us20091204d.tad** - DsiGolf
* **SPD-03895_TK72E00.tad** - DsiGolf
* **SPD-05577_KQ9J_DEBUG_2011_0915_1547.tad** - Knife (Zelda 4 swords?)


---
# References
[^1]: [DSi CID Discovered - Next Generation Emulation](https://www.ngemu.com/threads/dsi-cid-discovered.169257/)
[^2]: [Nintendo Software Planning & Development - Wikipedia](https://en.wikipedia.org/wiki/Nintendo_Software_Planning_%26_Development)
[^3]: [Electroplankton - Wikipedia](https://en.wikipedia.org/wiki/Electroplankton)
[^4]: [Gingerbread Man on Twitter: "@RetroReversing @orcastraw Zodiac Pinball I guess is Pinball Pulse: The Ancients Beckon, made by Fuse Games. It's based on Greek mythology. It was never released in Japan, so Zodiac Pinball was likely its planned JP title (or working title). Starship: maybe Starship Patrol / Defender?" / Twitter](https://twitter.com/confluentibus/status/1307833147007160320)
