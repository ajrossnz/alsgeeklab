# alsgeeklab
artefacts relating to Al's Geek Lab YouTube shows

## U18 and U19 roms (phatroms compiled for IntelInboard/386 PC)
The phatrom is an updated ROM pack for the IBM 5160 / XT or compatible XT's https://www.phatcode.net/downloads.php?id=101&action=get&file=pcxtbios31.zip, much like GLaBIOS. This one is known to work with the Intel Inboard/386, so this is here for that purpose. This is the 5160xt ROM images. I recompiled these as I changed the .ASM file to switch off (undefine) the turbo hotkey, since there is already a turbo hotkey built into the Inboard. I also switched off the turbo flag/turbo boot as it is superflous on an Inboard.
```
;TURBO_ENABLED   = 0             ; Define to enable "turbo" support
;TURBO_BOOT      = 0             ; Define to boot up in turbo mode (full speed)
;TURBO_HOTKEY    = 0             ; Define to enable "CTRL ALT -" hotkey to toggle turbo mode
```
