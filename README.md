# Learning Rust

Working through the examples from the [book](https://doc.rust-lang.org/book/index.html).

## Installing Rust

```bash
curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
```

or, if we don't want to install rust on the host machine, we can run containerised:

```bash
docker run --rm --user "$(id -u):$(id -g)" --volume "$PWD":/usr/src/hello-world --workdir /usr/src --name rust-dev --detach -it rust:latest
```
