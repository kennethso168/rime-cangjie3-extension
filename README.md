# rime-cangjie3-extension (RIME倉頡三代延伸碼表)

## 介紹
[RIME (中州韻輸入法引擎)](http://rime.im/) 是Windows、Mac OS X以及Linux上強大的輸入法引擎。但是它預設只提供倉頡五代。慣用三代的您因此卻步？不用怕，RIME是很容易作出延伸的，加上其實三代和五代之間只有近三百個字異碼，何不把三代的編碼加進去？

## 使用方法

* 下載 zip 並解壓 (或 git clone)
* 把`cangjie5.cj3ext.dict.yaml`和`cangjie5.custom.yaml`丢進[用戶資料夾](https://github.com/rime/home/wiki/RimeWithSchemata#user-content-rime-%E4%B8%AD%E7%9A%84%E6%95%B8%E6%93%9A%E6%96%87%E4%BB%B6%E5%88%86%E4%BD%88%E5%8F%8A%E4%BD%9C%E7%94%A8)中
```
用戶資料夾
【中州韻】 ~/.config/ibus/rime/ （0.9.1 以下版本爲 ~/.ibus/rime/)
【小狼毫】 "%APPDATA%\Rime"
【鼠鬚管】 ~/Library/Rime/
```
* 重新部署

註：如果您已經創建了一個cangjie5.custom.yaml來定製倉頡的話，那麼請您動動腦筋，自行把相關改變加進去

## 輸入說明

完成後，您將可同時以三代和五代編碼輸入。例如`人竹尸`和`人人尸`亦可得出「作」。

倉頡三代和五代的分別可參考 https://zh.wikibooks.org/zh-hk/%E5%80%89%E9%A0%A1%E8%BC%B8%E5%85%A5%E6%B3%95/%E4%B8%89%E4%BB%A3%E8%88%87%E4%BA%94%E4%BB%A3%E7%B7%A8%E7%A2%BC%E5%B7%AE%E7%95%B0

建議還使用三代的您，也試試學五代吧，差異的地方不多，但編碼更有規律。

## 頁獻

編碼是電腦自動生成的，而且只經過少量的人手校對。有問題的話，歡迎提出issue或pull request，謝謝！
本編碼只於linux系統上測試過，如在小狼毫或鼠鬚管有任何問題歡迎提出。
