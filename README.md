# luci-theme-neobird
## 针对移动端优化的Openwrt主题 
修改默认小飞机为passwall
## 自行编译：
cd lede/package/lean  
rm -rf luci-theme-neobird  
git clone https://github.com/msycnthinktip/luci-theme-neobird-passwall.git  
cd ~/lede/
make menuconfig #choose LUCI->Theme->Luci-theme-neobird  
make -j1 V=s
