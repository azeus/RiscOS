## RISC-V Toolchain Setup

brew tap riscv-software-src/riscv
brew install riscv-gnu-toolchain

## Verify installation

riscv64-unknown-elf-gcc --version
riscv64-unknown-elf-as --version

## Install QEMU with RISC-V support
brew install qemu

## Verify RISC-V system emulation
qemu-system-riscv64 --version

## Create project structure
mkdir -p riscos/{boot,kernel,docs,scripts}
cd riscos
git init
