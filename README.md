# video


## Equipment
- SONY Alpha ZV-E10
- radxa ROCK 5B


### SONY Alpha ZV-E10

#### Settings

Menu -> Cam2 (Page):
- (1) File Format -> `XAVC S 4K`
- (1) Record Setting -> `25p 60M`
- (2) Proxy Recording -> `Off`
- (3) SteadyShot -> `Standard`
- (6) Zoom Range -> `ClearImage Zoom`


### radxa ROCK 5B
#### Image
https://fi.mirror.armbian.de/archive/rock-5b/archive/Armbian_23.02.2_Rock-5b_jammy_legacy_5.10.110.img.xz

```
add-apt-repository ppa:liujianfeng1994/rockchip-multimedia
apt update
apt dist-upgrade
apt install v4l-utils libv4l-rkmpp rockchip-multimedia-config librga2 librockchip-mpp1 
apt install ffmpeg gstreamer1.0-rockchip1 gstreamer1.0-alsa gstreamer1.0-gl gstreamer1.0-x gstreamer1.0-plugins-good gstreamer1.0-plugins-bad
apt install lm-sensors
apt install lldpd
apt remove unattended-upgrades
```
