# hook函数的参数

Objection去hook安卓或iOS的函数，有些通用的逻辑

其中就包括：

* hook函数的参数
  * `--dump-args`：打印函数**参数值**
  * `--dump-backtrace`：打印函数**调用堆栈**
  * `--dump-return`：打印函数**返回值**

## 举例

* Android
  ```bash
  android hooking watch class_method android.app.ActivityManager.forceStopPackage --dump-args --dump-backtrace --dump-return

  android hooking watch class_method com.android.server.am.ActivityManagerService.startService --dump-args --dump-backtrace --dump-return

  android hooking watch class_method jd.wjlogin_sdk.common.inland.WJLoginInland.JDLoginWithPasswordNew --dump-args --dump-backtrace --dump-return
  ```
* iOS
  ```bash
  ios hooking watch method "-[iGoat_Swift.BinaryCookiesExerciseVC verifyItemPressed]" --dump-args --dump-backtrace --dump-return
  ```
