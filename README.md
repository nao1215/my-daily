# my-daily  
READMEに日記を書き、一定の期間経過後にバックログする。

# 2022年3月
## 2022年3月19日（土）
### 育児
3月3日に長男誕生。肺が湿っていたため、病院で１週間（通常の入院日数 + 1日）過ごし、我が家に迎え入れ。入院日数が伸びたのは、退院日間近で息子が元気になったので、妻と1日病院で過ごすため。驚いたのは、保険が適用されないので、入院1日で数万かかった事だ。  

息子と過ごした期間は、まだ一週間ぐらいだ。可愛い。静かな時は。泣き始めるとモンスターだ。産まれたての顔は「この子、この顔で大丈夫か？」と不安に思ったが、今は良い感じの顔で、目の色は薄い。鼻は妻より私に似ている気がする。  

新生児は、想像以上の頻度で泣く。  
オムツ交換やお風呂でガン泣きする。母乳を飲んだ直後に、お腹が空いて泣く。自分の手が顔に当たって泣く（対策としてお雛様巻を覚えた）。鼻がスピーっと鳴って泣く。抱っこして寝かしつけた後にベビーベッドに置いたら、背中センサーが反応して泣く。最近は、息子が泣いたら私も「ウェンウェン」と息子の耳元で声に出している。  

