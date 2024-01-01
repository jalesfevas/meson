# meson
Register [here](https://dashboard.meson.network/register)

Update system
```bash
sudo apt update && sudo apt upgrade -y
```

Download and Install
```bash
wget 'https://staticassets.meson.network/public/meson_cdn/v3.1.20/meson_cdn-linux-amd64.tar.gz' && tar -zxf meson_cdn-linux-amd64.tar.gz && rm -f meson_cdn-linux-amd64.tar.gz && cd ./meson_cdn-linux-amd64 && sudo ./service install meson_cdn
```

Set Token and Config
```bash
sudo ./meson_cdn config set --token=YOUR_TOKEN --https_port=443 --cache.size=30
```

Start Meson Service
```bash
sudo ./service start meson_cdn
```
