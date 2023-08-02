# Chicago bike sharing for temporal network
## About
修論で使うデータセットの選定。
railwayのデータだと、結局路線図の通りのネットワークでしかなく、weightedにする手法も浮かばなかったので、bike sharingのデータを使う。 
## Description
bike sharingのデータだと、Londonのものが有名。
諸外国での、bikeを使用した人の移動に地域差じみたものがあるのかどうかを検証する。

## Method
`start_station_id`と`end_station_id`をノードとする。station間をバイクで移動したらエッジを結ぶ。
## TODO
- [ ] 基本的なプロパティを見る
- [ ] 並び替えてスナップショットを作成し、時間経過でのノード数/エッジ数を見る
- [ ] GCCを時間経過でプロットする
- [ ] Higher order structureを見る   

## Ref
https://www.perplexity.ai/search/2a0086cd-52f3-4d0f-8742-fefef8b5522a?s=c