The Legendary Starfy series (GBA) - English patches
=====================================================
Patches only. No ROMs are included or distributed. Bring your own legally dumped cartridge.
Apply with Floating IPS (Flips), Rom Patcher JS, or any BPS patcher. BPS checks the base CRC, so a wrong base is refused.

Starfy 1 Eng v1.0.2  (Densetsu no Stafy, "Origins cleanup" v1.0.2)
  Patch (primary): "Starfy 1 Eng v1.0.2.bps"   SHA1 df5d790a6a273d392671db044b3b3de0be9c8609
  Base:  Densetsu no Stafy (Japan).gba, clean, 8 MiB
         CRC32 FAE94C8B  SHA1 75f6297f42c41e2a6d108de9a372308ad2df6a9c  MD5 06ed08799b2f163076fe9fc0cfe65a4c
  Alternate patch: "Starfy 1 Eng v1.0.2 (STT v1.1 base).bps"   SHA1 8ca993d292c386350ca3277f0211e109d5013515
  Alt base: Starfy Translation Team v1.1 English ROM (8 MiB)
         CRC32 F7CB8EE3  SHA1 79c4f1847dace4efceecff0a211cf341ad372808  MD5 43c29e64c16e26f3f0dae33120c9430d
  Result: CRC32 72AE1467  SHA1 27c69522d73a8af606f771d7bafc0cecda240baa

Starfy 2 Eng v0.9.6  (Densetsu no Stafy 2)
  Patch: "Starfy 2 Eng v0.9.6.bps"   SHA1 f5c2e3139105e075adefacb5a111c4c854f6a1f7
  Base:  Densetsu no Stafy 2 (Japan).gba, clean, 16 MiB
         CRC32 EA73EB54  SHA1 8322867cc4369307048deb20a8bb16c3dd0910df  MD5 0635251b85657f9c1de295546da09aeb
  Result (expanded to 32 MiB): CRC32 E29F64F8  SHA1 e86893d9b3e6dd186a8891db0b364ad54797f986
  Source: the Starfy 2 patch is built from Megahog2014's Starfy 2 translation project, which is GPL-3.0
          (github.com/Megahog2014/Densetsu_no_Starfy_2_Translation_ENG), with art from Luckylodeon98's GPL-3.0 fork.
          Our build scripts and changes are GPL-3.0 too; the source is at
          https://github.com/Pat227-spc/stafy-source

