# ZMK Firmware
[zmk](https://github.com/zmkfirmware/zmk) firmware for my wireless keyboards.


## Corne Details
- Keyboard: Corne 6 column [typeractive.xyz](https://typeractive.xyz)
- Controller: nice!nano v2
- Screen: nice!view
- Switches: Ambients Silent Kailh Low Profile Choc Switches (Twilight)
- Keycaps: Choc v1 Chicago Steno [etsy-link](https://www.etsy.com/listing/1841812213/choc-v1-chicago-steno-keycap-set-for?ls=s&ga_order=most_relevant&ga_search_type=all&ga_view_type=gallery&ga_search_query=stego+corner+keycaps&ref=sr_gallery-1-1&nob=1&content_source=a32ec505-6821-45c1-91d1-005108213b54%253ALT7028af2d572815f246910ab27bbae6ffca104ee0&organic_search_click=1&logging_key=a32ec505-6821-45c1-91d1-005108213b54%3ALT7028af2d572815f246910ab27bbae6ffca104ee0)
- Simple Nice!View sheild display
> https://github.com/infely/nice-view-battery

## Dongle
- https://github.com/carrefinho/prospector-zmk-module
- https://github.com/janpfischer/zmk-dongle-screen

- Controller: Seed Xiao nRF52840

With typical split keyboard usage the left half of the set will act as the 'brains' relaying all the information from the right to the system you're connecting to. 

This typically causes the battery of the left half of your keyboard set to drain faster than the right.

Using a dongle shifts this work the central node.

While you can use the dongle with a direct USB connection to the system the nRF52840 is capable of BT on it's own so as long as the dongle has power it can connect to multiple systems same as you would with a standard split set.

### Linking to dongle
- turn on dongle, power leftside first then right side. I had found a few random references that stated linking in this order prevents issues with the battery perctage displaying flipped on the dongle screen.

