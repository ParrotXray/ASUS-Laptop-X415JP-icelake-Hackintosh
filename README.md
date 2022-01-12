# Asus-laptop-X415jp-Hackintosh

## 🖥️Device
| Model | Asus Laptop X415JP |
|------------|-------------------------------|
| CPU | i5 1035G1 |
| GPU | Intel UHD Garphics |
| RAM | 16GB |
| Audio | Realtek ALC256 |
| WIFI／Bluetooth | DW1820A |
| BIOS Version | 303 |

## 📀System
OS：MacOS Big Sur

SMBIOS：MacBookPro16,2

## 🛠️Setting BIOS
Advanced > AES-NI：Disable

Advanced > SATA Configuration > SATA Mode Selection：AHCI

Boot > Fast Boot：Disable

Security > Secure Boot > Secure Boot Control：Disable

CFG Lock：Disable,You need to use ControlMsrE2.efi

                <key>Tools</key>
                <array>
                        <dict>
                                <key>Arguments</key>
                                <string>unlock</string>
                                <key>Auxiliary</key>
                                <true/>
                                <key>Comment</key>
                                <string></string>
                                <key>Enabled</key>
                                <true/>
                                <key>Name</key>
                                <string>ControlMsrE2</string>
                                <key>Path</key>
                                <string>ControlMsrE2.efi</string>
                                <key>RealPath</key>
                                <false/>
                                <key>TextMode</key>
                                <false/>
                        </dict>
                </array>
## 💡Device stetus
### Works：
- [x] Graphics
- [x] USB
- [x] Webcam
- [x] Brightness controls
- [x] Battery percentage
- [x] Sleep
- [x] TouchPad
- [x] WiFi
- [x] Speakers
- [x] Microphone
- [x] Bluetooth
### No Works：
- [ ] HDMI and HDMI Audio
### Unkown：
- [ ] Apple Services
