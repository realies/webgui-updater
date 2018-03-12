## Introduction
This tool allows unRAID users to update their webgui to its latest available version or restore it from a backup

## Usage

By default `wgu` creates a backup of the current webgui and updates it to [`limetech/webgui/tree/6.4-wip`](https://github.com/limetech/webgui/tree/6.4-wip)
```
wget https://raw.githubusercontent.com/realies/webgui-updater/master/wgu
chmod +x wgu
wgu
```

Restore webgui from backup
```
wgu restore
```

Backup current webgui
```
wgu backup
```

Update without backing up
```
wgu update
```
