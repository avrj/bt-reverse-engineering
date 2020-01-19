# bt-reverse-engineering

1. Enable "Enable Bluetooth HCI snoop log" in Developer Settings on Android
2. Run `adb bugreport`
3. `unzip bugreport*.zip`
4. Open `./bugreport-2020-01-19-19-01-37/FS/data/log/bt/btsnoop_hci.log` in WireShark
