# Upstart Config for Xvfb

## Installation

Install the `xvfb` package first:
```bash
sudo apt-get install xvfb
```

Copy configuration files:
```bash
sudo cp ./default/xvfb /etc/default/
sudo cp ./init/xvfb.conf /etc/init/
sudo ln -s /lib/init/upstart-job /etc/init.d/xvfb
```

### Usage

```bash
service xvfb start
service xvfb status
```
