# 第三週RWD響應式+第四週使用gulp

[網頁](https://wanchii.github.io/layout-gulp-w3-w4/dist/index.html)



### 網頁使用工具
SCSS、gulp、jQuery

### 網頁使用技巧

響應式多頁板型，斷點主要有  
-PC版1200px  
-平板992px  
-手機767px&375px  

首頁index-  
jq 漢堡選單  
jq top & down 效果  
聯名版型效果  

常見問題FAQ-  
jq選單開關

系列鏡框classic-  
內部分頁效果

#### SCSS結構
@import '_reset.scss'; meyerweb css reset  
@import '_variables.scss'; 放置變數和 @mixin  

@import '_base.scss'; 放全站設定  
@import '_layout.scss'; header和footer設定  
/*各頁*/  
@import '_index.scss'; 首頁css   
@import '_faq.scss'; FAQ頁面    
@import '_classic.scss'; 系列鏡框   


------

#### 作業修改建議


1) header 選單的 a 標籤可以藉由 padding 來增加點擊範圍（取代 margin）  
> 原本mr-64px  修改成pl32px pr32px

2) 在平板樣式時，.classic-group > li mb 應該是 8px  
> 跟多頁的鏡框系列class的classic-group 權重重疊

3) input 可以更換背景顏色為透明色 transparent，目前看顏色好像不太一樣  
> 加了 bg:transparent;-OK

4) scss 的部分會盡量避免直接使用標籤，可以開始習慣都寫 class 名稱  
> 回聽了卡斯柏老師5/6的補充影片，發現老師也有提到這段，下次會注意

5) 如果 reset.scss 內沒有使用 variables.scss 內的變數的話，會建議放在最前面  
> OK
