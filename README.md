# 西条でバイオインフォマティクスの勉強をしてきました.その内容を記録します.

## 0日目

### 21時　西条イン.おすすめされたルートイン西条駅前に宿泊。大浴場で移動の疲れを癒す.

## 1日目

### 10時　坊農研に到着.ラボの説明を受ける.バイオDXに関する本を頂きました.面白そう.

まずはWiFiに接続し、WSL2とdockerの設定を行う.

### 12時　近くのスーパーで昼ご飯を購入.物価が安すぎて腰抜けそう.惣菜パンのコスパがよすぎる件.

昼ご飯を済ませたのち、ikraの動作確認を行う.dockerを使用することで非常に簡単にテストを行うことができた.3150.

https://github.com/yyoshiaki/ikra


ikraの動作を確認後、先日のハンズオンの内容の復習も行った。  

https://github.com/yyoshiaki/2022_shinkei_handson  

こちらはikraの中身を1ステップずつ手動で試してみようという感じ.
  
dockerを使用せずlocalのconda仮想環境を作成するが、バージョン指定をしないと案の定conflict.やはり大人しくdockerを使用したほうが無難か. 

RNAseq自体は2年前に行ったことがあったが、その時はHisat2を使用していた.salmonはやはり早い.俺でなきゃ見逃しちゃうね.

ここで1日目は終了.ホテルは広島テクノプラザ.

### 1日目のメモ

・byobu：超有能な影武者.localではあまりお世話にならないかもしれないが、リモートサーバーとの接続では重宝しそう.screen,tmuxの系譜か.

・遺伝子定量の分類  
 遺伝子定量時に、リファレンスゲノムにマッピングするものとしてTophat,Hisat2,starなどが、マッピングフリーなものとしてkallisto,salmonがある。後者の方が圧倒的に早い.
 曰く、多くの研究では後者で十分であるが、研究内容によっては前者がバリバリ使用されるとのこと.

・ゲノム編集系のツールについて  
 こちらはゲノム編集イノベーションセンターの中前さんから伺ったお話.

 https://qiita.com/KazukiNakamae/items/fa1c58351c1a8ce4c937

 attention-baseのneural networkがこの分野でも使用されていることに驚き.  
 ツールを見ればわかるが、アメリカ(MIT,ハーバード)強すぎ.
 日本では定量については盛んだが、ゲノム配列を直接いじる系についてはアメリカなどに劣っているらしい.
 確かに自分もそうかも.

・白牡丹(ハクボタン)
  西条は日本酒が有名であり、別名「酒都」とも呼ばれている.その中の「白牡丹」を頂きました.
  常温で.

  うまーーーー. 

  うまーーーーーー.

  飲みやすい.甘口すぎず辛口すぎず.後味にもキレを感じる.  
  至高の領域.ごちそうさまでした.