# refs/tags/android-6.0.1_r81

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


## Additional notes

### asb-2017-10-addition

- Contains fixes for KRACK
