# JetBot

- This project is folked from https://github.com/NVIDIA-AI-IOT/jetbot

## 更新履歴
- [Collision Avoidance and Road Following](https://github.com/igakilab/jetbot/tree/master/notebooks/ca_rf) を作成した．
  - road followingに従って道路を走行し，正面に障害物があると左折する
  - 使い方．ca_rfフォルダに有る`live_demo.ipynb`を上から順番に実行する．その際，Collision AvoidanceのモデルとRoad Followingのモデルを同じディレクトリに置いておくこと(\*.pthファイル)．
- [Collision Avoidance](https://github.com/NVIDIA-AI-IOT/jetbot/tree/master/notebooks/collision_avoidance)にオージス総研のリポジトリで公開されてるdata_collection.ipynbを追加した
  - オージス総研リポジトリ
    - https://github.com/ogis-yamagishi/jetbot/blob/relearn/notebooks/collision_avoidance/data_collection.ipynb
- [road_following](https://github.com/igakilab/jetbot/tree/master/notebooks/road_following) のdata_collection.ipynbをゲームパッドを利用せずに，画面のSaveボタンをクリックして画像を記録するように変更した

## これまでの知見
- 有線環境（電源及びLAN）を必ず用意し，学習時は有線環境で実施すること
  - 無線はデモ走行のみ
- メモリ消費量は常に確認する．80%を定常的に超えるようなら一度再起動すると良い
- モードは特に理由がなければ20Wモードにしておいて良い

## デモ動画
### Collision Avoidance
- ソースコード：https://github.com/igakilab/jetbot/tree/master/notebooks/collision_avoidance
- https://www.instagram.com/p/By82NuzjE4q/?utm_source=ig_web_copy_link

### Road Following
- ソースコード：https://github.com/igakilab/jetbot/tree/master/notebooks/road_following
- https://www.instagram.com/p/B2MKAWojsw1/?utm_source=ig_web_copy_link
- https://www.instagram.com/p/B2ME6DgDQLC/?utm_source=ig_web_copy_link
