# 100 Days Of Code - Log - 学習ログ
### Day 1: 2020/06/23 0:00 + 1:00 = 1:00

**Today's Progress**:
- Adjusted handler functions in spellselection so that the selection candidates generated can easily be handed off to the curses player creation module for display and input/processing.
- Created new function in curses player creation module to display and process the selection candidates.
- Testing and debugging

**今日の進捗**:
- spellsectionモジュール内の選択候補生成関数の調整・・・これでcursesモジュールにデータを簡単に渡せるはず。
- cursesのplayer creationモジュールにspell選択の表示・入力を処理する関数の基本作成。
- テスト・デバッグ諸々

**Thoughts:**
Working in curses can be a mess sometime since it seems quite low-level and requires very explicit commands. Still making some mistakes, but I seem to be getting faster, proof I am progressing. Also, looking at similar code I wrote a week ago is a really good reference, but it would be even better if the code is easier to read. Must allocate time to revisit, organize, and beautify the code.

**思ったこと**
cursesはかなり低レベルのモジュールなので、何もかも明確に書く必要があるんだ。ちょこちょこミスもあるが、気づくのがだんだん早くなってくる・・・底力が付いてきた証拠。１週間前に書いたコードを見ると非常にいい参考になるが、やはりコードは読みづらい。コードをレビュー、整理、リファクタリングする時間も取らねば。

### Day 2: 2020/06/24 1:00 + 1:15 = 2:15

**Today's Progress**:
- Spell selection confirmation/finalization/application to player object
- Debugging

**今日の進捗**:
- spell選択の確認画面のUI仕上げ・・・playerオブジェクトへの反映など
- デバッグ諸々

**Thoughts:**
An hour goes by faster than I thought... need to refactor the code, but for now it is passing.

**思ったこと**
思ったより１時間ってあっという間に終わる。コードのリファクタリング後回しにしておくけど、一通り最初から最後まで動いたのでよかった。

### Day 3: 2020/06/25 2:15 + 2:06 = 4:21

**Today's Progress**:
- Finished player creation main functions
- Started studying urwid

**今日の進捗**:
- player作成のメイン関数仕上げ
- urwidの勉強始めた

**Thoughts:**
Looks like if I use urwid I will be able to write a lot more quicker without having to reinvent the wheel curses. Going to invest in some time now to learn urwid, probably take the next few days until I am comfortable.

**思ったこと**
cursesだとかなり低レベルまで何もかも自分で書かないといけないので、urwidの方が楽にいろいろなやりたいことが書けそう。今時間を投資すれば、絶対回収できる。urwid使いこなせるには数日間かかりそうだが、これから頑張ろう。

### Day 4: 2020/06/26 4:21 + 1:13 = 5:34

**Today's Progress**:
- mompy code cleanup
- urwid studying continued

**今日の進捗**:
- mompy コードクレンジング
- urwidの勉強の続き

**Thoughts:**
Still trying to disect and understand all the structure of of urwid's more advanced functions. Have time this weekend to go in deep.

**思ったこと**
urwidの高度な機能をまだ完全に理解できていないが少しずつ分解してみて、調整してみるとだんだんわかってきそう。週末はたっぷり時間があるので、勉強続ける。

### Day 5: 2020/06/27 5:34 + 1:54 = 7:28

**Today's Progress**:
- urwid & mompy - dynamically created created book selection interface including validation
- created child classes to modify the standard object and give it extra abilities

**今日の進捗**:
- urwid & mompy - ブック選択インタフェイスと検証機能を動的に作るようにできた
- 標準オブジェクトの子クラスを作り、いろいろな機能を追加

**Thoughts:**
Gained insight into how urwid is working. It's much more robust and versatile than curses.

**思ったこと**
urwidの大まかな動きを理解できるようになった。cursesよりも丈夫で使い勝手が良い。

### Day 6: 2020/06/28 7:28 + 1:00 = 8:28

**Today's Progress**:
- urwid & mompy - check box and retort objects created

**今日の進捗**:
- urwid & mompy - チェックボックスとretortオブジェクト作成

**Thoughts:**
Good refresh on what I did yesterday, coding everyday is very helpful and I spend a lot less time trying to relearn things.

**思ったこと**
昨日の勉強の良い復習。毎日コーディングすると便利、やはり忘れたことを再び覚える時間がかなり減った

