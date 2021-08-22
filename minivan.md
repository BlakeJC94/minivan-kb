# Minivan keyboard

---

## Flashing firmware with dfu-programmer

```bash
$ sudo apt install dfu-programmer
```

put keyboard into flashing mode by pressing button on underside
check it appears by using
```bash
$ dfu-tool list
```

erase memory
```bash
$ sudo dfu-programmer atmega32u4 erase
```

flash config
```bash
$ sudo dfu-programmer atmega32u4 flash keymap.hex
```

restart device
```bash
$ sudo dfu-programmer atmega32u4 start
```



---

## Links

- https://www.reddit.com/r/MechanicalKeyboards/comments/5o6dkd/layouts_for_programming_on_a_minivan/
- http://www.keyboard-layout-editor.com/#/gists/34112fcba561109d8516e2a64783120c
- https://github.com/achin/qmk_firmware/tree/tv44/keyboards/tv44/keymaps/achin
- Layouts
    - https://imgur.com/gallery/RrfHy
    - http://www.keyboard-layout-editor.com/#/gists/34112fcba561109d8516e2a64783120c
    - https://medium.com/@jack_21924/crackle-keyboard-layout-for-special-characters-e4dd04838231
    - https://imgur.com/a/GPh48
    - https://i.redd.it/7kppvdk3r2cy.png
    - https://www.reddit.com/r/MechanicalKeyboards/comments/6qr917/my_bantam_44_build_with_bluetooth_and_some_rick/

#### Pimpmykeyboard keycap colors

- White (WAN)
- Blue (BCT)
- Gray (GSF)



http://www.keyboard-layout-editor.com/#/gists/365410b23a30fb67d62e4e6bd7175a9d
