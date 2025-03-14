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
  ==> Minimal LLVM 17.0.6-20250313 targeting 'AArch64', 'ARM' (20250313 and newer), and 'X86'
  ==> Stripped binaries
  ==> Download size 222MB
  ==> Compressed tar archive with zstd v1.5.7
  ==> Build LLVM Polly & LLD
  ==> Build with ThinLTO + PGO
```
# Build script

  Visit https://github.com/mengkernel/clang-build
