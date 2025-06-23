# cresk_choc_nrf52

## Build

``` shell
cd path/to/zmk/app
west build -b cresk_choc_nrf52833_left -- -DZMK_EXTRA_MODULES="/path/to/zmk-cresk-module" -DZMK_CONFIG="/path/to/cresk_choc_nrf52-zmk-config/config"
west build -b cresk_choc_nrf52833_right -- -DZMK_EXTRA_MODULES="/path/to/zmk-cresk-module" -DZMK_CONFIG="/path/to/cresk_choc_nrf52-zmk-config/config"
```
