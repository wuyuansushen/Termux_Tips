# Termux_Android_Transfer
A basic Tip of transferring files between Termux and Android

__Open pipe__:
```
termux-setup-storage
```
Then,You will get a directory named __'storage'__

__Close pipe__:
```
rm -r storage
```
Calm down~This operation is safe because __'storage'__ directory is a __symbol-linked__ directory.
