EFI
\CLOVER
 +ACPI
 |\patched
 | \SSDT-UIAC.aml ---- USBInjectAllの設定。EHCIを無効、XHCIの使用ポートのみ有効にする
 \config.plist ---- Cloverの設定

SSDT-UIAC.amlはHackintoolで生成した後、下記ページのコードを追加してをEHCI無効化(理解はできてない)したもの。
https://www.tonymacx86.com/threads/guide-creating-a-custom-ssdt-for-usbinjectall-kext.211311/

config.plistの解説は以下。SMBIOSは各自設定する。
https://pastebin.com/MWSdGkvB