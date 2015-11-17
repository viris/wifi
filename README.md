# wifi

##Apply patch

1. download aircrack-ng source (aircrack-ng-1.2-rc2.tar.gz) 
2. download aircrack-ng-json.patch from https://github.com/viris/wifi 
2. tar -xvzf aircrack-ng-1.2-rc2.tar.gz 
3. cd aircrack-ng-1.2-rc2 
3. cp ../aircrack-ng-json.patch . 
4. patch -p1 < aircrack-ng-json.patch 
5. build aircrack-ng (make should work) 

