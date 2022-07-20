# hackintosh-xps-13-9370-monterey-opencore-0.8.3
hackintosh-xps-9370
EFI configuration and assorted notes on the xps 9370 configuration

<b>The Laptop Specs Below</b>

Dell XPS 13 9370

Intel Core i7 8550U (Kaby Lake)

Intel HD graphics 620

4k resolution touchscreen

8Gb LPDDR3 1866MHz Ram

Toshiba 256NVME SSD

Killer WiFi 1535 (internal wifi is soldered and will not work, currently using wifi-dongle tp-link archer t2u 11ac)

Webcam


<B>WHAT WORKS</B>

4k with touchscreen (for FHD laptops, will need to replace AAPL,ig-platform-id and device-id most likely)


igpu

touchpad

thunderbolt ports

usb c ports

iservices (need to use rehabman nullethernetinjector.kext, replace mac with tp-link mac address)

internal bluetooth

webcam facetime

imessages

sleep

almost everything




<B>WHAT DOESN'T WORK</B>

internal wifi (using wifi dongle TP-LINK ARCHER T2U 11AC off Amazon)

AppleTV (needs DGPU for DRM)

