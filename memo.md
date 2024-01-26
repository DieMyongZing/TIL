# memo

## TILの書き方について



2024/1/26　面接でコーディングについての問いかけがあり、
0点に近い回答をしてしまった。猛省。
考えたらいくら求職活動の手を広げてるからと言って、
こんな基本的なことをおざなりにしたのは恥じたいところだ。

Q1

出力結果：A

出力結果：B

上記結果を出力するコーディング（...部分）を補完せよ↓

console.writeline(calc(0))

console.writeline(calc(1))

string calc(int x ) {...


当初、0,1,2...という入力に対応してa,b,c....という出力ができるコードをしたいのかなと考える。

コーディングをさぼってなかったら最低限の回答はできたかもしれない。

string変数str1、str2を定義し、if　else構文を返すという原始的な構文で提出。

Q2

id・氏名・項目Aからなる名簿tableから特定姓の行だけ抜き出すSQLを作れ↓

SELECT と Likeしか思い出せず、

SELECT 氏名 FROM 名簿table Like 特定姓

などと書いて出す。

うろ覚え過ぎて今回のメモを取りたくなった発端。

正解は SELECT *（後ろにつけるべき氏名をなぜここにつけたのか、恥ずかしいにもほどがある) from 名簿table where 氏名 like N'%特定姓%'

SQL文そのものは覚えることは多くないのだから、さすがに初歩レベルでもこれは回答したかった。

しかし今回、生まれて初めてコーディングについて試されて、目が覚めた気がした。

次は0点の回答は脱出できるように復習する。


* リポジトリを作ります。
* コンテンツを作成します。

* 10/31　GitHub習熟にToday I Learn/日記をつけるのが練習になると見たので記述始める
* 10/31　ヒヒヒのエンディングスクリプト（Ｂ・Ｅ）をより自然な形に調整。

* 11/1 1社と面談
* 11/1　Discordのサーバーを一つ解散するのでログを移植。

* 10/07 https://shinshin-log.com/csharp-csv-output/ //C#:csvファイルを出力する簡単な方法
* 
* ＞Linqは見た感じ難しそうなのですが、慣れると簡単ですよ

* 画面に配置されたコントール群からTextBox型のものを選択
* this.Controls.OfType<TextBox>()
* 変数名で並べ替え
* .OrderBy(tb => tb.Name)
* TextBoxのTextプロパティの値を選択
* .Select(tb => tb.Text)
* 結果を配列に変換
* .ToArray();

* https://www.doraxdora.com/2018/08/14/5665/
* 【C#】WindowsForm にチェックボックスを動的に配置してみる | ドラブロ – let bygones be bygones...

* SQL BULK INSERT テーブル名
* FROM 'データファイルパス'
* WITH (
* CODEPAGE = '65001',
* FIELDTERMINATOR = ',',
* ROWTERMINATOR = '\n'
* );

* 文字列を特定の行数で折り返させたい・・・どんな方法があるかな
* https://teratail.com/questions/249814
* 
* https://kanchi0914.hatenablog.com/entry/2019/07/23/070005
* 【C#】Unity 2Dでできるだけ簡単にアドベンチャーゲーム(ノベルゲーム)を作る　その１ - Kanchiの日記