### Day 7: 2020/06/29 8:28 + 1:01 = 9:29

**Today's Progress**:
- player creation retort verification logic - still in progress
- experimenting with horizontal menu interfaces in urwid

**今日の進捗**:
- player作成のretort検証ロジック・・・まだ途中
- urwid: 横に広がるメニュのUIの実験

**Thoughts:**
Had to get up early for work today and was tired... didn't get in too much quality coding time.

**思ったこと**
仕事で早起きしたため、疲れすぎてそれほど良いコーディングできていない。

### Day 8: 2020/06/30 9:29 + 1:26 = 10:55

**Today's Progress**:
- more encapsulation - additonal layers of menu and submenus created
- screen changing for each part of the creation process

**今日の進捗**:
- カプセル化、メニューと入れ子のサブメニュー画面作成
- 作成過程での画面遷移対応できた

**Thoughts:**
Trying to apply unit test and functional test principles... still hard sometimes.

**思ったこと**
ユニットテストと機能テストの考え方をもって作業するといろいろメリットありますが、少し難しいですね。

### Day 9: 2020/07/01 10:55 + 1:00 = 11:55

**Today's Progress**:
- Messy first running program from start to end
- Start on cleaning up code

**今日の進捗**:
- 汚いけど最初から最後まで実行できるプログラム
- コードのクレンジング作業開始

**Thoughts:**
I think I code best in the morning... feel bad about taking time to organize my code instead of writing new functions, but I need to tell myself not to think this way and hone my practice.

**思ったこと**
朝の方が調子がいい。新しい機能を追加するよりも、時間かけて自分が書いたコードを磨くために時間を費やすのは罪悪感を感じるが、悪いことではなく、研鑽だと思えばやってよい。

### Day 10: 2020/07/02 11:55 + 1:35 = 13:30

**Today's Progress**:
- Cleaning up creation program, finding bugs and squashing

**今日の進捗**:
- プレイヤー作成プログラムの修正、バッグ炙り出し、撲滅

**Thoughts:**
Always work from large to small when planning the overall structure!

**思ったこと**
全体構造を考える時、必ず「大→小」の順に進めるとよい。

### Day 11: 2020/07/03 13:30 + 1:16 = 14:46

**Today's Progress**:
- Finished main creation program, cleaning up

**今日の進捗**:
- 作成プログラム完成、コード改良

**Thoughts:**
Objects are your friend!

**思ったこと**
迷ったら、オブジェクト使いましょう

### Day 12: 2020/07/04 14:46 + 1:09 = 15:55

**Today's Progress**:
- Trying to figure out overlays for a help menu

**今日の進捗**:
- ヘルプメニュー表示に必要なoverlayの勉強

**Thoughts:**
Getting confused by this API... need to do some modeling in an new experimental program.

**思ったこと**
このAPIでわからないことまだまだたくさんある。別の単独実験プログラムでいろいろと試すと良さそう。

### Day 13: 2020/07/05 15:55 + 1:04 = 16:59

**Today's Progress**:
- Fixed some nasty bugs and found more.

**今日の進捗**:
- 根深いバッグを見つけ修正。さらにバッグ発見。

**Thoughts:**
Getting confused by this API... need to do some modeling in an new experimental program.

**思ったこと**
このAPIでわからないことまだまだたくさんある。別の単独実験プログラムでいろいろと試すと良さそう。

### Day 14: 2020/07/06 16:59 + 1:08 = 18:07

**Today's Progress**:
- Added new game creation menu

**今日の進捗**:
- 新規ゲーム作成メニュー追加

**Thoughts:**
After spending a week in urwid I am much more comfortable now.

**思ったこと**
一週間もurwid触ったらだいぶわかるようになってきた気がする

### Day 15: 2020/07/07 18:07 + 1:07 = 19:14

**Today's Progress**:
- Error proofing inputs and exit conditions

**今日の進捗**:
- 各種入力や終了条件のエラー対策・修正

**Thoughts:**
Need to take some time to plan my next actions.

**思ったこと**
次どんな課題に取り組むか計画立てる時間が必要。

### Day 16: 2020/07/08 19:14 + 1:07 = 20:21

**Today's Progress**:
- Figuring out how to use GridFlow in urwid for map display

**今日の進捗**:
- urwidのGridFlowを使った地図の表示の勉強

