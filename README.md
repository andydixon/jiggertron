# RP2040 USB HID Proof of Concept - Jiggertron


## Do the system configureful

```shell
rustup target install thumbv6m-none-eabi
cargo install flip-link
cargo install elf2uf2-rs --locked
```

## Do the buildful

Reset the controller by BOOT+RST into bootloader mode, when the volume appears in the os
```shell
cargo build
```