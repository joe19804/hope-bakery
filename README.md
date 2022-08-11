首頁

-title
-header
-body
    .header
container(最新消息、關於我們、商品介紹、購物須知、聯絡我們)
-footer


最新消息

關於我們

商品介紹

購物須知

聯絡我們

- 參考網頁
https://shop2us.com/?template-preview=72&open=1

- icon
https://fontawesome.com/icons/star?s=solid

- google font

https://fonts.google.com/specimen/Lora?query=lora

- MDN

https://developer.mozilla.org/zh-TW/docs/Web/CSS/border

- 轉jpg檔案

https://www.aconvert.com/tw/image/avif-to-jpg/


--  圖片參考檔

https://unsplash.com/photos/GFhqNX1gE9E?utm_source=email&utm_medium=referral&utm_content=creditShareLink


## git操作

本地資料夾初始化git
```
git init .
```

將repository複製一份到本機
```
git clone https://github.com/joe19804/hope-bakery.git
```

在github開了一個新的repository後, 希望連接到本機指定的資料夾
```
git init .
git remote add origin https://github.com/joe19804/hope-bakery.git
git branch -M main
git push -u origin main
```

刪除本機「綁定帳號」
```
git credential-manager uninstall
```

把資料從本地上傳到github repository
```
git add .
git commit -m "更新內容說明"
git push
```