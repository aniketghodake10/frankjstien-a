# frankstien-a

git clone https://github.com/mdeejay/device_xiaomi_vince.git -b 8.1.x device/xiaomi/vince

git clone https://github.com/mdeejay/kernel_xiaomi_vince.git -b android-8.1-clang kernel/xiaomi/vince

git clone https://github.com/mdeejay/vendor_xiaomi_vince.git -b android-8.1 vendor/xiaomi



export USE_CCACHE=1


prebuilts/misc/linux-x86/ccache/ccache -M 50G


export CCACHE_COMPRESS=1


cd ~


wget https://docs.google.com/uc?id=0B3X9GlR6EmbnWksyTEtCM0VfaFE&export=download


mv uc\?id\=0B3X9GlR6EmbnWksyTEtCM0VfaFE gdrive


chmod +x gdrive


sudo install gdrive /usr/local/bin/gdrive


gdrive list


cd rom_name


cd out/target/product/vince


ls


gdrive upload zip_name




git clone https://github.com/aniketghodake10/android_device_xiaomi_msm8953-vince.git -b dot-o device/xiaomi/msm8953-common
