# The Legendary Starfy (GBA) – English Patches

English patches for all three Starfy games on the Game Boy Advance. **Patches only, no ROMs included.** You'll need your own legally dumped cartridge.

## Quick start

Grab the patches from the [latest release](https://github.com/Pat227-spc/stafy-patches/releases/latest).

| Game | Patch file | Japanese ROM needed |
|---|---|---|
| Starfy 1 (v1.0.2) | `Starfy.1.Eng.v1.0.2.bps` | Densetsu no Stafy (Japan) |
| Starfy 2 (v0.9.6) | `Starfy.2.Eng.v0.9.6.bps` | Densetsu no Stafy 2 (Japan) |
| Starfy 3 (v1.0.3) | `Starfy.3.Eng.v1.0.3.bps` | Densetsu no Stafy 3 (Japan) (Rev 1) |

How to patch:

1. Download the `.bps` patch for your game.
2. Open a BPS patcher: [Floating IPS (Flips)](https://github.com/Alcaro/Flips) or the [Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/) website.
3. Pick your clean Japanese ROM, then the patch.
4. Apply and play the patched ROM in your emulator or flashcart.

It should also work on flash carts like the EZ-Flash.

BPS checks the base ROM, so if you pick the wrong one it will refuse to patch. Save type is SRAM 32 KB for all three games.

**Found a bug?** Spotted a typo, or a patch won't apply? We'd love to hear about it on [GitHub issues](https://github.com/Pat227-spc/stafy-patches/issues).

## Credits

All credit goes to the translators and hackers who came before us. This is simply an assembly of their work, including the translations we used. We have no desire to take credit for it.

- **Megahog2014 / Starfy Translation Team** – Starfy 1 English translation (v1.1), Starfy 2 translation project and scripts ([GitHub](https://github.com/Megahog2014/Densetsu_no_Starfy_2_Translation_ENG), [romhacking.net](https://www.romhacking.net/translations/7057/))
- **Starfy 1 translation (Starfy Translation Team):** Higsby (original translation), pablitox (original hacking), wowjinxy (graphics: text GFX and English font), Megahog2015 (graphics), EvieMelody / EvieMelodylvsoulmate4ever (production)
- **SomeUselessTranslations (AUselessMage)** – complete Starfy 2 script localization, also the source of Dimedime's Starfy 3 script ([videos](https://www.youtube.com/playlist?list=PLA7NjZIk-WKX6E8fTEwiEtI3XlpZy2CQm))
- **Dimedime** – The Legendary Starfy 3 English patch v1.0
- **Luckylodeon98** – Starfy 2 graphics and VWF integration, World 5-3 fruit puzzle art and English clue chain ([GitHub](https://github.com/Luckylodeon98/Densetsu_no_Starfy_2_Translation_ENG))
- **RayCarrot** – VWF (variable-width font) code used in Starfy 2; with **Normmatt**, font graphics, tools and technical help
- **Thanks:** EpicSignal (spotting the World 5-3 puzzle issue), Giantbomb64 (bug hunting: reported the World 2-1 crash)
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

Check with `sha1sum <file>` or `certutil -hashfile <file> SHA1`. If anything doesn't match, please open an issue.

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
| Starfy.1.Eng.v1.0.2.bps | df5d790a6a273d392671db044b3b3de0be9c8609 |
| Starfy.1.Eng.v1.0.2.STT.v1.1.base.bps | 8ca993d292c386350ca3277f0211e109d5013515 |
| Starfy.2.Eng.v0.9.6.bps | f5c2e3139105e075adefacb5a111c4c854f6a1f7 |
| Starfy.3.Eng.v1.0.3.bps | e82864680b24eef73e64984c4e252ceef1fd5097 |
| Starfy.3.Eng.v1.0.3.Dimedime.v1.0.base.bps | b4e813a3696865dab50af2aacbe54c27e1bfe545 |

**Patched results**

| Game | CRC32 | SHA1 |
|---|---|---|
| Starfy 1 Eng v1.0.2 | 72AE1467 | 27c69522d73a8af606f771d7bafc0cecda240baa |
| Starfy 2 Eng v0.9.6 (32 MiB) | E29F64F8 | e86893d9b3e6dd186a8891db0b364ad54797f986 |
| Starfy 3 Eng v1.0.3 | 23170373 | 18968dde90fcc27c1bdc5092f77243c84aa4f85f |

</details>

Thank you for playing!
