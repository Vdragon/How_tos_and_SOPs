# 如何安裝 Mozilla Firefox 擴充功能到 GNU/Linux 作業系統全域<br />How-to Install Mozilla Firefox Extension to System-wide on GNU/Linux Operating System
這個標準操作程序將告訴您如何安裝 Firefox 擴充功能到全系統的使用者上。

## 步驟<br />Step by step
1. 取得擴充功能的 xpi 檔案（以 LastPass 密碼同步軟體的話是 `https://lastpass.com/lp_linux.xpi`）
1. 以 root 身份將擴充功能 xpi 檔案安裝到 `/usr/share/mozilla/extensions\{ec8030f7-c20a-464f-9b0e-13a3a9e97384\}` 目錄下
1. 重新啟動 Mozilla Firefox

## 已知問題<br />Known issues
* `/usr/local/share/mozilla/extensions\{ec8030f7-c20a-464f-9b0e-13a3a9e97384\}` 理論上要支援而未支援，應為 Mozilla Firefox 的軟體缺陷

## 參考資料<br />Reference Data
* [Cannot remove an add-on (extension or theme) | Firefox Help](https://support.mozilla.org/en-US/kb/cannot-remove-add-on-extension-or-theme#w_globally-installed-extensions)
* 「xul-ext-ubufox」軟體包  
  `/var/lib/dpkg/info/xul-ext-ubufox.*`
* [LastPass Universal Linux Installer](https://lastpass.com/lplinux.php) - install_lastpass.sh
