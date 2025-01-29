# AndroidAuto

Open this folder in one terminal
```shell
C:\Users\<User>\AppData\Local\Android\Sdk\platform-tools
```
Run:
```shell
adb forward tcp:5277 tcp:5277
```

This folder in another terminal
```
C:\Users\<User>\AppData\Local\Android\Sdk\extras\google\auto
```

Run:
```shell
./adb devices -l
```

You'll receive something similar to this:
```shell
d9814517               device product:RMX3363 model:RMX3363 device:RE54ABL1 transport_id:1
emulator-5562          offline transport_id:280
```
