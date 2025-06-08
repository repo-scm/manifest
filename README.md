# manifest

manifest test



## Repo

```bash
export REPO_URL='https://mirrors.tuna.tsinghua.edu.cn/git/git-repo'
export AOSP_MANIFEST='https://github.com/repo-scm/manifest'

repo init --partial-clone -b main -u $AOSP_MANIFEST --manifest-depth=1 -c --depth=1 -b android-15.0.0_r17
repo sync -c -j4 --fail-fast
```



## Reference

- [google-aosp](https://gist.github.com/craftslab/72bf50a05d047edff95dc2e13992c8b8)
