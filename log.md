# 100 Days Of Code - Log
# 100 Days Of Code - 学習ログ

### Day 1: 2020/06/23
### 1日目: 2020年6月23日

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