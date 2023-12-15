**ビルド方法**<br>
事前にPicoSDKに含まれる elf2uf2 ツールを入れておくこと<br>
https://github.com/raspberrypi/pico-sdk<br>
```
$ cargo build
$ cd \target\thumbv6m-none-eabi\debug
$ elf2uf2 rust-twitchy-mouse rust-twitchy-mouse.uf2
```
