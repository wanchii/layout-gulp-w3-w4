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
@import '_variables.scss'; 放置變數和 @mixin  
@import '_reset.scss'; meyerweb css reset  

@import '_base.scss'; 放全站設定  
@import '_layout.scss'; header和footer設定  
/*各頁*/  
@import '_index.scss'; 首頁css   
@import '_faq.scss'; FAQ頁面    
@import '_classic.scss'; 系列鏡框   
