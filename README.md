# refs/tags/android-7.1.2_r36

## Apply all patches

- Copy needed ASB folder to your local Android source
- Apply all changes

```
repo forall -c "git am *.asb.patch"
```

- Now delete all local patchfiles again

```
repo forall -c "rm -rf *.asb.patch"
```

- Add the next ASB folder and start from beginning

## Rename all patch files

```
find . -name "*.patch" -exec rename 's/.patch$/.asb.patch/' {} \;
```

### 2018

- https://review.lineageos.org/#/q/topic:n_asb_01-2018+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n_asb_02-2018+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n_asb_03-2018+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n_asb_04-2018+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n_asb_05-2018+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n_asb_06-2018+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n_asb_07-2018+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n_asb_08-2018+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n_asb_09-2018+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n_asb_10-2018+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n_asb_11-2018+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n_asb_12-2018+(status:open+OR+status:merged)

### 2019

- https://review.lineageos.org/#/q/topic:n-asb-2019-1+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n-asb-2019-2+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:asb-2019.03-cm14+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n-asb-2019-04+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n-asb-2019-05+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n-asb-2019-06+(status:open OR status:merged)
- https://review.lineageos.org/#/q/topic:n-asb-2019-07+(status:open OR status:merged)
- https://review.lineageos.org/#/q/topic:n-asb-2019-08+(status:open OR status:merged)
- https://review.lineageos.org/#/q/topic:N_asb_2019-09+(status:open OR status:merged)
- https://review.lineageos.org/#/q/topic:n-asb-2019-10+(status:open OR status:merged)
- https://review.lineageos.org/#/q/topic:n-asb-2019-11+(status:open OR status:merged)
- https://review.lineageos.org/#/q/topic:n-asb-2019-12+(status:open OR status:merged)

### 2020

- https://review.lineageos.org/#/q/topic:N_asb_2020-01+(status:open OR status:merged)
- https://review.lineageos.org/#/q/topic:N_asb_2020-02+(status:open OR status:merged)
- https://review.lineageos.org/#/q/topic:N_asb_2020-03+(status:open OR status:merged)
- https://review.lineageos.org/#/q/topic:N_asb_2020-04+(status:open OR status:merged)
- https://review.lineageos.org/#/q/topic:N_asb_2020-05+(status:open OR status:merged)
- https://review.lineageos.org/#/q/topic:N_asb_2020-06+(status:open OR status:merged)
