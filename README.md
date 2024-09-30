# ubuntu24-installers
Ubuntu 24.04 installer scripts to simplify things for the user.
### Modify Ubuntu pro option
#### Disable:
```
sudo pro config set apt_news=false
```
#### Enable (default):
```
sudo pro config set apt_news=true
```

## Instructions
```
mkdir -p ~/src && cd ~/src
```
```
git clone https://github.com/nt74/ubuntu24-installers.git
```
```
cd ubuntu24-installers
```
```
chmod +x install-*
```

It is now possible to run any installer script by running:

./install-*script*.sh
