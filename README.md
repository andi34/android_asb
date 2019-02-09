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

### 2017

- https://review.lineageos.org/#/q/topic:asb-2017.11+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:asb-2017.12+(status:open+OR+status:merged)

### asb-2017-10-addition

- Contains fixes for KRACK


### 2018

- https://review.lineageos.org/#/q/topic:asb-2018.01+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:asb-2018.02+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:asb-2018.03-cm13+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:asb-2018.04-cm13+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:asb-2018.05-cm13+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:asb-2018.06-cm13+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:asb-2018.07-cm13+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:asb-2018.08-cm13+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:asb-2018.09-cm13+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:asb-2018.10-cm13+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:asb-2018.11-cm13+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:asb-2018.12-cm13+(status:open+OR+status:merged)
