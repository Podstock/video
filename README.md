# video


## Equipment
- 3x SONY Alpha ZV-E10
- radxa ROCK 4C Plus


### SONY Alpha ZV-E10

#### Settings

Menu -> Cam2 (Page):
- (1) File Format -> `XAVC S 4K`
- (1) Record Setting -> `25p 60M`
- (2) Proxy Recording -> `Off`
- (3) SteadyShot -> `Standard`
- (6) Zoom Range -> `ClearImage Zoom`


### radxa ROCK 4C Plus
#### Image
https://github.com/radxa-build/rock-4c-plus/releases/download/20230312-1521/rock-4c-plus_debian_bullseye_cli_b55.img.xz

#### mpp

```bash
git clone https://github.com/rockchip-linux/mpp.git
cd mpp && cmake -B build && cmake --build build -j && cmake --install build
```
#### ffmpeg-rk

```bash
apt-get build-dep ffmpeg
git clone https://github.com/sreimers/ffmpeg-rk.git
```
