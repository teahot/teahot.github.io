【cloud上が更新されていた場合、cloud→local】
・作業のフォルダのディレクトリ内に移動
・Git Bashを作業フォルダ内で開く
・git pull origin master

【local→cloud】
・git add 更新または追加したファイル名
・git commit -m "コメント"
・git push origin master

【2機種目以降の前提】（初期設定。初回のみ）
・gitの環境構築が済んでいるPCでのみ更新や追加などの作業ができる。
・Git Bashを開く
・git config --global user.name "githubのuser名"
・git config --global user.email "githubに登録したメールアドレス"
・空のフォルダを作成
・空のフォルダのディレクトリ内に移動
・git init
・git clone https://github.com/teahot/teahot.github.io.git