Starfy 3 Eng v1.0.3  (Densetsu no Stafy 3, Dimedime cleanup v1.0.3)
  Patch (primary): "Starfy 3 Eng v1.0.3.bps"   SHA1 e82864680b24eef73e64984c4e252ceef1fd5097
  Base:  Densetsu no Stafy 3 (Japan) (Rev 1).gba, clean, 16 MiB
         CRC32 2D6E4C3B  SHA1 dae5354bfe4ccafc92d22b1389265dbf1f79b636  MD5 ee4fbcec249a68b796be491f56ffe03d
  Alternate patch: "Starfy 3 Eng v1.0.3 (Dimedime v1.0 base).bps"   SHA1 b4e813a3696865dab50af2aacbe54c27e1bfe545
  Alt base: Dimedime v1.0 English ROM (Rev 1 + Dimedime's v1.0 BPS)
         CRC32 850B4137  SHA1 179920be4a0ae5ed60137103deca4a760811517b
  Result: CRC32 23170373  SHA1 18968dde90fcc27c1bdc5092f77243c84aa4f85f

NOTE: Starfy 1 now has a clean-Japanese-base patch (primary); the STT v1.1 base patch is kept as an alternate.
Starfy 3 now has a clean-Japanese (Rev 1) base patch (primary); the Dimedime v1.0 base patch is kept as an alternate.

Box art: boxart/ contains English box covers for all three games ("Starfy N Eng vX - box.png"), fan-made by editing
  the original Japanese covers. Art (c) Nintendo / TOSE.

Save type: SRAM 32 KB (SRAM_V112 / SRAM_V113) for all three.

Credits
  Starfy Translation Team / Megahog2014 - Densetsu no Stafy English translation (v1.1), Stafy 2 translation project and scripts
      (source: github.com/Megahog2014/Densetsu_no_Starfy_2_Translation_ENG; romhacking.net/translations/7057)
  Starfy 1 translation (Starfy Translation Team), credited on romhacking.net/translations/7057:
    Higsby - original translation
    pablitox - original hacking
    wowjinxy - graphics (text GFX and English font)
    Megahog2015 - graphics
    EvieMelody (EvieMelodylvsoulmate4ever) - production
  SomeUselessTranslations (AUselessMage) - complete Stafy 2 script localization (source for untranslated scenes; also the source of Dimedime's Stafy 3 script)
      (source: starfywiki.org/wiki/Fan_translation; youtube.com/playlist?list=PLA7NjZIk-WKX6E8fTEwiEtI3XlpZy2CQm)
  Dimedime - The Legendary Starfy 3 English patch v1.0
      (source: starfywiki.org/wiki/Fan_translation)
  Luckylodeon98 - World 5-3 fruit puzzle art and English clue chain (used as-is in Starfy 2 since v0.9.5)
  Luckylodeon98 - Stafy 2 graphics and VWF integration (upstream fork of the Stafy 2 project); from his README:
      'VWF code by RayCarrot / Graphics by Megahog2015/Luckylodeon98 and WowJinxy / Translations supplied by SomeUselessTranslations'
  RayCarrot - VWF (variable-width font) code used in Stafy 2
  RayCarrot, Normmatt - font graphics, tools and technical help
      (Normmatt's VWF/text insertion tool: starfywiki.org/wiki/Fan_translation)
All credit goes to the translators and hackers who came before us. This is simply an assembly of their work, including the translations we used. We have no desire to take credit for it.
All translation credit belongs to the original translators. Starfy is (c) Nintendo / TOSE. Not affiliated with Nintendo.
Thanks: EpicSignal (spotting the World 5-3 puzzle issue), Giantbomb64 (bug hunting: reported the World 2-1 crash).
Source: https://github.com/Pat227-spc/stafy-source
Sharing: Feel free to share, mirror or republish these patches anywhere, in any form. All we ask is that the original translators, contributors and modders listed above keep their credit.

Tools (everyone who built a tool we used)
  armips by Kingcom, with contributors sp1187, unknownbrackets, Prof9, Fothsid, StraDaMa, queueRAM, Normmatt, hrydgard, Blade2187, Zeturic, tclamb, kabochi, adakite1, PeterLemon, LemonBoy, warmenhoven, radimerry, nekopsykose, onlymx13, GermanAizek, kwyxz, jeffman, archshift, aliaspider, dfuchsgruber, Thar0, Bigpet, socram8888, lioncash, joeydumont, bentley, Amjad50 - https://github.com/Kingcom/armips (MIT; bundled Linux build of commit 62adab4, licence in thirdparty/armips/)
  Floating IPS (flips) by Alcaro, with contributors Sir-Walrus, Miepee, orbea, Kekun, mrexodia, althonos, foxsouns, bbhtt, trillllian - https://github.com/Alcaro/Flips (GPL-3.0; bundled Linux build of commit ff216a7, licence in thirdparty/flips/)
  Atlas 1.11 by Klarth - https://www.romhacking.net/utilities/224/ (not bundled: no redistribution licence)
  LZSS (CUE's GBA/DS compressors, 2011) by CUE - https://www.romhacking.net/utilities/826/ (not bundled: no redistribution licence)
  VWF (variable-width font) code by RayCarrot, integrated by Luckylodeon98 - https://github.com/Luckylodeon98/Densetsu_no_Starfy_2_Translation_ENG
  Normmatt's VWF/text insertion tool - https://www.starfywiki.org/wiki/Fan_translation
  mGBA by endrift - https://github.com/mgba-emu/mgba (testing)
  NanoBoyAdvance by fleroviux - https://github.com/nba-emu/NanoBoyAdvance (testing)
  VisualBoyAdvance-M by the VBA-M project - https://github.com/visualboyadvance-m/visualboyadvance-m (testing)
  Wine by the Wine project - https://www.winehq.org/ (runs Atlas and lzss on Linux)
  Python, NumPy, SciPy and Pillow by their projects - https://www.python.org/, https://numpy.org/, https://scipy.org/, https://python-pillow.org/

Verify it yourself
------------------
Please don't just take our word for it. These are the hashes to check against (also in SHA1SUMS.txt):

Starfy 1 Eng v1.0.2
  Base:  Densetsu no Stafy (Japan)   CRC32 FAE94C8B  SHA1 75f6297f42c41e2a6d108de9a372308ad2df6a9c
  Alt base: STT v1.1 English ROM     CRC32 F7CB8EE3  SHA1 79c4f1847dace4efceecff0a211cf341ad372808
  Result:                            CRC32 72AE1467  SHA1 27c69522d73a8af606f771d7bafc0cecda240baa
  Patch SHA1: Starfy 1 Eng v1.0.2.bps                   df5d790a6a273d392671db044b3b3de0be9c8609
              Starfy 1 Eng v1.0.2 (STT v1.1 base).bps   8ca993d292c386350ca3277f0211e109d5013515
Starfy 2 Eng v0.9.6
  Base:  Densetsu no Stafy 2 (Japan) CRC32 EA73EB54  SHA1 8322867cc4369307048deb20a8bb16c3dd0910df
  Result (32 MiB):                   CRC32 E29F64F8  SHA1 e86893d9b3e6dd186a8891db0b364ad54797f986
  Patch SHA1: Starfy 2 Eng v0.9.6.bps                   f5c2e3139105e075adefacb5a111c4c854f6a1f7
Starfy 3 Eng v1.0.3
  Base:  Densetsu no Stafy 3 (Japan) (Rev 1)  CRC32 2D6E4C3B  SHA1 dae5354bfe4ccafc92d22b1389265dbf1f79b636
  Alt base: Dimedime v1.0 English ROM         CRC32 850B4137  SHA1 179920be4a0ae5ed60137103deca4a760811517b
  Result:                                     CRC32 23170373  SHA1 18968dde90fcc27c1bdc5092f77243c84aa4f85f
  Patch SHA1: Starfy 3 Eng v1.0.3.bps                   e82864680b24eef73e64984c4e252ceef1fd5097
              Starfy 3 Eng v1.0.3 (Dimedime v1.0 base).bps   b4e813a3696865dab50af2aacbe54c27e1bfe545

To check a file: sha1sum <file> (Linux/macOS) or certutil -hashfile <file> SHA1 (Windows).
You can also rebuild the patches yourself from https://github.com/Pat227-spc/stafy-source (see each game's README),
then compare the SHA1 of your patched ROM with the Result SHA1 above. If anything doesn't match, please let us know.

Original projects
-----------------
If you enjoy these games, please visit and support the people who actually made the translations:
- Megahog2014 / Starfy Translation Team (Starfy 2 project): https://github.com/Megahog2014/Densetsu_no_Starfy_2_Translation_ENG
- Starfy Translation Team, Starfy 1 (romhacking.net): https://www.romhacking.net/translations/7057/
- Luckylodeon98 (Starfy 2 fork, graphics and VWF): https://github.com/Luckylodeon98/Densetsu_no_Starfy_2_Translation_ENG
- SomeUselessTranslations (Starfy 2 script videos): https://www.youtube.com/playlist?list=PLA7NjZIk-WKX6E8fTEwiEtI3XlpZy2CQm
- Starfy Wiki fan translation page (Dimedime, SomeUselessTranslations, Normmatt): https://www.starfywiki.org/wiki/Fan_translation

Credit and takedown requests
----------------------------
If you are one of the original authors and would like your name changed or removed, or your work taken out,
please open an issue at https://github.com/Pat227-spc/stafy-patches/issues and it will be honored promptly. No questions asked.


Changelog
  v1.0.2
    Starfy 2 v0.9.6: fixed a crash during the conversation with Ruby in World 2-1 (the screen froze when the
      flashback started). The long English conversations in 2-1, 3-4 and 4-5 were too big for the game's text
      buffer and could corrupt memory; the buffer is now larger. Also fixed two typos in 2-1 ("Sheesh... Alright,
      listen!" and a missing space before "furniture"). If you play on an emulator, don't load savestates made
      with an older version; use your in-game save instead. Thanks to Giantbomb64 for reporting the crash.
    Starfy 1 v1.0.2 and Starfy 3 v1.0.3 are unchanged.
  v1.0.1
    Starfy 1 v1.0.2: fixed "Stafy" -> "Starfy" in Wozart's line, fixed "be used used to solve" (Old Man Lobber),
      and centered the stage names on the stage intro screens.
    Starfy 3 v1.0.3: fixed "This maybe a little tricky" -> "This may be a little tricky".
    Starfy 2 v0.9.5: World 5-3 fruit puzzle now uses Luckylodeon98's fruit set. This fixes a bug where the three
      puzzle rooms showed garbled backgrounds and some fruits were invisible, and makes the second room's word
      chain work in English (Eggplant > Turnip > Pumpkin > Nuts). Nothing else in Starfy 2 changed.
  v1.0
    First release.

Found a bug or a typo, or a patch that won't apply? Please open an issue at github.com/Pat227-spc/stafy-patches/issues.
Thank you for playing, and thank you to everyone above whose work this builds on.
