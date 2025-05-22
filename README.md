# CREDO
installation steps of CREDO container
## to install credo first we need some prerequisites
```bash
sudo apt update
sudo apt install -y docker.io git python3 python3-pip
sudo systemctl start docker
sudo systemctl enable docker
```
## verify docker installation
```bash
docker --version
```
## clone the CREDO GUI repo and enter into CREDOgui directory
```bash
git clone https://github.com/alessandriLuca/CREDOgui.git
cd CREDOgui
```
