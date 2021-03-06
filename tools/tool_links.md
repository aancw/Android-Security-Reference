#Pen Testing Frameworks / Collections

- [ajinabraham/Mobile-Security-Framework-MobSF](https://github.com/ajinabraham/Mobile-Security-Framework-MobSF)
- [QARK](https://github.com/linkedin/qark)
  - Nice apk static analysis tool for Android
  - No way to supress certain warnings / errors so probably would not want to run as part of CI build
- [Drozer](https://labs.mwrinfosecurity.com/tools/drozer/)
  - drozer is a comprehensive security audit and attack framework for Android
  - Needs to execute on a device the apk is installed on
- NowSecure
  - [Lab Suite](https://www.nowsecure.com/lab/) _Commercial_
- [MonkOp](http://www.monkop.com/index.html)
  - Upload apk to remote 

#Device Vuln Testing

- [X-Ray](https://labs.duo.com/xray/)
  - Attempts exploits on device 
- [NowSecure Android VTS](https://github.com/AndroidVTS/android-vts)

#OS Bundles

- [Kali Linux](https://www.kali.org/)
  - Kali Linux is a Debian-based Linux distribution aimed at advanced Penetration Testing and Security Auditing. Kali contains several hundred tools aimed at various information security tasks, such as  Penetration Testing, Forensics and Reverse Engineering. 
- [Santoku](https://santoku-linux.com/)

#Network traffic

- [Nogotofail](https://github.com/google/nogotofail) 
  - Nogotofail is a network security testing tool designed to help developers and security researchers spot and fix weak TLS/SSL connections and sensitive cleartext traffic on devices and applications in a flexible, scalable, powerful way. 

#MemDump

- [Introduction to Fridump](http://pentestcorner.com/introduction-to-fridump/)

#File System Analysis

_Below are taken from [FileSystem Monitor Tool For iOS and Android](https://www.nowsecure.com/blog/2016/02/18/filesystem-monitor-tool-for-ios-and-android/?mkt_tok=3RkMMJWWfF9wsRokv6%2FIZKXonjHpfsX56uovWaCylMI%2F0ER3fOvrPUfGjI4DTsBnI%2BSLDwEYGJlv6SgFSLDEMbhlzbgFXBI%3D)_

- `inotify` - In Linux, and therefore Android, the inotify syscall provides access to receive the filesystem events happening on a specific file or directory. 
- `fanotify` - Improved `inotify` added in Android 5.0
- [fsmon] (https://github.com/nowsecure/fsmon)
- [Linux debugging tools I love](http://jvns.ca/blog/2016/07/03/debugging-tools-i-love/)
