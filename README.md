# mprop
修改android系统属性。
转自 https://bbs.pediy.com/thread-215311.htm

# 用法
```bash
adb push mprop /data/local/tmp/
adb shell
```
```bash
# in adb shell
chmod +x /data/local/tmp/mprop
su
# inject & hack
/data/local/tmp/mprop

# verbose mode ==> dump memory 
# /data/local/tmp/mprop -v > myprop.txt

# restore
# /data/local/tmp/mprop -r

# change ro.xx property
setprop ro.debuggable 1
```
