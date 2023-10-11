# aikeywd
生成AIと学習アプリを連携させる
# 生成AIを使って応用情報問題からキーワード抽出する
google bardを起動する`https://bard.google.com/chat?utm_source=sem&utm_medium=paid-media&utm_campaign=q4jaJP_sem1`

barrdプロンプトに次の命令を入力してpdfファイルを指定して要約作成する  
```
次のPDF文書の問題１から問題１０までの要約をお願いしたいhttps://www.ipa.go.jp/shiken/mondai-kaiotu/ps6vr70000010d6y-att/2023r05a_ap_am_qs.pdf
```
barrdプロンプトにさらに次の命令を入力する
```
この文書で使われている情報処理用語をCSV形式で出力したい
```
  
結果表示

```
用語,説明
----------,---------
2進数,,2進法で表された数,,
逆ポーランド表記法,,後置記法とも呼ばれる、演算子の優先順位を明示的に表記する記法,,
パリティビット,,データの誤り検出・訂正に用いられるビット,,
双方向リスト,,先頭と末尾の要素を示す要素を持ち、双方向に要素を参照できるリスト,,
バブルソート,,隣接する要素を比較して、大小関係が逆になっている場合は大小関係を反転させるソートアルゴリズム,,
主成分分析,,データの背後にある構造を取得するために用いられる統計的手法,,
JSON,,JavaScript のオブジェクトの表記法などを基にして規定されたデータ記述の仕様,,
ヘテロジニアスマルチコアプロセッサ,,異なる種類のコアを搭載したマルチコアプロセッサ,,
投機実行,,分岐条件の結果が決定する前に、分岐先を予測して命令を実行する技術,,
デフラグ,,フラッシュメモリの寿命を延ばすために用いられる技術,,
```

入力フォーマットを合わせるためカンマを追加している

作成されたCSVファイルをコピーする
学習アプリhttps://apps.apple.com/us/app/応用情報/id6467130182
の設定・学習データの入力の画面にペースト、登録ボタンをクリックすると読み込み完了


<a href="https://apps.apple.com/us/app/%E5%BF%9C%E7%94%A8%E6%83%85%E5%A0%B1/id6467130182?itscg=30200&amp;itsct=apps_box_appicon" style="width: 170px; height: 170px; border-radius: 22%; overflow: hidden; display: inline-block; vertical-align: middle;"><img src="https://is1-ssl.mzstatic.com/image/thumb/Purple126/v4/50/1e/60/501e60ee-a389-356c-5616-120f1c6ce86f/AppIcon-0-0-1x_U007epad-0-85-220.png/540x540bb.jpg" alt="応用情報" style="width: 170px; height: 170px; border-radius: 22%; overflow: hidden; display: inline-block; vertical-align: middle;"></a>
