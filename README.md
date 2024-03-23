# Paranoid Android #

# This is fork of Paranoid Android for out own Realme GT Master Edition aka 'lunaa' #

### Initializing Repo ###

```bash

repo init -u https://github.com/pa-lunaa/manifest -b uvite-f

```
### Sync ###

```bash

repo sync -c --force-sync --optimized-fetch --no-tags --prune -j$(nproc --all)

```

## Building ##

The bundled builder tool `./rom-build.sh` handles all the building steps for the specified device
automatically. As the device value, you just feed it with the device codename (for example,
'beryllium' for the Pocophone F1).

```bash
# Go to the root of the source tree...
$ cd WORKSPACE
# ...and run the builder tool.
$ ./rom-build.sh DEVICE
```

