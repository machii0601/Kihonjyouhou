##　chapter13　セキュリティ
- 情報セキュリティマネジメントシステム(Information Security Management System)     組織が自身の情報資産を適切に管理し、守りための仕組み
- ISMSの国際規格（27000）
- 情報セキュリティ3つの要素　＋　４要素
- 機密性、完全性、可用性
- 真正性　　　　エンティティはそれが主張する通りのものであるという特性
- 責任追跡性　　説明責任。いつ、誰が、何をしたのかを特定・追跡できる特性
- 否認防止　　　主張された事象または処置の発生、およびそれらを引き起こしたエンティティを証明する能力
- 信頼性　　　　意図する行動と結果とが一貫している特性
- セキュリティポリシ　経営者が企業としてどのように取り組むか明文化して従業員や外部関係者に周知すること
- リスクマネジメント（31000）　経営層が責任を負い、業務の一環として役割を分担しながら会社的に取り組むもの
-
- リスクマネジメント　4つのプロセス
- リスク特定　　　　　　リスクを洗い出す
- リスク分析　　　　　　特定したリスクの影響度と発生頻度からリスクレベルを算定する
- リスク評価　　　　　　算出したリスクレベルをリスク受容基準と照らし合わせて対応の必要性も判断し、優先順位をつける
-
- これら3つを　リスクアセスメント　という
-
- リスク対応　　　　　　リスクに対してどのような対応を行うか決定する
- リスクコントロール　　損失の発生や拡大を防止する
- リスクファイナンシング　損失の補填や備えをする
-
- 不正のトライアングル
- 「機会」「動機・プレッシャー」「姿勢・正当化」の3つが揃った時に不正が発生する
-
- 個人情報（１５０００）
- プライバシーデザイン　7つの基本原則
- 1、事後的ではなく、事前的、救済的策ではなく予防的（あらかじめ）
- 2、初期設定としてのプライバシー（あらかじめ）
- 3、デザインに組み込まれるプライバシー（もともと組み込まれている）
- 4、全機能的　ゼロサムではなく、ポジティブサム（プライバシーとセキュリティの両立）
- 5、最初から最後までのセキュリティ　すべてのライフサイクルを保護（ライフサイクルを通して情報の安全を確保）
- 6、可視性と透明性　公開の維持（構成と機能は検証できる）
- 7、利用者のプライバシーの尊重　利用者中心を維持(個人の利益を最大限に維持する)
-
- コールバック　　　　　　　　遠隔地からサーバへ接続する場合などに一旦アクセスした後で回線を切り、逆にサーバ側からコールバック（着信側
- 　　　　　　　　　　　　　　から再発信）させることで、アクセス権を確認する
- ソーシャルエンジニアリング　コンピュータシステムのないところで人の心理的不注意をついて情報資産を盗み出す
- rootkit                     不正アクセスに成功したコンピュータに潜伏し、攻撃者がそのコンピュータをリモート制御できるようにする
- 　　　　　　　　　　　　　　ソフトウェアの集合体のこと
- ハニーポット　　　　　　　　侵入者やマルウェアの挙動を監視するために、意図的に脆弱性を持たせた機器をネットワーク上に公開し、おとり
- 　　　　　　　　　　　　　　として用いる手法（手口の研究が目的）
- CAPTCHA                     文字に歪みをつけて機械による自動入力を防ぐための仕組み
- ボット　　　　　　　　　　　作業を自動化してくれるプログラム
- C&Cサーバ　　　　　　　　　 「侵入して乗っ取ったコンピュータに対して、他のコンピュータへの攻撃などの不正な操作をするよう外部から
- 　　　　　　　　　　　　　　命令を出したり、応答を受け取ったりする」サーバのこと
- ウイルス対策
- ビヘイビア法(動的ヒューリスティック法)　　　実行中のプログラムの挙動を監視して、不審な処理が行われないか検査すること
- セキュアブート　　　　　　　　　　　　　　　コンピュータ起動時に、信頼性が確認できるソフトウェアしか実行できないように制限する機能
-
- ネットワークのセキュリティ対策
- ファイアウォール　　　　　　　　LANの中と外とを区切る壁
- アプリケーションゲートウェイ　　LANの中と外の間に位置して、外部とのやりとりを代行して行う機能。プロキシサーバともいう
- ペネとレーションテスト　　　　  基地の主t方を用いて実際に攻撃を行い、システムの脆弱性の有無を確認するテスト
- DMZ                             内部ネットワークからは隔離して設けられる中間的な領域
- ファジング　　　　　　　　　　　検査対象となるプログラムに対して、想定外のデータを大量に送りつけることで不具合のが生じないか
- 　　　　　　　　　　　　　　　　確認するテスト。問題を引き起こしそうなデータを「ファズ」という
-
- 共通鍵暗号方式　　　　　　　　　送り手と受け手が同じ鍵を用いる、秘密鍵暗号方式ともいう
- 公開鍵暗号方式　　　　　　　　　公開鍵と秘密鍵があり、公開鍵で暗号化、ペアの秘密鍵で複合することができる
- デジタル署名　　　　　　　　　　改竄されていないか確認できる
- 認証局（CA）　　　　　　　　　　「この公開鍵は確かに本人のものです」と証明する機構
- 公開基盤（PKI: Public Key Infrastructure）     認証期間と、公開鍵暗号技術を用いて通信安全性を保証する仕組み
- VPN（virtual Private Network）  ネットワーク上に仮想的な専用線空間を作り出して拠点間を安全に接続する技術、もしくはそれによって
- 　　　　　　　　　　　　　　　　構築されたネットワークのこと
- IPsec(Security Architecture for Internet protocol)　　ネットワーク層で動作するIP通信に、暗号化や認証機能を持たせることでより
- 　　　　　　　　　　　　　　　　　　　　　　　　　　　安全に通信を行えるようにしたプロトコル
##　chapter14　システム開発
- ソフトウェアサイクル　　　　　　運用と保守とを繰り返しながら、やがて役割を終えて破棄される瞬間まで働き続けるサイクル
-
- プログラミング
- コンパイラ方式　　　　　　　　　最初に全部機械語に翻訳してから実行する
- インタプリタ方式　　　　　　　　逐次翻訳しながら実行する
-
- ウォータフォールモデル　　　　　要件定義からテストまで各工程を順番に進めていくもの
- プロトタイプモデル　　　　　　　開発初期の段階で試作品（プロトタイプ）を作り、それを利用者に確認してもらうことで、
-                                 意識ずれを防ぐ
- スパイラルモデル　　　　　　　　システムを複数のサブシステムに分割して、それぞれのサブシステムごとに開発を進めていく方法
-
- システムのさまざまな開発手法
- RAD(Rapid Application Development)　短時間で開発を行うことを重視した手法
- タイムボックス　　　　　　　　　　　開発の期限を設けること
- アジャイル　　　　　　　　　　　　　スパイラルの派生で、より短い反復単位を用いて迅速に開発を行う手法の総称
- XP                                  テスト工藤開発、ペアプログラミング、リファクタリング、ソースコードの共同所有、
- 　　　　　　　　　　　　　　　　　　断続的インテグレーション、YAGNI
- リバースエンジニアリング　　　　　　既存ソフトウェアの動作を解析することで、プログラムの使用やソースコードを導き出すこと
- フォワードエンジニアリング　　　　　新規開発によって得られた仕様をもとに新しいソフトウェアを開発する手法
- マッシュアップ　　　　　　　　　　　公開されている複数のサービスを組み合わせることで新しいサービスを作り出す手法のこと
-
- 業務のモデル化
- ユーザインタフェース　　　　　　　　システムと人間の接点にあたる部分
- CUI(Character User Interface)　　　 画面に表示されるも入力するも文字だけのこのような文字ベースの方式のこと
- GUI(Graphical User Interface　　　　「画面にアイコンやボタンを表示して、それをマウスなどのポインティングデバイスで操作して命令を伝える」
- 　　　　　　　　　　　　　　　　　　といった、グラフィカルな操作方式のこと
-
- ティックディジット　　　　　　　　　誤入力を判定するためにコードへ付加された数字のこと
-
- 順番コード　　　　　　　　　　　　　連続した番号を順番に付与していくコード
- 区分コード　　　　　　　　　　　　　対象をいくつかのグループに分け、そのグループごとに連続した番号を付与するコード
- けた別コード　　　　　　　　　　　　桁ごとに意味を持たせたコード体系、大分類、中分類、小分類といった意味をケタに付与して階層化できる
- 表意コード　　　　　　　　　　　　　項目の意味を表す略称や記号などによって表銀するコード体系。コードを見ただけで内容を推測しやすい
-
- モジュールの分割
- モジュールの分割技法
- STS分割法　　　　　　　　　　　　　 プログラムを「入力処理(源泉:Source)」「変換(Transform)」「吸収(:Sink)」という3つの
- 　　　　　　　　　　　　　　　　　　モジュールに分割する方法
- トランザクション分割法　　　　　　　プログラムを一連の処理（トランザクション）単位に分割する方法
- 共通機能分割法　　　　　　　　　　　プログラム中の共通機能をモジュールとして分割する方法
-
- テスト
- 単体テスト　　　　　　　　各モジュールごとにテストを行なって、誤りがないかを検証。
- 結合テスト　　　　　　　　複数のモジュールを繋ぎ合わせて検証を行い、モジュール間のインターフェースが正常に機能しているかを検証
- システムテスト　　　　　　システム全体のテスト
-
- ブラックボックステスト　　モジュール内部構造は意識せず、入力に対して適切な出力が得られるか検証
- ホワイトボックステスト　　逆に、モジュール内部構造が正しく作られているか検証
-
- ブラックボックステストのデータの決め事
- 同値分割　　　　　　　　　データ範囲を種類ごとのグループに分け、それぞれから代表的な値を抜き出してテストデータに用いる
- 限界値（境界値）　　　　　上記グループの境界部分も重点的にチェックしよう
-
- ホワイトボックステスト
- トップダウンテスト　　　　上位モジュールから、先にテストを済ませていくテスト
- ボトムアップテスト　　　　下位モジュールからテストしていく
- 折衷テスト　　　　　　　　トップダウンとボトムアップを組み合わせて行う
- ビッグバンテスト　　　　　全てのモジュールを一気に繋げてテスト
- リグレッションテスト　　　プログラムを修正した時に、その修正内容がこれまで正常に作動していた範囲に悪影響を与えてないかを
- 　　　　　　　　　　　　　確認するテスト
##　chapter15　システム周りの各種マネジメント
- PMBOK　　　　　　　　         プロジェクトマネジメントの技法を体系的にまとめたもの
- WBS(Work Breakdown Structure) プロジェクトに必要な作業や成果物を階層化した図
-
- 開発コストの見積もり
- プログラムステップ法　　　　　従来からある見積もり手法でソースコードの行数により開発コストを算出する
- ファンクションポイント法　　　表示画面や印刷帳票、出力ファイルなど、利用者から見た機能に着目して、その個数や難易度から
- 　　　　　　　　　　　　　　　開発コストを算出する手法
- スケジュール管理とアローダイアグラム
- アローダイアグラム　　　　　　作業の流れとそこに要する日数をわかりやすく図にしたもの
- 最早結合点時刻　　　　　　　　対象となる結合展で最も早く作業開始できる日時（いつまでに次作業に取りかかれるか？）
- 最遅結合点時刻　　　　　　　　対象となる結合点が、全体的に影響を与えない範囲で最も開始を遅らせた日時
- クリティカルパス　　　　　　　ルート上のどの作業が遅れても、それが全体のスケジュールを狂わせる結果に即繋がってしまう
- 　　　　　　　　　　　　　　　要注意な経路のこと（最長ルート）
- PDM(Precedence Diagram Method) ここのアクティビティ（作業）を四角で囲み、それらを矢印で繋ぐことによってアクティビティの所要時間と
- 　　　　　　　　　　　　　　　 と順序、依存関係を表現する
-
- スケジュール短縮のために用いる方法
- クラッシング　　　　　　　　　資源を追加投入してコストの増大を最小限に抑えながらスケジュールの所要期間を短縮する方法
- ファストトラッキング　　　　　通常は順番に実施されるアクティビティやフェーズを並行して遂行するスケジュール技法
-
- ITサービスマネジメント　　　　顧客の欲求を満たすITサービスを効果的に提供できるよう体系的に管理する手法
-
- SLA(Service Level Agreement)　サービスの提供者とその利用者との間で「サービスや品質」を事前に取り決め、明文化したもの
- SLM(Service Level Management) PDCAサイクルを構築し、サービス水準の向上、維持に努める活動
- BCP(Business Continuity Plan) 緊急事態が発生しても、重要な事業を中断させない、中断しても可能な限り短い期間で復旧させるための計画
-
- 復旧目標3つ
- 目標復旧レベル(Recovery Level Objective)
- 目標復旧時間（Recovery Time Objective）
- 目標復旧時点（Recovery Point Objective）
-
- ファシリティマネジメント（設備のこと）　　これらの設備を適切に管理、改善する取り組みのこと
- UPS（Uninterraptivle Power Supply）　　　 無停電電源装置ともいい、外付けバッテリのような使い方ができる。停電になって
- 　　　　　　　　　　　　　　　　　　　　　一定時間電力を供給する
- システム監査
- ITガバナンス　　　　　　　　　ITシステムを適切に管理、運用するための体制や方法
- 監査証跡　　　　　　　　　　　システムの事象発生から最終結果までの一連の流れを追跡できる仕組みのこと
- フォローアップ　　　　　　　　システム監査人が行う改善指導のこと
-
##　chapter16　プログラムの作り方
- インタプリタ方式　　　　　　　ソースコードに書かれた命令を、1つずつ機械語に翻訳しながら実行する
- コンバイラ方式　　　　　　　　ソースコード内容を最初に全て翻訳して、機械語のプログラムを作成する
-
- コンバイラ方式でのプログラム実行手順
- リンカ　　　　　　　　　　　　繋ぎ合わせる。この作業をリンク（連携編集）
- 静的リンキング　　　　　　　　あらかじめリンク
- 動的リンキング　　　　　　　　ロード後にリンク
- ローダ　　　　　　　　　　　　ロードモジュールを主記憶装置に組み込ませる作業をロード。これを担当するプログラムをロータという
-
- データを探索するアルゴリズム
- 線形探索法　　　　　　　　　　先頭から順に探索していく方法
- 番兵　　　　　　　　　　　　　ループの終了判定を簡単にするため末尾に付加したデータのこと
-
- ハッシュ法　　　　　　　　　　ハッシュ関数と呼ばれる「一定の計算式」を用いてデータの格納位置をズバリ算出する方法
-
- データを整列させるアルゴリズム
- 基本交換法（バブルソート）　　隣接するデータの代償を比較、必要に応じて入れ替えることで全体を整列させる
- 基本挿入法（挿入ソート）　　　まず対象となるデータ列を「整列済みのもの」と「未整列のもの」とを分ける。この未整列側から1つずつ
-                               整列済みの適切な位置に挿入する
- 応用３種
- シェルソート、クイックソート（中間値を基準）、ヒープソート
-
- オブジェクト指向プログラミング
- オブジェクト　　　　　　　　　データ（属性）とそれに対するメソッド（手続き）を一つにまとめた概念。これをモジュール化していくことで
- 　　　　　　　　　　　　　　　全体を構成するやり方をオブジェクト指向という
- カプセル化の利点 : 知るべき情報以外は知らなくて良いと隠すことができる（情報隠蔽）
- クラス　　　　　　　　　　　　オブジェクトが持つ性質を定義したもの
- インスタンス　　　　　　　　　設計図に対して具体的な属性値を与え、メモリ上に生成してポコリと実体化させたもの
-
- 多態性（ポリモーフィズム）　　同じメッセージを複数のオブジェクトに送ると、それぞれが独立した固有の処理を行います。
- UML(Unified Modeling Language)　主に、オブジェクト指向分析・設計において用いられる統一モデリング言語
-
##　chapter17　システム構成と故障対策
- シンクライアント　　　　　　　サーバ側へと依存度を高くした。入力や表示部分のみ担当で残りの機能は全てサーバ側
- ピアツーピア　　　　　　　　　ネットワーク上で協調動作するコンピュータ同士が対等で、一元的に管理するリーダがいない
- ３種クライアントサーバシステム　クライアントサーバシステムの機能をプレゼンテーション層、ファンクション層、データ層の3つに分ける
- オンライントランザクション処理　システムの稼働形態として、要求に対して即座に処理を行い結果が反映されるもの
- バッチ処理　　　　　　　　　　　逆にリアルタイムではなく、一定時間ごとにまとめて実行する
-
- クラスタリングシステム
- クラスタリング　　　　　　　　　複数のコンピュータをネットワーク上で結合させることで、一つの巣ステムとして構築する技術
- クラスタリングシステム　　　　　この技術を用いて構成されるシステム
-
- 負荷分散クラスタ　　　　　　　　複数のコンピュータに処理を分散させることでえ、1台あたりの負荷を低くするシステム
- HA（High Availability)クラスタ　稼働中のコンピュータに障害が発生した場合、待機していた別のコンピュータが速やかに引き継ぐことで
- 　　　　　　　　　　　　　　　　停止時間を最小限にするシステム
- フェールオーバ　　　　　　　　　稼働系から待機系へと切り替わること
- フェールバック　　　　　　　　　元の可動系が復旧してそちらへと戻す切替処理
-
- HPC(High Performance Computingu)クラスタ　膨大な計算量を要するような一つの処理を分割し、複数のコンピュータが並行して処理にあたる
- 　　　　　　　　　　　　　　　　　　　　　ことで、全体の処理速度を高めるシステム
- スケールアップ　　　　　　　　　「サーバ自身の性能をより高いものに交換する」ことにより、システムの処理能力を高めること
- スケールアウト　　　　　　　　　「システムを構成するサーバの台数を増やす」ことにより、システムの処理能力を高める
-
- グリッドコンピューティング　　　小型のパソコンから大型のコンピュータに至るまで、インターネットなどのネットワーク上にある複数のプロセッサに処理を分散して、大規模な処理を行う方式
- SOA（サービス指向アーキテクチャ: Serrice Oriented Architecture）　個々の機能を「サービスというコンポーネント化（部品化）」をして、それを組み合わせることでシステムを構成するという考え方
-
- システムの性能指標
- ベンチマーク性能測定用ソフトウェアを使って、システムの各処理機能を数値化する
- スループット　　　　　　　　　　単位時間あたりの仕事（ジョブ）量
- レスポンスタイム　　　　　　　　コンピュータに処理を依頼し終えてから実際に応答が返されてくるまでの時間
- ターンアラウンドタイム　　　　　コンピュータに処理を依頼し始めてからその対応が全て返されるまでの時間
-
- システムの応答時間が重視される「オンライントランザクション処理」　→　レスポンスタイム
- 一連の処理をひとまとめに実行する「バッチ処理」　→　ターンアラウンドタイム
-
- システムを止めない工夫
- デュアルシステム　　　　　　　　２組のシステムを使って信頼性を高める。２組のシステムが同じ処理を行いながら、処理結果を見て誤動作を監視している
- 　　　　　　            　　　　1つ故障しても問題なし
- デュプレックスシステム　　　　　２組のシステムを用意するけど、片方は待機状態にしておく
- ホットスタンバイ　　　　　　　　プログラムだけ起動しておく
- コールドスタンバイ　　　　　　　完全オフ
-
- システムの信頼性と稼働率
- RASIS {Reliabilty（信頼性)　Availability(可用性)　Serviceability(保守性)　Integrity(保全性)　Security(安全性)}
- Reliabilty　　　システムが正常に稼働している状態にあること。　MTBFを用いる
- Availability　　必要な時いつでも利用できる状態にあること。　　稼働率を用いる
- Serviceability  障害発生時に、どれだけ早く発見修復が行えるかということ。　MTTRを用いる
- Integrity　　　 誤作動がなく、データの完全性が保たれること。
- Security        不正利用に対してシステム保護されていること
-
- MTBF(Mean Time Between Failure)   平均故障間隔
- MTTR(Mean Time To Repair）　　　　平均修理間隔
-
- システムの稼働率　　　　　　　　　システムが導入されてから全運転時間の中で、「正常稼働できていたのはどれくらいの割合か」
- 直列システムの稼働率 = 稼働率A ✖️稼働率B
-
- 並列システムの稼働率
- 故障率 = １- 稼働率
- 全体の故障率 = 故障率A ✖️故障率B
- 並列システムの稼働率
-
- フォールトレラント　　　　　　　　故障しても耐えるという考え方
- フェースセーフ　　　　　　　　　　故障の場合、安全最優先という考え方
- フェールソフト　　　　　　　　　　故障の場合、一部機能を切り離すなどして動作の継続を図る方法
- フールループ　　　　　　　　　　　意図しない使い方をしても故障しないようにする
- フォールアボイダンス　　　　　　　品質管理などを通じてシステム構成要素の信頼性を高め、故障そのものの発生を防ごうという考え方
-
- バスタブ曲線　　　　　　　　　　　故障の発生頻度と時間の関係性
-
- TCO(Total Cost Ownership)         全てのコスト。初期コストと運用コストに分かれる
-
- バックアップの方法
- フルバックアップ　　　　　　　　　保存されているデータの全てをバックアップする
- 差分バックアップ　　　　　　　　　前回のフルバックアップ以降に作成、変更された分だけバックアップする
- 増分バックアップ　　　　　　　　　バックアップの種類関係なく、前回のバックアップ以降の作成、変更分だけバックアップする
-
##　chapter18　企業活動と関連法規
- 経営資源　　　　　　　　　　　　　人、モノ、金
- 職能別組織、事業別制組織、プロジェクト組織、マトリックス組織
-
- マトリックス組織　　　　　　　　　事業部と職能別など、２系統の所属をマス目上に組み合わせた組織
-
- CEO(Chief Executive Officer)　　　最高経営責任者
- CIO(Chief Information Officer)    情報システム戦略を統括する最高責任者
- MOT（技術経営者: Management Of Technology）  技術的知識をどのように経営に活かせるかを体系化したもの
- イノベーション
- プロダクトイノベーション　　　　　革新的な新商品を開発することにより、他者との差別化を図る
- プロセスイノベーション　　　　　　開発、製造、物流などで革新的なプロセスを実現させることにより、他者との差別化を図る
-
- BI(Business Intelligence)　　　　 企業内の情報システムにおいて蓄積される膨大な業務データを分析・加工することにより、得られる知見をもとに経営や業務に関する意思決定を支援する手法をいう
- EA（Enterprise Architecture）　　 組織全体の最適化
- ギャップ分析　　　　　　　　　　　現状とあるべき姿を比較して分析する手法
-
- BPO(Business Process Outsourcing) 業務を外部委託すること
-
- 電子商取引（EC:Electronic Commerce）
- EDI（Electronic Data Interchage） 電子データ交換
- 耐タンパ性　　　　　　　　　　　　外部から不正に行われる内部データの改ざんや解読、取り出しなどがされづらくなっている性質
- パレートの法則　　　　　　　　　　上位20％の商品が売上の８０％を占めるという法則
- シェアリングエコノミー　　　　　　インターネットを介して個人が所有する遊休資産(モノ、場所、スキルなど)の貸し借りなどを行えるサービス
-
- 経営戦略と自社のポジショニング
- アライアンス　　　　　　　　　　　企業同士が提携して共同で事業を行うこと
- M&A　　　　　　　　　　　　　　　 買収
- アウトソーシング　　　　　　　　　他社に業務委託
-
- SWOT分析　　　　　　　　　　　　　強みと弱みを分析する手法
- PPM（Product Portfolio Management）経営資源の配分バランスを分析する
-
- コアコンピタンス　　　　　　　　　他社には真似できない企業独自のノウハウや強みのこと
- ベンチマーキング　　　　　　　　　最強企業や先進企業と比較することで、製品やサービスなどを定性的、定量的に測定すること
- コトラーの競争地位戦略　　　　　　リーダ戦略、チャレンジ戦略、フォロワ戦略、ニッチャ（ニッチ）戦略
-
- CRM（Customer Relationship Management）　顧客の情報から営業戦略を練り、ロイヤリティの獲得と顧客生涯値の最大化を目指す
- 関連法規いろいろ
- コンプライアンス　　　　　　　　　法律、各種ルールやモラルを持って企業活動を行うこと
- 著作権の帰属先は「誰が作ったのか？」という視点が重要
- PL法（著作物責任法）　　　　　　　制作物の欠陥によって損害を負った場合、製造業者等の負うべき損害賠償責任を定めた法律
- シュリンクラップ契約　　　　　　　包装を破くことで「使用許諾契約に同意したとみなしますからね」とする
- サイバーセキュリティ基本法　　　　情報システムや情報通信ネットワークへの防御施作を効率的に推進するための法律
- プロバイダ責任制限法　　　　　　　インターネット上で権利侵害があった場合に、特定電気通信役務提供者（プロバイダなど）が負うべき責任などを被害者が開示請求する権利について定めたもの
##　chapter19　経営戦略のための業務改善と分析手法
- PDCAサイクルとデータ整理技法
- ブレーンストーミング　　　　　　　複数人で自由に意見を出し合って幅広いアイデアを引っ張り出す手法
- ルール
- 批判厳禁、自由奔放、質より量、結合改善
- バズセッション　　　　　　　　　　全体を少数のグループに分け、それぞれのグループで結論を出す
- KJ法　　　　　　　　　　　　　　　多く出た意見を整理して、解決すべき問題を明確にするデータ整理技法
-
- グラフ
- レーダチャート　　　　　　　　　　クモの巣のような形をしているグラフのバランスを見るのに役立つ
- ポートフォリオ図　　　　　　　　　個々のグループが「どこの位置にどの大きさで分布しているか」見れる
-
- QC七つ道具と呼ばれる品質管理手法
- QC（Quality Contorol）　　　　　　品質管理
- ７つ
- 層別、パレート図、散布図、ヒストグラム、管理図、特性要因図、チェックシート
-
- 新七つの道具
- 連関図法、親和図法、系統図法、マトリックス図法、マトリックスデータ解析法、PDPS法、アローダイアグラム法
-
- 層別　　　　　　　　　　　　　　　データを属性ごとに分けることで特徴を掴みやすくなるという考え方
- パレート図　　　　　　　　　　　　棒グラフとして並べ、その累積値を折れ線グラフにして重ね合わせることで重要な項目を把握する手法
- ABC分析　　　　　　　　　　　　　 「比率の７0％を占める項目をA群、２０％を占める項目をB群、１０％をC群と分けて考える手法」する手法
- 散布図　　　　　　　　　　　　　　相関関係を調べたい２つの項目の点を打ち、その点のばらつきで両者の相関関係を判断する方法
- ヒストグラム　　　　　　　　　　　データを区間に分け、区間ごとのデータの個数を棒グラフとして描くことで、品質のばらつきなどを捉える手法
- 管理図　　　　　　　　　　　　　　上限と加減と設定して時系列的に発生するデータのばらつきを折れ線グラフで表す
- 特性要因図　　　　　　　　　　　　魚の骨のような形。結果に対してどのような原因が関連しているか明確にする手法
- チェックシート　　　　　　　　　　シートに確認結果を記入していく手法
- 連関図法　　　　　　　　　　　　　複雑な要因が絡み合う事象について因果関係を明らかにする手法
- ##　chapter20　財務会計は忘れちゃいけないお金の話
- 費用と利益
- 損益分岐点　　　　　　　　　　　　売上高 - (変動費＋固定費)が０になるポイント
- 変動費率＝仕入れ（600円）÷ 販売価格（1000円）＝0.6
- 売上高 ✖️ 変動費率(0.6)＝変動費
-
- 変動費＝売上高✖変動費率
- 損益分岐点売上高＝変動費＋固定費
- 　　　　　　　　＝（損益分岐点売上高✖️変動費率）＋固定費
- 減価償却
- 取得価額÷耐用年数＝毎年の減価償却額
- ROI                費用対効果
- ROI＝利益÷投資額✖️１００
- PBP(Pay Back Period)　　　　　　　投資したお金を何年後に回収できるか示す指標
- 在庫管理
- かんばん方式　　　　　　　　　　　後工程に必要な部品だけを全肯定から調達する
- ジャストインジャストタイム　　　　必要なものを、必要な時に、必要な分だけ生産する
-
- 財務緒表　　　　　　　　　　　　　企業の懐具合を示す。今の財務体質と損益状況を確認できる
- 貸借対照表　　　　　　　　　　　　資産、負債、純資産（資本）を集計したもの。バランスシートとも呼ばれる
- 損益計算書　　　　　　　　　　　　費用と収益を集計することで、会計期間における利益や損失を明らかにしたもの。ピーエル（P/L）とも呼ばれる
- 総資本利益率（ROA: Return On Assets）
- ROA＝当期純利益÷総資本✖️１００
- 自己資本利益率（ROE＝Return On Equity）
- ROE=当期純利益÷自己資本✖️１００
-