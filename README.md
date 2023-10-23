#  Hackintosh: This Time On Honor MagicBook X15
An EFI file for the ones with i5-10210U, and no keyboard backlighting variant.
## What's Working?
*   Wi-Fi
*   BlueTooth
*   camera
*   trackpad
*   audio
*   brightness keys, volume keys
*   iServices
*   HDMI
*   power management
*   battery read-outs
*   DRM
*   RTC
*   NVRAM
*   sleep (partially).
###  Sleep
When the laptop remains asleep for a long time, and I come to the computer to wake it up after a while, I see that the fans are spinning, then I lift the lid slightly - so that the computer does not detect the lid lift input: The keyboard lights are on. When I lift the cover in a way that the computer can detect, the screen does not light up (the screen is completely dark), and even if I press keys on the keyboard in a way that MacOS would give a warning, it does not provide a warning sound (I think it is still in sleep). So I have to hold the power button (to turn it off) and press it again (to turn it on).
#  What's Not Working?
*   secure boot
# Config
Note: I used a configurator to show the config because the contents of the config did not fit into the ProperTree window.
###  ACPI
####  AMLs
![image](https://github.com/Turkifier/Honor-MagicBook-X15-Hackintosh/assets/34972126/0e77b3be-b324-4cb4-ad32-44a7457e2428)
####  Patches
![image](https://github.com/Turkifier/Honor-MagicBook-X15-Hackintosh/assets/34972126/e8a9c307-b079-4fa4-8935-b5a1c8d9cf57)
### KEXTs
![image](https://github.com/Turkifier/Honor-MagicBook-X15-Hackintosh/assets/34972126/c315b054-1489-4d7c-acd7-aff45ea70368)
###  Boot Arguments
![image](https://github.com/Turkifier/Honor-MagicBook-X15-Hackintosh/assets/34972126/47e99a65-dab7-4815-926c-98e8850bd8a6)
