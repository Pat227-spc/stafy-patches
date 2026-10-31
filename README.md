# The Legendary Starfy (GBA) – English Patches

English patches for all three Starfy games on the Game Boy Advance. **Patches only, no ROMs included.** You'll need your own legally dumped cartridge.

## Quick start

Grab the patches from the [latest release](https://github.com/Pat227-spc/stafy-patches/releases/latest).

| Game | Patch file | Japanese ROM needed |
|---|---|---|
| Starfy 1 (v1.0.3) | `Starfy.1.Eng.v1.0.3.bps` | Densetsu no Stafy (Japan) |
| Starfy 2 (v0.9.8) | `Starfy.2.Eng.v0.9.8.bps` | Densetsu no Stafy 2 (Japan) |
| Starfy 3 (v1.0.4) | `Starfy.3.Eng.v1.0.4.bps` | Densetsu no Stafy 3 (Japan) (Rev 1) |

How to patch:

1. Download the `.bps` patch for your game.
2. Open a BPS patcher: [Floating IPS (Flips)](https://github.com/Alcaro/Flips) or the [Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/) website.
3. Pick your clean Japanese ROM, then the patch.
4. Apply and play the patched ROM in your emulator or flashcart.

It should also work on flash carts like the EZ-Flash.

BPS checks the base ROM, so if you pick the wrong one it will refuse to patch. Save type is SRAM 32 KB for all three games.

**Found a bug?** Spotted a typo, or a patch won't apply? We'd love to hear about it on [GitHub issues](https://github.com/Pat227-spc/stafy-patches/issues).

**Want to build on it?** Our source is open at [stafy-source](https://github.com/Pat227-spc/stafy-source), and we'd love to see forks, improvements, or new projects built on our work. Pull requests and forks are welcome; we just ask that you keep crediting the original translators.

## Credits

All credit goes to the translators and hackers who came before us. This is simply an assembly of their work, including the translations we used. We have no desire to take credit for it.

Every credit below links to the creator's original release and says where we got it and when.

- **Megahog2014 / Starfy Translation Team** – Starfy 1 English translation (v1.1), plus the Starfy 2 translation project and scripts.
  - Starfy 1: [romhacking.net #7057](https://www.romhacking.net/translations/7057/) (released there September 23, 2023, per the [Starfy Wiki](https://starfywiki.org/wiki/Fan_translations_of_The_Legendary_Starfy_series)).
  - Starfy 2: [Megahog2014/Densetsu_no_Starfy_2_Translation_ENG](https://github.com/Megahog2014/Densetsu_no_Starfy_2_Translation_ENG) on GitHub (first uploaded 2024-08-30; we used the latest commit `de569ee`, dated 2024-10-24).
- **Starfy 1 translation (Starfy Translation Team):** Higsby (original translation), pablitox (original hacking), wowjinxy (graphics: text GFX and English font), Megahog2015 (graphics), EvieMelody / EvieMelodylvsoulmate4ever (production). Same release as above: [romhacking.net #7057](https://www.romhacking.net/translations/7057/), September 23, 2023.
- **SomeUselessTranslations (AUselessMage)** – the complete Starfy 2 script, and the script Dimedime's Starfy 3 patch is based on. Taken from their translated playthrough videos on [YouTube](https://www.youtube.com/channel/UCxEXgKEbCgTI6jsKuzNAANw): [Starfy 2 playlist](https://www.youtube.com/playlist?list=PLA7NjZIk-WKX6E8fTEwiEtI3XlpZy2CQm), [Starfy 3 playlist](https://www.youtube.com/playlist?list=PLA7NjZIk-WKU2AeHgbKGhDb7ZvQ3Y79xy) (Starfy 3 videos started in 2022, per the Starfy Wiki). Starfy 2 also uses their script and translator notes posted on Reddit in [r/thelegendarystarfy](https://www.reddit.com/r/thelegendarystarfy/) (for example the [post-game World 9 translation](https://www.reddit.com/r/thelegendarystarfy/comments/r2b0pc/starfy_2_post_game_world_9_translation/)); v0.9.7 and later used them for an English polish pass.
- **Dimedime** – The Legendary Starfy 3 English patch v1.0, released in 2024. We got it from the [RetroAchievements RAPatches repository](https://github.com/RetroAchievements/RAPatches/blob/main/GBA/Translation/English/7270-DensetsunoStafy3-English.zip) (`GBA/Translation/English/7270-DensetsunoStafy3-English.zip`, added there 2024-05-19). The patch file inside is dated 2024-05-17. As far as we know, that's where it was first published; the [Starfy Wiki](https://starfywiki.org/wiki/Fan_translations_of_The_Legendary_Starfy_series) links to the same file.
- **Luckylodeon98** – Starfy 2 graphics and VWF integration, World 5-3 fruit puzzle art and English clue chain. From [Luckylodeon98/Densetsu_no_Starfy_2_Translation_ENG](https://github.com/Luckylodeon98/Densetsu_no_Starfy_2_Translation_ENG) on GitHub (a fork of Megahog2014's project; we used commit `dbfd7cc`, dated 2026-10-15).
- **RayCarrot** – the Starfy 2 VWF (variable-width font) code, "Starfy2 VWF Patch by RayCarrot with assistance from Normmatt". From [`asm/VWF/VWF.asm`](https://github.com/Megahog2014/Densetsu_no_Starfy_2_Translation_ENG/blob/main/asm/VWF/VWF.asm) in Megahog2014's Starfy 2 project (in its first upload, 2024-08-30). RayCarrot's GitHub: [github.com/RayCarrot](https://github.com/RayCarrot).
- **Normmatt** – helped with the Starfy 2 VWF (see above), and did the original Starfy 1 VWF and text insertion work (2012 or earlier, per the [Starfy Wiki](https://starfywiki.org/wiki/Fan_translations_of_The_Legendary_Starfy_series)). Original Starfy 1 project: [Normmatt/Densetsu-no-Stafy-GBA-Translation](https://github.com/Normmatt/Densetsu-no-Stafy-GBA-Translation) on GitHub (2014-08-11 to 2019-02-14).
- **Thanks:** Giantbomb64 for bug hunting: reported the World 2-1 crash in [issue #1](https://github.com/Pat227-spc/stafy-patches/issues/1) (2026-10-30). EpicSignal for spotting the World 5-3 puzzle issue.
- More on the fan translations: [Starfy Wiki](https://www.starfywiki.org/wiki/Fan_translation)

Tools: armips (Kingcom and contributors), Floating IPS (Alcaro and contributors), Atlas (Klarth), LZSS (CUE), Normmatt's VWF/text insertion tool, mGBA (endrift), NanoBoyAdvance (fleroviux), VisualBoyAdvance-M, Wine, Python, NumPy, SciPy and Pillow. Full contributor lists are in [stafy-source](https://github.com/Pat227-spc/stafy-source).

Starfy is (c) Nintendo / TOSE. Not affiliated with Nintendo. Box art in `boxart/` is fan-edited from the original Japanese covers; art (c) Nintendo / TOSE.

**Sharing:** Feel free to share, mirror or republish these patches anywhere, in any form. All we ask is that the original translators, contributors and modders listed above keep their credit.

If you're one of the original authors and want your name changed or removed, or your work taken out, open an issue and it will be honored promptly. No questions asked.

## Technical stuff

**Japanese ROM CRC32**
- Starfy 1: Densetsu no Stafy (Japan) – `FAE94C8B`
- Starfy 2: Densetsu no Stafy 2 (Japan) – `EA73EB54`
- Starfy 3: Densetsu no Stafy 3 (Japan) (Rev 1) – `2D6E4C3B`

Full technical details and checksums: see the [release notes](https://github.com/Pat227-spc/stafy-patches/releases) / [stafy-source](https://github.com/Pat227-spc/stafy-source) (being updated).

Changelog: see the [releases page](https://github.com/Pat227-spc/stafy-patches/releases).

## Checksums

<details>
<summary>SHA1 / CRC32 for base ROMs, patches and patched results</summary>

The release also includes `SHA1SUMS.txt` (check all patches at once with `sha1sum -c SHA1SUMS.txt`) and `README.txt` (a copy of this page). Check a single file with `sha1sum <file>` or `certutil -hashfile <file> SHA1`. If anything doesn't match, please open an issue.

**Base ROMs**

| Game | Base | CRC32 | SHA1 |
|---|---|---|---|
| Starfy 1 | Densetsu no Stafy (Japan) | FAE94C8B | 75f6297f42c41e2a6d108de9a372308ad2df6a9c |
| Starfy 1 (alt) | Starfy Translation Team v1.1 English ROM | F7CB8EE3 | 79c4f1847dace4efceecff0a211cf341ad372808 |
| Starfy 2 | Densetsu no Stafy 2 (Japan) | EA73EB54 | 8322867cc4369307048deb20a8bb16c3dd0910df |
| Starfy 3 | Densetsu no Stafy 3 (Japan) (Rev 1) | 2D6E4C3B | dae5354bfe4ccafc92d22b1389265dbf1f79b636 |
| Starfy 3 (alt) | Dimedime v1.0 English ROM | 850B4137 | 179920be4a0ae5ed60137103deca4a760811517b |

MD5: Starfy 1 `06ed08799b2f163076fe9fc0cfe65a4c`, STT v1.1 `43c29e64c16e26f3f0dae33120c9430d`, Starfy 2 `0635251b85657f9c1de295546da09aeb`, Starfy 3 `ee4fbcec249a68b796be491f56ffe03d`.

**Patches**

| Patch file | SHA1 |
|---|---|
| Starfy.1.Eng.v1.0.3.bps | 1c91ee398cc4de3fced52857f37fdf03d0321b02 |
| Starfy.1.Eng.v1.0.3.STT.v1.1.base.bps | 2d4d9f12b9e14218d762e02f1e20e70dfb5bf161 |
| Starfy.2.Eng.v0.9.8.bps | 1ed3784568471f83d406a24f06aada6b76e96764 |
| Starfy.3.Eng.v1.0.4.bps | 59036c1955c57fb78e72fff27fdf7fe4d7d89c69 |
| Starfy.3.Eng.v1.0.4.Dimedime.v1.0.base.bps | 7f20979a9cfa581cd0348c359f5ab813acb951ac |

**Patched results**

| Game | CRC32 | SHA1 |
|---|---|---|
| Starfy 1 Eng v1.0.3 | 44C2017A | 1c7ad3cd80e1ba146c88a315d22f6fb6bc17edfd |
| Starfy 2 Eng v0.9.8 (32 MiB) | 8C2D9266 | bd28fcd15cd7aebf9fb22cd77964e05d65a57d3d |
| Starfy 3 Eng v1.0.4 | 4F31E799 | 3d46521999d1bfea130b476a877013863b02b1c5 |

</details>

Thank you for playing!
