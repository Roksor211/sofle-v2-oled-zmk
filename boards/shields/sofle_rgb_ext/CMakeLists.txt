# Extended Sofle RGB (extra top row) shield
zephyr_library_named(shield_sofle_rgb_ext)
zephyr_library_sources_ifdef(CONFIG_ZMK_KEYBOARD_SOFTWARE "sofle_rgb_ext.overlay")
