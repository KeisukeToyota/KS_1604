#Flower Talk


[開発用レポジトリ](https://github.com/calmery/ks_1604/ "https://github.com/calmery/ks_1604")

## 製品概要
アプリで写真をとることで,撮影された画像が花であるかを判断し,花の種類に応じて独自に性格を与える.その性格をもとに花とチャット形式で会話することができ,素敵な花の魅力を気づかせてくれるだろう.

### Plant Tech

### 背景（製品開発のきっかけ,課題等）
当初は植物の健康管理を遠隔で行うこと目的としていたが，諸事情により開発に必要な機材を調達できなかった． 近年、ARを用いたスマートフォン向けアプリが注目されている．これは、スマートフォンに内蔵されているカメラの映像にコンピュータグラフィックス(以下CG)を重ね合わせることで、実世界にCGが存在しているような仮想現実を体感する製品である．しかしながら、従来のAR製品は人間側から仮想空間へ一方的なアクションを取ることしか出来ず、プレイヤーが直ぐに飽きてしまうケースが多く確認されている．本開発では植物の健康管理も重要な要素のひとつではあるがARに対して新たに、仮想現実へのコミュニケーション要素を追加することで，従来よりもプレイヤーに長く楽しんで貰えるのではないかと考えられる．

### 製品説明（具体的な製品の説明）
自分の身近な植物，主に花を撮影し，Microsoft Computer Visionによってそこに写っている対象物を判別する．それらが花と認識されれば利用者はUserLocalの全自動会話APIを使った擬似的なコミュニケーションを楽しむことができる．またSkyWayのPeerJS APIを利用し他のデバイスと連携させることでその植物，花の状態を監視することができる．

### 特長
#####1. 植物の写真を撮るだけで,その植物の性格を独自に判断して会話ができる．
#####2. ゲーム感覚で花と触れ合って楽しむことができる．
#####3. 屋外からでも自分の可愛らしい植物を眺め,寂しさを紛らわせることができる．

### 解決出来ること
#####植物と接する機会を増やすことで、アプリ利用者の植物に対する関心が向上することが期待できる．

### 今後の展望
#####外部のデバイス(Raspberry Piなど)を利用して,家の外にいても遠隔で簡単に植物の健康管理できるようにしたい.
#####また,他人と互いの植物同士を戦わせる機能や様々な種類の植物コレクションといったゲーム性の向上を計りたい.

### 注力したこと（こだわり等）
* 写真によって花の性格が変わる

## 開発技術
### 活用した外部技術
* 特になし

#### API・データ
* Microsoft Computer Vision API
* UserLocal 全自動会話 API
* UserLocal キャラクター会話 API
* LINE Messaging API
* SkyWay PeerJS API

#### フレームワーク・ライブラリ・モジュール
* Flask 0.11.1
* Express 4.14.0
* Electron 1.4.4
* Socket.io 1.5.1

#### デバイス
* スマートフォン（iOS，Android）
* PC（Windows，OS X，and more...）
* Raspberry Pi（Raspbian）

### 独自技術
#### 期間中に開発した独自機能・技術
* 特になし

#### 研究内容（任意）
* 特になし
