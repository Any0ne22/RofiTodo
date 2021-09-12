# **RofiTodo**

![Build](https://github.com/Any0ne22/RofiTodo/actions/workflows/rust.yml/badge.svg)
![LastCommit](https://img.shields.io/github/last-commit/Any0ne22/RofiTodo)
![LastRelease](https://img.shields.io/github/v/release/Any0ne22/RofiTodo)

A to-do list using Rofi

## **Installation**

1) Clone this repository
2) Go to `Rofitodo`
3) Run the following commands

    ```bash
    autoreconf -si
    ./configure
    make
    make install
    ```

    You can also build RofiTodo using cargo with

    ```bash
    cargo build --release
    ```

    and put the `rofitodo` executable (located in `target/release`) where you want.

## **Usage**

- Specify a tasklist-file:

    ```bash
    rofitodo -c path/to/your/todolist
    ```

- Use a specific rofi config file:
