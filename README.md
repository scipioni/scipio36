# scipio36
My corne crkbd qmk layout with 36 keys and miryoku directives

## prereq

arch
```
pacman -S qmk
```

qmk repo
```
git clone https://github.com/qmk/qmk_firmware.git
git clone https://github.com/scipioni/scipio36.git keyboards/crkbd/keymaps/scipio36
```

setup qmk
```
qmk setup
```


## personalize (optional)

Upload keyboards/crkbd/keymaps/scipio36/scipio36-miryoku.json on https://config.qmk.fm and modify

Download scipio36-miryoku.json and make layout.h
```
qmk json2c keyboards/crkbd/keymaps/scipio36/scipio36-miryoku.json -o keyboards/crkbd/keymaps/scipio36/layout.h
```

## compile

```
make crkbd:scipio36:avrdude
```

## resources