こんなイベントばかりでは、嫌気が差してしまう。  
しかし、面白いイベントが2つ起きている。1つ目は、息子がウンチをする時、ドラゴンボールの気合ためのように「アアぁぁーッ、アアー!!」と一定の調子で叫びながら、ブーブーオナラしている事だ。どうしても笑ってしまう。他の新生児は、静かに致しているのだろうか。  
2つ目は、息子がメタルを聴くと笑う事だ。アカペラメタルバンド"Van Canto"の[Battery（Metallicaカバー）](https://www.youtube.com/watch?v=BEwNrjvNiYs)や[Kings of Metal（Manowarカバー）](https://www.youtube.com/watch?v=IiESgYr35gA)が好きなようだ。破裂音が入っているからかな、と想像している。

### 仕事
転職して早2ヶ月。組み込みエンジニアからバックエンドエンジニアへジョブチェンジした影響で、開発を進める上で必要な知識が欠落したように思える。実際には、今までの生活で勉強不足だったとも感じている。前職は、ドメイン知識が必要であり、コンピュータサイエンスの知識は最低限あれば良かった。現職は、それが逆転した感じだ。  

現職で書いているコードは、私が役に立たない事を考慮して、実装難易度が低い部分を割り当てられている。担当部分のロジックは、DBにアクセスして、データをクライアント側にRESTful APIで返すだけなので実装難易度が低い。が、結構レビュー指摘を受けており、少しずつ対策をしている。仕様を明確にし、実装にコメントを書き、Pull Requestsにも実装意図をコメントしている。色々、理解度が低いから難易度に対する認識も間違えているのかもしれない。  

困っているのは、「アーキテクチャを正しく保つ事」と「暗黙的なルール（好み含む）」に悩む時間が長い事だ（前者は悪い事ではない）。まだ、修正に対するリターンを実感できていない。それよりも気になる事が何点かある。例えば、エラーハンドリング、ユニットテスト数、サラッと行われる関数の仕様変更。どれも前職と比較して、「本当にそれでいいの？」と疑問を抱きながら実装をしている。レビューコメントも優しい言葉使いが良いかな、とか色々悩んでる。良い事だ。  

前職で作っていたソフトは生産装置だったので、「決して装置が止まらぬように。顧客の製品に被害を与えぬように」という観点では、非常に優れていたと今更ながら感じた。考え方に筋が通っていた。当時は、その良さに気づいていなかった。

### OSS開発
- OSS開発では、DBを操作するCLIコマンドを考えている。着手は6月ぐらいと思われる。内容は、[Common SQL Environment](https://www.vector.co.jp/soft/win95/business/se180732.html)のTUI版だ。少し規模が大きいので、事前調査もしている。UIには、[Charm](https://charm.sh/)を採用するつもりだ。ただ、表を描画（かつマウスによるカラム選択）できるかどうかが分かってない。 

### 私生活
- 雑誌の仕事が舞い込んできた。思いがけぬプレゼントに舞い上がった。が、息子に振り回されて、手を動かす時間が取れない。気合が足りないのだ。ただ、締切までの期間が1ヶ月しかないのはキツイ。2ヶ月あれば余裕だろう。    
  
- フルリモートなので、音楽を聴く機会が増え、少し楽曲を買った。Michael KiskeのEagle Fly Freeが聴きたかったのでHelloweenのライブ音源、スラッシュメタルの開拓として[Darkness Descends（Dark Angel）](https://www.amazon.co.jp/gp/product/B0773F5534/ref=ppx_yo_dt_b_d_asin_title_o00?ie=UTF8&psc=1)と[	
Forbidden Evil（Forbidden）](https://www.amazon.co.jp/gp/product/B076NFNY12/ref=ppx_yo_dt_b_d_asin_title_o01?ie=UTF8&psc=1)を買った。スラッシュ系は、ちょっと音が悪い。純度の高いスラッシュは、最近発売された音源の方が音が良いので（ザクザクなリフでノレるので）、古いのより新し目を買った方が良いかなと感じた。  

- 眠い。日記を書いている現在も眠い。最近、眠る時は地面に落ちていく感覚と共に、意識を失う。目が覚める時は、身体が上手く動かない。ゆっくり起き上がる。

## 2022年3月20日（日）
### 育児
- 前日、息子が絶不調で一日中泣いていた。お腹が空いたり、オナラが上手く出なかったりで不機嫌。オムツを変える時にオッサンみたいなオナラをブーブーしていた。泣き声はスクリーミングで、耳がジンジンした。今日は、快便のようで大物が2回。背中まで汚れており、早く固形物になって欲しい。
  
### 私生活
- 家事を頑張った自分偉い。風呂掃除、トイレ掃除、掃除機がけ、洗濯、皿洗い……終わった頃には午後になっていた。
- 嫁と親の仲が悪い状態は少し改善した。解決には痛みを伴い、お互いに涙を流す状況になった。原因は、コミュニケーション。例えば、今日はこんな流れで不和があった。午後13時に来訪予定だった親が姪の世話の都合で14時に到着した。14時はちょうど授乳のタイミングだった。そのため、嫁は不機嫌そうに「以上です」と言いながらドアを閉めた。私の父親に授乳を見せないためだ。しかし、このやり取りは第三者視点で「帰れ」と言われたように感じる。しかし、嫁はそのつもりはない。こんなやり取りが年単位で続くので、私の母は、嫁が母のことを嫌いだと考えていた。しかし、嫁は母のことが嫌いではない。この認識差をなくすことは、精神的に辛い作業だったが、本日上手くいった。大人同士の仲直りだ。仲裁役の私は疲れた。
- 雑誌の仕事は、進捗30%ぐらい。明日40%になっても、進捗がマズイ。単純に工数投入できていない。タリーズにこもる日を一日作るか……

### OSS開発
- DBを操作するCLIコマンドは、lazygitを参考にして、lazysqlという名称にしようと考えた。しかし、[同名かつ作りたい内容に似ているOSS](https://github.com/Kavantix/lazysql)が既にあった。試してみたが、まだ出来が良いとは言いがたかった（機能不足、かつコードがゴチャついていた）。日本語環境では、[gocui](https://github.com/jroimartin/gocui)によるTUIは描画が崩れるので、gocui以外のTUIライブラリを採用したい所。問題は、グリッド（表）が描けるかだ。
- 関連ツール含めて、go version 1.18（新しいgolang）が安定化したように思えた。そのため、今まで開発してきたOSSのgo versionを1.18に更新した。更新作業中に、GoReleaserに対応していなかったOSSを対応させた。このタイミングで、いくつかのOSSはWindowsやMac向けにコンパイルできない事に気づいた。原因は、依存ライブラリがクロスプラットフォーム対応ではなかったため。将来的に使いそうなOSSは、クロスプラットフォーム対応できているので問題無しとした。

### 勉強
- [SQLアンチパターン](https://www.oreilly.co.jp/books/9784873115894/)の第一章を読んだ。ジェイウォーク（信号無視）、つまり交差テーブルの話。結論は、「ひとつひとつの値は個別の行と列に格納しましょう」（何らかの区切り文字を使って、一つのフィールドに複数の値を格納するのはNG）である。内容は問題ないが、交差テーブルをJOINするクエリがスッと書けない問題が別途ある。その点を改善したい。
  
## 2022年3月21日（月）
### 音楽
- ジョージア州サバンナ出身のアート・メタルバンド「[BARONESS](https://en.wikipedia.org/wiki/Baroness_(band))」が気になっている。独自の世界観（AORっぽい）で頭を振るタイプではないが、作業の邪魔をしない雰囲気。
- スラッシュメタルの発掘も再開した。現代的な音を求めて、[WARBRINGER](https://ja.wikipedia.org/wiki/%E3%82%A6%E3%82%A9%E3%83%BC%E3%83%96%E3%83%AA%E3%83%B3%E3%82%AC%E3%83%BC)に目をつけている。が、活動の後期で何かコレじゃないバンドに変貌しているらしく、聴くとしても1st〜3rdぐらいまでになりそう。
### 勉強
- [SQLアンチパターン](https://www.oreilly.co.jp/books/9784873115894/)の第二章、ナイーブツリー（素朴な木）。階層構造の話。具体例としては、コメントに対するリプライ（枝分かれ含む）を管理するための方法論で、実践的なアンチパターンだった。読んだが、すぐ実践はできないと思われる。閉包テーブル（親ID、子孫IDを全て保持する方法）が最も優れていた。
  
|設計|利点|欠点|  
|:--|:--|:--|
|隣接リスト|ノードの直近の親子を簡単に取得可能<br>列の挿入が簡単| 深い階層をサポートできない<br>ツリーへのクエリが難しい<br>ツリー内に孤児が出来る|
|再帰クエリ|WITHやCONNECT BY PRIORをサポートするDBでは、隣接リストの計算効率UP|隣接リストと同じ|
|経路列挙|Unix Path形式で分かりやすい<br>パターンマッチングで子孫、先祖を取得可能<br>ソートが楽|パスとノードが最新であると保証できない<br>深さに制約がある|
|入れ子集合|サブツリーに対する迅速かつ容易なクエリが可能|ノードの挿入や移動に計算が発生|
|閉包テーブル|ノードが複数のツリーに所属可能|階層が深くなると、レコードが増える|

### Golang DB周りの整理
- [kayac/ddl-maker](https://github.com/kayac/ddl-maker)：Golangの構造体（+ タグ）からDDLを生成する。規模が小さい割に、実用性がある。分かりやすい。MySQLだけに対応。PostgreSQLに対応しないのは開発元（カヤック内）で需要がないからだと思われる。
- [schemalex/schemalex](https://github.com/schemalex/schemalex)：DBマイグレーションツール。２つのMySQLのスキーマの差分(ALTER)を表示するツール。MySQLのみ対応。ALTER文の生成しかしないため、DBにSQLを適用する処理は別途必要。比較は、「sql <-> DBテーブル」「sql <-> gitコミットハッシュ」「sql <-> 標準入力」の3パターンでできる。
- [schemalex/git-schemalex](https://github.com/schemalex/git-schemalex)：「migrationを実行した際のsqlファイルのコミットハッシュ」と「最新のSQLファイル」との差分をDBに反映する。
- [k0kubun/sqldef](https://github.com/k0kubun/sqldef)：CREATE文と現在のスキーマを比較して、自動的にALTERやCREATEを作成し、実行する。MySQL／PostgreSQL／SQLite3／SQL Server対応。様々な企業がコントリビュートした形跡（スライドなど）がある。生SQL管理なので、DSL不要で学習コストが低い。
- [go-gorm/gorm](https://github.com/go-gorm/gorm)：Object-Relational Mappingツール。注意しないとハマる。例えば、idの値が指定されていないとテーブル全件のDeleteを試みる。コード記述量は減るが、意図しない挙動もする。また、複数テーブルを編集する時のお作法に対する学習コストがある。
- [dropbox/godropbox](https://github.com/dropbox/godropbox/tree/master/database/sqlbuilder)：クエリビルダー。MySQLのみ対応。プリペアドステートメントなし。更新も止まっている。
  ```
  query, err := t.Select(t.C("id"), t.C("hoge")).Where(sb.EqL(t.C("id"), 0)).String("test")

  // query == "SELECT `HOGE`.`id`,`HOGE`.`hoge` FROM `test`.`HOGE` WHERE `HOGE`.`id`=0"
  ```
- [Masterminds/squirrel](https://github.com/Masterminds/squirrel)：クエリビルダー。複雑なサブクエリに対応できない。
  ```
  subquery := sq.Select("id").From("users").Where(sq.Eq{"id": id})
  sql, args, err := subquery.Prefix("SELECT EXISTS (").Suffix(")").ToSql()
  // SELECT EXISTS ( SELECT id FROM users WHERE id = ? ) [hoge] <nil>
  ```
- [doug-martin/goqu](https://github.com/doug-martin/goqu)：クエリビルダー。
  ```
  ds := goqu.Insert("user").
	Cols("first_name", "last_name").
	Vals(
		goqu.Vals{"Greg", "Farley"},
		goqu.Vals{"Jimmy", "Stewart"},
		goqu.Vals{"Jeff", "Jeffers"},
	)
    insertSQL, args, _ := ds.ToSQL()
  ```

### OSS開発
- 雑誌の記事を書いている最中に、POSIXコマンド一覧を調べるのが面倒だったため、[posixerコマンド](https://github.com/nao1215/posixer)を作った。今後、POSIXに関係する機能を詰め込めるように、インターフェース的な名称（〜er）にした。結果を表で出力する理由は、[olekukonko/tablewriter](https://github.com/olekukonko/tablewriter)を使いたかったから。1時間で完成させるつもりが、2時間半ぐらいかかってしまった。
  ```
  $ posixer check
  +------------+----------------+----------------+
  |    NAME    |      TYPE      | IN YOUR SYSTEM |
  +------------+----------------+----------------+
  | alias      | shell built-in | installed      |
  | bg         | shell built-in | installed      |
  | cd         | shell built-in | installed      |
     :
     :
  | wait       | shell built-in | installed      |
  | ar         | required       | installed      |
  | at         | required       | installed      |
  | awk        | required       | installed      |
  | basename   | required       | installed      |
     :
     :
  | mesg       | required       | installed      |
  | sact       | optional       | not installed  |
  | sccs       | optional       | not installed  |
  | rmdel      | optional       | not installed  |
     :
     :
  | what       | optional       | not installed  |
  | yacc       | optional       | installed      |
  | zcat       | optional       | installed      |
  +------------+----------------+----------------+
  ```
- [ubumeコマンド](https://github.com/nao1215/ubume)が生成するGoReleaser周りが派手にバグってた。GitHubアクションは手動テストできないから発見が遅れてしまった。そもそも、設計が悪い。ファイルの内容をソースコードにベタ書きしているから、ymlファイルのインデントがズレる。出力対象のファイルは、embedすべき。でも、直す気力がない。

  
## 2022年3月23日（水）
### 勉強
- [SQLアンチパターン](https://www.oreilly.co.jp/books/9784873115894/)の第三章、「IDリクワイアド（とりあえずID）」。`id`カラムを追加する前に、レコードを一意にするカラムがないかを確認した方が良い。USING を使って JOIN できるのは知らなかった。今までは「`user`テーブルの`id`カラムは、JOIN する時に`user_id`として扱う」みたいな事をしていたが、最初から　`user_id`カラムとして定義した方がUSINGを使えて楽そう。

> これは個人的な感想ですが、 USING と ON id = user_id の使い分けをいちいち考えるのが面倒なので、必ずON句を使うのが好みなんですよね。前職でORMが生成するSQL文に慣れてしまったというのもあります。USING 使っても ORM の実装が複雑になるだけなので、基本的にORMは USING を使ったクエリを生成しません。これもまた「いちいち考えるのが面倒」という理由で、僕は省略できる場合でもテーブル名を明示します。 そうすると user.user_id vs user.id になってタイプ数が増えるだけなんですよね :thinking_junko:というわけで僕は id 派です。(異論は認める) **from :neet:**


- [SQLアンチパターン](https://www.oreilly.co.jp/books/9784873115894/)の第四章、「キーレスエントリ（外部キー嫌い）」。外部キー制約があった方がアプリ側のコードで楽できるよね、というお話。カスケード更新（親の更新や削除が子の行にも反映される）ができるメリットもある。SQLは、アプリ側で楽をするための仕組みが多い。

## 2022年3月27日（日）
### 育児
- 息子の顔にニキビ（乳児湿疹？）が出来て、可愛そうな感じ。生後２週間を過ぎた頃から、抱っこしていないとほぼ泣き続ける。なので、息子を抱きながらご飯を食べたり、記事を書いたり。泣いてる理由は腸内に溜まったガス。苦しみながら、汚いオナラをする息子。君はいつまでオナラが原因で泣くの？

### 料理
- スペアリブが安かったので、角煮的なものを仕込む。まだ出来上がっていないが、美味しくできると良いな。角煮を作るときだけ圧力鍋が欲しくなる。

### OSS開発
- DBMS自体を作りたくなり、[egsql](https://github.com/nao1215/egsql)の開発を開始。SQLiteのようにアプリに組み込むタイプのDBであり、Golang専用。DMBSを作りたかったが、DBMSにアクセスするためのドライバーが必要。そこからさらにクライアント（アプリ）が必要なことに気づき、「何人月かかるかな？」と若干ビビっている。ユニットテストやエラーハンドリングもきちんと設計し、「そこそこ使えるライブラリ」を目指す。

### 私生活
- 雑誌の記事を一通り書き終えたので、一安心。残りは完成度を90%から100%に高める作業。今回もボリュームオーバーしていて、加筆もしたい状態。8〜10ページの分量は難しい。物足りない。 
