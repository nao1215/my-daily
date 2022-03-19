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
転職して早2ヶ月。組み込みエンジニアからバックエンドエンジニアへジョブチェンジした影響で、開発を進める上で必要な様々な知識が欠落したように思える。実際には、今までの生活で勉強不足だったとも感じている。前職は、ドメイン知識が必要であり、コンピュータサイエンスの知識は最低限あれば良かった。現職は、それが逆転した感じだ。  

現職で書いているコードは、私が役に立たない事を考慮して、実装難易度が低い部分を割り当てられている。担当部分のロジックは、DBにアクセスして、データをクライアント側にRESTful APIで返すだけなので実装難易度が低い。が、結構レビュー指摘を受けており、少しずつ対策をしている。仕様を明確にし、実装にコメントを書き、Pull Requestsにも実装意図をコメントしている。色々、理解度が低いから難易度に対する認識も間違えているのかもしれない。  

困っているのは、「アーキテクチャを正しく保つ事」と「暗黙的なルール（好み含む）」に悩む時間が長い事だ（前者は悪い事ではない）。まだ、修正に対するリターンを実感できていない。それよりも気になる事が何点かある。例えば、エラーハンドリング、ユニットテスト数、サラッと行われる関数の仕様変更。どれも前職と比較して、「本当にそれでいいの？」と疑問を抱きながら実装をしている。レビューコメントも優しい言葉使いが良いかな、とか色々悩んでる。良い事だ。  

前職で作っていたソフトは生産装置だったので、「決して装置が止まらぬように。顧客の製品に被害を与えぬように」という観点では、非常に優れていたと今更ながら感じた。考え方に筋が通っていた。当時は、その良さに気づいていなかった。

### 私生活
雑誌の仕事が舞い込んできた。思いがけぬプレゼントに舞い上がった。が、息子に振り回されて、手を動かす時間が取れない。気合が足りないのだ。ただ、締切までの期間が1ヶ月しかないのはキツイ。2ヶ月あれば余裕だろう。    
  
フルリモートなので、音楽を聴く機会が増え、少し楽曲を買った。Michael KiskeのEagle Fly Freeが聴きたかったのでHelloweenのライブ音源、スラッシュメタルの開拓として[Darkness Descends（Dark Angel）](https://www.amazon.co.jp/gp/product/B0773F5534/ref=ppx_yo_dt_b_d_asin_title_o00?ie=UTF8&psc=1)と[	
Forbidden Evil(Forbidden)](https://www.amazon.co.jp/gp/product/B076NFNY12/ref=ppx_yo_dt_b_d_asin_title_o01?ie=UTF8&psc=1)を買った。スラッシュ系は、ちょっと音が悪い。純度の高いスラッシュは、最近発売された音源の方が音が良いので（ザクザクなリフでノレるので）、古いのより新し目を買った方が良いかなと感じた。  

OSS開発では、DBを操作するCLIコマンドを考えている。着手は6月ぐらいと思われる。内容は、[Common SQL Environment](https://www.vector.co.jp/soft/win95/business/se180732.html)のTUI版だ。少し規模が大きいので、事前調査もしている。UIには、[Charm](https://charm.sh/)を採用するつもりだ。ただ、表を描画（かつマウスによるカラム選択）できるかどうかが分かってない。  

眠い。日記を書いている現在も眠い。最近、眠る時は地面に落ちていく感覚と共に、意識を失う。目が覚める時は、身体が上手く動かない。ゆっくり起き上がる。
