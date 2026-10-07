# Clef Flash inference snap
[![clef-flash](https://snapcraft.io/clef-flash/badge.svg)](https://snapcraft.io/clef-flash)

Clef-Flash is a 9B multimodal decision model that turns text, JSON, images, or video into typed decisions and probabilities.

Use this snap to quickly install an optimized environment for local inference with Clef Flash.

The snap includes the following hardware-optimized inference engines:

* cpu: Optimized for x64 and ARM CPUs
* nvidia-gpu: CUDA-enabled GPU acceleration
* amd-gpu: ROCm-enabled GPU acceleration

The most suitable engine is automatically selected based on the available hardware.

#### Install
```
sudo snap install clef-flash
```

#### Run
```
clef-flash
```

> [!TIP]
> Some accelerators require extra [drivers](https://documentation.ubuntu.com/inference-snaps/how-to/setup/drivers/) to be usable with this snap.

## Resources

📚 **[Documentation](https://documentation.ubuntu.com/inference-snaps/)**, learn how to use inference snaps

💬 **[Discussions](https://github.com/canonical/inference-snaps/discussions)**, ask questions and share ideas

🐛 **[Issues](https://github.com/canonical/inference-snaps/issues)**, report bugs and request features

## Build and install from source

Clone the repo:
```shell
git clone https://github.com/canonical/clef-flash-snap.git
cd clef-flash-snap
```

Initialize the development environment:
```shell
make init
```

Build and install snap:
```shell
make build
make install
```
