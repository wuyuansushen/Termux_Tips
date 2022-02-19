# Termux_Tips

## File Transfer
A basic Tip of transferring files between Termux and Android

**Open pipe**
```
termux-setup-storage
```
Then,You will get a directory named `storage`

**Close pipe**
```
rm -r storage
```
Calm down~This operation is safe because __'storage'__ directory is a __symbol-linked__ directory.

## Change repo

```
termux-change-repo
```