# GitHub Action Build Status
[![Release Clang Build](https://github.com/mengkernel/clang-build/actions/workflows/build.yml/badge.svg)](https://github.com/mengkernel/clang-build/actions/workflows/build.yml)

# Download
Check latest release [here](https://github.com/mengkernel/clang-stable/releases/latest)

# Installation
```bash
rm -rf $HOME/.kucing-clang
mkdir $HOME/.kucing-clang
tar xf clang.tar.zst -C $HOME/.kucing-clang
echo "export PATH=$HOME/.kucing-clang/bin:$PATH" >> ~/.bashrc
source $HOME/.bashrc
clang --version
```

# Features
```
  ==> Minimal LLVM 20.1.0-20250307 targeting 'AArch64' and 'X86'
  ==> Stripped binaries
  ==> Download size 239MB
  ==> Compressed tar archive with zstd v1.5.6
  ==> Build LLVM Polly & LLD
  ==> Build with ThinLTO + PGO
```
# Build script

  Visit https://github.com/mengkernel/clang-build
