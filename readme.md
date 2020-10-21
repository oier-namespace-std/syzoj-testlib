# SYZOJ-Testlib

基于 `SYZOJ` 的 `testlib` 模块。

使用方法：将 `SYZOJ` 沙箱内 `/rootfs/usr/include/testlib.h` 文件替换为此文件即可。

由于 `SYZOJ` 奇怪的编译缓存机制，替换后引用了原有 `testlib` 的错误 `spj` 可能需要进行修改之后重新上传编译。

由于 `testlib` 文件较大，第一次提交的时候可能会编译超时，显示 `no testdata` 。遇到这种情况请重测几次，即可正常评测。

`testlib` 依赖 `c++11` 特性，编译时请不要使用 `cpp(cpp03)` 作为 `spj_LANG` 。
