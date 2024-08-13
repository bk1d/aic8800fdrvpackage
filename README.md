Mercury UX3H(免驱版)(一点也不免驱) AX300 Ubuntu24.04 Linux kernel 6.8.0 amd64 驱动
基于 [水星官方驱动](https://service.mercurycom.com.cn/download-2596.html) 修改

### Step 1:
```shell
sudo apt update
sudo apt install build-essential
```

### Step 2:
```shell
dpkg-deb -b src aic8800fdrvpackage_linux_6.8_amd64.deb
```

### Step 3:
```shell
sudo dpkg -i aic8800fdrvpackage_linux_6.8_amd64.deb
```