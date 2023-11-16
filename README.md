## 発表資料
https://docs.google.com/presentation/d/1xc4OOYl5_j52Ds2IyAdxx9bw5zB2ctCVluO3sbh3U4s/edit#slide=id.p

## ブランチ

1~3は恒常、4は必要に応じて
1. main
1. develop
1. front-develop, back-develop
1. 各機能ブランチ
- front/(目的)/(任意の名前)
- back/(目的)/(任意の名前)

目的例  
- feature, 機能開発  
- fix, バグ修正
- refactor, リファクタリング

Ex. back/feature/login-button  

(機能をスラッシュで区切らない)  
NG例  
back/feature/login/Button  
back/feature/login  

OK例
back/feature/login-Button  
back/feature/login  

###　進め方
各機能ブランチに機能を実装し push する    
各機能ブランチにまとまった実装ができれば、front-develop, back-develop にプルリクエスト  
front-develop, back-develop にまとまった実装ができれば、develop にプルリクエスト  

※ PR する時は、slack などで共有する->GitHub の push や PR などの通知が Slack に流れるようにしてもいいかも

## Issue

(必須)front か back かの Label をつける   
(任意)作業目的のLabelをつける  
