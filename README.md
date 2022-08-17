## Hardware
CPU: 12700k

Motherboard: MSI PRO Z690-a WIFI D4

GPU: Sapphire RX580 2304SP

## BIOS
Initiate Graphic Adapter PEG

IGD Multi-Monitor Disabled

Legacy USB Support Disabled

MSI Fast Boot Disabled

Fast Boot Disabled

VT-D Disabled

CFG LOCK Disabled

Secure Boot Disabled

Secure Device Support Disabled

## OS Version
Monterey 12.5

## Note

The kext is all latest except for **IntelBluetoothFirmware** and the **IntelBTPatcher**.

Thanks for @zxystd, the bluetooth and wifi is worked.

Up till the present moment (2022-07-23)，the author has not released the fixed kext **IntelBluetoothFirmware** and the **IntelBTPatcher**, so, we can only build from code source or fetch from [here](https://github.com/OpenIntelWireless/IntelBluetoothFirmware/issues/369).

If stuck on [EB|#LOG:EXITBS:START] on BIOS version E7D25IMS.170 or latter，maybe you need to trun config.plist **Booter->Quirks->SetupVirtualMap** to true, on the version E7D25IMS.140 you can keep false.

## Image

![image](./%E6%88%AA%E5%B1%8F2022-07-23%2010.41.15.png)
![image](./%E6%88%AA%E5%B1%8F2022-07-23%2011.19.20.png)