 # 円周率言えるかな？
## プロダクトの紹介
- 円周率1000桁暗記する学習ツールです
- ローカルストレージに過去の記録が残るので、どこで間違えたのかを確認できます
- みんな1000桁覚えよう！
## 工夫した点、こだわった点
- 連続した文字列を1文字ずつに区切って、それぞれの桁で合ってるかを確認しました
- ローカルストレージを使って過去の記録を残すようにしました
- 文字列の丸暗記に応用できます(枕草子とか平家物語とかww)
- 毎回の回答が違うローカルストレージに記録されるようにしたところ
## 苦戦した点、共有したいハマりポイントなど
- 二重繰り返しの時は(forのなかにfor)は同じ変数を使ってはならない(自明)
- リロードした時に回数カウントができていなかったのを実装(これこそローカルストレージの出番や！)
- 
## 感想
- 前回のじゃんけんのプロダクトの時もそうだったが、実生活で役立つものを作りたい！というマインドではなく、習った内容でどう面白いものを作るか考えてコードを書いた。
- 誰も作ったことないだろうというものを作りたい。誰もしようとしないことをするものなら、誰も作っていないだろうw 
## 追記
- カッコつけてMathJaxで\piを表示させていたが、それのせい？でバグが起きてたみたいなので、ないver.として_debugを置いておきます