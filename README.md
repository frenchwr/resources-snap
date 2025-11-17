# Resources

Snap packaging definition for the [Resources monitoring tool](https://github.com/nokyan/resources) for Linux, including support for GPU and NPU utlization across different vendor hardware.

## Installation from the Snap Store

```bash
sudo snap install resources
```

## Connecting snapd interfaces

Eventually I aim to auto-connect these (pending approval from the Snap Store team), but now they need to be manually connected in order to access host resources needed to support various features of the app.

```bash
sudo snap connect resources:desktop-launch
sudo snap connect resources:process-control
sudo snap connect resources:hardware-observe
sudo snap connect resources:usr-share
```
