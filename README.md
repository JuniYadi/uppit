## uppit.sh
### bash script for downloading uppit files

##### Download single file from uppit

```bash
./uppit.sh url
```

##### Batch-download files from URL list (url-list.txt must contain one uppit.com url per line)

```bash
./uppit.sh url-list.txt
```

##### Example:

```bash
./uppit.sh http://uppit.mobi/9hSdaL6EXli
```

uppit.sh uses `wget` with the `-C` flag, which skips over completed files and attempts to resume partially downloaded files.

### Requirements: `coreutils`, `grep`, `sed`, **`wget`**
