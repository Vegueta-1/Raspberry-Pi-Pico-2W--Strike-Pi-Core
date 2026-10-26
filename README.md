<img width="1376" height="768" alt="Strike Pi Core Studio banner 1280x300 pixels" src="https://github.com/user-attachments/assets/95aaafd8-9ac0-4129-a83c-70ef751dfdb2" />




Raspberry-Pi-Pico-2W--Strike-Pi-Core
Strike Pi Core is a next‑generation, open‑hardware controller enhancement platform built for gamers who want professional‑grade mods without the professional‑grade price tag. Powered by the Raspberry Pi Pico 2W microcontroller, Strike Pi Core delivers rapid‑fire, burst‑fire, anti‑recoil, macro scripting, and tactical assists with the precision of commercial devices like Cronus Zen — but completely free and DIY‑friendly.

Designed for accessibility, Strike Pi Core lets players configure every feature through a clean, intuitive Windows companion app. Rapid‑fire tuning, macro creation, assist toggles, and profile management are all handled through a modern interface, then saved directly into the device's onboard memory. Once configured, Strike Pi Core runs fully standalone: plug it into any supported console or PC, and your saved mods activate instantly.

🧩 Hardware Requirements
Raspberry Pi Pico 2W 
Supports true 1000 Hz polling (1 ms), ensuring zero input lag — ideal for competitive gaming.

USB cable 
Used for both power and programming.

PS4 DualShock Controller 
Supported models: JDM‑001 / 011 / 020 / 030 / 040 / 050 / 055

Sony DualSense Controller 
Alpha support — tested on model BDM‑010

🔧 Flashing the Firmware- download zip -includes firmware, app and Guide. [https://mega.nz/file/70QRVJ5Y#8SCg3qcpkyi8exqQUcCqC6rrmNl55X7vsA-Xv6VWyuI](https://mega.nz/file/u4AmDRYJ#l3NLY6-zH1ymGhKERPmI0UHhaOsxU0mcK-0HMKYrGgg)

Hold BOOTSEL on the Pico 2W while plugging it into your PC.

A drive named RPI‑RP2 will appear.

Copy Strike Pi Core Dongle.uf2 onto the drive.

The Pico 2W will reboot automatically and begin running the firmware.

🎮 Usage
Connect the Pico 2W (running Strike Pi Core firmware) to your supported console or PC via USB.

Put your controller into pairing mode:

DualShock 4: Hold Share + PS until the light bar flashes.

DualSense: Same process.

The Pico 2W automatically discovers and connects to the controller.

Your controller input is forwarded as a standard USB HID gamepad.

LED Status Indicators
Fast blink: Scanning / waiting for a controller

Slow blink (~1 Hz): Controller connected and streaming input

🛠 Configuration — Strike Pi Core Studio Only can be configured on PC
Use the Windows companion app to configure: Rapid‑fire, Burst‑fire, Anti‑recoil, Macros, Assists and Profiles.  


<img width="2550" height="1401" alt="Screenshot 2026-10-02 170247" src="https://github.com/user-attachments/assets/592d31b2-e467-419d-b904-8f85c2c94425" />
<img width="2517" height="399" alt="Screenshot 2026-10-02 170304" src="https://github.com/user-attachments/assets/f9239390-d421-4e15-ac79-97623ada89ff" />

Update Log — Smart Anti‑Recoil & UI Improvements

 Smart Anti‑Recoil Enhancements

Added Weapon Profile Locking — tune recoil on the test range and save the learned pattern.

Smart Anti‑Recoil no longer overwrites locked profiles during gameplay.

Improved adaptive learning speed and consistency.

Better handling of mixed fire‑rate weapons and burst‑hybrid recoil patterns.


 UI & Visual Improvements

Updated the Strike Pi Core Studio app icon with a cleaner, modern look.

All changes apply instantly through the Strike Pi Core Protocol. After that you can use it without the app open or on the other devices that supported.





Consoles That Support USB HID Gamepads (Native or Semi‑Native)
​

PC (Windows / Linux / macOS)
Fully supports USB HID gamepads.
This is the most compatible and stable platform.

Nintendo Switch
Supports USB HID gamepads in Wired Pro Controller Mode.

Android Phones & Tablets
Supports USB HID gamepads through OTG or USB‑C adapters.


coming soon PlayStation 4 console support if you have you own keys

Strike Pi Core Studio V2 Development Update
​
I'm excited to share that Strike Pi Core Studio V2 is officially in development, and for the first time I've successfully achieved PS5 DualSense controller support on a PS4 console using Strike Pi Core hardware.

This isn't just a concept anymore. It's currently working on real hardware, and active testing is underway.

Current test setup shown below:

PS5 DualSense and PS4 Controllers connected through Strike Pi Core
<img width="4080" height="3060" alt="PS4 DualShock 4 JDM-055 " src="https://github.com/user-attachments/assets/2886ae5f-8c24-4727-a44b-5dfc654420e8" />

<img width="4080" height="3060" alt="PS5 DualSense BDM-010" src="https://github.com/user-attachments/assets/9fb7573f-7b12-42cf-a2a7-36e1ae297727" />

What V2 Will Bring​
Version 2 is much more than a simple update. Nearly every part of the software is being redesigned and improved.

Planned Features​
🔹 PS4 Console Support with PS5 DualSense Controllers

🔹 Enhanced Authentication System

🔹 Improved Device Detection

🔹 Expanded Rapid Fire Engine

🔹 Advanced Anti-Recoil System

🔹 Improved Macro Creation and Management

🔹 Profile Save / Load Enhancements

🔹 Better Controller Diagnostics

🔹 Firmware Management Improvements

🔹 Hardware Monitoring Tools

🔹 Faster Configuration Deployment

Complete UI Redesign from Scratch​
One of the largest changes coming in V2 is a complete redesign of the interface.

Rather than building on the existing UI, the application is being rebuilt from the ground up with a cleaner and more modern.
<img width="2549" height="1407" alt="Strike PI Core v2 0 dashboard" src="https://github.com/user-attachments/assets/0435d0b4-1c63-4ed8-946f-44c1c74bce0a" />
<img width="2554" height="1404" alt="Strike PI Core v2 0" src="https://github.com/user-attachments/assets/05305888-e407-4153-b36b-df40271172f3" />

Safety and Legal​
Use your own hardware and keys.

Strike Pi Core does not provide Sony authentication keys, certificates, firmware, or any proprietary materials.

Users must obtain any required identity information from hardware they personally own. Importing data from hardware you do not own may violate local laws, contracts, or platform terms of service.

Owners of a DS4 JDM-011 board can follow this guide to extract identity information from their own hardware:

https://github.com/Vegueta-1/DS4-JDM-011-2014-Firmware-Dump-Identity-Extraction-2026-guide-and-Tools

Current Development Status​
The hardware, firmware, and software are all being actively tested and refined.

The successful PS4 + DualSense testing marks a major milestone for the project, and development is continuing toward a full V2 release.

Thank you to everyone supporting the project.

More screenshots, testing results, previews, and feature showcases will be shared as development continues.

Strike Pi Core Studio V2 is coming.

Developed by Vegueta1
