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



