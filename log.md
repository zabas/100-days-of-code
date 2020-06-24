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