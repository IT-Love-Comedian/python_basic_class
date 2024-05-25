# 概要
Python 学習用のコンテンツは、書籍、Webサイト、サービスなど有料・無料含めて膨大にある。
東京大学や京都大学が出している質の高いものから、それこそ Python 公式でも日本語で学ぶことができる。
ただし、これらのコンテンツは学習について進捗管理がし辛い。

そこで、データサイエンス100本ノックのような、Python の基礎について問題が列挙されているようなコンテンツを作ろうと思った。
GitHub に問題集を作成することで、取り組んだ内容や、コミット時の履歴、Slackへの通知連携などで取り組みが見えやすい。
複数人で同時に行えば、他者のコミットによる通知がモチベーションにも繋がると考えた。

Python 単体の学習だけではなく、エンジニアとしての基礎である Git の使い方についても同時に身につけて欲しい。

# 受講者向け
## GitHub の登録、準備
以下のドキュメントを参考に GitHub でアカウントの作成を行なってください。  
https://docs.github.com/ja/get-started/start-your-journey/creating-an-account-on-github  

次に、使用している端末で SSH キーを生成してアカウントに登録してください。  
https://docs.github.com/ja/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent  


## Git 環境を構築する
1. 自身のブランチを作成する
1. notebook フォルダをコピーして、自身の名前を付けたフォルダを作成する
1. コミット、プッシュを試す

## 課題の進め方
1. notebook の問題を解く
1. 区切りのいいタイミングや学習の終わりにコミットする
1. コミット手順は `git add`, `git commit`, `git pull`, `git push`

# 課題が完了したら
1. プルリクエストを出す
1. レビューしてもらって、OKが出たらマージ

# 問題作成者向け
問題の作成を手伝ってくれる人を募集しています。
[Python のチュートリアル](https://docs.python.org/ja/3/tutorial/)や、[東京大学のPython入門教材](https://github.com/utokyo-ipp/utokyo-ipp.github.io)をベースに問題を作成してください。

## 問題作成方法
branch を切って、マージリクエストを出す方式で問題を作成してください。
既存の問題に対して修正を提案する場合も、この方式をとってください。
issue を作成していただいても構いません。