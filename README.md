# Dell-5567-Big-sur-efi
Opencore Efi for Dell 5567 i7 7500u

 - What Works:
  - Amost everything is working perfectly
  - Sound
  - Graphics Intel 620 @ 1538 MBS Full Hardware acceleration
  - Touchpad with all gestures and tap to touch with integrated Apple Driver
  - Brightness Keys Working and Brightness Works
  - Battery % Indicator
  - Internal Intel 3165 Wifi
  - Camera
  - Bluetooth

 - What Not Works:
  - Touchscreen is not working i am working on that..
  
 - USB CREATION:
  - Download Big Sur app in App Store and upon download complete create a USB for Big Sur Using this Command in Terminal app:
    - sudo /Applications/Install\ macOS\ Big\ Sur.app/Contents/Resources/createinstallmedia --volume /Volumes/<YOUR USB DRIVE NAME> --nointeraction
    - Just Change <Your USB Drive Name> with the name your usb drive have (you can check that in diskutility)
  - When terminal is done creating USB Mount your USB Efi Drive Using ESP MOUNTER or OPENCORE Configurator Utility.
  - Paste All 3 /Dell /OC and/Boot Folers into you Efi Drive into a Folder Named EFI.
  - Boot From USB and start Installation.
  - After the First Phase finished boot from opencore Menu named Installer MacosBigSur.

 - NOTE: it will restart many times during installation so dont panic.
  
  Best of Luck..
