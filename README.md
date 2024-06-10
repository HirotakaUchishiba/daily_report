## なぜやろうと思ったのか？
> スクラム開発は、アジャイル開発の中でも特に短い期間で開発工程を区切って進めます。この短い開発期間を「スプリント」と呼び、１週間から４週間単位で組まれることが多いです。
> このように各工程を短く区切り調整を行うことで、工数の見積もりを正確に行える上、問題も早期発見できます。また、必要な機能から順番に開発を進めるため、失敗も少なくなるでしょう。

これを自分の普段の生活に転用すれば以下のようなメリットが得られるんじゃないかと思ったから
```
・長期的な目標を達成するための中期的な目標や短期的な目標を設定できる
・自分が目標に対して今どの位置にいるかを把握できる
・シンプルに習慣にできるしこの作業自体がPDCAサイクルを回すことにつながる
・毎日つづけてればBeReal的な義務感が出てくる（はず）
```

## それぞれの単位ごとの詳細
### ・全体目標
**キャリア全体を通した目標（漠然としててもいいからとりあえず書く）**

### ・年間目標
**全体目標の達成のために1年でどれだけのことをするか年間を通した目標**

### ・月間目標
**年間目標の達成のために1ヶ月でどれだけのことをするか月間を通した目標**

### ・週間目標
**月間目標の達成のために1週間でどれだけのことをするか週間を通した目標**

### ・月次レポート
**年間目標達成にために1ヶ月で何を行うか**
```
・1ヶ月でやること
・1ヶ月でできたこと
```

### ・週次レポート
**月間目標達成にために1週間で何を行うか**
```
・1週間でやること
・1週間でできたこと
```

### ・日次レポート
**週間目標達成にために1日で何を行うか**
```
・1日でやること
・1日でできたこと
```


## 日次レポート
## 2024/06/01
  - 今日やったこと
    - SpeakBuddy
    - マスタリングTCP/IP
    - freee技術の日

## 2024/06/02
  - 今日やったこと
    - SpeakBuddy
    - LitLink内容更新
    - マスタリングTCP/IP
    - 副業
    - 個人開発

## 2024/06/03
  - 今日やったこと
    - SpeakBuddy
    - マスタリングTCP/IP
    - AWS Startup Loftに行く
    - freeCodeCamp.orgでGoの動画をみる
    - 副業

## 2024/06/04
  - 今日やること
    - Recursion
    - SpeakBuddy
    - 読書(マスタリングTCP/IP)
    - freeCodeCamp.orgでGoの動画をみる
    - 本業(Kotlin)
    - 副業(Flutter)

  - 今日やったこと
    - SpeakBuddy
    - freeCodeCamp.orgでGoの動画をみる
    - 本業(Kotlin)
    - 副業(Flutter)

## 2024/06/05
  - 今日やること
    - Recursion
    - SpeakBuddy
    - 本業(Kotlin)
    - 副業(Flutter)

  - 今日やったこと
    - Recursion
    - SpeakBuddy
    - 本業(Kotlin)
    - 副業(Flutter)

  ## 2024/06/06
  - 今日やること
    - Recursion
    - SpeakBuddy
    - 本業(Kotlin)
    - 副業(Flutter)

  ## 2024/06/07
  - 今日やったこと
    - 8:30-9:30 CaTe
    - 9:30-18:30 dip
    - 19:00-21:30 Lint night

    - 具体的に何をしたか?
    - 日次記録を行うRepositoryを一つに統合
    →設計を1クラス1メソッドに方針変更したため

    - riverpod generatorを使わず代用として~/usecaseファイルを作成し、ここに定義したProviderを使用するように変更
    →riverpod generatorはコードジャンプができず見づらいため

    - 既存api仕様書に基づき新システム側でどのapiが使われているかを画面ごとに洗い出す
    →旧アプリから新アプリへの移行につき既存のapiを使いまわしたかったため(エクセルファイルで管理されてて結構見づらかった...)

    - charlesの導入
    →画面ごとにapiレスポンスを確認してどのapiレスポンスが帰ってきているかを判別したかったため

    - Lint関連のツールの勉強会に参加
    →そもそもLintというもの自体知らなかった自分には結構きつかったけど参加者の方と仲良くなれたのでよかった、次はちゃんと使えるようになった状態で勉強会に参加したい。

  ## 2024/06/08
  - 今日やること
    - 9:00-10:00 SpeakBuddy
    - 13:00-17:00 HarbarS もくもく会
    - 18:40-22:00 English Only Cafe

    - 具体的に何をしたか?
    - DioErrorHandlingMixinを削除し、既存のエラーハンドラーを使用してハンドリングするよう変更
      - 専用のエラーハンドラークラスを使用することで、エラーハンドリングロジックを一箇所に集約できるから（？）
    - DailyMeasurementRecordApiクライアントをProviderから注入するように変更
      - 共通化されたAPIクライアントを使用することで各関数に直接定義しなくても使えたり、他の関数が作られた時にも流用がしやすいから。
    - 英語初心者向けのイベントに行ってきた
      - 前は初心者向けではないイベントに行ってきたけど自分以外がほぼネイティブレベルだったため今回は初心者向けにした。こっちは英語話者に日本語でこれはどういう言い方をするのかなど積極的に聞きにいける環境だったからこっちメインで今後は参加してみる。

  - 今日やったこと
    - 10:00-10:00 SpeakBuddy
    - 13:00-18:00 個人開発
    - 18:30-22:00 Amigo international friendship

  - 今日やったこと
    - 7:30-8:00 SpeakBuddy
    - 8:00-9:30 朝の支度,出社
    - 9:30-18:30 dip
    - 18:30-20:00 帰宅,晩ご飯
    - 20:00-21:00 モロさんmtg
    - 21:00-0:00 CA理キャリア採用ES,職務経歴書作成