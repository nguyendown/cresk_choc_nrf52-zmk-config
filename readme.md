# cresk_choc_nrf52

## Build

``` shell
cd path/to/zmk/app
west build -p -b cresk_choc_nrf52833_left -- -DZMK_CONFIG=path/to/cresk_choc_nrf52/config
west build -p -b cresk_choc_nrf52833_right -- -DZMK_CONFIG=path/to/cresk_choc_nrf52/config
```
