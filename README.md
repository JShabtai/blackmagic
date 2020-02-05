Black Magic Probe (NRF52 only)
=================

This is a fork of the [official Black Magic Probe](https://github.com/blacksphere/blackmagic).
Targets other than the NRF52 have been removed to reduce the size. It should now fit comfortably on a 64K Blue Pill (STM32F103C8T6 dev board)

Hopefully this makes it easier for people to get started with nrf52 development.

The project can be built with the following command:

```
make -j PROBE_HOST=swlink
```

