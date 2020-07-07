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
