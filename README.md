# 職務経歴書

## 基本情報

|key|value|
|---|-----|
|Name|河田尚孝 (Naotaka KAWATA)|
|Age|25|
|Education|Master of Computer Science and Systems Engineering　<br> Okayama Prefectural University|

## スキル
### 開発言語
- C/C++
- Python

### フレームワーク

- ROS1
- Keras

### その他

- 自然言語処理
- 点群処理
- 画像処理

## 言語

- 日本語
  - ネイティブ
- 英語
  - かんたんな日常会話ができる
  - 国際学会発表経験あり
  - TOEIC: 695点（2017年取得）

## 強み

- 対話などの言語情報を用いたマルチモーダルなシステムを作成することができる
- 画像の準備・前処理～物体認識までの経験がある
- ROSを用いた実機とシミュレータ環境での開発どちらも経験している

## 職務経歴

### 2020/04 - 現在 : NTTテクノクロス株式会社

職務: システムエンジニア

#### 職務内容

- 言語処理ライブラリの開発
  - 日英翻訳、ラベル付与
- 音声音響ライブラリの開発
  - 音声認識、音声区間検出

## 課外活動

### 過去の登壇資料

- [slideshare](https://www.slideshare.net/NaotakaKawata)
- [Mention Detection Method for Entity Linking(BCD2019)](https://dblp.org/db/conf/bcd/bcd2019.html)
- [エンティティリンキングのための言及抽出手法(JSAI2019)](https://confit.atlas.jp/guide/event/jsai2019/subject/1N3-J-9-02/detail?lang=ja)
- [第9回インテリジェントホームロボティクス研究会(招待講演)](https://www.i-homerobotics.org/activity/iHR09)
- [統計的機械翻訳におけるRIBESによる最適化の効果(JSAI2018)](https://confit.atlas.jp/guide/event/jsai2018/subject/1J2-04/date?cryptoId=)


### 受賞歴

- [みんなのラズパイコンテスト2020](https://project.nikkeibp.co.jp/pc/rpic/)
  - [優秀賞](https://project.nikkeibp.co.jp/pc/rpic/)
    - チーム「瀬戸内ROS勉強会」として「ROSを用いたアイロンビーズ並べ、スカラロボット「アイロンビーズセッターR」」を出品
  - 大会の概要
    - RaspberryPiを使った電子工作やアプリケーションのコンテスト。2020年度は107件の応募から、技術及びアイデアを審査し、計39件が受賞した。
  - 担当した役割
    - 主にソフトウェアの開発を担当した。コロナ渦で遠隔地での作業が増えたため、gazeboでのデバッグが行えるよう環境を整備した。また設計段階では、topicごとの機能の粒度を大きすぎず小さすぎ設計することで、複数人での同時開発が円滑に進められるように貢献できた。この経験を通して、1から自作ロボットをROSで開発する経験を積むことができた。
  - [ソースコード](https://github.com/dreamdrive/seto_scararobot)

- [WRS2018パートナーロボットチャレンジバーチャルスペース](https://worldrobotsummit.org/wrc2018/service/partner_virtual.html)
  - [WRS実行委員会賞（3位入賞）](https://worldrobotsummit.org/wrc2018/)
    - チーム「eR@sers(Okayama Prefectural University)」として出場。写真の左から2番目が私。
  - 大会の概要
    - 経済産業省主催のロボットの国際大会。研究機関や大学、企業が参加。バーチャル部門は社会的知能発生学シミュレータであるSIGVrse上で動作するトヨタ社が開発した生活支援ロボットHSRを使用して競技が行われた。競技は対話認識により指定された物体を移動させるタスク（Hundyman）、指差しで指示された物体を指定の場所に運ぶタスク（CleanUp）、ロボットの発話により人間を誘導するタスク（HumanNavigation）の3タスクが実施される。
  - 担当した役割
    - CleanUpタスクとHumanNavigationタスクの開発をメインで行った。
    - CleanUpでは他大学と共同で開発を行っていたので、それぞれの得意分野ごとに設計を行い、画像処理機能、制御機能を実装した。工夫した点は２つあり、指差しから物体の距離を推定し、物体があると推定した位置に移動してから、物体認識を行うことで、指差し同一直線上の別物体を把持する問題を解決した。また、アバターが移動してから指差しを行うため、ロボットが後ろから追従すると体と腕がかぶってうまく物体位置が推定できない問題があったため、追従を行うための経路生成を工夫することで、物体位置推定の精度を向上させることができた。
    - HumanNavigationでは、対話を理解し物体と位置情報を認識するプログラムを実装した。工夫した点として、物体の位置を、右側や左側など人間との相対表現を用いて指示できるように、物体の位置及び人間の位置や向きから相対表現を発話させるシステムを作成し、よりわかりやすく人間を物体まで誘導することを可能にした。結果として、絶対座標で指示するチームよりも高い得点を獲得することができた。
  - [紹介記事および動作](https://qiita.com/Naotaka_Kawata/items/d2e2c94ac6b37afe5936)

- [レスキューロボットコンテスト2016](https://www.rescue-robot-contest.org/contest-2021/)
  - [レスキュー工学大賞（優勝相当の賞）](https://www.rescue-robot-contest.org/forTeam/16th-contest/honsen/prize#content_1_1)
    - チーム「メヒャ！」として出場。写真はリンク切れのためなし。
  - 大会の概要
    - 災害現場を模したフィールドで、自作のレスキューロボットを用いて要救助者を模した人形（ダミヤン）を救助した際のポイントを競う大会。全国の大学、高専が出場している。
  - 担当した役割
    - メインのソフトウェア開発を担当。具体的には、PCから無線でロボットを制御するソフトウェア。工夫した点は、大きい会場で無線通信を行う関係で、遅延が発生する環境下でいかに安定して動作させられるかという課題に対して、通信システムの見直しや送受信するデータの見直し、通信速度の調整などをソフトウェアに反映した。その結果、毎年複数のチームで発生する、遅延が原因で起こる制御不能状態に陥ることなく、その年の最高得点を記録することに貢献した。

### 執筆歴
- [Qiita](https://qiita.com/Naotaka_Kawata)
- [GitHub](https://github.com/NaotakaKawata)
