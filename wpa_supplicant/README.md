## 编译正常的 eapol_test

``` bash
make clean
make test=1

ls -al /app/third_party/wpa_supplicant-2.10/wpa_supplicant/eapol_test

ap /app/third_party/wpa_supplicant-2.10/wpa_supplicant/eapol_test /app/tools/simulator/bin/
```


## .config

``` bash
cp defconfig .config
```
