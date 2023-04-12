# TESEUS

## About TESEUS

TESEUS stands for TEst SErver for US. It provides a simple HTTP protocol web server.

## Requirements

- Python3.10
- Poetry

## Setup

1. Derive source code

    ```shell
    % git clone git@github.com:aYukiYoshida/teseus.git # via SSH
    ```

1. Install dependencies

    ```shell
    % poetry install
    ```

1. (optional) Install pre-commit

    ```shell
    % poetry run pre-commit install
    ```

## Commands

- Run server

    ```shell
    % poetry run teseus
    ```

- Run server with specified port

    ```shell
    % poetry run teseus --port 8888
    ```

- Run server with debug mode

    ```shell
    % poetry run teseus --debug
    ```
