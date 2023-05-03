# OS
A bare metal Rust based OS (for education purpose)
to follow the tutorial go to [here](https://os.phil-opp.com/) thanks Philipp Oppermann!


# install dependencies
you will have to install rustup

```bash
$ curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

then install the rust nightly toolchain

```bash
$ rustup install nightly
```

then install the rust source code

```bash
$ rustup component add rust-src
```

then install the rust llvm tools

```bash
$ rustup component add llvm-tools-preview
```

# run the project
you will have to install qemu

```bash
$ brew install qemu
```

then run the project with cargo run

```bash
$ cargo run

```