# macOS Big Sur - Opencore EFI for i5-4570 + Asus B85MG Motherboard + HD4600 iGPU

#### macOS Big Sur Version : ~~11.2~~ ~~11.2.3~~ 11.3.1 (Refer to [System Update](#system-update) part)
#### Opencore Version : 0.6.6
#### Special thanks to [Daliansky](https://github.com/daliansky)
#### EFI Download : [Click here](https://github.com/samleong123/i5-4570-B85MG-HD4600-BigSur-Opencore-EFI/releases)
#### Screenshots : [Click here](#screenshots)

### Specifications
| Hardware                           | Status                                                                                                                                                    |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Intel i5-4570                      | Working                                                                                                                                                   |
| ALC887 with Asus B85MG Motherboard | Working with layout-id 40 (Be sure to choose Line Out for Audio Jack located at back of the Motherboard) (Never test front audio jack not sure is it working) |
| Intel Graphics HD4600 (iGPU)       | Working (DRM seems to be not supported)                                                                                                                   |
| Realtek RTL8111 1Gbps              | Working                                                                                                                                                   |
| USB Front                          | Working                                                                                                                                                   |
| USB Back (3.0)                     | Working                                                                                                                                                   |
| SMBIOS                             | iMac 14,4                                                                                                                                                 |
| Intel AX200                        | Working with 802.11N/AC/AX 40MHz,80MHz,160MHz (Thanks to itlwm v2.0.0 Alpha Driver)                                                                       |

### Intel WiFi Card
- Intel WiFi Card has successfully run on macOS Big Sur based on [itlwm](https://github.com/OpenIntelWireless/itlwm/) !
- I added [itlwm v2.0.0 Alpha](https://github.com/OpenIntelWireless/itlwm/releases/tag/v2.0.0-alpha) for using Intel WiFi Card !
- OpenCore edited with Force Load 80211IO and AirportItlwm (natively support Intel WiFi Card direct from system panel)
- [itlwm v2.0.0 Alpha](https://github.com/OpenIntelWireless/itlwm/releases/tag/v2.0.0-alpha) added support for 802.11n/AC/AX 40MHz,80MHz,160MHz so you can gain **Almost same experience** on Windows (Read here : https://openintelwireless.github.io/itlwm/FAQ.html#features )
- I use AX200 + itlwm v2.0.0 Alpha
- Some screenshots about [itlwm v2.0.0 Alpha](https://github.com/OpenIntelWireless/itlwm/releases/tag/v2.0.0-alpha)
![AX200](https://github.com/samleong123/i5-4570-B85MG-HD4600-BigSur-Opencore-EFI/blob/main/Screenshot%202021-05-22%20at%2017.01.20.png?raw=true)
![DL](https://github.com/samleong123/i5-4570-B85MG-HD4600-BigSur-Opencore-EFI/blob/main/AX200%20DL.png?raw=true)
![UL](https://github.com/samleong123/i5-4570-B85MG-HD4600-BigSur-Opencore-EFI/blob/main/AX200%20UL.png?raw=true)
![Youtube with WiFi](https://github.com/samleong123/i5-4570-B85MG-HD4600-BigSur-Opencore-EFI/blob/main/Screenshot%202021-05-22%20at%2017.03.45.png?raw=true)

### Screenshots
![Ethernet](https://raw.githubusercontent.com/samleong123/i5-4570-B85MG-HD4600-BigSur-Opencore-EFI/main/Ethernet.png)
![System Info](https://raw.githubusercontent.com/samleong123/i5-4570-B85MG-HD4600-BigSur-Opencore-EFI/main/System%20Info.png)
![Youtube](https://raw.githubusercontent.com/samleong123/i5-4570-B85MG-HD4600-BigSur-Opencore-EFI/main/Youtube.png)
![Netflix](https://raw.githubusercontent.com/samleong123/i5-4570-B85MG-HD4600-BigSur-Opencore-EFI/main/Netflix.png)
![Sound](https://raw.githubusercontent.com/samleong123/i5-4570-B85MG-HD4600-BigSur-Opencore-EFI/main/Sound.png)


### System Update
Tested update from 11.2 to 11.2.3 to 11.3.1.
![11.2](https://raw.githubusercontent.com/samleong123/i5-4570-B85MG-HD4600-BigSur-Opencore-EFI/main/System%20Info.png)
![11.2.3](https://raw.githubusercontent.com/samleong123/i5-4570-B85MG-HD4600-BigSur-Opencore-EFI/main/Screenshot%202021-03-26%20at%2010.18.26.png)
![11.3.1](https://github.com/samleong123/i5-4570-B85MG-HD4600-BigSur-Opencore-EFI/blob/main/Screenshot%202021-05-22%20at%2017.06.11.png?raw=true)

