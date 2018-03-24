# Testproject abc

1. git submodule update --init
2. cp buildrootdotconfig buildroot
3. cd buildroot
4. make BR2_EXTERNAL=../external_packages/ menuconfig 
5. Select all external packages  and save
6. make linux-clean
7. make -j8

