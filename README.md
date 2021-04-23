# unraid-user.scripts

User Scripts require the [[PLUGIN] CA USER SCRIPTS](https://forums.unraid.net/topic/48286-plugin-ca-user-scripts/).

## mergerfs_mount

### Install

Install this user script with the following command:

```shell
SCRIPT_NAME=mergerfs_mount && git clone --single-branch --branch "${SCRIPT_NAME}" https://github.com/nemchik/unraid-user.scripts.git /boot/config/plugins/user.scripts/scripts/"${SCRIPT_NAME}"
```

### Update

**WARNING:** This will reset any changes you have made to the script! Settings for using the script should be kept in the `mergerfs_mount.env`

Update this user script with the following command:

```shell
SCRIPT_NAME=mergerfs_mount && git -C /boot/config/plugins/user.scripts/scripts/"${SCRIPT_NAME}" fetch origin "${SCRIPT_NAME}" && git -C /boot/config/plugins/user.scripts/scripts/"${SCRIPT_NAME}" reset --hard origin "${SCRIPT_NAME}"
```
