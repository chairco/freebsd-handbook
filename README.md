# FreeBSD 操作手冊 (繁體中文)

FreeBSD 文件計劃開始採用 GNU gettext 的方式來執行翻譯，GNU gettext 做為翻譯工具已相當成熟且已有許多可支援線上協同翻譯的平台，這解決了原採用 Docbook 格式無法同步最新的原文翻譯文件以及多人共同翻譯的問題。
但要採用 GNU gettext 的模式必須先將既有採用 Docbook 的文件內容轉移至 PO 檔，否則無法並存，本專案目標解決以下幾個問題：

* 將既有 Docbook 格式轉換為 GNU gettext 的 PO 格式以讓未來可以有更多人可參與翻譯工作
* 同步及匯整舊有翻譯至最新的原文翻譯版本以跟上目前的文件版本
* 統整文件內目錄標題以及相關名詞

# 官方文件
https://www.freebsd.org/doc/en_US.ISO8859-1/books/fdp-primer/po-translations.html

# PO 檔編輯器

##### Windows, Mac OS X
https://poedit.net/
##### Ubuntu
```
apt-get install poedit
```
##### FreeBSD
```
pkg install poedit
```

# 翻譯名詞對照表
| 原文  | 譯文 |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

# PO 線上協同翻譯平台
* https://hosted.weblate.org/
* https://translatewiki.net/
* https://www.transifex.com/
