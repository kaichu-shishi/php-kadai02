# 課題7　 -PHP2 ブックマークアプリ【登録】-

## ①課題内容（どんな作品か）
- 現実恋愛シミュレーションゲーム『ザ・ゲーム・ライオンキング』に、PHPとデータベースをつかって言動登録＆表示機能を実装した。
  - （「言動登録」とは、デート等でどんな発言や行動をすればオスとしての魅力を感じさせられるかを、プレイヤー自身が考えて文章で入力する機能である）

## ②工夫した点・こだわった点
- フロント側（HTMLとJavaScript）で簡易的なバリデーション機能を実装した点。すなわち、言動のタイトル・カード選択・言動の内容、これらの三つが入力されていないとPHPに送信できないようなアーキテクチャにした。
- タイトルとテキストエリアについては、HTMLの要素に「required」をつけることで実装した。checkboxについてはこちらの記事をもとに実装した。→https://qiita.com/katao_eng/items/ffea1575afdc95646995
- 言動を表示する部分の見た目に力を入れた（PHPによる出力と、CSSによるスタイリング）。

## ③難しかった点・次回トライしたいこと(又は機能)
- バリデーションの実装が最も難しかった。なかなか思い通りの実装にできず、今回は簡易的な実装にとどまったのが悔しかった。本当は確定ボタンを押したとき、「本当にこれで確定しますか？ - OK or キャンセル」というような確認ダイアログボックスまで実装したかった。JavaScriptのconfirm();で試したのだが、キャンセルを押してもPHPに送信されてしまう問題が発生した。どんなに調べてもどうしても解消することができず、次回の課題としたい。
- 次回は入力画面だけでなく、入力内容を確認する画面、登録完了画面、できればエラー画面まで実装したい。

## ④質問・疑問・感想、シェアしたいこと等なんでも
- [質問]
- [疑問]バリデーション機能をスマートに実装する方法はあるのかどうか疑問に感じた。
- [感想]PHPがからんでくるとバリデーション機能を実装する難易度が急激に上がると感じました。
- [tips]
- [参考記事]
