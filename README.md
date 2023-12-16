# P50-Hackintosh-Opencore


## Disclaimer
This EFI should only be used to help fix your own. Please make your own EFI using https://dortania.github.io/OpenCore-Install-Guide/.

## Specs
Intel Core i7-6700HQ

Intel HD 530

Nvidia Quadro M2000M (Disabled) 

WDC PC SN730 SDBQNTY-512G-1001 Media (Windows 11)

SM961 NVMe SAMSUNG 512GB Media (MacOS Sonoma)

48GB DDR4 2133 RAM

Intel Dual Band Wireless-AC 8260

MacOS Sonoma 14.2

OpenCore 0.9.7

## What's Working
MacOS

Bluetooth

Wi-Fi

IServices (Only with HeliPort + itwlm instead of Airportitwlm) 

Contiunity IPhone -> Mac

Graphics Accleration through OCLP

Camera, Microphone, and Speaker

## What's Not Working
dGPU (Not Compatible with MacOS)

AirDrop

Contiunity Mac -> iPhone

Location Services (I think this is because im using itwlm instead of Airportitwlm) (Can be fixed with AirportItwlm update)

DRM (IGPU doesnt work with DRM)

Video Out (I Think this is through the dGPU which is disabled)






