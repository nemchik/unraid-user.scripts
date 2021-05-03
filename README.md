# unraid-user.scripts

User Scripts require the [[PLUGIN] CA USER SCRIPTS](https://forums.unraid.net/topic/48286-plugin-ca-user-scripts/).

## template

### Install

Install this user script with the following command:

```shell
REPO="https://github.com/nemchik/unraid-user.scripts" && BRANCH="template" && git clone --single-branch --branch "${BRANCH}" "${REPO%/}".git /boot/config/plugins/user.scripts/scripts/"${BRANCH}"
```

### Update

The script may include an update check which will provide specific instructions. As long as you have not modified the files included in the repo you can update with the following command:

```shell
BRANCH="template" && git -C /boot/config/plugins/user.scripts/scripts/"${BRANCH}" pull"
```
