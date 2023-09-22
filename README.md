<p align="center">
  <img width="72" height="72" src="https://github.com/ebrahimkarimi/hasera-vpn/blob/main/org.gashbeer.Hasera.png">
</p>

<h1 align="center">Hasera</h1>

Best VPN Client Solution For Linux

### Quick Installation `latest`
#### Ubuntu (tested on 22.04 LTS)
```
wget https://github.com/ebrahimkarimi/hasera-vpn/releases/latest/download/hasera.deb -O hasera.deb && sudo dpkg -i hasera.deb ; sudo apt -f install -y ; sudo rm hasera.deb
```

### Manual Installation
#### Ubuntu
* Download the package from [here](https://github.com/ebrahimkarimi/hasera-vpn/releases)
* Install the dependencies:
`sudo apt install libxcb-cursor0 libpcre2-16-0 -y`
* Install the package:
`sudo dpkg -i hasera.deb`

### Supported Protocols
* SSH
* SSH-TLS
> feel free to request protocols on the pull requests

### Importing configs
* Standard URI (QRCode or Raw)

Standard URIs are using [this](https://regex101.com/r/IZtHlk/1) regex pattern to read connection information
>Note: host validation occurs based on the user dns settings real-time


### Screen Shots

<img width="300" height="300" src="https://github.com/ebrahimkarimi/hasera-vpn/blob/main/home.png">

<img width="300" height="300" src="https://github.com/ebrahimkarimi/hasera-vpn/blob/main/config-list.png">

<img width="300" height="300" src="https://github.com/ebrahimkarimi/hasera-vpn/blob/main/add-config-types.png">

<img width="300" height="300" src="https://github.com/ebrahimkarimi/hasera-vpn/blob/main/ssh-and-sshtls.png">
