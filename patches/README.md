## Create patch

Commit changes and run:
```
git format-patch --stdout HEAD^ > patches/<patchname>.diff
```

## Apply patch

```
patch -p1 < patches/<patchname>.diff
```

## Revert patch

```
git apply -R patches/<patchname>.diff
```
