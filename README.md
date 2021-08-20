# Playground

- [Playground](#playground)
  - [Requirements](#requirements)
  - [Run the Demos](#run-the-demos)

Demo scripts for the ultra fast and slim kubernetes playground.

Currently, the following services are integrated:

- Container Security

## Requirements

Running playground with registry deployed.

The playground must be located next to the `playground-demos` folder and have the word `playground` in the directory name.

Ensure to have run `up.sh` and `deploy-registry.sh` according to the [README.md](../README.md) of the playground. If you already deployed additional components, please restart from scratch (`down.sh`, `up.sh`, `deploy-registry.sh`).

## Run the Demos

```sh
./demo-container-security.sh
```
