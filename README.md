# testproject

1. git submodule update --init
2. cp buildrootdotconfig buildroot
3. cd buildroot
4. make BR2_EXTERNAL=../external_packages/ menuconfig 
5. make -j8
