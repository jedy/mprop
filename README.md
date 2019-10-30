# mprop
修改android系统属性。网上找到的，原始出处不明。如果是作者，可以和我联系加上说明。

# 用法
```bash
adb push mprop /data/local/tmp/
adb shell "chmod 755 /data/local/tmp/mprop"

# inject & hack
adb shell "/data/local/tmp/mprop"

# verbose mode ==> dump memory 
# adb shell "/data/local/tmp/mprop -v" > myprop.txt

# restore
# adb shell "/data/local/tmp/mprop -r"

# change ro.xx property
adb shell "setprop ro.debuggable 1"
```
