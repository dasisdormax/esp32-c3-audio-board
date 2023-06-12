# WIP: esp32-c3-headset

## Components and data sheets

- ESP32-C3:
  - Series Datasheet: https://espressif.com/documentation/esp32-c3_datasheet_en.pdf
  - ESP32-C3-WROOM-02 Module Datasheet: https://www.espressif.com/documentation/esp32-c3-wroom-02_datasheet_en.pdf
- Battery:
  - Cell holder: Keystone 2460: https://www.keyelco.com/userAssets/file/Keystone-M70-FullVersion.pdf
  - Battery Charge controller MCP73831-2ACI-OT: http://ww1.microchip.com/downloads/en/DeviceDoc/20001984g.pdf
  - Battery protection: BQ29728: https://www.ti.com/lit/ds/symlink/bq2972.pdf
  - Battery charge/discharge MOSFET: DMG9926 https://www.diodes.com/assets/Datasheets/ds31770.pdf
- Power Supply:
  - p-channel enhancement MOSFET: DMP3165L https://www.diodes.com/assets/Datasheets/DMP3165L.pdf
  - TPS63031 Buck-Boost Converter: https://www.ti.com/lit/ds/symlink/tps63031.pdf
- Audio:
  - Connector: PJ320-D
  - Stereo Audio DAC: PCM5102: https://www.ti.com/lit/ds/symlink/pcm5102.pdf
  - Stereo Audio Amplifier: 
    - PAM8908: https://www.diodes.com/assets/Datasheets/products_inactive_data/PAM8908.pdf
    - Compatible alternative TPA6132A2: https://www.ti.com/lit/ds/symlink/tpa6132a2.pdf

## Licensing

Copyright © 2023 Maximilian Wende

- KiCad components: These are adapted from the KiCad Libraries and licensed [under the same terms](https://www.kicad.org/libraries/license/).
- Hardware design, documentation and remaining files: GNU General Public License, version 3 or later.