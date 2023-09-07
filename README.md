# 繪文字

配方： ℞ **emoji**

[Rime](https://rime.im) 繪文字

本方案使用八股文及默認方案所用字型，**默認方案的簡繁轉換可正常使用**。

如與其它 OpenCC 轉換並用，建議將本條`simplifier`置於`filters`首位（`emoji_suggestion.yaml`已如此設計）。

如使用自定詞典，且詞典內所用字型與八股文不同者，請自行調整本方案轉換表用字。

## 自動安裝

[東風破](https://github.com/rime/plum) 安裝口令： `bash rime-install emoji`

在輸入方案中添加候選繪文字，以朙月拼音（`luna_pinyin`）爲例，代入配方參數：

`bash rime-install emoji:customize:schema=luna_pinyin`

## 自助安裝

1. 下載`opencc`檔案夾內容，將完整檔案夾放入Rime用戶檔案夾內，如圖所示：
![image](https://github.com/jsdryan/rime-emoji/assets/34669056/ac5167a1-8a2a-4082-9470-395e1c32f46a)

2. 將`emoji_suggestion.yaml`內的內容加入至想添加Emoji的方案custom檔中，如圖所示（以下範例為 `luna_pinyin_tw.custom.yaml` 檔案：
![image](https://github.com/jsdryan/rime-emoji/assets/34669056/487059e7-de2b-45f1-b85c-19c52a880009)

授權條款：見 [LICENSE](LICENSE)
