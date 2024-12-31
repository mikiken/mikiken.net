# 2024年を雑に振り返る


去年と同様、今年何をしてたかをざっくり振り返ります。

{{<cardlink url="https://mikiken.net/posts/2023-looking-back">}}

### 1月
- 研究室に(仮)配属されてゼミ発表の準備に気を取られていたら、某授業の成績に占めるウエイトの大きい課題を吹き飛ばして絶望するなどしていた
(試験頑張ってなんとか単位は確保した)
{{<tweet 1747991512913457223>}}

- 学校の実験で、ライフゲームをマトリクスLEDに表示する謎デバイスを作っていた
{{<cardlink url="https://mikiken.net/posts/lifegame-indicator/">}}
{{<tweet 1751962073792491877>}}
    - アホの量の配線と格闘していた模様
    {{<tweet 1749824107099926614>}}

- オシロスコープを買った
{{<tweet 1752551791785656798>}}

### 2月
- [RISC-V CPU自作本](https://amzn.asia/d/605m5tg)をやったりしていた
    - パイプラインの実装までやって、Tang Primerという中華FPGAへの実装を試みたところ論理合成がうまくいかなかった様子
    {{<tweet 1760695711308644759>}}

### 3月
- 情報科学若手の会 春の陣に参加していた
    - 何も発表できず…
    {{<tweet 1764134676657291395>}}
- MLIRに入門し(ようとしてい)た
    {{<cardlink url="https://github.com/mikiken/mlir-toy-tutorial">}}
    - MLIRはLLVM Projectの一部として開発が行われているプロジェクトで、中間表現(IR:Intermediate Representation)を定義したり、
    IR間の変換等を実装するためのフレームワークのようなもの
    - 公式でTutorialが用意されているので、それをやっていた
    - LLVMをビルドするためにCMakeを使う必要があるが、`CMakeLists.txt`の書き方が分からず、エラーと格闘しながら2-3週間溶かしていた気がする
    - 放置しているので時間を見つけて続きをやりたい

### 4月
- 年度が変わり、研究室に正式に配属された
- 研究室の発表2回目

このあたりから生活に占める研究のウエイトが大きくなり、趣味開発にあまり時間を割けなくなっている

### 5月
- 研究室で六甲縦走のコースの一部を実際に歩いてみる謎イベントが開催されたので参加した
- **ベル麻痺を発症し、顔の左半分の筋肉が動かなくなった**
    - **個人的に今年で一番影響が大きかった**
    - 日常生活がままならないうえに、精神的ダメージもそこそこデカかった
{{<tweet 1790197528010559562>}}
{{<cardlink url="https://mikiken.net/posts/bell-palsy/">}}

### 6月
- 研究室の発表3回目
    - ~~このあたりから研究の方向性が迷走し始めている(?)~~
    - 実装にRustを使うことにしたので、Rustに入門していた
{{<tweet 1805288845086441974>}}
- 顔ぶっ壊れて精神が割と死んでたので、研究サボってKiCadで基板引いて遊んだりしていた
- 院試が近づいてきたので、複素関数論とか常微分方程式とかをn年振りに思い出していた

### 7月
- 院試勉強の記憶しかない
    - 電気回路とか電子回路とか情報理論などをn年振りに思い出していた

### 8月
- 院試勉強の記憶しかない2
- 院試を受けた(8/22, 8/23)

### 9月
- 院試に一応受かっていた
    - 院から所属研究室が変わることになった
        - 機械学習系の研究室
        - 個人的には、今の所属研究室と2択で悩んだ研究室へ配属されることになったので割と嬉しい
    {{<tweet 1832049185119780903>}}

- 第57回 情報科学若手の会に参加した
    - 幹事としては初の参加
    - ~~直後に研究室の発表が控えていたので、夜中4時前くらいまでその原稿を書いたりしていて、ヘロヘロになっていた~~
    {{<tweet 1835639691565228530>}}

- 研究室の発表4回目

- 第2種電気工事士の筆記試験を受けた
{{<tweet 1840601123687903483>}}

### 10月
- 千葉県浦安市の某テーマパークに初めて行った

- ヤフオクで買ったジャンクのLet's noteの基板にProxmoxを入れて遊んでいた
{{<cardlink url="https://zenn.dev/mikiken/articles/proxmox-introduction">}}
{{<tweet 1845437257039348154>}}

### 11月
- [CAMPHOR-](https://camph.net)でSYCLにデータ並列プログラミング入門するイベントに参加した
{{<cardlink url="https://camphor.connpass.com/event/329392/">}}

- 研究室の中間発表が近づいているにも関わらず実装のコードがバグり散らかしていて、進捗が生まれず焦りを感じていた
{{<tweet 1851482027574640953>}}

- 電気工事士の実技試験の練習をしていた
{{<tweet 1858168725494730766>}}

### 12月
- 電気工事士の実技試験を受けた(12/14)

- CAMPHOR- でPFNのMN-Coreの話を聞けるイベントに参加した
{{<cardlink url="https://camphor.connpass.com/event/337837/">}}
{{<tweet 1867849812051431616>}}

- 研究室の中間発表

- ブラックフライデーセールで3Dプリンタを買った
{{<tweet 1870461472750657787>}}
{{<tweet 1870463232051388818>}}

- 卒論を書き始めた(現在進行系)
{{<tweet 1872704120190316976>}}

### 昨年の目標を見返す
昨年の記事で書いていた目標を見てみると、以下の内容を書いていたっぽい。
{{<cardlink url="https://mikiken.net/posts/2023-looking-back">}}
- 自作CPU
    - FPGAへの実装は未完だが、一応達成している
    - 本の写経メインだったことに加え、Chiselで実装したので、あまり頭に残ってない
    - System VerilogかVerylあたりでもう一回やってみたい
- KiCadで基板作ってみたい
    - 自作キーボードの基板を設計したりした
    - 設計の途中まではやった
    - 完成させて、業者に発注するところがまだ
- SecHackとか未踏とか、規模大きめのプログラムを長期で作るやつをやってみたい
    - これは全然できてない
    - やってみたいアイデアは一応あるので、なんとか企画書に書いて出したいところ
- 院試に通る
    - これは完全に達成している

### 感想
今年は、体調を大きく崩したり、院試があったり、生活に占める研究のウエイトが大きくなったりで、目の前のことをこなすだけで割と精一杯だった感じがある。
来年は心身の体調に気をつけつつ、最低限+αの活動もやっていきたい。

### 来年何をしたいか
今パッと思いついたことを書き連ねておくと、

- 心身の健康を保つ
- 未踏に応募したい
- 機械学習の研究動向をある程度キャッチアップしたい
    - 来年配属予定の研究室が機械学習系なので
- 情報科学若手の会で登壇したい
- 趣味開発にもう少し時間を割けるようにしたい
- 就活に向け、インターンに積極的に参加していきたい

あたりかなぁ。（適宜更新するかも）