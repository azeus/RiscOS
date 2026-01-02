## RISC-V Toolchain Setup

brew tap riscv-software-src/riscv
brew install riscv-gnu-toolchain

## Verify installation

riscv64-unknown-elf-gcc --version
riscv64-unknown-elf-as --version
