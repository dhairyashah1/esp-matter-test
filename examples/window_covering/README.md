# Window Covering
### Reference [esp-matter github issue #168](https://github.com/espressif/esp-matter/issues/168)

This example creates a Window Covering device using the ESP
Matter data model.

See the [docs](https://docs.espressif.com/projects/esp-matter/en/main/esp32/developing.html) for more information about building and flashing the firmware.

## 1. Additional Environment Setup

No additional setup is required.

## 2. Post Commissioning Setup

No additional setup is required.

## 3. Device Performance

### 3.1 Memory usage

TYet to be updated

Applications that do not require BLE post commissioning, can disable it using app_ble_disable() once commissioning is complete. It is not done explicitly because of a known issue with esp32c3 and will be fixed with the next IDF release (v4.4.2).
