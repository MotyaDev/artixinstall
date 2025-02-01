# artixinstall
## Usage
```
git clone https://github.com/MotyaDev/artixinstall && cd artixinstall && sudo bash artixinstall.sh
```
(OR)
```
curl -sLO https://raw.githubusercontent.com/MotyaDev/artixinstall/main/artixinstall.sh
sudo bash artixinstall.sh
```
The script will ask you
- root password
- username
- user password
- hostname
- disk to install
- boot partition size
- root partition size
- enable zram or not
- filesystem to use (btrfs or ext4)
- encrypt root partition or not
- init system to use (dinit or openrc or runit or s6)
- enable archlinux repo support or not

Then, the script will do all the necessary things.

## NOTE
> This script is for clean installation only as it will wipe out the chosen disk completely.
