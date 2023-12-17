# modpack

## Installation

### Prism Launcher/MultiMC
1. Download [packwiz-installer-bootstrap.jar](https://github.com/packwiz/packwiz-installer-bootstrap/releases) and move it to the instance's directory.

2. Go to `Edit Instance -> Settings -> Custom commands`, then check the Custom Commands box and paste the following command into the pre-launch command field:
```sh
    "$INST_JAVA" -jar packwiz-installer-bootstrap.jar https://raw.githubusercontent.com/njeromin/modpack/main/pack.toml
```
