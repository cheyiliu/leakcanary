# Leakcanary
* A memory leak detection library for Android and Java. Restructure this origin gradle project to eclipse project on 20150518

# What changed?
* Just place the origin code in one eclipse project
* The code include ```leakcanary-analyzer, leakcanary-watcher, leakcanary-android``` and ```code of https://github.com/square/haha```

# How to use this project?
1. Download and import this project to eclipse, make is as a library project
2. Add this lib as reference to your target project
3. Copy activity service and permission info from lib project to target project
4. Follow the instruction from [https://github.com/square/leakcanary#how-do-i-use-it](https://github.com/square/leakcanary#how-do-i-use-it)
