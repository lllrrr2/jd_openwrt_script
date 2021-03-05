# jd_openwrt_script
适用于openwrt安装jd脚本的插件,本插件不带luci界面！！！ 不带luci界面！！！ 不带luci界面！！！

## 编译
cd 到你的源码

        git clone  https://github.com/ITdesk01/jd_openwrt_script.git package/jd_openwrt_script
        ./scripts/feeds update && ./scripts/feeds install
        make menuconfig
        
选上插件

        Extra packages  --->
             <*> jd_openwrt_script
             
        
开始编译

        make V=99
