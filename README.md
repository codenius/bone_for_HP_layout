# Bone for HP Windows keyboard layout

The `><|` key (ISO scan code `0x56`) is mapped to Right Ctrl in `source/kbdbone/kbdbone.h`.

Pushes and pull requests build the 64-bit and 32-bit Windows layout DLLs with GitHub Actions. The workflow installs the required `kbd.h` header from Microsoft's WDK NuGet package and uploads the resulting DLLs as the `bone-for-hp-dlls` workflow artifact.
