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

Starfy 2 Eng v0.9.5  (Densetsu no Stafy 2)
  Patch: "Starfy 2 Eng v0.9.5.bps"   SHA1 6d7a44f99d6500ab172396c1ae62222f9ce5e6e7
  Base:  Densetsu no Stafy 2 (Japan).gba, clean, 16 MiB
         CRC32 EA73EB54  SHA1 8322867cc4369307048deb20a8bb16c3dd0910df  MD5 0635251b85657f9c1de295546da09aeb
  Result (expanded to 32 MiB): CRC32 2165E2C8  SHA1 bc76c940d686c4b6555be0f6c18542b04dc472da
  Source: the Starfy 2 patch is built from Megahog2014's Starfy 2 translation project, which is GPL-3.0
          (github.com/Megahog2014/Densetsu_no_Starfy_2_Translation_ENG), with art from Luckylodeon98's GPL-3.0 fork.
          Our build scripts and changes are GPL-3.0 too; the source is available on request; just ask in a GitHub issue
          (github.com/Pat227-spc/stafy-patches/issues).

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
  Luckylodeon98 - World 5-3 fruit puzzle art and English clue chain (used as-is in Starfy 2 v0.9.5)
  Luckylodeon98 - Stafy 2 graphics and VWF integration (upstream fork of the Stafy 2 project); from his README:
      'VWF code by RayCarrot / Graphics by Megahog2015/Luckylodeon98 and WowJinxy / Translations supplied by SomeUselessTranslations'
  RayCarrot - VWF (variable-width font) code used in Stafy 2
  RayCarrot, Normmatt - font graphics, tools and technical help
      (Normmatt's VWF/text insertion tool: starfywiki.org/wiki/Fan_translation)
  Cleanup builds, testing and packaging: Pat227-spc
All credit goes to the translators and hackers who came before us. We have no desire to take credit for their work; we only put the pieces together. All translation credit belongs to the original translators. Starfy is (c) Nintendo / TOSE. Not affiliated with Nintendo.

Changelog
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