**Thoughts:**
GridFlow's ability to resize is definitely not what I want here. Need to find a balance between control and flexibility. Probably need to carefully specify and control each row and column.

**思ったこと**
GridFlowのリサイズ機能（レスポンシブ仕様）はやはり使いたくないということがよくわかった。コントロールと柔軟性とのバランスが必要。各行と列の長さを強制的に指定して対応するしかないのでは？

### Day 17: 2020/07/09 20:21 + 1:01 = 21:22

**Today's Progress**:
- Creation of main map game screen

**今日の進捗**:
- メインゲームのマップ画面作成

**Thoughts:**
Need to figure out how to control spacing. I think the map will be a huge matrix of MapTile class objects I will create.

**思ったこと**
余白などのスペースの制御がまだ上手にできない。マップはMapTileというカスタムクラスのオブジェクトを集めたマトリックスになるのではないか。

### Day 18: 2020/07/10 21:22 + 1:02 = 22:24

**Today's Progress**:
- Slack bot programming
- Various module code cleanup

**今日の進捗**:
- Slack用のボットのプログラム作成開始
- 別のモジュールのコード見直し

**Thoughts:**
It's good to try a few small things on the side and take a break. Also set time to revisit your own bad code.

**思ったこと**
大きなプロジェクト進めている最中、たまに別の小さいプロジェクトをするといい刺激になるし、休憩も大事だね。あと、しばらく見ていない昔書いたコードを見直す時間も大事。

### Day 19: 2020/07/11 22:24 + 1:15 = 23:39

**Today's Progress**:
- Started creating a city management screen

**今日の進捗**:
- 都市管理画面の作成開始

**Thoughts:**
Will need to change the old functions I wrote that have a lot of direct terminal interface.

**思ったこと**
前に作った関数はターミナルで直接制御するものだったので、改修が必要になりそう。

### Day 20: 2020/07/12 23:39 + 1:17 = 24:56

**Today's Progress**:
- Building selection screen started

**今日の進捗**:
- 建築物選択画面に着手

**Thoughts:**
It's important for me to struggle with urwid some more, though I am definitely understanding a lot more now.

**思ったこと**
urwidとまた同じミスしたり、どこ理解できているかに気付きがえられるので、とても大事だな。

### Day 21: 2020/07/13 24:56 + 1:27  = 26:23

**Today's Progress**:
- Encapsulated city and building screen into one application object

**今日の進捗**:
- 都市と建物の各画面を一つのアプリケーションオブジェクトに統合

**Thoughts:**
Not sure on how to handle connect signals now...

**思ったこと**
この場合、connect_signalの使い方はどうなるか？

### Day 22: 2020/07/14 26:23 + 1:01  = 27:24

**Today's Progress**:
- City screen now updates per turn!!!

**今日の進捗**:
- ターン毎に都市画面が更新されます！

**Thoughts:**
Also made some minor aesthetic changes. Need to update twice, so I want to create a separate function to generate the main screen content and call that function by the create and update functions.

**思ったこと**
その他細かいビジュアル改善も。２つの似ている関数があるため、二重メンテがよろしくない。次は表示コンテンツを用意する関数一つを作り、作成と更新の関数から呼び出すように変えよう。

### Day 23: 2020/07/15 27:24 + 1:02  = 28:26

**Today's Progress**:
- Refactoring of city and building module code
- Testing out how to make a tile and grid for worldmap

**今日の進捗**:
- city及buildingモジュールのリファクタリング
- ワールドマップ用のタイルやグリッドの実験

**Thoughts:**
Still going to take a lot of time before I figure out how to pull off this world map.

**思ったこと**
ワールドマップの実現はまだまだ程遠いな。

### Day 24: 2020/07/16 28:26 + 1:11  = 29:37

**Today's Progress**:
- Developed building classes, now all buildings have race data

**今日の進捗**:
- buildingのクラス構築。すべてのbuildingは種族データ格納。

**Thoughts:**
- building and modeling the complexity of the game takes just as much as the normal coding. I enjoy it thought.

**思ったこと**


### Day 25: 2020/07/17 29:37 + 1:15  = 30:52

**Today's Progress**:
- Changed building requirements from strings to dynamic classes.
- Added building descriptions (some)

**今日の進捗**:
- buildingクラスの建設条件を文字列から別のクラスに変更。
- 一部のbuildingクラスに補足説明文を追加

