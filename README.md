┌────── ─ ─ ─ - - -
│git 操作関連memo
	┌────── ─ ─ ─ - - -
	│変更されたファイルを元に戻す
		git checkout <変更されたファイル>
	┌────── ─ ─ ─ - - -
	│リポジトリを最新のバージョンに更新
		git fetch 
	┌────── ─ ─ ─ - - -
	│リモートリポジトリにプッシュ
		git push -u origin master

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
┌────── ─ ─ ─ - - -
│2014年6月18日（水曜日）
	hover 時に h3 の line-height が変更できない問題に直面。
	もしかしたらなのだが、最初に選択された状態の要素数とかで決められてしまって
	いるのかも。
┌────── ─ ─ ─ - - -
│2014年7月2日（水曜日）
	勘定項目群の名称が勘定項目によって見えなくなるのが嫌。
	上にかぶせる勘定項目の透過性を加える。
	←	まだ見えにくい
	フォントも悪いかもしれない。。。
	←	フォントの太さも指定できた。
		でもまだなんだかな。。。
	選択された勘定項目を少し大きくしたい。
	←	並びが崩れてポイント位置が変化してしまう。あと、枠からはみ出して何か
		嫌だよね。
	取り敢えず見た目はおいとくか。
	機能として解説をちゃんと表示しなきゃ。

