┌────── ─ ─ ─ - - -
│git 操作関連memo
	┌────── ─ ─ ─ - - -
	│変更されたファイルを元に戻す
		git checkout <変更されたファイル>
	┌────── ─ ─ ─ - - -
	│リポジトリを最新のバージョンに更新
		git fetch 

┌────── ─ ─ ─ - - -
│2014年5月24日（土曜日）
	┌────── ─ ─ ─ - - -
	│Create a new repository on the command line
		$ touch README.md
		$ git init
		$ git add README.md
		$ git commit -m "first commit"
		$ git remote add origin https://github.com/Tsuyo4Sa10/booking.git
		$ git push -u origin master

	┌────── ─ ─ ─ - - -
	│Push an existing repository from the command line
		$ git remote add origin https://github.com/Tsuyo4Sa10/booking.git
		$ git push -u origin master
┌────── ─ ─ ─ - - -
│2014年6月10日（火曜日）
	┌────── ─ ─ ─ - - -
	│要件
		・hover で選択した項目の勘定項目一覧が表示されるが、その際に縦の
		サイズが変化してしまう問題が有る。この問題をなんとかしたい。
		希望を言うと、縦横のサイズは固定として表示が入りきらない場合は選択
		している方の横サイズを広げ、そのもう一方の横サイズを小さくしたい。
		←	まずは縦サイズを固定してオーバーフローした際には表示しない様に
			してみようか。。。
			うん。これはできる。
		←	親要素の変更は Js が必要と思われる。その為この案は一旦破棄する。
		・hover で項目の表示をバックグラウンド表示とする。






