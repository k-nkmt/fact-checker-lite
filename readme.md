# Fact-Checker-Lite
Fact-Checkerの動作をPythonとJupyter notebookで簡単に検証、Fact-Checkerについての簡単な補足

## 目的
チームみらいが公開した[Fact-Checker](https://github.com/team-mirai-volunteer/fact-checker)について、公開当日(2025-05-26)の状態だとシステムやAIにそれなりに詳しい人向けだなと感じました。  
AIについて関心が高まっていることから、もう少し詳しく知りたい・自分でも試してみたいという方もいるかと思い、簡単に試せるようにAI関連の処理を抜き出してPythonで実行できるようにしました。あわせて少しですが概要やカスタムに関する解説も置いています。  
Fact-Checkerの採用を検討する前の動作検証や、ボランティアの方がプロンプトを改善してみる、といった用途に使用してもらえるといいかと思います。

主なファイルは以下のようになっています。
- guide.md : Fact-Checkerの概要やカスタマイズする箇所についての簡単な解説
- fact-checker-lite.ipynb： AI関連の処理をpythonで動かせるようにしたコードと説明・実行例

fact-checker-lite.ipynbについては、元から比べるとかなり簡単に実行できるようになっていると思いますが、OpenAI社のAPIなどのサービスについて基本的な知識があることが前提となっている点にはご注意ください。  