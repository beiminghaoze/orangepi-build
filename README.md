## Supported boards

Soc | Boards |
|:--|:--|
| Allwinner H6 | Orange Pi 3/3 LTS |
| Allwinner H616 | Orange Pi Zero2/Zero2w/Zero3 | 
| Allwinner T527 | Orange Pi 4A |
| Allwinner A733 | Orange Pi 4Pro | 
| Rockchip RK3399 | Orange Pi 4/4B/4 LTS/800 |
| Rockchip RK3566 | Orange Pi 3B/CM4 |
| Rockchip RK3588S | Orange Pi 5/5B/5Pro/CM5/CM5-tablet |
| Rockchip RK3588 | Orange Pi 5Plus/5MAX/5Ultra |
| Cix P1 | Orange Pi 6Plus |
| Starfive  JH7110 | Orange Pi RV |
| Ky X1 | Orange Pi RV2/R2S |

## Download links

- 中文链接：     http://www.orangepi.cn
- English link：http://www.orangepi.org

## Supported Host Systems
- Ubuntu 22.04

## Compile
1.安装依赖
```bash
sudo apt update && sudo apt install -y \
  git build-essential bc bison flex libssl-dev libelf-dev \
  device-tree-compiler u-boot-tools kpartx dosfstools parted \
  pigz pv rsync unzip wget curl ca-certificates jq python3 \
  debootstrap qemu-user-static binfmt-support
```
2.执行 ./build.sh 并选择（orangepizero3、Full OS image for flashing、默认内核配置、next、resolute、精简控制台镜像、Standard版本）