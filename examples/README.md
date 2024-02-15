# Example init files

Those files are the *rc files deployed on the aosp_arm-trunk_staging-eng target
from Android 14 Open Source Platform.

Synced using the command:
```bash
rsync -am --include='*.*rc' --include='*/' --exclude='*' \
    $ANDROID_BUILD_TOP/out/target/product/generic/ ./examples/
```
