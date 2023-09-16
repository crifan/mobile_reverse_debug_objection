# android hooking watch class_method

Objection去hook列出单个函数`class_method`：

* 语法
  ```bash
  android hooking watch class_method {AndroidClassFunction} [optionalParameters]
  ```
* 举例
  * 只加函数名
    ```bash
    android hooking watch class_method android.app.ActivityManager.forceStopPackage
    ```
  * 加上额外参数
    ```bash
    android hooking watch class_method android.app.ActivityManager.forceStopPackage --dump-args --dump-backtrace --dump-return

    android hooking watch class_method jd.wjlogin_sdk.common.inland.WJLoginInland.JDLoginWithPasswordNew --dump-args --dump-backtrace --dump-return
    ```
