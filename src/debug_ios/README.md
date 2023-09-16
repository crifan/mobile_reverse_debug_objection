# Objection调试iOS

## ios hooking watch method

* 命令
  ```bash
  ios hooking watch method {iOSFullFunctionName}
  ```
  * 举例
    ```bash
    ios hooking watch method "-[iGoat_Swift.BinaryCookiesExerciseVC verifyItemPressed]" --dump-args --dump-backtrace --dump-return
    ```
