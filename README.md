# 網頁切版直播班 Gulp 範例 - 加入 Bootstrap 版本

> 使用該專案 Gulp 時，就可以不用使用其他編譯工具編譯 SCSS 或是 JavaScript 囉。

## 指令列表

- `gulp` - 執行開發模式(會開啟模擬瀏覽器並監聽相關檔案)
  - 若沒有自動開啟瀏覽器則可手動在瀏覽器上輸入 `http://localhost:8080/` 即可。
  - 假使監聽功能無效的話，可以檢查一下是否修改到資料夾的名稱等。
- `gulp build` - 執行編譯模式(不會開啟瀏覽器)
- `gulp clean` - 清除 dist 資料夾
- `gulp deploy` - 將 dist 資料夾部署至 GitHub Pages
  - 若無法部署到 GitHub Pages 的話，可以確定一下是否已經初始化專案等。

> 請務必確保已經在本機上輸入過 `npm install -g gulp`，否則電腦會不認識 `gulp` 指令哦。



## 學習資源

若對於 Gulp 有一定興趣的話，以下這邊提供學習資源

- [使用 Gulp 進行網頁前端自動化](https://courses.hexschool.com/p/gulp)
- [這是在講 Gulp 不是飲料是任務自動化工具這件事](https://hsiangfeng.github.io/tags/%E9%80%99%E6%98%AF%E5%9C%A8%E8%AC%9B-Gulp-%E4%B8%8D%E6%98%AF%E9%A3%B2%E6%96%99%E6%98%AF%E4%BB%BB%E5%8B%99%E8%87%AA%E5%8B%95%E5%8C%96%E5%B7%A5%E5%85%B7%E9%80%99%E4%BB%B6%E4%BA%8B/page/2/)
- [試著把切版專案升級到 gulp4.0 吧](https://ithelp.ithome.com.tw/users/20104132/ironman/2921)
