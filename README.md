# 顏文字

配方： ℞ **kaomoji**

![Screenshot](https://github.com/Freed-Wu/rime-kaomoji/assets/32936898/9bd64ee4-5aa6-480c-bbe1-02d2de77619e)

[Rime](https://rime.im) 顏文字

本方案使用八股文及默認方案所用字型，**默認方案的簡繁轉換可正常使用**。

如與其它 OpenCC 轉換並用，建議將本條`simplifier`置於`filters`首位（`kaomoji_suggestion.yaml`已如此設計）。

如使用自定詞典，且詞典內所用字型與八股文不同者，請自行調整本方案轉換表用字。

## 自動安裝

[東風破](https://github.com/rime/plum) 安裝口令： `bash rime-install kaomoji`

在輸入方案中添加候選繪文字，以朙月拼音（`luna_pinyin`）爲例，代入配方參數：

`bash rime-install kaomoji:customize:schema=luna_pinyin`

## 自助安裝

1. 下載`opencc`檔案夾內容，將完整檔案夾放入Rime用戶檔案夾內

2. 將`kaomoji_suggestion.yaml`內的內容加入至想添加Kaomoji的方案custom檔中

授權條款：見 [LICENSE](LICENSE)
