# adb

## unistall root app
adb shell
pm uninstall -k --user 0

## show apps running
adb shell "dumpsys activity activities | grep mResumedActivity | cut -d "{" -f2 | cut -d ' ' -f3 | cut -d "/" -f1"
