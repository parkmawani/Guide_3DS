---
head:
  - - script
    - src: /assets/js/common.js
  - - script
    - src: /assets/js/soundhax-frankenfirm-link.js
  - - script
    - src: /assets/js/link-common.js
---

# Hibaelhárítás (Soundhax)

Ez az oldal hibaelhárítási tanácsokat ad sűrűn előforduló problémákhoz a "Boot9strap telepítése (Soundhax)" oldalhoz, ami az 1.0.0 és 11.3.0 rendszer verziókon használt. Ha nem tudod megoldani a problémád az oldal tanácsai alapján, csatlakozz a [Nintendo Homebrew-hoz Discord-on](https://discord.gg/MWxPgEp) és írd le a problémádat és azt is hogy mi az amit már próbáltál.

## Problémák a Soundhax-szal

:::details Piros/lila/rózsaszín és fehér képernyő a Soundhax futtatása után

Ha a konzol rendszer verziód 9.4.0, 9.5.0, vagy 9.6.0, hibát tapasztalhatsz az universal-otherapp egy régebbi verziójával. Töltsd le a legfrissebb verziót [innen](https://github.com/TuxSH/universal-otherapp/releases/latest).

Ha nem ezeken a firmware verziókon van a konzolod, akkor ez valószínűleg azt jelzi, hogy már van egyedi firmware-ed. Érdemes elvégezned a [CFW ellenőrzését](checking-for-cfw).

:::

:::details "An error has occurred, forcing the software to close..." (fehér üzenet ablak)

Probléma van a `otherapp.bin` fájloddal (nem jó, hiányzik, rossz helyen van vagy sérült). Töltsd le a legutolsó kiadását az [universal-otherapp](https://github.com/TuxSH/universal-otherapp/releases/latest)-nak és rakd az SD kártyád gyökerébe.

If the above doesn't fix your issue, and you are using an Old 3DS / Old 3DS XL / Old 2DS, you may be encountering an issue involving cartridge updates. Take another look at the system version. If the last number is 4 or lower (e.g. 11.3.0-**4**U), replace the Soundhax file on the root of your SD card with the one from [here](http://soundhax.686178.xyz/frankenfirm.html?crash).

If none of these fix your issue, join [Nintendo Homebrew on Discord](https://discord.gg/MWxPgEp) for assistance.

:::

:::details "Could not play"

You have the wrong Soundhax file for your console, region and version. Double-check that you entered all the info correctly into the [Soundhax website](https://soundhax.com/), redownload your Soundhax file, and replace it with the one on the root of your SD card.

If the above doesn't fix your issue, and you are using an Old 3DS / Old 3DS XL / Old 2DS, you may be encountering an issue involving cartridge updates. Take another look at the system version. If the last number is 3 or lower (e.g. 11.3.0-**0**U), replace the Soundhax file on the root of your SD card with the one from [here](http://soundhax.686178.xyz/frankenfirm.html?unplayable).

If none of these fix your issue, join [Nintendo Homebrew on Discord](https://discord.gg/MWxPgEp) for assistance.

:::

:::details Failed to mount the SD card!

Ha ez sikertelen, próbálkozz egy másik SD kártyával.

:::

## Problémák a SafeB9SInstaller-rel

<!--@include: ./_include/troubleshooting-sb9si-bin.md -->

<!--@include: ./_include/troubleshooting-sb9si-common.md -->

<!--@include: ./_include/troubleshooting-get-help-common.md -->

---

::: tip

Vissza [Boot9strap telepítése (Soundhax)](installing-boot9strap-\(soundhax\))-hoz

:::

<!--@include: ./_include/troubleshooting-return.md -->