**Thoughts:**
Beginning to see how to organize very more complicated programs and get defensive.

**思ったこと**
たくさんのオブジェクトの整理や運用法にだんだん慣れてきた気がする。

### Day 26: 2020/07/18 30:52 + 2:03  = 32:55

**Today's Progress**:
- Cleaning up unit module race data, class refactoring, updating city/building/unit functions
- City class can now generate available unit classes

**今日の進捗**:
- unitモジュールとの種族データ整理、クラスリファクタリング、city/building/unitの関数更新
- cityクラスは作成可能なクラスのリストを表示できるようになった

**Thoughts:**
Like the weekends with extra time for coding and allows me to tackle larger tasks.

**思ったこと**
週末は時間たっぷりあるので、平日だとできない大きなタスクに取り掛かることもできる。

### Day 27: 2020/07/19 32:55 + 2:09  = 35:04

**Today's Progress**:
- Fixing bugs from refactoring, making sure things work again
- Cleaned up city module and renaming variables and methods (PEP8 compliant)

**今日の進捗**:
- リファクタリングのバッグ潰し、正常に機能しているように調整
- cityモジュールのクレンジング。変数やメソッドの名称変更（PEP8準拠）

**Thoughts:**
- Taking time to organize things relieves stress

**思ったこと**
- コードレビューなどに時間を使うとあとでそのコードを見るとストレスが減りますね。

### Day 28: 2020/07/20 35:04 + 1:15  = 36:19

**Today's Progress**:
- Worked on scrollable grid for world map interface

**今日の進捗**:
- スクロール可能なワールドマップの開発

**Thoughts:**
- Probably need to finish on the weekend when I have more time.

**思ったこと**
- 何日もかかる必要なので、時間がある週末とかにまとめて開発続けよう。

### Day 28: 2020/07/21 36:19 + 1:17  = 37:36

**Today's Progress**:
- Fixed city screen to properly handle building class updates
- Added starting city generation functions

**今日の進捗**:
- city画面でのbuildingクラスの変更が処理できるようになった
- 最初のcityの生成関数など

**Thoughts:**
- Due to the complex nature of the project I usually need to update multiple modules everytime I make a change. I realize how important it is to break things up into small manageable chunks.

**思ったこと**
- このプロジェクトがとても複雑なせいで、変更がある度に複数のモジュールに手を入れないといけない。毎日の作業を少しずつ管理できる範囲に絞り、計画的に進めることの大切さを感じね。

### Day 29: 2020/07/22 37:36 + 1:05  = 38:41

**Today's Progress**:
- Refactoring and cleanup
- Fixed building selling price data and functions

**今日の進捗**:
- リファクタリング・整理
- 建物の売買価格計算修正

**Thoughts:**
- Don't feel as scared about being bold in improving my code.

**思ったこと**
- コード改善が目的であれば、大胆な修正は惜しまない。

### Day 30: 2020/07/23 38:41 + 1:01  = 39:42

**Today's Progress**:
- Production selection screen improved

**今日の進捗**:
- 生産選択画面の改善

**Thoughts:**
- Small UI improvements and creature comforts are worth the time to add.

**思ったこと**
- どんなに小さな改善であっても、子持ちよくなるのであればどんどん進め。

### Day 31: 2020/07/24 39:42 + 2:03  = 41:45

**Today's Progress**:
- Production related functions cleaned up and improved

**今日の進捗**:
- 生産関係の関数の修正・改善

**Thoughts:**
- Feeling like I got better at identifying many areas of improvement.

**思ったこと**
- たくさんの改善点を見つけるのも上手になってきた気がする。

### Day 32: 2020/07/25 41:45 + 1:05  = 42:50

**Today's Progress**:
- Notifications support added
- City Enchantment support added

**今日の進捗**:
- 通知対
- CityのEnchantment対応

**Thoughts:**
- Noticed my code is starting to look more Pythonic.

**思ったこと**
- 自分が書くコードがよりPythonicになってきていることに気がづいた。

### Day 33: 2020/07/26 42:50 + 1:00  = 43:50

**Today's Progress**:
- Added production completion popup

**今日の進捗**:
- 生産完了画面

**Thoughts:**
- Feels good to add something you have been wanting to do for some time.

**思ったこと**
- しばらく前からやろうと思っていたことを実現できると気持ちいいね。