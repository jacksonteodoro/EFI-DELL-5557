# EFI Dell Inspiron 15-5557 with OpenCore

<div align="center">
  <img width="1500" alt="Screen shot Dell 5557" src="https://user-images.githubusercontent.com/20369803/159422302-7f67dc77-528f-4820-9561-77514c0c9036.png">
  Dell 5557 running Monterey
</div>

## System Information
<div align="center">
  
| Specification | Details | Comments |
| :--- | :--- | :--- |
|Computer model |Dell Inspiron 15-5557 |
|Processor |Intel Core i7 - 6th generation Intel Core i7-6500U ULV </br> 2.5 GHz to 3.1 GHz Max Turbo Cache: 4Mb|
|RAM |16GB DDR3L 1600MHz (2X8) |
|Display |15.6”  FULL HD 1920x1080p 60Hz |
|Camera |Intel(R) RealSense(TM) 3D Camera (Front F200)</br>1280 x 720 (HD) at 30 fps (maximum) |Only depth mode. see image above |
|Graphics |
||**Integrated:** Intel® HD Graphics 520 | |
||**Discrete:** NVIDIA® GeForce 930M with 4GB DDR3 | Disable |
|Audio |Realtek ALC3234CG |
|Communication card|Dell wireless DW1820 Dual Band + Bluetooth 4.0 - QCNFA344A |
||**Wireless** |Don’t have support. </br>I utilize HoRNDIS.kext (included on EFI) for Android USB Tethering. |
||**Bluetooth** |Works fine. |
|Ethernet |Realtek RTL8106E |
|Touchscreen | |Works fine. |
|Backlight | |This shortcuts iterate with the interface slide button:</br>- Decrease: Fn+S</br>- Increase: Fn+B.</br></br>The original (F11 - F12) iterates with BIOS separately from above. Generate crash sometimes, and only is active if on BIOS is enable:</br>`General` -> `Advanced Boot Options` -> `Enable Legacy Option ROMs` |

  
 </div>
