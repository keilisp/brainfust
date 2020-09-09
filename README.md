# Rust brainf\*ck compiler

# Description

Simple brainf\*uck complier written in Rust using LLVM

# Installation

At first you need to setup LLVM usign ![this](https://crates.io/crates/llvm-sys) guide

Then clone the repo into your folder

```sh
cd *your-folder*
git clone https://mediocreeee/brainfust.git
```

# Usage

Run the program via cargo

```sh
cargo run *yourbffile.bf* -o bfoutput.o
```

Then compile it with gcc

```sh
gcc bfoutput.o
```

Run the binary

```sh
./a.out
```
