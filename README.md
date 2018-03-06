# refs/tags/android-7.1.2_r36

## Apply all patches

- Copy needed ASB folder to your local Android source
- Apply all changes

```
repo forall -c "git am *.patch"
```

- Now delete all local patchfiles again

```
repo forall -c "rm -rf *.patch"
```

- Add the next ASB folder and start from beginning
