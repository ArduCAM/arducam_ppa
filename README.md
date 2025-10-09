# Arducam PPA

## Packages

1. arducam-config-parser-dev
2. arducam-usb-sdk-dev
3. arducam-tof-sdk-dev
4. arducam-pivariety-sdk-dev
5. arducam-evk-sdk-beta-dev
6. arducam-evk-sdk-dev
7. arducam-rgbir-remosaic-dev

## Usage

### Debian 13 (trixie) and above versions

```
sudo curl -s --compressed -o /usr/share/keyrings/arducam-keyring.pgp "https://arducam.github.io/arducam_ppa/KEY.gpg"
sudo curl -s --compressed -o /etc/apt/sources.list.d/arducam_list_files.sources "https://arducam.github.io/arducam_ppa/arducam_list_files.sources"
sudo apt update
sudo apt install arducam-config-parser-dev arducam-usb-sdk-dev
```

### Other

```
curl -s --compressed "https://arducam.github.io/arducam_ppa/KEY.gpg" | sudo apt-key add -
sudo curl -s --compressed -o /etc/apt/sources.list.d/arducam_list_files.list "https://arducam.github.io/arducam_ppa/arducam_list_files.list"
sudo apt update
sudo apt install arducam-config-parser-dev arducam-usb-sdk-dev
```